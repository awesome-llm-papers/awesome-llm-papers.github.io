---
layout: publication
title: 'Align, Reason And Learn: Enhancing Medical Vision-and-language Pre-training
  With Knowledge'
authors: Chen Zhihong, Li Guanbin, Wan Xiang
conference: Proceedings of the 30th ACM International Conference on Multimedia
year: 2022
bibkey: chen2022align
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.07118'}]
tags: [Training Techniques, Attention Mechanism, Alt, Evaluation, Model Architecture,
  Datasets, Merging]
---
Medical vision-and-language pre-training (Med-VLP) has received considerable
attention owing to its applicability to extracting generic vision-and-language
representations from medical images and texts. Most existing methods mainly
contain three elements: uni-modal encoders (i.e., a vision encoder and a
language encoder), a multi-modal fusion module, and pretext tasks, with few
studies considering the importance of medical domain expert knowledge and
explicitly exploiting such knowledge to facilitate Med-VLP. Although there
exist knowledge-enhanced vision-and-language pre-training (VLP) methods in the
general domain, most require off-the-shelf toolkits (e.g., object detectors and
scene graph parsers), which are unavailable in the medical domain. In this
paper, we propose a systematic and effective approach to enhance Med-VLP by
structured medical knowledge from three perspectives. First, considering
knowledge can be regarded as the intermediate medium between vision and
language, we align the representations of the vision encoder and the language
encoder through knowledge. Second, we inject knowledge into the multi-modal
fusion model to enable the model to perform reasoning using knowledge as the
supplementation of the input image and text. Third, we guide the model to put
emphasis on the most critical information in images and texts by designing
knowledge-induced pretext tasks. To perform a comprehensive evaluation and
facilitate further research, we construct a medical vision-and-language
benchmark including three tasks. Experimental results illustrate the
effectiveness of our approach, where state-of-the-art performance is achieved
on all downstream tasks. Further analyses explore the effects of different
components of our approach and various settings of pre-training.