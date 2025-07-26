---
layout: publication
title: End-to-end Slot Alignment And Recognition For Cross-lingual NLU
authors: Weijia Xu, Batool Haider, Saab Mansour
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: xu2020end
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14353'}]
tags: ["EMNLP"]
short_authors: Weijia Xu, Batool Haider, Saab Mansour
---
Natural language understanding (NLU) in the context of goal-oriented dialog
systems typically includes intent classification and slot labeling tasks.
Existing methods to expand an NLU system to new languages use machine
translation with slot label projection from source to the translated
utterances, and thus are sensitive to projection errors. In this work, we
propose a novel end-to-end model that learns to align and predict target slot
labels jointly for cross-lingual transfer. We introduce MultiATIS++, a new
multilingual NLU corpus that extends the Multilingual ATIS corpus to nine
languages across four language families, and evaluate our method using the
corpus. Results show that our method outperforms a simple label projection
method using fast-align on most languages, and achieves competitive performance
to the more complex, state-of-the-art projection method with only half of the
training time. We release our MultiATIS++ corpus to the community to continue
future research on cross-lingual NLU.