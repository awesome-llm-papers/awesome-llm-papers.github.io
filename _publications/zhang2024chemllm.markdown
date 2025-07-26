---
layout: publication
title: 'Chemllm: A Chemical Large Language Model'
authors: di Zhang, Wei Liu, Qian Tan, Jingdan Chen, Hang Yan, Yuliang Yan, Jiatong
  Li, Weiran Huang, Xiangyu Yue, Dongzhan Zhou, Shufei Zhang, Mao Su, Hansen Zhong,
  Yuqiang Li, Wanli Ouyang
conference: No Venue
year: 2024
bibkey: zhang2024chemllm
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65cad647ef77197acfba6a3a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2402.06852'}]
tags: ["Applications", "Model Architecture"]
short_authors: Zhang et al.
---
Large language models (LLMs) have made impressive progress in chemistry applications, including molecular property prediction, molecular generation, experimental protocol design, etc. However, the community lacks a dialogue-based model specifically designed for chemistry. The challenge arises from the fact that most chemical data and scientific knowledge are primarily stored in structured databases, and the direct use of these structured data compromises the model's ability to maintain coherent dialogue. To tackle this issue, we develop a novel template-based instruction construction method that transforms structured knowledge into plain dialogue, making it suitable for language model training. By leveraging this approach, we develop ChemLLM, the first large language model dedicated to chemistry, capable of performing various tasks across chemical disciplines with smooth dialogue interaction. ChemLLM beats GPT-3.5 on all three principal tasks in chemistry, i.e., name conversion, molecular caption, and reaction prediction, and surpasses GPT-4 on two of them. Remarkably, ChemLLM also shows exceptional adaptability to related mathematical and physical tasks despite being trained mainly on chemical-centric corpora. Furthermore, ChemLLM demonstrates proficiency in specialized NLP tasks within chemistry, such as literature translation and cheminformatic programming. ChemLLM opens up a new avenue for exploration within chemical studies, while our method of integrating structured chemical knowledge into dialogue systems sets a new frontier for developing LLMs across various scientific fields. Codes, Datasets, and Model weights are publicly accessible at hf.co/AI4Chem/ChemLLM-7B-Chat.

https://huggingface.co/discussions/paper/65cad647ef77197acfba6a3a