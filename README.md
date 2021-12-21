# io_scene_obj_rgba

Adds vertex color support to Blender's Wavefront OBJ importer, specifically for importing files exporting used [RareExports](https://github.com/RareExports) tools.

The `.py` files in this repo are meant to overwrite the files in [Blender 2.79c](https://download.blender.org/release/Blender2.79/latest/)'s `scripts/addons/io_scene_obj`.

It expects vertices in Wavefront OBJ files to use the format:
```
v x y z r g b a
```

Where `r`, `g`, `b`, `a` are values `0 <= n <= 255`.

## Why vertex colors?

This screenshot speaks for itself:

![Terrydactyland](why-vertex-colors.jpg)
