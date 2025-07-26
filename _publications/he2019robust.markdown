---
layout: publication
title: Robust Sequence-to-sequence Acoustic Modeling With Stepwise Monotonic Attention
  For Neural TTS
authors: Mutian He, Yan Deng, Lei He
conference: Interspeech 2019
year: 2019
bibkey: he2019robust
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.00672'}]
tags: ["INTERSPEECH", "Training Techniques"]
short_authors: Mutian He, Yan Deng, Lei He
---
Neural TTS has demonstrated strong capabilities to generate human-like speech
with high quality and naturalness, while its generalization to out-of-domain
texts is still a challenging task, with regard to the design of attention-based
sequence-to-sequence acoustic modeling. Various errors occur in those inputs
with unseen context, including attention collapse, skipping, repeating, etc.,
which limits the broader applications. In this paper, we propose a novel
stepwise monotonic attention method in sequence-to-sequence acoustic modeling
to improve the robustness on out-of-domain inputs. The method utilizes the
strict monotonic property in TTS with constraints on monotonic hard attention
that the alignments between inputs and outputs sequence must be not only
monotonic but allowing no skipping on inputs. Soft attention could be used to
evade mismatch between training and inference. The experimental results show
that the proposed method could achieve significant improvements in robustness
on out-of-domain scenarios for phoneme-based models, without any regression on
the in-domain naturalness test.