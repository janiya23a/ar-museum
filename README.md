# Mini Museum AR - The Avocado Exhibit

A marker-based AR scene built with A-Frame + AR.js. Point your phone camera at the Hiro marker to see a mini museum exhibit.

## Live demo
https://YOUR-USERNAME.github.io/YOUR-REPO/

## How to use
1. Open the live link on a phone (HTTPS, allow camera).
2. Show the Hiro marker: https://ar-js-org.github.io/AR.js/data/images/hiro.png
3. Tap the ball to change its colour.
4. Tap the orange box to grow / shrink it.
5. Banner at the top turns green when the marker is found and red when lost.

## Features
- Hiro marker scene: cylinder, box, sphere, torus, glTF model + `<a-text>` label
- Animations: ball position bob, torus rotation, avocado rotation
- Interaction: `ball-color` (workshop) + `grow-toggle` (own custom component)
- Status banner via `marker-status` component (markerFound / markerLost)
- Hosted on GitHub Pages (HTTPS)

## Credits / Licences
- 3D model: **Avocado** by Microsoft - licensed CC0 1.0 Universal (public domain).
  Source: https://github.com/KhronosGroup/glTF-Sample-Models/tree/main/2.0/Avocado
- A-Frame (MIT): https://aframe.io
- AR.js (MIT): https://github.com/AR-js-org/AR.js
