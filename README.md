TonyRetro Multi Emulator v0.1

Upload everything in this folder to the root of a GitHub Pages repo.

Files included:
- index.html, the TonyRetro system carousel launcher
- manifest.webmanifest
- .nojekyll
- systems/nes/index.html
- systems/atari-st/index.html
- systems/atari-st/tonyst.html
- engine/hatari/PUT_HATARI_FILES_HERE.txt

NES:
- Uses the stable JSNES route, not the broken EmulatorJS test.
- Has a local library.
- Uses a visible native file picker to avoid iPhone greying out .nes files.
- No ROMs are included.

Atari ST:
- Uses the existing TonyST Hatari module.
- You must copy your Hatari engine files into:
  engine/hatari/hatari.js
  engine/hatari/hatari.wasm
  engine/hatari/hatari.data

If you already have those files in your current repo, keep them there. Do not move them.

GitHub Pages:
- Upload the contents of the TonyRetro_Multi_Emulator_v0_1 folder, not the zip and not the folder itself.
- Make sure index.html is in the repo root.
- Make sure .nojekyll is in the repo root.
- Open your Pages URL and add to iPhone Home Screen.

Legal:
- No commercial ROMs or copyrighted BIOS files are included.
- Import your own local files privately inside each system module.
