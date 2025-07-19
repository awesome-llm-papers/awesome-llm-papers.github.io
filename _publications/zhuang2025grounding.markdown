---
layout: publication
title: 'Grounding-md: Grounded Video-language Pre-training For Open-world Moment Detection'
authors: Zhuang et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: zhuang2025grounding
citations: 376
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.14553'}]
tags: [RAG, Training Techniques, Prompting, Tools, Evaluation, Reinforcement Learning,
  Multimodal Models, Datasets, Merging]
---
Temporal Action Detection and Moment Retrieval constitute two pivotal tasks
in video understanding, focusing on precisely localizing temporal segments
corresponding to specific actions or events. Recent advancements introduced
Moment Detection to unify these two tasks, yet existing approaches remain
confined to closed-set scenarios, limiting their applicability in open-world
contexts. To bridge this gap, we present Grounding-MD, an innovative, grounded
video-language pre-training framework tailored for open-world moment detection.
Our framework incorporates an arbitrary number of open-ended natural language
queries through a structured prompt mechanism, enabling flexible and scalable
moment detection. Grounding-MD leverages a Cross-Modality Fusion Encoder and a
Text-Guided Fusion Decoder to facilitate comprehensive video-text alignment and
enable effective cross-task collaboration. Through large-scale pre-training on
temporal action detection and moment retrieval datasets, Grounding-MD
demonstrates exceptional semantic representation learning capabilities,
effectively handling diverse and complex query conditions. Comprehensive
evaluations across four benchmark datasets including ActivityNet, THUMOS14,
ActivityNet-Captions, and Charades-STA demonstrate that Grounding-MD
establishes new state-of-the-art performance in zero-shot and supervised
settings in open-world moment detection scenarios. All source code and trained
models will be released.