---
layout: publication
title: Learning To Order Sub-questions For Complex Question Answering
authors: Yunan Zhang, Xiang Cheng, Yufeng Zhang, Zihan Wang, Zhengqi Fang, Xiaoyan
  Wang, Zhenya Huang, Chengxiang Zhai
conference: Interspeech 2019
year: 2019
bibkey: zhang2019learning
citations: 149
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.04065'}]
tags: ["INTERSPEECH"]
short_authors: Zhang et al.
---
Answering complex questions involving multiple entities and relations is a
challenging task. Logically, the answer to a complex question should be derived
by decomposing the complex question into multiple simple sub-questions and then
answering those sub-questions. Existing work has followed this strategy but has
not attempted to optimize the order of how those sub-questions are answered. As
a result, the sub-questions are answered in an arbitrary order, leading to
larger search space and a higher risk of missing an answer. In this paper, we
propose a novel reinforcement learning(RL) approach to answering complex
questions that can learn a policy to dynamically decide which sub-question
should be answered at each stage of reasoning. We lever-age the expected
value-variance criterion to enable the learned policy to balance between the
risk and utility of answering a sub-question. Experiment results show that the
RL approach can substantially improve the optimality of ordering the
sub-questions, leading to improved accuracy of question answering. The proposed
method for learning to order sub-questions is general and can thus be
potentially combined with many existing ideas for answering complex questions
to enhance their performance.