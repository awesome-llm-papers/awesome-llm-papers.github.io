---
layout: publication
title: 'The Amazing Mysteries Of The Gutter: Drawing Inferences Between Panels In
  Comic Book Narratives'
authors: Iyyer et al.
conference: 2017 IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2016
bibkey: iyyer2016amazing
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.05118'}]
tags: [Model Architecture, CVPR, Datasets]
---
Visual narrative is often a combination of explicit information and judicious
omissions, relying on the viewer to supply missing details. In comics, most
movements in time and space are hidden in the "gutters" between panels. To
follow the story, readers logically connect panels together by inferring unseen
actions through a process called "closure". While computers can now describe
what is explicitly depicted in natural images, in this paper we examine whether
they can understand the closure-driven narratives conveyed by stylized artwork
and dialogue in comic book panels. We construct a dataset, COMICS, that
consists of over 1.2 million panels (120 GB) paired with automatic textbox
transcriptions. An in-depth analysis of COMICS demonstrates that neither text
nor image alone can tell a comic book story, so a computer must understand both
modalities to keep up with the plot. We introduce three cloze-style tasks that
ask models to predict narrative and character-centric aspects of a panel given
n preceding panels as context. Various deep neural architectures underperform
human baselines on these tasks, suggesting that COMICS contains fundamental
challenges for both vision and language.