# Images Folder Guide

All website images live here.

## Structure
```
images/
├── muyi.png                 # profile photo
├── schools/                # education logos
├── publications/           # paper images (one per paper)
└── design/                 # design projects (subfolders)
```

## Requirements
- Format: PNG or JPG
- Size: keep files reasonably small (< 1 MB recommended)
- Naming: meaningful and stable; for papers, use the exact paper title as file name

## Where to put
- Profile: `images/muyi.png`
- School logos: `images/schools/hku.png`, `images/schools/bjfu.png`
- Publications: `images/publications/<Exact Paper Title>.png`
- Design: `images/design/<project>/{cover.png, image1.png ...}`

Notes
- Transparent PNGs are rendered on white backgrounds in cards.
- Images are displayed using `object-fit: contain` to keep full content visible.
