---
layout: publication
title: Practical Efficiency Of Muon For Pretraining
authors: Essential Ai, Ishaan Shah, Anthony M. Polloreno, Karl Stratos, Philip Monk,
  Adarsh Chaluvaraju, Andrew Hojel, Andrew Ma, Anil Thomas, Ashish Tanwer, Darsh J
  Shah, Khoi Nguyen, Kurt Smith, Michael Callahan, Michael Pust, Mohit Parmar, Peter
  Rushton, Platon Mazarakis, Ritvik Kapila, Saurabh Srivastava, Somanshu Singla, Tim
  Romanski, Yash Vanjani, Ashish Vaswani
conference: No Venue
year: 2025
bibkey: ai2025practical
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.02222'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Ai et al.
---
We demonstrate that Muon, the simplest instantiation of a second-order optimizer, explicitly expands the Pareto frontier over AdamW on the compute-time tradeoff. We find that Muon is more effective than AdamW in retaining data efficiency at large batch sizes, far beyond the so-called critical batch size, while remaining computationally efficient, thus enabling more economical training. We study the combination of Muon and the maximal update parameterization (muP) for efficient hyperparameter transfer and present a simple telescoping algorithm that accounts for all sources of error in muP while introducing only a modest overhead in resources. We validate our findings through extensive experiments with model sizes up to four billion parameters and ablations on the data distribution and architecture.

https://huggingface.co/discussions/paper/6819780fc3d212ad5b48cc89