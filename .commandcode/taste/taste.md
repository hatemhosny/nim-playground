# Taste

## Tooling & Workflow

- Builds browser-based programming-language playgrounds as self-contained single-file static HTML pages (`index.html`, no build step), embedding the LiveCodes SDK loaded from a CDN. Confidence: 0.6
- Keeps one playground per language under `D:\DevWork\{language}-playground` (e.g. `crystal-playground`, `odin-playground`, `nim-playground`), each using LiveCodes with `appUrl: https://dev.livecodes.io` and offering a code playground, a dropdown of code samples, and a share-URL button. Confidence: 0.6

## Design & Communication

- Wants generated UIs styled to match the official project/language website, drawing on the real palette, fonts and logo rather than inventing a look. Confidence: 0.55
- Cares about embedded widgets booting in the host page's theme rather than flashing a mismatched default — e.g. forcing the LiveCodes embed light via `params: { theme }` on `createPlayground` instead of accepting its dark loading splash. Confidence: 0.6
- Prefers a subdued, greyish accent color (e.g. `themeColor: "#6c757d"`) for embedded playground chrome rather than a strong on-brand color that clashes with the language's own palette. Confidence: 0.55
