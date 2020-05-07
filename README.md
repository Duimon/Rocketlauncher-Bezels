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

Folder structure is important so I will put an example using the proper convention in the repo.
