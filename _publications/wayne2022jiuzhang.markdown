---
layout: publication
title: 'Jiuzhang: A Chinese Pre-trained Language Model For Mathematical Problem Understanding'
authors: Wayne Xin Zhao, Kun Zhou, Zheng Gong, Beichen Zhang, Yuanhang Zhou, Jing
  Sha, Zhigang Chen, Shijin Wang, Cong Liu, Ji-rong Wen
conference: Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and
  Data Mining
year: 2022
bibkey: wayne2022jiuzhang
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2206.06315v1'}]
tags: [Training Techniques, Evaluation, Ethics And Bias, KDD]
---
This paper aims to advance the mathematical intelligence of machines by
presenting the first Chinese mathematical pre-trained language model~(PLM) for
effectively understanding and representing mathematical problems. Unlike other
standard NLP tasks, mathematical texts are difficult to understand, since they
involve mathematical terminology, symbols and formulas in the problem
statement. Typically, it requires complex mathematical logic and background
knowledge for solving mathematical problems.
  Considering the complex nature of mathematical texts, we design a novel
curriculum pre-training approach for improving the learning of mathematical
PLMs, consisting of both basic and advanced courses. Specially, we first
perform token-level pre-training based on a position-biased masking strategy,
and then design logic-based pre-training tasks that aim to recover the shuffled
sentences and formulas, respectively. Finally, we introduce a more difficult
pre-training task that enforces the PLM to detect and correct the errors in its
generated solutions. We conduct extensive experiments on offline evaluation
(including nine math-related tasks) and online \\(A/B\\) test. Experimental results
demonstrate the effectiveness of our approach compared with a number of
competitive baselines. Our code is available at:
\textcolor\{blue\}\{https://github.com/RUCAIBox/JiuZhang\}.