---
layout: publication
title: 'Fedmkt: Federated Mutual Knowledge Transfer For Large And Small Language Models'
authors: Fan et al.
conference: IEEE Internet of Things Journal
year: 2024
bibkey: fan2024fedmkt
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2406.02224'}]
tags: [Language Modeling, Tools]
---
Recent research in federated large language models (LLMs) has primarily
focused on enabling clients to fine-tune their locally deployed homogeneous
LLMs collaboratively or on transferring knowledge from server-based LLMs to
small language models (SLMs) at downstream clients. However, a significant gap
remains in the simultaneous mutual enhancement of both the server's LLM and
clients' SLMs. To bridge this gap, we propose FedMKT, a parameter-efficient
federated mutual knowledge transfer framework for large and small language
models. This framework is designed to adaptively transfer knowledge from the
server's LLM to clients' SLMs while concurrently enriching the LLM with
clients' unique domain insights. We facilitate token alignment using minimum
edit distance (MinED) and then selective mutual knowledge transfer between
client-side SLMs and a server-side LLM, aiming to collectively enhance their
performance. Through extensive experiments across three distinct scenarios, we
evaluate the effectiveness of FedMKT using various public LLMs and SLMs on a
range of NLP text generation tasks. Empirical results demonstrate that FedMKT
simultaneously boosts the performance of both LLMs and SLMs.