---
layout: publication
title: 'Findings Of The Second Babylm Challenge: Sample-efficient Pretraining On Developmentally
  Plausible Corpora'
authors: Michael Y. Hu et al.
conference: Arxiv
year: 2024
citations: 16
bibkey: hu2024findings
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.05149'}]
tags: [Masked Language Model, Training Techniques, RAG, BERT, Efficiency and Optimization,
  Multimodal Models, Language Modeling, Model Architecture]
---
The BabyLM Challenge is a community effort to close the data-efficiency gap
between human and computational language learners. Participants compete to
optimize language model training on a fixed language data budget of 100 million
words or less. This year, we released improved text corpora, as well as a
vision-and-language corpus to facilitate research into cognitively plausible
vision language models. Submissions were compared on evaluation tasks targeting
grammatical ability, (visual) question answering, pragmatic abilities, and
grounding, among other abilities. Participants could submit to a 10M-word
text-only track, a 100M-word text-only track, and/or a 100M-word and image
multimodal track. From 31 submissions employing diverse methods, a hybrid
causal-masked language model architecture outperformed other approaches. No
submissions outperformed the baselines in the multimodal track. In follow-up
analyses, we found a strong relationship between training FLOPs and average
performance across tasks, and that the best-performing submissions proposed
changes to the training data, training objective, and model architecture. This
year's BabyLM Challenge shows that there is still significant room for
innovation in this setting, in particular for image-text modeling, but
community-driven research can yield actionable insights about effective
strategies for small-scale language modeling.