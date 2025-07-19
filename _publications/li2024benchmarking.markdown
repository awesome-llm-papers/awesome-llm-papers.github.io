---
layout: publication
title: 'Benchmarking Retrieval-augmented Large Language Models In Biomedical NLP:
  Application, Robustness, And Self-awareness'
authors: Li et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2024
bibkey: li2024benchmarking
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.08151'}]
tags: [RAG, Tools, Evaluation, Reinforcement Learning, Security, AAAI, Datasets]
---
Large language models (LLM) have demonstrated remarkable capabilities in
various biomedical natural language processing (NLP) tasks, leveraging the
demonstration within the input context to adapt to new tasks. However, LLM is
sensitive to the selection of demonstrations. To address the hallucination
issue inherent in LLM, retrieval-augmented LLM (RAL) offers a solution by
retrieving pertinent information from an established database. Nonetheless,
existing research work lacks rigorous evaluation of the impact of
retrieval-augmented large language models on different biomedical NLP tasks.
This deficiency makes it challenging to ascertain the capabilities of RAL
within the biomedical domain. Moreover, the outputs from RAL are affected by
retrieving the unlabeled, counterfactual, or diverse knowledge that is not well
studied in the biomedical domain. However, such knowledge is common in the real
world. Finally, exploring the self-awareness ability is also crucial for the
RAL system. So, in this paper, we systematically investigate the impact of RALs
on 5 different biomedical tasks (triple extraction, link prediction,
classification, question answering, and natural language inference). We analyze
the performance of RALs in four fundamental abilities, including unlabeled
robustness, counterfactual robustness, diverse robustness, and negative
awareness. To this end, we proposed an evaluation framework to assess the RALs'
performance on different biomedical NLP tasks and establish four different
testbeds based on the aforementioned fundamental abilities. Then, we evaluate 3
representative LLMs with 3 different retrievers on 5 tasks over 9 datasets.