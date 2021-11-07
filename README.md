# Rocketlauncher-Bezels
Rocketlauncher bezels derived from my HSM Reflection Shader Graphics.

## Instructions

Since the only differnece between RA Overlay and RL Bezels is folder structure and coordinate systems, until such time as I create bezels for systems that RA doesn't support, I will leave converting the RA Overlays to the end user.

RA uses the top left coordinate of the veiwport in concert with the dimension of the viewport so the info we need is:


**4K**
* Viewport Height = 1853
* Viewport Width = 2461
* Viewport x = 690
* Viewport y = 153

**1080**
* Viewport Height = 927
* Viewport Width = 1231
* Viewport x = 345
* Viewport y = 76

as stated in my RA Overlay README.

For RL the bezel.ini uses the top left coordinate in concert with the bottom right coordinate and the bezel.ini would read:


**4K** 
```
[General]
Bezel Screen Top Left X Coordinate=690
Bezel Screen Top Left Y Coordinate=153
Bezel Screen Bottom Right X Coordinate=3151
Bezel Screen Bottom Right Y Coordinate=2006
```

**1080** 
```
[General]
Bezel Screen Top Left X Coordinate=345
Bezel Screen Top Left Y Coordinate=76
Bezel Screen Bottom Right X Coordinate=1576
Bezel Screen Bottom Right Y Coordinate=1003
```

I believe RL will also scale the bezel to your screen so unless you are really trying to save space there is no reason to use the 1080 version.

Folder structure is important so I have put an example using the proper convention in the repo.

### LICENSE
*******************
All the assets, including documentation and code, are published under the 'Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)' Creative Commons license.

Extract from ['CC BY-NC-SA 4.0' Commons Deed](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en):


> You are free to:
> - Share &#8212; copy and redistribute the material in any medium or format
> - Adapt &#8212; remix, transform, and build upon the material
> 
> The licensor cannot revoke these freedoms as long as you follow the license terms.
> 
> Under the following terms:
>
> - Attribution &#8212;You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
> - NonCommercial &#8212; You may not use the material for commercial purposes.
> - ShareAlike &#8212; If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.
> - No additional restrictions &#8212; You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

For further reading check the ['CC BY-NC-SA 4.0' legal code](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en).