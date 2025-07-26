---
layout: publication
title: 'Octopus V4: Graph Of Language Models'
authors: Wei Chen, Zhiyuan Li
conference: No Venue
year: 2024
bibkey: chen2024octopus
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.19296'}]
tags: ["Model Architecture"]
short_authors: Wei Chen, Zhiyuan Li
---
Language models have been effective in a wide range of applications, yet the most sophisticated models are often proprietary. For example, GPT-4 by OpenAI and various models by Anthropic are expensive and consume substantial energy. In contrast, the open-source community has produced competitive models, like Llama3. Furthermore, niche-specific smaller language models, such as those tailored for legal, medical or financial tasks, have outperformed their proprietary counterparts. This paper introduces a novel approach that employs functional tokens to integrate multiple open-source models, each optimized for particular tasks. Our newly developed Octopus v4 model leverages functional tokens to intelligently direct user queries to the most appropriate vertical model and reformat the query to achieve the best performance. Octopus v4, an evolution of the Octopus v1, v2, and v3 models, excels in selection and parameter understanding and reformatting. Additionally, we explore the use of graph as a versatile data structure that effectively coordinates multiple open-source models by harnessing the capabilities of the Octopus model and functional tokens. Use our open-sourced GitHub (https://www.nexa4ai.com/) to try Octopus v4 models (https://huggingface.co/NexaAIDev/Octopus-v4), and contrite to a larger graph of language models. By activating models less than 10B parameters, we achieved SOTA MMLU score of 74.8 among the same level models.

https://huggingface.co/discussions/paper/663197a7a2354b0f50ae1627