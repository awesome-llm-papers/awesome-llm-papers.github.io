---
layout: publication
title: Do Large Language Models Latently Perform Multi-hop Reasoning?
authors: Sohee Yang, Elena Gribovskaya, Nora Kassner, Mor Geva, Sebastian Riedel
conference: No Venue
year: 2024
bibkey: yang2024do
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2402.16837'}]
tags: ["Applications", "Prompting"]
short_authors: Yang et al.
---
We study whether Large Language Models (LLMs) latently perform multi-hop reasoning with complex prompts such as "The mother of the singer of 'Superstition' is". We look for evidence of a latent reasoning pathway where an LLM (1) latently identifies "the singer of 'Superstition'" as Stevie Wonder, the bridge entity, and (2) uses its knowledge of Stevie Wonder's mother to complete the prompt. We analyze these two hops individually and consider their co-occurrence as indicative of latent multi-hop reasoning. For the first hop, we test if changing the prompt to indirectly mention the bridge entity instead of any other entity increases the LLM's internal recall of the bridge entity. For the second hop, we test if increasing this recall causes the LLM to better utilize what it knows about the bridge entity. We find strong evidence of latent multi-hop reasoning for the prompts of certain relation types, with the reasoning pathway used in more than 80% of the prompts. However, the utilization is highly contextual, varying across different types of prompts. Also, on average, the evidence for the second hop and the full multi-hop traversal is rather moderate and only substantial for the first hop. Moreover, we find a clear scaling trend with increasing model size for the first hop of reasoning but not for the second hop. Our experimental findings suggest potential challenges and opportunities for future development and applications of LLMs.

https://huggingface.co/discussions/paper/65dd6d06f2687e07c2c5564c