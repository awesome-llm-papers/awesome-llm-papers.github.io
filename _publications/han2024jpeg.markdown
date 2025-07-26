---
layout: publication
title: 'JPEG-LM: Llms As Image Generators With Canonical Codec Representations'
authors: Xiaochuang Han, Marjan Ghazvininejad, Pang Wei Koh, Yulia Tsvetkov
conference: No Venue
year: 2024
bibkey: han2024jpeg
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66c2a4af2777c05070a6db89'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2408.08459'}]
tags: ["Efficiency", "Model Architecture", "Training Techniques"]
short_authors: Han et al.
---
Recent work in image and video generation has been adopting the autoregressive LLM architecture due to its generality and potentially easy integration into multi-modal systems. The crux of applying autoregressive training in language generation to visual generation is discretization -- representing continuous data like images and videos as discrete tokens. Common methods of discretizing images and videos include modeling raw pixel values, which are prohibitively lengthy, or vector quantization, which requires convoluted pre-hoc training. In this work, we propose to directly model images and videos as compressed files saved on computers via canonical codecs (e.g., JPEG, AVC/H.264). Using the default Llama architecture without any vision-specific modifications, we pretrain JPEG-LM from scratch to generate images (and AVC-LM to generate videos as a proof of concept), by directly outputting compressed file bytes in JPEG and AVC formats. Evaluation of image generation shows that this simple and straightforward approach is more effective than pixel-based modeling and sophisticated vector quantization baselines (on which our method yields a 31% reduction in FID). Our analysis shows that JPEG-LM has an especial advantage over vector quantization models in generating long-tail visual elements. Overall, we show that using canonical codec representations can help lower the barriers between language generation and visual generation, facilitating future research on multi-modal language/image/video LLMs.

https://huggingface.co/discussions/paper/66c2a4af2777c05070a6db89