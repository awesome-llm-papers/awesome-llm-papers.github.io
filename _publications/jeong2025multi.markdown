---
layout: publication
title: Multi-modal Knowledge Distillation-based Human Trajectory Forecasting
authors: Jeong et al.
conference: IEEE Transactions on Medical Imaging
year: 2025
bibkey: jeong2025multi
citations: 162
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.22201'}]
tags: [Distillation, Agentic, Tools, Evaluation, Efficiency And Optimization, Time
    Series, Applications, Datasets]
---
Pedestrian trajectory forecasting is crucial in various applications such as
autonomous driving and mobile robot navigation. In such applications,
camera-based perception enables the extraction of additional modalities (human
pose, text) to enhance prediction accuracy. Indeed, we find that textual
descriptions play a crucial role in integrating additional modalities into a
unified understanding. However, online extraction of text requires the use of
VLM, which may not be feasible for resource-constrained systems. To address
this challenge, we propose a multi-modal knowledge distillation framework: a
student model with limited modality is distilled from a teacher model trained
with full range of modalities. The comprehensive knowledge of a teacher model
trained with trajectory, human pose, and text is distilled into a student model
using only trajectory or human pose as a sole supplement. In doing so, we
separately distill the core locomotion insights from intra-agent multi-modality
and inter-agent interaction. Our generalizable framework is validated with two
state-of-the-art models across three datasets on both ego-view (JRDB, SIT) and
BEV-view (ETH/UCY) setups, utilizing both annotated and VLM-generated text
captions. Distilled student models show consistent improvement in all
prediction metrics for both full and instantaneous observations, improving up
to ~13%. The code is available at https://github.com/Jaewoo97/KDTF.