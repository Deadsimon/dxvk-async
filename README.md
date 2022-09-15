## dxvk-async for guild wars
A Fork of https://github.com/Sporif/dxvk-async for use with Guild wars 1

This fork contains Specific patches and configurations specific to Guild wars 1


##DXVK for Guild wars
DXVK for guild wars is a Translation wrapper for translating DirectX 9 to Vulkan, using a fork [https://github.com/Sporif/dxvk-async] of a fork [https://github.com/doitsujin/dxvk] with performance optimisations such as Asynchronous compute and Fast path algorithm.
This Boosts performance or lowers power consumption, while retain compatibility with other 3rd party tools and Operating systems such as Windows XP through windows 11 and Linux.

Compatible with:
* DSOAL-GW1
* Reshade
* GW toolbox
* GW Armory 
* GW Launcher (No uMod or TPF support)


## Instructions:

* 1. Copy d3d9.dll and DXGI.dll to your guild wars installation folder.
* 2. Copy DXVK.Conf and Gw.dxvk-cache to your guild wars folder.
* 3. (optional) find your Guildwars shortcut and right click, Properties. in the target field change "C:\Program Files (x86)\Guild Wars\Gw.exe" to "C:\Program Files *(x86)\Guild Wars\Gw.exe" -d3d9.dll
* 4. run the game and enjoy.

Credits
* https://github.com/Sporif/dxvk-async For DXVK Async
* https://github.com/doitsujin/dxvk For creating DXVK
* https://github.com/Deadsimon/dxvk-async
* https://www.reddit.com/user/simonhazel00
