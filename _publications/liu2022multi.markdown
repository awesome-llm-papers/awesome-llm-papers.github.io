---
layout: publication
title: Multi-stage Prompting For Knowledgeable Dialogue Generation
authors: Zihan Liu et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2022'
year: 2022
citations: 15
bibkey: liu2022multi
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.08745'}, {name: Code,
    url: 'https://github.com/NVIDIA/Megatron-LM'}]
tags: [Has Code, RAG, Prompting]
---
Existing knowledge-grounded dialogue systems typically use finetuned versions
of a pretrained language model (LM) and large-scale knowledge bases. These
models typically fail to generalize on topics outside of the knowledge base,
and require maintaining separate potentially large checkpoints each time
finetuning is needed. In this paper, we aim to address these limitations by
leveraging the inherent knowledge stored in the pretrained LM as well as its
powerful generation ability. We propose a multi-stage prompting approach to
generate knowledgeable responses from a single pretrained LM. We first prompt
the LM to generate knowledge based on the dialogue context. Then, we further
prompt it to generate responses based on the dialogue context and the
previously generated knowledge. Results show that our knowledge generator
outperforms the state-of-the-art retrieval-based model by 5.8% when combining
knowledge relevance and correctness. In addition, our multi-stage prompting
outperforms the finetuning-based dialogue model in terms of response
knowledgeability and engagement by up to 10% and 5%, respectively. Furthermore,
we scale our model up to 530 billion parameters and show that larger LMs
improve the generation correctness score by up to 10%, and response relevance,
knowledgeability and engagement by up to 10%. Our code is available at:
https://github.com/NVIDIA/Megatron-LM.