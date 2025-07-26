---
layout: publication
title: Generative Representational Instruction Tuning
authors: Niklas Muennighoff, Hongjin Su, Liang Wang, Nan Yang, Furu Wei, Tao Yu, Amanpreet
  Singh, Douwe Kiela
conference: No Venue
year: 2024
bibkey: muennighoff2024generative
additional_links: [{name: Code, url: 'https://github.com/ContextualAI/gritlm'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/65cec095e1c8a3d33cf694f9'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2402.09906'}]
tags: ["Training Techniques"]
short_authors: Muennighoff et al.
---
All text-based language problems can be reduced to either generation or embedding. Current models only perform well at one or the other. We introduce generative representational instruction tuning (GRIT) whereby a large language model is trained to handle both generative and embedding tasks by distinguishing between them through instructions. Compared to other open models, our resulting GritLM 7B sets a new state of the art on the Massive Text Embedding Benchmark (MTEB) and outperforms all models up to its size on a range of generative tasks. By scaling up further, GritLM 8x7B outperforms all open generative language models that we tried while still being among the best embedding models. Notably, we find that GRIT matches training on only generative or embedding data, thus we can unify both at no performance loss. Among other benefits, the unification via GRIT speeds up Retrieval-Augmented Generation (RAG) by > 60% for long documents, by no longer requiring separate retrieval and generation models. Models, code, etc. are freely available at https://github.com/ContextualAI/gritlm.

https://huggingface.co/discussions/paper/65cec095e1c8a3d33cf694f9