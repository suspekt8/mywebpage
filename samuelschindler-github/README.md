# Samuel K. Schindler — static website

A GitHub-ready static version of the public website at `https://samuelschindler.org/`.

## What changed

- Converted the core public pages to plain HTML/CSS.
- Removed the homepage background image completely.
- Removed WordPress-specific comments, analytics markup, theme code, and other CMS dependencies.
- Made internal navigation work as static files suitable for GitHub Pages.
- Kept the design intentionally simple, responsive, and easy to edit.

## Pages

- `index.html` — Home
- `papers.html` — Papers (currently links to the original page because the source timed out during conversion)
- `books.html`
- `projects.html`
- `talks.html`
- `events.html`
- `teaching.html`
- `contact.html`
- `styles.css` — shared styling

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then save.

GitHub will provide the public Pages URL after deployment.

## Local preview

Open `index.html` directly in a browser, or run a small local web server from this folder, for example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Source note

This repository was prepared from publicly visible content on Samuel K. Schindler's website. Review the imported content and external links before publishing.
