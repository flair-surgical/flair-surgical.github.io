# FLAIR

Project website for **Beyond Masks and Trajectories: Flow-Guided Latent Action Injection for Stable Surgical Video Generation**.

**[Project page](https://flair-surgical.github.io/)** · **[Paper](https://arxiv.org/abs/2610.09800)**

Tsz-Yui Qin*, Siyu Zhou*, Chi-Keung Tang, Yuxiang Nie†, Shu Yang†
The Hong Kong University of Science and Technology
\* Equal contribution. † Corresponding authors.

FLAIR learns action priors from optical flow during training and predicts those priors from text to guide surgical video generation. Only a text prompt is required at inference.

**Code — released soon.** This repository currently contains the project website, not the research implementation.

## Website

Static HTML, CSS, and JavaScript, deployed by GitHub Pages from the root of `main`. No build step is needed. To preview locally, serve this directory with any static web server.

- `index.html`: project content, publication metadata, and citation.
- `styles.css`: responsive layout.
- `script.js`: independent controls for all three visible animations, global play/pause, and citation copy.
- `assets/`: original supplied GIF comparisons, static preview frames, and figures extracted from the paper.
- `citation.bib`: downloadable BibTeX.

The displayed figures correspond to Figures 1–2 and Table 1 of arXiv:2610.09800v1. The three GIF comparisons are the author-provided demonstrations, copied without modification. All three appear as unified cards in a standalone Gallery section and play automatically, with LoRA labeled on the left and LoRA-FLAIR (ours) on the right. The display trims the GIFs' 32-pixel title strip to avoid duplicate labels; the original animated assets remain intact. Static previews respect reduced-motion preferences. Each comparison can be paused independently or all at once. Each author-supplied generation prompt appears as plain text above its video card, prefixed with "User Input:". An excerpt of the paper abstract introduces the gallery, followed by quantitative results before the method overview. The desktop layout is approximately 80% of its original scale, with GIFs independently reduced to 70% of their original display width; phone typography remains responsive.

The visual layout is inspired by [Follow-Your-Click](https://follow-your-click.github.io/): centered paper information, blue text links, white panels, and an open comparison gallery. The page includes publication metadata, canonical URLs, a sitemap, and structured research metadata for discoverability; these do not guarantee search-engine indexing or rankings.

## Citation

```bibtex
@misc{qin2026flair,
  title={Beyond Masks and Trajectories: Flow-Guided Latent Action
         Injection for Stable Surgical Video Generation},
  author={Tsz-Yui Qin and Siyu Zhou and Chi-Keung Tang
          and Yuxiang Nie and Shu Yang},
  year={2026},
  eprint={2610.09800},
  archivePrefix={arXiv},
  primaryClass={cs.CV},
  url={https://arxiv.org/abs/2610.09800}
}
```
