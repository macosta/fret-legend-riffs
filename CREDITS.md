# Credits

Every riff and lick here is original, written for Sustain Six.

- **Source:** Karoryfer Black And Green Guitars, "green" (Gretsch), `ord` and `stac` articulations, f layer (CC0-1.0),
  https://github.com/sfzinstruments/karoryfer.black-and-green-guitars.
- **Amps:** Neural Amp Modeler captures on TONE3000. Their T3K licence lets users publish the resulting outputs; the
  capture files are not redistributed and are not in this repo. Each file name carries its preset:
  - `tight_metal` = "Diezel VH4 ch3" by @petrc blended with "EVH 5150III 100W CH Red" by @ripper, through the Mesa 4x12
    impulse response from MIT JS Rocks (MIT licence).
  - `seventies_rock` = "Marshall Plexi Super Lead 1959 EL34" by @ripper
    (https://www.tone3000.com/tones/marshall-plexi-super-lead-1959-el34-40971) through the Marshall 1960 IR (MIT JS Rocks).
  - `classic_crunch` = "Marshall JCM 800 2203 - Crunch 2" by @sarcobe
    (https://www.tone3000.com/tones/marshall-jcm-800-2203-86089) through the same IR.
  - `clean_spring` = "Fender 68 Custom Deluxe Reverb - Full Rig" by @tannerc
    (https://www.tone3000.com/tones/fender-68-custom-deluxe-reverb-full-rig-64712), which includes its own miked
    cabinet, so no IR.
- **Our processing:** `scripts/tone/render_library.py` in the app repo: own-code boost, EQ, compressor, delay and
  Pedalboard reverb; levelled to -16 LUFS; folded to one exact loop per file. The app repo's `scripts/tone/sources.json`
  logs each licence and the date it was read.
