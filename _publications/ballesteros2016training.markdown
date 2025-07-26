---
layout: publication
title: Training With Exploration Improves A Greedy Stack-lstm Parser
authors: Miguel Ballesteros, Yoav Goldberg, Chris Dyer, Noah A. Smith
conference: Proceedings of the 2016 Conference on Empirical Methods in Natural Language
  Processing
year: 2016
bibkey: ballesteros2016training
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1603.03793'}]
tags: ["EMNLP", "Model Architecture", "Training Techniques"]
short_authors: Ballesteros et al.
---
We adapt the greedy Stack-LSTM dependency parser of Dyer et al. (2015) to
support a training-with-exploration procedure using dynamic oracles(Goldberg
and Nivre, 2013) instead of cross-entropy minimization. This form of training,
which accounts for model predictions at training time rather than assuming an
error-free action history, improves parsing accuracies for both English and
Chinese, obtaining very strong results for both languages. We discuss some
modifications needed in order to get training with exploration to work well for
a probabilistic neural-network.