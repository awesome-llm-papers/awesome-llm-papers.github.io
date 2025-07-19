---
layout: publication
title: 'Adacm\(^2\): On Understanding Extremely Long-term Video With Adaptive Cross-modality
  Memory Reduction'
authors: Man et al.
conference: Journal of Memory and Language
year: 2024
bibkey: man2024adacm
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.12593'}]
tags: [RAG, Prompting, Reinforcement Learning, Multimodal Models, Datasets]
---
The advancements in large language models (LLMs) have propelled the
improvement of video understanding tasks by incorporating LLMs with visual
models. However, most existing LLM-based models (e.g., VideoLLaMA, VideoChat)
are constrained to processing short-duration videos. Recent attempts to
understand long-term videos by extracting and compressing visual features into
a fixed memory size. Nevertheless, those methods leverage only visual modality
to merge video tokens and overlook the correlation between visual and textual
queries, leading to difficulties in effectively handling complex
question-answering tasks. To address the challenges of long videos and complex
prompts, we propose AdaCM\\(^2\\), which, for the first time, introduces an
adaptive cross-modality memory reduction approach to video-text alignment in an
auto-regressive manner on video streams. Our extensive experiments on various
video understanding tasks, such as video captioning, video question answering,
and video classification, demonstrate that AdaCM\\(^2\\) achieves state-of-the-art
performance across multiple datasets while significantly reducing memory usage.
Notably, it achieves a 4.5% improvement across multiple tasks in the LVU
dataset with a GPU memory consumption reduction of up to 65%.