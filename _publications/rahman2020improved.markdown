---
layout: publication
title: An Improved Attention For Visual Question Answering
authors: Tanzila Rahman, Shih-han Chou, Leonid Sigal, Giuseppe Carenini
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops
  (CVPRW)
year: 2021
bibkey: rahman2020improved
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2011.02164'}]
tags: ["CVPR", "Model Architecture"]
short_authors: Rahman et al.
---
We consider the problem of Visual Question Answering (VQA). Given an image
and a free-form, open-ended, question, expressed in natural language, the goal
of VQA system is to provide accurate answer to this question with respect to
the image. The task is challenging because it requires simultaneous and
intricate understanding of both visual and textual information. Attention,
which captures intra- and inter-modal dependencies, has emerged as perhaps the
most widely used mechanism for addressing these challenges. In this paper, we
propose an improved attention-based architecture to solve VQA. We incorporate
an Attention on Attention (AoA) module within encoder-decoder framework, which
is able to determine the relation between attention results and queries.
Attention module generates weighted average for each query. On the other hand,
AoA module first generates an information vector and an attention gate using
attention results and current context; and then adds another attention to
generate final attended information by multiplying the two. We also propose
multimodal fusion module to combine both visual and textual information. The
goal of this fusion module is to dynamically decide how much information should
be considered from each modality. Extensive experiments on VQA-v2 benchmark
dataset show that our method achieves the state-of-the-art performance.