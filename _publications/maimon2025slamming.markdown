---
layout: publication
title: 'Slamming: Training A Speech Language Model On One GPU In A Day'
authors: Gallil Maimon, Avishai Elmakies, Yossi Adi
conference: No Venue
year: 2025
bibkey: maimon2025slamming
additional_links: [{name: Code, url: 'https://pages.cs.huji.ac.il/adiyoss-lab/slamming'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/67bd3973f077ddf1f98bacf9'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.15814'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Gallil Maimon, Avishai Elmakies, Yossi Adi
---
We introduce Slam, a recipe for training high-quality Speech Language Models (SLMs) on a single academic GPU in 24 hours. We do so through empirical analysis of model initialisation and architecture, synthetic training data, preference optimisation with synthetic data and tweaking all other components. We empirically demonstrate that this training recipe also scales well with more compute getting results on par with leading SLMs in a fraction of the compute cost. We hope these insights will make SLM training and research more accessible. In the context of SLM scaling laws, our results far outperform predicted compute optimal performance, giving an optimistic view to SLM feasibility. See code, data, models, samples at - https://pages.cs.huji.ac.il/adiyoss-lab/slamming .

https://huggingface.co/discussions/paper/67bd3973f077ddf1f98bacf9