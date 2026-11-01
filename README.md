DD Produce — Tavasci Planting Map, Build 7.4

This build uses the supplied Farm_map_experiment_1-main.zip.

Changes:
- Fixes JavaScript variable shadowing that prevented plant overlays, black borders, labels and outlet labels from rendering.
- Retains live plant age under the transplant date.
- Select one 36-row strip or a previously divided length section, then choose "Adjust planting length".
- Drag large START and FINISH handles with mouse or finger; Apply length. Existing plantings save immediately, new ones save when you save the planting operation.
- Stores approximate start/finish as percentages of full row length per planted section, without changing outlet identity or transplant date.
- Preserves the existing localStorage key and backup JSON structure (adds optional ranges per operation).
- Six-row mode remains available but is not being developed further.

IMPORTANT: Export your planting backup before replacing index.html. Browser data stays on that device, not in GitHub. Test with a sample planting before relying on the new controls.
