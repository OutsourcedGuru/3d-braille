# Generating a 3D Mesh File with JavaScript
### (The Braille Project)

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

# 3d-braille

&nbsp;

This is a Node-based CLI which will dynamically render a 3D mesh scene and store it to a file, suitable for slicing/printing on a 3D printer.

&nbsp;

![Braille](https://user-images.githubusercontent.com/15971213/42252232-83627488-7ef0-11e8-9d94-65818884e688.png)

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

## Requirements for this project:
* **Node** and **git**
* The **3d-braille** CLI code with a simple command line interface
* **Cura** app (or similar) for slicing the `.STL` file into `.GCODE` for the printer
* **3D printer** Any GCODE-compatible 3D printer

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

## Overview of Typical Session
&nbsp;1. Generate the mesh file:

```
$ 3d-braille "abcdefghijklmnopqrstuvwx" --w=100 --h=35
platformX: 100
platformY: 35
Printing: abcdefghijklmnopqrstuvwx
Created output.stl
```

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;2. Bring the `output.stl` file into Cura and slice it for your printer

![screen shot 2018-07-28 at 2 20 08 pm](https://user-images.githubusercontent.com/15971213/43360740-67e2d92a-9271-11e8-9d53-7103ce3d7e80.png)

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;3. Upload the `text.gcode` file to your printer and print it.

&nbsp;

&nbsp;

&nbsp;

&nbsp;

## Future Development
I hope to incorporate the Braille Neue typeface (by Kosuke Takahashi) later when I get a second extruder installed into my printer.

![Concept](https://cdn0.tnwcdn.com/wp-content/blogs.dir/1/files/2018/04/braille_neue_system-1592x398.png)

![Braille Neue](https://cdn0.tnwcdn.com/wp-content/blogs.dir/1/files/2018/04/Braille-Neue-hed-796x419.jpg)


&nbsp;

&nbsp;

&nbsp;

&nbsp;


&nbsp;

&nbsp;

&nbsp;

&nbsp;

# https://github.com/OutsourcedGuru/3d-braille