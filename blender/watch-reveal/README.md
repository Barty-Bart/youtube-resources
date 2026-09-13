# Watch reveal — Blender scene

Download `watch-reveal.blend` and open it in Blender **5.2.1 LTS** (the version tested). No Higgsfield add-on, login or paid generation is required to open or render it.

This is the original simple 3D watch proxy and camera animation from the tutorial, not the photorealistic watch produced by Seedance. No generated Higgsfield video is included.

## Viewing and rendering

- Put your pointer over the 3D viewport and press Numpad 0 to enter camera view; alternatively use View → Cameras → Active Camera.
- Press Space to play. The timeline runs from frame 1 to 222 at 24 fps (9.25 seconds).
- Render a still with F12 or Render → Render Image. Use Render → Render Animation for the whole sequence.
- The scene uses Cycles and preview render settings. Increase resolution percentage and samples for final rendering.
- Output is relative to the file: `renders/frame-`. Set a writable output folder before rendering.

## What's included

Editable model, materials, lights, sequential sensor lights, three display states and animated camera. The camera opens above the rear sensor, aligns to neutral, pulls back, rotates continuously through the rear views, briefly pauses at the front faces and ends on the third face.

## Release audit

A clean copy was saved from v8 with factory-startup Blender and automatic script execution disabled. Audit found 56 scene objects, no embedded text scripts, no animation drivers, no linked libraries, no sound files, no external image textures and no custom properties. Render output was changed to a relative path. A final-frame render succeeded without the Higgsfield add-on loaded.

This is a creative reference scene, not a manufactured-product specification. A public reuse licence will be selected before public release.
