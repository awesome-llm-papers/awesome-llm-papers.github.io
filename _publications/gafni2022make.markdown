---
layout: publication
title: 'Make-a-scene: Scene-based Text-to-image Generation With Human Priors'
authors: Oran Gafni, Adam Polyak, Oron Ashual, Shelly Sheynin, Devi Parikh, Yaniv
  Taigman
conference: Lecture Notes in Computer Science
year: 2022
bibkey: gafni2022make
citations: 211
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.13131'}]
tags: ["Model Architecture"]
short_authors: Gafni et al.
---
Recent text-to-image generation methods provide a simple yet exciting
conversion capability between text and image domains. While these methods have
incrementally improved the generated image fidelity and text relevancy, several
pivotal gaps remain unanswered, limiting applicability and quality. We propose
a novel text-to-image method that addresses these gaps by (i) enabling a simple
control mechanism complementary to text in the form of a scene, (ii)
introducing elements that substantially improve the tokenization process by
employing domain-specific knowledge over key image regions (faces and salient
objects), and (iii) adapting classifier-free guidance for the transformer use
case. Our model achieves state-of-the-art FID and human evaluation results,
unlocking the ability to generate high fidelity images in a resolution of
512x512 pixels, significantly improving visual quality. Through scene
controllability, we introduce several new capabilities: (i) Scene editing, (ii)
text editing with anchor scenes, (iii) overcoming out-of-distribution text
prompts, and (iv) story illustration generation, as demonstrated in the story
we wrote.