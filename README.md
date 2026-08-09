# ZeroCross

ZeroCross is a precision audio editor that runs locally in your browser. Import
audio, edit ranges and clips across as many as ten tracks, apply effects, save a
portable project, and export WAV or MP3 without sending source audio to an
application server.

Current release: **0.1.0**

[Open ZeroCross](https://97wobbler.github.io/zerocross/)

## What it does

- Imports audio formats supported by the browser.
- Provides waveform, range, clip, multitrack, Beat Grid, and silence-removal
  editing workflows.
- Applies non-destructive Clip effects and destructive Range effects.
- Saves new projects as `.zcross` files and opens legacy `.myaudition` files.
- Exports WAV and MP3 in the browser.
- Keeps project editing, recovery, and export data in the browser or in files
  you explicitly choose.

## Browser support and limits

The latest desktop Chrome is the primary supported browser. Large decoded audio
and project files can use substantial memory. ZeroCross currently has no
account, backend, cloud storage, collaboration, recording, microphone input, or
third-party plug-in hosting.

## Copyright and third-party material

ZeroCross application code is copyright © 2026 97Wobbler. All rights reserved.
See [COPYRIGHT.md](COPYRIGHT.md) for the application notice and
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for dependency licenses and
the Plate Reverb impulse-response attribution.

This repository is the public release and hosting repository. It contains the
static client build and public-facing documents, not the private development
source, engineering records, or development history. Browser-delivered
JavaScript remains inspectable as part of the distributed build.
