# Place-Stardew-Valley-Tampermonkey-Overlays

Add the [Tamper Monkey Extention](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)

This will want you to allow access to all websites so if you're not comfortable with that maybe don't do this. Just make sure your trust any scripts you add to it. I triple checked this script before I modified it for my use. Please be careful out there.

**Please DM me on Discord if we need anything updated Vera#4726 or send a push request :)**

***
**Install from link**
- [Main pixel art overlay](https://github.com/VeraLapsa/Place-Stardew-Valley-Tampermonkey-Overlays/raw/caf7f1041581cf8a7b5fa7f6b43b0272385b6726/r-place%20templater%20Stardew%20Valley%20Main%20Place.user.js) v0.4 should be the final version @ 71,345 
- [Mouse Shop Overlay with our PepeRat Allies](https://github.com/VeraLapsa/Place-Stardew-Valley-Tampermonkey-Overlays/raw/01b1e10c6e09370f3d266e114d40ad0e8758fdf0/r-place%20SDV%20Mouse%20Shop%20%26%20PepeRat%20Allies.user.js) v0.5 @ 1645,956 to 1768,1082 - uses pinned sprites in defence-chat
**Makes sure that only these 2 are active in tampermonkey for SDV sprites**
- Do a Ctrl-R of r/place when installing or reinstalling(if there's an update) these scripts.

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
