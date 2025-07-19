---
layout: publication
title: 'Videorepair: Improving Text-to-video Generation Via Misalignment Evaluation
  And Localized Refinement'
authors: Lee et al.
conference: IEEE Transactions on Multimedia
year: 2024
bibkey: lee2024videorepair
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.15115'}]
tags: [Training Techniques, Prompting, Tools, Evaluation, Datasets, Merging]
---
Recent text-to-video (T2V) diffusion models have demonstrated impressive
generation capabilities across various domains. However, these models often
generate videos that have misalignments with text prompts, especially when the
prompts describe complex scenes with multiple objects and attributes. To
address this, we introduce VideoRepair, a novel model-agnostic, training-free
video refinement framework that automatically identifies fine-grained
text-video misalignments and generates explicit spatial and textual feedback,
enabling a T2V diffusion model to perform targeted, localized refinements.
VideoRepair consists of two stages: In (1) video refinement planning, we first
detect misalignments by generating fine-grained evaluation questions and
answering them using an MLLM. Based on video evaluation outputs, we identify
accurately generated objects and construct localized prompts to precisely
refine misaligned regions. In (2) localized refinement, we enhance video
alignment by 'repairing' the misaligned regions from the original video while
preserving the correctly generated areas. This is achieved by frame-wise region
decomposition using our Region-Preserving Segmentation (RPS) module. On two
popular video generation benchmarks (EvalCrafter and T2V-CompBench),
VideoRepair substantially outperforms recent baselines across various
text-video alignment metrics. We provide a comprehensive analysis of
VideoRepair components and qualitative examples.