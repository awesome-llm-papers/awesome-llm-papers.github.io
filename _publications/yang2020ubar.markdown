---
layout: publication
title: 'UBAR: Towards Fully End-to-end Task-oriented Dialog Systems With GPT-2'
authors: Yunyi Yang, Yunhao Li, Xiaojun Quan
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: yang2020ubar
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.03539'}]
tags: ["AAAI", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Yunyi Yang, Yunhao Li, Xiaojun Quan
---
This paper presents our task-oriented dialog system UBAR which models
task-oriented dialogs on a dialog session level. Specifically, UBAR is acquired
by fine-tuning the large pre-trained unidirectional language model GPT-2 on the
sequence of the entire dialog session which is composed of user utterance,
belief state, database result, system act, and system response of every dialog
turn. Additionally, UBAR is evaluated in a more realistic setting, where its
dialog context has access to user utterances and all content it generated such
as belief states, system acts, and system responses. Experimental results on
the MultiWOZ datasets show that UBAR achieves state-of-the-art performances in
multiple settings, improving the combined score of response generation, policy
optimization, and end-to-end modeling by 4.7, 3.5, and 9.4 points respectively.
Thorough analyses demonstrate that the session-level training sequence
formulation and the generated dialog context are essential for UBAR to operate
as a fully end-to-end task-oriented dialog system in real life. We also examine
the transfer ability of UBAR to new domains with limited data and provide
visualization and a case study to illustrate the advantages of UBAR in modeling
on a dialog session level.