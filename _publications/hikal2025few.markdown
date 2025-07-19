---
layout: publication
title: Few-shot Optimized Framework For Hallucination Detection In Resource-limited
  NLP Systems
authors: Hikal et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: hikal2025few
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.16616'}]
tags: [Training Techniques, Prompting, Tools, CVPR, Evaluation, Few Shot, Efficiency
    And Optimization, Language Modeling, Applications, Fine Tuning, Datasets]
---
Hallucination detection in text generation remains an ongoing struggle for
natural language processing (NLP) systems, frequently resulting in unreliable
outputs in applications such as machine translation and definition modeling.
Existing methods struggle with data scarcity and the limitations of unlabeled
datasets, as highlighted by the SHROOM shared task at SemEval-2024. In this
work, we propose a novel framework to address these challenges, introducing
DeepSeek Few-shot optimization to enhance weak label generation through
iterative prompt engineering. We achieved high-quality annotations that
considerably enhanced the performance of downstream models by restructuring
data to align with instruct generative models. We further fine-tuned the
Mistral-7B-Instruct-v0.3 model on these optimized annotations, enabling it to
accurately detect hallucinations in resource-limited settings. Combining this
fine-tuned model with ensemble learning strategies, our approach achieved 85.5%
accuracy on the test set, setting a new benchmark for the SHROOM task. This
study demonstrates the effectiveness of data restructuring, few-shot
optimization, and fine-tuning in building scalable and robust hallucination
detection frameworks for resource-constrained NLP systems.