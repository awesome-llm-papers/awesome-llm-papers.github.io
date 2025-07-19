---
layout: publication
title: Learning To Prompt For Vision-language Models
authors: Zhou et al.
conference: International Journal of Computer Vision
year: 2021
bibkey: zhou2021learning
citations: 1275
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.01134'}]
tags: [RAG, Training Techniques, Prompting, Efficiency And Optimization, Multimodal
    Models, Datasets]
---
Large pre-trained vision-language models like CLIP have shown great potential
in learning representations that are transferable across a wide range of
downstream tasks. Different from the traditional representation learning that
is based mostly on discretized labels, vision-language pre-training aligns
images and texts in a common feature space, which allows zero-shot transfer to
a downstream task via prompting, i.e., classification weights are synthesized
from natural language describing classes of interest. In this work, we show
that a major challenge for deploying such models in practice is prompt
engineering, which requires domain expertise and is extremely time-consuming --
one needs to spend a significant amount of time on words tuning since a slight
change in wording could have a huge impact on performance. Inspired by recent
advances in prompt learning research in natural language processing (NLP), we
propose Context Optimization (CoOp), a simple approach specifically for
adapting CLIP-like vision-language models for downstream image recognition.
Concretely, CoOp models a prompt's context words with learnable vectors while
the entire pre-trained parameters are kept fixed. To handle different image
recognition tasks, we provide two implementations of CoOp: unified context and
class-specific context. Through extensive experiments on 11 datasets, we
demonstrate that CoOp requires as few as one or two shots to beat hand-crafted
prompts with a decent margin and is able to gain significant improvements over
prompt engineering with more shots, e.g., with 16 shots the average gain is
around 15% (with the highest reaching over 45%). Despite being a learning-based
approach, CoOp achieves superb domain generalization performance compared with
the zero-shot model using hand-crafted prompts.