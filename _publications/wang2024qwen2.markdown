---
layout: publication
title: 'Qwen2-vl: Enhancing Vision-language Model''s Perception Of The World At Any
  Resolution'
authors: Peng Wang, Shuai Bai, Sinan Tan, Shijie Wang, Zhihao Fan, Jinze Bai, Keqin
  Chen, Xuejing Liu, Jialin Wang, Wenbin Ge, Yang Fan, Kai Dang, Mengfei Du, Xuancheng
  Ren, Rui Men, Dayiheng Liu, Chang Zhou, Jingren Zhou, Junyang Lin
conference: No Venue
year: 2024
bibkey: wang2024qwen2
additional_links: [{name: Code, url: 'https://github.com/QwenLM/Qwen2-VL'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66eb8aaefe376db0aa90bcae'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2409.12191'}]
tags: ["Has Code", "Model Architecture", "Training Techniques"]
short_authors: Wang et al.
---
We present the Qwen2-VL Series, an advanced upgrade of the previous Qwen-VL models that redefines the conventional predetermined-resolution approach in visual processing. Qwen2-VL introduces the Naive Dynamic Resolution mechanism, which enables the model to dynamically process images of varying resolutions into different numbers of visual tokens. This approach allows the model to generate more efficient and accurate visual representations, closely aligning with human perceptual processes. The model also integrates Multimodal Rotary Position Embedding (M-RoPE), facilitating the effective fusion of positional information across text, images, and videos. We employ a unified paradigm for processing both images and videos, enhancing the model's visual perception capabilities. To explore the potential of large multimodal models, Qwen2-VL investigates the scaling laws for large vision-language models (LVLMs). By scaling both the model size-with versions at 2B, 8B, and 72B parameters-and the amount of training data, the Qwen2-VL Series achieves highly competitive performance. Notably, the Qwen2-VL-72B model achieves results comparable to leading models such as GPT-4o and Claude3.5-Sonnet across various multimodal benchmarks, outperforming other generalist models. Code is available at https://github.com/QwenLM/Qwen2-VL.

https://huggingface.co/discussions/paper/66eb8aaefe376db0aa90bcae