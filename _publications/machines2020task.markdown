---
layout: publication
title: Task-oriented Dialogue As Dataflow Synthesis
authors: Semantic Machines, Jacob Andreas, John Bufe, David Burkett, Charles Chen,
  Josh Clausman, Jean Crawford, Kate Crim, Jordan Deloach, Leah Dorner, Jason Eisner,
  Hao Fang, Alan Guo, David Hall, Kristin Hayes, Kellie Hill, Diana Ho, Wendy Iwaszuk,
  Smriti Jha, Dan Klein, Jayant Krishnamurthy, Theo Lanman, Percy Liang, Christopher
  H Lin, Ilya Lintsbakh, Andy Mcgovern, Aleksandr Nisnevich, Adam Pauls, Dmitrij Petters,
  Brent Read, Dan Roth, Subhro Roy, Jesse Rusak, Beth Short, Div Slomin, Ben Snyder,
  Stephon Striplin, Yu Su, Zachary Tellman, Sam Thomson, Andrei Vorobev, Izabela Witoszko,
  Jason Wolfe, Abby Wray, Yuchen Zhang, Alexander Zotov
conference: Transactions of the Association for Computational Linguistics
year: 2020
bibkey: machines2020task
citations: 100
additional_links: [{name: Code, url: 'https://www.microsoft.com/en-us/research/project/dataflow-based-dialogue-semantic-machines'},
  {name: Paper, url: 'https://arxiv.org/abs/2009.11423'}]
tags: ["Datasets", "TACL"]
short_authors: Machines et al.
---
We describe an approach to task-oriented dialogue in which dialogue state is
represented as a dataflow graph. A dialogue agent maps each user utterance to a
program that extends this graph. Programs include metacomputation operators for
reference and revision that reuse dataflow fragments from previous turns. Our
graph-based state enables the expression and manipulation of complex user
intents, and explicit metacomputation makes these intents easier for learned
models to predict. We introduce a new dataset, SMCalFlow, featuring complex
dialogues about events, weather, places, and people. Experiments show that
dataflow graphs and metacomputation substantially improve representability and
predictability in these natural dialogues. Additional experiments on the
MultiWOZ dataset show that our dataflow representation enables an otherwise
off-the-shelf sequence-to-sequence model to match the best existing
task-specific state tracking model. The SMCalFlow dataset and code for
replicating experiments are available at
https://www.microsoft.com/en-us/research/project/dataflow-based-dialogue-semantic-machines.