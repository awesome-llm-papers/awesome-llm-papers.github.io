---
layout: publication
title: Language Models (mostly) Know What They Know
authors: Saurav Kadavath, Tom Conerly, Amanda Askell, Tom Henighan, Dawn Drain, Ethan
  Perez, Nicholas Schiefer, Zac Hatfield-dodds, Nova Dassarma, Eli Tran-johnson, Scott
  Johnston, Sheer El-showk, Andy Jones, Nelson Elhage, Tristan Hume, Anna Chen, Yuntao
  Bai, Sam Bowman, Stanislav Fort, Deep Ganguli, Danny Hernandez, Josh Jacobson, Jackson
  Kernion, Shauna Kravec, Liane Lovitt, Kamal Ndousse, Catherine Olsson, Sam Ringer,
  Dario Amodei, Tom Brown, Jack Clark, Nicholas Joseph, Ben Mann, Sam Mccandlish,
  Chris Olah, Jared Kaplan
conference: Arxiv
year: 2022
bibkey: kadavath2022language
citations: 126
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.05221'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: Kadavath et al.
---
We study whether language models can evaluate the validity of their own
claims and predict which questions they will be able to answer correctly. We
first show that larger models are well-calibrated on diverse multiple choice
and true/false questions when they are provided in the right format. Thus we
can approach self-evaluation on open-ended sampling tasks by asking models to
first propose answers, and then to evaluate the probability "P(True)" that
their answers are correct. We find encouraging performance, calibration, and
scaling for P(True) on a diverse array of tasks. Performance at self-evaluation
further improves when we allow models to consider many of their own samples
before predicting the validity of one specific possibility. Next, we
investigate whether models can be trained to predict "P(IK)", the probability
that "I know" the answer to a question, without reference to any particular
proposed answer. Models perform well at predicting P(IK) and partially
generalize across tasks, though they struggle with calibration of P(IK) on new
tasks. The predicted P(IK) probabilities also increase appropriately in the
presence of relevant source materials in the context, and in the presence of
hints towards the solution of mathematical word problems. We hope these
observations lay the groundwork for training more honest models, and for
investigating how honesty generalizes to cases where models are trained on
objectives other than the imitation of human writing.