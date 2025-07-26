---
layout: publication
title: Phi-4-reasoning Technical Report
authors: "Marah Abdin, Sahaj Agarwal, Ahmed Awadallah, Vidhisha Balachandran, Harkirat\
  \ Behl, Lingjiao Chen, Gustavo de Rosa, Suriya Gunasekar, Mojan Javaheripi, Neel\
  \ Joshi, Piero Kauffmann, Yash Lara, Caio C\xE9sar Teodoro Mendes, Arindam Mitra,\
  \ Besmira Nushi, Dimitris Papailiopoulos, Olli Saarikivi, Shital Shah, Vaishnavi\
  \ Shrivastava, Vibhav Vineet, Yue Wu, Safoora Yousefi, Guoqing Zheng"
conference: No Venue
year: 2025
bibkey: abdin2025phi
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6812d3c4e74b39182bd0dcd1'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2504.21318'}]
tags: ["Evaluation", "Fine-Tuning", "Reinforcement Learning", "Security", "Training Techniques"]
short_authors: Abdin et al.
---
We introduce Phi-4-reasoning, a 14-billion parameter reasoning model that achieves strong performance on complex reasoning tasks. Trained via supervised fine-tuning of Phi-4 on carefully curated set of "teachable" prompts-selected for the right level of complexity and diversity-and reasoning demonstrations generated using o3-mini, Phi-4-reasoning generates detailed reasoning chains that effectively leverage inference-time compute. We further develop Phi-4-reasoning-plus, a variant enhanced through a short phase of outcome-based reinforcement learning that offers higher performance by generating longer reasoning traces. Across a wide range of reasoning tasks, both models outperform significantly larger open-weight models such as DeepSeek-R1-Distill-Llama-70B model and approach the performance levels of full DeepSeek-R1 model. Our comprehensive evaluations span benchmarks in math and scientific reasoning, coding, algorithmic problem solving, planning, and spatial understanding. Interestingly, we observe a non-trivial transfer of improvements to general-purpose benchmarks as well. In this report, we provide insights into our training data, our training methodologies, and our evaluations. We show that the benefit of careful data curation for supervised fine-tuning (SFT) extends to reasoning language models, and can be further amplified by reinforcement learning (RL). Finally, our evaluation points to opportunities for improving how we assess the performance and robustness of reasoning models.

https://huggingface.co/discussions/paper/6812d3c4e74b39182bd0dcd1