---
layout: publication
title: Deep Modular Co-attention Networks For Visual Question Answering
authors: Zhou Yu, Jun Yu, Yuhao Cui, Dacheng Tao, Qi Tian
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2019
bibkey: yu2019deep
citations: 803
additional_links: [{name: Code, url: 'https://github.com/MILVLG/mcan-vqa'}, {name: Paper,
    url: 'https://arxiv.org/abs/1906.10770'}]
tags: ["CVPR"]
short_authors: Yu et al.
---
Visual Question Answering (VQA) requires a fine-grained and simultaneous
understanding of both the visual content of images and the textual content of
questions. Therefore, designing an effective `co-attention' model to associate
key words in questions with key objects in images is central to VQA
performance. So far, most successful attempts at co-attention learning have
been achieved by using shallow models, and deep co-attention models show little
improvement over their shallow counterparts. In this paper, we propose a deep
Modular Co-Attention Network (MCAN) that consists of Modular Co-Attention (MCA)
layers cascaded in depth. Each MCA layer models the self-attention of questions
and images, as well as the guided-attention of images jointly using a modular
composition of two basic attention units. We quantitatively and qualitatively
evaluate MCAN on the benchmark VQA-v2 dataset and conduct extensive ablation
studies to explore the reasons behind MCAN's effectiveness. Experimental
results demonstrate that MCAN significantly outperforms the previous
state-of-the-art. Our best single model delivers 70.63\\(%\\) overall accuracy on
the test-dev set. Code is available at https://github.com/MILVLG/mcan-vqa.