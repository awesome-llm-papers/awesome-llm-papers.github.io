---
layout: publication
title: Temporal In-context Fine-tuning For Versatile Control Of Video Diffusion Models
authors: Kinam Kim, Junha Hyung, Jaegul Choo
conference: No Venue
year: 2025
bibkey: kim2025temporal
additional_links: [{name: Code, url: 'https://kinam0252.github.io/TIC-FT/'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/683e7cc1402acb186580d663'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2506.00996'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Kinam Kim, Junha Hyung, Jaegul Choo
---
Recent advances in text-to-video diffusion models have enabled high-quality video synthesis, but controllable generation remains challenging, particularly under limited data and compute. Existing fine-tuning methods for conditional generation often rely on external encoders or architectural modifications, which demand large datasets and are typically restricted to spatially aligned conditioning, limiting flexibility and scalability. In this work, we introduce Temporal In-Context Fine-Tuning (TIC-FT), an efficient and versatile approach for adapting pretrained video diffusion models to diverse conditional generation tasks. Our key idea is to concatenate condition and target frames along the temporal axis and insert intermediate buffer frames with progressively increasing noise levels. These buffer frames enable smooth transitions, aligning the fine-tuning process with the pretrained model's temporal dynamics. TIC-FT requires no architectural changes and achieves strong performance with as few as 10-30 training samples. We validate our method across a range of tasks, including image-to-video and video-to-video generation, using large-scale base models such as CogVideoX-5B and Wan-14B. Extensive experiments show that TIC-FT outperforms existing baselines in both condition fidelity and visual quality, while remaining highly efficient in both training and inference. For additional results, visit https://kinam0252.github.io/TIC-FT/

https://huggingface.co/discussions/paper/683e7cc1402acb186580d663