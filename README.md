# EasedDiscordTheme
Builds on the dark theme of Discord. Gives Discord a discreet color change and calming background for the chat. (Background image and color can be changed.)

## Created for BetterDiscord
This theme requires Better Discord to function, as "vanilla" Discord does not currently support custom themes.

Download Better Discord @ - https://betterdiscord.net/home/

### Files
**Source Code -** For copy/pasting into the "Custom CSS" tab, use this if you wish to customize a few bits for yourself.

**Theme File -** For dragging into the "Themes" folder for Better Discord, use this for an easy install.

**Preview -** Shows how Discord appears with this theme installed. ("Stock" image and color used.)

### How do I change the background image for chat?
First off, I'd recommend using an image with a wallpaper-standard resolution.

To use an image, you need a hyperlink for it. (Ex. https://imagedomain.com/thisimage.jpg) Must have *.jpg* or *.png* extension.

- To change the image with the source code, scroll down until you find the *Variables* section.
- To change the image with the theme file, open it in notepad.

With this hyperlink, change the `--chat-bck` variable's hyperlink to the image you wish to use.

`--chat-bck: linear-gradient( rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8) ), url(**CHANGE THIS**);`

> The `linear-gradient( rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8) )` part has to stay as it is, so the image doesn't dominate the chat.

### Changing the Main Color
The main color can also be changed. It uses standard RGB.

Edit the `--main-clr` variable.

`--main-clr: rgba(RED, GREEN, BLUE, ALPHA);`

> **Alpha** means how "dominant" the color will be, the closer to 1 the value is, the more saturated the color will be.
