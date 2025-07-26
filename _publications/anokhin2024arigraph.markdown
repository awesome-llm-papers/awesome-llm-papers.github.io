---
layout: publication
title: 'Arigraph: Learning Knowledge Graph World Models With Episodic Memory For LLM
  Agents'
authors: Petr Anokhin, Nikita Semenov, Artyom Sorokin, Dmitry Evseev, Mikhail Burtsev,
  Evgeny Burnaev
conference: No Venue
year: 2024
bibkey: anokhin2024arigraph
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2407.04363'}]
tags: ["Agentic", "Model Architecture"]
short_authors: Anokhin et al.
---
Advancements in generative AI have broadened the potential applications of Large Language Models (LLMs) in the development of autonomous agents. Achieving true autonomy requires accumulating and updating knowledge gained from interactions with the environment and effectively utilizing it. Current LLM-based approaches leverage past experiences using a full history of observations, summarization or retrieval augmentation. However, these unstructured memory representations do not facilitate the reasoning and planning essential for complex decision-making. In our study, we introduce AriGraph, a novel method wherein the agent constructs a memory graph that integrates semantic and episodic memories while exploring the environment. This graph structure facilitates efficient associative retrieval of interconnected concepts, relevant to the agent's current state and goals, thus serving as an effective environmental model that enhances the agent's exploratory and planning capabilities. We demonstrate that our Ariadne LLM agent, equipped with this proposed memory architecture augmented with planning and decision-making, effectively handles complex tasks on a zero-shot basis in the TextWorld environment. Our approach markedly outperforms established methods such as full-history, summarization, and Retrieval-Augmented Generation in various tasks, including the cooking challenge from the First TextWorld Problems competition and novel tasks like house cleaning and puzzle Treasure Hunting.

https://huggingface.co/discussions/paper/668b8e256ce40bc8352c5230