---
layout: publication
title: A Recurrent Vision-and-language BERT For Navigation
authors: Yicong Hong, Qi Wu, Yuankai Qi, Cristian Rodriguez-opazo, Stephen Gould
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2021
bibkey: hong2020recurrent
citations: 143
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.13922'}]
tags: ["CVPR", "Model Architecture"]
short_authors: Hong et al.
---
Accuracy of many visiolinguistic tasks has benefited significantly from the
application of vision-and-language(V&L) BERT. However, its application for the
task of vision-and-language navigation (VLN) remains limited. One reason for
this is the difficulty adapting the BERT architecture to the partially
observable Markov decision process present in VLN, requiring history-dependent
attention and decision making. In this paper we propose a recurrent BERT model
that is time-aware for use in VLN. Specifically, we equip the BERT model with a
recurrent function that maintains cross-modal state information for the agent.
Through extensive experiments on R2R and REVERIE we demonstrate that our model
can replace more complex encoder-decoder models to achieve state-of-the-art
results. Moreover, our approach can be generalised to other transformer-based
architectures, supports pre-training, and is capable of solving navigation and
referring expression tasks simultaneously.