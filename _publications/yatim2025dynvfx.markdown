---
layout: publication
title: 'Dynvfx: Augmenting Real Videos With Dynamic Content'
authors: Danah Yatim, Rafail Fridman, Omer Bar-tal, Tali Dekel
conference: No Venue
year: 2025
bibkey: yatim2025dynvfx
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.03621'}]
tags: ["Tools"]
short_authors: Yatim et al.
---
We present a method for augmenting real-world videos with newly generated dynamic content. Given an input video and a simple user-provided text instruction describing the desired content, our method synthesizes dynamic objects or complex scene effects that naturally interact with the existing scene over time. The position, appearance, and motion of the new content are seamlessly integrated into the original footage while accounting for camera motion, occlusions, and interactions with other dynamic objects in the scene, resulting in a cohesive and realistic output video. We achieve this via a zero-shot, training-free framework that harnesses a pre-trained text-to-video diffusion transformer to synthesize the new content and a pre-trained Vision Language Model to envision the augmented scene in detail. Specifically, we introduce a novel inference-based method that manipulates features within the attention mechanism, enabling accurate localization and seamless integration of the new content while preserving the integrity of the original scene. Our method is fully automated, requiring only a simple user instruction. We demonstrate its effectiveness on a wide range of edits applied to real-world videos, encompassing diverse objects and scenarios involving both camera and object motion.

https://huggingface.co/discussions/paper/67a59e5798f41a0460ee5389