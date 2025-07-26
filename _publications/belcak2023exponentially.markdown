---
layout: publication
title: Exponentially Faster Language Modelling
authors: Peter Belcak, Roger Wattenhofer
conference: No Venue
year: 2023
bibkey: belcak2023exponentially
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/655c1d9b58eaf1464320274c'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2311.10770'}]
tags: ["Datasets", "Model Architecture", "Training Techniques"]
short_authors: Peter Belcak, Roger Wattenhofer
---
Language models only really need to use an exponential fraction of their neurons for individual inferences. As proof, we present FastBERT, a BERT variant that uses 0.3% of its neurons during inference while performing on par with similar BERT models. FastBERT selectively engages just 12 out of 4095 neurons for each layer inference. This is achieved by replacing feedforward networks with fast feedforward networks (FFFs). While no truly efficient implementation currently exists to unlock the full acceleration potential of conditional neural execution, we provide high-level CPU code achieving 78x speedup over the optimized baseline feedforward implementation, and a PyTorch implementation delivering 40x speedup over the equivalent batched feedforward inference. We publish our training code, benchmarking setup, and model weights.

https://huggingface.co/discussions/paper/655c1d9b58eaf1464320274c