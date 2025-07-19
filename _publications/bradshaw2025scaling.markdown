---
layout: publication
title: Scaling Self-supervised Representation Learning For Symbolic Piano Performance
authors: Bradshaw et al.
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2025
bibkey: bradshaw2025scaling
citations: 203
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.23869'}]
tags: [ICCV, Training Techniques, GPT, Tools, Evaluation, Transformer, Model Architecture,
  Datasets]
---
We study the capabilities of generative autoregressive transformer models trained on large amounts of symbolic solo-piano transcriptions. After first pretraining on approximately 60,000 hours of music, we use a comparatively smaller, high-quality subset, to finetune models to produce musical continuations, perform symbolic classification tasks, and produce general-purpose contrastive MIDI embeddings by adapting the SimCLR framework to symbolic music. When evaluating piano continuation coherence, our generative model outperforms leading symbolic generation techniques and remains competitive with proprietary audio generation models. On MIR classification benchmarks, frozen representations from our contrastive model achieve state-of-the-art results in linear probe experiments, while direct finetuning demonstrates the generalizability of pretrained representations, often requiring only a few hundred labeled examples to specialize to downstream tasks.