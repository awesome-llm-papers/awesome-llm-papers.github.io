---
layout: publication
title: 'The AI Teacher Test: Measuring The Pedagogical Ability Of Blender And GPT-3
  In Educational Dialogues'
authors: "Ana\xEFs Tack, Chris Piech"
conference: Arxiv
year: 2022
citations: 29
bibkey: tack2022ai
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.07540'}]
tags: [Reinforcement Learning, Agentic, Model Architecture, GPT]
---
How can we test whether state-of-the-art generative models, such as Blender
and GPT-3, are good AI teachers, capable of replying to a student in an
educational dialogue? Designing an AI teacher test is challenging: although
evaluation methods are much-needed, there is no off-the-shelf solution to
measuring pedagogical ability. This paper reports on a first attempt at an AI
teacher test. We built a solution around the insight that you can run
conversational agents in parallel to human teachers in real-world dialogues,
simulate how different agents would respond to a student, and compare these
counterpart responses in terms of three abilities: speak like a teacher,
understand a student, help a student. Our method builds on the reliability of
comparative judgments in education and uses a probabilistic model and Bayesian
sampling to infer estimates of pedagogical ability. We find that, even though
conversational agents (Blender in particular) perform well on conversational
uptake, they are quantifiably worse than real teachers on several pedagogical
dimensions, especially with regard to helpfulness (Blender: \{\Delta\} ability =
-0.75; GPT-3: \{\Delta\} ability = -0.93).