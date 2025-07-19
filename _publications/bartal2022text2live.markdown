---
layout: publication
title: 'Text2live: Text-driven Layered Image And Video Editing'
authors: Bar-tal et al.
conference: Lecture Notes in Computer Science
year: 2022
bibkey: bartal2022text2live
citations: 129
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.02491'}]
tags: [Prompting, RAG, Training Techniques, Datasets]
---
We present a method for zero-shot, text-driven appearance manipulation in
natural images and videos. Given an input image or video and a target text
prompt, our goal is to edit the appearance of existing objects (e.g., object's
texture) or augment the scene with visual effects (e.g., smoke, fire) in a
semantically meaningful manner. We train a generator using an internal dataset
of training examples, extracted from a single input (image or video and target
text prompt), while leveraging an external pre-trained CLIP model to establish
our losses. Rather than directly generating the edited output, our key idea is
to generate an edit layer (color+opacity) that is composited over the original
input. This allows us to constrain the generation process and maintain high
fidelity to the original input via novel text-driven losses that are applied
directly to the edit layer. Our method neither relies on a pre-trained
generator nor requires user-provided edit masks. We demonstrate localized,
semantic edits on high-resolution natural images and videos across a variety of
objects and scenes.