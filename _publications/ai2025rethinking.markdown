---
layout: publication
title: Rethinking Reflection In Pre-training
authors: Essential Ai, Darsh J Shah, Peter Rushton, Somanshu Singla, Mohit Parmar,
  Kurt Smith, Yash Vanjani, Ashish Vaswani, Adarsh Chaluvaraju, Andrew Hojel, Andrew
  Ma, Anil Thomas, Anthony Polloreno, Ashish Tanwer, Burhan Drak Sibai, Divya S Mansingka,
  Divya Shivaprasad, Ishaan Shah, Karl Stratos, Khoi Nguyen, Michael Callahan, Michael
  Pust, Mrinal Iyer, Philip Monk, Platon Mazarakis, Ritvik Kapila, Saurabh Srivastava,
  Tim Romanski
conference: No Venue
year: 2025
bibkey: ai2025rethinking
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.04022'}]
tags: ["Training Techniques"]
short_authors: Ai et al.
---
A language model's ability to reflect on its own reasoning provides a key advantage for solving complex problems. While most recent research has focused on how this ability develops during reinforcement learning, we show that it actually begins to emerge much earlier - during the model's pre-training. To study this, we introduce deliberate errors into chains-of-thought and test whether the model can still arrive at the correct answer by recognizing and correcting these mistakes. By tracking performance across different stages of pre-training, we observe that this self-correcting ability appears early and improves steadily over time. For instance, an OLMo2-7B model pre-trained on 4 trillion tokens displays self-correction on our six self-reflection tasks.

https://huggingface.co/discussions/paper/67f46e68a5ea8948d60c621f