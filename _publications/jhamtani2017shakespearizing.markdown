---
layout: publication
title: Shakespearizing Modern Language Using Copy-enriched Sequence-to-sequence Models
authors: Jhamtani et al.
conference: Proceedings of the Workshop on Stylistic Variation
year: 2017
bibkey: jhamtani2017shakespearizing
citations: 166
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.01161'}]
tags: [RAG]
---
Variations in writing styles are commonly used to adapt the content to a
specific context, audience, or purpose. However, applying stylistic variations
is still by and large a manual process, and there have been little efforts
towards automating it. In this paper we explore automated methods to transform
text from modern English to Shakespearean English using an end to end trainable
neural model with pointers to enable copy action. To tackle limited amount of
parallel data, we pre-train embeddings of words by leveraging external
dictionaries mapping Shakespearean words to modern English words as well as
additional text. Our methods are able to get a BLEU score of 31+, an
improvement of ~6 points above the strongest baseline. We publicly release our
code to foster further research in this area.