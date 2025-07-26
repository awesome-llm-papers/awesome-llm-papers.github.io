---
layout: publication
title: 'Transformer^2: Self-adaptive Llms'
authors: Qi Sun, Edoardo Cetin, Yujin Tang
conference: No Venue
year: 2025
bibkey: sun2025transformer
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.06252'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Qi Sun, Edoardo Cetin, Yujin Tang
---
Self-adaptive large language models (LLMs) aim to solve the challenges posed by traditional fine-tuning methods, which are often computationally intensive and static in their ability to handle diverse tasks. We introduce \implname, a novel self-adaptation framework that adapts LLMs for unseen tasks in real-time by selectively adjusting only the singular components of their weight matrices. During inference, \implname employs a two-pass mechanism: first, a dispatch system identifies the task properties, and then task-specific "expert" vectors, trained using reinforcement learning, are dynamically mixed to obtain targeted behavior for the incoming prompt. Our method outperforms ubiquitous approaches such as LoRA, with fewer parameters and greater efficiency. \implname demonstrates versatility across different LLM architectures and modalities, including vision-language tasks. \implname represents a significant leap forward, offering a scalable, efficient solution for enhancing the adaptability and task-specific performance of LLMs, paving the way for truly dynamic, self-organizing AI systems.

https://huggingface.co/discussions/paper/6785e78b117627fe71200618