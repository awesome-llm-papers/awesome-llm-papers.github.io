---
layout: publication
title: 'SPICE: Semantic Propositional Image Caption Evaluation'
authors: Peter Anderson, Basura Fernando, Mark Johnson, Stephen Gould
conference: Lecture Notes in Computer Science
year: 2016
bibkey: anderson2016spice
citations: 1724
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1607.08822'}]
tags: ["Datasets", "Evaluation"]
short_authors: Anderson et al.
---
There is considerable interest in the task of automatically generating image
captions. However, evaluation is challenging. Existing automatic evaluation
metrics are primarily sensitive to n-gram overlap, which is neither necessary
nor sufficient for the task of simulating human judgment. We hypothesize that
semantic propositional content is an important component of human caption
evaluation, and propose a new automated caption evaluation metric defined over
scene graphs coined SPICE. Extensive evaluations across a range of models and
datasets indicate that SPICE captures human judgments over model-generated
captions better than other automatic metrics (e.g., system-level correlation of
0.88 with human judgments on the MS COCO dataset, versus 0.43 for CIDEr and
0.53 for METEOR). Furthermore, SPICE can answer questions such as `which
caption-generator best understands colors?' and `can caption-generators count?'