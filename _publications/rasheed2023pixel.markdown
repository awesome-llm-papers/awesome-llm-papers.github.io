---
layout: publication
title: 'Glamm: Pixel Grounding Large Multimodal Model'
authors: Hanoona Rasheed et al.
conference: Arxiv
year: 2023
citations: 34
bibkey: rasheed2023pixel
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.03356'}]
tags: [Prompting, Multimodal Models]
---
Large Multimodal Models (LMMs) extend Large Language Models to the vision
domain. Initial LMMs used holistic images and text prompts to generate
ungrounded textual responses. Recently, region-level LMMs have been used to
generate visually grounded responses. However, they are limited to only
referring to a single object category at a time, require users to specify the
regions, or cannot offer dense pixel-wise object grounding. In this work, we
present Grounding LMM (GLaMM), the first model that can generate natural
language responses seamlessly intertwined with corresponding object
segmentation masks. GLaMM not only grounds objects appearing in the
conversations but is flexible enough to accept both textual and optional visual
prompts (region of interest) as input. This empowers users to interact with the
model at various levels of granularity, both in textual and visual domains. Due
to the lack of standard benchmarks for the novel setting of visually Grounded
Conversation Generation (GCG), we introduce a comprehensive evaluation protocol
with our curated grounded conversations. Our proposed GCG task requires densely
grounded concepts in natural scenes at a large-scale. To this end, we propose a
densely annotated Grounding-anything Dataset (GranD) using our proposed
automated annotation pipeline that encompasses 7.5M unique concepts grounded in
a total of 810M regions available with segmentation masks. Besides GCG, GLaMM
also performs effectively on several downstream tasks, e.g., referring
expression segmentation, image and region-level captioning and vision-language
conversations.