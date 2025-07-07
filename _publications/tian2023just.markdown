---
layout: publication
title: 'Just Ask For Calibration: Strategies For Eliciting Calibrated Confidence Scores
  From Language Models Fine-tuned With Human Feedback'
authors: Katherine Tian et al.
conference: Arxiv
year: 2023
citations: 24
bibkey: tian2023just
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.14975'}]
tags: [GPT, Training Techniques, Pre-Training, Reinforcement Learning, Agentic, Model
    Architecture]
---
A trustworthy real-world prediction system should produce well-calibrated
confidence scores; that is, its confidence in an answer should be indicative of
the likelihood that the answer is correct, enabling deferral to an expert in
cases of low-confidence predictions. Recent studies have shown that
unsupervised pre-training produces large language models (LMs) whose
conditional probabilities are remarkably well-calibrated. However, the most
widely-used LMs are fine-tuned with reinforcement learning from human feedback
(RLHF-LMs), and some studies have suggested that RLHF-LMs produce conditional
probabilities that are very poorly calibrated. In light of this perceived
weakness, we conduct a broad evaluation of methods for extracting confidence
scores from RLHF-LMs. For RLHF-LMs such as ChatGPT, GPT-4, and Claude, we find
that verbalized confidences emitted as output tokens are typically
better-calibrated than the model's conditional probabilities on the TriviaQA,
SciQ, and TruthfulQA benchmarks, often reducing the expected calibration error
by a relative 50%.