# VR Therapy App — Asset Folder Structure

Place this alongside your `main_code.html` file.

## Folder Layout

```
your-app/
├── main_code.html
├── assets/
│   ├── hdr/
│   │   ├── nature/
│   │   │   ├── nature-meadow-1.hdr
│   │   │   ├── nature-meadow-2.hdr
│   │   │   ├── nature-forest-1.hdr
│   │   │   ├── nature-forest-2.hdr
│   │   │   ├── nature-hills-1.hdr
│   │   │   ├── nature-hills-2.hdr
│   │   │   ├── nature-river-1.hdr
│   │   │   ├── nature-river-2.hdr
│   │   │   ├── nature-field-1.hdr
│   │   │   └── nature-field-2.hdr
│   │   ├── space/          (space-nebula-1.hdr ... space-cosmic-2.hdr)
│   │   ├── ocean/          (ocean-sunset-1.hdr ... ocean-storm-2.hdr)
│   │   ├── forest/         (forest-dawn-1.hdr ... forest-redwood-2.hdr)
│   │   ├── mountains/      (mountain-sunrise-1.hdr ... mountain-sunset-2.hdr)
│   │   ├── desert/         (desert-dunes-1.hdr ... desert-mesa-2.hdr)
│   │   └── city/           (city-night-1.hdr ... city-sunset-2.hdr)
│   │
│   └── music/
│       ├── nature/
│       │   ├── ambient/        (nature-ambient-1.mp3, nature-ambient-2.mp3)
│       │   ├── classical/      (nature-classical-1.mp3, nature-classical-2.mp3)
│       │   ├── nature-sounds/  (nature-sounds-1.mp3, nature-sounds-2.mp3)
│       │   └── binaural/       (nature-binaural-1.mp3, nature-binaural-2.mp3)
│       ├── space/          (same subfolders: ambient, classical, nature-sounds, binaural)
│       ├── ocean/
│       ├── forest/
│       ├── mountains/
│       ├── desert/
│       └── city/
```

## Categories × Music Types

| Category   | Ambient | Classical | Nature Sounds | Binaural | Silence |
|------------|---------|-----------|---------------|----------|---------|
| Nature     | ✅      | ✅        | ✅            | ✅       | (no file needed) |
| Space      | ✅      | ✅        | ✅            | ✅       | (no file needed) |
| Ocean      | ✅      | ✅        | ✅            | ✅       | (no file needed) |
| Forest     | ✅      | ✅        | ✅            | ✅       | (no file needed) |
| Mountains  | ✅      | ✅        | ✅            | ✅       | (no file needed) |
| Desert     | ✅      | ✅        | ✅            | ✅       | (no file needed) |
| City       | ✅      | ✅        | ✅            | ✅       | (no file needed) |

**Total files needed:** 7 categories × 10 HDRs = **70 HDR files**
**Music:** 7 categories × 4 music types × 2 tracks = **56 music files**

## Notes
- HDR files can be `.hdr` or `.exr` (update the paths in ASSET_LIBRARY if using .exr)
- Free HDRs: https://polyhaven.com/hdris
- If a file is missing, the viewer will show a blank/dark environment — no crash
- "Silence" music type needs no files — the music player simply stays hidden
