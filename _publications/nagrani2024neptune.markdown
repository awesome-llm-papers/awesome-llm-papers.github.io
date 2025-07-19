---
layout: publication
title: 'Neptune: The Long Orbit To Benchmarking Long Video Understanding'
authors: Nagrani et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: nagrani2024neptune
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.09582'}]
tags: [RAG, Evaluation, CVPR, Reinforcement Learning, Multimodal Models, Datasets]
---
We introduce Neptune, a benchmark for long video understanding that requires
reasoning over long time horizons and across different modalities. Many
existing video datasets and models are focused on short clips (10s-30s). While
some long video datasets do exist, they can often be solved by powerful image
models applied per frame (and often to very few frames) in a video, and are
usually manually annotated at high cost. In order to mitigate both these
problems, we propose a scalable dataset creation pipeline which leverages large
models (VLMs and LLMs), to automatically generate dense, time-aligned video
captions, as well as tough question answer decoy sets for video segments (up to
15 minutes in length). Our dataset Neptune covers a broad range of long video
reasoning abilities and consists of a subset that emphasizes multimodal
reasoning. Since existing metrics for open-ended question answering are either
rule-based or may rely on proprietary models, we provide a new open source
model-based metric GEM to score open-ended responses on Neptune. Benchmark
evaluations reveal that most current open-source long video models perform
poorly on Neptune, particularly on questions testing temporal ordering,
counting and state changes. Through Neptune, we aim to spur the development of
more advanced models capable of understanding long videos. The dataset is
available at https://github.com/google-deepmind/neptune