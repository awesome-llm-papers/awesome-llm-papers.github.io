---
layout: publication
title: 'Move Forward And Tell: A Progressive Generator Of Video Descriptions'
authors: Yilei Xiong, Bo Dai, Dahua Lin
conference: Lecture Notes in Computer Science
year: 2018
bibkey: xiong2018move
citations: 115
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.10018'}]
tags: ["Datasets", "Tools"]
short_authors: Yilei Xiong, Bo Dai, Dahua Lin
---
We present an efficient framework that can generate a coherent paragraph to
describe a given video. Previous works on video captioning usually focus on
video clips. They typically treat an entire video as a whole and generate the
caption conditioned on a single embedding. On the contrary, we consider videos
with rich temporal structures and aim to generate paragraph descriptions that
can preserve the story flow while being coherent and concise. Towards this
goal, we propose a new approach, which produces a descriptive paragraph by
assembling temporally localized descriptions. Given a video, it selects a
sequence of distinctive clips and generates sentences thereon in a coherent
manner. Particularly, the selection of clips and the production of sentences
are done jointly and progressively driven by a recurrent network -- what to
describe next depends on what have been said before. Here, the recurrent
network is learned via self-critical sequence training with both sentence-level
and paragraph-level rewards. On the ActivityNet Captions dataset, our method
demonstrated the capability of generating high-quality paragraph descriptions
for videos. Compared to those by other methods, the descriptions produced by
our method are often more relevant, more coherent, and more concise.