---
layout: publication
title: Multi-task Learning For Joint Language Understanding And Dialogue State Tracking
authors: Abhinav Rastogi, Raghav Gupta, Dilek Hakkani-tur
conference: Proceedings of the 19th Annual SIGdial Meeting on Discourse and Dialogue
year: 2018
bibkey: rastogi2018multi
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.05408'}]
tags: ["Training Techniques"]
short_authors: Abhinav Rastogi, Raghav Gupta, Dilek Hakkani-tur
---
This paper presents a novel approach for multi-task learning of language
understanding (LU) and dialogue state tracking (DST) in task-oriented dialogue
systems. Multi-task training enables the sharing of the neural network layers
responsible for encoding the user utterance for both LU and DST and improves
performance while reducing the number of network parameters. In our proposed
framework, DST operates on a set of candidate values for each slot that has
been mentioned so far. These candidate sets are generated using LU slot
annotations for the current user utterance, dialogue acts corresponding to the
preceding system utterance and the dialogue state estimated for the previous
turn, enabling DST to handle slots with a large or unbounded set of possible
values and deal with slot values not seen during training. Furthermore, to
bridge the gap between training and inference, we investigate the use of
scheduled sampling on LU output for the current user utterance as well as the
DST output for the preceding turn.