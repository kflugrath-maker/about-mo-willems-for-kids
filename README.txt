MEET MO WILLEMS! — SCHOOLOGY / GITHUB / ONCOURSE PACKAGE

FILES
- index.html = the complete interactive website
- .nojekyll = keeps GitHub Pages from applying unnecessary Jekyll processing
- README.txt = these notes

GITHUB PAGES
1. Create a public GitHub repository.
2. Upload index.html and .nojekyll to the top level (root).
3. Settings > Pages > Deploy from a branch.
4. Branch: main. Folder: /(root). Save.
5. GitHub Pages will publish the site at a github.io URL.

SCHOOLOGY
1. Keep index.html at the ZIP root.
2. Add Materials > Add Package > Web Content.
3. Upload this ZIP.
4. Submit.

ONCOURSE
Use the published GitHub Pages URL as a web link/resource in the lesson plan.

DESIGN / RELIABILITY
- No external JavaScript libraries are used.
- Uses responsive CSS for narrow iframe widths.
- Adds keyboard focus states and reduced-motion support.
- Images use HTTPS, async decoding, and fallback graphics if an external image host blocks the image.
- Read Aloud uses the browser's built-in speechSynthesis API and may depend on browser/device permissions.
- The site contains no student data or login information.
