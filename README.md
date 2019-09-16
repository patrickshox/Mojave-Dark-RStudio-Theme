# Mojave Dark: An RStudio Theme for Apple Lovers

![](Main.png)

### Dynamic darkening of plots and markdown:

Plot (white to alpha)             |  Markdown (invert colors)
:-------------------------:|:-------------------------:
![](PlotsWhiteTransparencyDemo.gif)  |  ![](MarkdownColorInversionDemo.gif)

### An Xcode-inspired debugger:
![](DebugStyles.png)

### Dark styles across the entire IDE, not just the editor:
![](DarkEverywhere.png)

### Code coloring inspired by Xcode:

Mojave Dark              |  Xcode
:-------------------------:|:-------------------------:
<img src="Mojave Dark Fonts and Colors.png">  |  <img src="Xcode Fonts And Colors Screenshot.png" height="80%"> 

## Installation
In RStudio Preferences > Appearance, set the theme to Modern or Sky. Currently, Mojave Dark doesn't work when the RStudio theme is set to Classic. Then, run the snippet in the RStudio console to install and apply Mojave Dark.
```
rstudioapi::addTheme("https://raw.githubusercontent.com/patrickshox/Mojave-Dark-RStudio-Theme/master/Mojave%20Dark.rstheme", apply=TRUE, force=TRUE, global=FALSE)
```
The parameter `force=TRUE` will delete any other themes named "Mojave Dark" and the parameter `globally=TRUE` will install the theme for all users.
