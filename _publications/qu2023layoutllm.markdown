---
layout: publication
title: 'Layoutllm-t2i: Eliciting Layout Guidance From LLM For Text-to-image Generation'
authors: Leigang Qu, Shengqiong Wu, Hao Fei, Liqiang Nie, Tat-seng Chua
conference: 'MM ''23: The 31st ACM International Conference on Multimedia'
year: 2023
citations: 42
bibkey: qu2023layoutllm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.05095'}, {name: Code,
    url: 'https://layoutllm-t2i.github.io'}]
tags: [In-Context Learning, Has Code, Prompting, Merging]
---
In the text-to-image generation field, recent remarkable progress in Stable
Diffusion makes it possible to generate rich kinds of novel photorealistic
images. However, current models still face misalignment issues (e.g.,
problematic spatial relation understanding and numeration failure) in complex
natural scenes, which impedes the high-faithfulness text-to-image generation.
Although recent efforts have been made to improve controllability by giving
fine-grained guidance (e.g., sketch and scribbles), this issue has not been
fundamentally tackled since users have to provide such guidance information
manually. In this work, we strive to synthesize high-fidelity images that are
semantically aligned with a given textual prompt without any guidance. Toward
this end, we propose a coarse-to-fine paradigm to achieve layout planning and
image generation. Concretely, we first generate the coarse-grained layout
conditioned on a given textual prompt via in-context learning based on Large
Language Models. Afterward, we propose a fine-grained object-interaction
diffusion method to synthesize high-faithfulness images conditioned on the
prompt and the automatically generated layout. Extensive experiments
demonstrate that our proposed method outperforms the state-of-the-art models in
terms of layout and image generation. Our code and settings are available at
https://layoutllm-t2i.github.io.