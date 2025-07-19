---
layout: publication
title: Generating Chinese Classical Poems With RNN Encoder-decoder
authors: Yi Xiaoyuan, Li Ruoyu, Sun Maosong
conference: Lecture Notes in Computer Science
year: 2016
bibkey: yi2016generating
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1604.01537'}]
tags: [Model Architecture, Training Techniques, Attention Mechanism, Transformer]
---
We take the generation of Chinese classical poem lines as a
sequence-to-sequence learning problem, and build a novel system based on the
RNN Encoder-Decoder structure to generate quatrains (Jueju in Chinese), with a
topic word as input. Our system can jointly learn semantic meaning within a
single line, semantic relevance among lines in a poem, and the use of
structural, rhythmical and tonal patterns, without utilizing any constraint
templates. Experimental results show that our system outperforms other
competitive systems. We also find that the attention mechanism can capture the
word associations in Chinese classical poetry and inverting target lines in
training can improve performance.