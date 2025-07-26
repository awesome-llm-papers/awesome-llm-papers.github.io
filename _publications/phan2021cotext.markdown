---
layout: publication
title: 'Cotext: Multi-task Learning With Code-text Transformer'
authors: Long Phan, Hieu Tran, Daniel Le, Hieu Nguyen, James Anibal, Alec Peltekian,
  Yanfang Ye
conference: Proceedings of the 1st Workshop on Natural Language Processing for Programming
  (NLP4Prog 2021)
year: 2021
bibkey: phan2021cotext
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.08645'}]
tags: ["Llm For Code", "Model Architecture"]
short_authors: Phan et al.
---
We present CoTexT, a pre-trained, transformer-based encoder-decoder model
that learns the representative context between natural language (NL) and
programming language (PL). Using self-supervision, CoTexT is pre-trained on
large programming language corpora to learn a general understanding of language
and code. CoTexT supports downstream NL-PL tasks such as code
summarizing/documentation, code generation, defect detection, and code
debugging. We train CoTexT on different combinations of available PL corpus
including both "bimodal" and "unimodal" data. Here, bimodal data is the
combination of text and corresponding code snippets, whereas unimodal data is
merely code snippets. We first evaluate CoTexT with multi-task learning: we
perform Code Summarization on 6 different programming languages and Code
Refinement on both small and medium size featured in the CodeXGLUE dataset. We
further conduct extensive experiments to investigate CoTexT on other tasks
within the CodeXGlue dataset, including Code Generation and Defect Detection.
We consistently achieve SOTA results in these tasks, demonstrating the
versatility of our models.