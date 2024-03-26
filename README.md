# Lukas Sketch Panel
A Custom Panel with a collection of tools and scripts for TVPaint.
> [!NOTE]
> There's a bunch of very useful buttons that will need explanation, but don't have any. Good luck!
## How to install
Download [Lukas_Sketch_Panel.tvpx](panels/Lukas_Sketch_Panel.tvpx?raw=1) and drag it into TVPaint.
> [!CAUTION]
> Some buttons might not work in older versions of TVPaint or non-Pro versions.
## Recommended shortcuts
Keyboard shortcut | Panel button
--- | ---
`Left` | Previous Frame (and Clip)
`Right` | Next Frame (and Clip)
`,` | Previous Instance (and Clip)
`.` | Next Instance (and Clip)
`<` | Add clip exposure
`>` | Remove clip exposure
`Up` | Move up a layer (skip locked layers)
`Down` | Move down a layer (skip locked layers)
`H` | Toggle show/hide other layers
`Shift H` | Toggle show/hide other layers
`Cmd L` / `Ctrl L` | 1-1
`` ` ``| Select Color Group Preset
`/`| Set In/Out to selection
`T`| Tintlasso (Normal)
`Y`| Eraselasso (Normal)

## Change Log
<img align="right" src="screenshot.png">

- [2.8]
  - Fixed bug in `Create color fill layer` where it would color more than just the current layer if the current layer was not the top layer.
  - Removed version number from Panel Identification string.
- [2.7]
  - Fixed bug in `Create color fill layer` where line layer name would get cut off after space character.
  - Added `Cycle Color Group`.
  - Renamed `Label` to `Select Color Group Preset` and changed icon.
  - Replaced dummy button by vertical separators.
- [2.6]
  - Added `Add/remove clip exposure`.
  - Added `Create BG layer`.
- [2.5]
  - `Create color fill layer` adds appropriate `_line` and `_color` postfixes to layers it uses.
  - Updated and translated `Toggle visibilty for line/color/detail/shading layers` to use English layer naming conventions.
- [2.4]
  - Fixed `Create color fill layer` for TVP11.
  - Changed `Toggle color layers` to use English layer naming conventions.
- [2.3]
  - Fixed `New static/animated layer` for TVP11.
  - Renamed `Up/Down` to `Move up/down a layer (skip locked layers)`.
- [2.2]
  - Changed light table buttons to toggle instead of simply turning on/off.
- [2.1]
  - Fixed XML export.
- [2.0]
  - Release.
