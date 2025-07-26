---
layout: publication
title: 'Commoncanvas: An Open Diffusion Model Trained With Creative-commons Images'
authors: Aaron Gokaslan, A. Feder Cooper, Jasmine Collins, Landan Seguin, Austin Jacobson,
  Mihir Patel, Jonathan Frankle, Cory Stephenson, Volodymyr Kuleshov
conference: No Venue
year: 2023
bibkey: gokaslan2023commoncanvas
additional_links: [{name: Code, url: 'https://github.com/mosaicml/diffusion/blob/main/assets/common-canvas.md'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6539e118f186c8b4a8b252ef'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2310.16825'}]
tags: ["Datasets", "Has Code"]
short_authors: Gokaslan et al.
---
We assemble a dataset of Creative-Commons-licensed (CC) images, which we use to train a set of open diffusion models that are qualitatively competitive with Stable Diffusion 2 (SD2). This task presents two challenges: (1) high-resolution CC images lack the captions necessary to train text-to-image generative models; (2) CC images are relatively scarce. In turn, to address these challenges, we use an intuitive transfer learning technique to produce a set of high-quality synthetic captions paired with curated CC images. We then develop a data- and compute-efficient training recipe that requires as little as 3% of the LAION-2B data needed to train existing SD2 models, but obtains comparable quality. These results indicate that we have a sufficient number of CC images (~70 million) for training high-quality models. Our training recipe also implements a variety of optimizations that achieve ~3X training speed-ups, enabling rapid model iteration. We leverage this recipe to train several high-quality text-to-image models, which we dub the CommonCanvas family. Our largest model achieves comparable performance to SD2 on a human evaluation, despite being trained on our CC dataset that is significantly smaller than LAION and using synthetic captions for training. We release our models, data, and code at https://github.com/mosaicml/diffusion/blob/main/assets/common-canvas.md

https://huggingface.co/discussions/paper/6539e118f186c8b4a8b252ef