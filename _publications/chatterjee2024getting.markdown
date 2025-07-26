---
layout: publication
title: 'Getting It Right: Improving Spatial Consistency In Text-to-image Models'
authors: Agneet Chatterjee, Gabriela Ben Melech Stan, Estelle Aflalo, Sayak Paul,
  Dhruba Ghosh, Tejas Gokhale, Ludwig Schmidt, Hannaneh Hajishirzi, Vasudev Lal, Chitta
  Baral, Yezhou Yang
conference: No Venue
year: 2024
bibkey: chatterjee2024getting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.01197'}]
tags: ["Datasets", "Evaluation", "Fine-Tuning", "Prompting", "Training Techniques"]
short_authors: Chatterjee et al.
---
One of the key shortcomings in current text-to-image (T2I) models is their inability to consistently generate images which faithfully follow the spatial relationships specified in the text prompt. In this paper, we offer a comprehensive investigation of this limitation, while also developing datasets and methods that achieve state-of-the-art performance. First, we find that current vision-language datasets do not represent spatial relationships well enough; to alleviate this bottleneck, we create SPRIGHT, the first spatially-focused, large scale dataset, by re-captioning 6 million images from 4 widely used vision datasets. Through a 3-fold evaluation and analysis pipeline, we find that SPRIGHT largely improves upon existing datasets in capturing spatial relationships. To demonstrate its efficacy, we leverage only ~0.25% of SPRIGHT and achieve a 22% improvement in generating spatially accurate images while also improving the FID and CMMD scores. Secondly, we find that training on images containing a large number of objects results in substantial improvements in spatial consistency. Notably, we attain state-of-the-art on T2I-CompBench with a spatial score of 0.2133, by fine-tuning on <500 images. Finally, through a set of controlled experiments and ablations, we document multiple findings that we believe will enhance the understanding of factors that affect spatial consistency in text-to-image models. We publicly release our dataset and model to foster further research in this area.

https://huggingface.co/discussions/paper/660b8585cafce26b3c53f804