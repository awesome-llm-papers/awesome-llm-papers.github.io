---
layout: publication
title: 'Mm-bigbench: Evaluating Multimodal Models On Multimodal Content Comprehension
  Tasks'
authors: Xiaocui Yang, Wenfang Wu, Shi Feng, Ming Wang, Daling Wang, Yang Li, Qi Sun,
  Yifei Zhang, Xiaoming Fu, Soujanya Poria
conference: Arxiv
year: 2023
bibkey: yang2023mm
citations: 60
additional_links: [{name: Code, url: 'https://github.com/declare-lab/MM-BigBench'},
  {name: Paper, url: 'https://arxiv.org/abs/2310.09036'}]
tags: ["Datasets", "Evaluation"]
short_authors: Yang et al.
---
The popularity of multimodal large language models (MLLMs) has triggered a
recent surge in research efforts dedicated to evaluating these models.
Nevertheless, existing evaluation studies of MLLMs primarily focus on the
comprehension and reasoning of unimodal (vision) content, neglecting
performance evaluations in the domain of multimodal (vision-language) content
understanding. Beyond multimodal reasoning, tasks related to multimodal content
comprehension necessitate a profound understanding of multimodal contexts,
achieved through the multimodal interaction to obtain a final answer. In this
paper, we introduce a comprehensive assessment framework called MM-BigBench,
which incorporates a diverse range of metrics to offer an extensive evaluation
of the performance of various models and instructions across a wide spectrum of
diverse multimodal content comprehension tasks. Consequently, our work
complements research on the performance of MLLMs in multimodal comprehension
tasks, achieving a more comprehensive and holistic evaluation of MLLMs. To
begin, we employ the Best Performance metric to ascertain each model's
performance upper bound on different datasets. Subsequently, the Mean Relative
Gain metric offers an assessment of the overall performance of various models
and instructions, while the Stability metric measures their sensitivity.
Furthermore, previous research centers on evaluating models independently or
solely assessing instructions, neglecting the adaptability between models and
instructions. We propose the Adaptability metric to quantify the adaptability
between models and instructions. Our paper evaluates a total of 20 language
models (14 MLLMs) on 14 multimodal datasets spanning 6 tasks, with 10
instructions for each task, and derives novel insights. Our code will be
released at https://github.com/declare-lab/MM-BigBench.