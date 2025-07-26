---
layout: publication
title: Reinforcement Learning For Bandit Neural Machine Translation With Simulated
  Human Feedback
authors: "Khanh Nguyen, Hal Daum\xE9, Jordan Boyd-graber"
conference: Proceedings of the 2017 Conference on Empirical Methods in Natural Language
  Processing
year: 2017
bibkey: nguyen2017reinforcement
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.07402'}]
tags: ["EMNLP", "Reinforcement Learning"]
short_authors: "Khanh Nguyen, Hal Daum\xE9, Jordan Boyd-graber"
---
Machine translation is a natural candidate problem for reinforcement learning
from human feedback: users provide quick, dirty ratings on candidate
translations to guide a system to improve. Yet, current neural machine
translation training focuses on expensive human-generated reference
translations. We describe a reinforcement learning algorithm that improves
neural machine translation systems from simulated human feedback. Our algorithm
combines the advantage actor-critic algorithm (Mnih et al., 2016) with the
attention-based neural encoder-decoder architecture (Luong et al., 2015). This
algorithm (a) is well-designed for problems with a large action space and
delayed rewards, (b) effectively optimizes traditional corpus-level machine
translation metrics, and (c) is robust to skewed, high-variance, granular
feedback modeled after actual human behaviors.