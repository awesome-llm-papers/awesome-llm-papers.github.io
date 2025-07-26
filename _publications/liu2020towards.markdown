---
layout: publication
title: Towards Conversational Recommendation Over Multi-type Dialogs
authors: Zeming Liu, Haifeng Wang, Zheng-yu Niu, Hua Wu, Wanxiang Che, Ting Liu
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: liu2020towards
citations: 143
additional_links: [{name: Code, url: 'https://github.com/PaddlePaddle/models/tree/develop/PaddleNLP/Research/ACL2020-DuRecDial'},
  {name: Paper, url: 'https://arxiv.org/abs/2005.03954'}]
tags: ["Has Code"]
short_authors: Liu et al.
---
We propose a new task of conversational recommendation over multi-type
dialogs, where the bots can proactively and naturally lead a conversation from
a non-recommendation dialog (e.g., QA) to a recommendation dialog, taking into
account user's interests and feedback. To facilitate the study of this task, we
create a human-to-human Chinese dialog dataset *DuRecDial* (about 10k
dialogs, 156k utterances), which contains multiple sequential dialogs for every
pair of a recommendation seeker (user) and a recommender (bot). In each dialog,
the recommender proactively leads a multi-type dialog to approach
recommendation targets and then makes multiple recommendations with rich
interaction behavior. This dataset allows us to systematically investigate
different parts of the overall problem, e.g., how to naturally lead a dialog,
how to interact with users for recommendation. Finally we establish baseline
results on DuRecDial for future studies. Dataset and codes are publicly
available at
https://github.com/PaddlePaddle/models/tree/develop/PaddleNLP/Research/ACL2020-DuRecDial.