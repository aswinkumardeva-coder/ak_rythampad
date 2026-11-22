# AK Rhythm Pad and AK Shred

Two browser-based music apps by **Aswin Kumar**. No install, no server, works offline.

- **AK RHYTHM PAD** (`ak-rhythm-pad.html`): a DTX-style pad and loop machine.
- **AK SHRED** (`ak-shred.html`): a touch string instrument with glides, scale lock and a looper.

## AK Rhythm Pad

- 16 pads, 14 kits, a 16-step sequencer, tempo and volume knobs.
- Kits: EDM, Future Bass, Tamil Perc (thavil, tabla, parai, chenda), Loops, String Loops, Steel Drum (loops and fills), Vocal Loops, EDM Drums, Indian Fusion, Fashion, Indian Strings (veena, sitar, violin), Electro Drums, 808, Tabla & Mridangam.
- Choose a kit with the up and down arrow buttons beside the display (or the Up and Down keys).
- **REC**: press it, play pads, press it again and your playing loops. REC again adds layers, **LOOP** starts or stops it, **CLEAR** erases it.
- Keys: `1 2 3 4 / Q W E R / A S D F / Z X C V`. Space starts or stops. F11 is full screen in the desktop app.

## AK Shred

- Touch or drag on a string and slide to glide between notes. Move up or down for vibrato.
- Sounds: Shred Lead, Clean Guitar, Violin, Synth Lead, Indian Veena.
- Scales and keys, snap-to-scale, drive, delay, reverb, octave shift, gesture looper.

## Run it

Open `index.html` in a browser, or open either app file directly.

## Put it online with GitHub Pages

1. Upload these files to a repository.
2. Settings, then Pages, then Deploy from a branch, `main`, `/ (root)`.
3. Your site will be at `https://YOUR-NAME.github.io/REPO-NAME/`.

## Build the Windows app

On GitHub: Actions tab, then **Build Windows app**, then **Run workflow**. Or push a tag such as `v1.0.0` to also create a Release with the installer and portable .exe.

On your own PC (needs Node.js):

```
cd desktop
npm install
npm run dist
```

The .exe files appear in `desktop/dist`.

## License

Code: MIT, see `LICENSE`. Embedded audio clips: see `AUDIO-CREDITS.md`.
