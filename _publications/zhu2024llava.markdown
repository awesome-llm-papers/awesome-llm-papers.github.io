---
layout: publication
title: 'Llava-3d: A Simple Yet Effective Pathway To Empowering Lmms With 3d-awareness'
authors: Zhu et al.
conference: 2017 IEEE International Conference on Computer Vision (ICCV)
year: 2024
bibkey: zhu2024llava
citations: 1063
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.18125'}]
tags: [RAG, ICCV, Tools, Model Architecture, Reinforcement Learning, Multimodal Models,
  Datasets]
---
Recent advancements in Large Multimodal Models (LMMs) have greatly enhanced
their proficiency in 2D visual understanding tasks, enabling them to
effectively process and understand images and videos. However, the development
of LMMs with 3D scene understanding capabilities has been hindered by the lack
of large-scale 3D vision-language datasets and powerful 3D encoders. In this
paper, we introduce a simple yet effective framework called LLaVA-3D.
Leveraging the strong 2D visual understanding priors from LLaVA, our LLaVA-3D
efficiently adapts LLaVA for 3D scene understanding without compromising 2D
understanding capabilities. To achieve this, we utilize the 3D position
embeddings to enhance the 2D CLIP Patches with 3D spatial context information
and construct 3D patches. By integrating the 3D position embeddings into 2D
LMMs and employing joint 2D and 3D vision-language instruction tuning, we
establish a unified architecture for both 2D visual understanding and 3D scene
understanding. In contrast to previous 3D LMMs, LLaVA-3D supports decoding
accurate 3D spatial perception outputs, e.g., 3D bounding boxes, directly from
these 3D patches, without relying on the time-consuming off-the-shelf 3D
segmentors. Experimental results show that LLaVA-3D converges 3.5x faster than
existing 3D LMMs when trained on 3D vision-language datasets. Moreover,
LLaVA-3D not only achieves state-of-the-art performance across various 3D tasks
but also maintains comparable 2D visual understanding and vision-language
conversation capabilities with LLaVA.