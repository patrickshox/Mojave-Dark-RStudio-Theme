⚠️ I'm currently looking for someone interested in maintaining this project. Email me at keys4safari@gmail.com if you're interested. ⚠️

# Mojave Dark: An RStudio Theme for Apple Lovers

![](https://github.com/patrickshox/Mojave-Dark-RStudio-Theme/blob/master/Demo%20Images%20and%20Gifs/Main.png)

### Dark styles across the entire IDE, not just the editor:
<img src="https://github.com/patrickshox/Mojave-Dark-RStudio-Theme/blob/master/Demo%20Images%20and%20Gifs/DarkPanels.png" class="box-shadow-large p-3">

### *(Optional)* Dynamic darkening of plots and markdown:

Plot (white to alpha)             |  Markdown (invert colors)
:--------------------------------:|:-------------------------:
![](https://github.com/patrickshox/Mojave-Dark-RStudio-Theme/blob/master/Demo%20Images%20and%20Gifs/PlotsWhiteTransparencyDemo.gif)  |  ![](https://github.com/patrickshox/Mojave-Dark-RStudio-Theme/blob/master/Demo%20Images%20and%20Gifs/MarkdownColorInversionDemo.gif)

### An Xcode-inspired debugger:
![](https://github.com/patrickshox/Mojave-Dark-RStudio-Theme/blob/master/Demo%20Images%20and%20Gifs/DebugStyles.png)

### Code coloring inspired by Xcode:

Mojave Dark              |  Xcode
:-----------------------:|:-------------------------:
<img src="https://github.com/patrickshox/Mojave-Dark-RStudio-Theme/blob/master/Demo%20Images%20and%20Gifs/Mojave%20Dark%20Fonts%20and%20Colors.png">   |  <img src="https://github.com/patrickshox/Mojave-Dark-RStudio-Theme/blob/master/Demo%20Images%20and%20Gifs/Xcode%20Fonts%20and%20Colors.png"> 

## Installation
In RStudio Preferences > Appearance, **set the theme to Modern or Sky**. Currently, Mojave Dark doesn't work when the RStudio theme is set to Classic. Then, run the snippet in the RStudio console to install and apply Mojave Dark.
```
rstudioapi::addTheme("https://raw.githubusercontent.com/patrickshox/Mojave-Dark-RStudio-Theme/master/Mojave%20Dark.rstheme", apply=TRUE, force=TRUE)
rstudioapi::addTheme("https://raw.githubusercontent.com/patrickshox/Mojave-Dark-RStudio-Theme/master/Mojave%20Dark%20(Static).rstheme", apply=TRUE, force=TRUE)
```
The parameter `force=TRUE` will delete any other themes named "Mojave Dark" and the parameter `globally=TRUE` will install the theme for all users. This will also install a static version, "Mojave Dark (Static)", which does **not** dynamically darken plots and markdown.

## Troubleshooting
- `Error in value[[3L]](cond): Unable to add the theme file "/var/folders/tj/w1l6l2hj11l4kpyhv4r2p6gh0000gn/T//RtmpZTjGp2/Mojave Dark.rstheme". The specified theme, "Mojave Dark", already exists in the target location. Please delete the existing theme and try again.`

Go to the Folder (&#8984; &#8679; G) `~/.R/rstudio/themes` and delete the file "Mojave Dark.rstheme". Then retry installing Mojave Dark.
- `Error in loadNamespace(name) : there is no package called ‘rstudioapi’`

Run `install.packages("rstudioapi")`. Then retry installing Mojave Dark. 
