# KiCAD Template
This repository contains the template that I use in my KiCAD projects
_____________
Based on [Anool Mahidharia](https://hackaday.com/2017/05/18/kicad-best-practises-library-management/) article about KiCAD library management I created this folder structure as stated below:


```c
project_name
  ↳3d_models     // .STEP and .WRL model files for all footprints
  ↳datasheets    // data sheets for components used
  ↳gerber        // final production files
  ↳images        // SVG images and 3D board renders
  ↳lib_sch       // schematic symbols
  ↳lib_fp.pretty // footprints
  ↳pdf           // schematics, board layouts, dimension drawings
```

