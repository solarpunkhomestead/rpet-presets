# rpet-presets

Demo m30ml project for modeling 3D printer slicer presets for recycled PET (rPET)

## Requirements

- git
- gradle
- npm

## Building project from cloned repo

### Clone and `cd` into repo

```bash
git clone https://github.com/solarpunkhomestead/rpet-presets.git
cd rpet-presets/
```

### Install dependencies

```bash
npm i
```

### Run build

```bash
npm run build
```

This will generate the following presets in the `build/` directory:

<!-- include (build/.buildTree lang=txt) -->
```txt
build
└── orcaslicer
    ├── filament
    │   └── KrogerPETE.json
    └── process
        └── PrusaMINIAlignedRectilinear.json
```
<!-- /include -->

