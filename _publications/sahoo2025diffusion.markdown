---
layout: publication
title: The Diffusion Duality
authors: Subham Sekhar Sahoo, Justin Deschenaux, Aaron Gokaslan, Guanghan Wang, Justin
  Chiu, Volodymyr Kuleshov
conference: No Venue
year: 2025
bibkey: sahoo2025diffusion
additional_links: [{name: Code, url: 'http://s-sahoo.github.io/duo'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/684fb2f060b4a34dbe007af1'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2506.10892'}]
tags: ["Efficiency", "Has Code", "Training Techniques"]
short_authors: Sahoo et al.
---
Uniform-state discrete diffusion models hold the promise of fast text generation due to their inherent ability to self-correct. However, they are typically outperformed by autoregressive models and masked diffusion models. In this work, we narrow this performance gap by leveraging a key insight: Uniform-state diffusion processes naturally emerge from an underlying Gaussian diffusion. Our method, Duo, transfers powerful techniques from Gaussian diffusion to improve both training and sampling. First, we introduce a curriculum learning strategy guided by the Gaussian process, doubling training speed by reducing variance. Models trained with curriculum learning surpass autoregressive models in zero-shot perplexity on 3 of 7 benchmarks. Second, we present Discrete Consistency Distillation, which adapts consistency distillation from the continuous to the discrete setting. This algorithm unlocks few-step generation in diffusion language models by accelerating sampling by two orders of magnitude. We provide the code and model checkpoints on the project page: http://s-sahoo.github.io/duo

https://huggingface.co/discussions/paper/684fb2f060b4a34dbe007af1