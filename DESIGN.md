---
name: ORBIT 2050
description: A0 print poster drawn as a power-grid single-line diagram
colors:
  drawing-paper: "#F2F3EF"
  line-ink: "#151617"
  annotation-gray: "#50555B"
  hairline: "#A9ADA8"
  overload-red: "#C8321F"
  orbit-blue: "#1565A8"
typography:
  display:
    fontFamily: "Barlow Condensed, Gothic A1, sans-serif"
    fontSize: "236pt"
    fontWeight: 700
    lineHeight: 0.8
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "Gothic A1, sans-serif"
    fontSize: "52pt"
    fontWeight: 900
    lineHeight: 1.15
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Gothic A1, sans-serif"
    fontSize: "29pt"
    fontWeight: 900
    lineHeight: 1.5
  body:
    fontFamily: "Gothic A1, sans-serif"
    fontSize: "20pt"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "Barlow Condensed, Gothic A1, sans-serif"
    fontSize: "14pt"
    fontWeight: 600
    letterSpacing: "0.04em"
rounded:
  none: "0"
spacing:
  section-gap: "8mm"
  sheet-margin: "40mm"
  frame-inset: "22mm"
components:
  section-rule:
    textColor: "{colors.line-ink}"
    padding: "3.5mm 0 0"
  table-cell:
    textColor: "{colors.line-ink}"
    rounded: "{rounded.none}"
    padding: "1.3mm 2.5mm"
  hold-tag:
    textColor: "{colors.overload-red}"
    rounded: "{rounded.none}"
    height: "9mm"
    width: "23mm"
---

# Design System: ORBIT 2050

## Overview

**Creative North Star: "The Single-Line Diagram"**

The poster is an electrical engineering drawing of AI's power problem. Every section reads as part of one drawing sheet: a zone-marked border frame, heavy section rules, a revision table, a component list, HOLD marks for unresolved items and a title block for the team. Information is drawn, not boxed. The ground grid and the orbit layer share one line language, so the argument (the 수도권 bus is overloaded, ORBIT adds a bus in orbit) is visible before any paragraph is read.

Density is that of a working drawing: many labelled elements, small but legible annotation, large quiet paper. Color is signal, never decoration. The world deliberately refuses the navy space poster with satellite art and rounded cards that the first drafts used.

**Key Characteristics:**
- Drawing-sheet frame with zone markers (1–8, A–F) and a 40 mm content margin
- Square corners everywhere; containers are ruled tables and frame lines, never cards
- Two signal colors on paper and ink: red for stress, blue for ORBIT
- Condensed technical lettering for numbers and labels, a plain Korean gothic for prose
- Vector only: no gradients, patterns or raster images

## Colors

Paper and ink carry everything; two signal colors mark meaning.

### Primary
- **Orbit Blue** (#1565A8): every ORBIT element — the orbit bus, solar panels, compute satellites, uplink and downlink, the "2050" in the title, the current revision row.

### Secondary
- **Overload Red** (#C8321F): stress and problems only — the overloaded 수도권 bus, AI data-center loads, the hook line, HOLD tags.

### Neutral
- **Drawing Paper** (#F2F3EF): the sheet ground, a cool off-white.
- **Line Ink** (#151617): all lines, symbols, rules and primary text.
- **Annotation Gray** (#50555B): secondary annotation, captions, citations (≈6.9:1 on paper).
- **Hairline** (#A9ADA8): light separators and removed/ghost elements.

### Named Rules
**The Signal Rule.** Red means stress, blue means ORBIT. Neither color is used for emphasis that does not carry that meaning.

**The Solid–Dashed Rule.** Solid lines are present-day fact; dashed lines are projection, optical links or removed items.

## Typography

**Display Font:** Barlow Condensed (with Gothic A1)
**Body Font:** Gothic A1 (with sans-serif)
**Label Font:** Barlow Condensed

**Character:** Condensed technical lettering like a drawing's title block, paired with a plain Korean gothic like a government engineering document. No Pretendard.

### Hierarchy
- **Display** (700, 236pt, 0.8): the project name "ORBIT 2050" only.
- **Headline** (900, 52pt, 1.15): the one-line concept under the title.
- **Title** (900, 29pt): section headings ① to ⑥.
- **Body** (400, 17.5–22pt, 1.5): prose, captions under diagrams, table cells.
- **Label** (600–700, 14pt and up): table headers, REV/No. columns, tags, figures and units; in SVG diagrams, labels run 5–9 mm.

### Named Rules
**The Lettering Rule.** Numbers, codes and units are set in Barlow Condensed; Korean sentences are set in Gothic A1.

## Layout

A0 portrait (841 × 1189 mm). A drawing frame sits 22 mm in (outer line) and 30 mm in (heavy line), with zone markers between. Content occupies 40–801 mm horizontally and 40–1149 mm vertically, in a single flex column with 8 mm gaps. Sections are separated by a 0.9 mm full-width rule, not by boxes. Two-column rows use a fixed left column (300–395 mm) and a 14 mm gutter. Diagrams are inline SVG whose viewBox units are millimetres.

## Elevation & Depth

Flat. No shadows anywhere. Depth comes from line weight: heavy rules and buses, medium symbols, hairline annotation.

## Shapes

Square corners only (0). Shapes are engineering symbols: circles for generators and transformers, triangles for loads, rectangles for panels and modules, circle balloons for numbered steps.

## Components

### Section Rule
A 0.9 mm ink rule across the full width, then the circled section number, the title (Title role) and a gray subtitle on one baseline.

### Ruled Table (revision table, component list, title block)
0.3–0.45 mm ink borders, no fill, square corners. Header cells in Barlow Condensed. The revision table strikes through superseded rows and colors the current row Orbit Blue.

### HOLD Tag
Red outlined rectangle (23 × 9 mm) with "HOLD n" in Barlow Condensed, beside an unresolved question.

### Diagram Symbols (signature)
Generator (circle with sine), transformer (two overlapping circles), bus (thick line, red or blue), load (line ending in a filled triangle), solar panel (rectangle with diagonal), ground station (dish on a mast), step balloon (5.5 mm circle with a number). A legend in section ① defines them.

## Do's and Don'ts

### Do:
- **Do** draw information as diagram, table or rule before reaching for a container.
- **Do** keep every figure traceable to a numbered reference.
- **Do** mark fictional examples as examples (e.g. "수용가 예시").
- **Do** keep all text at least 40 mm from the sheet edge.

### Don't:
- **Don't** use rounded cards, soft shadows or gradients (Chrome rasterizes gradients and patterns at low resolution).
- **Don't** use red or blue as decoration.
- **Don't** set the poster in Pretendard or another default UI sans.
- **Don't** add version labels or disclaimer footers to the sheet.
