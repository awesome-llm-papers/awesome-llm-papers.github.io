---
layout: publication
title: 'Adaptmllm: Fine-tuning Multilingual Language Models On Low-resource Languages
  With Integrated LLM Playgrounds'
authors: "S\xE9amus Lankford, Haithem Afli, Andy Way"
conference: Information
year: 2024
citations: 19
bibkey: lankford2024fine
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.02370'}]
tags: [Training Techniques, Fine-Tuning, Evaluation]
---
The advent of Multilingual Language Models (MLLMs) and Large Language Models
has spawned innovation in many areas of natural language processing. Despite
the exciting potential of this technology, its impact on developing
high-quality Machine Translation (MT) outputs for low-resource languages
remains relatively under-explored. Furthermore, an open-source application,
dedicated to both fine-tuning MLLMs and managing the complete MT workflow for
low-resources languages, remains unavailable. We aim to address these
imbalances through the development of adaptMLLM, which streamlines all
processes involved in the fine-tuning of MLLMs for MT. This open-source
application is tailored for developers, translators, and users who are engaged
in MT. An intuitive interface allows for easy customisation of hyperparameters,
and the application offers a range of metrics for model evaluation and the
capability to deploy models as a translation service directly within the
application. As a multilingual tool, we used adaptMLLM to fine-tune models for
two low-resource language pairs: English to Irish (EN\\(\leftrightarrow\\)GA) and
English to Marathi (EN\\(\leftrightarrow\\)MR). Compared with baselines from the
LoResMT2021 Shared Task, the adaptMLLM system demonstrated significant
improvements. In the EN\\(\rightarrow\\)GA direction, an improvement of 5.2 BLEU
points was observed and an increase of 40.5 BLEU points was recorded in the
GA\\(\rightarrow\\)EN direction. Significant improvements in the translation
performance of the EN\\(\leftrightarrow\\)MR pair were also observed notably in the
MR\\(\rightarrow\\)EN direction with an increase of 21.3 BLEU points. Finally, a
fine-grained human evaluation of the MLLM output on the EN\\(\rightarrow\\)GA pair
was conducted using the Multidimensional Quality Metrics and Scalar Quality
Metrics error taxonomies. The application and models are freely available.