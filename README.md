# EasedDiscordTheme 3.1
Aims to compact and simplify Discord by adding hover and focus effects on unecessary clutter. (Background image and color can be changed.)

When using Discord on a 2nd monitor, it's nice to not have everything clutter the chat, as that's what you really wanna see. This theme adds hover functionality to compact the chat form, the channels, the guild list, and members list.

> VIDEO PREVIEW (Showcases hover functionality):
> https://i.gyazo.com/87506795503770bffc53bf893e8250f4.mp4

A few examples of how you can customize the theme: (takes about 2-3 minutes if you're slow)

Keep in mind that the channel tab, chat and member tab are all compacted until you hover them.

<img src="https://camo.githubusercontent.com/98c7e9c59dbedb4efe8d881739d82ff225960448/68747470733a2f2f692e6779617a6f2e636f6d2f31363831313038353038656164646437636665303730383463366563643339622e6a7067" alt="Example 1" data-canonical-src="https://i.gyazo.com/1681108508eaddd7cfe07084c6ecd39b.jpg" width="245" style="">
<img src="https://camo.githubusercontent.com/31c66aad77dd3b50115e5b360ee090009013f45d/68747470733a2f2f692e6779617a6f2e636f6d2f37303365643935313936633836313965326130616466323565346437313162322e6a7067" alt="Example 2" data-canonical-src="https://i.gyazo.com/703ed95196c8619e2a0adf25e4d711b2.jpg" width="245px" style="">
<img src="https://camo.githubusercontent.com/cee1109ceb0eb0ee3fad3fb7e334e173236943d6/68747470733a2f2f692e6779617a6f2e636f6d2f65656536323833313865313933306666393163356536393663333031363532322e6a7067" alt="Example 3" data-canonical-src="https://i.gyazo.com/eee628318e1930ff91c5e696c3016522.jpg" width="245px" style="">

> NOTE: Some small details may be outdated in the examples. GIF should always be up-to date.

> NEW IN 3.1: Fixes for new Discord update + sleeker style for streaming banner

> NEW IN 3.1.2: Multiple fixes to the channels bar and reduced file size

## Created for BetterDiscord
This theme requires Better Discord to function, as "vanilla" Discord does not currently support custom themes.

Get Better Discord @ - https://betterdiscord.net/home/

### Files
**Source Code -** For copy/pasting into the "Custom CSS" tab.

**Readme.md** - This file.

### How do I change the background image for chat?
First off, I'd recommend using an image with a wallpaper-standard resolution.

To use an image, you need a hyperlink for it. (E.g. https://imagedomain.com/thisimage.jpg) Must have *.jpg* or *.png* extension.

- To change the image or colors, you need to modiby the variables in the *:root* section at the top of the code.

With this hyperlink, change the `--img-url` variables hyperlink to the image you wish to use.

`--img-url: url(**CHANGE THIS**);`

### Changing the Main Color
The main color can also be changed. It uses standard RGB.

Edit the `--main-clr` variable in the *:root* section, which is at the top of the code.

`--main-clr: RED, GREEN, BLUE;`

> The `--dark-clr` variable may be changed too, although it's not recommended, but feel free to play around with it as you wish.

