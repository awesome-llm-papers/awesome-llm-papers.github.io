---
layout: publication
title: A Large Encoder-decoder Family Of Foundation Models For Chemical Language
authors: Eduardo Soares, Victor Shirasuna, Emilio Vital Brazil, Renato Cerqueira,
  Dmitry Zubarev, Kristin Schmidt
conference: No Venue
year: 2024
bibkey: soares2024large
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66aa32f1a7081716091aabda'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2407.20267'}]
tags: ["Datasets", "Evaluation", "Few-Shot", "Fine-Tuning", "Training Techniques"]
short_authors: Soares et al.
---
Large-scale pre-training methodologies for chemical language models represent a breakthrough in cheminformatics. These methods excel in tasks such as property prediction and molecule generation by learning contextualized representations of input tokens through self-supervised learning on large unlabeled corpora. Typically, this involves pre-training on unlabeled data followed by fine-tuning on specific tasks, reducing dependence on annotated datasets and broadening chemical language representation understanding. This paper introduces a large encoder-decoder chemical foundation models pre-trained on a curated dataset of 91 million SMILES samples sourced from PubChem, which is equivalent to 4 billion of molecular tokens. The proposed foundation model supports different complex tasks, including quantum property prediction, and offer flexibility with two main variants (289M and 8times289M). Our experiments across multiple benchmark datasets validate the capacity of the proposed model in providing state-of-the-art results for different tasks. We also provide a preliminary assessment of the compositionality of the embedding space as a prerequisite for the reasoning tasks. We demonstrate that the produced latent space is separable compared to the state-of-the-art with few-shot learning capabilities.

https://huggingface.co/discussions/paper/66aa32f1a7081716091aabda