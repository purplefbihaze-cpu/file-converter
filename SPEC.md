# File Converter MVP — Spec

## Product
Privacy-first file converter. Runs 100% in the browser. No uploads, no server.
Tagline: "Your files never leave your browser."

## MVP Conversions (5)
1. **Image→PDF** — JPG/PNG/WebP to PDF (jsPDF + Canvas)
2. **PDF→Image** — PDF pages to PNG/JPG (pdf.js + Canvas)
3. **HEIC→JPG** — iPhone photos (libheif-js WASM)
4. **WebP↔PNG/JPG** — Canvas API native
5. **SVG→PNG** — Canvas API native

## Tech Stack
- Single `index.html` file
- Vanilla JS, no build tools
- CDN libraries (verified):
  - pdf.js: `https://cdnjs.cloudflare.com/ajax/libs/pdf.js/4.0.379/pdf.min.mjs`
  - jsPDF: `https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js`
  - libheif-js: `https://cdn.jsdelivr.net/npm/libheif-js@1.18.2/libheif/libheif.min.js`
  - JSZip: `https://cdnjs.cloudflare.com/ajax/libs/jszip/3.10.1/jszip.min.js`

## UX
- Drag & drop zone + file picker button
- Auto-detect input format → show available output formats
- Convert button → progress bar → download
- Batch: multiple files → ZIP download
- Mobile-friendly, responsive

## Design
- Clean, minimal (like Stundensatz-Rechner)
- Trust signals: "🔒 Your files never leave your browser"
- Show conversion count (social proof)
- Dark/light mode

## Open Source
- 100% free, unlimited conversions
- MIT License

## SEO
- Title: "Free Private File Converter — No Upload Required"
- Target: "convert heic to jpg online free", "pdf to image converter privacy"
