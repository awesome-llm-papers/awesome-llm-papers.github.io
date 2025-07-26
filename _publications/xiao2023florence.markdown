---
layout: publication
title: 'Florence-2: Advancing A Unified Representation For A Variety Of Vision Tasks'
authors: Bin Xiao, Haiping Wu, Weijian Xu, Xiyang Dai, Houdong Hu, Yumao Lu, Michael
  Zeng, Ce Liu, Lu Yuan
conference: No Venue
year: 2023
bibkey: xiao2023florence
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2311.06242'}]
tags: ["Fine-Tuning", "Prompting"]
short_authors: Xiao et al.
---
We introduce Florence-2, a novel vision foundation model with a unified, prompt-based representation for a variety of computer vision and vision-language tasks. While existing large vision models excel in transfer learning, they struggle to perform a diversity of tasks with simple instructions, a capability that implies handling the complexity of various spatial hierarchy and semantic granularity. Florence-2 was designed to take text-prompt as task instructions and generate desirable results in text forms, whether it be captioning, object detection, grounding or segmentation. This multi-task learning setup demands large-scale, high-quality annotated data. To this end, we co-developed FLD-5B that consists of 5.4 billion comprehensive visual annotations on 126 million images, using an iterative strategy of automated image annotation and model refinement. We adopted a sequence-to-sequence structure to train Florence-2 to perform versatile and comprehensive vision tasks. Extensive evaluations on numerous tasks demonstrated Florence-2 to be a strong vision foundation model contender with unprecedented zero-shot and fine-tuning capabilities.

https://huggingface.co/discussions/paper/65519ea5b5ec9f9a0772932c