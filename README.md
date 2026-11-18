# GIF and Palette Limits Before an Upscale: 256 Colours, Measured at 1× to 8×

A GIF can hold 256 colours. Upscaling does not add any — it spreads them into bands. Measured with ffmpeg palettegen/paletteuse from 1x to 8x: band width grows 1.58 to 6.34 px entirely from detail the upscale invented, dither costs 1.22× the file at 1× and 2.78× at 8×, and quantising before the upscale is 3.43× larger for 1.77 dB it should not have earned.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-gif-palette-upscaling/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
