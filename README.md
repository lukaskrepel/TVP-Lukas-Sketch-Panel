# Lukas Sketch Panel
A Custom Panel with a collection of tools and scripts for TVPaint.
> [!NOTE]
> There's a bunch of very useful buttons that will need explanation, but don't have any. Good luck!

> [!CAUTION]
> Some buttons might not work in older versions of TVPaint or non-Pro versions.
## How to install
Download [Lukas_Sketch_Panel.tvpx](panels/Lukas_Sketch_Panel.tvpx?raw=1) and drag it into TVPaint.
> [!TIP]
> It gets updated pretty regulary, the link above will always be the newest version. See [Updates](https://github.com/lukaskrepel/TVP-Lukas-Sketch-Panel/commits/master/panels/Lukas_Sketch_Panel.tvpx).
## Recommended shortcuts
<img align="right" src="screenshot.png">

Keyboard shortcut|Panel button
---|---
`E`|Eraser (Normal)
`T`|Tintlasso (Normal)
`Y`|Eraselasso (Normal)
`G`|Fill (Layer)
`Shift G`|Fill (Above)
`Ctrl G`|Fill (Display)
`Cmd G`|Create Color Fill Layer
`P`, `Shift P`, `Ctrl P`|Rotate Brush by Increments
`:`|Magic Color Picker
`H`, `Shift H`|Toggle show/hide other layers
`<`|Add clip exposure
`>`|Remove clip exposure
`/`|Set In/Out to selection
`Cmd L`|1-1
`Left`|Previous Frame (and Clip)
`Right`|Next Frame (and Clip)
`,`|Previous Instance (and Clip)
`.`|Next Instance (and Clip)
`Numpad 0`, `Tab`|Toggle Project/Clip View
`Cmd A`|Select All Layers/Clips
`Cmd J`|Duplicate Layer/Clip
`Cmd N`|New Layer/Clip
`Cmd R`|Rename Selected Layers/Clips
`` ` ``|Select Color Group for Selected Layers/Clips
`Z`, `Shift Z`|Cycle Color Group Preset for Selected Layers/Clips
> [!IMPORTANT]
> You need to use the `Toggle Project/Clip View` button instead of the default `Project`/`Clip: Timeline` tabs on the timeline panel! Otherwise certain actions like `New Layer/Clip` won't work.
## Suggested folder structure for projects
> [!IMPORTANT]
> - Running `Render Selected Clips With XML` will prefix exported file and folder names like this: `001_Clipname` (unless there's an `_` in the Clipname).
> - Running `Clips to TVPaint Projects` on `STB/EP01_EpisodeSTB_v001_L.tvpp` creates the `Shots` folder structure with TVP files.
> - Running `Render to 'Renders' Folder` on `Shots/EP001_Intro/EP01_001_Intro_v001_L.tvpp` will create folders and image sequence `Renders/EP01_001_Intro_v001_L/EP01_001_Intro_00001.jpg` etc. If you choose the option to render color groups individually it will create a subfolder for each sequence.
- EP01_Pilot
  - Dailies
  - Edit
  - Renders
    - EP01_001_Intro
      - EP01_001_Intro_00001.jpg
      - EP01_001_Intro_00002.jpg
      - EP01_001_Intro_00003.jpg
    - EP01_002_SomethingHappens
      - Character
        - EP01_002_SomethingHappens_Character_0001.png
        - EP01_002_SomethingHappens_Character_0002.png
        - EP01_002_SomethingHappens_Character_0003.png
      - Thing
        - EP01_002_SomethingHappens_Thing_0001.png
        - EP01_002_SomethingHappens_Thing_0002.png
        - EP01_002_SomethingHappens_Thing_0003.png
  - Shots
    - 001_Intro
      - EP01_001_Intro_v001_L.tvpp
    - 002_SomethingHappens
    - 003_Etcetera
  - STB
    - EP01_EpisodeSTB_v001_L.tvpp
