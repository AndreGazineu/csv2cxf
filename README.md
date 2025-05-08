Convert color lists from CSV to X-Rite CxF3 files—right in your browser.
csv2cxf is a zero-dependency, client-side web app that transforms simple CSV tables (name, L, a, b) into fully-featured CxF 3 color libraries, complete with D50/2° Lab values and optional tolerance sets for X-Rite eXact devices.

Why use it?

Offline & secure – All parsing and XML generation happen locally; your color data never leaves the browser.

Stand-alone – Pure HTML + JavaScript, no build step or server required; just open index.html.

Standards-compliant – Outputs valid CxF3 XML that imports cleanly into PantoneLIVE, ColorCert, InkFormulation and other QC software.

Extensible – Tweak the template literals to add metadata, illuminants, or extra color spaces.

Quick start

Clone or download the repo.

Open index.html in any modern browser.

Drop a CSV file formatted as

name,L,a,b
Red 485,53.12,75.23,42.91
Click “Convert & Download” to get <your-file>_convertido.cxf.

Roadmap

Batch-download ZIP archives for large color libraries

Drag-and-drop multiple CSVs

Optional ΔE94/ΔE00 tolerance presets
