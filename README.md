# HARVE · EMNLP 2026 project website

Static project page for **HARVE: Hacking-Aware Reward-Head Vector Editing for Robust Reward Models**. The design follows the SAEExplainer, Rep2Text, and UAV pages, with no top navigation or conference badge.

## Local preview

Run `python3 -m http.server 8003` in this folder, then open http://localhost:8003/. No build step is required.

## Files and sources

- `index.html`: authors, overview, benchmark, method, main results, and citation.
- `style.css`: shared project-site styling; `paper.css`: HARVE-specific layout.
- `script.js`: BibTeX copy interaction.
- `assets/framework.webp`: Figure 1 cropped from the supplied PDF; `assets/favicon.svg`: shared favicon.
- `3100_HARVE_Hacking_Aware_Rewar.pdf`: supplied paper, unchanged.

The supplied PDF is the source for authors, affiliations, figure, method, and numbers. Results refer to Table 1 (benchmark) and Table 2 (main evaluation). The PDF and [research code/data](https://github.com/olivialiu121/HARVE-Reward-Head-Editing) should be consulted for full settings. The public [arXiv page](https://arxiv.org/abs/2606.03131) was verified. EMNLP 2026 acceptance was provided by the author. No page numbers or ACL Anthology URL are invented in the provisional BibTeX.

## GitHub Pages

Website: https://mndu.github.io/harve/

Repository: https://github.com/mndu/harve

GitHub Pages deploys `main` from `/ (root)`. The website and supplied PDF are published with the author's permission.
