# fxrender CUDA runtime

Private pinned runtime package for Studio Pipeline Classic renderer.

Current release: `fxrender-v1.0.1`.

- CUDA effects remain inside the `fxcuda` filter.
- Still images use aspect-preserving scale-to-fill (`scale + center crop`), so portrait and square sources do not stretch or create black bars.
- The application verifies HTTPS, SHA-256, archive paths, FFmpeg startup, `fxcuda`, and a CUDA self-test before using the bundle.
- This repository contains no Studio Pipeline configuration, credentials, projects, prompts, media, or user data.
