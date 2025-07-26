---
layout: publication
title: Aligning Large Multimodal Models With Factually Augmented RLHF
authors: Zhiqing Sun, Sheng Shen, Shengcao Cao, Haotian Liu, Chunyuan Li, Yikang Shen,
  Chuang Gan, Liang-yan Gui, Yu-xiong Wang, Yiming Yang, Kurt Keutzer, Trevor Darrell
conference: No Venue
year: 2023
bibkey: sun2023aligning
additional_links: [{name: Code, url: 'https://llava-rlhf.github.io'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/65137ef7b7994cff61e6392b'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2309.14525'}]
tags: ["Datasets", "Evaluation", "Has Code", "Model Architecture", "Reinforcement Learning", "Training Techniques"]
short_authors: Sun et al.
---
Large Multimodal Models (LMM) are built across modalities and the misalignment between two modalities can result in "hallucination", generating textual outputs that are not grounded by the multimodal information in context. To address the multimodal misalignment issue, we adapt the Reinforcement Learning from Human Feedback (RLHF) from the text domain to the task of vision-language alignment, where human annotators are asked to compare two responses and pinpoint the more hallucinated one, and the vision-language model is trained to maximize the simulated human rewards. We propose a new alignment algorithm called Factually Augmented RLHF that augments the reward model with additional factual information such as image captions and ground-truth multi-choice options, which alleviates the reward hacking phenomenon in RLHF and further improves the performance. We also enhance the GPT-4-generated training data (for vision instruction tuning) with previously available human-written image-text pairs to improve the general capabilities of our model. To evaluate the proposed approach in real-world scenarios, we develop a new evaluation benchmark MMHAL-BENCH with a special focus on penalizing hallucinations. As the first LMM trained with RLHF, our approach achieves remarkable improvement on the LLaVA-Bench dataset with the 94% performance level of the text-only GPT-4 (while previous best methods can only achieve the 87% level), and an improvement by 60% on MMHAL-BENCH over other baselines. We opensource our code, model, data at https://llava-rlhf.github.io.

https://huggingface.co/discussions/paper/65137ef7b7994cff61e6392b