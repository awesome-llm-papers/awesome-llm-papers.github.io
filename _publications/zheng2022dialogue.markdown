---
layout: publication
title: 'Augesc: Dialogue Augmentation With Large Language Models For Emotional Support
  Conversation'
authors: Chujie Zheng, Sahand Sabour, Jiaxin Wen, Zheng Zhang, Minlie Huang
conference: 'Findings of the Association for Computational Linguistics: ACL 2023'
year: 2022
citations: 15
bibkey: zheng2022dialogue
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.13047'}]
tags: [RAG, Reinforcement Learning, Prompting, Training Techniques, Evaluation]
---
Crowdsourced dialogue corpora are usually limited in scale and topic coverage
due to the expensive cost of data curation. This would hinder the
generalization of downstream dialogue models to open-domain topics. In this
work, we leverage large language models for dialogue augmentation in the task
of emotional support conversation (ESC). By treating dialogue augmentation as a
dialogue completion task, we prompt a fine-tuned language model to complete
full dialogues from available dialogue posts of various topics, which are then
postprocessed based on heuristics. Applying this approach, we construct AugESC,
an augmented dataset for the ESC task, which largely extends the scale and
topic coverage of the crowdsourced ESConv corpus. Through comprehensive human
evaluation, we demonstrate that our approach is superior to strong baselines of
dialogue augmentation and that AugESC has comparable dialogue quality to the
crowdsourced corpus. We also conduct human interactive evaluation and prove
that post-training on AugESC improves downstream dialogue models'
generalization ability to open-domain topics. These results suggest the utility
of AugESC and highlight the potential of large language models in improving
data-scarce dialogue generation tasks.