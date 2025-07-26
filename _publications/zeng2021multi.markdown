---
layout: publication
title: 'Multi-grained Vision Language Pre-training: Aligning Texts With Visual Concepts'
authors: Yan Zeng, Xinsong Zhang, Hang Li
conference: Arxiv
year: 2021
bibkey: zeng2021multi
citations: 90
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.08276'}]
tags: ["Training Techniques"]
short_authors: Yan Zeng, Xinsong Zhang, Hang Li
---
Most existing methods in vision language pre-training rely on object-centric
features extracted through object detection and make fine-grained alignments
between the extracted features and texts. It is challenging for these methods
to learn relations among multiple objects. To this end, we propose a new method
called X-VLM to perform `multi-grained vision language pre-training.' The key
to learning multi-grained alignments is to locate visual concepts in the image
given the associated texts, and in the meantime align the texts with the visual
concepts, where the alignments are in multi-granularity. Experimental results
show that X-VLM effectively leverages the learned multi-grained alignments to
many downstream vision language tasks and consistently outperforms
state-of-the-art methods.