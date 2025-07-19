---
layout: publication
title: End-to-end Dense Video Captioning As Sequence Generation
authors: Zhu et al.
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2022
bibkey: zhu2022end
citations: 380
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.08121'}]
tags: [RAG, CVPR, Training Techniques]
---
Dense video captioning aims to identify the events of interest in an input
video, and generate descriptive captions for each event. Previous approaches
usually follow a two-stage generative process, which first proposes a segment
for each event, then renders a caption for each identified segment. Recent
advances in large-scale sequence generation pretraining have seen great success
in unifying task formulation for a great variety of tasks, but so far, more
complex tasks such as dense video captioning are not able to fully utilize this
powerful paradigm. In this work, we show how to model the two subtasks of dense
video captioning jointly as one sequence generation task, and simultaneously
predict the events and the corresponding descriptions. Experiments on YouCook2
and ViTT show encouraging results and indicate the feasibility of training
complex tasks such as end-to-end dense video captioning integrated into
large-scale pretrained models.