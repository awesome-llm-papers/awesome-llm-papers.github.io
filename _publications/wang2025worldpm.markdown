---
layout: publication
title: 'Worldpm: Scaling Human Preference Modeling'
authors: Binghai Wang, Runji Lin, Keming Lu, Le Yu, Zhenru Zhang, Fei Huang, Chujie
  Zheng, Kai Dang, Yang Fan, Xingzhang Ren, An Yang, Binyuan Hui, Dayiheng Liu, Tao
  Gui, Qi Zhang, Xuanjing Huang, Yu-gang Jiang, Bowen Yu, Jingren Zhou, Junyang Lin
conference: No Venue
year: 2025
bibkey: wang2025worldpm
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.10527'}]
tags: ["Datasets", "Efficiency", "Emergent Abilities", "Evaluation", "Fine-Tuning", "Reinforcement Learning", "Security", "Training Techniques"]
short_authors: Wang et al.
---
Motivated by scaling laws in language modeling that demonstrate how test loss scales as a power law with model and dataset sizes, we find that similar laws exist in preference modeling. We propose World Preference Modeling$ (WorldPM) to emphasize this scaling potential, where World Preference embodies a unified representation of human preferences. In this paper, we collect preference data from public forums covering diverse user communities, and conduct extensive training using 15M-scale data across models ranging from 1.5B to 72B parameters. We observe distinct patterns across different evaluation metrics: (1) Adversarial metrics (ability to identify deceptive features) consistently scale up with increased training data and base model size; (2) Objective metrics (objective knowledge with well-defined answers) show emergent behavior in larger language models, highlighting WorldPM's scalability potential; (3) Subjective metrics (subjective preferences from a limited number of humans or AI) do not demonstrate scaling trends. Further experiments validate the effectiveness of WorldPM as a foundation for preference fine-tuning. Through evaluations on 7 benchmarks with 20 subtasks, we find that WorldPM broadly improves the generalization performance across human preference datasets of varying sizes (7K, 100K and 800K samples), with performance gains exceeding 5% on many key subtasks. Integrating WorldPM into our internal RLHF pipeline, we observe significant improvements on both in-house and public evaluation sets, with notable gains of 4% to 8% in our in-house evaluations.

https://huggingface.co/discussions/paper/682699dd19c4a596dbcea604