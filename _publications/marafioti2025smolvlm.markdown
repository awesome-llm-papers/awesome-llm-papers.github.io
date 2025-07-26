---
layout: publication
title: 'Smolvlm: Redefining Small And Efficient Multimodal Models'
authors: "Andr\xE9s Marafioti, Orr Zohar, Miquel Farr\xE9, Merve Noyan, Elie Bakouch,\
  \ Pedro Cuenca, Cyril Zakka, Loubna Ben Allal, Anton Lozhkov, Nouamane Tazi, Vaibhav\
  \ Srivastav, Joshua Lochner, Hugo Larcher, Mathieu Morlon, Lewis Tunstall, Leandro\
  \ von Werra, Thomas Wolf"
conference: No Venue
year: 2025
bibkey: marafioti2025smolvlm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.05299'}]
tags: ["Applications", "Training Techniques"]
short_authors: Marafioti et al.
---
Large Vision-Language Models (VLMs) deliver exceptional performance but require significant computational resources, limiting their deployment on mobile and edge devices. Smaller VLMs typically mirror design choices of larger models, such as extensive image tokenization, leading to inefficient GPU memory usage and constrained practicality for on-device applications. We introduce SmolVLM, a series of compact multimodal models specifically engineered for resource-efficient inference. We systematically explore architectural configurations, tokenization strategies, and data curation optimized for low computational overhead. Through this, we identify key design choices that yield substantial performance gains on image and video tasks with minimal memory footprints. Our smallest model, SmolVLM-256M, uses less than 1GB GPU memory during inference and outperforms the 300-times larger Idefics-80B model, despite an 18-month development gap. Our largest model, at 2.2B parameters, rivals state-of-the-art VLMs consuming twice the GPU memory. SmolVLM models extend beyond static images, demonstrating robust video comprehension capabilities. Our results emphasize that strategic architectural optimizations, aggressive yet efficient tokenization, and carefully curated training data significantly enhance multimodal performance, facilitating practical, energy-efficient deployments at significantly smaller scales.

https://huggingface.co/discussions/paper/67f4cf5d504263bce1236dda