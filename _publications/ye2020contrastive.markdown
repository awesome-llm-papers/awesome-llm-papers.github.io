---
layout: publication
title: Contrastive Triple Extraction With Generative Transformer
authors: Hongbin Ye, Ningyu Zhang, Shumin Deng, Mosha Chen, Chuanqi Tan, Fei Huang,
  Huajun Chen
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: ye2020contrastive
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.06207'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Ye et al.
---
Triple extraction is an essential task in information extraction for natural
language processing and knowledge graph construction. In this paper, we revisit
the end-to-end triple extraction task for sequence generation. Since generative
triple extraction may struggle to capture long-term dependencies and generate
unfaithful triples, we introduce a novel model, contrastive triple extraction
with a generative transformer. Specifically, we introduce a single shared
transformer module for encoder-decoder-based generation. To generate faithful
results, we propose a novel triplet contrastive training object. Moreover, we
introduce two mechanisms to further improve model performance (i.e., batch-wise
dynamic attention-masking and triple-wise calibration). Experimental results on
three datasets (i.e., NYT, WebNLG, and MIE) show that our approach achieves
better performance than that of baselines.