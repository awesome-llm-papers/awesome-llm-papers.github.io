---
layout: publication
title: Vision-language Navigation With Self-supervised Auxiliary Reasoning Tasks
authors: Fengda Zhu, Yi Zhu, Xiaojun Chang, Xiaodan Liang
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2020
bibkey: zhu2019vision
citations: 189
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.07883'}]
tags: ["CVPR"]
short_authors: Zhu et al.
---
Vision-Language Navigation (VLN) is a task where agents learn to navigate
following natural language instructions. The key to this task is to perceive
both the visual scene and natural language sequentially. Conventional
approaches exploit the vision and language features in cross-modal grounding.
However, the VLN task remains challenging, since previous works have neglected
the rich semantic information contained in the environment (such as implicit
navigation graphs or sub-trajectory semantics). In this paper, we introduce
Auxiliary Reasoning Navigation (AuxRN), a framework with four self-supervised
auxiliary reasoning tasks to take advantage of the additional training signals
derived from the semantic information. The auxiliary tasks have four reasoning
objectives: explaining the previous actions, estimating the navigation
progress, predicting the next orientation, and evaluating the trajectory
consistency. As a result, these additional training signals help the agent to
acquire knowledge of semantic representations in order to reason about its
activity and build a thorough perception of the environment. Our experiments
indicate that auxiliary reasoning tasks improve both the performance of the
main task and the model generalizability by a large margin. Empirically, we
demonstrate that an agent trained with self-supervised auxiliary reasoning
tasks substantially outperforms the previous state-of-the-art method, being the
best existing approach on the standard benchmark.