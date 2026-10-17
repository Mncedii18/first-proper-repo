# Simple Omelette — Frontend practice

A responsive, accessible recipe page demonstrating a small, well-styled HTML & CSS layout: a Simple Omelette recipe card built as a frontend practice project.

Live demo
- Open `index.html` locally in your browser, or serve the repository with a static server (instructions below).
- Tip: You can also publish this repository to GitHub Pages to get a public preview.

Features
- Clean, responsive layout for recipe content (ingredients, instructions, nutrition).
- Custom typography via Google Fonts.
- Semantic HTML and accessible headings/labels.
- Mobile-friendly breakpoints and CSS custom properties for theme colors.

Built with
- HTML5
- CSS3 (custom properties, responsive layout)
- Google Fonts (Outfit, Young Serif)

Repository structure
- index.html — the page markup and content
- style.css — all styling for the page
- assets/ (expected) — images and favicon referenced by the page (e.g., `assets/images/image-omelette.jpeg`)
- LICENSE — project license

How to run (shortest path)
1. Clone the repo:
   git clone https://github.com/Mncedii18/first-proper-repo.git
   cd first-proper-repo

2. Open locally (quick):
   - Double-click `index.html` or open it in your browser.

3. Serve with a simple static server (recommended for fonts/CORS parity):
   - Python 3:
     python -m http.server 8000
     # then open http://localhost:8000
   - Node (http-server):
     npx http-server -p 8000

Notes about required files
- index.html references `./assets/images/image-omelette.jpeg` and a favicon at `./assets/images/favicon-32x32.png`. If those files are missing, replace the src/href references or add images at those paths.

Customizing
- Edit content in `index.html` to change recipe name, ingredients, or instructions.
- Modify `style.css` to update colors, spacing, or responsive breakpoints.
- Replace the Google Fonts link in the head if you want different typography.

Contributing
- This is a personal practice project; contributions are welcome. Open an issue or submit a pull request with small, focused changes (styling fixes, improved accessibility, or adding tests/examples).

License
- See the LICENSE file in the repository.

Author
- Coded by Mncedisi Mzolo

Acknowledgements
- Layout and challenge inspired by frontend practice exercises (design credit as appropriate for any original assets).
