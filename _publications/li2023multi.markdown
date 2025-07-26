---
layout: publication
title: Multi-sentence Grounding For Long-term Instructional Video
authors: Zeqian Li, Qirui Chen, Tengda Han, Ya Zhang, Yanfeng Wang, Weidi Xie
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2023'
year: 2023
bibkey: li2023multi
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.14055'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Li et al.
---
In this paper, we aim to establish an automatic, scalable pipeline for
denoising the large-scale instructional dataset and construct a high-quality
video-text dataset with multiple descriptive steps supervision, named
HowToStep. We make the following contributions: (i) improving the quality of
sentences in dataset by upgrading ASR systems to reduce errors from speech
recognition and prompting a large language model to transform noisy ASR
transcripts into descriptive steps; (ii) proposing a Transformer-based
architecture with all texts as queries, iteratively attending to the visual
features, to temporally align the generated steps to corresponding video
segments. To measure the quality of our curated datasets, we train models for
the task of multi-sentence grounding on it, i.e., given a long-form video, and
associated multiple sentences, to determine their corresponding timestamps in
the video simultaneously, as a result, the model shows superior performance on
a series of multi-sentence grounding tasks, surpassing existing
state-of-the-art methods by a significant margin on three public benchmarks,
namely, 9.0% on HT-Step, 5.1% on HTM-Align and 1.9% on CrossTask. All codes,
models, and the resulting dataset have been publicly released.