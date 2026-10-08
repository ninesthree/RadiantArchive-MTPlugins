# Radiant Archive Tools

A plugin for Call of Duty: Black Ops III's Radiant (Mod Tools), made for MTPlugins, plus a Blender add-on that links Blender to Radiant.

## Features
- **Blender Live Link:** brushes made in Blender appear in Radiant, and brushes selected in Radiant appear in Blender. Compatible with the Team Create plugin.
- **Terrain Brushes:** Blender's sculpt brushes (Draw, Clay, Layer, Inflate, Smooth, Flatten, Fill, Scrape, Pinch, Crease, Grab, Elastic Deform, Snake Hook, Nudge, plus experimental ones) on Radiant terrain patches, with adjustable radius, strength, falloff and brush feel.
- **Terrain Tools:** Sculpt mode, and an option to make a terrain patch instead of a brush when you drag in the top view.

### Planned
- **Terrain Presets:** ready-made terrain setups.
- **Terrain Optimization:** tools to keep terrain patches light.




## Requirements
- Call of Duty: Black Ops III Mod Tools with MTPlugins
- Blender 4.2 or newer

## Install
**Plugin**
1. Copy `RadiantArchive.dll` into `<BO3>\bin\plugins\RadiantArchive\`, and the `assets\brushes` folder into `<BO3>\bin\plugins\RadiantArchive\assets\brushes\`.
2. In Radiant, press **Ctrl+Shift+P** and tick **Radiant Archive**.

**Blender add-on**
1. **Edit > Preferences > Add-ons > Install from Disk**, pick `dist\radiant_blender_link.zip` and enable it.
2. Open the 3D view sidebar (**N**), go to the **Radiant** tab and press **Connect**.

## Credits
Brush icons are Blender's artwork (GPL). Built on MTPlugins (GPL-3.0).

## License
GPL-3.0
