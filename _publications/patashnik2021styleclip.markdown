---
layout: publication
title: 'Styleclip: Text-driven Manipulation Of Stylegan Imagery'
authors: Patashnik et al.
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2021
bibkey: patashnik2021styleclip
citations: 738
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.17249'}]
tags: [RAG, ICCV, Training Techniques, Prompting, Efficiency And Optimization]
---
Inspired by the ability of StyleGAN to generate highly realistic images in a
variety of domains, much recent work has focused on understanding how to use
the latent spaces of StyleGAN to manipulate generated and real images. However,
discovering semantically meaningful latent manipulations typically involves
painstaking human examination of the many degrees of freedom, or an annotated
collection of images for each desired manipulation. In this work, we explore
leveraging the power of recently introduced Contrastive Language-Image
Pre-training (CLIP) models in order to develop a text-based interface for
StyleGAN image manipulation that does not require such manual effort. We first
introduce an optimization scheme that utilizes a CLIP-based loss to modify an
input latent vector in response to a user-provided text prompt. Next, we
describe a latent mapper that infers a text-guided latent manipulation step for
a given input image, allowing faster and more stable text-based manipulation.
Finally, we present a method for mapping a text prompts to input-agnostic
directions in StyleGAN's style space, enabling interactive text-driven image
manipulation. Extensive results and comparisons demonstrate the effectiveness
of our approaches.