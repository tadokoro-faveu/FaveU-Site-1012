# FaveU Site — RealWorld OS top visual

Interactive 3D visual for the top page of [faveu.biz](https://faveu.biz/).

## What it shows

Scrolling moves the camera through three worlds:

1. **MACRO**: Lines spread from one dense source into an endless neural network. Floating memory blocks, information terminals and bounding boxes sit along the way, and neurons appear in the latter half.
2. **FLOW**: The lines break into a stream of event points along a time axis. Neuron trunks carry on toward the Earth.
3. **EARTH**: The points regroup into an Earth made of information. The camera passes through its warm core and out to the full globe. REALWORLD OS is at the center, and the five product lines form the hubs: Entertainment, Guard, Hospitality, Industrial and Intelligence. Drag to rotate.

The cursor acts as "YOU": nearby lines light up and carry event labels to it.

## Files

- `index.html`: a single self-contained page

## Running it

Open `index.html` in a browser, or serve the folder with any static server:

```sh
npx serve .
```

## Requirements

- WebGL
- An internet connection, because three.js r128 and Google Fonts (Archivo, IBM Plex Mono) load from public CDNs
- If the viewer prefers reduced motion, the scene renders without animation
