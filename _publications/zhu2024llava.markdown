---
layout: publication
title: 'Llava-3d: A Simple Yet Effective Pathway To Empowering Lmms With 3d-awareness'
authors: Chenming Zhu, Tai Wang, Wenwei Zhang, Jiangmiao Pang, Xihui Liu
conference: No Venue
year: 2024
bibkey: zhu2024llava
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66f62dad793e1463e406fff4'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2409.18125'}]
tags: ["Model Architecture"]
short_authors: Zhu et al.
---
Recent advancements in Large Multimodal Models (LMMs) have greatly enhanced their proficiency in 2D visual understanding tasks, enabling them to effectively process and understand images and videos. However, the development of LMMs with 3D-awareness for 3D scene understanding has been hindered by the lack of large-scale 3D vision-language datasets and powerful 3D encoders. In this paper, we introduce a simple yet effective framework called LLaVA-3D. Leveraging the strong 2D understanding priors from LLaVA, our LLaVA-3D efficiently adapts LLaVA for 3D scene understanding without compromising 2D understanding capabilities. To achieve this, we employ a simple yet effective representation, 3D Patch, which connects 2D CLIP patch features with their corresponding positions in 3D space. By integrating the 3D Patches into 2D LMMs and employing joint 2D and 3D vision-language instruction tuning, we establish a unified architecture for both 2D image understanding and 3D scene understanding. Experimental results show that LLaVA-3D converges 3.5x faster than existing 3D LMMs when trained on 3D vision-language datasets. Moreover, LLaVA-3D not only achieves state-of-the-art performance across various 3D tasks but also maintains comparable 2D image understanding and vision-language conversation capabilities with LLaVA.

https://huggingface.co/discussions/paper/66f62dad793e1463e406fff4