# make-favicon
How to make favicon on Linux.

## Install ImageMagick

```
sudo apt install imagemagick
```

## Put your image(256x256 or higher)

```
image.png
```

## Convert to favicon.ico

```
convert image.png -define icon:auto-resize favicon.ico
```

or

```
convert image.png -define icon:auto-resize=16,32,48,64,128 favicon.ico
```

## Check your favicon.ico

```
> identify favicon.ico
favicon.ico[0] PNG 256x256 256x256+0+0 8-bit sRGB 332KB 0.000u 0:00.009
favicon.ico[1] ICO 192x192 192x192+0+0 32-bit sRGB 332KB 0.000u 0:00.009
favicon.ico[2] ICO 128x128 128x128+0+0 32-bit sRGB 332KB 0.000u 0:00.009
favicon.ico[3] ICO 96x96 96x96+0+0 32-bit sRGB 332KB 0.000u 0:00.000
favicon.ico[4] ICO 64x64 64x64+0+0 32-bit sRGB 332KB 0.000u 0:00.000
favicon.ico[5] ICO 48x48 48x48+0+0 32-bit sRGB 332KB 0.000u 0:00.000
favicon.ico[6] ICO 40x40 40x40+0+0 32-bit sRGB 332KB 0.000u 0:00.000
favicon.ico[7] ICO 32x32 32x32+0+0 32-bit sRGB 332KB 0.000u 0:00.000
favicon.ico[8] ICO 24x24 24x24+0+0 32-bit sRGB 332KB 0.000u 0:00.000
favicon.ico[9] ICO 16x16 16x16+0+0 32-bit sRGB 332KB 0.000u 0:00.000
```