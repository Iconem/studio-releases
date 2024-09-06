public folder structure:

```
 public /
    └── $id.bundle.js
    └── $id.bundle.js.LICENSE.txt
    └── favicon.ico
    └── index.html
    └── data /
        └── experiences /
        └── models /
              ├── 3dtiles /
              |     └── All /
              |         └── ...
              |     └── Coupoles /
              |         └── ...
              |── focus /
              |   └── cupola /
              |         ├── mesh.bin
              |         └── ...
              ├── gltf /
              |     ├── mesh.bin
              |     ├── mesh.gltf
              |     ├── mesh.rcInfo
              |     ├── mesh.ktx2
              |     ├── 4k /
              |     |   ├── mesh.bin
              |     |   └── ...
              |     ├── 8k /
              |     |   ├── mesh.bin
              |     |   └── ...
              |     |   └── tomb /
              |     |         ├── mesh.bin
              |     |         └── ...
              |── bing_3dtiles /
              |   ├── tilesetRoot.json
              |   └── ...
        └── scenarios /
        └── thumbnails /
    └── fonts /
    └── locales /
```

Steps to run studio webapp locally:
- Retrieve dropbox link to the assets
- Download `studio_assets`
- Unzip `build` folder so the `data`, `fonts`, and `locales` folder are at the root of the folder
- Serve index.html
