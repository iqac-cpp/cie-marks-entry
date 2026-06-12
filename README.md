# CIE Marks Entry Portal - GitHub Pages Wrapper

Institution: GDC Cheepurupalli  
Project: Continuous Internal Evaluation Marks Entry Portal

## Purpose

This GitHub Pages version acts as a public landing page/wrapper for the official Google Apps Script Web App.

## Official Apps Script Web App URL

https://script.google.com/macros/s/AKfycbyBQv6sdtv0JWT1CrlYsk5ZsOYSML_-9EOYcS1RryEfAAviS0poBmHanR96U9Ob7jBP/exec

## Files in this package

- `index.html` - GitHub Pages landing page with iframe wrapper and direct app buttons.
- `README.md` - Setup notes.

## Upload Instructions

1. Create or open your GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. Go to repository `Settings`.
4. Open `Pages`.
5. Under `Build and deployment`, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Click `Save`.
7. Wait 1 to 3 minutes.
8. Open the GitHub Pages URL.

## Important

Do not upload the Apps Script `Index.html` from the Apps Script project directly to GitHub Pages because it uses `google.script.run`, which works only inside Apps Script.

This GitHub Pages wrapper keeps both links useful:

1. Apps Script Web App link - official working application.
2. GitHub Pages link - public wrapper page that opens/loads the same official application.

## If iframe does not load

Use the `Open Full App` button on the GitHub Pages page. The Apps Script link will still work.
