---
layout: publication
title: 'RITUAL: Random Image Transformations As A Universal Anti-hallucination Lever
  In Large Vision Language Models'
authors: Woo et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2024
bibkey: woo2024ritual
citations: 136
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.17821'}]
tags: [RAG, EMNLP, Training Techniques, Alt, Evaluation, Datasets]
---
Recent advancements in Large Vision Language Models (LVLMs) have
revolutionized how machines understand and generate textual responses based on
visual inputs, yet they often produce "hallucinatory" outputs that misinterpret
visual information, posing challenges in reliability and trustworthiness. We
propose RITUAL, a simple decoding method that reduces hallucinations by
leveraging randomly transformed images as complementary inputs during decoding,
adjusting the output probability distribution without additional training or
external models. Our key insight is that random transformations expose the
model to diverse visual perspectives, enabling it to correct misinterpretations
that lead to hallucinations. Specifically, when a model hallucinates based on
the original image, the transformed images -- altered in aspects such as
orientation, scale, or color -- provide alternative viewpoints that help
recalibrate the model's predictions. By integrating the probability
distributions from both the original and transformed images, RITUAL effectively
reduces hallucinations. To further improve reliability and address potential
instability from arbitrary transformations, we introduce RITUAL+, an extension
that selects image transformations based on self-feedback from the LVLM.
Instead of applying transformations randomly, RITUAL+ uses the LVLM to evaluate
and choose transformations that are most beneficial for reducing hallucinations
in a given context. This self-adaptive approach mitigates the potential
negative impact of certain transformations on specific tasks, ensuring more
consistent performance across different scenarios. Experiments demonstrate that
RITUAL and RITUAL+ significantly reduce hallucinations across several object
hallucination benchmarks.