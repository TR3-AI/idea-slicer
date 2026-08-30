# Idea Slicer

Raw, scrambled thoughts in — parallel departments of work out.

- **Site:** https://tr3-ai.github.io/ideaslicer/
- **How it works:** every idea is a GitHub issue (label `idea`). Additions to an idea are new issues (label `thought`) linked to their parent. The agent skill `/ideaslicer` slices each idea into departments, keeps the issue body as the structured state (`maps/<slug>.md`), and regenerates the visual map page (`<slug>.html`) on every update.
- **Manifest:** `pages.json` — the index page and search bar read it at runtime.

Everything here is published straight to `main` by the agent; GitHub Pages serves it.
