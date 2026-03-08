# CS2 Settings

This repository contains all of my **Counter-Strike 2 settings and configuration files** in one place.

It includes:

- mouse sensitivity
- resolution and video settings
- crosshair
- viewmodel
- radar
- launch options
- full config files

All configuration files can be found in the **cfg folder**.

---

# Quick Overview

| Setting | Value |
|-------|-------|
| DPI | 500| 
| Sensitivity | 1.2|
| eDPI |600|
| Resolution |1080x1080 |
| Aspect Ratio | 1:1|
| Refresh Rate |360hz |
|Startup Options:| +fps_max 0 -noreflex -w 1920 -h 1080 -exec autoexec +cl_forcepreload 1 -allow_third_party_software|

# Hardware
| Part |  |
|-------|-------|
|CPU | 9800x3d|
|GPU|4070Super|
|RAM|2x16 GB 6000MTs CL26|
|Keyboard|Wooting 60HE|
|Mouse|Endgamegear OP1w 4K PurpleFrost-Shell-Mod|
|Monitor|Zowie XL2566K|
|Microphone|Rode Procaster|

---

# Mouse Settings

| Setting | Value |
|-------|-------|
| DPI | 500|
| Sensitivity | 1.2|
| eDPI |600 |
| Zoom Sensitivity Ratio |1.0 |

---

# Resolution & Video Settings

| Setting | Value |
|-------|-------|
| Resolution |1080x1080|
| Aspect Ratio |1:1 |
| Scaling Mode | Display|
| Display Mode | Fullscreen Windowed|
| Refresh Rate | 360hz|
| GSYNC | On|
| VSYNC(Nvidia) | On|
| VSYNC(ingame) | Off|
| Low Latency Mode(Nvidia) | Ultra|
**-noreflex startup option used!**



| Setting | Value |
|-------|-------|
|Multisampling Anti-Aliasing Mode| CMAA2|
|Global Shadow Quality|Low|
|Dynamic shadows|All|
|Model / Texture Detail|High|
|Texture Filtering Mode|Bilinear|
|Shader Detail|Low|
|Particle Detail|Low|
|Ambient Occlusion|Disabled|
|High Dynamic Range|Quality|
|FidelityFX Super Resolution|Disabled|

---

# Crosshair

```cfg
cl_crosshairalpha 173;cl_crosshaircolor 2;cl_crosshaircolor_b 255;cl_crosshaircolor_r 255;cl_crosshaircolor_g 255;cl_crosshairdot 1;cl_crosshairgap -3;cl_crosshairsize 0;cl_crosshairstyle 4;cl_crosshairusealpha 1;cl_crosshairthickness 0.9;cl_fixedcrosshairgap -3;cl_crosshair_outlinethickness 1;cl_crosshair_drawoutline 1
```
---

# Viewmodel

```viewmodel
viewmodel_presetpos "2";viewmodel_fov "68";viewmodel_offset_x "2";viewmodel_offset_y "0";viewmodel_offset_z "-2"
```
---

# HUD & Radar

```radar
cl_radar_scale 0.35;bind capslock toggle cl_radar_scale 0.35 1;cl_radar_icon_scale_min 0.4;cl_hud_radar_scale 1.3;hud_scaling 1.1
```
---
