---
layout: publication
title: How Do Your Code Llms Perform? Empowering Code Instruction Tuning With High-quality
  Data
authors: Yejie Wang, Keqing He, Dayuan Fu, Zhuoma Gongque, Heyang Xu, Yanxu Chen,
  Zhexu Wang, Yujia Fu, Guanting Dong, Muxi Diao, Jingang Wang, Mengdi Zhang, Xunliang
  Cai, Weiran Xu
conference: No Venue
year: 2024
bibkey: wang2024how
additional_links: [{name: Code, url: 'https://github.com/banksy23/XCoder'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66de6a5813e3a385360893dd'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2409.03810'}]
tags: ["Has Code", "Training Techniques"]
short_authors: Wang et al.
---
Recently, there has been a growing interest in studying how to construct better code instruction tuning data. However, we observe Code models trained with these datasets exhibit high performance on HumanEval but perform worse on other benchmarks such as LiveCodeBench. Upon further investigation, we find that many datasets suffer from severe data leakage. After cleaning up most of the leaked data, some well-known high-quality datasets perform poorly. This discovery reveals a new challenge: identifying which dataset genuinely qualify as high-quality code instruction data. To address this, we propose an efficient code data pruning strategy for selecting good samples. Our approach is based on three dimensions: instruction complexity, response quality, and instruction diversity. Based on our selected data, we present XCoder, a family of models finetuned from LLaMA3. Our experiments show XCoder achieves new state-of-the-art performance using fewer training data, which verify the effectiveness of our data strategy. Moreover, we perform a comprehensive analysis on the data composition and find existing code datasets have different characteristics according to their construction methods, which provide new insights for future code LLMs. Our models and dataset are released in https://github.com/banksy23/XCoder

https://huggingface.co/discussions/paper/66de6a5813e3a385360893dd