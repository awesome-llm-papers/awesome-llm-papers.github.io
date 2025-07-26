---
layout: publication
title: 'Selfcite: Self-supervised Alignment For Context Attribution In Large Language
  Models'
authors: Yung-sung Chuang, Benjamin Cohen-wang, Shannon Zejiang Shen, Zhaofeng Wu,
  Hu Xu, Xi Victoria Lin, James Glass, Shang-wen Li, Wen-tau Yih
conference: No Venue
year: 2025
bibkey: chuang2025selfcite
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2502.09604'}]
tags: ["Efficiency", "Evaluation", "Reinforcement Learning", "Training Techniques"]
short_authors: Chuang et al.
---
We introduce SelfCite, a novel self-supervised approach that aligns LLMs to generate high-quality, fine-grained, sentence-level citations for the statements in their generated responses. Instead of only relying on costly and labor-intensive annotations, SelfCite leverages a reward signal provided by the LLM itself through context ablation: If a citation is necessary, removing the cited text from the context should prevent the same response; if sufficient, retaining the cited text alone should preserve the same response. This reward can guide the inference-time best-of-N sampling strategy to improve citation quality significantly, as well as be used in preference optimization to directly fine-tune the models for generating better citations. The effectiveness of SelfCite is demonstrated by increasing citation F1 up to 5.3 points on the LongBench-Cite benchmark across five long-form question answering tasks.

https://huggingface.co/discussions/paper/67aeac502d48d9bf77283380