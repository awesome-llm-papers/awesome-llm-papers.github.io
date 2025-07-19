---
layout: publication
title: 'From Features To Transformers: Redefining Ranking For Scalable Impact'
authors: Borisyuk et al.
conference: Synthesis Lectures on Human Language Technologies
year: 2025
bibkey: borisyuk2025features
citations: 148
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.03417'}]
tags: [Training Techniques, Attention Mechanism, Tools, Transformer, Model Architecture]
---
We present LiGR, a large-scale ranking framework developed at LinkedIn that brings state-of-the-art transformer-based modeling architectures into production. We introduce a modified transformer architecture that incorporates learned normalization and simultaneous set-wise attention to user history and ranked items. This architecture enables several breakthrough achievements, including: (1) the deprecation of most manually designed feature engineering, outperforming the prior state-of-the-art system using only few features (compared to hundreds in the baseline), (2) validation of the scaling law for ranking systems, showing improved performance with larger models, more training data, and longer context sequences, and (3) simultaneous joint scoring of items in a set-wise manner, leading to automated improvements in diversity. To enable efficient serving of large ranking models, we describe techniques to scale inference effectively using single-pass processing of user history and set-wise attention. We also summarize key insights from various ablation studies and A/B tests, highlighting the most impactful technical approaches.