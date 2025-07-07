---
layout: publication
title: Text-free Prosody-aware Generative Spoken Language Modeling
authors: Eugene Kharitonov et al.
conference: Arxiv
year: 2021
citations: 18
bibkey: kharitonov2021text
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.03264'}, {name: Code,
    url: 'https://speechbot.github.io/pgslm'}, {name: Code, url: 'https://github.com/pytorch/fairseq/tree/main/examples/textless_nlp/pgslm'}]
tags: [Training Techniques, Transformer, GPT, RAG, Pre-Training, Has Code, Prompting,
  Language Modeling, Model Architecture]
---
Speech pre-training has primarily demonstrated efficacy on classification
tasks, while its capability of generating novel speech, similar to how GPT-2
can generate coherent paragraphs, has barely been explored. Generative Spoken
Language Modeling (GSLM) \cite\{Lakhotia2021\} is the only prior work addressing
the generative aspects of speech pre-training, which replaces text with
discovered phone-like units for language modeling and shows the ability to
generate meaningful novel sentences. Unfortunately, despite eliminating the
need of text, the units used in GSLM discard most of the prosodic information.
Hence, GSLM fails to leverage prosody for better comprehension, and does not
generate expressive speech. In this work, we present a prosody-aware generative
spoken language model (pGSLM). It is composed of a multi-stream transformer
language model (MS-TLM) of speech, represented as discovered unit and prosodic
feature streams, and an adapted HiFi-GAN model converting MS-TLM outputs to
waveforms. We devise a series of metrics for prosody modeling and generation,
and re-use metrics from GSLM for content modeling. Experimental results show
that the pGSLM can utilize prosody to improve both prosody and content
modeling, and also generate natural, meaningful, and coherent speech given a
spoken prompt. Audio samples can be found at https://speechbot.github.io/pgslm.
Codes and models are available at
https://github.com/pytorch/fairseq/tree/main/examples/textless_nlp/pgslm.