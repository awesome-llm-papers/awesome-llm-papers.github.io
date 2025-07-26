---
layout: publication
title: End-to-end Joint Learning Of Natural Language Understanding And Dialogue Manager
authors: Xuesong Yang, Yun-nung Chen, Dilek Hakkani-tur, Paul Crook, Xiujun Li, Jianfeng
  Gao, Li Deng
conference: 2017 IEEE International Conference on Acoustics, Speech and Signal Processing
  (ICASSP)
year: 2017
bibkey: yang2016end
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1612.00913'}]
tags: ["ICASSP"]
short_authors: Yang et al.
---
Natural language understanding and dialogue policy learning are both
essential in conversational systems that predict the next system actions in
response to a current user utterance. Conventional approaches aggregate
separate models of natural language understanding (NLU) and system action
prediction (SAP) as a pipeline that is sensitive to noisy outputs of
error-prone NLU. To address the issues, we propose an end-to-end deep recurrent
neural network with limited contextual dialogue memory by jointly training NLU
and SAP on DSTC4 multi-domain human-human dialogues. Experiments show that our
proposed model significantly outperforms the state-of-the-art pipeline models
for both NLU and SAP, which indicates that our joint model is capable of
mitigating the affects of noisy NLU outputs, and NLU model can be refined by
error flows backpropagating from the extra supervised signals of system
actions.