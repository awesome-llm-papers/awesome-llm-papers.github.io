---
layout: publication
title: Key-locked Rank One Editing For Text-to-image Personalization
authors: Yoad Tewel, Rinon Gal, Gal Chechik, Yuval Atzmon
conference: Special Interest Group on Computer Graphics and Interactive Techniques
  Conference Conference Proceedings
year: 2023
bibkey: tewel2023key
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.01644'}]
tags: ["Training Techniques"]
short_authors: Tewel et al.
---
Text-to-image models (T2I) offer a new level of flexibility by allowing users
to guide the creative process through natural language. However, personalizing
these models to align with user-provided visual concepts remains a challenging
problem. The task of T2I personalization poses multiple hard challenges, such
as maintaining high visual fidelity while allowing creative control, combining
multiple personalized concepts in a single image, and keeping a small model
size. We present Perfusion, a T2I personalization method that addresses these
challenges using dynamic rank-1 updates to the underlying T2I model. Perfusion
avoids overfitting by introducing a new mechanism that "locks" new concepts'
cross-attention Keys to their superordinate category. Additionally, we develop
a gated rank-1 approach that enables us to control the influence of a learned
concept during inference time and to combine multiple concepts. This allows
runtime-efficient balancing of visual-fidelity and textual-alignment with a
single 100KB trained model, which is five orders of magnitude smaller than the
current state of the art. Moreover, it can span different operating points
across the Pareto front without additional training. Finally, we show that
Perfusion outperforms strong baselines in both qualitative and quantitative
terms. Importantly, key-locking leads to novel results compared to traditional
approaches, allowing to portray personalized object interactions in
unprecedented ways, even in one-shot settings.