# Roblox Multi-Instance
Open this program to run multiple Roblox instances (on different accounts) on the same Windows device.

This code was made by MiningTcup and MainDabRblx but was compiled to and exe by CalvinCooler to make it easier to use.


**Download** [**Here**](https://github.com/CalvinCooler/Roblox-Multi-Instance/raw/main/MultiInstance.exe)

***

## Instructions
1. Download and open the file from above
2. Make sure to close all instances of Roblox
3. Press any key
4. You can now open as many Roblox instances as you want on the same device, granted they are on separate accounts.

***

## How it works
```c#
new Mutex(true, "ROBLOX_singletonMutex");
```
Basically, this line of code takes control of the part of Roblox that says "No multi-instance for you!" and disables it.

***
## Malware
I want to address any concerns about the legitimacy of this software. Roblox Multi-Instance is distributed under the MIT license, and I encourage users to review the source code and compile it themselves for assurance.


If you have any questions or concerns about Roblox Multi-Instance, feel free to contact me through appropriate channels. I appreciate your understanding and cooperation.
***
## More
Q. Why does my antivirus ding it?


A. Because it uses a mutex, which could be malicious.


Q. Will I get banned from Roblox?


A. Extremely unlikely, as this is not against Roblox ToS and the exploit is undetectable anyway. However, I cannot guarantee anything, and, as Roblox is banning alt accounts, try not to be too suspicious.
