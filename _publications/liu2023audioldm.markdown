---
layout: publication
title: 'Audioldm 2: Learning Holistic Audio Generation With Self-supervised Pretraining'
authors: Haohe Liu, Qiao Tian, Yi Yuan, Xubo Liu, Xinhao Mei, Qiuqiang Kong, Yuping
  Wang, Wenwu Wang, Yuxuan Wang, Mark D. Plumbley
conference: No Venue
year: 2023
bibkey: liu2023audioldm
additional_links: [{name: Code, url: 'https://audioldm.github.io/audioldm2'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/64d59c3354bb9eb704f073d2'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2308.05734'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Liu et al.
---
Although audio generation shares commonalities across different types of audio, such as speech, music, and sound effects, designing models for each type requires careful consideration of specific objectives and biases that can significantly differ from those of other types. To bring us closer to a unified perspective of audio generation, this paper proposes a framework that utilizes the same learning method for speech, music, and sound effect generation. Our framework introduces a general representation of audio, called language of audio (LOA). Any audio can be translated into LOA based on AudioMAE, a self-supervised pre-trained representation learning model. In the generation process, we translate any modalities into LOA by using a GPT-2 model, and we perform self-supervised audio generation learning with a latent diffusion model conditioned on LOA. The proposed framework naturally brings advantages such as in-context learning abilities and reusable self-supervised pretrained AudioMAE and latent diffusion models. Experiments on the major benchmarks of text-to-audio, text-to-music, and text-to-speech demonstrate new state-of-the-art or competitive performance to previous approaches. Our demo and code are available at https://audioldm.github.io/audioldm2.

https://huggingface.co/discussions/paper/64d59c3354bb9eb704f073d2