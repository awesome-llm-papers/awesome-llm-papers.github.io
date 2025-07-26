---
layout: publication
title: Leveraging Video Descriptions To Learn Video Question Answering
authors: Kuo-hao Zeng, Tseng-hung Chen, Ching-yao Chuang, Yuan-hong Liao, Juan Carlos
  Niebles, Min Sun
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2017
bibkey: zeng2016leveraging
citations: 169
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1611.04021'}]
tags: ["AAAI"]
short_authors: Zeng et al.
---
We propose a scalable approach to learn video-based question answering (QA):
answer a "free-form natural language question" about a video content. Our
approach automatically harvests a large number of videos and descriptions
freely available online. Then, a large number of candidate QA pairs are
automatically generated from descriptions rather than manually annotated. Next,
we use these candidate QA pairs to train a number of video-based QA methods
extended fromMN (Sukhbaatar et al. 2015), VQA (Antol et al. 2015), SA (Yao et
al. 2015), SS (Venugopalan et al. 2015). In order to handle non-perfect
candidate QA pairs, we propose a self-paced learning procedure to iteratively
identify them and mitigate their effects in training. Finally, we evaluate
performance on manually generated video-based QA pairs. The results show that
our self-paced learning procedure is effective, and the extended SS model
outperforms various baselines.