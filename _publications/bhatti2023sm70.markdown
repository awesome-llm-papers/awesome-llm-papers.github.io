---
layout: publication
title: 'SM70: A Large Language Model For Medical Devices'
authors: Bhatti Anubhav, Parmar Surajsinh, Lee San
conference: Nature Medicine
year: 2023
bibkey: bhatti2023sm70
citations: 123
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.06974'}]
tags: [Training Techniques, GPT, Evaluation, Model Architecture, Reinforcement Learning,
  Fine Tuning, Datasets]
---
We are introducing SM70, a 70 billion-parameter Large Language Model that is
specifically designed for SpassMed's medical devices under the brand name
'JEE1' (pronounced as G1 and means 'Life'). This large language model provides
more accurate and safe responses to medical-domain questions. To fine-tune
SM70, we used around 800K data entries from the publicly available dataset
MedAlpaca. The Llama2 70B open-sourced model served as the foundation for SM70,
and we employed the QLoRA technique for fine-tuning. The evaluation is
conducted across three benchmark datasets - MEDQA - USMLE, PUBMEDQA, and USMLE
- each representing a unique aspect of medical knowledge and reasoning. The
performance of SM70 is contrasted with other notable LLMs, including Llama2
70B, Clinical Camel 70 (CC70), GPT 3.5, GPT 4, and Med-Palm, to provide a
comparative understanding of its capabilities within the medical domain. Our
results indicate that SM70 outperforms several established models in these
datasets, showcasing its proficiency in handling a range of medical queries,
from fact-based questions derived from PubMed abstracts to complex clinical
decision-making scenarios. The robust performance of SM70, particularly in the
USMLE and PUBMEDQA datasets, suggests its potential as an effective tool in
clinical decision support and medical information retrieval. Despite its
promising results, the paper also acknowledges the areas where SM70 lags behind
the most advanced model, GPT 4, thereby highlighting the need for further
development, especially in tasks demanding extensive medical knowledge and
intricate reasoning.