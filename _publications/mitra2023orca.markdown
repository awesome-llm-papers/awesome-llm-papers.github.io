---
layout: publication
title: 'Orca 2: Teaching Small Language Models How To Reason'
authors: Arindam Mitra, Luciano del Corro, Shweti Mahajan, Andres Codas, Clarisse
  Simoes, Sahaj Agrawal, Xuxi Chen, Anastasia Razdaibiedina, Erik Jones, Kriti Aggarwal,
  Hamid Palangi, Guoqing Zheng, Corby Rosset, Hamed Khanpour, Ahmed Awadallah
conference: No Venue
year: 2023
bibkey: mitra2023orca
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2311.11045'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: Mitra et al.
---
Orca 1 learns from rich signals, such as explanation traces, allowing it to outperform conventional instruction-tuned models on benchmarks like BigBench Hard and AGIEval. In Orca 2, we continue exploring how improved training signals can enhance smaller LMs' reasoning abilities. Research on training small LMs has often relied on imitation learning to replicate the output of more capable models. We contend that excessive emphasis on imitation may restrict the potential of smaller models. We seek to teach small LMs to employ different solution strategies for different tasks, potentially different from the one used by the larger model. For example, while larger models might provide a direct answer to a complex task, smaller models may not have the same capacity. In Orca 2, we teach the model various reasoning techniques (step-by-step, recall then generate, recall-reason-generate, direct answer, etc.). More crucially, we aim to help the model learn to determine the most effective solution strategy for each task. We evaluate Orca 2 using a comprehensive set of 15 diverse benchmarks (corresponding to approximately 100 tasks and over 36,000 unique prompts). Orca 2 significantly surpasses models of similar size and attains performance levels similar or better to those of models 5-10x larger, as assessed on complex tasks that test advanced reasoning abilities in zero-shot settings. We open-source Orca 2 to encourage further research on the development, evaluation, and alignment of smaller LMs.

https://huggingface.co/discussions/paper/655c0b866d02c2b1a92d1b2a