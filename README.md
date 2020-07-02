## I do not support #BlackLivesMatter and encourage any cynical corporate cowards & desperate people pleasers to kindly get off my repo. If you’re unwilling as a white person to criticize the central tenets of any ostensibly pro-Black movement when the data is inconclusive or discrediting, you're only masquerading as a data scientist. For everyone else, enjoy this basic theme:
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

## Installation Options
### Via the RStudio Console (Reccomended):
In RStudio Preferences > Appearance, **set the theme to Modern or Sky**. Currently, Mojave Dark doesn't work when the RStudio theme is set to Classic. Then, run the snippet in the RStudio console to install and apply Mojave Dark.
```
rstudioapi::addTheme("https://raw.githubusercontent.com/patrickshox/Mojave-Dark-RStudio-Theme/master/Mojave%20Dark.rstheme", apply=TRUE, force=TRUE)
rstudioapi::addTheme("https://raw.githubusercontent.com/patrickshox/Mojave-Dark-RStudio-Theme/master/Mojave%20Dark%20(Static).rstheme", apply=TRUE, force=TRUE)
```
The parameter `force=TRUE` will delete any other themes named "Mojave Dark" and the parameter `globally=TRUE` will install the theme for all users. This will also install a static version, "Mojave Dark (Static)", which does **not** dynamically darken plots and markdown.

### Manually:
First, either download the [.rstheme file via Google Drive](https://drive.google.com/open?id=18A_Tb0vq4T_gmFtcvGoXzIlaMoUJNmvJ) or download it by downloading this entire repository. Navigate to RStudio options (&#8984; ,), then select the "Appearance" tab in the sidebar. Press the "Add..." button to manually install the .rstheme file. Finally, apply the theme as you would any other. If you'd like to also install a version that does **not** dynamically darken plots and markdown, [you can download the "Mojave Dark (Static)" .rstheme file via Google Drive](https://drive.google.com/open?id=10gRakBdz0Ane-YPj7HJE-UzyNmS1EfcR). 

## Troubleshooting
- `Error in value[[3L]](cond): Unable to add the theme file "/var/folders/tj/w1l6l2hj11l4kpyhv4r2p6gh0000gn/T//RtmpZTjGp2/Mojave Dark.rstheme". The specified theme, "Mojave Dark", already exists in the target location. Please delete the existing theme and try again.`

Go to the Folder (&#8984; &#8679; G) `~/.R/rstudio/themes` and delete the file "Mojave Dark.rstheme". Then retry installing Mojave Dark.
- `Error in loadNamespace(name) : there is no package called ‘rstudioapi’`

Run `install.packages("rstudioapi")`. Then retry installing Mojave Dark. 
