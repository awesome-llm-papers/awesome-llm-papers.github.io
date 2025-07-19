---
layout: publication
title: Prompting For Multi-modal Tracking
authors: Yang et al.
conference: Proceedings of the 30th ACM International Conference on Multimedia
year: 2022
bibkey: yang2022prompting
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.14571'}]
tags: [Training Techniques, Attention Mechanism, Alt, Prompting, Evaluation, Model
    Architecture, Datasets, Merging]
---
Multi-modal tracking gains attention due to its ability to be more accurate
and robust in complex scenarios compared to traditional RGB-based tracking. Its
key lies in how to fuse multi-modal data and reduce the gap between modalities.
However, multi-modal tracking still severely suffers from data deficiency, thus
resulting in the insufficient learning of fusion modules. Instead of building
such a fusion module, in this paper, we provide a new perspective on
multi-modal tracking by attaching importance to the multi-modal visual prompts.
We design a novel multi-modal prompt tracker (ProTrack), which can transfer the
multi-modal inputs to a single modality by the prompt paradigm. By best
employing the tracking ability of pre-trained RGB trackers learning at scale,
our ProTrack can achieve high-performance multi-modal tracking by only altering
the inputs, even without any extra training on multi-modal data. Extensive
experiments on 5 benchmark datasets demonstrate the effectiveness of the
proposed ProTrack.