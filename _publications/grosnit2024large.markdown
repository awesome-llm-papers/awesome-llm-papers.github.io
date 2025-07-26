---
layout: publication
title: Large Language Models Orchestrating Structured Reasoning Achieve Kaggle Grandmaster
  Level
authors: Antoine Grosnit, Alexandre Maraval, James Doran, Giuseppe Paolo, Albert Thomas,
  Refinath Shahul Hameed Nabeezath Beevi, Jonas Gonzalez, Khyati Khandelwal, Ignacio
  Iacobacci, Abdelhakim Benechehab, Hamza Cherkaoui, Youssef Attia El-hili, Kun Shao,
  Jianye Hao, Jun Yao, Balazs Kegl, Haitham Bou-ammar, Jun Wang
conference: No Venue
year: 2024
bibkey: grosnit2024large
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2411.03562'}]
tags: ["Evaluation", "Tools"]
short_authors: Grosnit et al.
---
We introduce Agent K v1.0, an end-to-end autonomous data science agent designed to automate, optimise, and generalise across diverse data science tasks. Fully automated, Agent K v1.0 manages the entire data science life cycle by learning from experience. It leverages a highly flexible structured reasoning framework to enable it to dynamically process memory in a nested structure, effectively learning from accumulated experience stored to handle complex reasoning tasks. It optimises long- and short-term memory by selectively storing and retrieving key information, guiding future decisions based on environmental rewards. This iterative approach allows it to refine decisions without fine-tuning or backpropagation, achieving continuous improvement through experiential learning. We evaluate our agent's apabilities using Kaggle competitions as a case study. Following a fully automated protocol, Agent K v1.0 systematically addresses complex and multimodal data science tasks, employing Bayesian optimisation for hyperparameter tuning and feature engineering. Our new evaluation framework rigorously assesses Agent K v1.0's end-to-end capabilities to generate and send submissions starting from a Kaggle competition URL. Results demonstrate that Agent K v1.0 achieves a 92.5% success rate across tasks, spanning tabular, computer vision, NLP, and multimodal domains. When benchmarking against 5,856 human Kaggle competitors by calculating Elo-MMR scores for each, Agent K v1.0 ranks in the top 38%, demonstrating an overall skill level comparable to Expert-level users. Notably, its Elo-MMR score falls between the first and third quartiles of scores achieved by human Grandmasters. Furthermore, our results indicate that Agent K v1.0 has reached a performance level equivalent to Kaggle Grandmaster, with a record of 6 gold, 3 silver, and 7 bronze medals, as defined by Kaggle's progression system.

https://huggingface.co/discussions/paper/672c969216766a76a769a9f9