---
layout: publication
title: 'Forgotten Polygons: Multimodal Large Language Models Are Shape-blind'
authors: Rudman et al.
conference: 2023 IEEE International Conference on Big Data (BigData)
year: 2025
bibkey: rudman2025forgotten
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.15969'}]
tags: [GPT, Prompting, Evaluation, Model Architecture, Multimodal Models, Datasets]
---
Despite strong performance on vision-language tasks, Multimodal Large
Language Models (MLLMs) struggle with mathematical problem-solving, with both
open-source and state-of-the-art models falling short of human performance on
visual-math benchmarks. To systematically examine visual-mathematical reasoning
in MLLMs, we (1) evaluate their understanding of geometric primitives, (2) test
multi-step reasoning, and (3) explore a potential solution to improve visual
reasoning capabilities. Our findings reveal fundamental shortcomings in shape
recognition, with top models achieving under 50% accuracy in identifying
regular polygons. We analyze these failures through the lens of dual-process
theory and show that MLLMs rely on System 1 (intuitive, memorized associations)
rather than System 2 (deliberate reasoning). Consequently, MLLMs fail to count
the sides of both familiar and novel shapes, suggesting they have neither
learned the concept of sides nor effectively process visual inputs. Finally, we
propose Visually Cued Chain-of-Thought (VC-CoT) prompting, which enhances
multi-step mathematical reasoning by explicitly referencing visual annotations
in diagrams, boosting GPT-4o's accuracy on an irregular polygon side-counting
task from 7% to 93%. Our findings suggest that System 2 reasoning in MLLMs
remains an open problem, and visually-guided prompting is essential for
successfully engaging visual reasoning. Code available at:
https://github.com/rsinghlab/Shape-Blind.