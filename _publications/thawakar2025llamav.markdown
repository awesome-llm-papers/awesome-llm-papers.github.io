---
layout: publication
title: 'Llamav-o1: Rethinking Step-by-step Visual Reasoning In Llms'
authors: Omkar Thawakar, Dinura Dissanayake, Ketan More, Ritesh Thawkar, Ahmed Heakl,
  Noor Ahsan, Yuhao Li, Mohammed Zumri, Jean Lahoud, Rao Muhammad Anwer, Hisham Cholakkal,
  Ivan Laptev, Mubarak Shah, Fahad Shahbaz Khan, Salman Khan
conference: No Venue
year: 2025
bibkey: thawakar2025llamav
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6784817d956a6e0944954821'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2501.06186'}]
tags: ["Evaluation", "Prompting", "Tools", "Training Techniques"]
short_authors: Thawakar et al.
---
Reasoning is a fundamental capability for solving complex multi-step problems, particularly in visual contexts where sequential step-wise understanding is essential. Existing approaches lack a comprehensive framework for evaluating visual reasoning and do not emphasize step-wise problem-solving. To this end, we propose a comprehensive framework for advancing step-by-step visual reasoning in large language models (LMMs) through three key contributions. First, we introduce a visual reasoning benchmark specifically designed to evaluate multi-step reasoning tasks. The benchmark presents a diverse set of challenges with eight different categories ranging from complex visual perception to scientific reasoning with over 4k reasoning steps in total, enabling robust evaluation of LLMs' abilities to perform accurate and interpretable visual reasoning across multiple steps. Second, we propose a novel metric that assesses visual reasoning quality at the granularity of individual steps, emphasizing both correctness and logical coherence. The proposed metric offers deeper insights into reasoning performance compared to traditional end-task accuracy metrics. Third, we present a new multimodal visual reasoning model, named LlamaV-o1, trained using a multi-step curriculum learning approach, where tasks are progressively organized to facilitate incremental skill acquisition and problem-solving. The proposed LlamaV-o1 is designed for multi-step reasoning and learns step-by-step through a structured training paradigm. Extensive experiments show that our LlamaV-o1 outperforms existing open-source models and performs favorably against close-source proprietary models. Compared to the recent Llava-CoT, our LlamaV-o1 achieves an average score of 67.3 with an absolute gain of 3.8% across six benchmarks while being 5 times faster during inference scaling. Our benchmark, model, and code are publicly available.

https://huggingface.co/discussions/paper/6784817d956a6e0944954821