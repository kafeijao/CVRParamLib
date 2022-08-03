# CVRParamLib
A Library for interacting with ChilloutVR's Animator Parameters

## Checklist

- [X] MelonLoader Support
- [X] BepInEx Support
- [X] ParameterSDK
  + Interaction with CVR Animator Parameters via. a Mod/Plugin
- [ ] Config
  - [ ] Enable OSC
  - [ ] OSC Port
- [ ] OSC
  - [X] `/avatar/parameter` Address
  - [ ] `/avatar/change` Address
  - [ ] `/settings/cvrpl` Address
    + Ability to change config via. OSC
  - [ ] `/input` Address

## Installing

This guide is split into two loaders, please follow the guide for which mod loader you use.

### MelonLoader

1. Install [MelonLoader](https://github.com/LavaGang/MelonLoader)
2. Download `CVRParamLib.MelonLoader.dll`
3. Place the dll at `[ChilloutVR]\Mods`

### BepInEx

1. Install [BepInEx](https://github.com/BepInEx/BepInEx)
    + You may need to run the game once for all required directories to appear
2. Download `CVRParamLib.BepInEx.dll`
3. Place the dll at `[ChilloutVR]/BepInEx/plugins`

> ___
> ### ⚠️ **Notice!**
> 
> This mod developer(s) and the mod itself, along with the respective mod loaders, have no affiliation with ABI and are not supported by ABI!
> ___
