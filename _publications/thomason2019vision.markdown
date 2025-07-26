---
layout: publication
title: Vision-and-dialog Navigation
authors: Jesse Thomason, Michael Murray, Maya Cakmak, Luke Zettlemoyer
conference: Arxiv
year: 2019
bibkey: thomason2019vision
citations: 127
additional_links: [{name: Code, url: 'https://cvdn.dev/'}, {name: Paper, url: 'https://arxiv.org/abs/1907.04957'}]
tags: ["Agentic", "Datasets"]
short_authors: Thomason et al.
---
Robots navigating in human environments should use language to ask for
assistance and be able to understand human responses. To study this challenge,
we introduce Cooperative Vision-and-Dialog Navigation, a dataset of over 2k
embodied, human-human dialogs situated in simulated, photorealistic home
environments. The Navigator asks questions to their partner, the Oracle, who
has privileged access to the best next steps the Navigator should take
according to a shortest path planner. To train agents that search an
environment for a goal location, we define the Navigation from Dialog History
task. An agent, given a target object and a dialog history between humans
cooperating to find that object, must infer navigation actions towards the goal
in unexplored environments. We establish an initial, multi-modal
sequence-to-sequence model and demonstrate that looking farther back in the
dialog history improves performance. Sourcecode and a live interface demo can
be found at https://cvdn.dev/