# ProsperoPatches - PKG Link Extractor

A userscript that extracts all PKG download links from prosperopatches.com.

## Features

- **One-click extraction** – Opens a floating panel with all PKG links
- **Manual copy only** – Nothing is copied automatically
- **Bulk copy** – Copies all numbered pieces (`_0.pkg`, `_1.pkg`, etc.) – one link per line
- **Individual copy** – Copy any single link with one click
- **Auto-refresh** – Links update automatically when you open patch details
- **Draggable panel** – Move the panel anywhere on screen

## Installation

1. Install [Violentmonkey](https://violentmonkey.github.io/) or [Tampermonkey](https://www.tampermonkey.net/)
2. Click the raw `.user.js` file link below
3. Confirm installation

**[Download Script](https://github.com/Pippo26442999/ProsperoPatches-PKG-Link-Extractor/releases/download/v1.0/prosperopatches-pkg-extractor.user.js)**

## How to Use

1. Go to `prosperopatches.com`
2. Click the green **📦 button** (bottom-right corner)
3. Open any patch details (click "Details" or "Share")
4. All PKG links appear in the panel
5. Click **"MANUAL COPY"** to copy all numbered piece links

## What Gets Copied

Only links ending with `_0.pkg`, `_1.pkg`, `_2.pkg`, etc.

Extra files (DP, SC, CRC) are shown but **NOT** included in bulk copy.

## Requirements

- Violentmonkey or Tampermonkey
- A browser that supports userscripts (Chrome, Firefox, Edge, etc.)
