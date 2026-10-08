<div align="center">

# 🛰️ Radiant Archive Tools

**Blender ⇄ Radiant live link and terrain sculpting for Call of Duty: Black Ops III**

![Game](https://img.shields.io/badge/Call%20of%20Duty-Black%20Ops%20III-orange?style=for-the-badge)
![Editor](https://img.shields.io/badge/Radiant-Mod%20Tools-red?style=for-the-badge)
![Blender](https://img.shields.io/badge/Blender-4.2%2B-blue?style=for-the-badge&logo=blender&logoColor=white)
![License](https://img.shields.io/badge/License-GPL--3.0-green?style=for-the-badge)

A plugin for Radiant, made for MTPlugins, plus a Blender add-on that links Blender to Radiant.

</div>

---

## ✨ Features

### 🔗 Blender Live Link
Build in Blender and see it in Radiant, select in Radiant and see it in Blender.

- Brushes made in Blender appear in Radiant.
- Brushes selected in Radiant appear in Blender.
- Compatible with the Team Create plugin.

### 🖌️ Terrain Brushes
Blender's sculpt brushes on Radiant terrain patches, with Blender's own icons and a hover tag on each. Radius, strength, falloff and brush feel are all adjustable.

<div align="center">

**Brushes**

<table>
<tr>
<td align="center"><img src="repo/assets/images/brushes/draw.png" width="48"><br><sub>Draw</sub></td>
<td align="center"><img src="repo/assets/images/brushes/clay.png" width="48"><br><sub>Clay</sub></td>
<td align="center"><img src="repo/assets/images/brushes/layer.png" width="48"><br><sub>Layer</sub></td>
<td align="center"><img src="repo/assets/images/brushes/inflate.png" width="48"><br><sub>Inflate</sub></td>
<td align="center"><img src="repo/assets/images/brushes/smooth.png" width="48"><br><sub>Smooth</sub></td>
<td align="center"><img src="repo/assets/images/brushes/flatten.png" width="48"><br><sub>Flatten</sub></td>
<td align="center"><img src="repo/assets/images/brushes/fill.png" width="48"><br><sub>Fill</sub></td>
</tr>
<tr>
<td align="center"><img src="repo/assets/images/brushes/scrape.png" width="48"><br><sub>Scrape</sub></td>
<td align="center"><img src="repo/assets/images/brushes/pinch.png" width="48"><br><sub>Pinch</sub></td>
<td align="center"><img src="repo/assets/images/brushes/crease.png" width="48"><br><sub>Crease</sub></td>
<td align="center"><img src="repo/assets/images/brushes/grab.png" width="48"><br><sub>Grab</sub></td>
<td align="center"><img src="repo/assets/images/brushes/elastic_deform.png" width="48"><br><sub>Elastic Deform</sub></td>
<td align="center"><img src="repo/assets/images/brushes/snake_hook.png" width="48"><br><sub>Snake Hook</sub></td>
<td align="center"><img src="repo/assets/images/brushes/nudge.png" width="48"><br><sub>Nudge</sub></td>
</tr>
</table>

**Experimental**

<table>
<tr>
<td align="center"><img src="repo/assets/images/brushes/draw_sharp.png" width="48"><br><sub>Draw Sharp</sub></td>
<td align="center"><img src="repo/assets/images/brushes/clay_strips.png" width="48"><br><sub>Clay Strips</sub></td>
<td align="center"><img src="repo/assets/images/brushes/clay_thumb.png" width="48"><br><sub>Clay Thumb</sub></td>
<td align="center"><img src="repo/assets/images/brushes/blob.png" width="48"><br><sub>Blob</sub></td>
<td align="center"><img src="repo/assets/images/brushes/pull.png" width="48"><br><sub>Pull</sub></td>
<td align="center"><img src="repo/assets/images/brushes/plateau.png" width="48"><br><sub>Plateau</sub></td>
<td align="center"><img src="repo/assets/images/brushes/multi_plane.png" width="48"><br><sub>Multi-plane Scrape</sub></td>
</tr>
<tr>
<td align="center"><img src="repo/assets/images/brushes/relax_slide.png" width="48"><br><sub>Relax Slide</sub></td>
<td align="center"><img src="repo/assets/images/brushes/relax_pinch.png" width="48"><br><sub>Relax Pinch</sub></td>
<td align="center"><img src="repo/assets/images/brushes/thumb.png" width="48"><br><sub>Thumb</sub></td>
<td align="center"><img src="repo/assets/images/brushes/twist.png" width="48"><br><sub>Twist</sub></td>
<td align="center"><img src="repo/assets/images/brushes/airbrush.png" width="48"><br><sub>Airbrush</sub></td>
<td align="center"><img src="repo/assets/images/brushes/crease_sharp.png" width="48"><br><sub>Crease Sharp</sub></td>
<td align="center"><img src="repo/assets/images/brushes/sharpen.png" width="48"><br><sub>Sharpen</sub></td>
</tr>
</table>

</div>

### 🧰 Terrain Tools
- **Sculpt mode:** select terrain patches and sculpt them in the 3D view.
- **Drag makes a patch:** drag in the top view to make a terrain patch instead of a brush.

### 🗺️ Planned
- 🎨 **Terrain Presets:** ready-made terrain setups.
- ⚡ **Terrain Optimization:** tools to keep terrain patches light.




## 📋 Requirements
- 🎮 Call of Duty: Black Ops III Mod Tools with MTPlugins
- 🟠 Blender 4.2 or newer

## 📦 Install

### Plugin
1. Copy `RadiantArchive.dll` into `<BO3>\bin\plugins\RadiantArchive\`, and the `assets\brushes` folder into `<BO3>\bin\plugins\RadiantArchive\assets\brushes\`.
2. In Radiant, press **Ctrl+Shift+P** and tick **Radiant Archive**.

### Blender add-on
1. **Edit > Preferences > Add-ons > Install from Disk**, pick `dist\radiant_blender_link.zip` and enable it.
2. Open the 3D view sidebar (**N**), go to the **Radiant** tab and press **Connect**.

## 🙏 Credits
Brush icons are Blender's artwork (GPL). Built on MTPlugins (GPL-3.0).

## 📄 License
GPL-3.0
