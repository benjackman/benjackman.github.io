# Instructions for AI assistants

## Rendering the blog

- Always render the site from the **top-level directory** using `quarto render` (not individual pages like `quarto render tinkering/index.qmd`). Rendering individual pages causes incorrect relative paths to shared CSS/JS assets. After a full-site render, any page can be opened directly (e.g., `docs/space_corner/index.html`).
