# Taste

## Tooling & Workflow

- Builds browser-based programming-language playgrounds as self-contained single-file static HTML pages (`index.html`, no build step), embedding the LiveCodes SDK loaded from a CDN. Confidence: 0.6
- Keeps one playground per language under `D:\DevWork\{language}-playground` (e.g. `crystal-playground`, `odin-playground`, `nim-playground`), each using LiveCodes with `appUrl: https://dev.livecodes.io` and offering a code playground, a dropdown of code samples, and a share-URL button. Confidence: 0.6

## Design & Communication

- Wants generated UIs styled to match the official project/language website, drawing on the real palette, fonts and logo rather than inventing a look. Confidence: 0.55
