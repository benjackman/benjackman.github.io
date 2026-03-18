# Instructions for AI assistants

## Rendering the blog

- Always render the site from the **top-level directory** using `quarto render` (not individual pages like `quarto render tinkering/index.qmd`). Rendering individual pages causes CSS styling to not pass through correctly.
- After rendering, open the site from the top-level `docs/index.html` or navigate to the relevant page from there, so that styles and navigation work properly.
