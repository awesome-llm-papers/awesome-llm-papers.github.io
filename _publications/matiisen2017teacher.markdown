---
layout: publication
title: Teacher-student Curriculum Learning
authors: Tambet Matiisen, Avital Oliver, Taco Cohen, John Schulman
conference: IEEE Transactions on Neural Networks and Learning Systems
year: 2019
bibkey: matiisen2017teacher
citations: 238
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.00183'}]
tags: ["Training Techniques"]
short_authors: Matiisen et al.
---
We propose Teacher-Student Curriculum Learning (TSCL), a framework for
automatic curriculum learning, where the Student tries to learn a complex task
and the Teacher automatically chooses subtasks from a given set for the Student
to train on. We describe a family of Teacher algorithms that rely on the
intuition that the Student should practice more those tasks on which it makes
the fastest progress, i.e. where the slope of the learning curve is highest. In
addition, the Teacher algorithms address the problem of forgetting by also
choosing tasks where the Student's performance is getting worse. We demonstrate
that TSCL matches or surpasses the results of carefully hand-crafted curricula
in two tasks: addition of decimal numbers with LSTM and navigation in
Minecraft. Using our automatically generated curriculum enabled to solve a
Minecraft maze that could not be solved at all when training directly on
solving the maze, and the learning was an order of magnitude faster than
uniform sampling of subtasks.