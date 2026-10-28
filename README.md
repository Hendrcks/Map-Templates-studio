# MapTemplate Studio — QGIS Plugin
<p align="center">
  <img src="logo.png" alt="MapTemplate Studio Logo" width="480"/>
</p>

> **A high-resolution, cartography-ready QGIS print layout template studio with 50 pure white templates across 14 layout architectures.**  
> *Developed by **Ariesplus Geospatial Solution***
<h1 align="center">MapTemplate Studio — QGIS Plugin</h1>

[![QGIS Compatibility](https://img.shields.io/badge/QGIS-3.28%2B%20%7C%204.x-589632.svg?logo=qgis&logoColor=white)](https://qgis.org)
[![Qt 5 & 6](https://img.shields.io/badge/Qt-5%20%26%206%20Compatible-41cd52.svg?logo=qt&logoColor=white)](https://qt.io)
[![License: GPL-2.0-or-later](https://img.shields.io/badge/License-GPL--2.0--or--later-blue.svg)](LICENSE)
[![Templates: CC-BY-4.0](https://img.shields.io/badge/Templates-CC--BY--4.0-orange.svg)](docs/LICENSE_REGISTER.csv)
[![Tests: 27 Passed](https://img.shields.io/badge/Tests-27%20Passed-success.svg)](tests/)
[![Author](https://img.shields.io/badge/Author-Ariesplus%20Geospatial%20Solution-0f172a.svg)](mailto:ariesplusgeo@gmail.com)
<p align="center">
  <strong>A high-resolution, cartography-ready QGIS print layout template studio with 60 pure white templates across 24 layout architectures.</strong><br/>
  <em>Developed by <strong>Ariesplus Geospatial Solution</strong></em>
</p>

<p align="center">
  <a href="https://qgis.org"><img src="https://img.shields.io/badge/QGIS-3.28%2B%20%7C%204.x-589632.svg?logo=qgis&logoColor=white" alt="QGIS Compatibility"/></a>
  <a href="https://qt.io"><img src="https://img.shields.io/badge/Qt-5%20%26%206%20Compatible-41cd52.svg?logo=qt&logoColor=white" alt="Qt 5 & 6"/></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-GPL--2.0--or--later-blue.svg" alt="License: GPL-2.0-or-later"/></a>
  <a href="docs/LICENSE_REGISTER.csv"><img src="https://img.shields.io/badge/Templates-60%20%7C%20CC--BY--4.0-orange.svg" alt="Templates: CC-BY-4.0"/></a>
  <a href="tests/"><img src="https://img.shields.io/badge/Tests-30%20Passed-success.svg" alt="Tests: 30 Passed"/></a>
  <a href="mailto:ariesplusgeo@gmail.com"><img src="https://img.shields.io/badge/Author-Ariesplus%20Geospatial%20Solution-0f172a.svg" alt="Author"/></a>
</p>

---

## 📌 Overview

**MapTemplate Studio** is a production-grade QGIS plugin developed by **Ariesplus Geospatial Solution**. It empowers GIS professionals, cartographers, urban planners, surveyors, researchers, and remote sensing analysts with an interactive, searchable gallery of **50 original print layout templates**.
**MapTemplate Studio** is a production-grade QGIS plugin developed by **Ariesplus Geospatial Solution**. It empowers GIS professionals, cartographers, urban planners, surveyors, researchers, and remote sensing analysts with an interactive, searchable gallery of **60 original print layout templates**.

All templates are designed with a **clean white cartographic theme** (`#ffffff` canvas, crisp dark slate `#334155` / `#0f172a` neatlines, and high-contrast charcoal typography) across **14 distinct layout architectures**—from formal cadastral survey sheets and executive KPI dashboards to twin-viewport multi-temporal comparisons and presentation slides.
All templates are designed with a **clean white cartographic theme** (`#ffffff` canvas, crisp dark slate `#334155` / `#0f172a` neatlines, and high-contrast charcoal typography) across **24 distinct layout architectures**—from open frameless study-area figures, four-panel municipal planning grids, and cadastral survey sheets with embedded key-plan insets to executive KPI dashboards, twin-viewport multi-temporal comparisons, and widescreen presentation slides.

---

## 🎨 Consistent with QGIS Software UI Theme

MapTemplate Studio is built to look, feel, and behave like an integrated component of QGIS Desktop:

- **Official Brand Identity**: Features the custom **MapTemplate Studio** layered-map north-arrow icon (`icon.png`) across toolbars, menus, and dialogs, alongside the studio banner (`logo.png`) in the dock header.
- **Adaptive Light & Dark Modes**: Dynamically detects the QGIS desktop palette (*Default Light* or *Night Mapping Dark*) and adjusts backgrounds, cards, text, and inputs accordingly.
- **Native QGIS Widgets**: Utilizes `QgsCollapsibleGroupBox`, `QgsFilterLineEdit` with live search and clear buttons, `QgsMapLayerComboBox` with native layer geometry icons, and `QgsFileWidget`.
- **QGIS Cartographic Brand Accents**: Clean QGIS green accenting (`#589632`), standard 6–8px padding, and responsive status pills.
- **Flexible Docking**: Operates as a native `QDockWidget` that docks into either side of QGIS or floats freely.

---

## 📐 14 Distinct Layout Architectures
## 📐 24 Distinct Layout Architectures

Every template is tailored to a specific communicative purpose, utilizing one of 14 architectural layouts:
Every template is tailored to a specific communicative purpose, utilizing one of 24 architectural compositions:

| Layout Architecture | Description | Target Use Cases |
| :--- | :--- | :--- |
| **Standard Hero Landscape** | Landscape map with dedicated top header block and bottom marginalia bar | Reference, administrative, environmental risk (`GEN-01`, `RS-01`, `ENV-01`) |
| **Corner Floating Full-Bleed** | Full-bleed map with floating white title card, legend card, and scale/north block | Continuous surfaces, NDVI, imagery indices (`RS-03`, `ENV-04`, `TER-05`) |
| **Left Rail Column** | Large map viewport on right, dedicated left column with regional locator map & legend | Regional growth, urban corridor redevelopment (`PLN-04`, `PLN-05`, `URB-01`) |
| **Right Rail Column** | Main map on left, dedicated right column with locator map, legend, and metadata | District profiles, emergency situation reports (`GEN-06`, `PLN-01`, `EMR-01`) |
| **Bottom Band Master** | Expansive A3/A2 master map on top with a 4-column marginalia panel below | Comprehensive master zoning, topographic contours (`PLN-02`, `TER-02`, `URB-03`) |
| **Minimal Portrait Figure** | Clean portrait figure with formal academic caption and figure numbering below | Theses, dissertations, peer-reviewed journals (`GEN-02`, `EDU-01`) |
| **Executive Report Portrait** | A4 portrait map with a 3-column bottom control panel (legend, scale, projection, source) | Municipal profiles, thermal surveys, social vulnerability (`GEN-03`, `RS-04`, `ENV-03`, `SOC-04`) |
| **Right Rail Portrait** | Portrait map with a dedicated right sidebar column for legend, north arrow, and stats | Multi-criteria suitability, population choropleths (`PLN-03`, `SOC-01`, `URB-02`) |
| **Cadastral Survey Plan** | Double neatlines (0.6mm outer, 0.25mm inner) with formal **Surveyor's Certificate & Seal Box** | Cadastral parcels, geodetic control sheets (`SUR-01`, `SUR-02`) |
| **Split Compare Horizontal** | Twin side-by-side synchronized viewports with baseline (T1) and observed (T2) headers | Before-and-after change, multi-sensor radar vs optical (`ATL-02`, `RS-02`, `RS-05`, `ENV-02`) |
| **Executive Dashboard** | Main map with territorial context map and **metric KPI indicator cards** with bold numerals | Asset governance, executive briefings, emergency sitreps (`GEN-05`, `EMR-04`) |
| **Atlas Series Sheet** | Dynamic map series sheet with `[% @atlas_pagename %]` and series locator index | Ward index, district atlas series (`ATL-01`, `ATL-03`) |
| **Widescreen 16:9 Slide** | 16:9 landscape format optimized for digital slide decks with right briefing card | Executive PowerPoint/Keynote briefings (`DIG-01`) |
| **Compact Briefing Card** | A5 landscape compact card with embedded legend and scale | Social media, web summaries, rapid briefs (`DIG-02`) |
| **Open Canvas + Bottom Title + Dual Right Stack** | Frameless primary study area on left with bottom title/scale bar and dual stacked right locator & legend | Administrative & regional context (`GEN-08`) |
| **Top Banner + Open Canvas + Dual Right Stack** | Framed top-left header above an open thematic map, paired with stacked right locator & legend | Demographic & socio-economic profiles (`SOC-05`) |
| **Dual Left Stack + Top Banner + Open Right Canvas** | Stacked left locator & legend panels paired with a top-bannered frameless study area on right | Academic & journal study-area figures (`EDU-03`) |
| **Four-Panel Municipal Planning Grid** | Dual-stacked left locator & legend column paired with a framed right map and bottom title bar | Municipal zoning & land management (`PLN-06`) |
| **Full-Height Left Specification Rail** | Continuous left rail (title, multi-class legend, notes) with framed right map and bottom scale bar | Ecological & environmental inventories (`ENV-06`) |
| **Framed Map + Bottom Bar + Full Right Rail** | Framed primary map and bottom title/scale strip on left with expansive full-height right legend rail | Geomorphology & stratigraphic units (`TER-06`) |
| **Full-Height Twin Epoch Comparison** | Maximized side-by-side twin viewports without top header overhead, anchored by a full-width bottom strip | Multi-temporal satellite change detection (`RS-07`) |
| **Captioned Twin-Panel Comparative Sheet** | Twin viewports with dedicated sub-panel caption band above a full-width bottom title & scale strip | Comparative atlas & before/after sheets (`ATL-04`) |
| **Wide Engineering Map + Abutting Footer + Right Rail** | Wide primary map above a deep engineering block abutting a full-height right symbology rail | Transport corridors & utility engineering (`URB-05`) |
| **Survey Master + Embedded Right-Rail Key Plan** | Wide survey viewport and aligned title block paired with a right rail containing an embedded key-plan inset | Cadastral & engineering master surveys (`SUR-04`) |

---

## 🗂️ Complete 50-Template Catalog
## 🗂️ Complete 60-Template Catalog

The 50 templates are categorized across **12 thematic families**:
The 60 templates are categorized across **12 thematic families**:

```text
├── General & Reference (7)        │ GEN-01 to GEN-07
├── Urban Planning & Zoning (5)    │ PLN-01 to PLN-05
├── Remote Sensing & Imagery (6)   │ RS-01 to RS-06
├── Environment & Hazard (5)       │ ENV-01 to ENV-05
├── Terrain & Geomorphology (5)    │ TER-01 to TER-05
├── Social & Demographics (4)      │ SOC-01 to SOC-04
├── Transport & Mobility (4)       │ URB-01 to URB-04
├── General & Reference (8)        │ GEN-01 to GEN-08
├── Urban Planning & Zoning (6)    │ PLN-01 to PLN-06
├── Remote Sensing & Imagery (7)   │ RS-01 to RS-07
├── Environment & Hazard (6)       │ ENV-01 to ENV-06
├── Terrain & Geomorphology (6)    │ TER-01 to TER-06
├── Social & Demographics (5)      │ SOC-01 to SOC-05
├── Transport & Mobility (5)       │ URB-01 to URB-05
├── Humanitarian & Emergency (4)   │ EMR-01 to EMR-04
├── Cadastral & Surveying (3)      │ SUR-01 to SUR-03
├── Atlas & Multi-Map (3)          │ ATL-01 to ATL-03
├── Academic & Publishing (2)      │ EDU-01 to EDU-02
├── Cadastral & Surveying (4)      │ SUR-01 to SUR-04
├── Atlas & Multi-Map (4)          │ ATL-01 to ATL-04
├── Academic & Publishing (3)      │ EDU-01 to EDU-03
└── Digital & Presentation (2)     │ DIG-01 to DIG-02
```

### 🆕 Newly Added Architectural Wireframe Series (10 Templates)

| ID | Template Name | Family | Archetype | Viewports |
| :--- | :--- | :--- | :--- | :--- |
| `GEN-08` | **Open Canvas Administrative & Locator** | General | Right Rail | `main_map` (frameless), `locator_map` |
| `SOC-05` | **Open Thematic Map with Dual Right Stack** | Social | Right Rail | `main_map` (frameless), `locator_map` |
| `EDU-03` | **Study Area Figure with Left Locator Stack** | Academic | Hero Map | `main_map` (frameless), `locator_map` |
| `PLN-06` | **Four-Panel Municipal Planning Sheet** | Planning | Hero Map | `main_map`, `locator_map` |
| `ENV-06` | **Left Specification Rail & Framed Map** | Environment | Hero Map | `main_map` |
| `TER-06` | **Geomorphology & Lithology Right Rail** | Terrain | Right Rail | `main_map` |
| `RS-07` | **Full-Height Twin Epoch Comparison** | Remote Sensing | Split Compare | `before_map`, `after_map` |
| `ATL-04` | **Captioned Twin-Panel Comparative Sheet** | Atlas | Split Compare | `before_map`, `after_map` |
| `URB-05` | **Infrastructure Engineering & Right Rail** | Transport | Right Rail | `main_map` |
| `SUR-04` | **Survey Master Sheet with Embedded Rail Inset** | Surveying | Right Rail | `main_map`, `locator_map` |

---

## 🚀 Key Features

### 1. Interactive Template Gallery Dock
- Real-time instant search by template name, keywords, author, or map roles.
- Filter by **12 Thematic Families**, **6 Page Archetypes**, and **Paper Sizes (A4, A3, A2, A5, 16:9)**.
- Quick-access **Favorites (Star)** and **Recently Used** sections.
- High-resolution thumbnails showing exact white cartographic layout geometry.

### 2. Four-Stage Guided Creation Wizard
- **Step 1: Template & Style**: Select template, view metadata, and choose your preferred paper size and orientation.
- **Step 2: Map Content & Roles**: Seamlessly bind active QGIS project layers to layout viewports (`main_map`, `locator_map`, `before_map`, `after_map`) with automated extent fitting (*Canvas*, *Layer*, or *Fixed Scale*) and margin padding.
- **Step 3: Cartography & Marginalia**: Configure Title, Subtitle, Sources, Surveyor/Author attribution, Date, CRS, dynamic scale bars, north arrows, and logos.
- **Step 3: Cartography & Marginalia**: Configure Title, Subtitle, Sources, Surveyor/Author attribution, Date, CRS, dynamic scale bars, north arrows, and organization logos.
- **Step 4: Preflight & Output**: Inspect real-time QA validation, view the readiness score, and generate the editable `QgsPrintLayout`.

### 3. Preflight Quality Assurance Engine
Automatic QA inspection prevents bad exports before they happen:
- Detects unmapped required map roles, empty extents, or broken linkages.
- Flags missing title, scale bar, north arrow, or projection metadata.
- Calculates an automated **Readiness Score (0–100%)** with clear Pass, Warning, and Blocker remediation instructions.

### 4. Production Multi-Format Exporter
Export directly with production presets or open the native composer:
- **Print PDF (300 DPI & 600 DPI)** with vector geometry preservation.
- **Geospatial PDF** with embedded georeferencing and layer trees.
- **Digital 4K & Full HD PNG** (3840×2160 / 1920×1080).
- **Scalable Vector Graphics (SVG)** and **GeoTIFF / High-Res TIFF**.
- Real-time raster memory safety estimator to prevent out-of-memory crashes on large plotters.

### 5. Custom Template Importer (.qpt)
- Safely inspects and imports third-party or organizational `.qpt` templates into your local library with path-traversal sandboxing.

### 6. 100% Offline-First
- Zero external cloud dependencies. All 50 templates, XML schemas, and preview assets are bundled locally.
- Zero external cloud dependencies. All 60 templates, XML schemas, brand graphics, and preview assets are bundled locally.

---

## 💻 Installation

### Method 1: Install from ZIP in QGIS (Recommended)
1. Download the latest release: [`maptemplate_studio.zip`](maptemplate_studio.zip).
2. In QGIS, navigate to **Plugins → Manage and Install Plugins...**.
3. Select **Install from ZIP** on the left menu.
4. Browse to the downloaded `maptemplate_studio.zip` file and click **Install Plugin**.
5. MapTemplate Studio will appear in your panels and toolbar!

### Method 2: Manual Directory Installation
Clone or copy the repository directly into your QGIS profile's plugin directory:

- **Windows**:
  ```powershell
  %APPDATA%\QGIS\QGIS4\profiles\default\python\plugins\maptemplate_studio
  ```
- **Linux**:
  ```bash
  ~/.local/share/QGIS/QGIS3/profiles/default/python/plugins/maptemplate_studio
  ```
- **macOS**:
  ```bash
  ~/Library/Application Support/QGIS/QGIS3/profiles/default/python/plugins/maptemplate_studio
  ```

---

## 🧪 Testing & Verification

The plugin includes a full unit test suite ensuring 100% reliability across headless environments:

```powershell
& "C:\Program Files\QGIS 4.2.1\bin\python-qgis.bat" -m unittest discover tests -v
```

**Results:** `27 tests passed` (0 errors, 0 failures), verifying:
- Schema validation for all 50 template manifests
- Search, filter, favorite, and recent caching logic
**Results:** `30 tests passed` (0 errors, 0 failures), verifying:
- Schema validation for all 60 template manifests, `.qpt` files, and `preview.png` thumbnails
- Brand icon (`icon.png`) and studio banner (`logo.png`) asset verification
- Search, filter, favorite, and recent caching logic across all 12 families
- Automated bounding box aspect-ratio calculations and margin expansion
- Non-destructive `QgsPrintLayout` generation and item role binding
- Non-destructive `QgsPrintLayout` generation and item role binding across classic and wireframe series templates
- Headless PDF and PNG generation
- Dark/light mode theme awareness

---

## 📁 Repository Structure

```text
MapTemplate Studio/
├── metadata.txt               # QGIS official plugin metadata (v1.0.1)
├── metadata.txt               # QGIS official plugin metadata (v1.1.0)
├── LICENSE                    # GNU General Public License v2.0+
├── README.md                  # Comprehensive plugin documentation
├── __init__.py                # QGIS classFactory initialization
├── main_plugin.py             # Plugin lifecycle, menu actions, toolbars
├── icon.png                   # High-res 64x64 QGIS-styled plugin icon
├── icon.png                   # High-res 128x128 MapTemplate Studio emblem icon
├── logo.png                   # High-res MapTemplate Studio full horizontal brand logo
│
├── core/                      # Headless core business logic
│   ├── catalog_service.py     # Discovers, indexes, and searches templates
│   ├── manifest_validator.py  # JSON Schema and integrity validation
│   ├── template_importer.py   # Sandboxed .qpt parser and custom template manager
│   ├── layout_factory.py      # Non-destructive QgsPrintLayout constructor
│   ├── role_binder.py         # Dynamic layer, legend, scale, and text binding
│   ├── extent_scale.py        # Frame-aspect extent fitting and scale calculation
│   ├── preflight.py           # Cartographic QA preflight engine
│   ├── exporter.py            # Multi-format production exporter
│   ├── asset_resolver.py      # Path and asset resolution
│   ├── asset_resolver.py      # Path, icon, logo, and asset resolution
│   └── settings_service.py    # Persistent user preferences (QgsSettings + JSON)
│
├── ui/                        # Native QGIS Theme UI Components
│   ├── theme.py               # Palette awareness, light/dark mode QSS, theme icons
│   ├── template_model.py      # TemplateCardWidget with thumbnails & pills
│   ├── gallery_dock.py        # Dockable gallery studio with category sidebar
│   ├── gallery_dock.py        # Dockable gallery studio with brand header & sidebar
│   ├── wizard_dialog.py       # 4-stage guided creation wizard
│   ├── preflight_dialog.py    # Cartographic QA preflight inspector
│   ├── export_dialog.py       # High-resolution production export dialog
│   └── import_template_dialog.py # Custom .qpt importer dialog
│
├── templates/                 # 50 Production-Grade Pure White Templates (GEN-01 ... DIG-02)
├── templates/                 # 60 Production-Grade Pure White Templates (GEN-01 ... SUR-04)
├── schema/                    # Manifest JSON Schema definition
├── styles/                    # Color tokens and cartographic standards
├── tests/                     # 27 automated unit tests
├── tests/                     # 30 automated unit tests
└── docs/                      # User guide, template authoring guide, license register
```

---

## 📄 License & Attribution

- **Developer**: **[Ariesplus Geospatial Solution](https://github.com/oseidesmondcms-eng/-MapTemplate-Studio)**  
- **Email**: `ariesplusgeo@gmail.com`  
- **Plugin Source Code**: Licensed under the [GNU General Public License v2.0 or later](LICENSE) (Copyright © 2026 Ariesplus Geospatial Solution).  
- **Template Layouts & Cartographic Assets**: Licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](docs/LICENSE_REGISTER.csv).
