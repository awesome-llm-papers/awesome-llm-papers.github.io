---
layout: publication
title: Direct Speech-to-speech Translation With A Sequence-to-sequence Model
authors: Ye Jia, Ron J. Weiss, Fadi Biadsy, Wolfgang Macherey, Melvin Johnson, Zhifeng
  Chen, Yonghui Wu
conference: Interspeech 2019
year: 2019
bibkey: jia2019direct
citations: 150
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.06037'}]
tags: ["INTERSPEECH"]
short_authors: Jia et al.
---
We present an attention-based sequence-to-sequence neural network which can
directly translate speech from one language into speech in another language,
without relying on an intermediate text representation. The network is trained
end-to-end, learning to map speech spectrograms into target spectrograms in
another language, corresponding to the translated content (in a different
canonical voice). We further demonstrate the ability to synthesize translated
speech using the voice of the source speaker. We conduct experiments on two
Spanish-to-English speech translation datasets, and find that the proposed
model slightly underperforms a baseline cascade of a direct speech-to-text
translation model and a text-to-speech synthesis model, demonstrating the
feasibility of the approach on this very challenging task.