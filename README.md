## Running:
See <https://github.com/nihui/waifu2x-ncnn-vulkan#usage> for details.  
With flatpak you would do this:
```
flatpak run com.github.nihui.waifu2x-ncnn-vulkan -i [input.png] -o [output.png] -n [noise-level] -s [scale] -t [tile size] -m [model dir]
```
For example (using default model and denoise disabled):
```
$ flatpak run com.github.nihui.waifu2x-ncnn-vulkan -i ~/Pictures/foo.jpg -o ~/Pictures/bar.png -n -1 -s 2 -t 400
```
