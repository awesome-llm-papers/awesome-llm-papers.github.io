---
layout: publication
title: 'Aligned With LLM: A New Multi-modal Training Paradigm For Encoding Fmri Activity
  In Visual Cortex'
authors: Ma et al.
conference: NeuroImage
year: 2024
bibkey: ma2024aligned
citations: 134
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2401.03851'}]
tags: [Training Techniques, GPT, Evaluation, Model Architecture, Datasets]
---
Recently, there has been a surge in the popularity of pre trained large
language models (LLMs) (such as GPT-4), sweeping across the entire Natural
Language Processing (NLP) and Computer Vision (CV) communities. These LLMs have
demonstrated advanced multi-modal understanding capabilities and showcased
strong performance across various benchmarks. The LLM has started to embody
traits of artificial general intelligence, which holds vital guidance for
enhancing brain-like characteristics within visual encoding models. Hence, This
paper proposes a new multi-modal training paradigm, aligning with LLM, for
encoding fMRI activity in visual cortex. Based on this paradigm, we trained an
encoding model in fMRI data named the LLM-Visual Encoding Model (LLM-VEM).
Specifically, we utilize LLM (miniGPT4) to generate descriptive text for all
stimulus images, forming a high-quality textual description set. Moreover, we
use the pre-trained text encoder (CLIP) to process these detailed descriptions,
obtaining the text embedding features. Next, we use the contrast loss function
to minimize the distance between the image embedding features and the text
embedding features to complete the alignment operation of the stimulus image
and text information. With the assistance of the pre-trained LLM, this
alignment process facilitates better learning of the visual encoding model,
resulting in higher precision. The final experimental results indicate that our
training paradigm has significantly aided in enhancing the performance of the
visual encoding model.