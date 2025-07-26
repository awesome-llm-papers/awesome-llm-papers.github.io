---
layout: publication
title: 'When Less Is Enough: Adaptive Token Reduction For Efficient Image Representation'
authors: Eduard Allakhverdov, Elizaveta Goncharova, Andrey Kuznetsov
conference: No Venue
year: 2025
bibkey: allakhverdov2025when
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67e0ffb229682c8065e1c2c6'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.16660'}]
tags: ["Efficiency"]
short_authors: Eduard Allakhverdov, Elizaveta Goncharova, Andrey Kuznetsov
---
Vision encoders typically generate a large number of visual tokens, providing information-rich representations but significantly increasing computational demands. This raises the question of whether all generated tokens are equally valuable or if some of them can be discarded to reduce computational costs without compromising quality. In this paper, we introduce a new method for determining feature utility based on the idea that less valuable features can be reconstructed from more valuable ones. We implement this concept by integrating an autoencoder with a Gumbel-Softmax selection mechanism, that allows identifying and retaining only the most informative visual tokens. To validate our approach, we compared the performance of the LLaVA-NeXT model, using features selected by our method with randomly selected features. We found that on OCR-based tasks, more than 50% of the visual context can be removed with minimal performance loss, whereas randomly discarding the same proportion of features significantly affects the model capabilities. Furthermore, in general-domain tasks, even randomly retaining only 30% of tokens achieves performance comparable to using the full set of visual tokens. Our results highlight a promising direction towards adaptive and efficient multimodal pruning that facilitates scalable and low-overhead inference without compromising performance.

https://huggingface.co/discussions/paper/67e0ffb229682c8065e1c2c6