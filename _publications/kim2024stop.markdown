---
layout: publication
title: Stop Playing The Guessing Game! Target-free User Simulation For Evaluating
  Conversational Recommender Systems
authors: Kim et al.
conference: Proceedings of the 26th ACM SIGKDD International Conference on Knowledge
  Discovery &amp; Data Mining
year: 2024
bibkey: kim2024stop
citations: 67
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.16160'}]
tags: [Agentic, Evaluation, RSS, Ethics And Bias, Reinforcement Learning, Fine Tuning,
  KDD]
---
Recent approaches in Conversational Recommender Systems (CRSs) have tried to
simulate real-world users engaging in conversations with CRSs to create more
realistic testing environments that reflect the complexity of human-agent
dialogue. Despite the significant advancements, reliably evaluating the
capability of CRSs to elicit user preferences still faces a significant
challenge. Existing evaluation metrics often rely on target-biased user
simulators that assume users have predefined preferences, leading to
interactions that devolve into simplistic guessing game. These simulators
typically guide the CRS toward specific target items based on fixed attributes,
limiting the dynamic exploration of user preferences and struggling to capture
the evolving nature of real-user interactions. Additionally, current evaluation
metrics are predominantly focused on single-turn recall of target items,
neglecting the intermediate processes of preference elicitation. To address
this, we introduce PEPPER, a novel CRS evaluation protocol with target-free
user simulators constructed from real-user interaction histories and reviews.
PEPPER enables realistic user-CRS dialogues without falling into simplistic
guessing games, allowing users to gradually discover their preferences through
enriched interactions, thereby providing a more accurate and reliable
assessment of the CRS's ability to elicit personal preferences. Furthermore,
PEPPER presents detailed measures for comprehensively evaluating the preference
elicitation capabilities of CRSs, encompassing both quantitative and
qualitative measures that capture four distinct aspects of the preference
elicitation process. Through extensive experiments, we demonstrate the validity
of PEPPER as a simulation environment and conduct a thorough analysis of how
effectively existing CRSs perform in preference elicitation and recommendation.