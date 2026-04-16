# Contrastive Learning — Interactive Demo

Interactive web demo for CS 5330 Assessment #2. Built to accompany a presentation on contrastive self-supervised learning via SimCLR.

**Live site:** [jsakuraa.github.io/contrastive-learning-demo](https://jsakuraa.github.io/contrastive-learning-demo)
**Slide Video** [YouTube](https://youtu.be/-oibWQ9iLXQ)

---

## What's in this repo

`index.html` — the entire site, single file, no dependencies, no build step.

---

## The three demos

**Embedding Space Visualizer** — Animates 60 points across 5 classes over 50 simulated training epochs. Shows how contrastive training pulls same-class embeddings together and pushes different classes apart, with a live NT-Xent loss estimate.

**Augmentation Playground** — Toggle augmentations (random crop, color jitter, gaussian blur, grayscale, horizontal flip) on and off and watch two views of the same image get constructed in real time. Demonstrates how positive pairs are formed.

**NT-Xent Loss Explorer** — Sliders for temperature τ, batch size N, and positive pair similarity. Live formula outputs and two charts showing how the loss responds to each parameter.

---

## References

- Chen et al. 2020 — _A Simple Framework for Contrastive Learning of Visual Representations_ — [arXiv:2002.05709](https://arxiv.org/abs/2002.05709)
- He et al. 2020 — _Momentum Contrast for Unsupervised Visual Representation Learning_ — [arXiv:1911.05722](https://arxiv.org/abs/1911.05722)
- Chopra et al. 2005 — _Learning a Similarity Metric Discriminatively, with Application to Face Verification_ — CVPR 2005
- Weng, L. 2021 — _Contrastive Representation Learning_ — [lilianweng.github.io](https://lilianweng.github.io/posts/2021-05-31-contrastive/)

---

## Acknowledgements

Built for CS 5330 Computer Vision, Assessment #2.

LLM use: Claude (Anthropic) was used to help build the interactive site. All written content and presentation decisions are my own.
