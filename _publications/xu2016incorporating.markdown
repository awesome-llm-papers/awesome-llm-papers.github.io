---
layout: publication
title: Incorporating Loose-structured Knowledge Into Conversation Modeling Via Recall-gate
  LSTM
authors: Zhen Xu, Bingquan Liu, Baoxun Wang, Chengjie Sun, Xiaolong Wang
conference: 2017 International Joint Conference on Neural Networks (IJCNN)
year: 2017
bibkey: xu2016incorporating
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1605.05110'}]
tags: ["Model Architecture"]
short_authors: Xu et al.
---
Modeling human conversations is the essence for building satisfying chat-bots
with multi-turn dialog ability. Conversation modeling will notably benefit from
domain knowledge since the relationships between sentences can be clarified due
to semantic hints introduced by knowledge. In this paper, a deep neural network
is proposed to incorporate background knowledge for conversation modeling.
Through a specially designed Recall gate, domain knowledge can be transformed
into the extra global memory of Long Short-Term Memory (LSTM), so as to enhance
LSTM by cooperating with its local memory to capture the implicit semantic
relevance between sentences within conversations. In addition, this paper
introduces the loose structured domain knowledge base, which can be built with
slight amount of manual work and easily adopted by the Recall gate. Our model
is evaluated on the context-oriented response selecting task, and experimental
results on both two datasets have shown that our approach is promising for
modeling human conversations and building key components of automatic chatting
systems.