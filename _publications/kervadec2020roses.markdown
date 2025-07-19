---
layout: publication
title: Roses Are Red, Violets Are Blue... But Should Vqa Expect Them To?
authors: Kervadec et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2020
bibkey: kervadec2020roses
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.05121'}]
tags: [Training Techniques, Alt, CVPR, Evaluation, Ethics And Bias, Reinforcement
    Learning, Datasets]
---
Models for Visual Question Answering (VQA) are notorious for their tendency
to rely on dataset biases, as the large and unbalanced diversity of questions
and concepts involved and tends to prevent models from learning to reason,
leading them to perform educated guesses instead. In this paper, we claim that
the standard evaluation metric, which consists in measuring the overall
in-domain accuracy, is misleading. Since questions and concepts are unbalanced,
this tends to favor models which exploit subtle training set statistics.
Alternatively, naively introducing artificial distribution shifts between train
and test splits is also not completely satisfying. First, the shifts do not
reflect real-world tendencies, resulting in unsuitable models; second, since
the shifts are handcrafted, trained models are specifically designed for this
particular setting, and do not generalize to other configurations. We propose
the GQA-OOD benchmark designed to overcome these concerns: we measure and
compare accuracy over both rare and frequent question-answer pairs, and argue
that the former is better suited to the evaluation of reasoning abilities,
which we experimentally validate with models trained to more or less exploit
biases. In a large-scale study involving 7 VQA models and 3 bias reduction
techniques, we also experimentally demonstrate that these models fail to
address questions involving infrequent concepts and provide recommendations for
future directions of research.