# RDTweaks
*A [BepInEx](https://github.com/BepInEx/BepInEx) plugin which contains a collection of tweaks for RD.*


## Features
- too
- lazy
- to 
- do tihs
- rn

## TODO
- make startup tweaks better
- maybe randomizer animation? kinda hard tho
- CLS folders?

## Installation
1. Download the latest version of BepInEx 5 **x86** [here](https://github.com/BepInEx/BepInEx/releases).
2. Unzip the file into your RD folder. You should have a `winhttp.dll`, `doorstop_config.ini`, and `BepInEx` folder next to Rhythm Doctor.exe.
3. Launch RD once to generate BepInEx files.
4. Download the latest version of the mod from [here](https://github.com/huantianad/RDTweaks/releases).
5. Put the mod into the `BepInEx/Plugins` folder.
6. Launch the game, and configure the mod in `BepInEx/Config`.

For more information, check out the [BepInEx installation guide](https://docs.bepinex.dev/articles/user_guide/installation/index.html).

## Development
In order to build the game dll, you need some external dlls to compile it, not included for copyright purposes.\
Get these files from the Rhythm Doctor and BepInEx installation, and put it in a Libs folder, then add all the dlls as references.\
- `BepInEx/core`
  - `0Harmony.dll`
  - `BepInEx.dll`
  - `BepInEx.Harmony.dll`
- `Rhythm Doctor_Data/Managed/`
  - `Assembly-CSharp.dll`
  - `UnityEngine.AudioModule.dll`
  - `UnityEngine.CoreModule.dll`
  - `UnityEngine.dll`
  - `UnityEngine.InputLegacyModule.dll`
  - `UnityEngine.UI.dll`


For more information, check out the [BepInEx plugin creation guide](https://docs.bepinex.dev/articles/dev_guide/plugin_tutorial/index.html).
