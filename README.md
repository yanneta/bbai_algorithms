# bbai_algorithms: DSA visualizations

Interactive, dependency-free visualizations for the Data Structures and Algorithm Design lectures. Each page is a single self-contained HTML file: no build step, no external libraries.

## Pages

| Page | Lecture | Description |
| --- | --- | --- |
| [`balanced-brackets/`](balanced-brackets/index.html) | 6. Stacks and queues | Step through the stack algorithm that checks balanced `()` and `[]` |

## Run locally

Open `index.html` in a browser. Nothing else is needed.

## Publish with GitHub Pages

1. Push this repository to GitHub (`yanneta/bbai_algorithms`).
2. In the repository, go to Settings, then Pages. Under "Build and deployment", set Source to "Deploy from a branch", choose `main` and `/ (root)`, and save.
3. After a minute, the site is live at `https://yanneta.github.io/bbai_algorithms/`.

## Use it in Moodle

Add a URL resource that points to the page, for example `https://yanneta.github.io/bbai_algorithms/balanced-brackets/`.

## Adding a new visualization

Create a new folder with its own `index.html`, then add a card for it in the root `index.html`.
