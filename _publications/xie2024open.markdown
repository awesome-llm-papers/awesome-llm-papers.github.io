---
layout: publication
title: 'Open-finllms: Open Multimodal Large Language Models For Financial Applications'
authors: Qianqian Xie, Dong Li, Mengxi Xiao, Zihao Jiang, Ruoyu Xiang, Xiao Zhang,
  Zhengyu Chen, Yueru He, Weiguang Han, Yuzhe Yang, Shunian Chen, Yifei Zhang, Lihang
  Shen, Daniel Kim, Zhiwei Liu, Zheheng Luo, Yangyang Yu, Yupeng Cao, Zhiyang Deng,
  Zhiyuan Yao, Haohang Li, Duanyu Feng, Yongfu Dai, Vijayasai Somasundaram, Peng Lu,
  Yilun Zhao, Yitao Long, Guojun Xiong, Kaleb Smith, Honghai Yu, Yanzhao Lai, Min
  Peng, Jianyun Nie, Jordan W. Suchow, Xiao-yang Liu, Benyou Wang, Alejandro Lopez-lira,
  Jimin Huang, Sophia Ananiadou
conference: No Venue
year: 2024
bibkey: xie2024open
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2408.11878'}]
tags: ["Applications"]
short_authors: Xie et al.
---
Large language models (LLMs) have advanced financial applications, yet they often lack sufficient financial knowledge and struggle with tasks involving multi-modal inputs like tables and time series data. To address these limitations, we introduce Open-FinLLMs, a series of Financial LLMs. We begin with FinLLaMA, pre-trained on a 52 billion token financial corpus, incorporating text, tables, and time-series data to embed comprehensive financial knowledge. FinLLaMA is then instruction fine-tuned with 573K financial instructions, resulting in FinLLaMA-instruct, which enhances task performance. Finally, we present FinLLaVA, a multimodal LLM trained with 1.43M image-text instructions to handle complex financial data types. Extensive evaluations demonstrate FinLLaMA's superior performance over LLaMA3-8B, LLaMA3.1-8B, and BloombergGPT in both zero-shot and few-shot settings across 19 and 4 datasets, respectively. FinLLaMA-instruct outperforms GPT-4 and other Financial LLMs on 15 datasets. FinLLaVA excels in understanding tables and charts across 4 multimodal tasks. Additionally, FinLLaMA achieves impressive Sharpe Ratios in trading simulations, highlighting its robust financial application capabilities. We will continually maintain and improve our models and benchmarks to support ongoing innovation in academia and industry.

https://huggingface.co/discussions/paper/66c80592ab23d3d7df9c9b49