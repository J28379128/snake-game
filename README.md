# Interior Design KI Prototype

This repository contains a standalone HTML prototype (`index.html`) that illustrates the user journey for the conversational interior design KI assistant.

## Running the prototype

Because everything is bundled inside a single HTML file, there is no build step or dependency installation required. You have two easy options:

1. **Open the file directly**
   - Double-click `index.html`, or open it in your browser via `File` → `Open`.

2. **Serve it from a lightweight local server** (recommended for consistent asset loading)
   - Using Python 3:
     ```bash
     cd /path/to/repository
     python -m http.server 8000
     ```
   - Then visit <http://localhost:8000/index.html> in your browser.

If you see a blank page, make sure your browser allows local scripts to run. Serving over `http.server` avoids those security restrictions.

## Project files

- `index.html` – the interactive prototype with markup, styling, and JavaScript.
- `interior_design_ki.md` – product brief and planning notes for the KI experience.

## Known limitations

- The prototype does not connect to a real AI backend; chat responses are static placeholders meant to show the intended flow.
- File uploads are not processed; they exist to indicate where inspirational imagery would be provided in a future implementation.

