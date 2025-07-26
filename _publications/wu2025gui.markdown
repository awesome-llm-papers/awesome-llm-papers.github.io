---
layout: publication
title: 'Gui-actor: Coordinate-free Visual Grounding For GUI Agents'
authors: Qianhui Wu, Kanzhi Cheng, Rui Yang, Chaoyun Zhang, Jianwei Yang, Huiqiang
  Jiang, Jian Mu, Baolin Peng, Bo Qiao, Reuben Tan, Si Qin, Lars Liden, Qingwei Lin,
  Huan Zhang, Tong Zhang, Jianbing Zhang, Dongmei Zhang, Jianfeng Gao
conference: No Venue
year: 2025
bibkey: wu2025gui
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.03143'}]
tags: ["Fine-Tuning"]
short_authors: Wu et al.
---
One of the principal challenges in building VLM-powered GUI agents is visual grounding, i.e., localizing the appropriate screen region for action execution based on both the visual content and the textual plans. Most existing work formulates this as a text-based coordinate generation task. However, these approaches suffer from several limitations: weak spatial-semantic alignment, inability to handle ambiguous supervision targets, and a mismatch between the dense nature of screen coordinates and the coarse, patch-level granularity of visual features extracted by models like Vision Transformers. In this paper, we propose GUI-Actor, a VLM-based method for coordinate-free GUI grounding. At its core, GUI-Actor introduces an attention-based action head that learns to align a dedicated <ACTOR> token with all relevant visual patch tokens, enabling the model to propose one or more action regions in a single forward pass. In line with this, we further design a grounding verifier to evaluate and select the most plausible action region from the candidates proposed for action execution. Extensive experiments show that GUI-Actor outperforms prior state-of-the-art methods on multiple GUI action grounding benchmarks, with improved generalization to unseen screen resolutions and layouts. Notably, GUI-Actor-7B even surpasses UI-TARS-72B (38.1) on ScreenSpot-Pro, achieving scores of 40.7 with Qwen2-VL and 44.6 with Qwen2.5-VL as backbones. Furthermore, by incorporating the verifier, we find that fine-tuning only the newly introduced action head (~100M parameters for 7B model) while keeping the VLM backbone frozen is sufficient to achieve performance comparable to previous state-of-the-art models, highlighting that GUI-Actor can endow the underlying VLM with effective grounding capabilities without compromising its general-purpose strengths.

https://huggingface.co/discussions/paper/683fc55d9363b50c19f17e6b