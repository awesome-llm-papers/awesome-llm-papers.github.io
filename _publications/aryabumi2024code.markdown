---
layout: publication
title: To Code, Or Not To Code? Exploring Impact Of Code In Pre-training
authors: "Viraat Aryabumi, Yixuan Su, Raymond Ma, Adrien Morisot, Ivan Zhang, Acyr\
  \ Locatelli, Marzieh Fadaee, Ahmet \xDCst\xFCn, Sara Hooker"
conference: No Venue
year: 2024
bibkey: aryabumi2024code
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66c556de50f505c5451ce947'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2408.10914'}]
tags: ["Llm For Code", "Training Techniques"]
short_authors: Aryabumi et al.
---
Including code in the pre-training data mixture, even for models not specifically designed for code, has become a common practice in LLMs pre-training. While there has been anecdotal consensus among practitioners that code data plays a vital role in general LLMs' performance, there is only limited work analyzing the precise impact of code on non-code tasks. In this work, we systematically investigate the impact of code data on general performance. We ask "what is the impact of code data used in pre-training on a large variety of downstream tasks beyond code generation". We conduct extensive ablations and evaluate across a broad range of natural language reasoning tasks, world knowledge tasks, code benchmarks, and LLM-as-a-judge win-rates for models with sizes ranging from 470M to 2.8B parameters. Across settings, we find a consistent results that code is a critical building block for generalization far beyond coding tasks and improvements to code quality have an outsized impact across all tasks. In particular, compared to text-only pre-training, the addition of code results in up to relative increase of 8.2% in natural language (NL) reasoning, 4.2% in world knowledge, 6.6% improvement in generative win-rates, and a 12x boost in code performance respectively. Our work suggests investments in code quality and preserving code during pre-training have positive impacts.

https://huggingface.co/discussions/paper/66c556de50f505c5451ce947