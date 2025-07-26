---
layout: publication
title: Transformers Can Do Arithmetic With The Right Embeddings
authors: Sean Mcleish, Arpit Bansal, Alex Stein, Neel Jain, John Kirchenbauer, Brian
  R. Bartoldson, Bhavya Kailkhura, Abhinav Bhatele, Jonas Geiping, Avi Schwarzschild,
  Tom Goldstein
conference: No Venue
year: 2024
bibkey: mcleish2024transformers
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66555b27480d7e1ccba35e27'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2405.17399'}]
tags: ["Training Techniques"]
short_authors: Mcleish et al.
---
The poor performance of transformers on arithmetic tasks seems to stem in large part from their inability to keep track of the exact position of each digit inside of a large span of digits. We mend this problem by adding an embedding to each digit that encodes its position relative to the start of the number. In addition to the boost these embeddings provide on their own, we show that this fix enables architectural modifications such as input injection and recurrent layers to improve performance even further. With positions resolved, we can study the logical extrapolation ability of transformers. Can they solve arithmetic problems that are larger and more complex than those in their training data? We find that training on only 20 digit numbers with a single GPU for one day, we can reach state-of-the-art performance, achieving up to 99% accuracy on 100 digit addition problems. Finally, we show that these gains in numeracy also unlock improvements on other multi-step reasoning tasks including sorting and multiplication.

https://huggingface.co/discussions/paper/66555b27480d7e1ccba35e27