# Color Palette Generator

Simple web app that generates and copies color palette hex values.

## Files

- `index.html` - markup, palette structure, copy buttons, generate button
- `style.css` - styles for layout and controls
- `script.js` - palette generation, copy-to-clipboard, click handling

## How to run

1. Start a local server in project folder:
   - `python3 -m http.server 8000`
2. Open: `http://localhost:8000`

## Usage

- Click **Generate Palette** to randomize colors.
- Click a color or copy icon to copy its hex value to clipboard.

## Notes

- Ensure `style.css` is linked in `index.html`
- `generate-btn`, `.palette-container`, and `.color` classes must match in all files
- The app is tested on modern browsers with Clipboard API support.
