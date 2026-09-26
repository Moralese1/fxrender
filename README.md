# fxrender CUDA runtime

Private pinned runtime package for Studio Pipeline Classic renderer.

Current release: `fxrender-v1.6.0` (26.09.2026).

- Archive: `fxrender-win64-v1.6.0.zip` — `fxrender.py`, `bin/ffmpeg.exe`, `bin/ffprobe.exe`, `bin/libwinpthread-1.dll`, `bin/zlib1.dll`.
- SHA-256: `19d404c2161ae6007c6ea3d53aabdb7c52e0dc551825ee72873bffb7609c3e53`
- New since v1.5.0: subtitle glow (`mask_glow`), per-word index mask, static masked layers (`still`), wavebar and voicebars overlays, `video_base`, `FXRENDER_VTRACK_NOREMUX`.
- CUDA effects remain inside the `fxcuda` filter.
- Still images use aspect-preserving scale-to-fill (`scale + center crop`), so portrait and square sources do not stretch or create black bars.
- The application verifies HTTPS, SHA-256, archive paths, FFmpeg startup, `fxcuda`, and a CUDA self-test before using the bundle.
- This repository contains no Studio Pipeline configuration, credentials, projects, prompts, media, or user data.
