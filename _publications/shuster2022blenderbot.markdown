---
layout: publication
title: 'Blenderbot 3: A Deployed Conversational Agent That Continually Learns To Responsibly
  Engage'
authors: Kurt Shuster, Jing Xu, Mojtaba Komeili, da Ju, Eric Michael Smith, Stephen
  Roller, Megan Ung, Moya Chen, Kushal Arora, Joshua Lane, Morteza Behrooz, William
  Ngan, Spencer Poff, Naman Goyal, Arthur Szlam, Y-lan Boureau, Melanie Kambadur,
  Jason Weston
conference: Arxiv
year: 2022
bibkey: shuster2022blenderbot
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.03188'}]
tags: ["Ethics & Fairness", "Model Architecture", "Training Techniques"]
short_authors: Shuster et al.
---
We present BlenderBot 3, a 175B parameter dialogue model capable of
open-domain conversation with access to the internet and a long-term memory,
and having been trained on a large number of user defined tasks. We release
both the model weights and code, and have also deployed the model on a public
web page to interact with organic users. This technical report describes how
the model was built (architecture, model and training scheme), and details of
its deployment, including safety mechanisms. Human evaluations show its
superiority to existing open-domain dialogue agents, including its predecessors
(Roller et al., 2021; Komeili et al., 2022). Finally, we detail our plan for
continual learning using the data collected from deployment, which will also be
publicly released. The goal of this research program is thus to enable the
community to study ever-improving responsible agents that learn through
interaction.