---
layout: publication
title: Encouraging Lstms To Anticipate Actions Very Early
authors: Mohammad Sadegh Aliakbarian, Fatemeh Sadat Saleh, Mathieu Salzmann, Basura
  Fernando, Lars Petersson, Lars Andersson
conference: 2017 IEEE International Conference on Computer Vision (ICCV)
year: 2017
bibkey: aliakbarian2017encouraging
citations: 164
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.07023'}]
tags: ["ICCV", "Model Architecture"]
short_authors: Aliakbarian et al.
---
In contrast to the widely studied problem of recognizing an action given a
complete sequence, action anticipation aims to identify the action from only
partially available videos. As such, it is therefore key to the success of
computer vision applications requiring to react as early as possible, such as
autonomous navigation. In this paper, we propose a new action anticipation
method that achieves high prediction accuracy even in the presence of a very
small percentage of a video sequence. To this end, we develop a multi-stage
LSTM architecture that leverages context-aware and action-aware features, and
introduce a novel loss function that encourages the model to predict the
correct class as early as possible. Our experiments on standard benchmark
datasets evidence the benefits of our approach; We outperform the
state-of-the-art action anticipation methods for early prediction by a relative
increase in accuracy of 22.0% on JHMDB-21, 14.0% on UT-Interaction and 49.9% on
UCF-101.