# GUtilities
Reaper DAW Plugin/Extension that provides tools created for editors and sound designers. 

At present, currently supports Win x64 and x86 platforms.

The Reaper Forum post can be found here <https://forum.cockos.com/showthread.php?t=273060>

Current Tools:
- Item Length Adjuster (relative to snap offset)
- Item Fader
- Item Renamer
- Batch Importer
- Sourve Validator

GUtilities is installed via [ReaPack](https://reapack.com/ "https://reapack.com/"), a package manager for Reaper. If you're unfamiliar with ReaPack, you can find a brief guide [here](https://reapack.com/user-guide "https://reapack.com/user-guide") which explains installation and usage.

To install this extension, paste the link below into ReaPack → Import repositories. Installation of new extensions will require restarting Reaper.
> https://raw.githubusercontent.com/gu-on/GUtilities/main/index.xml

GUtilities relies on [ReaImGui](https://forum.cockos.com/showthread.php?t=250419 "https://forum.cockos.com/showthread.php?t=250419"), which is also installed via ReaPack. Ensure that ReaTeam Extensions/ReaImGui is installed before attempting to use GUtilities. 

If you don't see "GUtilities" in the Extensions toolbar or Actions List after following the above, you may need to install the latest vc redistributables <https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170>
