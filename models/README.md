# Real 3D car models

1. Download a model in **glTF** format (`.glb`, or a `.gltf` with its files).
2. Put it in this folder, for example `skyline.glb`.
3. Add it to `models.json`, using the car's key from the game:

```json
{
  "skyline": {
    "file": "skyline.glb",
    "title": "Low Poly Nissan Skyline GT-R R34",
    "by": "Arifido._",
    "license": "CC BY 4.0",
    "url": "https://sketchfab.com/3d-models/low-poly-nissan-skyline-gt-r-r34-8ecbe8e4e432439fa7159d2e61f6bc9b"
  }
}
```

Optional: `rotY` (degrees, if the car faces the wrong way, default 90), `scale` (default 1.05),
`paint` (material name to recolor), `recolor: false` (keep the model's own colors).

Car keys: supra, eclipse, civic, s2000, maxima, skyline, evo, jetta, s240, s2000tran, r33, evo9, rx7, spyder, camaro, challenger, charger.
