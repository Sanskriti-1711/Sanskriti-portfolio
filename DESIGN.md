---
name: Sanskriti Shevgaonkar Portfolio
description: An evidence casebook for applied AI, software engineering, and technical writing.
colors:
  graphite: "#101714"
  panel: "#19231e"
  dossier-paper: "#f2ead8"
  signal-green: "#a8d977"
  evidence-blue: "#8ebad0"
  rust: "#db6b50"
  deep-blue: "#25495d"
typography:
  display:
    fontFamily: "Alegreya, Georgia, serif"
    fontSize: "clamp(3rem, 6vw, 5.4rem)"
    fontWeight: 600
    lineHeight: 1.08
    letterSpacing: "-.035em"
  body:
    fontFamily: "Work Sans, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "DM Mono, Consolas, monospace"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: 1.4
rounded:
  sm: "8px"
  md: "10px"
  lg: "14px"
components:
  button-primary:
    backgroundColor: "{colors.signal-green}"
    textColor: "{colors.graphite}"
    rounded: "{rounded.sm}"
    padding: "11.2px 16px"
    height: "46px"
---

# Design System: Sanskriti Shevgaonkar Portfolio

## Overview

**Creative North Star: "The Evidence Casebook"**

The portfolio is a graphite investigation console framing warm evidence plates. It blends Linux terminal cues, forensic case files, and a neural-network-inspired map, while keeping the interface grounded in real projects, experience, and writing.

The system should feel technical and investigative without becoming a generic neon dashboard. The evidence map is a portfolio index, not a machine-learning architecture; terminal-style labels describe real sources and sections, never fabricated system status.

**Key Characteristics:**
- Graphite surfaces and signal-green focus points.
- Warm paper plates for project evidence and dissertation imagery.
- Direct paths from work themes to real portfolio sections.
- Monospace reserved for compact metadata and labels.

## Colors

The palette pairs dark console surfaces with warm dossier paper, using green for active signals and blue for supporting evidence links.

### Primary
- **Graphite** (#101714): Main page background and dark action text.
- **Signal Green** (#a8d977): Primary actions, focus indicators, and selected network routes.

### Secondary
- **Evidence Blue** (#8ebad0): Links and supporting metadata on dark surfaces.
- **Rust** (#db6b50): Investigation marks and link accents on light evidence plates.

### Neutral
- **Graphite Panel** (#19231e): Navigation, map, and skip-link surfaces.
- **Dossier Paper** (#f2ead8): Project plates and evidence backgrounds.
- **Deep Blue** (#25495d): Contact section background.
- **Ink** (#edf1e9) and **Soft Ink** (#c2cdc4): Primary and secondary copy on dark surfaces.

**The Evidence-First Rule.** Color distinguishes navigation, context, and source material; it never substitutes for the evidence itself.

## Typography

**Display Font:** Alegreya (with Georgia, serif)
**Body Font:** Work Sans (with Arial, sans-serif)
**Label/Mono Font:** DM Mono (with Consolas, monospace)

**Character:** Alegreya gives the casebook a confident editorial voice; Work Sans keeps project and experience copy clear. DM Mono marks concise metadata, dates, and technical labels.

### Hierarchy
- **Display** (600, clamp(3rem, 6vw, 5.4rem), 1.08): The opening statement.
- **Headline** (600, clamp(2.15rem, 4vw, 3.35rem), 1.08): Major section titles.
- **Title** (600, clamp(1.55rem, 2.5vw, 2.05rem), 1.08): Project, role, and article titles.
- **Body** (400, 16px, 1.65): Explanations and evidence; measure is restrained where the layout defines a maximum width.
- **Label** (500, 12px, 1.4): Navigation, metadata, dates, and source labels.

## Layout

Bootstrap 5 provides the responsive container and grid; the page remains static HTML, CSS, and JavaScript. The hero pairs a concise profile with a large dissertation image, followed by a five-topic evidence map and vertically ordered case files.

The map uses five columns on wide screens and a connected vertical list on phones. Layout shifts at Bootstrap's 576px, 768px, and 992px breakpoints. Keep touch controls at least 44px tall and allow long project and experience copy to wrap naturally.

## Elevation & Depth

Depth is a restrained hybrid: graphite tonal layers separate interface regions, while warm evidence plates use offset, soft shadows to read as physical case material. Do not add glow or shadow to every surface.

### Shadow Vocabulary
- **Hero plate** (`12px 14px 32px rgba(0, 0, 0, .3)`): Lift the featured visual evidence.
- **Map panel** (`0 18px 36px rgba(0, 0, 0, .28)`): Separate the connected index from the page.
- **Case plate** (`8px 10px 24px rgba(0, 0, 0, .22)`): Add quiet depth to project evidence.

## Shapes

Controls and map panels use modest 8–14px corners. Evidence plates remain squared and paper-like. The root node alone uses a pill shape to mark the beginning of the map.

## Components

### Buttons
- **Shape:** 8px radius.
- **Primary:** Signal-green fill, graphite text, 11.2px by 16px padding, and 46px minimum height.
- **Hover / Focus:** Slight lift on hover; a clear signal-green outline for keyboard focus.
- **Secondary:** Text links use evidence blue on dark surfaces and remain visibly underlined or strongly weighted.

### Cards / Containers
- **Evidence plates:** Warm paper, graphite ink, compact source metadata, and direct links to project repositories.
- **Map panel:** Graphite panel with a dotted field, branching lines, and selectable topic nodes.
- **Shadow strategy:** Use the named roles above; avoid stacking additional decorative halos.

### Navigation
The desktop navigation is a compact DM Mono rail. On narrow screens it becomes a keyboard-operable menu with an explicit expanded state, Escape-to-close behavior, and focus restoration.

### Evidence Map
Each node links to a real section. Selecting a node highlights its route and announces the selected topic; no portfolio content is hidden. Reduced-motion preferences preserve the selected state without animated travel.

## Do's and Don'ts

### Do:
- **Do** connect every map node to real project, experience, or writing evidence.
- **Do** keep keyboard focus visible and retain the reduced-motion alternative.
- **Do** preserve factual claims, image credits, and useful image descriptions.

### Don't:
- **Don't** present the evidence map as a model architecture.
- **Don't** invent terminal output, system status, testimonials, or performance claims.
- **Don't** use monospace for long-form copy or add motion that competes with the work.
