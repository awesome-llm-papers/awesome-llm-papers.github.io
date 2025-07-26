---
layout: publication
title: Discovering Language Model Behaviors With Model-written Evaluations
authors: "Ethan Perez, Sam Ringer, Kamil\u0117 Luko\u0161i\u016Bt\u0117, Karina Nguyen,\
  \ Edwin Chen, Scott Heiner, Craig Pettit, Catherine Olsson, Sandipan Kundu, Saurav\
  \ Kadavath, Andy Jones, Anna Chen, Ben Mann, Brian Israel, Bryan Seethor, Cameron\
  \ Mckinnon, Christopher Olah, da Yan, Daniela Amodei, Dario Amodei, Dawn Drain,\
  \ Dustin Li, Eli Tran-johnson, Guro Khundadze, Jackson Kernion, James Landis, Jamie\
  \ Kerr, Jared Mueller, Jeeyoon Hyun, Joshua Landau, Kamal Ndousse, Landon Goldberg,\
  \ Liane Lovitt, Martin Lucas, Michael Sellitto, Miranda Zhang, Neerav Kingsland,\
  \ Nelson Elhage, Nicholas Joseph, Noem\xED Mercado, Nova Dassarma, Oliver Rausch,\
  \ Robin Larson, Sam Mccandlish, Scott Johnston, Shauna Kravec, Sheer El Showk, Tamera\
  \ Lanham, Timothy Telleen-lawton, Tom Brown, Tom Henighan, Tristan Hume, Yuntao\
  \ Bai, Zac Hatfield-dodds, Jack Clark, Samuel R. Bowman, Amanda Askell, Roger Grosse,\
  \ Danny Hernandez, Deep Ganguli, Evan Hubinger, Nicholas Schiefer, Jared Kaplan"
conference: 'Findings of the Association for Computational Linguistics: ACL 2023'
year: 2023
bibkey: perez2022discovering
citations: 85
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.09251'}]
tags: ["Datasets", "Reinforcement Learning"]
short_authors: Perez et al.
---
As language models (LMs) scale, they develop many novel behaviors, good and
bad, exacerbating the need to evaluate how they behave. Prior work creates
evaluations with crowdwork (which is time-consuming and expensive) or existing
data sources (which are not always available). Here, we automatically generate
evaluations with LMs. We explore approaches with varying amounts of human
effort, from instructing LMs to write yes/no questions to making complex
Winogender schemas with multiple stages of LM-based generation and filtering.
Crowdworkers rate the examples as highly relevant and agree with 90-100% of
labels, sometimes more so than corresponding human-written datasets. We
generate 154 datasets and discover new cases of inverse scaling where LMs get
worse with size. Larger LMs repeat back a dialog user's preferred answer
("sycophancy") and express greater desire to pursue concerning goals like
resource acquisition and goal preservation. We also find some of the first
examples of inverse scaling in RL from Human Feedback (RLHF), where more RLHF
makes LMs worse. For example, RLHF makes LMs express stronger political views
(on gun rights and immigration) and a greater desire to avoid shut down.
Overall, LM-written evaluations are high-quality and let us quickly discover
many novel LM behaviors.