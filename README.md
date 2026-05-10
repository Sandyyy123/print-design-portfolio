# Print Design Portfolio

Three client-grade print design pieces built programmatically - A3 clinical forms, industrial company profiles, and luxury real estate brand suites. All layouts are generated from source (HTML+CSS or Python) making them fully reproducible and easy to customise.

---

## 1. Clinical Monitoring Record (A3 Landscape)

**Format:** A3 landscape, 2 pages, print-ready vector PDF
**Renderer:** HTML + CSS via WeasyPrint
**Use case:** Phase 3 clinical trial cycle monitoring - daily stimulation grids, biomarker logs, procedure sign-off panels

**Highlights:**
- Day grid (1-8) with extension arrow and action threshold band
- Numeric biomarker rows (no graphs - spec-locked for scanning compatibility)
- Dual-sidebar layout: protocol info + medications
- Stacked procedure panels on page 2 (EPU, ET, Outcome, USS)
- Full typography system: Inter body, Source Serif Pro wordmark
- Photocopy-safe amber action band (~10% K-equivalent)

**Files:** `clinical-monitoring-record/`

---

## 2. Industrial Company Profile (4-Page Brochure)

**Format:** A4 portrait, 4 pages, print-ready vector PDF
**Renderer:** HTML + CSS via WeasyPrint
**Use case:** B2B company profile for a multi-division industrial services firm

**Highlights:**
- Cover page with tagline and capability overview
- Three-division structure: Industrial Doors, Loading Docks, Facility Safety
- Stats row, partner logos, case study panels
- Certification badges and contact block
- Translation-ready English copy (European procurement audience)

**Files:** `industrial-company-profile/`

---

## 3. Luxury Real Estate Brand Suite

**Format:** 11x17" bi-fold brochure + 9x6" direct-mail postcard
**Renderer:** Python (python-pptx) - outputs editable PPTX + PDF
**Use case:** Agent-branded print collateral for luxury property listings

**Highlights:**
- Gold/cream/black luxury palette (GOLD #C9A961)
- Playfair Display serif + Montserrat sans typography
- Bi-fold brochure: outside cover + inside property spread
- Postcard mailer: front hero + back contact/CTA layout
- Fully editable PPTX source - agents customise without a designer

**Files:** `real-estate-brand-suite/`

---

## 4. Clinical Form - Figma Source File

**Format:** Native Figma file (editable layers, auto-layout)
**Source:** Captured from HTML+CSS via Figma MCP (Code to Canvas)
**Use case:** Handoff-ready design file for the clinical monitoring record - every cell, label, font and colour is a live Figma layer

**Highlights:**
- Full auto-layout structure - resize any section without breaking the grid
- Typography, color styles, and spacing all editable natively in Figma
- Ready for DCE variant generation - duplicate frames and change variables
- Shareable with design teams via Figma link (no Figma account needed to view)

**Figma file:** Available on request.

---

## Tech Stack

| Tool | Purpose |
|---|---|
| HTML + CSS | Layout and typography for clinical and industrial pieces |
| WeasyPrint | HTML-to-PDF renderer (vector output) |
| python-pptx | PPTX generation for real estate suite |
| LibreOffice headless | PPTX-to-PDF conversion |

---

## Enquiries

These pieces are anonymised portfolio samples. If you need similar work - clinical data capture forms, company profile brochures, or branded print collateral - get in touch via GitHub.
