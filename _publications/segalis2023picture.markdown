---
layout: publication
title: 'A Picture Is Worth A Thousand Words: Principled Recaptioning Improves Image
  Generation'
authors: Eyal Segalis, Dani Valevski, Danny Lumen, Yossi Matias, Yaniv Leviathan
conference: No Venue
year: 2023
bibkey: segalis2023picture
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2310.16656'}]
tags: ["Datasets", "Efficiency", "Evaluation", "Prompting", "Training Techniques"]
short_authors: Segalis et al.
---
Text-to-image diffusion models achieved a remarkable leap in capabilities over the last few years, enabling high-quality and diverse synthesis of images from a textual prompt. However, even the most advanced models often struggle to precisely follow all of the directions in their prompts. The vast majority of these models are trained on datasets consisting of (image, caption) pairs where the images often come from the web, and the captions are their HTML alternate text. A notable example is the LAION dataset, used by Stable Diffusion and other models. In this work we observe that these captions are often of low quality, and argue that this significantly affects the model's capability to understand nuanced semantics in the textual prompts. We show that by relabeling the corpus with a specialized automatic captioning model and training a text-to-image model on the recaptioned dataset, the model benefits substantially across the board. First, in overall image quality: e.g. FID 14.84 vs. the baseline of 17.87, and 64.3% improvement in faithful image generation according to human evaluation. Second, in semantic alignment, e.g. semantic object accuracy 84.34 vs. 78.90, counting alignment errors 1.32 vs. 1.44 and positional alignment 62.42 vs. 57.60. We analyze various ways to relabel the corpus and provide evidence that this technique, which we call RECAP, both reduces the train-inference discrepancy and provides the model with more information per example, increasing sample efficiency and allowing the model to better understand the relations between captions and images.

https://huggingface.co/discussions/paper/6539d9d1f2ef6c212318b9d7