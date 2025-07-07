---
layout: publication
title: 'Controlled Hallucinations: Learning To Generate Faithfully From Noisy Data'
authors: Katja Filippova
conference: Findings of EMNLP 2020
year: 2020
citations: 18
bibkey: filippova2020controlled
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.05873'}]
tags: [Training Techniques, Reinforcement Learning, Applications, Language Modeling,
  Model Architecture]
---
Neural text generation (data- or text-to-text) demonstrates remarkable
performance when training data is abundant which for many applications is not
the case. To collect a large corpus of parallel data, heuristic rules are often
used but they inevitably let noise into the data, such as phrases in the output
which cannot be explained by the input. Consequently, models pick up on the
noise and may hallucinate--generate fluent but unsupported text. Our
contribution is a simple but powerful technique to treat such hallucinations as
a controllable aspect of the generated text, without dismissing any input and
without modifying the model architecture. On the WikiBio corpus (Lebret et al.,
2016), a particularly noisy dataset, we demonstrate the efficacy of the
technique both in an automatic and in a human evaluation.