---
layout: publication
title: 'SPAR: Personalized Content-based Recommendation Via Long Engagement Attention'
authors: Chiyu Zhang, Yifei Sun, Jun Chen, Jie Lei, Muhammad Abdul-mageed, Sinong
  Wang, Rong Jin, Sem Park, Ning Yao, Bo Long
conference: No Venue
year: 2024
bibkey: zhang2024spar
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65d2dc3dc6f238f8687cd64e'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2402.10555'}]
tags: ["Datasets", "Evaluation", "Tools"]
short_authors: Zhang et al.
---
Leveraging users' long engagement histories is essential for personalized content recommendations. The success of pretrained language models (PLMs) in NLP has led to their use in encoding user histories and candidate items, framing content recommendations as textual semantic matching tasks. However, existing works still struggle with processing very long user historical text and insufficient user-item interaction. In this paper, we introduce a content-based recommendation framework, SPAR, which effectively tackles the challenges of holistic user interest extraction from the long user engagement history. It achieves so by leveraging PLM, poly-attention layers and attention sparsity mechanisms to encode user's history in a session-based manner. The user and item side features are sufficiently fused for engagement prediction while maintaining standalone representations for both sides, which is efficient for practical model deployment. Moreover, we enhance user profiling by exploiting large language model (LLM) to extract global interests from user engagement history. Extensive experiments on two benchmark datasets demonstrate that our framework outperforms existing state-of-the-art (SoTA) methods.

https://huggingface.co/discussions/paper/65d2dc3dc6f238f8687cd64e