---
layout: publication
title: 'Higru: Hierarchical Gated Recurrent Units For Utterance-level Emotion Recognition'
authors: Jiao et al.
conference: Arxiv
year: 2019
bibkey: jiao2019higru
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.04446'}]
tags: [Attention Mechanism, Tools, Transformer, Model Architecture, Reinforcement
    Learning, Datasets, Merging]
---
In this paper, we address three challenges in utterance-level emotion
recognition in dialogue systems: (1) the same word can deliver different
emotions in different contexts; (2) some emotions are rarely seen in general
dialogues; (3) long-range contextual information is hard to be effectively
captured. We therefore propose a hierarchical Gated Recurrent Unit (HiGRU)
framework with a lower-level GRU to model the word-level inputs and an
upper-level GRU to capture the contexts of utterance-level embeddings.
Moreover, we promote the framework to two variants, HiGRU with individual
features fusion (HiGRU-f) and HiGRU with self-attention and features fusion
(HiGRU-sf), so that the word/utterance-level individual inputs and the
long-range contextual information can be sufficiently utilized. Experiments on
three dialogue emotion datasets, IEMOCAP, Friends, and EmotionPush demonstrate
that our proposed HiGRU models attain at least 8.7%, 7.5%, 6.0% improvement
over the state-of-the-art methods on each dataset, respectively. Particularly,
by utilizing only the textual feature in IEMOCAP, our HiGRU models gain at
least 3.8% improvement over the state-of-the-art conversational memory network
(CMN) with the trimodal features of text, video, and audio.