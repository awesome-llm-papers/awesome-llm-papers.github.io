---
layout: publication
title: Context-aware Visual Policy Network For Sequence-level Image Captioning
authors: Liu et al.
conference: Proceedings of the 26th ACM international conference on Multimedia
year: 2018
bibkey: liu2018context
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.05864'}]
tags: [Training Techniques, Attention Mechanism, Agentic, Evaluation, Ethics And Bias,
  Model Architecture, Reinforcement Learning, Multimodal Models]
---
Many vision-language tasks can be reduced to the problem of sequence
prediction for natural language output. In particular, recent advances in image
captioning use deep reinforcement learning (RL) to alleviate the "exposure
bias" during training: ground-truth subsequence is exposed in every step
prediction, which introduces bias in test when only predicted subsequence is
seen. However, existing RL-based image captioning methods only focus on the
language policy while not the visual policy (e.g., visual attention), and thus
fail to capture the visual context that are crucial for compositional reasoning
such as visual relationships (e.g., "man riding horse") and comparisons (e.g.,
"smaller cat"). To fill the gap, we propose a Context-Aware Visual Policy
network (CAVP) for sequence-level image captioning. At every time step, CAVP
explicitly accounts for the previous visual attentions as the context, and then
decides whether the context is helpful for the current word generation given
the current visual attention. Compared against traditional visual attention
that only fixes a single image region at every step, CAVP can attend to complex
visual compositions over time. The whole image captioning model --- CAVP and
its subsequent language policy network --- can be efficiently optimized
end-to-end by using an actor-critic policy gradient method with respect to any
caption evaluation metric. We demonstrate the effectiveness of CAVP by
state-of-the-art performances on MS-COCO offline split and online server, using
various metrics and sensible visualizations of qualitative visual context. The
code is available at https://github.com/daqingliu/CAVP