---
layout: publication
title: Meta-learning For Low-resource Neural Machine Translation
authors: Jiatao Gu, Yong Wang, Yun Chen, Kyunghyun Cho, Victor O. K. Li
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: gu2018meta
citations: 322
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.08437'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Gu et al.
---
In this paper, we propose to extend the recently introduced model-agnostic
meta-learning algorithm (MAML) for low-resource neural machine translation
(NMT). We frame low-resource translation as a meta-learning problem, and we
learn to adapt to low-resource languages based on multilingual high-resource
language tasks. We use the universal lexical
representation~\citep\{gu2018universal\} to overcome the input-output mismatch
across different languages. We evaluate the proposed meta-learning strategy
using eighteen European languages (Bg, Cs, Da, De, El, Es, Et, Fr, Hu, It, Lt,
Nl, Pl, Pt, Sk, Sl, Sv and Ru) as source tasks and five diverse languages (Ro,
Lv, Fi, Tr and Ko) as target tasks. We show that the proposed approach
significantly outperforms the multilingual, transfer learning based
approach~\citep\{zoph2016transfer\} and enables us to train a competitive NMT
system with only a fraction of training examples. For instance, the proposed
approach can achieve as high as 22.04 BLEU on Romanian-English WMT'16 by seeing
only 16,000 translated words (~600 parallel sentences).