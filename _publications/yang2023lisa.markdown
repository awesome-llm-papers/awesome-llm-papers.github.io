---
layout: publication
title: 'LISA++: An Improved Baseline For Reasoning Segmentation With Large Language
  Model'
authors: Yang et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: yang2023lisa
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.17240'}]
tags: [Datasets, Model Architecture, CVPR, Applications]
---
While LISA effectively bridges the gap between segmentation and large
language models to enable reasoning segmentation, it poses certain limitations:
unable to distinguish different instances of the target region, and constrained
by the pre-defined textual response formats. In this work, we introduce LISA++,
an update to the existing LISA model, focusing on improving core
functionalities while keeping the base architecture intact. The main
enhancements in LISA++ include: \textbf\{1) Enhanced Segmentation\}: The instance
segmentation ability has been added, providing a more detailed scene analysis
along with the existing multi-region semantic segmentation. \textbf\{2) More
Natural Conversation\}: Improved capability for multi-turn dialogue, with the
ability to incorporate segmentation results directly into text responses, i.e.,
Segmentation in Dialogue (SiD). These improvements are achieved by curating the
existing samples of generic segmentation datasets, aimed specifically at
enhancing the segmentation and conversational skills without structural change
and additional data sources. Comparative analysis with the original LISA model
shows significant advancements in these areas, positioning LISA++ as a notable
upgrade in visual understanding and interaction. LISA++'s adaptability and
improved features highlight the versatility of the mask-as-embedding paradigm
proposed by LISA, and the potential as a foundational model for diverse
applications.