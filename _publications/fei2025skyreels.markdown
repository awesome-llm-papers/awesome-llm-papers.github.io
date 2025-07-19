---
layout: publication
title: 'Skyreels-audio: Omni Audio-conditioned Talking Portraits In Video Diffusion
  Transformers'
authors: Fei et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: fei2025skyreels
citations: 146
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.00830'}]
tags: [Tools, Evaluation, CVPR, Transformer, Model Architecture, Reinforcement Learning,
  Multimodal Models, Datasets, Merging]
---
The generation and editing of audio-conditioned talking portraits guided by multimodal inputs, including text, images, and videos, remains under explored. In this paper, we present SkyReels-Audio, a unified framework for synthesizing high-fidelity and temporally coherent talking portrait videos. Built upon pretrained video diffusion transformers, our framework supports infinite-length generation and editing, while enabling diverse and controllable conditioning through multimodal inputs. We employ a hybrid curriculum learning strategy to progressively align audio with facial motion, enabling fine-grained multimodal control over long video sequences. To enhance local facial coherence, we introduce a facial mask loss and an audio-guided classifier-free guidance mechanism. A sliding-window denoising approach further fuses latent representations across temporal segments, ensuring visual fidelity and temporal consistency across extended durations and diverse identities. More importantly, we construct a dedicated data pipeline for curating high-quality triplets consisting of synchronized audio, video, and textual descriptions. Comprehensive benchmark evaluations show that SkyReels-Audio achieves superior performance in lip-sync accuracy, identity consistency, and realistic facial dynamics, particularly under complex and challenging conditions.