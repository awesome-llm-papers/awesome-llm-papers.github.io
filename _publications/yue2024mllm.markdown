---
layout: publication
title: 'MLLM As Retriever: Interactively Learning Multimodal Retrieval For Embodied
  Agents'
authors: "Junpeng Yue, Xinru Xu, B\xF6rje F. Karlsson, Zongqing Lu"
conference: No Venue
year: 2024
bibkey: yue2024mllm
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6708926cd08850e483b2e59a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2410.03450'}]
tags: ["Retrieval Systems"]
short_authors: Yue et al.
---
MLLM agents demonstrate potential for complex embodied tasks by retrieving multimodal task-relevant trajectory data. However, current retrieval methods primarily focus on surface-level similarities of textual or visual cues in trajectories, neglecting their effectiveness for the specific task at hand. To address this issue, we propose a novel method, MLLM as ReTriever (MART), which enhances the performance of embodied agents by utilizing interaction data to fine-tune an MLLM retriever based on preference learning, such that the retriever fully considers the effectiveness of trajectories and prioritize them for unseen tasks. We also introduce Trajectory Abstraction, a mechanism that leverages MLLMs' summarization capabilities to represent trajectories with fewer tokens while preserving key information, enabling agents to better comprehend milestones in the trajectory. Experimental results across various environments demonstrate our method significantly improves task success rates in unseen scenes compared to baseline methods. This work presents a new paradigm for multimodal retrieval in embodied agents, by fine-tuning a general-purpose MLLM as the retriever to assess trajectory effectiveness. All benchmark task sets and simulator code modifications for action and observation spaces will be released.

https://huggingface.co/discussions/paper/6708926cd08850e483b2e59a