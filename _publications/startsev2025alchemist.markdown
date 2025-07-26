---
layout: publication
title: 'Alchemist: Turning Public Text-to-image Data Into Generative Gold'
authors: Valerii Startsev, Alexander Ustyuzhanin, Alexey Kirillov, Dmitry Baranchuk,
  Sergey Kastryulin
conference: No Venue
year: 2025
bibkey: startsev2025alchemist
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.19297'}]
tags: ["Datasets"]
short_authors: Startsev et al.
---
Pre-training equips text-to-image (T2I) models with broad world knowledge, but this alone is often insufficient to achieve high aesthetic quality and alignment. Consequently, supervised fine-tuning (SFT) is crucial for further refinement. However, its effectiveness highly depends on the quality of the fine-tuning dataset. Existing public SFT datasets frequently target narrow domains (e.g., anime or specific art styles), and the creation of high-quality, general-purpose SFT datasets remains a significant challenge. Current curation methods are often costly and struggle to identify truly impactful samples. This challenge is further complicated by the scarcity of public general-purpose datasets, as leading models often rely on large, proprietary, and poorly documented internal data, hindering broader research progress. This paper introduces a novel methodology for creating general-purpose SFT datasets by leveraging a pre-trained generative model as an estimator of high-impact training samples. We apply this methodology to construct and release Alchemist, a compact (3,350 samples) yet highly effective SFT dataset. Experiments demonstrate that Alchemist substantially improves the generative quality of five public T2I models while preserving diversity and style. Additionally, we release the fine-tuned models' weights to the public.

https://huggingface.co/discussions/paper/68354c07f7b44d5d50526322