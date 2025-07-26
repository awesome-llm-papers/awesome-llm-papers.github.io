---
layout: publication
title: Are We Done With MMLU?
authors: Aryo Pradipta Gema, Joshua Ong Jun Leang, Giwon Hong, Alessio Devoto, Alberto
  Carlo Maria Mancino, Rohit Saxena, Xuanli He, Yu Zhao, Xiaotang Du, Mohammad Reza
  Ghasemi Madani, Claire Barale, Robert Mchardy, Joshua Harris, Jean Kaddour, Emile
  van Krieken, Pasquale Minervini
conference: No Venue
year: 2024
bibkey: gema2024are
additional_links: [{name: Code, url: 'https://huggingface.co/datasets/edinburgh-dawg/mmlu-redux'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/66636e5f0b562c29c5bddabf'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.04127'}]
tags: ["Datasets", "Evaluation Frameworks", "Evaluation"]
short_authors: Gema et al.
---
Maybe not. We identify and analyse errors in the popular Massive Multitask Language Understanding (MMLU) benchmark. Even though MMLU is widely adopted, our analysis demonstrates numerous ground truth errors that obscure the true capabilities of LLMs. For example, we find that 57% of the analysed questions in the Virology subset contain errors. To address this issue, we introduce a comprehensive framework for identifying dataset errors using a novel error taxonomy. Then, we create MMLU-Redux, which is a subset of 3,000 manually re-annotated questions across 30 MMLU subjects. Using MMLU-Redux, we demonstrate significant discrepancies with the model performance metrics that were originally reported. Our results strongly advocate for revising MMLU's error-ridden questions to enhance its future utility and reliability as a benchmark. Therefore, we open up MMLU-Redux for additional annotation https://huggingface.co/datasets/edinburgh-dawg/mmlu-redux.

https://huggingface.co/discussions/paper/66636e5f0b562c29c5bddabf