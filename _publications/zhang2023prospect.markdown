---
layout: publication
title: 'Prospect: Prompt Spectrum For Attribute-aware Personalization Of Diffusion
  Models'
authors: Zhang et al.
conference: ACM Transactions on Graphics
year: 2023
bibkey: zhang2023prospect
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.16225'}]
tags: [RAG, Training Techniques, Prompting, Applications, Fine Tuning, Merging]
---
Personalizing generative models offers a way to guide image generation with
user-provided references. Current personalization methods can invert an object
or concept into the textual conditioning space and compose new natural
sentences for text-to-image diffusion models. However, representing and editing
specific visual attributes such as material, style, and layout remains a
challenge, leading to a lack of disentanglement and editability. To address
this problem, we propose a novel approach that leverages the step-by-step
generation process of diffusion models, which generate images from low to high
frequency information, providing a new perspective on representing, generating,
and editing images. We develop the Prompt Spectrum Space P*, an expanded
textual conditioning space, and a new image representation method called
\sysname. ProSpect represents an image as a collection of inverted textual
token embeddings encoded from per-stage prompts, where each prompt corresponds
to a specific generation stage (i.e., a group of consecutive steps) of the
diffusion model. Experimental results demonstrate that P* and ProSpect offer
better disentanglement and controllability compared to existing methods. We
apply ProSpect in various personalized attribute-aware image generation
applications, such as image-guided or text-driven manipulations of materials,
style, and layout, achieving previously unattainable results from a single
image input without fine-tuning the diffusion models. Our source code is
available athttps://github.com/zyxElsa/ProSpect.