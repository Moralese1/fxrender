# fxrender

GPU video renderer for Windows x64: a build of FFmpeg with the `fxcuda` CUDA filter plus the `fxrender.py` engine that drives it.

Current release: `fxrender-v1.6.2` (26.09.2026).

- Archive: `fxrender-win64-v1.6.2.zip` — `fxrender.py`, `bin/ffmpeg.exe`, `bin/ffprobe.exe`, `bin/libwinpthread-1.dll`, `bin/zlib1.dll`.
- SHA-256: `540dc053e9c779632dafde8c4cd149fb1d4258659232d69688a68af0e8a1c600`
- Requires an NVIDIA GPU, Turing or newer (compute capability 7.5+), with a current driver.
- All effects, transitions and subtitle masks run inside the `fxcuda` filter; still images use aspect-preserving scale-to-fill (scale + center crop).
- Verify the archive against `SHA256SUMS` before use.
