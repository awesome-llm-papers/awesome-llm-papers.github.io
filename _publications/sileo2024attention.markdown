---
layout: publication
title: 'Attention Overflow: Language Model Input Blur During Long-context Missing
  Items Recommendation'
authors: Sileo Damien
conference: Information Sciences
year: 2024
bibkey: sileo2024attention
citations: 106
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.13481'}]
tags: [Alt, Model Architecture, Prompting, Attention Mechanism]
---
Large language models (LLMs) can suggest missing elements from items listed
in a prompt, which can be used for list completion or recommendations based on
users' history. However, their performance degrades when presented with too
many items, as they start to suggest items already included in the input list.
This occurs at around 100 items for mid-2024 flagship LLMs. We evaluate this
phenomenon on both synthetic problems (e.g., finding missing numbers in a given
range of shuffled integers) and realistic movie recommendation scenarios. We
refer to this issue as \textit\{attention overflow\}, as preventing repetition
requires attending to all items simultaneously. Although iterative loops can
mitigate this problem, their costs increase with the repetition rate, affecting
the language models' ability to derive novelty from lengthy inputs.