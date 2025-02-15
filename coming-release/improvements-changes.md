# Amazon Lumberyard Release Notes: Known Issues in [VERSION NUMBER] ([MONTH OF RELEASE] [YEAR OF RELEASE])

Lumberyard Beta [VERSION NUMBER]] provides improvements and changes to Lumberyard systems and functionality.

**Topics**
+ [FEATURE 1](#anchor-link-here)
+ [FEATURE 2](#anchor-link-here)
+ [AWS Native SDK - Updated to 1.7.167](#anchor-link-here)
+ [Networking: simplyify your code using Network Context](#anchor-link-here)


## [FEATURE 1]

[FEATURE 1] has the following improvements and changes:
+ ...

## [FEATURE 2]

[FEATURE 2] has the following improvements and changes:
+ ...

## [AWS Native SDK version update]

AWS Native SDK version was updated to 1.7.167. 
**Note for Linux users:** If your project or a gem depends on AWS Native SDK on Linux (such as a Twitch gem) then debug/profile builds requires your Linux configuration to have libssl.so.1.1 and libcrypto.so.1.1 present on your system. Release builds link these libraries staticly. No changes are required for release Linux builds of Lumberyard.

## [Networking: Network Context]

[Networking: Network Context] has the following improvements and changes:
+ In Lumberyard, Network Context simplifies writing multiplayer components in C++. What can take 100 lines of code in raw GridMate implementation, Network Context accomplishes in less than a dozen lines with the interface.
+ Network Context is part of the context family, along with Serialize Context, Edit Context and Behavior Context. Network Context allows you to tag component member variables as network fields or remote procedure calls and use them in a simpler manner, compared to direct GridMate use.
+ <<link to the public doc on Network Context goes here>>
+ MultiplayerSample has been updated to use Network Context in multiple components, such as HealthBarComponent.
