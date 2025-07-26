---
layout: publication
title: 'Videobert: A Joint Model For Video And Language Representation Learning'
authors: Chen Sun, Austin Myers, Carl Vondrick, Kevin Murphy, Cordelia Schmid
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2019
bibkey: sun2019videobert
citations: 1044
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.01766'}]
tags: ["Efficiency", "ICCV", "Model Architecture", "Training Techniques"]
short_authors: Sun et al.
---
Self-supervised learning has become increasingly important to leverage the
abundance of unlabeled data available on platforms like YouTube. Whereas most
existing approaches learn low-level representations, we propose a joint
visual-linguistic model to learn high-level features without any explicit
supervision. In particular, inspired by its recent success in language
modeling, we build upon the BERT model to learn bidirectional joint
distributions over sequences of visual and linguistic tokens, derived from
vector quantization of video data and off-the-shelf speech recognition outputs,
respectively. We use VideoBERT in numerous tasks, including action
classification and video captioning. We show that it can be applied directly to
open-vocabulary classification, and confirm that large amounts of training data
and cross-modal information are critical to performance. Furthermore, we
outperform the state-of-the-art on video captioning, and quantitative results
verify that the model learns high-level semantic features.