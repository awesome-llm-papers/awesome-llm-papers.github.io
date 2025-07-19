---
layout: publication
title: Zero-shot Tokenizer Transfer
authors: "Minixhofer Benjamin, Ponti Edoardo Maria, Vuli\u0107 Ivan"
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2024
bibkey: minixhofer2024zero
citations: 61
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.07883'}]
tags: [ACL, Training Techniques, Efficiency And Optimization]
---
Language models (LMs) are bound to their tokenizer, which maps raw text to a
sequence of vocabulary items (tokens). This restricts their flexibility: for
example, LMs trained primarily on English may still perform well in other
natural and programming languages, but have vastly decreased efficiency due to
their English-centric tokenizer. To mitigate this, we should be able to swap
the original LM tokenizer with an arbitrary one, on the fly, without degrading
performance. Hence, in this work we define a new problem: Zero-Shot Tokenizer
Transfer (ZeTT). The challenge at the core of ZeTT is finding embeddings for
the tokens in the vocabulary of the new tokenizer. Since prior heuristics for
initializing embeddings often perform at chance level in a ZeTT setting, we
propose a new solution: we train a hypernetwork taking a tokenizer as input and
predicting the corresponding embeddings. We empirically demonstrate that the
hypernetwork generalizes to new tokenizers both with encoder (e.g., XLM-R) and
decoder LLMs (e.g., Mistral-7B). Our method comes close to the original models'
performance in cross-lingual and coding tasks while markedly reducing the
length of the tokenized sequence. We also find that the remaining gap can be
quickly closed by continued training on less than 1B tokens. Finally, we show
that a ZeTT hypernetwork trained for a base (L)LM can also be applied to
fine-tuned variants without extra training. Overall, our results make
substantial strides toward detaching LMs from their tokenizer.