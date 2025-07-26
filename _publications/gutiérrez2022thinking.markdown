---
layout: publication
title: Thinking About GPT-3 In-context Learning For Biomedical IE? Think Again
authors: "Bernal Jim\xE9nez Guti\xE9rrez, Nikolas Mcneal, Clay Washington, You Chen,\
  \ Lang Li, Huan Sun, Yu Su"
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2022'
year: 2022
bibkey: "guti\xE9rrez2022thinking"
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.08410'}]
tags: ["EMNLP"]
short_authors: "Guti\xE9rrez et al."
---
The strong few-shot in-context learning capability of large pre-trained
language models (PLMs) such as GPT-3 is highly appealing for application
domains such as biomedicine, which feature high and diverse demands of language
technologies but also high data annotation costs. In this paper, we present the
first systematic and comprehensive study to compare the few-shot performance of
GPT-3 in-context learning with fine-tuning smaller (i.e., BERT-sized) PLMs on
two highly representative biomedical information extraction tasks, named entity
recognition and relation extraction. We follow the true few-shot setting to
avoid overestimating models' few-shot performance by model selection over a
large validation set. We also optimize GPT-3's performance with known
techniques such as contextual calibration and dynamic in-context example
retrieval. However, our results show that GPT-3 still significantly
underperforms compared to simply fine-tuning a smaller PLM. In addition, GPT-3
in-context learning also yields smaller gains in accuracy when more training
data becomes available. Our in-depth analyses further reveal issues of the
in-context learning setting that may be detrimental to information extraction
tasks in general. Given the high cost of experimenting with GPT-3, we hope our
study provides guidance for biomedical researchers and practitioners towards
more promising directions such as fine-tuning small PLMs.