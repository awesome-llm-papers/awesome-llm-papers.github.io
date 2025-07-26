---
layout: publication
title: On Extended Long Short-term Memory And Dependent Bidirectional Recurrent Neural
  Network
authors: Yuanhang Su, C. -c. Jay Kuo
conference: Neurocomputing
year: 2019
bibkey: su2018extended
citations: 159
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1803.01686'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Yuanhang Su, C. -c. Jay Kuo
---
In this work, we first analyze the memory behavior in three recurrent neural
networks (RNN) cells; namely, the simple RNN (SRN), the long short-term memory
(LSTM) and the gated recurrent unit (GRU), where the memory is defined as a
function that maps previous elements in a sequence to the current output. Our
study shows that all three of them suffer rapid memory decay. Then, to
alleviate this effect, we introduce trainable scaling factors that act like an
attention mechanism to adjust memory decay adaptively. The new design is called
the extended LSTM (ELSTM). Finally, to design a system that is robust to
previous erroneous predictions, we propose a dependent bidirectional recurrent
neural network (DBRNN). Extensive experiments are conducted on different
language tasks to demonstrate the superiority of the proposed ELSTM and DBRNN
solutions. The ELTSM has achieved up to 30% increase in the labeled attachment
score (LAS) as compared to LSTM and GRU in the dependency parsing (DP) task.
Our models also outperform other state-of-the-art models such as bi-attention
and convolutional sequence to sequence (convseq2seq) by close to 10% in the
LAS. The code is released as an open source
(https://github.com/yuanhangsu/ELSTM-DBRNN)