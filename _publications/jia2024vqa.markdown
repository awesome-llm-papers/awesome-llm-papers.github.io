---
layout: publication
title: 'VQA\(^2\): Visual Question Answering For Video Quality Assessment'
authors: Jia et al.
conference: International Journal of Computer Vision
year: 2024
bibkey: jia2024vqa
citations: 229
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.03795'}]
tags: [RAG, GPT, Tools, Evaluation, Model Architecture, Reinforcement Learning, Datasets]
---
The advent and proliferation of large multi-modal models (LMMs) have
introduced new paradigms to computer vision, transforming various tasks into a
unified visual question answering framework. Video Quality Assessment (VQA), a
classic field in low-level visual perception, focused initially on quantitative
video quality scoring. However, driven by advances in LMMs, it is now
progressing toward more holistic visual quality understanding tasks. Recent
studies in the image domain have demonstrated that Visual Question Answering
(VQA) can markedly enhance low-level visual quality evaluation. Nevertheless,
related work has not been explored in the video domain, leaving substantial
room for improvement. To address this gap, we introduce the VQA2 Instruction
Dataset - the first visual question answering instruction dataset that focuses
on video quality assessment. This dataset consists of 3 subsets and covers
various video types, containing 157,755 instruction question-answer pairs.
Then, leveraging this foundation, we present the VQA2 series models. The VQA2
series models interleave visual and motion tokens to enhance the perception of
spatial-temporal quality details in videos. We conduct extensive experiments on
video quality scoring and understanding tasks, and results demonstrate that the
VQA2series models achieve excellent performance in both tasks. Notably, our
final model, the VQA2-Assistant, exceeds the renowned GPT-4o in visual quality
understanding tasks while maintaining strong competitiveness in quality scoring
tasks. Our work provides a foundation and feasible approach for integrating
low-level video quality assessment and understanding with LMMs.