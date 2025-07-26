---
layout: publication
title: End-to-end Audio Visual Scene-aware Dialog Using Multimodal Attention-based
  Video Features
authors: Chiori Hori, Huda Alamri, Jue Wang, Gordon Wichern, Takaaki Hori, Anoop Cherian,
  Tim K. Marks, Vincent Cartillier, Raphael Gontijo Lopes, Abhishek Das, Irfan Essa,
  Dhruv Batra, Devi Parikh
conference: ICASSP 2019 - 2019 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)
year: 2019
bibkey: hori2018end
citations: 115
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.08409'}]
tags: ["Applications", "Datasets", "ICASSP", "Model Architecture"]
short_authors: Hori et al.
---
Dialog systems need to understand dynamic visual scenes in order to have
conversations with users about the objects and events around them. Scene-aware
dialog systems for real-world applications could be developed by integrating
state-of-the-art technologies from multiple research areas, including:
end-to-end dialog technologies, which generate system responses using models
trained from dialog data; visual question answering (VQA) technologies, which
answer questions about images using learned image features; and video
description technologies, in which descriptions/captions are generated from
videos using multimodal information. We introduce a new dataset of dialogs
about videos of human behaviors. Each dialog is a typed conversation that
consists of a sequence of 10 question-and-answer(QA) pairs between two Amazon
Mechanical Turk (AMT) workers. In total, we collected dialogs on roughly 9,000
videos. Using this new dataset for Audio Visual Scene-aware dialog (AVSD), we
trained an end-to-end conversation model that generates responses in a dialog
about a video. Our experiments demonstrate that using multimodal features that
were developed for multimodal attention-based video description enhances the
quality of generated dialog about dynamic scenes (videos). Our dataset, model
code and pretrained models will be publicly available for a new Video
Scene-Aware Dialog challenge.