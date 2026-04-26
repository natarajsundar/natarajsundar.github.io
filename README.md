# Minimal GitHub Pages site for a canonical paper page

This package gives you a very small personal site that is ready for GitHub Pages:

- `/index.html` - homepage
- `/publications/index.html` - publication index
- `/papers/chargebacks-agentic-ai/index.html` - dedicated paper page with visible abstract
- `/papers/chargebacks-agentic-ai/governed-agentic-automation-for-chargebacks-technical-report.pdf` - downloadable PDF (generated from the same content)

## Finalized author and contact details

These values are already set in the package:

- `Nataraj Agaram Sundar`
- `Tejas Morabia`
- `natsundar@ebay.com`
- `tmorabia@ebay.com`

## One value to update after you create the repo

Replace the base URL placeholder below with your actual GitHub Pages URL:

- `https://YOUR-GITHUB-USERNAME.github.io`

If you buy a custom domain later, replace the GitHub Pages URL with your final domain in:

- `/index.html`
- `/publications/index.html`
- `/papers/chargebacks-agentic-ai/index.html`
- `/robots.txt`
- `/sitemap.xml`

## Recommended GitHub Pages setup

1. Create a **public** GitHub repository.
2. The easiest option is to name the repo `YOUR-GITHUB-USERNAME.github.io` so the GitHub Pages base URL matches this package structure. Once the repo exists, replace the placeholder base URL with your actual GitHub Pages address.
3. Upload all files in this folder to the repository root.
4. In GitHub, go to **Settings -> Pages**.
5. Set the source to **Deploy from a branch**, using `main` and the `/ (root)` folder.
6. Wait for the site to publish.
7. After the site is live, verify it in Google Search Console and submit `/sitemap.xml`.

## Medium later

After the site is live, import the paper URL into Medium rather than pasting the text manually so Medium preserves the canonical link.

## Notes

- The paper page includes Google Scholar friendly repeated `citation_author` and `citation_*` meta tags for a two-author paper.
- The PDF is stored in the **same subdirectory** as the HTML abstract page, which aligns with Google Scholar's technical guidance.
