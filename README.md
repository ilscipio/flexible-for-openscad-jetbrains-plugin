# Flexible For OpenSCAD

A JetBrains IDE plugin that brings full OpenSCAD language support to IntelliJ IDEA and the rest of the JetBrains product range — with a live interactive 3D preview, visual gizmo editing, smart completion, navigation, and code inspections. Design parts that are precise, parametric, and version-controlled, without leaving your IDE.

**Get it on the JetBrains Marketplace: [Flexible For OpenSCAD](https://plugins.jetbrains.com/plugin/32015-flexible-for-openscad)**

## Features

- **Language support** — syntax highlighting, code folding, brace matching, auto-closing quotes, a code formatter, and a structure view
- **Smart completion & docs** — built-in, keyword, and user-symbol completion, plus documentation on hover
- **Navigation & refactoring** — go to definition, find usages, rename, and cross-file `include`/`use` resolution
- **Code analysis** — inspections for unresolved includes, undefined references, argument arity, unused declarations, and performance hints, plus inline render errors from the OpenSCAD CLI
- **Interactive 3D preview** — rendered inside the IDE (no OpenSCAD executable required), with orbit controls, measurement tools, a cross-section clipping plane, an animation timeline, and source ↔ preview sync
- **Transform gizmos** — move/rotate/scale geometry and write the edit back into your source
- **Parametric Customizer & Outliner** — sliders/dropdowns from `// [..]` annotations, plus per-statement visibility and isolate toggles
- **STL viewer** — interactive WebGL `.stl` viewing
- **OpenSCAD integration (optional)** — with a local OpenSCAD install: export (STL, 3MF, AMF, DXF, SVG, PNG), external rendering, and open in OpenSCAD

## Installation

**From the JetBrains Marketplace (recommended)**

1. Open your JetBrains IDE
2. Go to **Settings → Plugins → Marketplace**
3. Search for **Flexible For OpenSCAD**
4. Click **Install** and restart the IDE when prompted

You can also install it directly from its [JetBrains Marketplace page](https://plugins.jetbrains.com/plugin/32015-flexible-for-openscad).

## Usage

1. Open or create a `.scad` file — it will show the OpenSCAD icon in the project tree
2. Edit with completion, navigation, and inspections; the live 3D preview renders inside the IDE as you save — no external tools required
3. Drag the gizmos to transform geometry, and add `// [min:max]` comments to get Customizer sliders
4. *(Optional)* Install [OpenSCAD](https://openscad.org/) (2021.01+) and set its path under **Settings → OpenSCAD** to export to STL/3MF/AMF/DXF/SVG/PNG and render via the OpenSCAD engine

## Requirements

- A JetBrains IDE, version **2023.3** or later
- **OpenSCAD 2021.01+** *(optional)* — only needed for export and external/CLI rendering; editing and the live 3D preview work without it

## Feedback & Community

We are a young project and we want to make this the best OpenSCAD experience in any JetBrains IDE. Bug reports, feature requests, and reviews are all very welcome — please open an issue here on GitHub or reach out to us. We're happy to hear from you.

## About Ilscipio

This plugin is built by [Ilscipio](https://www.ilscipio.com/), developers working across AI, e-commerce, and the JetBrains plugin ecosystem. We also offer custom plugin development, and special discounts for individual developers and the Open Source community.

- Website: [www.ilscipio.com](https://www.ilscipio.com/)
- AI compliance project: [aivory.net](https://aivory.net)
- Contact: [info@ilscipio.com](mailto:info@ilscipio.com)
