---
layout: publication
title: Fixing Data Augmentation To Improve Adversarial Robustness
authors: Sylvestre-alvise Rebuffi, Sven Gowal, Dan A. Calian, Florian Stimberg, Olivia
  Wiles, Timothy Mann
conference: Arxiv
year: 2021
bibkey: rebuffi2021fixing
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.01946'}]
tags: ["Security", "Training Techniques"]
short_authors: Rebuffi et al.
---
Adversarial training suffers from robust overfitting, a phenomenon where the
robust test accuracy starts to decrease during training. In this paper, we
focus on both heuristics-driven and data-driven augmentations as a means to
reduce robust overfitting. First, we demonstrate that, contrary to previous
findings, when combined with model weight averaging, data augmentation can
significantly boost robust accuracy. Second, we explore how state-of-the-art
generative models can be leveraged to artificially increase the size of the
training set and further improve adversarial robustness. Finally, we evaluate
our approach on CIFAR-10 against \\(\ell_\infty\\) and \\(ℓ₂\\) norm-bounded
perturbations of size \\(\epsilon = 8/255\\) and \\(\epsilon = 128/255\\),
respectively. We show large absolute improvements of +7.06% and +5.88% in
robust accuracy compared to previous state-of-the-art methods. In particular,
against \\(\ell_\infty\\) norm-bounded perturbations of size \\(\epsilon = 8/255\\),
our model reaches 64.20% robust accuracy without using any external data,
beating most prior works that use external data.