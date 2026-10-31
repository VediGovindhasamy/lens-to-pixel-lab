# Lens to Pixel Lab

Interactive 3D optics bench for camera-basics training: a near letter F and a far letter T, a lens with an adjustable iris, and a fixed 24 × 18-pixel sensor.

- Drag to orbit 360°, scroll to zoom
- Focus slides the lens (sensor stays fixed)
- Aperture changes only the light that continues from the iris to the sensor
- Green zone shows depth of field

Single file: `index.html`. Loads three.js r128 from cdnjs and OrbitControls from jsDelivr; no build step.
