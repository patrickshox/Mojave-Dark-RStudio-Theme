# Mojave Dark: An RStudio Theme for Apple Lovers

![](Main.png)

### Dynamic darkening of plots and markdown:

Plot (white to alpha)             |  Markdown (invert colors)
:-------------------------:|:-------------------------:
![](PlotsWhiteTransparencyDemo.gif)  |  ![](MarkdownColorInversionDemo.gif)

### An Xcode-inspired debugger:
![](DebugStyles.png)

### And Dark styles across the entire IDE, not just the editor:
![](DarkEverywhere.png)

## Installation
Enter the following into the RStudio console.
```
rstudioapi::addTheme("https://raw.githubusercontent.com/patrickshox/Mojave-Dark-RStudio-Theme/master/Mojave%20Dark.rstheme", apply=TRUE, force=TRUE, global=TRUE)
```
The parameter `force=TRUE` will delete any other themes named "Mojave Dark" and the parameter `global=TRUE` will install the theme for all users.
