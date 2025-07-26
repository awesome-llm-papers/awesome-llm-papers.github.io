---
layout: publication
title: 'Aligntts: Efficient Feed-forward Text-to-speech System Without Explicit Alignment'
authors: Zhen Zeng, Jianzong Wang, Ning Cheng, Tian Xia, Jing Xiao
conference: ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2020
bibkey: zeng2020aligntts
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2003.01950'}]
tags: ["Efficiency", "ICASSP", "Model Architecture"]
short_authors: Zeng et al.
---
Targeting at both high efficiency and performance, we propose AlignTTS to
predict the mel-spectrum in parallel. AlignTTS is based on a Feed-Forward
Transformer which generates mel-spectrum from a sequence of characters, and the
duration of each character is determined by a duration predictor.Instead of
adopting the attention mechanism in Transformer TTS to align text to
mel-spectrum, the alignment loss is presented to consider all possible
alignments in training by use of dynamic programming. Experiments on the
LJSpeech dataset show that our model achieves not only state-of-the-art
performance which outperforms Transformer TTS by 0.03 in mean option score
(MOS), but also a high efficiency which is more than 50 times faster than
real-time.