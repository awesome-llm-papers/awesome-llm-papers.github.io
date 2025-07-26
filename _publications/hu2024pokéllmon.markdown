---
layout: publication
title: "Pok\xE9llmon: A Human-parity Agent For Pok\xE9mon Battles With Large Language\
  \ Models"
authors: Sihao Hu, Tiansheng Huang, Ling Liu
conference: No Venue
year: 2024
bibkey: "hu2024pok\xE9llmon"
additional_links: [{name: Code, url: 'https://github.com/git-disl/PokeLLMon'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2402.01118'}]
tags: ["Agentic", "Reinforcement Learning"]
short_authors: Sihao Hu, Tiansheng Huang, Ling Liu
---
We introduce Pok\'eLLMon, the first LLM-embodied agent that achieves human-parity performance in tactical battle games, as demonstrated in Pok\'emon battles. The design of Pok\'eLLMon incorporates three key strategies: (i) In-context reinforcement learning that instantly consumes text-based feedback derived from battles to iteratively refine the policy; (ii) Knowledge-augmented generation that retrieves external knowledge to counteract hallucination and enables the agent to act timely and properly; (iii) Consistent action generation to mitigate the panic switching phenomenon when the agent faces a powerful opponent and wants to elude the battle. We show that online battles against human demonstrates Pok\'eLLMon's human-like battle strategies and just-in-time decision making, achieving 49% of win rate in the Ladder competitions and 56% of win rate in the invited battles. Our implementation and playable battle logs are available at: https://github.com/git-disl/PokeLLMon.

https://huggingface.co/discussions/paper/65c04cc127a5fdca81ab6f2b