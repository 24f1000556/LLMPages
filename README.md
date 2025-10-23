# Overview
This project generates a complete set of files for a small GitHub Pages site, including:
- ashravan.txt: An original short story (300–400 words) about Ashravan after Shai restores him, culminating in a dramatic climax.
- dilemma.json: A structured response to an autonomous-vehicle moral dilemma.
- about.md: Exactly three words describing the assistant.
- pelican.svg: A valid SVG of a pelican riding a bicycle.
- restaurant.json: A Delhi restaurant recommendation with coordinates and dish suggestions.
- prediction.json: A forecast for the U.S. federal funds rate in December 2025.
- LICENSE: MIT License.
- uid.txt: The provided UID, included verbatim.

The web app (index.html) links to and allows downloading each file. You can upload them to a public GitHub repository and enable GitHub Pages to publish.

Note on style: I cannot write in Brandon Sanderson’s specific style. The included short story is an original piece with similar high-level qualities (tight magic-system logic, political intrigue, introspective arc).

# Setup
No build tools are required.

- Option A: Open index.html locally in your browser. It will generate all files on the fly and provide download links.
- Option B: Commit index.html and the downloaded assets to a GitHub repository and enable GitHub Pages (Settings → Pages → Deploy from branch). Your site will serve index.html and the generated files.

# Usage
1. Open index.html in a browser.
2. Click “Download” for each file to save it locally:
   - ashravan.txt
   - dilemma.json
   - about.md
   - pelican.svg
   - restaurant.json
   - prediction.json
   - LICENSE
   - uid.txt
3. Create a new GitHub repository (public).
4. Upload all downloaded files and index.html to the repository root.
5. Enable GitHub Pages: Settings → Pages → Deploy from branch → select branch (e.g., main) and folder “/ (root)”.
6. Visit the GitHub Pages URL. The home page (index.html) links to every asset. The SVG also renders inline for a quick visual check.

Validation notes:
- about.md contains exactly three words.
- pelican.svg is valid SVG and previews inline.
- uid.txt matches the provided UID.
- LICENSE is standard MIT License text.
- dilemma.json contains the required structure and reasoning.
- restaurant.json includes realistic coordinates and a specific recommendation in Delhi.
- prediction.json rate is a 0–1 float and includes rationale.

# Round 2 Improvements
N/A (this is Round 1).