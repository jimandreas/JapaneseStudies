# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A single-page Japanese vocabulary study tool (`index.html`) with no build system, frameworks, or dependencies. All CSS and JS are embedded inline. The app uses the Web Speech API for Japanese audio pronunciation.

## Architecture

- **`index.html`** — the entire application: HTML structure, embedded `<style>`, and embedded `<script>` containing both data arrays and all logic
- **`menuItems.json` / `gardenFeatures.json`** — reference data files (JS format with `const` declarations, not pure JSON). The data is duplicated inside `index.html` as inline arrays.
- **`ProgramRequirements.txt`** — original customer requirements document

## Key Design Decisions

- Data is embedded directly in the HTML file for zero-dependency offline use. If vocabulary data changes, update both the JSON reference files and the inline arrays in `index.html`.
- Audio uses `window.speechSynthesis` with `lang: "ja-JP"`. Requires a Japanese voice pack on the host OS.
- Uses Google Fonts CDN (`Noto Sans JP`) — this is the only external dependency and requires internet on first load.

## Running

Open `index.html` directly in a browser. No server or build step needed. Chrome/Edge recommended for Web Speech API support.
