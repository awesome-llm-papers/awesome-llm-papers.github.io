---
layout: publication
title: 'Omni-rgpt: Unifying Image And Video Region-level Understanding Via Token Marks'
authors: Miran Heo, Min-hung Chen, De-an Huang, Sifei Liu, Subhashree Radhakrishnan,
  Seon Joo Kim, Yu-chiang Frank Wang, Ryo Hachiuma
conference: No Venue
year: 2025
bibkey: heo2025omni
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.08326'}]
tags: ["Datasets", "Prompting"]
short_authors: Heo et al.
---
We present Omni-RGPT, a multimodal large language model designed to facilitate region-level comprehension for both images and videos. To achieve consistent region representation across spatio-temporal dimensions, we introduce Token Mark, a set of tokens highlighting the target regions within the visual feature space. These tokens are directly embedded into spatial regions using region prompts (e.g., boxes or masks) and simultaneously incorporated into the text prompt to specify the target, establishing a direct connection between visual and text tokens. To further support robust video understanding without requiring tracklets, we introduce an auxiliary task that guides Token Mark by leveraging the consistency of the tokens, enabling stable region interpretation across the video. Additionally, we introduce a large-scale region-level video instruction dataset (RegVID-300k). Omni-RGPT achieves state-of-the-art results on image and video-based commonsense reasoning benchmarks while showing strong performance in captioning and referring expression comprehension tasks.

https://huggingface.co/discussions/paper/6787772816c02260b4e65a22