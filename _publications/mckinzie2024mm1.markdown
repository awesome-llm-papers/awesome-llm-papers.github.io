---
layout: publication
title: 'MM1: Methods, Analysis & Insights From Multimodal LLM Pre-training'
authors: "Brandon Mckinzie, Zhe Gan, Jean-philippe Fauconnier, Sam Dodge, Bowen Zhang,\
  \ Philipp Dufter, Dhruti Shah, Xianzhi Du, Futang Peng, Floris Weers, Anton Belyi,\
  \ Haotian Zhang, Karanjeet Singh, Doug Kang, Hongyu H\xE8, Max Schwarzer, Tom Gunter,\
  \ Xiang Kong, Aonan Zhang, Jianyu Wang, Chong Wang, Nan Du, Tao Lei, Sam Wiseman,\
  \ Guoli Yin, Mark Lee, Zirui Wang, Ruoming Pang, Peter Grasch, Alexander Toshev,\
  \ Yinfei Yang"
conference: No Venue
year: 2024
bibkey: mckinzie2024mm1
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/65f3b1fd7c44e9e26df103c4'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2403.09611'}]
tags: ["Evaluation", "Few-Shot", "Fine-Tuning", "In Context Learning", "Model Architecture", "Prompting", "Training Techniques"]
short_authors: Mckinzie et al.
---
In this work, we discuss building performant Multimodal Large Language Models (MLLMs). In particular, we study the importance of various architecture components and data choices. Through careful and comprehensive ablations of the image encoder, the vision language connector, and various pre-training data choices, we identified several crucial design lessons. For example, we demonstrate that for large-scale multimodal pre-training using a careful mix of image-caption, interleaved image-text, and text-only data is crucial for achieving state-of-the-art (SOTA) few-shot results across multiple benchmarks, compared to other published pre-training results. Further, we show that the image encoder together with image resolution and the image token count has substantial impact, while the vision-language connector design is of comparatively negligible importance. By scaling up the presented recipe, we build MM1, a family of multimodal models up to 30B parameters, consisting of both dense models and mixture-of-experts (MoE) variants, that are SOTA in pre-training metrics and achieve competitive performance after supervised fine-tuning on a range of established multimodal benchmarks. Thanks to large-scale pre-training, MM1 enjoys appealing properties such as enhanced in-context learning, and multi-image reasoning, enabling few-shot chain-of-thought prompting.

https://huggingface.co/discussions/paper/65f3b1fd7c44e9e26df103c4