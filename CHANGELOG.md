# Changelog

## 2026-10-01

### Fixed

- Pin the web editor dependencies to MapLibre 5.24.0 so the CDN cannot select
  an incompatible MapLibre release and leave the viewer stuck loading.
- Reset the OpenDrive 3D Viewer panel to the right side on each page load instead
  of restoring obsolete drag coordinates from browser storage.
- Resolve the `tutorial.py` sample OpenDRIVE file relative to the script so the
  tutorial runs correctly from any working directory.
