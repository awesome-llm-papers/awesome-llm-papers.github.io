---
layout: publication
title: 'Watch What You Just Said: Image Captioning With Text-conditional Attention'
authors: Zhou et al.
conference: Proceedings of the on Thematic Workshops of ACM Multimedia 2017
year: 2016
bibkey: zhou2016watch
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.04621'}]
tags: [Training Techniques, Attention Mechanism, Evaluation, Transformer, Model Architecture,
  Reinforcement Learning, Fine Tuning, Datasets]
---
Attention mechanisms have attracted considerable interest in image captioning
due to its powerful performance. However, existing methods use only visual
content as attention and whether textual context can improve attention in image
captioning remains unsolved. To explore this problem, we propose a novel
attention mechanism, called \textit\{text-conditional attention\}, which allows
the caption generator to focus on certain image features given previously
generated text. To obtain text-related image features for our attention model,
we adopt the guiding Long Short-Term Memory (gLSTM) captioning architecture
with CNN fine-tuning. Our proposed method allows joint learning of the image
embedding, text embedding, text-conditional attention and language model with
one network architecture in an end-to-end manner. We perform extensive
experiments on the MS-COCO dataset. The experimental results show that our
method outperforms state-of-the-art captioning methods on various quantitative
metrics as well as in human evaluation, which supports the use of our
text-conditional attention in image captioning.