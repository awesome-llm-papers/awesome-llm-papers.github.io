---
layout: publication
title: Title Generation For User Generated Videos
authors: Kuo-hao Zeng, Tseng-hung Chen, Juan Carlos Niebles, Min Sun
conference: Lecture Notes in Computer Science
year: 2016
bibkey: zeng2016title
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1608.07068'}]
tags: ["Datasets"]
short_authors: Zeng et al.
---
A great video title describes the most salient event compactly and captures
the viewer's attention. In contrast, video captioning tends to generate
sentences that describe the video as a whole. Although generating a video title
automatically is a very useful task, it is much less addressed than video
captioning. We address video title generation for the first time by proposing
two methods that extend state-of-the-art video captioners to this new task.
First, we make video captioners highlight sensitive by priming them with a
highlight detector. Our framework allows for jointly training a model for title
generation and video highlight localization. Second, we induce high sentence
diversity in video captioners, so that the generated titles are also diverse
and catchy. This means that a large number of sentences might be required to
learn the sentence structure of titles. Hence, we propose a novel sentence
augmentation method to train a captioner with additional sentence-only examples
that come without corresponding videos. We collected a large-scale Video Titles
in the Wild (VTW) dataset of 18100 automatically crawled user-generated videos
and titles. On VTW, our methods consistently improve title prediction accuracy,
and achieve the best performance in both automatic and human evaluation.
Finally, our sentence augmentation method also outperforms the baselines on the
M-VAD dataset.