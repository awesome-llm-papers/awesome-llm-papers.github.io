---
layout: publication
title: 'Llm2rec: Large Language Models Are Powerful Embedding Models For Sequential
  Recommendation'
authors: He et al.
conference: Proceedings of the 17th ACM Conference on Recommender Systems
year: 2025
bibkey: he2025llm2rec
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.21579'}]
tags: [Tools, Fine Tuning, Training Techniques, RecSys, RAG, Datasets, Reinforcement
    Learning]
---
Sequential recommendation aims to predict users' future interactions by modeling collaborative filtering (CF) signals from historical behaviors of similar users or items. Traditional sequential recommenders predominantly rely on ID-based embeddings, which capture CF signals through high-order co-occurrence patterns. However, these embeddings depend solely on past interactions, lacking transferable knowledge to generalize to unseen domains. Recent advances in large language models (LLMs) have motivated text-based recommendation approaches that derive item representations from textual descriptions. While these methods enhance generalization, they fail to encode CF signals-i.e., latent item correlations and preference patterns-crucial for effective recommendation. We argue that an ideal embedding model should seamlessly integrate CF signals with rich semantic representations to improve both in-domain and out-of-domain recommendation performance.
  To this end, we propose LLM2Rec, a novel embedding model tailored for sequential recommendation, integrating the rich semantic understanding of LLMs with CF awareness. Our approach follows a two-stage training framework: (1) Collaborative Supervised Fine-tuning, which adapts LLMs to infer item relationships based on historical interactions, and (2) Item-level Embedding Modeling, which refines these specialized LLMs into structured item embedding models that encode both semantic and collaborative information. Extensive experiments on real-world datasets demonstrate that LLM2Rec effectively improves recommendation quality across both in-domain and out-of-domain settings. Our findings highlight the potential of leveraging LLMs to build more robust, generalizable embedding models for sequential recommendation. Our codes are available at https://github.com/HappyPointer/LLM2Rec.