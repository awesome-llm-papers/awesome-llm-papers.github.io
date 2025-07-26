---
layout: publication
title: 'Mattnet: Modular Attention Network For Referring Expression Comprehension'
authors: Licheng Yu, Zhe Lin, Xiaohui Shen, Jimei Yang, Xin Lu, Mohit Bansal, Tamara
  L. Berg
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2018
bibkey: yu2018mattnet
citations: 750
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.08186'}]
tags: ["CVPR"]
short_authors: Yu et al.
---
In this paper, we address referring expression comprehension: localizing an
image region described by a natural language expression. While most recent work
treats expressions as a single unit, we propose to decompose them into three
modular components related to subject appearance, location, and relationship to
other objects. This allows us to flexibly adapt to expressions containing
different types of information in an end-to-end framework. In our model, which
we call the Modular Attention Network (MAttNet), two types of attention are
utilized: language-based attention that learns the module weights as well as
the word/phrase attention that each module should focus on; and visual
attention that allows the subject and relationship modules to focus on relevant
image components. Module weights combine scores from all three modules
dynamically to output an overall score. Experiments show that MAttNet
outperforms previous state-of-art methods by a large margin on both
bounding-box-level and pixel-level comprehension tasks. Demo and code are
provided.