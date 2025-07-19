---
layout: publication
title: 'Neurolip: Interpretable And Fair Cross-modal Alignment Of Fmri And Phenotypic
  Text'
authors: Yang Yanting, Li Xiaoxiao
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2025
bibkey: yang2025neurolip
citations: 55
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.21964'}]
tags: [Interpretability And Explainability, RAG, Fairness, Attention Mechanism, Alt,
  Bias Mitigation, Tools, Evaluation, Ethics And Bias, Model Architecture, Multimodal
    Models, AAAI, Datasets]
---
Integrating functional magnetic resonance imaging (fMRI) connectivity data
with phenotypic textual descriptors (e.g., disease label, demographic data)
holds significant potential to advance our understanding of neurological
conditions. However, existing cross-modal alignment methods often lack
interpretability and risk introducing biases by encoding sensitive attributes
together with diagnostic-related features. In this work, we propose NeuroLIP, a
novel cross-modal contrastive learning framework. We introduce text
token-conditioned attention (TTCA) and cross-modal alignment via localized
tokens (CALT) to the brain region-level embeddings with each disease-related
phenotypic token. It improves interpretability via token-level attention maps,
revealing brain region-disease associations. To mitigate bias, we propose a
loss for sensitive attribute disentanglement that maximizes the attention
distance between disease tokens and sensitive attribute tokens, reducing
unintended correlations in downstream predictions. Additionally, we incorporate
a negative gradient technique that reverses the sign of CALT loss on sensitive
attributes, further discouraging the alignment of these features. Experiments
on neuroimaging datasets (ABIDE and ADHD-200) demonstrate NeuroLIP's
superiority in terms of fairness metrics while maintaining the overall best
standard metric performance. Qualitative visualization of attention maps
highlights neuroanatomical patterns aligned with diagnostic characteristics,
validated by the neuroscientific literature. Our work advances the development
of transparent and equitable neuroimaging AI.