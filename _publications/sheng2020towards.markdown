---
layout: publication
title: Towards Controllable Biases In Language Generation
authors: Emily Sheng, Kai-wei Chang, Premkumar Natarajan, Nanyun Peng
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: sheng2020towards
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00268'}]
tags: ["EMNLP", "Ethics & Fairness"]
short_authors: Sheng et al.
---
We present a general approach towards controllable societal biases in natural
language generation (NLG). Building upon the idea of adversarial triggers, we
develop a method to induce societal biases in generated text when input prompts
contain mentions of specific demographic groups. We then analyze two scenarios:
1) inducing negative biases for one demographic and positive biases for another
demographic, and 2) equalizing biases between demographics. The former scenario
enables us to detect the types of biases present in the model. Specifically, we
show the effectiveness of our approach at facilitating bias analysis by finding
topics that correspond to demographic inequalities in generated text and
comparing the relative effectiveness of inducing biases for different
demographics. The second scenario is useful for mitigating biases in downstream
applications such as dialogue generation. In our experiments, the mitigation
technique proves to be effective at equalizing the amount of biases across
demographics while simultaneously generating less negatively biased text
overall.