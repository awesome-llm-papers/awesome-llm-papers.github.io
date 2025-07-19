---
layout: publication
title: Outlier Dimensions Favor Frequent Tokens In Language Models
authors: Macocco et al.
conference: Computer Science and Information Systems
year: 2025
bibkey: macocco2025outlier
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.21718'}]
tags: [Training Techniques]
---
We study last-layer outlier dimensions, i.e. dimensions that display extreme
activations for the majority of inputs. We show that outlier dimensions arise
in many different modern language models, and trace their function back to the
heuristic of constantly predicting frequent words. We further show how a model
can block this heuristic when it is not contextually appropriate, by assigning
a counterbalancing weight mass to the remaining dimensions, and we investigate
which model parameters boost outlier dimensions and when they arise during
training. We conclude that outlier dimensions are a specialized mechanism
discovered by many distinct models to implement a useful token prediction
heuristic.