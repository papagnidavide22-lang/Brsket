# Third-party notices

Brsket runs these programs and libraries, unmodified. Each remains under its own license.
The license texts are also inside the app, in `Brsket.app/Contents/Resources/Licenze`.

| Component | Version | License | Source |
| --- | --- | --- | --- |
| [FFmpeg](https://ffmpeg.org) (`ffmpeg`, `ffprobe`) | 9.0.2 | LGPL-2.1-or-later | Release asset, see below |
| LAME, libogg, libvorbis, libtheora, libvpx, libwebp, Opus, Snappy, Speex, GSM | see the file names in the sources archive | LGPL or BSD-style | Release asset, see below |
| [gallery-dl](https://github.com/mikf/gallery-dl) | 1.32.20 | GPL-2.0 | Release asset, see below |
| [yt-dlp](https://github.com/yt-dlp/yt-dlp) | 2026.10.21 | Unlicense | Upstream |
| [Deno](https://github.com/denoland/deno) | 2.9.8 | MIT | Upstream |
| [Demucs](https://github.com/adefossez/demucs) and the `htdemucs_6s` model | 4.1.0 | MIT | Upstream |
| [PyTorch](https://github.com/pytorch/pytorch) | 2.15.0 | BSD-3-Clause | Upstream |
| [ONNX Runtime](https://github.com/microsoft/onnxruntime) | 1.31.0 | MIT | Upstream |
| [NumPy](https://github.com/numpy/numpy) | 2.4.6 | BSD-3-Clause | Upstream |
| Python | 3.11 | PSF-2.0 | [python.org](https://www.python.org) |
| Kim_Vocal_2 voice model | | see the upstream project | [TRvlvr/model_repo](https://github.com/TRvlvr/model_repo) |
| [Hanken Grotesk](https://github.com/marcologous/hanken-grotesk) typeface | | SIL OFL 1.1 | Upstream |

## Source code for the LGPL and GPL components

Every release includes **Brsket-<version>-third-party-sources.zip**, with the exact source
archives of FFmpeg and the codecs built into it, and the gallery-dl code shipped in the app.

FFmpeg is built as separate programs in its LGPL configuration, without GPL or non-free
components. gallery-dl runs as a separate program. Brsket starts these tools and doesn't
modify them.
