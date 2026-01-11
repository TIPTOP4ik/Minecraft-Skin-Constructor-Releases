# Minecraft Skin Constructor

A small desktop app to preview Minecraft skins in **2D** and **3D**, rotate the model, and build a final skin by stacking **PNG overlays**.

## Download
➡️ **[Download latest release](../../releases/latest)**

## What you can do
- Load a **64×64** Minecraft skin
- Switch **2D / 3D** view and rotate the model
- Toggle **Classic / Slim** arms
- Pick multiple overlay assets (click again to unselect)
- Export the final skin as **PNG** (`Save Skin`)

## Add your own assets (recommended)
You can add your own overlay PNGs anytime — just drop them into the folders below (next to the app).

**Folder structure must stay exactly the same** (category folder names are required):
- `assets/Head/`, `assets/Body/`, `assets/Arms/`, `assets/Legs/`, `assets/Shoes/`, `assets/Accessories/`
- `assets_slim/Head/`, `assets_slim/Body/`, `assets_slim/Arms/`, `assets_slim/Legs/`, `assets_slim/Shoes/`, `assets_slim/Accessories/`
- `assets_global/Head/`, `assets_global/Body/`, `assets_global/Arms/`, `assets_global/Legs/`, `assets_global/Shoes/`, `assets_global/Accessories/`

### Rules
- Overlays must be **64×64 PNG** with transparency.
- Put **Classic-only** assets into `assets/`
- Put **Slim-only** assets into `assets_slim/`
- Put assets that work for both into `assets_global/`
- You can add/remove files while the app is closed — they will appear next launch (or after switching category/model).

## Notes
This app reads asset folders from disk, so you keep full control over your custom overlays.
