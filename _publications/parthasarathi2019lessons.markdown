---
layout: publication
title: Lessons From Building Acoustic Models With A Million Hours Of Speech
authors: Sree Hari Krishnan Parthasarathi, Nikko Strom
conference: ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2019
bibkey: parthasarathi2019lessons
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.01624'}]
tags: ["ICASSP"]
short_authors: Sree Hari Krishnan Parthasarathi, Nikko Strom
---
This is a report of our lessons learned building acoustic models from 1
Million hours of unlabeled speech, while labeled speech is restricted to 7,000
hours. We employ student/teacher training on unlabeled data, helping scale out
target generation in comparison to confidence model based methods, which
require a decoder and a confidence model. To optimize storage and to
parallelize target generation, we store high valued logits from the teacher
model. Introducing the notion of scheduled learning, we interleave learning on
unlabeled and labeled data. To scale distributed training across a large number
of GPUs, we use BMUF with 64 GPUs, while performing sequence training only on
labeled data with gradient threshold compression SGD using 16 GPUs. Our
experiments show that extremely large amounts of data are indeed useful; with
little hyper-parameter tuning, we obtain relative WER improvements in the 10 to
20% range, with higher gains in noisier conditions.