# waifu2x-ncnn-vulkan

## Running

See <https://github.com/nihui/waifu2x-ncnn-vulkan> for details.

With Flatpak you would do this:

```
flatpak run com.github.nihui.waifu2x-ncnn-vulkan \
-i [input.png] -o [output.png] -n [noise-level] -s [scale] -t [tile size] -m [model dir]
```

For example (using default model and denoise disabled):

```
flatpak run com.github.nihui.waifu2x-ncnn-vulkan \
-i ~/Pictures/foo.jpg -o ~/Pictures/bar.png -n -1 -s 2 -t 400
```

Same example with a specific model:

```
flatpak run com.github.nihui.waifu2x-ncnn-vulkan \
-i ~/Pictures/foo.jpg -o ~/Pictures/bar.png -n -1 -s 2 -t 400 \
-m /app/share/models/models-cunet
```

The following models are available:

```
/app/share/models/models-cunet (default model)
/app/share/models/models-upconv_7_anime_style_art_rgb
/app/share/models/models-upconv_7_photo
```

