# Manufacturing outputs

These are the original project exports, retained as build evidence:

- `gerbers/`: seven layers covering front/back copper, front/back solder mask, front/back silkscreen, and the board outline.
- `gerbers/audiovisualiser-PTH.drl`: plated component holes.
- `gerbers/audiovisualiser-NPTH.drl`: non-plated mounting holes.
- `gerbers/audiovisualiser-job.gbrjob`: layer manifest and fabrication metadata.
- `bill-of-materials.csv`: reference designators, quantities, values, and footprints.
- `component-positions.csv`: original placement export.

The design BOM includes BR1 and a blue D6. The demonstrated build omitted BR1 and substituted a yellow D6; see the testing notes. These files have not been regenerated or requalified for a new production order. Open the Gerbers and drills together in KiCad Gerber Viewer before using them.
