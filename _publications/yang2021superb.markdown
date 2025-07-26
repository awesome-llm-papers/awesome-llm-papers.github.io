---
layout: publication
title: 'SUPERB: Speech Processing Universal Performance Benchmark'
authors: Shu-wen Yang, Po-han Chi, Yung-sung Chuang, Cheng-i Jeff Lai, Kushal Lakhotia,
  Yist Y. Lin, Andy T. Liu, Jiatong Shi, Xuankai Chang, Guan-ting Lin, Tzu-hsien Huang,
  Wei-cheng Tseng, Ko-tik Lee, Da-rong Liu, Zili Huang, Shuyan Dong, Shang-wen Li,
  Shinji Watanabe, Abdelrahman Mohamed, Hung-yi Lee
conference: Interspeech 2021
year: 2021
bibkey: yang2021superb
citations: 473
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.01051'}]
tags: ["Evaluation", "INTERSPEECH"]
short_authors: Yang et al.
---
Self-supervised learning (SSL) has proven vital for advancing research in
natural language processing (NLP) and computer vision (CV). The paradigm
pretrains a shared model on large volumes of unlabeled data and achieves
state-of-the-art (SOTA) for various tasks with minimal adaptation. However, the
speech processing community lacks a similar setup to systematically explore the
paradigm. To bridge this gap, we introduce Speech processing Universal
PERformance Benchmark (SUPERB). SUPERB is a leaderboard to benchmark the
performance of a shared model across a wide range of speech processing tasks
with minimal architecture changes and labeled data. Among multiple usages of
the shared model, we especially focus on extracting the representation learned
from SSL due to its preferable re-usability. We present a simple framework to
solve SUPERB tasks by learning task-specialized lightweight prediction heads on
top of the frozen shared model. Our results demonstrate that the framework is
promising as SSL representations show competitive generalizability and
accessibility across SUPERB tasks. We release SUPERB as a challenge with a
leaderboard and a benchmark toolkit to fuel the research in representation
learning and general speech processing.