---
layout: publication
title: 'Audiolm: A Language Modeling Approach To Audio Generation'
authors: "Zal\xE1n Borsos, Rapha\xEBl Marinier, Damien Vincent, Eugene Kharitonov,\
  \ Olivier Pietquin, Matt Sharifi, Dominik Roblek, Olivier Teboul, David Grangier,\
  \ Marco Tagliasacchi, Neil Zeghidour"
conference: IEEE/ACM Transactions on Audio, Speech, and Language Processing
year: 2023
bibkey: borsos2022audiolm
citations: 183
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.03143'}]
tags: ["Tools"]
short_authors: Borsos et al.
---
We introduce AudioLM, a framework for high-quality audio generation with
long-term consistency. AudioLM maps the input audio to a sequence of discrete
tokens and casts audio generation as a language modeling task in this
representation space. We show how existing audio tokenizers provide different
trade-offs between reconstruction quality and long-term structure, and we
propose a hybrid tokenization scheme to achieve both objectives. Namely, we
leverage the discretized activations of a masked language model pre-trained on
audio to capture long-term structure and the discrete codes produced by a
neural audio codec to achieve high-quality synthesis. By training on large
corpora of raw audio waveforms, AudioLM learns to generate natural and coherent
continuations given short prompts. When trained on speech, and without any
transcript or annotation, AudioLM generates syntactically and semantically
plausible speech continuations while also maintaining speaker identity and
prosody for unseen speakers. Furthermore, we demonstrate how our approach
extends beyond speech by generating coherent piano music continuations, despite
being trained without any symbolic representation of music.