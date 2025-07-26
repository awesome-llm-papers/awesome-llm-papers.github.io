---
layout: publication
title: Can Generalist Foundation Models Outcompete Special-purpose Tuning? Case Study
  In Medicine
authors: Harsha Nori, Yin Tat Lee, Sheng Zhang, Dean Carignan, Richard Edgar, Nicolo
  Fusi, Nicholas King, Jonathan Larson, Yuanzhi Li, Weishung Liu, Renqian Luo, Scott
  Mayer Mckinney, Robert Osazuwa Ness, Hoifung Poon, Tao Qin, Naoto Usuyama, Chris
  White, Eric Horvitz
conference: Arxiv
year: 2023
bibkey: nori2023can
citations: 86
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.16452'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: Nori et al.
---
Generalist foundation models such as GPT-4 have displayed surprising
capabilities in a wide variety of domains and tasks. Yet, there is a prevalent
assumption that they cannot match specialist capabilities of fine-tuned models.
For example, most explorations to date on medical competency benchmarks have
leveraged domain-specific training, as exemplified by efforts on BioGPT and
Med-PaLM. We build on a prior study of GPT-4's capabilities on medical
challenge benchmarks in the absence of special training. Rather than using
simple prompting to highlight the model's out-of-the-box capabilities, we
perform a systematic exploration of prompt engineering. We find that prompting
innovation can unlock deeper specialist capabilities and show that GPT-4 easily
tops prior leading results for medical benchmarks. The prompting methods we
explore are general purpose, and make no specific use of domain expertise,
removing the need for expert-curated content. Our experimental design carefully
controls for overfitting during the prompt engineering process. We introduce
Medprompt, based on a composition of several prompting strategies. With
Medprompt, GPT-4 achieves state-of-the-art results on all nine of the benchmark
datasets in the MultiMedQA suite. The method outperforms leading specialist
models such as Med-PaLM 2 by a significant margin with an order of magnitude
fewer calls to the model. Steering GPT-4 with Medprompt achieves a 27%
reduction in error rate on the MedQA dataset over the best methods to date
achieved with specialist models and surpasses a score of 90% for the first
time. Beyond medical problems, we show the power of Medprompt to generalize to
other domains and provide evidence for the broad applicability of the approach
via studies of the strategy on exams in electrical engineering, machine
learning, philosophy, accounting, law, nursing, and clinical psychology.