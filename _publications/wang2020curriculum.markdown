---
layout: publication
title: Curriculum Pre-training For End-to-end Speech Translation
authors: Chengyi Wang, Yu Wu, Shujie Liu, Ming Zhou, Zhenglu Yang
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: wang2020curriculum
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.10093'}]
tags: ["Training Techniques"]
short_authors: Wang et al.
---
End-to-end speech translation poses a heavy burden on the encoder, because it
has to transcribe, understand, and learn cross-lingual semantics
simultaneously. To obtain a powerful encoder, traditional methods pre-train it
on ASR data to capture speech features. However, we argue that pre-training the
encoder only through simple speech recognition is not enough and high-level
linguistic knowledge should be considered. Inspired by this, we propose a
curriculum pre-training method that includes an elementary course for
transcription learning and two advanced courses for understanding the utterance
and mapping words in two languages. The difficulty of these courses is
gradually increasing. Experiments show that our curriculum pre-training method
leads to significant improvements on En-De and En-Fr speech translation
benchmarks.