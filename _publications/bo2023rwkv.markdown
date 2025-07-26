---
layout: publication
title: 'RWKV: Reinventing Rnns For The Transformer Era'
authors: [bo Peng, eric Alcaide, quentin Anthony, alon Albalak, samuel Arcadinho,
  stella Biderman, huanqi Cao, xin Cheng, michael Chung, matteo Grella, kranthi Kiran
    Gv, xuzheng He, haowen Hou, jiaju Lin, przemyslaw Kazienko, jan Kocon, jiaming
    Kong, bartlomiej Koptyra, hayden Lau, krishna Sri Ipsit Mantri, ferdinand Mom,
  atsushi Saito, guangyu Song, xiangru Tang, bolun Wang, johan S. Wind, stanislaw
    Wozniak, ruichong Zhang, zhenyuan Zhang, qihang Zhao, peng Zhou, qinghua Zhou,
  jian Zhu, rui-jie Zhu]
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2023
bibkey: bo2023rwkv
citations: 117
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2305.13048v2'}]
tags: ["EMNLP", "Model Architecture", "Training Techniques"]
short_authors: Peng et al.
---
Transformers have revolutionized almost all natural language processing (NLP)
tasks but suffer from memory and computational complexity that scales
quadratically with sequence length. In contrast, recurrent neural networks
(RNNs) exhibit linear scaling in memory and computational requirements but
struggle to match the same performance as Transformers due to limitations in
parallelization and scalability. We propose a novel model architecture,
Receptance Weighted Key Value (RWKV), that combines the efficient
parallelizable training of transformers with the efficient inference of RNNs.
  Our approach leverages a linear attention mechanism and allows us to
formulate the model as either a Transformer or an RNN, thus parallelizing
computations during training and maintains constant computational and memory
complexity during inference. We scale our models as large as 14 billion
parameters, by far the largest dense RNN ever trained, and find RWKV performs
on par with similarly sized Transformers, suggesting future work can leverage
this architecture to create more efficient models. This work presents a
significant step towards reconciling trade-offs between computational
efficiency and model performance in sequence processing tasks.