---
layout: publication
title: 'Oneig-bench: Omni-dimensional Nuanced Evaluation For Image Generation'
authors: Jingjing Chang, Yixiao Fang, Peng Xing, Shuhan Wu, Wei Cheng, Rui Wang, Xianfang
  Zeng, Gang Yu, Hai-bao Chen
conference: No Venue
year: 2025
bibkey: chang2025oneig
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/684792f03ec10bdd8ab4de0f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2506.07977'}]
tags: ["Evaluation", "Tools"]
short_authors: Chang et al.
---
Text-to-image (T2I) models have garnered significant attention for generating high-quality images aligned with text prompts. However, rapid T2I model advancements reveal limitations in early benchmarks, lacking comprehensive evaluations, for example, the evaluation on reasoning, text rendering and style. Notably, recent state-of-the-art models, with their rich knowledge modeling capabilities, show promising results on the image generation problems requiring strong reasoning ability, yet existing evaluation systems have not adequately addressed this frontier. To systematically address these gaps, we introduce OneIG-Bench, a meticulously designed comprehensive benchmark framework for fine-grained evaluation of T2I models across multiple dimensions, including prompt-image alignment, text rendering precision, reasoning-generated content, stylization, and diversity. By structuring the evaluation, this benchmark enables in-depth analysis of model performance, helping researchers and practitioners pinpoint strengths and bottlenecks in the full pipeline of image generation. Specifically, OneIG-Bench enables flexible evaluation by allowing users to focus on a particular evaluation subset. Instead of generating images for the entire set of prompts, users can generate images only for the prompts associated with the selected dimension and complete the corresponding evaluation accordingly. Our codebase and dataset are now publicly available to facilitate reproducible evaluation studies and cross-model comparisons within the T2I research community.

https://huggingface.co/discussions/paper/684792f03ec10bdd8ab4de0f