---
layout: publication
title: 'Med-flamingo: A Multimodal Medical Few-shot Learner'
authors: Michael Moor et al.
conference: Arxiv
year: 2023
citations: 31
bibkey: moor2023med
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.15189'}, {name: Code,
    url: 'https://github.com/snap-stanford/med-flamingo'}]
tags: [Training Techniques, Pre-Training, Few-Shot, Reinforcement Learning, Has Code,
  Applications, Survey Paper, Multimodal Models]
---
Medicine, by its nature, is a multifaceted domain that requires the synthesis
of information across various modalities. Medical generative vision-language
models (VLMs) make a first step in this direction and promise many exciting
clinical applications. However, existing models typically have to be fine-tuned
on sizeable down-stream datasets, which poses a significant limitation as in
many medical applications data is scarce, necessitating models that are capable
of learning from few examples in real-time. Here we propose Med-Flamingo, a
multimodal few-shot learner adapted to the medical domain. Based on
OpenFlamingo-9B, we continue pre-training on paired and interleaved medical
image-text data from publications and textbooks. Med-Flamingo unlocks few-shot
generative medical visual question answering (VQA) abilities, which we evaluate
on several datasets including a novel challenging open-ended VQA dataset of
visual USMLE-style problems. Furthermore, we conduct the first human evaluation
for generative medical VQA where physicians review the problems and blinded
generations in an interactive app. Med-Flamingo improves performance in
generative medical VQA by up to 20% in clinician's rating and firstly enables
multimodal medical few-shot adaptations, such as rationale generation. We
release our model, code, and evaluation app under
https://github.com/snap-stanford/med-flamingo.