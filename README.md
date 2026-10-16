# Movado 3D watch experience

A minimal Three.js viewer that loads the original model at `Models/movado_gold_watch__photorealistic_3d_model.glb`. The GLB remains in the repository and is served from its existing path.

## Preview locally

From the repository root, run a local static server:

```sh
npx serve .
```

Open the URL printed by the server. An internet connection is required for the pinned Three.js modules and fonts from CDN. Drag with a mouse or touch to rotate the watch; release to let it coast into a slow idle turn.

If the model does not appear, check the browser console and open `/Models/movado_gold_watch__photorealistic_3d_model.glb` on the same local server. The server should return the GLB, not a 404 page.
