---
layout: publication
title: Generating Self-serendipity Preference In Recommender Systems For Addressing
  Cold Start Problems
authors: Xu Yuanbo, Yang Yongjian, Wang En
conference: Proceedings of the 37th international ACM SIGIR conference on Research
  &amp; development in information retrieval
year: 2022
bibkey: xu2022generating
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.12651'}]
tags: [RSS, Evaluation, Datasets, SIGIR]
---
Classical accuracy-oriented Recommender Systems (RSs) typically face the
cold-start problem and the filter-bubble problem when users suffer the
familiar, repeated, and even predictable recommendations, making them boring
and unsatisfied. To address the above issues, serendipity-oriented RSs are
proposed to recommend appealing and valuable items significantly deviating from
users' historical interactions and thus satisfying them by introducing
unexplored but relevant candidate items to them. In this paper, we devise a
novel serendipity-oriented recommender system (\textbf\{G\}enerative
\textbf\{S\}elf-\textbf\{S\}erendipity \textbf\{R\}ecommender \textbf\{S\}ystem,
\textbf\{GS\\(^2\\)-RS\}) that generates users' self-serendipity preferences to
enhance the recommendation performance. Specifically, this model extracts
users' interest and satisfaction preferences, generates virtual but convincible
neighbors' preferences from themselves, and achieves their self-serendipity
preference. Then these preferences are injected into the rating matrix as
additional information for RS models. Note that GS\\(^2\\)-RS can not only tackle
the cold-start problem but also provides diverse but relevant recommendations
to relieve the filter-bubble problem. Extensive experiments on benchmark
datasets illustrate that the proposed GS\\(^2\\)-RS model can significantly
outperform the state-of-the-art baseline approaches in serendipity measures
with a stable accuracy performance.