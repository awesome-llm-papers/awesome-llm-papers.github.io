---
layout: publication
title: Evaluating Hallucination In Large Vision-language Models Based On Context-aware
  Object Similarities
authors: Datta Shounak, Sundararaman Dhanasekar
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: datta2025evaluating
citations: 136
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.15046'}]
tags: [Training Techniques, EMNLP, Tools, Evaluation, Multimodal Models, Datasets]
---
Despite their impressive performance on multi-modal tasks, large
vision-language models (LVLMs) tend to suffer from hallucinations. An important
type is object hallucination, where LVLMs generate objects that are
inconsistent with the images shown to the model. Existing works typically
attempt to quantify object hallucinations by detecting and measuring the
fraction of hallucinated objects in generated captions. Additionally, more
recent work also measures object hallucinations by directly querying the LVLM
with binary questions about the presence of likely hallucinated objects based
on object statistics like top-k frequent objects and top-k co-occurring
objects. In this paper, we present Context-Aware Object Similarities (CAOS), a
novel approach for evaluating object hallucination in LVLMs using object
statistics as well as the generated captions. CAOS uniquely integrates object
statistics with semantic relationships between objects in captions and
ground-truth data. Moreover, existing approaches usually only detect and
measure hallucinations belonging to a predetermined set of in-domain objects
(typically the set of all ground-truth objects for the training dataset) and
ignore generated objects that are not part of this set, leading to
under-evaluation. To address this, we further employ language model--based
object recognition to detect potentially out-of-domain hallucinated objects and
use an ensemble of LVLMs for verifying the presence of such objects in the
query image. CAOS also examines the sequential dynamics of object generation,
shedding light on how the order of object appearance influences hallucinations,
and employs word embedding models to analyze the semantic reasons behind
hallucinations. CAOS aims to offer a nuanced understanding of the hallucination
tendencies of LVLMs by providing a systematic framework to identify and
interpret object hallucinations.