<div align="center">
  <img width="680" alt="DRH - Rock Studio banner" src="docs/media/Logo.png" />
</div>

<br>

<div align="center">

# DRH - Rock Studio

### Support · Documentation · Feedback · Development On-Hold

Procedural rock generation with Mesh and Geometry Nodes workflows, advanced distributions, and surface scatter tools.

![Status](https://img.shields.io/badge/status-In%20Development%20%5BOn-Hold%5D-7C3AED?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-00B7FF?style=for-the-badge)
![Blender](https://img.shields.io/badge/blender-4.2%2B-0B1F4D?style=for-the-badge)
![Platforms](https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux-EAF2FF?style=for-the-badge&labelColor=0B1F4D&color=EAF2FF)

<br>

DRH Blender Tools: support, documentation, and release information.

[![DRH Add-ons Hub](https://img.shields.io/badge/DRH%20Add--ons%20Hub-Visit%20Hub-1E5BFF?style=for-the-badge&labelColor=0B1F4D)](https://github.com/pacosalasv/DRH_Addons_Hub)

</div>

---

<div align="center">

DRH - Rock Studio helps Blender users generate procedural rock assets as Mesh objects or Geometry Nodes setups, then arrange them using predefined 2D and 3D placement patterns.

This repository tracks documentation, support, compatibility reports, and development notes while active development is on hold.

</div>

---

## Overview

DRH - Rock Studio is a Blender workflow utility designed to help users create procedural rock assets, choose between Mesh or Geometry Nodes output, explore shape variations, and arrange rocks using predefined 2D and 3D placement layouts.

It is intended for environment artists, asset creators, game artists, procedural artists, scene builders, and Blender users who need rock forms for natural scenes, terrains, props, kitbashing, scattering layouts, or visual development.

Instead of modeling every rock manually from scratch or arranging assets one by one, DRH - Rock Studio helps turn rock creation and placement into a faster, more adjustable, and repeatable workflow.

## Media preview

<!--
<div align="center">
  <img width="920" alt="DRH - Color Ramp Studio feature preview showing palette generation, native editable conversion, curated presets, and precision editing tools" src="docs/media/Featured_Image.png" />
</div>
-->

### Screenshots

<div align="center">

| Rock Generation and Placement | Shape and Surface Controls |
|---|---|
| <img height="420" alt="Rock Generation and Placement" src="docs/media/ScreenShot_01.png" /> | <img height="420" alt="Shape and Surface Controls" src="docs/media/ScreenShot_02.png" /> |

</div>

<details>

  <summary><strong>More Screenshots...</strong></summary>

<div align="center">

| Rock Studio Settings | Generated Rock Pattern Preview |
|:---:|:---:|
| <img height="420" alt="Rock Studio Settings" src="docs/media/ScreenShot_03.png" /> | <img height="420" alt="Generated Rock Pattern Preview" src="docs/media/ScreenShot_04.png" /> |

</div>

</details>


---

## What DRH - Rock Studio does

DRH - Rock Studio helps you create, configure, and arrange rock assets directly inside Blender.

It is not only a simple object preset tool. It is designed as a workflow helper for generating rock forms, choosing between Mesh or Geometry Nodes output, creating variations, and placing rock arrangements using predefined 2D and 3D layouts.

Use it to:

| Details |
|---|
| Generate rock assets faster |
| Create rocks as Mesh objects |
| Create rocks as Geometry Nodes setups |
| Build natural-looking shape variations |
| Use predefined 2D placement arrangements |
| Use predefined 3D placement arrangements |
| Explore procedural rock forms |
| Build environment props and terrain details |
| Reduce repetitive manual modeling and placement work |
| Create reusable rock variations for scenes |
| Support asset creation for games, renders, kitbashing, or BlendKit-style workflows |

---

### Capabilities

| Details |
|---|
| Generate procedural rocks as Mesh or Geometry Nodes assets |
| Massive placement system with 2D, 3D, and on-surface scatter workflows |
| Ready-made rock presets for rapid environment production |
| Procedural variation controls for more natural and less repetitive sets |
| Surface scatter and drop tools for faster scene dressing |
| Auto Apply and manual Apply Changes workflow for heavy rebuild safety |
| User preset storage on disk and inside the blend file |
| LOD and preview density controls to balance speed and detail |

---

<details>
  <summary>Feature reference</summary>

## Feature reference

### Generation modes
| Details |
|---|
| Mesh generation mode |
| Geometry Nodes generation mode |
| Preview density: Full |
| Preview density: Draft |
| Preview density: Ultra Draft |
| First-rock generation workflow |
| Batch regeneration workflow |

### Rock presets and profiles
| Details |
|---|
| Preset: Asteroid |
| Preset: Basalt Rock |
| Preset: Boulder |
| Preset: Chalk |
| Preset: Cliff |
| Preset: Cliff Formation |
| Preset: Craggy |
| Preset: Deformed Conglomerate |
| Preset: Ground Scatter |
| Preset: Hero Rock |
| Preset: Ice |
| Preset: Low Poly |
| Preset: Marble |
| Preset: Monolith |
| Preset: Obsidian |
| Preset: Pebble |
| Preset: Pumice |
| Preset: Quarry Set |
| Preset: Reef Cluster |
| Preset: Reef Outcrop |
| Preset: River Rock |
| Preset: Sandstone |
| Preset: Sea Stack |
| Preset: Shard |
| Preset: Shelly Limestone |
| Preset: Slate |
| Preset: Smooth Boulder |
| Variation profile: Hero |
| Variation profile: Debris |
| Variation profile: Cliff |
| Variation profile: Shard |
| Variation profile: Pebble |
| Randomize shape |
| Randomize placement |
| Randomize surface |
| Seed history and randomization workflow |

### Base shapes and surface style
| Details |
|---|
| Base shape: Cone |
| Base shape: Cube |
| Base shape: Cylinder |
| Base shape: Icosphere |
| Base shape: Octahedron |
| Base shape: Quad Sphere |
| Base shape: Tetrahedron |
| Base shape: UV Sphere |
| Material style: Basalt |
| Material style: Strata |
| Material style: Moss |
| Material style: Ice |
| Material style: Volcanic |
| LOD: Low |
| LOD: Balanced |
| LOD: High |
| LOD: Ultra |

### Placement and scatter
| Details |
|---|
| Scatter mode: Pattern |
| Scatter mode: On Surface |
| 2D pattern: Random |
| 2D pattern: Arc |
| 2D pattern: Circle |
| 2D pattern: Cluster |
| 2D pattern: Diamond |
| 2D pattern: Ellipse |
| 2D pattern: Fractal |
| 2D pattern: Grid |
| 2D pattern: Hexagonal |
| 2D pattern: Honeycomb Trim |
| 2D pattern: Lemniscate |
| 2D pattern: Linear |
| 2D pattern: Multi Ring |
| 2D pattern: Poisson Disk |
| 2D pattern: Progressive Rotation |
| 2D pattern: Progressive Scale |
| 2D pattern: Radial |
| 2D pattern: Random Grid |
| 2D pattern: Rosette |
| 2D pattern: Spiral |
| 2D pattern: Star |
| 2D pattern: Triangular |
| 2D pattern: Wave |
| 2D pattern: Zigzag |
| 3D pattern: Cluster 3D |
| 3D pattern: Cone 3D |
| 3D pattern: Cylinder 3D |
| 3D pattern: Dome 3D |
| 3D pattern: Ellipsoid 3D |
| 3D pattern: Explosion 3D |
| 3D pattern: Grid 3D |
| 3D pattern: Helix |
| 3D pattern: Layered Sphere 3D |
| 3D pattern: Lissajous 3D |
| 3D pattern: Prism 3D |
| 3D pattern: Pyramid 3D |
| 3D pattern: Shell 3D |
| 3D pattern: Spheric 3D |
| 3D pattern: Stacked Rings 3D |
| 3D pattern: Torus 3D |
| 3D pattern: Vortex 3D |
| Use active surface target |
| Drop active object to ground |
| Drop selected objects to ground |

### Workflow controls
| Details |
|---|
| Apply Changes |
| Auto Apply Changes toggle |
| Regenerate Batch |
| Reset active defaults |
| Reset scene defaults |
| Reset Geometry Nodes parameters |

### Presets and storage
| Details |
|---|
| Save user presets |
| Load user presets |
| Delete user presets |
| Open preset directory |
| Export preset pack |
| Store presets on disk |
| Store presets inside the blend file |

### UI and integration
| Details |
|---|
| Build tab |
| Form tab |
| Settings tab |
| Optional Add > Mesh menu entry |
| Sidebar category rename |
| Preferences integration |

</details>

---

## Intended users

DRH - Rock Studio is designed for:

| Details |
|---|
| Environment artists |
| Blender asset creators |
| Game artists |
| Procedural artists |
| Geometry Nodes users |
| Scene builders |
| Kitbash creators |
| BlendKit creators |
| Natural environment artists |
| Stylized rendering artists |
| Technical artists |
| Users who need reusable rock assets, variations, placement presets, or environment props |

---

## Status

| Item | Details |
|---|---|
| Status | 🟣 In Development [On-Hold] |
| Current version | 1.0.0 |
| Minimum Blender version | 4.2.0 |
| Platforms | Windows, macOS, Linux |
| Release type | In development before public marketplace release |
| Support repository | [DRH Rock Studio Support](https://github.com/pacosalasv/DRH_Rock_Studio-Support) |

This add-on is currently in development. Compatibility feedback, usability comments, feature expectations, and workflow suggestions are welcome before public release.

---

## Technical notes

This add-on is source based, with:

- No obfuscation
- No binary-only content
- No external services
- No account requirements

Local system access may be used only for normal Blender workflows such as saving files, loading assets, exporting data, or using project resources when applicable.

The add-on is intended to work locally inside Blender.

---

## Availability

This add-on may be available through multiple marketplaces and storefronts after release.

This GitHub repository remains the central public location for:

| Details |
|---|
| Support |
| Documentation |
| Issue tracking |
| Compatibility reports |
| Public feedback |
| Release notes |

---

## Documentation

- [User Manual](docs/manual/user-manual.pdf)
- [Changelog](CHANGELOG.md)

---


## Support

Use [GitHub Discussions](https://github.com/pacosalasv/DRH_Rock_Studio-Support/discussions) for setup questions, workflow guidance, and general feedback. Use [GitHub Issues](https://github.com/pacosalasv/DRH_Rock_Studio-Support/issues/new/choose) for reproducible bugs, regressions, compatibility problems, and focused feature requests.

Do not post credentials, payment information, license keys, confidential production files, private client material, or sensitive local paths.

Detailed guidance is available in [SUPPORT.md](SUPPORT.md).

## Support DRH development

Development support is optional. Contributions through [Ko-fi](https://ko-fi.com/pacosalasv) help cover maintenance, Blender compatibility work, documentation, and testing.

## License

This repository is distributed under GPL-3.0-or-later.

---

<div align="center">
