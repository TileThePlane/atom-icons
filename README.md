# Atom App Icons
 A project for custom [Atom](https://atom.io) Icons. All Rights Reserved with [Github](https://github.com) and the respective owners of the themes I am using.
 Inspired from [vscode-icons](https://github.com/dhanishgajjar/vscode-icons), a similar project for [Visual Studio Code](https://code.visualstudio.com/) by [@dhanishgajjar](https://github.com/dhanishgajjar/)
 
 ## Available Icons
 ### Material Series
 These icons were contributed by: [@haideralipunjabi](https://github.com/haideralipunjabi)

 <img title="material_amber.svg" src="svg/material_amber.svg" width="128px"> <img title="material_blue.svg" src="svg/material_blue.svg" width="128px"> <img title="material_bluegrey.svg" src="svg/material_bluegrey.svg" width="128px"> <img title="material_brown.svg" src="svg/material_brown.svg" width="128px"> <img title="material_cyan.svg" src="svg/material_cyan.svg" width="128px"> <img title="material_deeporange.svg" src="svg/material_deeporange.svg" width="128px"> <img title="material_deeppurple.svg" src="svg/material_deeppurple.svg" width="128px"> <img title="material_green.svg" src="svg/material_green.svg" width="128px"> <img title="material_grey.svg" src="svg/material_grey.svg" width="128px"> <img title="material_indigo.svg" src="svg/material_indigo.svg" width="128px"> <img title="material_lightblue.svg" src="svg/material_lightblue.svg" width="128px"> <img title="material_lightgreen.svg" src="svg/material_lightgreen.svg" width="128px"> <img title="material_lime.svg" src="svg/material_lime.svg" width="128px"> <img title="material_orange.svg" src="svg/material_orange.svg" width="128px"> <img title="material_pink.svg" src="svg/material_pink.svg" width="128px"> <img title="material_purple.svg" src="svg/material_purple.svg" width="128px"> <img title="material_red.svg" src="svg/material_red.svg" width="128px"> <img title="material_teal.svg" src="svg/material_teal.svg" width="128px"> <img title="material_yellow.svg" src="svg/material_yellow.svg" width="128px"> ### Social Media Series
 These icons were contributed by: [@haideralipunjabi](https://github.com/haideralipunjabi)

 <img title="social_facebook.svg" src="svg/social_facebook.svg" width="128px"> <img title="social_medium.svg" src="svg/social_medium.svg" width="128px"> <img title="social_reddit.svg" src="svg/social_reddit.svg" width="128px"> <img title="social_snapchat.svg" src="svg/social_snapchat.svg" width="128px"> <img title="social_twitter.svg" src="svg/social_twitter.svg" width="128px"> <img title="social_whatsapp.svg" src="svg/social_whatsapp.svg" width="128px"> <img title="social_wordpress.svg" src="svg/social_wordpress.svg" width="128px"> <img title="social_youtube.svg" src="svg/social_youtube.svg" width="128px"> 
### Others
 <img title="blackonwhite.svg" src="svg/blackonwhite.svg" width="128px"> <img title="whiteonblack.svg" src="svg/whiteonblack.svg" width="128px"> 
 
 ## How to Contribute
 * Different Color Icon:
     * Download the [icon.svg](icon.svg) file.
     * Open the file in any text editor.
     * Change the required color values.
     * Send a PR with the new SVG file in `svg` folder, the Linux and Windows flavours will be generated by code.
 * Different Design:
     * Use any software to make an SVG.
     * It would be better if you use the [icon.svg](icon.svg) as a base.
     * Keep the size `512x512px`
     * In the SVG code, remove the width & height attributes. (They create issues while resizing for Linux and Windows icons).
     * Keeping the `viewbox` at `0 0` is also recommended
     * Send a PR with the new SVG file in `svg` folder, the Linux and Windows flavours will be generated by code.
 
 ## How to Install
 
 **Mac OS:**
 
 Download [Image2Icon](http://www.img2icnsapp.com/) app. Drop the  `svg` as source and export a `ICNS` file.
 
 Easiest way to change the icons is by using https://freemacsoft.net/liteicon/. Just Drag and Drop the custom icon and hit `Apply Changes`.
 
 Copy the `.icns` file you'd like to use. Find VS Code in your Applications folder, right click the icon and select `Get Info`. Click the icon in the top right corner so that a blue highlight appears around it. `⌘ + V` to paste the new icon in. It may take a few restarts of VS Code for the icon to take.
 
 If for some reason that doesn't work, then dragging the `.icns` to the icon (in the top left) of the info pane, until you see the green plus sign and then dropping it works.
 
 **Windows:**
 
 Right click on the shortcut App Icon, select properties and then shortcut tab and then `change icon` button.
 
 **Linux:**
 
 I think this works, but not sure https://smdavis.us/projects/menulibre/

