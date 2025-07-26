---
layout: publication
title: 'Bert4rec: Sequential Recommendation With Bidirectional Encoder Representations
  From Transformer'
authors: Fei Sun, Jun Liu, Jian Wu, Changhua Pei, Xiao Lin, Wenwu Ou, Peng Jiang
conference: Arxiv
year: 2019
bibkey: sun2019bert4rec
citations: 260
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.06690'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Sun et al.
---
Modeling users' dynamic and evolving preferences from their historical
behaviors is challenging and crucial for recommendation systems. Previous
methods employ sequential neural networks (e.g., Recurrent Neural Network) to
encode users' historical interactions from left to right into hidden
representations for making recommendations. Although these methods achieve
satisfactory results, they often assume a rigidly ordered sequence which is not
always practical. We argue that such left-to-right unidirectional architectures
restrict the power of the historical sequence representations. For this
purpose, we introduce a Bidirectional Encoder Representations from Transformers
for sequential Recommendation (BERT4Rec). However, jointly conditioning on both
left and right context in deep bidirectional model would make the training
become trivial since each item can indirectly "see the target item". To address
this problem, we train the bidirectional model using the Cloze task, predicting
the masked items in the sequence by jointly conditioning on their left and
right context. Comparing with predicting the next item at each position in a
sequence, the Cloze task can produce more samples to train a more powerful
bidirectional model. Extensive experiments on four benchmark datasets show that
our model outperforms various state-of-the-art sequential models consistently.