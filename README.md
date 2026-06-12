# UK NTH Annual Technical Meeting 2026

This repository hosts the temporary GitHub Pages site for the UK NTH Annual Technical Meeting 2026.

The site uses plain HTML and CSS and does not require a build step. The suggested repository name is `uk-nth-atm-2026`.

## Update the programme

Edit `index.html` directly. Programme entries are grouped by day and session inside the `#programme` section. Each agenda item uses the `programme-item` class, with optional visual tags such as `tag-invited`, `tag-flash`, `tag-break`, `tag-lunch`, `tag-dinner`, `tag-panel`, and `tag-tbc`.

After making changes, open `index.html` in a browser to check the layout before publishing.

## Replace the draft agenda PDF

Place the agenda PDF in the `assets/` folder using this filename:

```text
assets/UK-NTH-ATM-2026-draft-agenda.pdf
```

Replacing the file while keeping the same filename will update the existing download button automatically. When the final agenda is ready, the button text and filename can also be updated in `index.html`.

## Enable GitHub Pages

1. Go to **Settings → Pages** in the GitHub repository.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Select the **main** branch.
4. Select the **/root** folder.
5. Save the settings.

GitHub will publish the site from the root-level `index.html`.
