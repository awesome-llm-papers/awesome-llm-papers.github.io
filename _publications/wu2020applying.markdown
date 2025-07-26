---
layout: publication
title: Applying The Transformer To Character-level Transduction
authors: Shijie Wu, Ryan Cotterell, Mans Hulden
conference: 'Proceedings of the 16th Conference of the European Chapter of the Association
  for Computational Linguistics: Main Volume'
year: 2021
bibkey: wu2020applying
citations: 76
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.10213'}]
tags: ["EACL", "Model Architecture"]
short_authors: Shijie Wu, Ryan Cotterell, Mans Hulden
---
The transformer has been shown to outperform recurrent neural network-based
sequence-to-sequence models in various word-level NLP tasks. Yet for
character-level transduction tasks, e.g. morphological inflection generation
and historical text normalization, there are few works that outperform
recurrent models using the transformer. In an empirical study, we uncover that,
in contrast to recurrent sequence-to-sequence models, the batch size plays a
crucial role in the performance of the transformer on character-level tasks,
and we show that with a large enough batch size, the transformer does indeed
outperform recurrent models. We also introduce a simple technique to handle
feature-guided character-level transduction that further improves performance.
With these insights, we achieve state-of-the-art performance on morphological
inflection and historical text normalization. We also show that the transformer
outperforms a strong baseline on two other character-level transduction tasks:
grapheme-to-phoneme conversion and transliteration.