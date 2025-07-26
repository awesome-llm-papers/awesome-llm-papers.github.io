---
layout: publication
title: 'Text2motion: From Natural Language Instructions To Feasible Plans'
authors: Kevin Lin, Christopher Agia, Toki Migimatsu, Marco Pavone, Jeannette Bohg
conference: Autonomous Robots
year: 2023
bibkey: lin2023text2motion
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.12153'}]
tags: ["Tools"]
short_authors: Lin et al.
---
We propose Text2Motion, a language-based planning framework enabling robots
to solve sequential manipulation tasks that require long-horizon reasoning.
Given a natural language instruction, our framework constructs both a task- and
motion-level plan that is verified to reach inferred symbolic goals.
Text2Motion uses feasibility heuristics encoded in Q-functions of a library of
skills to guide task planning with Large Language Models. Whereas previous
language-based planners only consider the feasibility of individual skills,
Text2Motion actively resolves geometric dependencies spanning skill sequences
by performing geometric feasibility planning during its search. We evaluate our
method on a suite of problems that require long-horizon reasoning,
interpretation of abstract goals, and handling of partial affordance
perception. Our experiments show that Text2Motion can solve these challenging
problems with a success rate of 82%, while prior state-of-the-art
language-based planning methods only achieve 13%. Text2Motion thus provides
promising generalization characteristics to semantically diverse sequential
manipulation tasks with geometric dependencies between skills.