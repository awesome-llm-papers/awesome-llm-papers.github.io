---
layout: publication
title: Mapping Natural Language Instructions To Mobile UI Action Sequences
authors: Yang Li, Jiacong He, Xin Zhou, Yuan Zhang, Jason Baldridge
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: li2020mapping
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.03776'}]
tags: ["Datasets", "Evaluation", "Model Architecture", "Training Techniques"]
short_authors: Li et al.
---
We present a new problem: grounding natural language instructions to mobile
user interface actions, and create three new datasets for it. For full task
evaluation, we create PIXELHELP, a corpus that pairs English instructions with
actions performed by people on a mobile UI emulator. To scale training, we
decouple the language and action data by (a) annotating action phrase spans in
HowTo instructions and (b) synthesizing grounded descriptions of actions for
mobile user interfaces. We use a Transformer to extract action phrase tuples
from long-range natural language instructions. A grounding Transformer then
contextually represents UI objects using both their content and screen position
and connects them to object descriptions. Given a starting screen and
instruction, our model achieves 70.59% accuracy on predicting complete
ground-truth action sequences in PIXELHELP.