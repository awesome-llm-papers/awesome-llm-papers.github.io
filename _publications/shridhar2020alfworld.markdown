---
layout: publication
title: 'Alfworld: Aligning Text And Embodied Environments For Interactive Learning'
authors: Shridhar et al.
conference: Arxiv
year: 2020
bibkey: shridhar2020alfworld
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.03768'}]
tags: [Training Techniques, Agentic, Evaluation, Efficiency And Optimization, Reinforcement
    Learning, Datasets]
---
Given a simple request like Put a washed apple in the kitchen fridge, humans
can reason in purely abstract terms by imagining action sequences and scoring
their likelihood of success, prototypicality, and efficiency, all without
moving a muscle. Once we see the kitchen in question, we can update our
abstract plans to fit the scene. Embodied agents require the same abilities,
but existing work does not yet provide the infrastructure necessary for both
reasoning abstractly and executing concretely. We address this limitation by
introducing ALFWorld, a simulator that enables agents to learn abstract, text
based policies in TextWorld (C\^ot\'e et al., 2018) and then execute goals from
the ALFRED benchmark (Shridhar et al., 2020) in a rich visual environment.
ALFWorld enables the creation of a new BUTLER agent whose abstract knowledge,
learned in TextWorld, corresponds directly to concrete, visually grounded
actions. In turn, as we demonstrate empirically, this fosters better agent
generalization than training only in the visually grounded environment.
BUTLER's simple, modular design factors the problem to allow researchers to
focus on models for improving every piece of the pipeline (language
understanding, planning, navigation, and visual scene understanding).