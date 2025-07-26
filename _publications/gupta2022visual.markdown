---
layout: publication
title: 'Visual Programming: Compositional Visual Reasoning Without Training'
authors: Tanmay Gupta, Aniruddha Kembhavi
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: gupta2022visual
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.11559'}]
tags: ["CVPR"]
short_authors: Tanmay Gupta, Aniruddha Kembhavi
---
We present VISPROG, a neuro-symbolic approach to solving complex and
compositional visual tasks given natural language instructions. VISPROG avoids
the need for any task-specific training. Instead, it uses the in-context
learning ability of large language models to generate python-like modular
programs, which are then executed to get both the solution and a comprehensive
and interpretable rationale. Each line of the generated program may invoke one
of several off-the-shelf computer vision models, image processing routines, or
python functions to produce intermediate outputs that may be consumed by
subsequent parts of the program. We demonstrate the flexibility of VISPROG on 4
diverse tasks - compositional visual question answering, zero-shot reasoning on
image pairs, factual knowledge object tagging, and language-guided image
editing. We believe neuro-symbolic approaches like VISPROG are an exciting
avenue to easily and effectively expand the scope of AI systems to serve the
long tail of complex tasks that people may wish to perform.