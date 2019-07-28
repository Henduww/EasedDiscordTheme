# EasedDiscordTheme 3.0
Aims to compact and simplify Discord by adding hover and focus effects on unecessary clutter. (Background image and color can be changed.)

When using Discord on a 2nd monitor, it's nice to not have everything clutter the chat, as that's what you really wanna see. This theme adds hover functionality to compact the chat form, the channels, the guild list, and members list.

GIF PREVIEW (Showcases hover functionality):
![Functionality GIF](https://i.gyazo.com/ae4049e02b03dad867d533c2222d7877.mp4)

A few examples of how you can customize the theme: (takes about 2-3 minutes if you're slow)
![Example 1](https://i.gyazo.com/1681108508eaddd7cfe07084c6ecd39b.jpg)
![Example 2](https://i.gyazo.com/703ed95196c8619e2a0adf25e4d711b2.jpg)
![Example 3](https://i.gyazo.com/eee628318e1930ff91c5e696c3016522.jpg)

> NOTE: Some small details may be outdated in the examples. GIF should always be up-to date.

## Created for BetterDiscord
This theme requires Better Discord to function, as "vanilla" Discord does not currently support custom themes.

Download Better Discord @ - https://betterdiscord.net/home/

### Files
**Source Code -** For copy/pasting into the "Custom CSS" tab, use this if you wish to customize a few bits for yourself.
**NOTE:** If you're using this file, you need to grab the `:root { }` section from the theme file and add it to the top of the code to get the colors and the background image.

**Theme File -** For dragging into the "Themes" folder for Better Discord, use this for an easy install.

**Preview -** Shows how Discord appears with this theme installed. ("Stock" image and color used.)

### How do I change the background image for chat?
First off, I'd recommend using an image with a wallpaper-standard resolution.

To use an image, you need a hyperlink for it. (E.g. https://imagedomain.com/thisimage.jpg) Must have *.jpg* or *.png* extension.

- To change the image or colors with the source code, copy the root section from the theme file to the top of the code in the source file.
- To change the image or colors with the theme file, open it in notepad.

With this hyperlink, change the `--chat-bck` variable's hyperlink to the image you wish to use.

`--img-url: url(**CHANGE THIS**);`

### Changing the Main Color
The main color can also be changed. It uses standard RGB.

Edit the `--main-clr` variable.

`--main-clr: RED, GREEN, BLUE;`

> The `--dark-clr` variable may be changed too, although it's not recommended, but feel free to play around with it as you wish.

