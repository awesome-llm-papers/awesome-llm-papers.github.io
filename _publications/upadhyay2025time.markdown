---
layout: publication
title: 'Time Blindness: Why Video-language Models Can''t See What Humans Can?'
authors: Ujjwal Upadhyay, Mukul Ranjan, Zhiqiang Shen, Mohamed Elhoseiny
conference: No Venue
year: 2025
bibkey: upadhyay2025time
additional_links: [{name: Code, url: 'https://timeblindness.github.io/'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/683d3d743f97feb881155c56'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2505.24867'}]
tags: ["Datasets", "Evaluation", "Has Code", "Training Techniques"]
short_authors: Upadhyay et al.
---
Recent advances in vision-language models (VLMs) have made impressive strides in understanding spatio-temporal relationships in videos. However, when spatial information is obscured, these models struggle to capture purely temporal patterns. We introduce SpookyBench, a benchmark where information is encoded solely in temporal sequences of noise-like frames, mirroring natural phenomena from biological signaling to covert communication. Interestingly, while humans can recognize shapes, text, and patterns in these sequences with over 98% accuracy, state-of-the-art VLMs achieve 0% accuracy. This performance gap highlights a critical limitation: an over-reliance on frame-level spatial features and an inability to extract meaning from temporal cues. Furthermore, when trained in data sets with low spatial signal-to-noise ratios (SNR), temporal understanding of models degrades more rapidly than human perception, especially in tasks requiring fine-grained temporal reasoning. Overcoming this limitation will require novel architectures or training paradigms that decouple spatial dependencies from temporal processing. Our systematic analysis shows that this issue persists across model scales and architectures. We release SpookyBench to catalyze research in temporal pattern recognition and bridge the gap between human and machine video understanding. Dataset and code has been made available on our project website: https://timeblindness.github.io/.

https://huggingface.co/discussions/paper/683d3d743f97feb881155c56