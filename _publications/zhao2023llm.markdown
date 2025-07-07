---
layout: publication
title: 'Expel: LLM Agents Are Experiential Learners'
authors: Andrew Zhao et al.
conference: Arxiv
year: 2023
citations: 31
bibkey: zhao2023llm
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2308.10144v2'}]
tags: [Training Techniques, GPT, Merging, RAG, Fine-Tuning, Tools, Reinforcement Learning,
  Agentic, Model Architecture]
---
The recent surge in research interest in applying large language models
(LLMs) to decision-making tasks has flourished by leveraging the extensive
world knowledge embedded in LLMs. While there is a growing demand to tailor
LLMs for custom decision-making tasks, finetuning them for specific tasks is
resource-intensive and may diminish the model's generalization capabilities.
Moreover, state-of-the-art language models like GPT-4 and Claude are primarily
accessible through API calls, with their parametric weights remaining
proprietary and unavailable to the public. This scenario emphasizes the growing
need for new methodologies that allow learning from agent experiences without
requiring parametric updates. To address these problems, we introduce the
Experiential Learning (ExpeL) agent. Our agent autonomously gathers experiences
and extracts knowledge using natural language from a collection of training
tasks. At inference, the agent recalls its extracted insights and past
experiences to make informed decisions. Our empirical results highlight the
robust learning efficacy of the ExpeL agent, indicating a consistent
enhancement in its performance as it accumulates experiences. We further
explore the emerging capabilities and transfer learning potential of the ExpeL
agent through qualitative observations and additional experiments.