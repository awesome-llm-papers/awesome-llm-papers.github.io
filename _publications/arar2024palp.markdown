---
layout: publication
title: 'PALP: Prompt Aligned Personalization Of Text-to-image Models'
authors: Moab Arar, Andrey Voynov, Amir Hertz, Omri Avrahami, Shlomi Fruchter, Yael
  Pritch, Daniel Cohen-or, Ariel Shamir
conference: No Venue
year: 2024
bibkey: arar2024palp
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2401.06105'}]
tags: ["Prompting"]
short_authors: Arar et al.
---
Content creators often aim to create personalized images using personal subjects that go beyond the capabilities of conventional text-to-image models. Additionally, they may want the resulting image to encompass a specific location, style, ambiance, and more. Existing personalization methods may compromise personalization ability or the alignment to complex textual prompts. This trade-off can impede the fulfillment of user prompts and subject fidelity. We propose a new approach focusing on personalization methods for a single prompt to address this issue. We term our approach prompt-aligned personalization. While this may seem restrictive, our method excels in improving text alignment, enabling the creation of images with complex and intricate prompts, which may pose a challenge for current techniques. In particular, our method keeps the personalized model aligned with a target prompt using an additional score distillation sampling term. We demonstrate the versatility of our method in multi- and single-shot settings and further show that it can compose multiple subjects or use inspiration from reference images, such as artworks. We compare our approach quantitatively and qualitatively with existing baselines and state-of-the-art techniques.

https://huggingface.co/discussions/paper/65a0bd7c9185dcca3061aa79