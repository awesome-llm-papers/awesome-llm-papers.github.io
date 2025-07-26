---
layout: publication
title: Proactive Human-machine Conversation With Explicit Conversation Goals
authors: Wenquan Wu, Zhen Guo, Xiangyang Zhou, Hua Wu, Xiyuan Zhang, Rongzhong Lian,
  Haifeng Wang
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: wu2019proactive
citations: 150
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.05572'}]
tags: ["Agentic"]
short_authors: Wu et al.
---
Though great progress has been made for human-machine conversation, current
dialogue system is still in its infancy: it usually converses passively and
utters words more as a matter of response, rather than on its own initiatives.
In this paper, we take a radical step towards building a human-like
conversational agent: endowing it with the ability of proactively leading the
conversation (introducing a new topic or maintaining the current topic). To
facilitate the development of such conversation systems, we create a new
dataset named DuConv where one acts as a conversation leader and the other acts
as the follower. The leader is provided with a knowledge graph and asked to
sequentially change the discussion topics, following the given conversation
goal, and meanwhile keep the dialogue as natural and engaging as possible.
DuConv enables a very challenging task as the model needs to both understand
dialogue and plan over the given knowledge graph. We establish baseline results
on this dataset (about 270K utterances and 30k dialogues) using several
state-of-the-art models. Experimental results show that dialogue models that
plan over the knowledge graph can make full use of related knowledge to
generate more diverse multi-turn conversations. The baseline systems along with
the dataset are publicly available