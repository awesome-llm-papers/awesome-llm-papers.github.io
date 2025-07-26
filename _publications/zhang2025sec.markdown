---
layout: publication
title: 'Sec: Advancing Complex Video Object Segmentation Via Progressive Concept Construction'
authors: Zhixiong Zhang, Shuangrui Ding, Xiaoyi Dong, Songxin He, Jianfan Lin, Junsong
  Tang, Yuhang Zang, Yuhang Cao, Dahua Lin, Jiaqi Wang
conference: No Venue
year: 2025
bibkey: zhang2025sec
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.15852'}]
tags: ["Evaluation", "Tools"]
short_authors: Zhang et al.
---
Video Object Segmentation (VOS) is a core task in computer vision, requiring models to track and segment target objects across video frames. Despite notable advances with recent efforts, current techniques still lag behind human capabilities in handling drastic visual variations, occlusions, and complex scene changes. This limitation arises from their reliance on appearance matching, neglecting the human-like conceptual understanding of objects that enables robust identification across temporal dynamics. Motivated by this gap, we propose Segment Concept (SeC), a concept-driven segmentation framework that shifts from conventional feature matching to the progressive construction and utilization of high-level, object-centric representations. SeC employs Large Vision-Language Models (LVLMs) to integrate visual cues across diverse frames, constructing robust conceptual priors. During inference, SeC forms a comprehensive semantic representation of the target based on processed frames, realizing robust segmentation of follow-up frames. Furthermore, SeC adaptively balances LVLM-based semantic reasoning with enhanced feature matching, dynamically adjusting computational efforts based on scene complexity. To rigorously assess VOS methods in scenarios demanding high-level conceptual reasoning and robust semantic understanding, we introduce the Semantic Complex Scenarios Video Object Segmentation benchmark (SeCVOS). SeCVOS comprises 160 manually annotated multi-scenario videos designed to challenge models with substantial appearance variations and dynamic scene transformations. In particular, SeC achieves an 11.8-point improvement over SAM 2.1 on SeCVOS, establishing a new state-of-the-art in concept-aware video object segmentation.

https://huggingface.co/discussions/paper/687efbab33947f780d9b4af8