---
layout: publication
title: 'Llms Know More Than They Show: On The Intrinsic Representation Of LLM Hallucinations'
authors: Hadas Orgad, Michael Toker, Zorik Gekhman, Roi Reichart, Idan Szpektor, Hadas
  Kotek, Yonatan Belinkov
conference: No Venue
year: 2024
bibkey: orgad2024llms
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6703267fc265fe2565c141be'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.02707'}]
tags: ["Datasets"]
short_authors: Orgad et al.
---
Large language models (LLMs) often produce errors, including factual inaccuracies, biases, and reasoning failures, collectively referred to as "hallucinations". Recent studies have demonstrated that LLMs' internal states encode information regarding the truthfulness of their outputs, and that this information can be utilized to detect errors. In this work, we show that the internal representations of LLMs encode much more information about truthfulness than previously recognized. We first discover that the truthfulness information is concentrated in specific tokens, and leveraging this property significantly enhances error detection performance. Yet, we show that such error detectors fail to generalize across datasets, implying that -- contrary to prior claims -- truthfulness encoding is not universal but rather multifaceted. Next, we show that internal representations can also be used for predicting the types of errors the model is likely to make, facilitating the development of tailored mitigation strategies. Lastly, we reveal a discrepancy between LLMs' internal encoding and external behavior: they may encode the correct answer, yet consistently generate an incorrect one. Taken together, these insights deepen our understanding of LLM errors from the model's internal perspective, which can guide future research on enhancing error analysis and mitigation.

https://huggingface.co/discussions/paper/6703267fc265fe2565c141be