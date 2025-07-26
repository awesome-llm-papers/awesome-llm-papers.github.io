---
layout: publication
title: Going Full-tilt Boogie On Document Understanding With Text-image-layout Transformer
authors: "Rafa\u0142 Powalski, \u0141ukasz Borchmann, Dawid Jurkiewicz, Tomasz Dwojak,\
  \ Micha\u0142 Pietruszka, Gabriela Pa\u0142ka"
conference: Lecture Notes in Computer Science
year: 2021
bibkey: powalski2021going
citations: 116
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2102.09550'}]
tags: ["Model Architecture"]
short_authors: Powalski et al.
---
We address the challenging problem of Natural Language Comprehension beyond
plain-text documents by introducing the TILT neural network architecture which
simultaneously learns layout information, visual features, and textual
semantics. Contrary to previous approaches, we rely on a decoder capable of
unifying a variety of problems involving natural language. The layout is
represented as an attention bias and complemented with contextualized visual
information, while the core of our model is a pretrained encoder-decoder
Transformer. Our novel approach achieves state-of-the-art results in extracting
information from documents and answering questions which demand layout
understanding (DocVQA, CORD, SROIE). At the same time, we simplify the process
by employing an end-to-end model.