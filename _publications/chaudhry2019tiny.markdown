---
layout: publication
title: On Tiny Episodic Memories In Continual Learning
authors: Arslan Chaudhry, Marcus Rohrbach, Mohamed Elhoseiny, Thalaiyasingam Ajanthan,
  Puneet K. Dokania, Philip H. S. Torr, Marc'aurelio Ranzato
conference: Arxiv
year: 2019
bibkey: chaudhry2019tiny
citations: 331
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.10486'}]
tags: ["Training Techniques"]
short_authors: Chaudhry et al.
---
In continual learning (CL), an agent learns from a stream of tasks leveraging
prior experience to transfer knowledge to future tasks. It is an ideal
framework to decrease the amount of supervision in the existing learning
algorithms. But for a successful knowledge transfer, the learner needs to
remember how to perform previous tasks. One way to endow the learner the
ability to perform tasks seen in the past is to store a small memory, dubbed
episodic memory, that stores few examples from previous tasks and then to
replay these examples when training for future tasks. In this work, we
empirically analyze the effectiveness of a very small episodic memory in a CL
setup where each training example is only seen once. Surprisingly, across four
rather different supervised learning benchmarks adapted to CL, a very simple
baseline, that jointly trains on both examples from the current task as well as
examples stored in the episodic memory, significantly outperforms specifically
designed CL approaches with and without episodic memory. Interestingly, we find
that repetitive training on even tiny memories of past tasks does not harm
generalization, on the contrary, it improves it, with gains between 7% and
17% when the memory is populated with a single example per class.