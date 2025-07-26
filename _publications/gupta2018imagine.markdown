---
layout: publication
title: Imagine This! Scripts To Compositions To Videos
authors: Tanmay Gupta, Dustin Schwenk, Ali Farhadi, Derek Hoiem, Aniruddha Kembhavi
conference: Lecture Notes in Computer Science
year: 2018
bibkey: gupta2018imagine
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.03608'}]
tags: ["Datasets", "Training Techniques"]
short_authors: Gupta et al.
---
Imagining a scene described in natural language with realistic layout and
appearance of entities is the ultimate test of spatial, visual, and semantic
world knowledge. Towards this goal, we present the Composition, Retrieval, and
Fusion Network (CRAFT), a model capable of learning this knowledge from
video-caption data and applying it while generating videos from novel captions.
CRAFT explicitly predicts a temporal-layout of mentioned entities (characters
and objects), retrieves spatio-temporal entity segments from a video database
and fuses them to generate scene videos. Our contributions include sequential
training of components of CRAFT while jointly modeling layout and appearances,
and losses that encourage learning compositional representations for retrieval.
We evaluate CRAFT on semantic fidelity to caption, composition consistency, and
visual quality. CRAFT outperforms direct pixel generation approaches and
generalizes well to unseen captions and to unseen video databases with no text
annotations. We demonstrate CRAFT on FLINTSTONES, a new richly annotated
video-caption dataset with over 25000 videos. For a glimpse of videos generated
by CRAFT, see https://youtu.be/688Vv86n0z8.