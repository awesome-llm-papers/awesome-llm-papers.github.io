---
layout: publication
title: Hierarchical Context Enabled Recurrent Neural Network For Recommendation
authors: Kyungwoo Song, Mingi Ji, Sungrae Park, Il-chul Moon
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2019
bibkey: song2019hierarchical
citations: 242
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.12674'}]
tags: ["Llm For Code"]
short_authors: Song et al.
---
A long user history inevitably reflects the transitions of personal interests
over time. The analyses on the user history require the robust sequential model
to anticipate the transitions and the decays of user interests. The user
history is often modeled by various RNN structures, but the RNN structures in
the recommendation system still suffer from the long-term dependency and the
interest drifts. To resolve these challenges, we suggest HCRNN with three
hierarchical contexts of the global, the local, and the temporary interests.
This structure is designed to withhold the global long-term interest of users,
to reflect the local sub-sequence interests, and to attend the temporary
interests of each transition. Besides, we propose a hierarchical context-based
gate structure to incorporate our \textit\{interest drift assumption\}. As we
suggest a new RNN structure, we support HCRNN with a complementary
\textit\{bi-channel attention\} structure to utilize hierarchical context. We
experimented the suggested structure on the sequential recommendation tasks
with CiteULike, MovieLens, and LastFM, and our model showed the best
performances in the sequential recommendations.