---
layout: publication
title: 'Ola: Pushing The Frontiers Of Omni-modal Language Model With Progressive Modality
  Alignment'
authors: Zuyan Liu, Yuhao Dong, Jiahui Wang, Ziwei Liu, Winston Hu, Jiwen Lu, Yongming
  Rao
conference: No Venue
year: 2025
bibkey: liu2025ola
additional_links: [{name: Code, url: 'https://github.com/Ola-Omni/Ola'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/67a586fbd177de2eeba7deae'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2502.04328'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Liu et al.
---
Recent advances in large language models, particularly following GPT-4o, have sparked increasing interest in developing omni-modal models capable of understanding more modalities. While some open-source alternatives have emerged, there is still a notable lag behind specialized single-modality models in performance. In this paper, we present Ola, an Omni-modal language model that achieves competitive performance across image, video, and audio understanding compared to specialized counterparts. The core design of Ola lies in its progressive modality alignment strategy that extends the supporting modality of the language model progressively. Our training pipeline begins with the most distinct modalities: image and text, then gradually expands the skill sets of the model using speech data that connects language and audio knowledge, and video data that connects all modalities. The progressive learning pipeline also enables us to maintain a relatively small size of the cross-modal alignment data, making developing omni-modal from existing vision-language models easy and less costly. Moreover, to unlock an advanced interactive experience like GPT-4o, we further design a sentence-wise decoding solution for streaming speech generation. Extensive experiments demonstrate that Ola surpasses existing open omni-modal LLMs across all modalities while achieving highly competitive performance compared to state-of-the-art specialized models of similar sizes. We aim to make Ola a fully open omni-modal understanding solution to advance future research in this emerging field. Model weights, code, and data are open-sourced at https://github.com/Ola-Omni/Ola.

https://huggingface.co/discussions/paper/67a586fbd177de2eeba7deae