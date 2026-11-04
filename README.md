# Sustain Six riff and lick loops

Audio for the Riffs and Licks pages of Sustain Six (https://sustainsix.com), served through jsDelivr:
`https://cdn.jsdelivr.net/gh/macosta/fret-legend-riffs/<version>/<file>`.

This repo holds every riff and lick added from item 17 on (2026-11-04). The first 16 items stay in
`macosta/fret-legend-samples/riffs/`, which also serves the app's guitar notes; riffs moved here so that repo
stays under jsDelivr's 150 MB per-repo limit.

## Files

`<version>/<item>_<preset>_<speed>_<version>.flac`, e.g. `v1/minor_gallop_e_tight_metal_50_v1.flac`: one riff or
lick, rendered alone at that percent of its tempo, 16-bit stereo 44.1 kHz FLAC (lossless, so the length is
sample-exact). Each file is EXACTLY one loop long; ring-out and effects tails are folded onto the head, so it loops
seamlessly. Rendered by `scripts/tone/render_library.py` in the app repo, which also writes the app's
`scripts/tone/riffs/manifest.json`.

**Never overwrite a published file name**: the URLs are unversioned. New audio gets a new version folder.

## Attribution and licences

See [CREDITS.md](CREDITS.md).
