---
layout: publication
title: 'Generate, But Verify: Reducing Hallucination In Vision-language Models With
  Retrospective Resampling'
authors: Tsung-han Wu, Heekyung Lee, Jiaxin Ge, Joseph E. Gonzalez, Trevor Darrell,
  David M. Chan
conference: No Venue
year: 2025
bibkey: wu2025generate
additional_links: [{name: Code, url: 'https://reverse-vlm.github.io'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/6801bcd684335da5c3e32db7'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2504.13169'}]
tags: ["Applications", "Datasets", "Ethics & Fairness", "Has Code", "Tools", "Training Techniques"]
short_authors: Wu et al.
---
Vision-Language Models (VLMs) excel at visual understanding but often suffer from visual hallucinations, where they generate descriptions of nonexistent objects, actions, or concepts, posing significant risks in safety-critical applications. Existing hallucination mitigation methods typically follow one of two paradigms: generation adjustment, which modifies decoding behavior to align text with visual inputs, and post-hoc verification, where external models assess and correct outputs. While effective, generation adjustment methods often rely on heuristics and lack correction mechanisms, while post-hoc verification is complicated, typically requiring multiple models and tending to reject outputs rather than refine them. In this work, we introduce REVERSE, a unified framework that integrates hallucination-aware training with on-the-fly self-verification. By leveraging a new hallucination-verification dataset containing over 1.3M semi-synthetic samples, along with a novel inference-time retrospective resampling technique, our approach enables VLMs to both detect hallucinations during generation and dynamically revise those hallucinations. Our evaluations show that REVERSE achieves state-of-the-art hallucination reduction, outperforming the best existing methods by up to 12% on CHAIR-MSCOCO and 28% on HaloQuest. Our dataset, model, and code are available at: https://reverse-vlm.github.io.

https://huggingface.co/discussions/paper/6801bcd684335da5c3e32db7