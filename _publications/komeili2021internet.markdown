---
layout: publication
title: Internet-augmented Dialogue Generation
authors: Mojtaba Komeili, Kurt Shuster, Jason Weston
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: komeili2021internet
citations: 143
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.07566'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Mojtaba Komeili, Kurt Shuster, Jason Weston
---
The largest store of continually updating knowledge on our planet can be
accessed via internet search. In this work we study giving access to this
information to conversational agents. Large language models, even though they
store an impressive amount of knowledge within their weights, are known to
hallucinate facts when generating dialogue (Shuster et al., 2021); moreover,
those facts are frozen in time at the point of model training. In contrast, we
propose an approach that learns to generate an internet search query based on
the context, and then conditions on the search results to finally generate a
response, a method that can employ up-to-the-minute relevant information. We
train and evaluate such models on a newly collected dataset of human-human
conversations whereby one of the speakers is given access to internet search
during knowledgedriven discussions in order to ground their responses. We find
that search-query based access of the internet in conversation provides
superior performance compared to existing approaches that either use no
augmentation or FAISS-based retrieval (Lewis et al., 2020).