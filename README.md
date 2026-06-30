TonyRetro Multi Emulator v0.2

This does 1 to 3 from the plan:
1. Layout fix, systems now launch directly instead of being trapped inside an iframe wrapper.
2. Game Boy / Game Boy Color Labs module added.
3. Game Boy Advance Labs module added.

Upload the CONTENTS of this folder to the root of your GitHub Pages repo:
- index.html
- manifest.webmanifest
- .nojekyll
- systems/
- engine/

Do not upload:
- the zip itself
- the containing TonyRetro_Multi_Emulator_v0_2 folder

NES:
- Stable JSNES version, visible file picker, local library.

Atari ST:
- Uses your TonyST Hatari module.
- Copy your existing Hatari files to:
  engine/hatari/hatari.js
  engine/hatari/hatari.wasm
  engine/hatari/hatari.data

Game Boy / Game Boy Color:
- Labs module using EmulatorJS direct.
- Test with .gb first, then .gbc.

Game Boy Advance:
- Labs module using EmulatorJS direct.
- Test with a small .gba file first.

Honest bit:
NES and Atari ST are the proven modules.
GB/GBC and GBA are Labs modules because web cores can be fussy on iPhone.
No ROMs or copyrighted BIOS files are included.
