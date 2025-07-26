---
layout: publication
title: The Microsoft 2017 Conversational Speech Recognition System
authors: W. Xiong, L. Wu, F. Alleva, J. Droppo, X. Huang, A. Stolcke
conference: 2017 IEEE International Conference on Acoustics, Speech and Signal Processing
  (ICASSP)
year: 2017
bibkey: xiong2017microsoft
citations: 313
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1708.06073'}]
tags: ["ICASSP"]
short_authors: Xiong et al.
---
We describe the 2017 version of Microsoft's conversational speech recognition
system, in which we update our 2016 system with recent developments in
neural-network-based acoustic and language modeling to further advance the
state of the art on the Switchboard speech recognition task. The system adds a
CNN-BLSTM acoustic model to the set of model architectures we combined
previously, and includes character-based and dialog session aware LSTM language
models in rescoring. For system combination we adopt a two-stage approach,
whereby subsets of acoustic models are first combined at the senone/frame
level, followed by a word-level voting via confusion networks. We also added a
confusion network rescoring step after system combination. The resulting system
yields a 5.1% word error rate on the 2000 Switchboard evaluation set.