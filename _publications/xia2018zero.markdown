---
layout: publication
title: Zero-shot User Intent Detection Via Capsule Neural Networks
authors: Congying Xia, Chenwei Zhang, Xiaohui Yan, Yi Chang, Philip S. Yu
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: xia2018zero
citations: 209
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.00385'}]
tags: ["EMNLP"]
short_authors: Xia et al.
---
User intent detection plays a critical role in question-answering and dialog
systems. Most previous works treat intent detection as a classification problem
where utterances are labeled with predefined intents. However, it is
labor-intensive and time-consuming to label users' utterances as intents are
diversely expressed and novel intents will continually be involved. Instead, we
study the zero-shot intent detection problem, which aims to detect emerging
user intents where no labeled utterances are currently available. We propose
two capsule-based architectures: INTENT-CAPSNET that extracts semantic features
from utterances and aggregates them to discriminate existing intents, and
INTENTCAPSNET-ZSL which gives INTENTCAPSNET the zero-shot learning ability to
discriminate emerging intents via knowledge transfer from existing intents.
Experiments on two real-world datasets show that our model not only can better
discriminate diversely expressed existing intents, but is also able to
discriminate emerging intents when no labeled utterances are available.