---
layout: publication
title: Improving One-stage Visual Grounding By Recursive Sub-query Construction
authors: Yang et al.
conference: Lecture Notes in Computer Science
year: 2020
bibkey: yang2020improving
citations: 185
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.01059'}]
tags: [Model Architecture, Tools, Reinforcement Learning, BERT]
---
We improve one-stage visual grounding by addressing current limitations on
grounding long and complex queries. Existing one-stage methods encode the
entire language query as a single sentence embedding vector, e.g., taking the
embedding from BERT or the hidden state from LSTM. This single vector
representation is prone to overlooking the detailed descriptions in the query.
To address this query modeling deficiency, we propose a recursive sub-query
construction framework, which reasons between image and query for multiple
rounds and reduces the referring ambiguity step by step. We show our new
one-stage method obtains 5.0%, 4.5%, 7.5%, 12.8% absolute improvements over the
state-of-the-art one-stage baseline on ReferItGame, RefCOCO, RefCOCO+, and
RefCOCOg, respectively. In particular, superior performances on longer and more
complex queries validates the effectiveness of our query modeling.