---
layout: publication
title: Document-level Language Models For Machine Translation
authors: Petrick et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2023
bibkey: petrick2023document
citations: 79
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.12303'}]
tags: [RAG, EMNLP, Training Techniques, Evaluation, Merging]
---
Despite the known limitations, most machine translation systems today still
operate on the sentence-level. One reason for this is, that most parallel
training data is only sentence-level aligned, without document-level meta
information available. In this work, we set out to build context-aware
translation systems utilizing document-level monolingual data instead. This can
be achieved by combining any existing sentence-level translation model with a
document-level language model. We improve existing approaches by leveraging
recent advancements in model combination. Additionally, we propose novel
weighting techniques that make the system combination more flexible and
significantly reduce computational overhead. In a comprehensive evaluation on
four diverse translation tasks, we show that our extensions improve
document-targeted scores substantially and are also computationally more
efficient. However, we also find that in most scenarios, back-translation gives
even better results, at the cost of having to re-train the translation system.
Finally, we explore language model fusion in the light of recent advancements
in large language models. Our findings suggest that there might be strong
potential in utilizing large language models via model combination.