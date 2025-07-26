---
layout: publication
title: Episodic Memory In Lifelong Language Learning
authors: Cyprien de Masson D'autume, Sebastian Ruder, Lingpeng Kong, Dani Yogatama
conference: Arxiv
year: 2019
bibkey: dautume2019episodic
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.01076'}]
tags: ["Datasets"]
short_authors: D'autume et al.
---
We introduce a lifelong language learning setup where a model needs to learn
from a stream of text examples without any dataset identifier. We propose an
episodic memory model that performs sparse experience replay and local
adaptation to mitigate catastrophic forgetting in this setup. Experiments on
text classification and question answering demonstrate the complementary
benefits of sparse experience replay and local adaptation to allow the model to
continuously learn from new datasets. We also show that the space complexity of
the episodic memory module can be reduced significantly (~50-90%) by randomly
choosing which examples to store in memory with a minimal decrease in
performance. We consider an episodic memory component as a crucial building
block of general linguistic intelligence and see our model as a first step in
that direction.