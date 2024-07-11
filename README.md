
# Windows Emulation on Android!

 an Android application that lets you to run Windows (x86_64) applications with Wine and Box86/Box64. Originally modified from [Brunodev85](https://github.com/brunodev85/Winlator)



# Installation

1. Download and install the APK 
2. Launch the app and wait for the installation process to finish

----

[![Play on Youtube](https://img.youtube.com/vi/8PKhmT7B3Xo/1.jpg)](https://www.youtube.com/watch?v=8PKhmT7B3Xo)
[![Play on Youtube](https://img.youtube.com/vi/9E4wnKf2OsI/2.jpg)](https://www.youtube.com/watch?v=9E4wnKf2OsI)
[![Play on Youtube](https://img.youtube.com/vi/czEn4uT3Ja8/2.jpg)](https://www.youtube.com/watch?v=czEn4uT3Ja8)
[![Play on Youtube](https://img.youtube.com/vi/eD36nxfT_Z0/2.jpg)](https://www.youtube.com/watch?v=eD36nxfT_Z0)

----

# Useful Tips

- If you are experiencing performance issues, try changing the preset for Box86/Box64 in Container Settings -> Advanced Tab.
- For applications that use .NET Framework, try installing Wine Mono found in Start Menu -> System Tools.
- If some older games don't open, try adding the environment variable MESA_EXTENSION_MAX_YEAR=2003 in Container Settings -> Environment Variables.
- Try running the games using the shortcut on the Winlator home screen, there you can define individual settings for each game.
- If you want to hide the annoying dxvk hud, please removing this env from here
<p align="center">
	<img src="hide_dxvk_hud.png" width="480" height="240" alt="Winlator-Frost Hide DXVK HUD" />  
</p>

# System requirements
- `Turnip` - For `Adreno 6xx and 7xx` only at the moment. `Adreno 735, 732, 720, 710 and 613` are not working. You have to use VirGL if you're using this GPU
- `VirGL` - Universal, all GPU `like Mali, Exynos, Kirin, Unisoc, etc`(include unsupport GPU of turnip adreno like in above)` might work with VirGL but you can only play DX9 games
- `LLVMPIPE` - Use this if you want to run software apps `(not for game)`

# Known issues (TODO LIST)
- [ ] Snapdragon 8s gen 3 `Adreno​ 735` container not starting issue
- [ ] Snapdragon 8 gen 3 `Adreno 750` may not working/compatible with this mod
- [ ] Some game have a xinput issue which virtual gamepad are not working

# What is the difference between bench and without bench apk? 
- Bench is for the user that have 2 or more winlator. It's suitable for the user to compare other winlator. While, without bench is for the user that don't have/install any winlator yet.

# Like my mod? 
- Star This Repo!

# Want to Contribute?
- Open a Pull request!

# Credits and Third-party apps
- Ubuntu RootFs ([Focal Fossa](https://releases.ubuntu.com/focal))
- Wine ([winehq.org](https://www.winehq.org/))
- Box86/Box64 by [ptitseb](https://github.com/ptitSeb)
- PRoot ([proot-me.github.io](https://proot-me.github.io))
- Mesa3D (Turnip, Zink, VirGL) ([mesa3d.org](https://www.mesa3d.org))
- DXVK ([github.com/doitsujin/dxvk](https://github.com/doitsujin/dxvk))
- D8VK ([github.com/AlpyneDreams/d8vk](https://github.com/AlpyneDreams/d8vk))
- CNC DDraw ([github.com/FunkyFr3sh/cnc-ddraw](https://github.com/FunkyFr3sh/cnc-ddraw))
