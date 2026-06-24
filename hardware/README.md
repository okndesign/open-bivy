# hardware/

Design files for the bivy system. Everything here is licensed under [CERN-OHL-S-2.0](../LICENSE).

## Structure

```
hardware/
├── cad/        — parametric / digital design files
└── patterns/   — sewing patterns for fabric cutting
```

## cad/

Currently empty / placeholder. The base geometry has so far been designed directly as a vector pattern, not parametrically in a CAD tool. If you want to build a parametric version (e.g. to generate size variants for different body sizes), that would be a very welcome contribution — see [Open Problem #3](../README.md#open-problems).

**Planned / wanted:**
- A parametric pattern (Grasshopper, OpenSCAD, or similar) that takes body size as an input parameter
- An export pipeline to SVG/DXF for plotters or cutting plotters

## patterns/

Sewing pattern as a vector file (currently documented as reference measurements in [`docs/status.md`](../docs/status.md), original file to follow).

**Base section (core measurements):**
- Total length: 2100 mm (sleeping area) + 500 mm (head/storage space) = 2600 mm
- Width at head height: 1000 mm
- Head-end radius: 500 mm
- Allowance: 20 mm (Velcro fixing) + 20 mm seam allowance = 40 mm total

**Fabrication note:** This pattern is designed to be projection-friendly — i.e. it can be projected directly onto fabric with a projector + [patternprojector.com](https://patternprojector.com) (free, open-source tool). This entirely replaces paper templates and is the recommended method for building your own.

## Contributing to this folder

If you add files here:
- Note file formats in the filename or an accompanying `.md` (e.g. which CAD software/version)
- Add a short note for any new/changed file describing what changed (see CERN-OHL-S license condition 3.3.b)
- Prefer open, non-proprietary file formats (SVG, DXF, STEP) where possible, so nobody needs to buy a specific piece of software to contribute
