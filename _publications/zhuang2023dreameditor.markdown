---
layout: publication
title: 'Dreameditor: Text-driven 3D Scene Editing With Neural Fields'
authors: Zhuang et al.
conference: SIGGRAPH Asia 2023 Conference Papers
year: 2023
bibkey: zhuang2023dreameditor
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.13455'}]
tags: [Distillation, Prompting, Tools, Evaluation, Efficiency And Optimization, Reinforcement
    Learning, Merging]
---
Neural fields have achieved impressive advancements in view synthesis and
scene reconstruction. However, editing these neural fields remains challenging
due to the implicit encoding of geometry and texture information. In this
paper, we propose DreamEditor, a novel framework that enables users to perform
controlled editing of neural fields using text prompts. By representing scenes
as mesh-based neural fields, DreamEditor allows localized editing within
specific regions. DreamEditor utilizes the text encoder of a pretrained
text-to-Image diffusion model to automatically identify the regions to be
edited based on the semantics of the text prompts. Subsequently, DreamEditor
optimizes the editing region and aligns its geometry and texture with the text
prompts through score distillation sampling [29]. Extensive experiments have
demonstrated that DreamEditor can accurately edit neural fields of real-world
scenes according to the given text prompts while ensuring consistency in
irrelevant areas. DreamEditor generates highly realistic textures and geometry,
significantly surpassing previous works in both quantitative and qualitative
evaluations.