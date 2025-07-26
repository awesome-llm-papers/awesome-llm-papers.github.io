---
layout: publication
title: Leveraging Weakly Supervised Data To Improve End-to-end Speech-to-text Translation
authors: Ye Jia, Melvin Johnson, Wolfgang Macherey, Ron J. Weiss, Yuan Cao, Chung-cheng
  Chiu, Naveen Ari, Stella Laurenzo, Yonghui Wu
conference: ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2019
bibkey: jia2018leveraging
citations: 163
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.02050'}]
tags: ["Datasets", "ICASSP", "Training Techniques"]
short_authors: Jia et al.
---
End-to-end Speech Translation (ST) models have many potential advantages when
compared to the cascade of Automatic Speech Recognition (ASR) and text Machine
Translation (MT) models, including lowered inference latency and the avoidance
of error compounding. However, the quality of end-to-end ST is often limited by
a paucity of training data, since it is difficult to collect large parallel
corpora of speech and translated transcript pairs. Previous studies have
proposed the use of pre-trained components and multi-task learning in order to
benefit from weakly supervised training data, such as speech-to-transcript or
text-to-foreign-text pairs. In this paper, we demonstrate that using
pre-trained MT or text-to-speech (TTS) synthesis models to convert weakly
supervised data into speech-to-translation pairs for ST training can be more
effective than multi-task learning. Furthermore, we demonstrate that a high
quality end-to-end ST model can be trained using only weakly supervised
datasets, and that synthetic data sourced from unlabeled monolingual text or
speech can be used to improve performance. Finally, we discuss methods for
avoiding overfitting to synthetic speech with a quantitative ablation study.