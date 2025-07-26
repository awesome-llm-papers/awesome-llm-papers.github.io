---
layout: publication
title: 'NVLM: Open Frontier-class Multimodal Llms'
authors: Wenliang Dai, Nayeon Lee, Boxin Wang, Zhuoling Yang, Zihan Liu, Jon Barker,
  Tuomas Rintamaki, Mohammad Shoeybi, Bryan Catanzaro, Wei Ping
conference: No Venue
year: 2024
bibkey: dai2024nvlm
additional_links: [{name: Code, url: 'https://nvlm-project.github.io/'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66ea3bb56d83fd1e4fce261e'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2409.11402'}]
tags: ["Model Architecture"]
short_authors: Dai et al.
---
We introduce NVLM 1.0, a family of frontier-class multimodal large language models (LLMs) that achieve state-of-the-art results on vision-language tasks, rivaling the leading proprietary models (e.g., GPT-4o) and open-access models (e.g., Llama 3-V 405B and InternVL 2). Remarkably, NVLM 1.0 shows improved text-only performance over its LLM backbone after multimodal training. In terms of model design, we perform a comprehensive comparison between decoder-only multimodal LLMs (e.g., LLaVA) and cross-attention-based models (e.g., Flamingo). Based on the strengths and weaknesses of both approaches, we propose a novel architecture that enhances both training efficiency and multimodal reasoning capabilities. Furthermore, we introduce a 1-D tile-tagging design for tile-based dynamic high-resolution images, which significantly boosts performance on multimodal reasoning and OCR-related tasks. Regarding training data, we meticulously curate and provide detailed information on our multimodal pretraining and supervised fine-tuning datasets. Our findings indicate that dataset quality and task diversity are more important than scale, even during the pretraining phase, across all architectures. Notably, we develop production-grade multimodality for the NVLM-1.0 models, enabling them to excel in vision-language tasks while maintaining and even improving text-only performance compared to their LLM backbones. To achieve this, we craft and integrate a high-quality text-only dataset into multimodal training, alongside a substantial amount of multimodal math and reasoning data, leading to enhanced math and coding capabilities across modalities. To advance research in the field, we are releasing the model weights and will open-source the code for the community: https://nvlm-project.github.io/.

https://huggingface.co/discussions/paper/66ea3bb56d83fd1e4fce261e