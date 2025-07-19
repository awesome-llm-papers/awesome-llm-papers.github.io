---
layout: publication
title: 'E-vil: A Dataset And Benchmark For Natural Language Explanations In Vision-language
  Tasks'
authors: Kayser et al.
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2021
bibkey: kayser2021e
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2105.03761'}]
tags: [Interpretability And Explainability, ICCV, GPT, Tools, Evaluation, Model Architecture,
  Language Modeling, Multimodal Models, Datasets]
---
Recently, there has been an increasing number of efforts to introduce models
capable of generating natural language explanations (NLEs) for their
predictions on vision-language (VL) tasks. Such models are appealing, because
they can provide human-friendly and comprehensive explanations. However, there
is a lack of comparison between existing methods, which is due to a lack of
re-usable evaluation frameworks and a scarcity of datasets. In this work, we
introduce e-ViL and e-SNLI-VE. e-ViL is a benchmark for explainable
vision-language tasks that establishes a unified evaluation framework and
provides the first comprehensive comparison of existing approaches that
generate NLEs for VL tasks. It spans four models and three datasets and both
automatic metrics and human evaluation are used to assess model-generated
explanations. e-SNLI-VE is currently the largest existing VL dataset with NLEs
(over 430k instances). We also propose a new model that combines UNITER, which
learns joint embeddings of images and text, and GPT-2, a pre-trained language
model that is well-suited for text generation. It surpasses the previous state
of the art by a large margin across all datasets. Code and data are available
here: https://github.com/maximek3/e-ViL.