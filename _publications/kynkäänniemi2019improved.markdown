---
layout: publication
title: Improved Precision And Recall Metric For Assessing Generative Models
authors: "Tuomas Kynk\xE4\xE4nniemi, Tero Karras, Samuli Laine, Jaakko Lehtinen, Timo\
  \ Aila"
conference: Arxiv
year: 2019
bibkey: "kynk\xE4\xE4nniemi2019improved"
citations: 189
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.06991'}]
tags: ["Evaluation"]
short_authors: "Kynk\xE4\xE4nniemi et al."
---
The ability to automatically estimate the quality and coverage of the samples
produced by a generative model is a vital requirement for driving algorithm
research. We present an evaluation metric that can separately and reliably
measure both of these aspects in image generation tasks by forming explicit,
non-parametric representations of the manifolds of real and generated data. We
demonstrate the effectiveness of our metric in StyleGAN and BigGAN by providing
several illustrative examples where existing metrics yield uninformative or
contradictory results. Furthermore, we analyze multiple design variants of
StyleGAN to better understand the relationships between the model architecture,
training methods, and the properties of the resulting sample distribution. In
the process, we identify new variants that improve the state-of-the-art. We
also perform the first principled analysis of truncation methods and identify
an improved method. Finally, we extend our metric to estimate the perceptual
quality of individual samples, and use this to study latent space
interpolations.