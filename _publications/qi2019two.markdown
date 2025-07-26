---
layout: publication
title: Two Causal Principles For Improving Visual Dialog
authors: Jiaxin Qi, Yulei Niu, Jianqiang Huang, Hanwang Zhang
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2020
bibkey: qi2019two
citations: 144
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.10496'}]
tags: ["CVPR"]
short_authors: Qi et al.
---
This paper unravels the design tricks adopted by us, the champion team
MReaL-BDAI, for Visual Dialog Challenge 2019: two causal principles for
improving Visual Dialog (VisDial). By "improving", we mean that they can
promote almost every existing VisDial model to the state-of-the-art performance
on the leader-board. Such a major improvement is only due to our careful
inspection on the causality behind the model and data, finding that the
community has overlooked two causalities in VisDial. Intuitively, Principle 1
suggests: we should remove the direct input of the dialog history to the answer
model, otherwise a harmful shortcut bias will be introduced; Principle 2 says:
there is an unobserved confounder for history, question, and answer, leading to
spurious correlations from training data. In particular, to remove the
confounder suggested in Principle 2, we propose several causal intervention
algorithms, which make the training fundamentally different from the
traditional likelihood estimation. Note that the two principles are
model-agnostic, so they are applicable in any VisDial model. The code is
available at https://github.com/simpleshinobu/visdial-principles.