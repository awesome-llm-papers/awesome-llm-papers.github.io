---
layout: publication
title: Transferring Visual Attributes From Natural Language To Verified Image Generation
authors: Valerio et al.
conference: Lecture Notes in Computer Science
year: 2023
bibkey: valerio2023transferring
citations: 289
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.15026'}]
tags: [Prompting, Reinforcement Learning]
---
Text to image generation methods (T2I) are widely popular in generating art
and other creative artifacts. While visual hallucinations can be a positive
factor in scenarios where creativity is appreciated, such artifacts are poorly
suited for cases where the generated image needs to be grounded in complex
natural language without explicit visual elements. In this paper, we propose to
strengthen the consistency property of T2I methods in the presence of natural
complex language, which often breaks the limits of T2I methods by including
non-visual information, and textual elements that require knowledge for
accurate generation. To address these phenomena, we propose a Natural Language
to Verified Image generation approach (NL2VI) that converts a natural prompt
into a visual prompt, which is more suitable for image generation. A T2I model
then generates an image for the visual prompt, which is then verified with VQA
algorithms. Experimentally, aligning natural prompts with image generation can
improve the consistency of the generated images by up to 11% over the state of
the art. Moreover, improvements can generalize to challenging domains like
cooking and DIY tasks, where the correctness of the generated image is crucial
to illustrate actions.