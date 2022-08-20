 <p align="center">
<img src="./program_info/dabmc-header-black.png#gh-light-mode-only" alt="DabMC logo" width="50%"/>
<img src="./program_info/dabmc-header.png#gh-dark-mode-only" alt="DabMC logo" width="50%"/>
</p>

DISCLAIMER! This fork is not PolyMC and is not endorsed by or affiliated with the PolyMC project (https://polymc.org).
Do not complain to PolyMC about any issues you encounter while using this fork. Don't complain to me either.


DabMC is a custom launcher for Minecraft that focuses on predictability, long term stability, simplicity, and Yarg.

This is a **fork** of the PolyMC Launcher and not endorsed by PolyMC.
If you want to read about why this fork was created, check out https://www.minecraft.net/en-us/article/addressing-player-chat-reporting-tool.
<br>


# Development

I don't want help.

## Building

If you want to build DabMC yourself, check [Build Instructions](https://polymc.org/wiki/development/build-instructions/) for build instructions.
Just clone this repo instead of PolyMC's

## Forking/Redistributing/Custom builds policy

We don't care what you do with your fork/custom build as long as you follow the terms of the [license](LICENSE) (this is a legal responsibility), and if you made code changes rather than just packaging a custom build, please do the following as a basic courtesy:
- Make it clear that your fork is not PolyMC and is not endorsed by or affiliated with the PolyMC project (https://polymc.org).
- Go through [CMakeLists.txt](CMakeLists.txt) and change PolyMC's API keys to your own or set them to empty strings (`""`) to disable them (this way the program will still compile but the functionality requiring those keys will be disabled).

If you have any questions or want any clarification on the above conditions please make an issue and ask us.

Be aware that if you build this software without removing the provided API keys in [CMakeLists.txt](CMakeLists.txt) you are accepting the following terms and conditions:
 - [Microsoft Identity Platform Terms of Use](https://docs.microsoft.com/en-us/legal/microsoft-identity-platform/terms-of-use)
 - [CurseForge 3rd Party API Terms and Conditions](https://support.curseforge.com/en/support/solutions/articles/9000207405-curse-forge-3rd-party-api-terms-and-conditions)

If you do not agree with these terms and conditions, then remove the associated API keys from the [CMakeLists.txt](CMakeLists.txt) file by setting them to an empty string (`""`).

All launcher code is available under the GPL-3.0-only license.
  
The logo and related assets are under the CC BY-SA 4.0 license.

## Sponsors
Destroy All Bacteria (The DAB Server)

God (The good one)
