---
layout: publication
title: Multi-prompt With Depth Partitioned Cross-modal Learning
authors: Tian et al.
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: tian2023multi
citations: 324
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.06221'}]
tags: [RAG, Prompting, Evaluation, CVPR, Multimodal Models, Datasets]
---
In recent years, soft prompt learning methods have been proposed to fine-tune
large-scale vision-language pre-trained models for various downstream tasks.
These methods typically combine learnable textual tokens with class tokens as
input for models with frozen parameters. However, they often employ a single
prompt to describe class contexts, failing to capture categories' diverse
attributes adequately. This study introduces the Partitioned Multi-modal Prompt
(PMPO), a multi-modal prompting technique that extends the soft prompt from a
single learnable prompt to multiple prompts. Our method divides the visual
encoder depths and connects learnable prompts to the separated visual depths,
enabling different prompts to capture the hierarchical contextual depths of
visual representations. Furthermore, to maximize the advantages of multi-prompt
learning, we incorporate prior information from manually designed templates and
learnable multi-prompts, thus improving the generalization capabilities of our
approach. We evaluate the effectiveness of our approach on three challenging
tasks: new class generalization, cross-dataset evaluation, and domain
generalization. For instance, our method achieves a \\(79.28\\) harmonic mean,
averaged over 11 diverse image recognition datasets (\\(+7.62\\) compared to CoOp),
demonstrating significant competitiveness compared to state-of-the-art
prompting methods.