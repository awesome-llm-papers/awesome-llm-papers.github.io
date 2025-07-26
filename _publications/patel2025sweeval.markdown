---
layout: publication
title: 'Sweeval: Do Llms Really Swear? A Safety Benchmark For Testing Limits For Enterprise
  Use'
authors: Hitesh Laxmichand Patel, Amit Agarwal, Arion Das, Bhargava Kumar, Srikant
  Panda, Priyaranjan Pattnayak, Taki Hasan Rafi, Tejaswini Kumar, Dong-kyu Chae
conference: No Venue
year: 2025
bibkey: patel2025sweeval
additional_links: [{name: Code, url: 'https://github.com/amitbcp/multilingual_profanity'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/68349acf56ca97d1b2f1ebba'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2505.17332'}]
tags: ["Applications", "Ethics & Fairness", "Evaluation"]
short_authors: Patel et al.
---
Enterprise customers are increasingly adopting Large Language Models (LLMs) for critical communication tasks, such as drafting emails, crafting sales pitches, and composing casual messages. Deploying such models across different regions requires them to understand diverse cultural and linguistic contexts and generate safe and respectful responses. For enterprise applications, it is crucial to mitigate reputational risks, maintain trust, and ensure compliance by effectively identifying and handling unsafe or offensive language. To address this, we introduce SweEval, a benchmark simulating real-world scenarios with variations in tone (positive or negative) and context (formal or informal). The prompts explicitly instruct the model to include specific swear words while completing the task. This benchmark evaluates whether LLMs comply with or resist such inappropriate instructions and assesses their alignment with ethical frameworks, cultural nuances, and language comprehension capabilities. In order to advance research in building ethically aligned AI systems for enterprise use and beyond, we release the dataset and code: https://github.com/amitbcp/multilingual_profanity.

https://huggingface.co/discussions/paper/68349acf56ca97d1b2f1ebba