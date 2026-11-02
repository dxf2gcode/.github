# Profile examples

The screenshots show the current DXF2GCODE Qt interface with these example
drawings. They were rendered from the real MainWindow in an isolated profile,
using PyQt5 on 02 November 2026; no interface mockups or historical screenshots
were used. The screenshots use English labels for the international profile.

- `dxf2gcode-logo.dxf`: vector outlines derived from the project's own
  [logo SVG](https://github.com/dxf2gcode/dxf2gcode/blob/develop/source/dxf2gcode/presentation/qt/resources/images/dxf2gcode-logo.svg).
  Nominal SVG canvas width: 180 mm. Arial text is outlined, curves are sampled
  as polylines, and cutter decorations are clipped to the cutter silhouette.
  There are 46 closed contours on six layers; colour gradients are omitted.
  The same DXF is stored in the main checkout's `dxf/` test-file directory.
- `pocket.dxf`: a purpose-made, closed seven-sided milling example, in mm.
- `drag-knife.dxf`: a purpose-made, closed arrow contour, in mm.

The wordmark PNG is copied unchanged from the main project's image resources.
Screenshots include only these examples; the isolated profile log contains no
personal paths or recent-file lists. Original project and contribution
licensing applies to the project assets. The two simple geometric examples
were created specifically for this profile and may be reused with the project.

These DXFs illustrate geometry import and planning, rather than a configured
job for a particular machine. The website is maintained in `profile/README.md`.
