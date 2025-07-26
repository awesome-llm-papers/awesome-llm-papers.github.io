---
layout: publication
title: 'Nablanabla: Neighborhood Adaptive Block-level Attention'
authors: Dmitrii Mikhailov, Aleksey Letunovskiy, Maria Kovaleva, Vladimir Arkhipkin,
  Vladimir Korviakov, Vladimir Polovnikov, Viacheslav Vasilev, Evelina Sidorova, Denis
  Dimitrov
conference: No Venue
year: 2025
bibkey: mikhailov2025nablanabla
additional_links: [{name: Code, url: 'https://github.com/gen-ai-team/Wan2.1-NABLA'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6883427a846d2e78b7548bd7'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.13546'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Mikhailov et al.
---
Recent progress in transformer-based architectures has demonstrated remarkable success in video generation tasks. However, the quadratic complexity of full attention mechanisms remains a critical bottleneck, particularly for high-resolution and long-duration video sequences. In this paper, we propose NABLA, a novel Neighborhood Adaptive Block-Level Attention mechanism that dynamically adapts to sparsity patterns in video diffusion transformers (DiTs). By leveraging block-wise attention with adaptive sparsity-driven threshold, NABLA reduces computational overhead while preserving generative quality. Our method does not require custom low-level operator design and can be seamlessly integrated with PyTorch's Flex Attention operator. Experiments demonstrate that NABLA achieves up to 2.7x faster training and inference compared to baseline almost without compromising quantitative metrics (CLIP score, VBench score, human evaluation score) and visual quality drop. The code and model weights are available here: https://github.com/gen-ai-team/Wan2.1-NABLA

https://huggingface.co/discussions/paper/6883427a846d2e78b7548bd7