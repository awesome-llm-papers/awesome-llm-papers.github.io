---
layout: publication
title: 'MM1.5: Methods, Analysis & Insights From Multimodal LLM Fine-tuning'
authors: Haotian Zhang, Mingfei Gao, Zhe Gan, Philipp Dufter, Nina Wenzel, Forrest
  Huang, Dhruti Shah, Xianzhi Du, Bowen Zhang, Yanghao Li, Sam Dodge, Keen You, Zhen
  Yang, Aleksei Timofeev, Mingze Xu, Hong-you Chen, Jean-philippe Fauconnier, Zhengfeng
  Lai, Haoxuan You, Zirui Wang, Afshin Dehghan, Peter Grasch, Yinfei Yang
conference: No Venue
year: 2024
bibkey: zhang2024mm1
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2409.20566'}]
tags: ["Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Zhang et al.
---
We present MM1.5, a new family of multimodal large language models (MLLMs) designed to enhance capabilities in text-rich image understanding, visual referring and grounding, and multi-image reasoning. Building upon the MM1 architecture, MM1.5 adopts a data-centric approach to model training, systematically exploring the impact of diverse data mixtures across the entire model training lifecycle. This includes high-quality OCR data and synthetic captions for continual pre-training, as well as an optimized visual instruction-tuning data mixture for supervised fine-tuning. Our models range from 1B to 30B parameters, encompassing both dense and mixture-of-experts (MoE) variants, and demonstrate that careful data curation and training strategies can yield strong performance even at small scales (1B and 3B). Additionally, we introduce two specialized variants: MM1.5-Video, designed for video understanding, and MM1.5-UI, tailored for mobile UI understanding. Through extensive empirical studies and ablations, we provide detailed insights into the training processes and decisions that inform our final designs, offering valuable guidance for future research in MLLM development.

https://huggingface.co/discussions/paper/66fb8ee60c0759cfa092113e