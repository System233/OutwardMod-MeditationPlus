# MeditationPlus

Enables players to sit and recover status, with support for local split-screen and controllers.

[English](./README.md), [中文](./README.CN.md)

## Usage

Hold the “sheath weapon” key to sit—no extra key bindings required, and it won’t interfere with existing actions.

* Default for keyboard: **Z**
* Default for controllers: **D-Pad Down**
* Key bindings can be customized in the settings menu.

## Build

1. Create a symbolic link from the game’s **Managed** directory to this repository.
2. Install the .NET SDK.
3. Run the following commands:

```sh
dotnet nuget add source https://nuget.bepinex.dev/v3/index.json -n BepInEx
dotnet build -c Release
```

The compiled output will be located at:
`bin\Release\net472\MeditationPlus.dll`

## Credits
Thanks to SavanticIO’s [Meditation](https://github.com/SavanticIO/OutwardMods/tree/master/Meditation) mod, which served as the foundation for this improved version.


## LICENSE

[MIT LICENSE](./LICENSE)
