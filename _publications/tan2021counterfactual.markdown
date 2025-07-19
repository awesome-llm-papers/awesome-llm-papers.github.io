---
layout: publication
title: Counterfactual Explainable Recommendation
authors: Tan et al.
conference: Proceedings of the 30th ACM International Conference on Information &amp;
  Knowledge Management
year: 2021
bibkey: tan2021counterfactual
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.10539'}]
tags: [Tools, Interpretability And Explainability, Efficiency And Optimization, Evaluation,
  Datasets, Reinforcement Learning, CIKM, Alt]
---
By providing explanations for users and system designers to facilitate better
understanding and decision making, explainable recommendation has been an
important research problem. In this paper, we propose Counterfactual
Explainable Recommendation (CountER), which takes the insights of
counterfactual reasoning from causal inference for explainable recommendation.
CountER is able to formulate the complexity and the strength of explanations,
and it adopts a counterfactual learning framework to seek simple (low
complexity) and effective (high strength) explanations for the model decision.
Technically, for each item recommended to each user, CountER formulates a joint
optimization problem to generate minimal changes on the item aspects so as to
create a counterfactual item, such that the recommendation decision on the
counterfactual item is reversed. These altered aspects constitute the
explanation of why the original item is recommended. The counterfactual
explanation helps both the users for better understanding and the system
designers for better model debugging. Another contribution of the work is the
evaluation of explainable recommendation, which has been a challenging task.
Fortunately, counterfactual explanations are very suitable for standard
quantitative evaluation. To measure the explanation quality, we design two
types of evaluation metrics, one from user's perspective (i.e. why the user
likes the item), and the other from model's perspective (i.e. why the item is
recommended by the model). We apply our counterfactual learning algorithm on a
black-box recommender system and evaluate the generated explanations on five
real-world datasets. Results show that our model generates more accurate and
effective explanations than state-of-the-art explainable recommendation models.