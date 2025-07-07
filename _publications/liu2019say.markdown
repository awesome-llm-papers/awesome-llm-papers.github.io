---
layout: publication
title: 'Say What I Want: Towards The Dark Side Of Neural Dialogue Models'
authors: Haochen Liu, Tyler Derr, Zitao Liu, Jiliang Tang
conference: Arxiv
year: 2019
citations: 18
bibkey: liu2019say
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.06044'}]
tags: [Reinforcement Learning, Agentic, Applications, Security, Prompting]
---
Neural dialogue models have been widely adopted in various chatbot
applications because of their good performance in simulating and generalizing
human conversations. However, there exists a dark side of these models -- due
to the vulnerability of neural networks, a neural dialogue model can be
manipulated by users to say what they want, which brings in concerns about the
security of practical chatbot services. In this work, we investigate whether we
can craft inputs that lead a well-trained black-box neural dialogue model to
generate targeted outputs. We formulate this as a reinforcement learning (RL)
problem and train a Reverse Dialogue Generator which efficiently finds such
inputs for targeted outputs. Experiments conducted on a representative neural
dialogue model show that our proposed model is able to discover such desired
inputs in a considerable portion of cases. Overall, our work reveals this
weakness of neural dialogue models and may prompt further researches of
developing corresponding solutions to avoid it.