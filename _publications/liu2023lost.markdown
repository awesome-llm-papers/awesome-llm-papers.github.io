---
layout: publication
title: 'Lost In The Middle: How Language Models Use Long Contexts'
authors: Nelson F. Liu, Kevin Lin, John Hewitt, Ashwin Paranjape, Michele Bevilacqua,
  Fabio Petroni, Percy Liang
conference: No Venue
year: 2023
bibkey: liu2023lost
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2307.03172'}]
tags: ["Memory & Context"]
short_authors: Liu et al.
---
While recent language models have the ability to take long contexts as input, relatively little is known about how well the language models use longer context. We analyze language model performance on two tasks that require identifying relevant information within their input contexts: multi-document question answering and key-value retrieval. We find that performance is often highest when relevant information occurs at the beginning or end of the input context, and significantly degrades when models must access relevant information in the middle of long contexts. Furthermore, performance substantially decreases as the input context grows longer, even for explicitly long-context models. Our analysis provides a better understanding of how language models use their input context and provides new evaluation protocols for future long-context models.

https://huggingface.co/discussions/paper/64a784277fc46ddd14e16f43