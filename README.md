DD Produce — Tavasci Planting Map — Build 7

Upload index.html and tavasci-map.jpg to the root of the existing GitHub Pages repository.

New: Grid calibration mode for mouse and touch, three draggable handles, 1-pixel fine-adjust buttons, Show Grid, Save & Lock, Cancel, Reset.

Calibration uses a separate localStorage key (dd-tavasci-grid-calibration-v1), independent of the existing planting records. It is device/browser local; calibrate again on other devices if needed. Export a planting backup before updating.

Calibration maps the planting grid as a parallelogram (three-point affine transform), not an arbitrary four-corner perspective correction. Verify alignment at all four corners before saving.
