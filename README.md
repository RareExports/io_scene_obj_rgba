# io_scene_obj_rgba

These files overwrite the files in [Blender 2.79c](https://download.blender.org/release/Blender2.79/latest/)'s `scripts/addons/io_scene_obj`.

It expects vertices in Wavefront OBJ files to use the format:
```
v x y z r g b a
```

Where `r`, `g`, `b`, `a` are values `0 <= n <= 255`.
