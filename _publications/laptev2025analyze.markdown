---
layout: publication
title: Analyze Feature Flow To Enhance Interpretation And Steering In Language Models
authors: Daniil Laptev, Nikita Balagansky, Yaroslav Aksenov, Daniil Gavrilov
conference: No Venue
year: 2025
bibkey: laptev2025analyze
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67a59c4f7ffacd843a56408f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.03032'}]
tags: ["Tools"]
short_authors: Laptev et al.
---
We introduce a new approach to systematically map features discovered by sparse autoencoder across consecutive layers of large language models, extending earlier work that examined inter-layer feature links. By using a data-free cosine similarity technique, we trace how specific features persist, transform, or first appear at each stage. This method yields granular flow graphs of feature evolution, enabling fine-grained interpretability and mechanistic insights into model computations. Crucially, we demonstrate how these cross-layer feature maps facilitate direct steering of model behavior by amplifying or suppressing chosen features, achieving targeted thematic control in text generation. Together, our findings highlight the utility of a causal, cross-layer interpretability framework that not only clarifies how features develop through forward passes but also provides new means for transparent manipulation of large language models.

https://huggingface.co/discussions/paper/67a59c4f7ffacd843a56408f