---
layout: publication
title: Contextrefine-clip For EPIC-KITCHENS-100 Multi-instance Retrieval Challenge
  2025
authors: He et al.
conference: International Journal of Computer Vision
year: 2025
bibkey: he2025contextrefine
citations: 221
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.10550'}]
tags: [Attention Mechanism, Evaluation, Model Architecture, Efficiency And Optimization,
  Multimodal Models, Datasets]
---
This report presents ContextRefine-CLIP (CR-CLIP), an efficient model for visual-textual multi-instance retrieval tasks. The approach is based on the dual-encoder AVION, on which we introduce a cross-modal attention flow module to achieve bidirectional dynamic interaction and refinement between visual and textual features to generate more context-aware joint representations. For soft-label relevance matrices provided in tasks such as EPIC-KITCHENS-100, CR-CLIP can work with Symmetric Multi-Similarity Loss to achieve more accurate semantic alignment and optimization using the refined features. Without using ensemble learning, the CR-CLIP model achieves 66.78mAP and 82.08nDCG on the EPIC-KITCHENS-100 public leaderboard, which significantly outperforms the baseline model and fully validates its effectiveness in cross-modal retrieval. The code will be released open-source on https://github.com/delCayr/ContextRefine-Clip