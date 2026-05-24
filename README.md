# Arithmetic in the Wild — Explainer

A single-page interactive walkthrough of [Feucht, Haklay et al. 2026, *Arithmetic in the Wild: Llama uses Base-10 Addition to Reason About Cyclic Concepts*](https://arxiv.org/abs/2605.01148).

Built for one focused reading session: covers the central claim (Llama-3.1-8B does base-10 addition, not modular arithmetic, for cyclic tasks), the four interpretability methods used (DAS, cross-task patching, Fourier probes, neuron ablations), and includes interactive visualizations of the mechanism, low-rank subspaces, Fourier-feature integer encodings, steering, and neuron clusters.

No build step — pure HTML + SVG + vanilla JS, with KaTeX from a CDN for the math.

## View locally

Just open `index.html` in a browser.
