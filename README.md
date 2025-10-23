# Ashravan Project — GitHub Pages Assets

## Overview
This project packages a small collection of downloadable assets as a simple web app:
- ashravan.txt — a 300–400 word original short story about Ashravan after Shai restores him, building to a dramatic climax.
- dilemma.json — an autonomous-vehicle ethical scenario with two cases and rationale.
- about.md — exactly three words describing the assistant.
- pelican.svg — a hand-authored SVG illustration of a pelican riding a bicycle (with an inline preview and an LLM rating blurb).
- restaurant.json — a Delhi restaurant recommendation with coordinates and a suggested dish.
- prediction.json — a reasonable forecast for the Federal Funds rate by December 2025.
- LICENSE — an MIT License file.
- uid.txt — the provided UID included verbatim.

All files are generated client-side via JavaScript and exposed as downloadable Blob links. This makes it trivial to host the entire bundle using GitHub Pages.

## Setup
1. Create a new public GitHub repository.
2. Add the two files from this project:
   - index.html
   - README.md
3. Commit and push to GitHub.
4. Enable GitHub Pages:
   - Go to Settings → Pages.
   - Set Source to “Deploy from a branch”.
   - Select the branch (e.g., main) and the root folder.
   - Save. Your site will be published at the provided URL.

## Usage
- Open the deployed GitHub Pages URL (or just open index.html locally).
- Use the Download links to save each file:
  - ashravan.txt (short story)
  - dilemma.json (AV ethics cases)
  - about.md (three words)
  - pelican.svg (SVG art; preview shown)
  - restaurant.json (Delhi recommendation)
  - prediction.json (Fed forecast)
  - LICENSE (MIT text)
  - uid.txt (verbatim UID)
- To persist these assets directly in your repo instead of downloading from the page:
  - Click each link to download the file.
  - Commit the downloaded files to your repository alongside index.html.
  - Your GitHub Pages site will then serve the assets as static files.

## Round Notes
Round 1 submission.