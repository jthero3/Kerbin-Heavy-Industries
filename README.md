# Kerbin Heavy Industries

A modernization of Extraplanetary Launchpads for Kerbal Space Program.

EPL's construction mechanics are still solid, but its parts have aged. KHI keeps the EPL workflow intact and swaps the old parts out for the Keridian Dynamics part set - a cleaner, Restock-style look that fits alongside modern part mods.

## Current state

- EPL:
    - Construction mechanics, unchanged
    - Moved EPL Parts to `EPL_Legacy`
    - Fixed some pathing bugs in Craft loader
- Keridian Dynamics:
    - parts replacing the old EPL models
    - Cleaned up config structure, removing some bloat.
    - Removed all ARR and CC-BY-ND Files.
    - Removed support for Firespitter and IFS. B9PS is now required.

## Planned

- SimpleConstruction as a toggle, for a lighter build path
- NSSC as a toggle, for more in-depth chains.
- Fold in PRs and community config updates for KD/SC/NSSC.

## Dependencies

**Required**
- [ModuleManager](https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/)
- [B9PartSwitch](https://forum.kerbalspaceprogram.com/index.php?/topic/140541-*/)

KSP version: 1.12.5

## Supports

- [Community Tech Tree](https://forum.kerbalspaceprogram.com/index.php?/topic/90530-*/)
- [Community Resource Pack](http://forum.kerbalspaceprogram.com/index.php?/topic/83007-*/)
- [Connected Living Space](http://forum.kerbalspaceprogram.com/index.php?showtopic=192130-*/)

## Installation

**CKAN:** Coming soon!
<!-- **CKAN** (recommended): search for Kerbin Heavy Industries and install. Dependencies resolve automatically. -->

**Manual**: drop the `GameData/KerbinHeavyIndustries` folder into your KSP `GameData` directory. Make sure the dependencies above are installed too.

Do not run KHI alongside the standalone versions of the mods it replaces. Remove EPL, Keridian Dynamics, SimpleConstruction, and NSSC first.

## Building from source

Standard SDK-style project. You'll need the KSP managed assemblies referenced; point the build at your install as mentioned in the [KSPBuildTools wiki](https://github.com/KSPModdingLibs/KSPBuildTools/tree/main).

```
git submodule init
git submodule update
dotnet build
```

Versioning is handled by MinVer off git tags.

## License and credits

KHI is a consolidation, so it inherits the licenses of the mods it's built from. Authors are in chronological order (oldest -> latest).

- [Extraplanetary Launchpads](https://github.com/taniwha/Extraplanetary-Launchpads)
    - Author(s): 
        - [taniwha](https://github.com/taniwha)
        - [Greys0](https://github.com/Greys0) (Hexcans)
    - License:
        - Code/Parts: GPL
        - [HexCans](https://github.com/Greys0/HexCans): [CC-BY 3.0](https://creativecommons.org/licenses/by/3.0/)
- [Keridian Dynamics](https://github.com/zer0Kerbal/KeridianDynamics) 
    - Author(s):
        - [Eleusis La Arwall](https://forum.kerbalspaceprogram.com/index.php?/profile/116286-*/)
        - [zer0Kerbal](https://forum.kerbalspaceprogram.com/index.php?/profile/190933-*/)
    - License:
        - Parts/Configs: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
- [SimpleConstruction](https://github.com/zer0Kerbal/SimpleConstruction/)
    - Author(s):
        - [MatterBeam](http://forum.kerbalspaceprogram.com/index.php?/profile/133334-*/)
        - [RealGecko](https://forum.kerbalspaceprogram.com/index.php?/profile/162682-*/)
        - [EricWI](https://forum.kerbalspaceprogram.com/index.php?/profile/152716-*/)
        - [zer0Kerbal](https://forum.kerbalspaceprogram.com/index.php?/profile/190933-*/)
    - License:
        - Configs: [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0-standalone.html)
- [NSSC](https://github.com/zer0Kerbal/NotSoSimpleConstruction/)
    - Author(s):
        - [RealGecko](https://forum.kerbalspaceprogram.com/index.php?/profile/162682-*/)
        - [MrCarrot](https://forum.kerbalspaceprogram.com/index.php?/profile/176291-*/)
        - [zer0Kerbal](https://forum.kerbalspaceprogram.com/index.php?/profile/190933-*/)
    - License:
        - Configs: [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0-standalone.html)

## Issues

Bug reports and feature requests go on the tracker: [Issues Page](https://github.com/jthero3/Kerbin-Heavy-Industries/issues)