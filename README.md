# Welcome

This is my personal collection of wallpapers!
All of them are found publicly on the web and I will try to provide the sources of the images.
If you think an image should not be listed here, please open an issue and I will try to take it from the repository ASAP!

## Palette Switcher

If you have an image which you like, but it doesn't fit the theme,
try the [palette switcher](https://paletteswitcher.bruyant.xyz/).

# Sources

If you are interested in the images, you can lookup the README file in each folder for links to the images.

# webp

`webp` images are not supported by some tools.
To transform them into `png` files, the following bash one-liner can be executed in the folder:

```bash
for file in *.webp; do magick "$file" "${file%.webp}.png"; done;
```
