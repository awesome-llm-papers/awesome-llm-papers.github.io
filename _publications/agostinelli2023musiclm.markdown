---
layout: publication
title: 'Musiclm: Generating Music From Text'
authors: "Andrea Agostinelli, Timo I. Denk, Zal\xE1n Borsos, Jesse Engel, Mauro Verzetti,\
  \ Antoine Caillon, Qingqing Huang, Aren Jansen, Adam Roberts, Marco Tagliasacchi,\
  \ Matt Sharifi, Neil Zeghidour, Christian Frank"
conference: Arxiv
year: 2023
bibkey: agostinelli2023musiclm
citations: 146
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.11325'}]
tags: ["Datasets", "Time Series"]
short_authors: Agostinelli et al.
---
We introduce MusicLM, a model generating high-fidelity music from text
descriptions such as "a calming violin melody backed by a distorted guitar
riff". MusicLM casts the process of conditional music generation as a
hierarchical sequence-to-sequence modeling task, and it generates music at 24
kHz that remains consistent over several minutes. Our experiments show that
MusicLM outperforms previous systems both in audio quality and adherence to the
text description. Moreover, we demonstrate that MusicLM can be conditioned on
both text and a melody in that it can transform whistled and hummed melodies
according to the style described in a text caption. To support future research,
we publicly release MusicCaps, a dataset composed of 5.5k music-text pairs,
with rich text descriptions provided by human experts.