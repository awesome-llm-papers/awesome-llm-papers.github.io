---
layout: publication
title: 'VIOLET : End-to-end Video-language Transformers With Masked Visual-token Modeling'
authors: Tsu-jui Fu, Linjie Li, Zhe Gan, Kevin Lin, William Yang Wang, Lijuan Wang,
  Zicheng Liu
conference: Arxiv
year: 2021
bibkey: fu2021violet
citations: 88
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.12681'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Fu et al.
---
A great challenge in video-language (VidL) modeling lies in the disconnection
between fixed video representations extracted from image/video understanding
models and downstream VidL data. Recent studies try to mitigate this
disconnection via end-to-end training. To make it computationally feasible,
prior works tend to "imagify" video inputs, i.e., a handful of sparsely sampled
frames are fed into a 2D CNN, followed by a simple mean-pooling or
concatenation to obtain the overall video representations. Although achieving
promising results, such simple approaches may lose temporal information that is
essential for performing downstream VidL tasks. In this work, we present
VIOLET, a fully end-to-end VIdeO-LanguagE Transformer, which adopts a video
transformer to explicitly model the temporal dynamics of video inputs. Further,
unlike previous studies that found pre-training tasks on video inputs (e.g.,
masked frame modeling) not very effective, we design a new pre-training task,
Masked Visual-token Modeling (MVM), for better video modeling. Specifically,
the original video frame patches are "tokenized" into discrete visual tokens,
and the goal is to recover the original visual tokens based on the masked
patches. Comprehensive analysis demonstrates the effectiveness of both explicit
temporal modeling via video transformer and MVM. As a result, VIOLET achieves
new state-of-the-art performance on 5 video question answering tasks and 4
text-to-video retrieval tasks.