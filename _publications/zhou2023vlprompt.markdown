---
layout: publication
title: 'Vlprompt: Vision-language Prompting For Panoptic Scene Graph Generation'
authors: Zhou Zijian, Shi Miaojing, Caesar Holger
conference: Lecture Notes in Computer Science
year: 2023
bibkey: zhou2023vlprompt
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.16492'}]
tags: [RAG, Attention Mechanism, Prompting, Model Architecture, Reinforcement Learning,
  Applications, Multimodal Models, Datasets]
---
Panoptic Scene Graph Generation (PSG) aims at achieving a comprehensive image
understanding by simultaneously segmenting objects and predicting relations
among objects. However, the long-tail problem among relations leads to
unsatisfactory results in real-world applications. Prior methods predominantly
rely on vision information or utilize limited language information, such as
object or relation names, thereby overlooking the utility of language
information. Leveraging the recent progress in Large Language Models (LLMs), we
propose to use language information to assist relation prediction, particularly
for rare relations. To this end, we propose the Vision-Language Prompting
(VLPrompt) model, which acquires vision information from images and language
information from LLMs. Then, through a prompter network based on attention
mechanism, it achieves precise relation prediction. Our extensive experiments
show that VLPrompt significantly outperforms previous state-of-the-art methods
on the PSG dataset, proving the effectiveness of incorporating language
information and alleviating the long-tail problem of relations. Code is
available at https://github.com/franciszzj/TP-SIS.