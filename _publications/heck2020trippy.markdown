---
layout: publication
title: 'Trippy: A Triple Copy Strategy For Value Independent Neural Dialog State Tracking'
authors: "Michael Heck, Carel van Niekerk, Nurul Lubis, Christian Geishauser, Hsien-chin\
  \ Lin, Marco Moresi, Milica Ga\u0161i\u0107"
conference: Proceedings of the 21th Annual Meeting of the Special Interest Group on
  Discourse and Dialogue
year: 2020
bibkey: heck2020trippy
citations: 191
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.02877'}]
tags: ["Evaluation"]
short_authors: Heck et al.
---
Task-oriented dialog systems rely on dialog state tracking (DST) to monitor
the user's goal during the course of an interaction. Multi-domain and
open-vocabulary settings complicate the task considerably and demand scalable
solutions. In this paper we present a new approach to DST which makes use of
various copy mechanisms to fill slots with values. Our model has no need to
maintain a list of candidate values. Instead, all values are extracted from the
dialog context on-the-fly. A slot is filled by one of three copy mechanisms:
(1) Span prediction may extract values directly from the user input; (2) a
value may be copied from a system inform memory that keeps track of the
system's inform operations; (3) a value may be copied over from a different
slot that is already contained in the dialog state to resolve coreferences
within and across domains. Our approach combines the advantages of span-based
slot filling methods with memory methods to avoid the use of value picklists
altogether. We argue that our strategy simplifies the DST task while at the
same time achieving state of the art performance on various popular evaluation
sets including Multiwoz 2.1, where we achieve a joint goal accuracy beyond 55%.