TonyNES JSNES Stable Restore v0.5

This restores the original working JSNES engine route.

Upload ONLY these files to the root of the TonyNES GitHub Pages repo:
- index.html
- manifest.webmanifest
- .nojekyll

Do NOT upload:
- player.html
- any EmulatorJS test files
- the zip itself
- the containing folder

Recommended cleanup:
If player.html is still in your repo from the EmulatorJS test, delete it. It is not used by this version.

After upload:
Open your TonyNES GitHub Pages URL with:
?v=50

Then:
Library
Import ROMs
Choose a simple .nes file
Play

This version:
- uses JSNES, the one that worked
- keeps local library
- keeps the handheld style
- removes the broken EmulatorJS route
- includes no ROMs
