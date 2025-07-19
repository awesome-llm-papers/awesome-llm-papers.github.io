---
layout: publication
title: 'Graphflow: Exploiting Conversation Flow With Graph Neural Networks For Conversational
  Machine Comprehension'
authors: Chen Yu, Wu Lingfei, Zaki Mohammed J.
conference: Proceedings of the Twenty-Ninth International Joint Conference on Artificial
  Intelligence
year: 2019
bibkey: chen2019graphflow
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.00059'}]
tags: [Interpretability And Explainability, Evaluation, AAAI, IJCAI, Datasets]
---
Conversational machine comprehension (MC) has proven significantly more
challenging compared to traditional MC since it requires better utilization of
conversation history. However, most existing approaches do not effectively
capture conversation history and thus have trouble handling questions involving
coreference or ellipsis. Moreover, when reasoning over passage text, most of
them simply treat it as a word sequence without exploring rich semantic
relationships among words. In this paper, we first propose a simple yet
effective graph structure learning technique to dynamically construct a
question and conversation history aware context graph at each conversation
turn. Then we propose a novel Recurrent Graph Neural Network, and based on
that, we introduce a flow mechanism to model the temporal dependencies in a
sequence of context graphs. The proposed GraphFlow model can effectively
capture conversational flow in a dialog, and shows competitive performance
compared to existing state-of-the-art methods on CoQA, QuAC and DoQA
benchmarks. In addition, visualization experiments show that our proposed model
can offer good interpretability for the reasoning process.