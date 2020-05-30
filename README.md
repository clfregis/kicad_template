# KiCAD Template
This repository contains the template that I use in my KiCAD projects
_____________
Based on [Anool Mahidharia](https://hackaday.com/2017/05/18/kicad-best-practises-library-management/) article about KiCAD library management I created this folder structure as stated below:


```c
project_name
  ↳bom           // interactive BOM
  ↳datasheets    // data sheets for components used
  ↳gerber        // final production files
  ↳images        // SVG images and 3D board renders
  ↳pdf           // schematics, board layouts, dimension drawings
```

As you can see, I prefer to have my global library. The reason for that is that I don't design a huge variety of boards nor share my projects with someone (although I would love to, I am just not that popular), so I can keep track of all modifications pretty well.

For more information, please refer to my [KiCAD example](https://github.com/clfregis/kicad-example)
_____________
## Usage

1. Git clone this repo
2. Rename the folder to your project name
3. Create a new project on KiCAD with the same name used on step 2
4. Have fun!