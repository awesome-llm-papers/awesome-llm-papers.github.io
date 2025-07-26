---
layout: publication
title: Controlling Personality-based Stylistic Variation With Neural Natural Language
  Generators
authors: Shereen Oraby, Lena Reed, Shubhangi Tandon, T. S. Sharath, Stephanie Lukin,
  Marilyn Walker
conference: Proceedings of the 19th Annual SIGdial Meeting on Discourse and Dialogue
year: 2018
bibkey: oraby2018controlling
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.08352'}]
tags: ["Applications", "Training Techniques"]
short_authors: Oraby et al.
---
Natural language generators for task-oriented dialogue must effectively
realize system dialogue actions and their associated semantics. In many
applications, it is also desirable for generators to control the style of an
utterance. To date, work on task-oriented neural generation has primarily
focused on semantic fidelity rather than achieving stylistic goals, while work
on style has been done in contexts where it is difficult to measure content
preservation. Here we present three different sequence-to-sequence models and
carefully test how well they disentangle content and style. We use a
statistical generator, Personage, to synthesize a new corpus of over 88,000
restaurant domain utterances whose style varies according to models of
personality, giving us total control over both the semantic content and the
stylistic variation in the training data. We then vary the amount of explicit
stylistic supervision given to the three models. We show that our most explicit
model can simultaneously achieve high fidelity to both semantic and stylistic
goals: this model adds a context vector of 36 stylistic parameters as input to
the hidden state of the encoder at each time step, showing the benefits of
explicit stylistic supervision, even when the amount of training data is large.