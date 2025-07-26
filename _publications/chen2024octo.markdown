---
layout: publication
title: 'Octo-planner: On-device Language Model For Planner-action Agents'
authors: Wei Chen, Zhiyuan Li, Zhen Guo, Yikang Shen
conference: No Venue
year: 2024
bibkey: chen2024octo
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.18082'}]
tags: ["Agentic", "Efficiency", "Model Architecture", "Tools"]
short_authors: Chen et al.
---
AI agents have become increasingly significant in various domains, enabling autonomous decision-making and problem-solving. To function effectively, these agents require a planning process that determines the best course of action and then executes the planned actions. In this paper, we present an efficient on-device Planner-Action framework that separates planning and action execution into two distinct components: a planner agent based on Phi-3 Mini, a 3.8 billion parameter LLM optimized for edge devices, and an action agent using the Octopus model for function execution. The planner agent first responds to user queries by decomposing tasks into a sequence of sub-steps, which are then executed by the action agent. To optimize performance on resource-constrained devices, we employ model fine-tuning instead of in-context learning, reducing computational costs and energy consumption while improving response times. Our approach involves using GPT-4 to generate diverse planning queries and responses based on available functions, with subsequent validations to ensure data quality. We fine-tune the Phi-3 Mini model on this curated dataset, achieving a 97% success rate in our in-domain test environment. To address multi-domain planning challenges, we developed a multi-LoRA training method that merges weights from LoRAs trained on distinct function subsets. This approach enables flexible handling of complex, multi-domain queries while maintaining computational efficiency on resource-constrained devices. To support further research, we have open-sourced our model weights at https://huggingface.co/NexaAIDev/octopus-planning. For the demo, please refer to https://www.nexa4ai.com/octo-planner.

https://huggingface.co/discussions/paper/667cbb5202ffd4993e26126b