---
layout: publication
title: Linear Transformers With Learnable Kernel Functions Are Better In-context Models
authors: Yaroslav Aksenov, Nikita Balagansky, Sofia Maria Lo Cicero Vaina, Boris Shaposhnikov,
  Alexey Gorbatovski, Daniil Gavrilov
conference: No Venue
year: 2024
bibkey: aksenov2024linear
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2402.10644'}]
tags: ["Model Architecture"]
short_authors: Aksenov et al.
---
Advancing the frontier of subquadratic architectures for Language Models (LMs) is crucial in the rapidly evolving field of natural language processing. Current innovations, including State Space Models, were initially celebrated for surpassing Transformer performance on language modeling tasks. However, these models have revealed deficiencies in essential In-Context Learning capabilities - a domain where the Transformer traditionally shines. The Based model emerged as a hybrid solution, blending a Linear Transformer with a kernel inspired by the Taylor expansion of exponential functions, augmented by convolutional networks. Mirroring the Transformer's in-context adeptness, it became a strong contender in the field. In our work, we present a singular, elegant alteration to the Based kernel that amplifies its In-Context Learning abilities evaluated with the Multi-Query Associative Recall task and overall language modeling process, as demonstrated on the Pile dataset.

https://huggingface.co/discussions/paper/65d2e27d8120c6edb8230766