---
layout: publication
title: Blended Diffusion For Text-driven Editing Of Natural Images
authors: Omri Avrahami, Dani Lischinski, Ohad Fried
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: avrahami2021blended
citations: 436
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2111.14818'}]
tags: ["Applications", "CVPR"]
short_authors: Omri Avrahami, Dani Lischinski, Ohad Fried
---
Natural language offers a highly intuitive interface for image editing. In
this paper, we introduce the first solution for performing local (region-based)
edits in generic natural images, based on a natural language description along
with an ROI mask. We achieve our goal by leveraging and combining a pretrained
language-image model (CLIP), to steer the edit towards a user-provided text
prompt, with a denoising diffusion probabilistic model (DDPM) to generate
natural-looking results. To seamlessly fuse the edited region with the
unchanged parts of the image, we spatially blend noised versions of the input
image with the local text-guided diffusion latent at a progression of noise
levels. In addition, we show that adding augmentations to the diffusion process
mitigates adversarial results. We compare against several baselines and related
methods, both qualitatively and quantitatively, and show that our method
outperforms these solutions in terms of overall realism, ability to preserve
the background and matching the text. Finally, we show several text-driven
editing applications, including adding a new object to an image,
removing/replacing/altering existing objects, background replacement, and image
extrapolation. Code is available at:
https://omriavrahami.com/blended-diffusion-page/