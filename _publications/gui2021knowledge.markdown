---
layout: publication
title: 'KAT: A Knowledge Augmented Transformer For Vision-and-language'
authors: Liangke Gui et al.
conference: 'Proceedings of the 2022 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
citations: 49
bibkey: gui2021knowledge
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.08614'}]
tags: [Model Architecture, Transformer, RAG, Interpretability and Explainability,
  Multimodal Models]
---
The primary focus of recent work with largescale transformers has been on
optimizing the amount of information packed into the model's parameters. In
this work, we ask a different question: Can multimodal transformers leverage
explicit knowledge in their reasoning? Existing, primarily unimodal, methods
have explored approaches under the paradigm of knowledge retrieval followed by
answer prediction, but leave open questions about the quality and relevance of
the retrieved knowledge used, and how the reasoning processes over implicit and
explicit knowledge should be integrated. To address these challenges, we
propose a novel model - Knowledge Augmented Transformer (KAT) - which achieves
a strong state-of-the-art result (+6 points absolute) on the open-domain
multimodal task of OK-VQA. Our approach integrates implicit and explicit
knowledge in an end to end encoder-decoder architecture, while still jointly
reasoning over both knowledge sources during answer generation. An additional
benefit of explicit knowledge integration is seen in improved interpretability
of model predictions in our analysis.