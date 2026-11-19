# StarLake LED Lighting

Professional LED lighting catalog for North American distributors, contractors, and OEM/ODM partners.

## Website

- 64 catalog families with individual product pages
- U.S. inventory pricing matched to 122 model/configuration options across 40 families
- Inquiry buttons for unpriced families
- Browser-local cart with quantities, totals, and email order inquiries
- Product specification sheets and complete catalog downloads
- Static hash routing; no backend, build step, or online payment required

## GitHub Pages deployment

The static site is designed for the project path `/starlake-led/`.

1. Upload the contents of the deployment package to the repository root, keeping `assets`, `brand`, `fonts`, `images`, and `specs` as top-level folders.
2. In **Settings → Pages**, select **Deploy from a branch**.
3. Select **main** and **/(root)**, then save.
4. Open `https://zshctt-a11y.github.io/starlake-led/` after GitHub finishes deployment.

Cart data is stored only in the visitor's current browser. Freight, taxes, stock, and final prices are confirmed by email.
