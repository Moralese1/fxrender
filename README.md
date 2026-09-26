# fxrender

GPU video renderer for Windows x64: a build of FFmpeg with the `fxcuda` CUDA filter plus the `fxrender.py` engine that drives it.

Current release: `fxrender-v1.6.1` (26.09.2026).

- Archive: `fxrender-win64-v1.6.1.zip` — `fxrender.py`, `bin/ffmpeg.exe`, `bin/ffprobe.exe`, `bin/libwinpthread-1.dll`, `bin/zlib1.dll`.
- SHA-256: `de06ee49f366ebebca9ef52a7eef2e1fd73895a36ab8a8dd3265b6d0e8f26c98`
- Requires an NVIDIA GPU, Turing or newer (compute capability 7.5+), with a current driver.
- All effects, transitions and subtitle masks run inside the `fxcuda` filter; still images use aspect-preserving scale-to-fill (scale + center crop).
- Verify the archive against `SHA256SUMS` before use.
