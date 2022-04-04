# Place-Stardew-Valley-Tampermonkey-Overlays

Add the [Tamper Monkey Extention](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)

This will want you to allow access to all websites so if you're not comfortable with that maybe don't do this. Just make sure your trust any scripts you add to it. I triple checked this script before I modified it for my use. Please be careful out there.

**Please DM me on Discord if we need anything updated Vera#4726 or send a push request :)**

***
**Install from link**
- [Main pixel art overlay](https://github.com/VeraLapsa/Place-Stardew-Valley-Tampermonkey-Overlays/raw/main/r-place%20templater%20Stardew%20Valley%20Main%20Place.user.js) @ 71,345
- [Mouse Shop Overlay](https://github.com/VeraLapsa/Place-Stardew-Valley-Tampermonkey-Overlays/raw/main/stardewvalleymousehouse.user.js) @ 1708,1008
- ~~[Above Mouse Shop Overlay](https://github.com/VeraLapsa/Place-Stardew-Valley-Tampermonkey-Overlays)~~
- [Above Mouse Shop Overlay Respects Kobe's 24](https://github.com/VeraLapsa/Place-Stardew-Valley-Tampermonkey-Overlays/raw/main/r-place%20templater%20Stardew%20Valley%20Above%20Mouse%20Shop%20Leaving%20Kobe.user.js) @ 1708,1000
- [Below Mouse Shop Overlay](https://github.com/VeraLapsa/Place-Stardew-Valley-Tampermonkey-Overlays/raw/861c1fba26285c7fdca30b9929fa53b1b8cb4d0f/r-place%20templater%20Below%20Mouse%20Hat%20Shop.user.js) @ 1708,1043
- [Duck](https://github.com/VeraLapsa/Place-Stardew-Valley-Tampermonkey-Overlays/raw/main/r-place%20templater%20Stardew%20Valley%20Duck.user.js) @ 1692,985

***
- Enjoy the overlays.

***
**Manually Add Script**
- Click on the Tamper Monkey icon up where extention icons are added( it's like a black rounded square with 2 white circles in it.)
- Click create new script.
- Clear the editor of it's default content.
- Copy the code from a js file in this respository.
- Save the script via File->Save or do a Ctrl-S
- It should be enabled by default.
- Do a Ctrl-Shift-R on /r/place to clear your cache.
***
*To Use the Scipt for other things* 
- This script can do tranparent pngs and can have multilple versions of it running as long as you change the name of the script.
- There's a `TEMPLATE` varible on the 16th line that contains the url of the image you want to overlay. Make sure it's the same size you want it on the canvas.
- Also if you change use a different image domain, I use Imgur, change the `// @connect      imgur.com` to what ever domain your using.
- The Coords for where the overlay will be placed are in on the 18th line, with the in an `[X,Y]` style.
