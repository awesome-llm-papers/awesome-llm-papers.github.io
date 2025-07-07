---
layout: publication
title: 'Speak Foreign Languages With Your Own Voice: Cross-lingual Neural Codec Language
  Modeling'
authors: Ziqiang Zhang et al.
conference: Arxiv
year: 2023
citations: 20
bibkey: zhang2023speak
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.03926'}, {name: Code,
    url: 'https://aka.ms/vallex'}]
tags: [Language Modeling, Has Code, In-Context Learning, Prompting]
---
We propose a cross-lingual neural codec language model, VALL-E X, for
cross-lingual speech synthesis. Specifically, we extend VALL-E and train a
multi-lingual conditional codec language model to predict the acoustic token
sequences of the target language speech by using both the source language
speech and the target language text as prompts. VALL-E X inherits strong
in-context learning capabilities and can be applied for zero-shot cross-lingual
text-to-speech synthesis and zero-shot speech-to-speech translation tasks.
Experimental results show that it can generate high-quality speech in the
target language via just one speech utterance in the source language as a
prompt while preserving the unseen speaker's voice, emotion, and acoustic
environment. Moreover, VALL-E X effectively alleviates the foreign accent
problems, which can be controlled by a language ID. Audio samples are available
at https://aka.ms/vallex.