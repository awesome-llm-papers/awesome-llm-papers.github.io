---
layout: publication
title: Visual Cues Enhance Predictive Turn-taking For Two-party Human Interaction
authors: Russell Sam O'connor, Harte Naomi
conference: Proceedings of the 2015 ACM on International Conference on Multimodal
  Interaction
year: 2025
bibkey: russell2025visual
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.21043'}]
tags: [Multimodal Models, Reinforcement Learning, Training Techniques]
---
Turn-taking is richly multimodal. Predictive turn-taking models (PTTMs) facilitate naturalistic human-robot interaction, yet most rely solely on speech. We introduce MM-VAP, a multimodal PTTM which combines speech with visual cues including facial expression, head pose and gaze. We find that it outperforms the state-of-the-art audio-only in videoconferencing interactions (84% vs. 79% hold/shift prediction accuracy). Unlike prior work which aggregates all holds and shifts, we group by duration of silence between turns. This reveals that through the inclusion of visual features, MM-VAP outperforms a state-of-the-art audio-only turn-taking model across all durations of speaker transitions. We conduct a detailed ablation study, which reveals that facial expression features contribute the most to model performance. Thus, our working hypothesis is that when interlocutors can see one another, visual cues are vital for turn-taking and must therefore be included for accurate turn-taking prediction. We additionally validate the suitability of automatic speech alignment for PTTM training using telephone speech. This work represents the first comprehensive analysis of multimodal PTTMs. We discuss implications for future work and make all code publicly available.