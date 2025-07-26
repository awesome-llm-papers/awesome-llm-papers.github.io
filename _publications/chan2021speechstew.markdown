---
layout: publication
title: 'Speechstew: Simply Mix All Available Speech Recognition Data To Train One
  Large Neural Network'
authors: William Chan, Daniel Park, Chris Lee, Yu Zhang, Quoc Le, Mohammad Norouzi
conference: Arxiv
year: 2021
bibkey: chan2021speechstew
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.02133'}]
tags: ["Datasets"]
short_authors: Chan et al.
---
We present SpeechStew, a speech recognition model that is trained on a
combination of various publicly available speech recognition datasets: AMI,
Broadcast News, Common Voice, LibriSpeech, Switchboard/Fisher, Tedlium, and
Wall Street Journal. SpeechStew simply mixes all of these datasets together,
without any special re-weighting or re-balancing of the datasets. SpeechStew
achieves SoTA or near SoTA results across a variety of tasks, without the use
of an external language model. Our results include 9.0% WER on AMI-IHM, 4.7%
WER on Switchboard, 8.3% WER on CallHome, and 1.3% on WSJ, which
significantly outperforms prior work with strong external language models. We
also demonstrate that SpeechStew learns powerful transfer learning
representations. We fine-tune SpeechStew on a noisy low resource speech
dataset, CHiME-6. We achieve 38.9% WER without a language model, which
compares to 38.6% WER to a strong HMM baseline with a language model.