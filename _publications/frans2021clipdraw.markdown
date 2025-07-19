---
layout: publication
title: 'Clipdraw: Exploring Text-to-drawing Synthesis Through Language-image Encoders'
authors: Frans Kevin, Soros L. B., Witkowski Olaf
conference: Arxiv
year: 2021
bibkey: frans2021clipdraw
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.14843'}]
tags: [Efficiency And Optimization, Training Techniques, Ethics And Bias]
---
This work presents CLIPDraw, an algorithm that synthesizes novel drawings
based on natural language input. CLIPDraw does not require any training; rather
a pre-trained CLIP language-image encoder is used as a metric for maximizing
similarity between the given description and a generated drawing. Crucially,
CLIPDraw operates over vector strokes rather than pixel images, a constraint
that biases drawings towards simpler human-recognizable shapes. Results compare
between CLIPDraw and other synthesis-through-optimization methods, as well as
highlight various interesting behaviors of CLIPDraw, such as satisfying
ambiguous text in multiple ways, reliably producing drawings in diverse
artistic styles, and scaling from simple to complex visual representations as
stroke count is increased. Code for experimenting with the method is available
at:
https://colab.research.google.com/github/kvfrans/clipdraw/blob/main/clipdraw.ipynb