---
layout: publication
title: Large Language Model-guided Prediction Toward Quantum Materials Synthesis
authors: Okabe et al.
conference: Proceedings 2024 Network and Distributed System Security Symposium
year: 2024
bibkey: okabe2024large
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.20976'}]
tags: [Fine Tuning, Tools, Training Techniques, Security]
---
The synthesis of inorganic crystalline materials is essential for modern
technology, especially in quantum materials development. However, designing
efficient synthesis workflows remains a significant challenge due to the
precise experimental conditions and extensive trial and error. Here, we present
a framework using large language models (LLMs) to predict synthesis pathways
for inorganic materials, including quantum materials. Our framework contains
three models: LHS2RHS, predicting products from reactants; RHS2LHS, predicting
reactants from products; and TGT2CEQ, generating full chemical equations for
target compounds. Fine-tuned on a text-mined synthesis database, our model
raises accuracy from under 40% with pretrained models, to under 80% using
conventional fine-tuning, and further to around 90% with our proposed
generalized Tanimoto similarity, while maintaining robust to additional
synthesis steps. Our model further demonstrates comparable performance across
materials with varying degrees of quantumness quantified using quantum weight,
indicating that LLMs offer a powerful tool to predict balanced chemical
equations for quantum materials discovery.