---
layout: publication
title: 'Better Rewards Yield Better Summaries: Learning To Summarise Without References'
authors: "B\xF6hm et al."
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: "b\xF6hm2019better"
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.01214'}]
tags: [Training Techniques, EMNLP, Agentic, Evaluation, Reinforcement Learning]
---
Reinforcement Learning (RL) based document summarisation systems yield
state-of-the-art performance in terms of ROUGE scores, because they directly
use ROUGE as the rewards during training. However, summaries with high ROUGE
scores often receive low human judgement. To find a better reward function that
can guide RL to generate human-appealing summaries, we learn a reward function
from human ratings on 2,500 summaries. Our reward function only takes the
document and system summary as input. Hence, once trained, it can be used to
train RL-based summarisation systems without using any reference summaries. We
show that our learned rewards have significantly higher correlation with human
ratings than previous approaches. Human evaluation experiments show that,
compared to the state-of-the-art supervised-learning systems and
ROUGE-as-rewards RL summarisation systems, the RL systems using our learned
rewards during training generate summarieswith higher human ratings. The
learned reward function and our source code are available at
https://github.com/yg211/summary-reward-no-reference.