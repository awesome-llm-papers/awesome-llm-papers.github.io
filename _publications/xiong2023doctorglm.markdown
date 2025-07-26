---
layout: publication
title: 'Doctorglm: Fine-tuning Your Chinese Doctor Is Not A Herculean Task'
authors: Honglin Xiong, Sheng Wang, Yitao Zhu, Zihao Zhao, Yuxiao Liu, Linlin Huang,
  Qian Wang, Dinggang Shen
conference: Arxiv
year: 2023
bibkey: xiong2023doctorglm
citations: 60
additional_links: [{name: Code, url: 'https://github.com/xionghonglin/DoctorGLM'},
  {name: Paper, url: 'https://arxiv.org/abs/2304.01097'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Xiong et al.
---
The recent progress of large language models (LLMs), including ChatGPT and
GPT-4, in comprehending and responding to human instructions has been
remarkable. Nevertheless, these models typically perform better in English and
have not been explicitly trained for the medical domain, resulting in
suboptimal precision in diagnoses, drug recommendations, and other medical
advice. Additionally, training and deploying a dialogue model is still believed
to be impossible for hospitals, hindering the promotion of LLMs. To tackle
these challenges, we have collected databases of medical dialogues in Chinese
with ChatGPT's help and adopted several techniques to train an easy-deploy LLM.
Remarkably, we were able to fine-tune the ChatGLM-6B on a single A100 80G in 13
hours, which means having a healthcare-purpose LLM can be very affordable.
DoctorGLM is currently an early-stage engineering attempt and contain various
mistakes. We are sharing it with the broader community to invite feedback and
suggestions to improve its healthcare-focused capabilities:
https://github.com/xionghonglin/DoctorGLM.