---
layout: publication
title: Generating Attribute-aware Human Motions From Textual Prompt
authors: Wang et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: wang2025generating
citations: 182
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.21912'}]
tags: [Attention Mechanism, Prompting, Tools, Evaluation, Model Architecture, Fine
    Tuning, Datasets]
---
Text-driven human motion generation has recently attracted considerable attention, allowing models to generate human motions based on textual descriptions. However, current methods neglect the influence of human attributes (such as age, gender, weight, and height) which are key factors shaping human motion patterns. This work represents a pilot exploration for bridging this gap. We conceptualize each motion as comprising both attribute information and action semantics, where textual descriptions align exclusively with action semantics. To achieve this, a new framework inspired by Structural Causal Models is proposed to decouple action semantics from human attributes, enabling text-to-semantics prediction and attribute-controlled generation. The resulting model is capable of generating realistic, attribute-aware motion aligned with the user's text and attribute inputs. For evaluation, we introduce HumanAttr, a comprehensive dataset containing attribute annotations for text-motion pairs, setting the first benchmark for attribute-aware text-to-motion generation. Extensive experiments on the new dataset validate our model's effectiveness.