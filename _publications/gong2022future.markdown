---
layout: publication
title: Future Transformer For Long-term Action Anticipation
authors: Dayoung Gong, Joonseok Lee, Manjin Kim, Seong Jong Ha, Minsu Cho
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
citations: 39
bibkey: gong2022future
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.14022'}]
tags: [Model Architecture, Attention Mechanism, Transformer, RAG, Reinforcement Learning,
  Agentic, GPT, Evaluation]
---
The task of predicting future actions from a video is crucial for a
real-world agent interacting with others. When anticipating actions in the
distant future, we humans typically consider long-term relations over the whole
sequence of actions, i.e., not only observed actions in the past but also
potential actions in the future. In a similar spirit, we propose an end-to-end
attention model for action anticipation, dubbed Future Transformer (FUTR), that
leverages global attention over all input frames and output tokens to predict a
minutes-long sequence of future actions. Unlike the previous autoregressive
models, the proposed method learns to predict the whole sequence of future
actions in parallel decoding, enabling more accurate and fast inference for
long-term anticipation. We evaluate our method on two standard benchmarks for
long-term action anticipation, Breakfast and 50 Salads, achieving
state-of-the-art results.