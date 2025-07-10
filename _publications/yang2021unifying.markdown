---
layout: publication
title: 'Unitab: Unifying Text And Box Outputs For Grounded Vision-language Modeling'
authors: Zhengyuan Yang et al.
conference: Lecture Notes in Computer Science
year: 2021
citations: 45
bibkey: yang2021unifying
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.12085'}]
tags: [Language Modeling, Multimodal Models, Evaluation]
---
We propose UniTAB that Unifies Text And Box outputs for grounded
vision-language (VL) modeling. Grounded VL tasks such as grounded captioning
require the model to generate a text description and align predicted words with
object regions. To achieve this, models must generate desired text and box
outputs together, and meanwhile indicate the alignments between words and
boxes. In contrast to existing solutions that use multiple separate modules for
different outputs, UniTAB represents both text and box outputs with a shared
token sequence, and introduces a special <obj> token to naturally indicate
word-box alignments in the sequence. UniTAB thus could provide a more
comprehensive and interpretable image description, by freely grounding
generated words to object regions. On grounded captioning, UniTAB presents a
simpler solution with a single output head, and significantly outperforms state
of the art in both grounding and captioning evaluations. On general VL tasks
that have different desired output formats (i.e., text, box, or their
combination), UniTAB with a single network achieves better or comparable
performance than task-specific state of the art. Experiments cover 7 VL
benchmarks, including grounded captioning, visual grounding, image captioning,
and visual question answering. Furthermore, UniTAB's unified multi-task network
and the task-agnostic output sequence design make the model parameter efficient
and generalizable to new tasks.