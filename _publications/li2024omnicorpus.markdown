---
layout: publication
title: 'Omnicorpus: A Unified Multimodal Corpus Of 10 Billion-level Images Interleaved
  With Text'
authors: Qingyun Li, Zhe Chen, Weiyun Wang, Wenhai Wang, Shenglong Ye, Zhenjiang Jin,
  Guanzhou Chen, Yinan He, Zhangwei Gao, Erfei Cui, Jiashuo Yu, Hao Tian, Jiasheng
  Zhou, Chao Xu, Bin Wang, Xingjian Wei, Wei Li, Wenjian Zhang, Bo Zhang, Pinlong
  Cai, Licheng Wen, Xiangchao Yan, Zhenxiang Li, Pei Chu, Yi Wang, Min Dou, Changyao
  Tian, Xizhou Zhu, Lewei Lu, Yushi Chen, Junjun He, Zhongying Tu, Tong Lu, Yali Wang,
  Limin Wang, Dahua Lin, Yu Qiao, Botian Shi, Conghui He, Jifeng Dai
conference: No Venue
year: 2024
bibkey: li2024omnicorpus
additional_links: [{name: Code, url: 'https://github.com/OpenGVLab/OmniCorpus'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/666fd32d4aae2409910e2537'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.08418'}]
tags: ["Datasets"]
short_authors: Li et al.
---
Image-text interleaved data, consisting of multiple images and texts arranged in a natural document format, aligns with the presentation paradigm of internet data and closely resembles human reading habits. Recent studies have shown that such data aids multimodal in-context learning and maintains the capabilities of large language models during multimodal fine-tuning. However, the limited scale and diversity of current image-text interleaved data restrict the development of multimodal large language models. In this paper, we introduce OmniCorpus, a 10 billion-scale image-text interleaved dataset. Using an efficient data engine, we filter and extract large-scale high-quality documents, which contain 8.6 billion images and 1,696 billion text tokens. Compared to counterparts (e.g., MMC4, OBELICS), our dataset 1) has 15 times larger scales while maintaining good data quality; 2) features more diverse sources, including both English and non-English websites as well as video-centric websites; 3) is more flexible, easily degradable from an image-text interleaved format to pure text corpus and image-text pairs. Through comprehensive analysis and experiments, we validate the quality, usability, and effectiveness of the proposed dataset. We hope this could provide a solid data foundation for future multimodal model research. Code and data are released at https://github.com/OpenGVLab/OmniCorpus.

https://huggingface.co/discussions/paper/666fd32d4aae2409910e2537