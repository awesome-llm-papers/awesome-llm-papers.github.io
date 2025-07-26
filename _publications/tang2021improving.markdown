---
layout: publication
title: Improving Speech Translation By Understanding And Learning From The Auxiliary
  Text Translation Task
authors: Yun Tang, Juan Pino, Xian Li, Changhan Wang, Dmitriy Genzel
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: tang2021improving
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.05782'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Tang et al.
---
Pretraining and multitask learning are widely used to improve the speech to
text translation performance. In this study, we are interested in training a
speech to text translation model along with an auxiliary text to text
translation task. We conduct a detailed analysis to understand the impact of
the auxiliary task on the primary task within the multitask learning framework.
Our analysis confirms that multitask learning tends to generate similar decoder
representations from different modalities and preserve more information from
the pretrained text translation modules. We observe minimal negative transfer
effect between the two tasks and sharing more parameters is helpful to transfer
knowledge from the text task to the speech task. The analysis also reveals that
the modality representation difference at the top decoder layers is still not
negligible, and those layers are critical for the translation quality. Inspired
by these findings, we propose three methods to improve translation quality.
First, a parameter sharing and initialization strategy is proposed to enhance
information sharing between the tasks. Second, a novel attention-based
regularization is proposed for the encoders and pulls the representations from
different modalities closer. Third, an online knowledge distillation is
proposed to enhance the knowledge transfer from the text to the speech task.
Our experiments show that the proposed approach improves translation
performance by more than 2 BLEU over a strong baseline and achieves
state-of-the-art results on the \textsc\{MuST-C\} English-German, English-French
and English-Spanish language pairs.