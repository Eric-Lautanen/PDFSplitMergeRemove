# PDF Split Merge Remove

**A clean, modern, browser-based PDF tool** — split documents into individual pages, merge multiple PDFs, or remove selected pages — **100% client-side** with no server upload required.

## Features

- **Split Engine** — Extract all pages or only selected pages from a PDF
- **Remove Engine** — Delete unwanted pages from a document (keep the ones you want)
- **Merge Engine** — Combine multiple PDF files into one
- Beautiful grid-based page preview with selection
- Real-time canvas rendering using pdf.js
- Processing powered by PDF-Lib (client-side)
- Clean modal download interface
- Toast notifications & responsive action bar
- Dark-mode friendly (assumes CSS variables)

## Tech Stack

- **HTML5 / CSS** (custom theme with CSS variables)
- **JavaScript (ES modules/async)**
- **pdf.js** — for fast page rendering & preview
- **PDF-Lib** — for actual PDF manipulation (split, merge, remove)
- No build tools / frameworks required — pure vanilla web app

## Demo

You can try a live version here:  
🔗 [https://Eric-Lautanen.github.io/PDFSplitMerge/](https://Eric-Lautanen.github.io/PDFSplitMerge/)  

## How to Use

1. Open `splitmerge.html` in a modern browser (Chrome, Edge, Firefox, Safari)
2. Choose a tab: **Split**, **Remove**, or **Merge**
3. Drag & drop or click to select PDF file(s)
4. Select/deselect pages (click on thumbnails)
5. Click **Process Files**
6. Download your resulting PDF(s) from the modal

## Local Development

```bash
# Just open the file
open splitmerge.html    # macOS
start splitmerge.html   # Windows
xdg-open splitmerge.html # Linux
