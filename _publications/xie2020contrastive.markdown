---
layout: publication
title: Contrastive Learning For Sequential Recommendation
authors: Xu Xie, Fei Sun, Zhaoyang Liu, Shiwen Wu, Jinyang Gao, Bolin Ding, Bin Cui
conference: 2022 IEEE 38th International Conference on Data Engineering (ICDE)
year: 2022
bibkey: xie2020contrastive
citations: 401
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.14395'}]
tags: ["Datasets", "Tools"]
short_authors: Xie et al.
---
Sequential recommendation methods play a crucial role in modern recommender
systems because of their ability to capture a user's dynamic interest from
her/his historical interactions. Despite their success, we argue that these
approaches usually rely on the sequential prediction task to optimize the huge
amounts of parameters. They usually suffer from the data sparsity problem,
which makes it difficult for them to learn high-quality user representations.
To tackle that, inspired by recent advances of contrastive learning techniques
in the computer version, we propose a novel multi-task model called
\textbf\{C\}ontrastive \textbf\{L\}earning for \textbf\{S\}equential
\textbf\{Rec\}ommendation~(\textbf\{CL4SRec\}). CL4SRec not only takes advantage of
the traditional next item prediction task but also utilizes the contrastive
learning framework to derive self-supervision signals from the original user
behavior sequences. Therefore, it can extract more meaningful user patterns and
further encode the user representation effectively. In addition, we propose
three data augmentation approaches to construct self-supervision signals.
Extensive experiments on four public datasets demonstrate that CL4SRec achieves
state-of-the-art performance over existing baselines by inferring better user
representations.