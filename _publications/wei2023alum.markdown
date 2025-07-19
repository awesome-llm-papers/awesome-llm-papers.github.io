---
layout: publication
title: 'ALUM: Adversarial Data Uncertainty Modeling From Latent Model Uncertainty
  Compensation'
authors: Wei et al.
conference: Journal of the European Economic Association
year: 2023
bibkey: wei2023alum
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.16866'}]
tags: [Model Architecture, Security, Training Techniques, Attention Mechanism]
---
It is critical that the models pay attention not only to accuracy but also to
the certainty of prediction. Uncertain predictions of deep models caused by
noisy data raise significant concerns in trustworthy AI areas. To explore and
handle uncertainty due to intrinsic data noise, we propose a novel method
called ALUM to simultaneously handle the model uncertainty and data uncertainty
in a unified scheme. Rather than solely modeling data uncertainty in the
ultimate layer of a deep model based on randomly selected training data, we
propose to explore mined adversarial triplets to facilitate data uncertainty
modeling and non-parametric uncertainty estimations to compensate for the
insufficiently trained latent model layers. Thus, the critical data uncertainty
and model uncertainty caused by noisy data can be readily quantified for
improving model robustness. Our proposed ALUM is model-agnostic which can be
easily implemented into any existing deep model with little extra computation
overhead. Extensive experiments on various noisy learning tasks validate the
superior robustness and generalization ability of our method. The code is
released at https://github.com/wwzjer/ALUM.