---
layout: publication
title: 'URECA: Unique Region Caption Anything'
authors: Sangbeom Lim, Junwan Kim, Heeji Yoon, Jaewoo Jung, Seungryong Kim
conference: No Venue
year: 2025
bibkey: lim2025ureca
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67f495477e1624ebbaf2da2f'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.05305'}]
tags: ["Datasets"]
short_authors: Lim et al.
---
Region-level captioning aims to generate natural language descriptions for specific image regions while highlighting their distinguishing features. However, existing methods struggle to produce unique captions across multi-granularity, limiting their real-world applicability. To address the need for detailed region-level understanding, we introduce URECA dataset, a large-scale dataset tailored for multi-granularity region captioning. Unlike prior datasets that focus primarily on salient objects, URECA dataset ensures a unique and consistent mapping between regions and captions by incorporating a diverse set of objects, parts, and background elements. Central to this is a stage-wise data curation pipeline, where each stage incrementally refines region selection and caption generation. By leveraging Multimodal Large Language Models (MLLMs) at each stage, our pipeline produces distinctive and contextually grounded captions with improved accuracy and semantic diversity. Building upon this dataset, we present URECA, a novel captioning model designed to effectively encode multi-granularity regions. URECA maintains essential spatial properties such as position and shape through simple yet impactful modifications to existing MLLMs, enabling fine-grained and semantically rich region descriptions. Our approach introduces dynamic mask modeling and a high-resolution mask encoder to enhance caption uniqueness. Experiments show that URECA achieves state-of-the-art performance on URECA dataset and generalizes well to existing region-level captioning benchmarks.

https://huggingface.co/discussions/paper/67f495477e1624ebbaf2da2f