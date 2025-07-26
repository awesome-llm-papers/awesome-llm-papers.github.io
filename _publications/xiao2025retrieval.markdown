---
layout: publication
title: Retrieval-augmented Large Language Models For Financial Time Series Forecasting
authors: Mengxi Xiao, Zihao Jiang, Lingfei Qian, Zhengyu Chen, Yueru He, Yijing Xu,
  Yuecheng Jiang, Dong Li, Ruey-ling Weng, Min Peng, Jimin Huang, Sophia Ananiadou,
  Qianqian Xie
conference: No Venue
year: 2025
bibkey: xiao2025retrieval
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.05878'}]
tags: ["RAG", "Retrieval Systems", "Time Series"]
short_authors: Xiao et al.
---
Stock movement prediction, a fundamental task in financial time-series forecasting, requires identifying and retrieving critical influencing factors from vast amounts of time-series data. However, existing text-trained or numeric similarity-based retrieval methods fall short in handling complex financial analysis. To address this, we propose the first retrieval-augmented generation (RAG) framework for financial time-series forecasting, featuring three key innovations: a fine-tuned 1B parameter large language model (StockLLM) as the backbone, a novel candidate selection method leveraging LLM feedback, and a training objective that maximizes similarity between queries and historically significant sequences. This enables our retriever, FinSeer, to uncover meaningful patterns while minimizing noise in complex financial data. We also construct new datasets integrating financial indicators and historical stock prices to train FinSeer and ensure robust evaluation. Experimental results demonstrate that our RAG framework outperforms bare StockLLM and random retrieval, highlighting its effectiveness, while FinSeer surpasses existing retrieval methods, achieving an 8% higher accuracy on BIGDATA22 and retrieving more impactful sequences. This work underscores the importance of tailored retrieval models in financial forecasting and provides a novel framework for future research.

https://huggingface.co/discussions/paper/67aab4ac8642da4d695cf101