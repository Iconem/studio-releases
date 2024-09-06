
## Steps to run studio webapp locally
- Retrieve dropbox link to the assets - shared privately
- Download `studio_assets`
- Unzip `build` folder so the `data` folder is at the same location than `fonts`, and `locales`, all folders should be at the root of the folder
- Serve `index.html`, e.g. via [http-server](https://www.npmjs.com/package/http-server)


## Project folder structure:

```
 studio /
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
