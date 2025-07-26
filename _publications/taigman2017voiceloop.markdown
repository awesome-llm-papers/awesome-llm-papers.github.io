---
layout: publication
title: 'Voiceloop: Voice Fitting And Synthesis Via A Phonological Loop'
authors: Yaniv Taigman, Lior Wolf, Adam Polyak, Eliya Nachmani
conference: Arxiv
year: 2018
bibkey: taigman2017voiceloop
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.06588'}]
tags: ["Applications", "Model Architecture"]
short_authors: Taigman et al.
---
We present a new neural text to speech (TTS) method that is able to transform
text to speech in voices that are sampled in the wild. Unlike other systems,
our solution is able to deal with unconstrained voice samples and without
requiring aligned phonemes or linguistic features. The network architecture is
simpler than those in the existing literature and is based on a novel shifting
buffer working memory. The same buffer is used for estimating the attention,
computing the output audio, and for updating the buffer itself. The input
sentence is encoded using a context-free lookup table that contains one entry
per character or phoneme. The speakers are similarly represented by a short
vector that can also be fitted to new identities, even with only a few samples.
Variability in the generated speech is achieved by priming the buffer prior to
generating the audio. Experimental results on several datasets demonstrate
convincing capabilities, making TTS accessible to a wider range of
applications. In order to promote reproducibility, we release our source code
and models.