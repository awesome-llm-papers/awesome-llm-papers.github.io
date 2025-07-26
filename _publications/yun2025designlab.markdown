---
layout: publication
title: 'Designlab: Designing Slides Through Iterative Detection And Correction'
authors: Jooyeol Yun, Heng Wang, Yotaro Shimose, Jaegul Choo, Shingo Takamatsu
conference: No Venue
year: 2025
bibkey: yun2025designlab
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.17202'}]
tags: ["Tools"]
short_authors: Yun et al.
---
Designing high-quality presentation slides can be challenging for non-experts due to the complexity involved in navigating various design choices. Numerous automated tools can suggest layouts and color schemes, yet often lack the ability to refine their own output, which is a key aspect in real-world workflows. We propose DesignLab, which separates the design process into two roles, the design reviewer, who identifies design-related issues, and the design contributor who corrects them. This decomposition enables an iterative loop where the reviewer continuously detects issues and the contributor corrects them, allowing a draft to be further polished with each iteration, reaching qualities that were unattainable. We fine-tune large language models for these roles and simulate intermediate drafts by introducing controlled perturbations, enabling the design reviewer learn design errors and the contributor learn how to fix them. Our experiments show that DesignLab outperforms existing design-generation methods, including a commercial tool, by embracing the iterative nature of designing which can result in polished, professional slides.

https://huggingface.co/discussions/paper/6881cb17df7c5aafaf37f0f6