# 3D Radio/RPF
This modification renders the sector of the Radio Position Finding in the 3D world.

The direction and width of the cone are always precise. (22.5 degrees / sector)

# Overview
![image](https://github.com/AndrewTaro/ThreeDimentionalRadioPublic/assets/36262823/d27e0983-faee-4fb0-8087-648e752c3a19)
![image](https://github.com/AndrewTaro/ThreeDimentionalRadioPublic/assets/36262823/ac30ad3e-29aa-4179-967f-7670e0924daa)

# Install
1. Download a zip.
2. Unzip the archive and you should get `gui`, `PnFMods` folders and `PnFModsLoader.py`.
3. Move them to `(wows)/bin/(latest_number)/res_mods/`. So the path will look like `res_mods/PnFModsLoader.py`, etc.
4. Done!

# Config
[TTaro Mod Config](../../../TTaroModConfig) supports this mod.  You can adjust the opacity of radar circle, depending on the radar state and has enemy within.

![image](https://github.com/AndrewTaro/ThreeDimentionalRadioPublic/assets/36262823/96d41ff9-027a-4665-8051-5e4bf00657a5)

### Circle Opacity
- The opacity of the circle when there is No visible enemy within the range.
### Circle Opacity (With Enemy in Range)
- The opacity of a circle when there is a visible enemy within the range.
### "Enemy in Range" Distance Offset
- The distance offset for detecting visible enemies within the range. It affects the **Circle Opacity (With Enemy in Range)**.
