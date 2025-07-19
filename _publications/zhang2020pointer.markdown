---
layout: publication
title: 'POINTER: Constrained Progressive Text Generation Via Insertion-based Generative
  Pre-training'
authors: Zhang et al.
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: zhang2020pointer
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00558'}]
tags: [Training Techniques, EMNLP, GPT, Transformer, BERT, Model Architecture, Language
    Modeling, Datasets]
---
Large-scale pre-trained language models, such as BERT and GPT-2, have
achieved excellent performance in language representation learning and
free-form text generation. However, these models cannot be directly employed to
generate text under specified lexical constraints. To address this challenge,
we present POINTER (PrOgressive INsertion-based TransformER), a simple yet
novel insertion-based approach for hard-constrained text generation. The
proposed method operates by progressively inserting new tokens between existing
tokens in a parallel manner. This procedure is recursively applied until a
sequence is completed. The resulting coarse-to-fine hierarchy makes the
generation process intuitive and interpretable. We pre-train our model with the
proposed progressive insertion-based objective on a 12GB Wikipedia dataset, and
fine-tune it on downstream hard-constrained generation tasks.
Non-autoregressive decoding yields an empirically logarithmic time complexity
during inference time. Experimental results on both News and Yelp datasets
demonstrate that POINTER achieves state-of-the-art performance on constrained
text generation. We released the pre-trained models and the source code to
facilitate future research (https://github.com/dreasysnail/POINTER).