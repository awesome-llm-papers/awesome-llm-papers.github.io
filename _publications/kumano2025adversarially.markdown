---
layout: publication
title: Adversarially Pretrained Transformers May Be Universally Robust In-context
  Learners
authors: Kumano Soichiro, Kera Hiroshi, Yamasaki Toshihiko
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2025
bibkey: kumano2025adversarially
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.14042'}]
tags: [Training Techniques, In Context Learning, Transformer, Model Architecture,
  Security, AAAI]
---
Adversarial training is one of the most effective adversarial defenses, but it incurs a high computational cost. In this study, we show that transformers adversarially pretrained on diverse tasks can serve as robust foundation models and eliminate the need for adversarial training in downstream tasks. Specifically, we theoretically demonstrate that through in-context learning, a single adversarially pretrained transformer can robustly generalize to multiple unseen tasks without any additional training, i.e., without any parameter updates. This robustness stems from the model's focus on robust features and its resistance to attacks that exploit non-predictive features. Besides these positive findings, we also identify several limitations. Under certain conditions (though unrealistic), no universally robust single-layer transformers exist. Moreover, robust transformers exhibit an accuracy--robustness trade-off and require a large number of in-context demonstrations. The code is available at https://github.com/s-kumano/universally-robust-in-context-learner.