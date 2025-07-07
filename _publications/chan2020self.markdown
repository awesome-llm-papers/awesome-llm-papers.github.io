---
layout: publication
title: 'Cocon: A Self-supervised Approach For Controlled Text Generation'
authors: Alvin Chan, Yew-soon Ong, Bill Pung, Aston Zhang, Jie Fu
conference: Arxiv
year: 2020
citations: 45
bibkey: chan2020self
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.03535'}]
tags: [Training Techniques, Transformer, Attention Mechanism, Language Modeling, Model
    Architecture]
---
Pretrained Transformer-based language models (LMs) display remarkable natural
language generation capabilities. With their immense potential, controlling
text generation of such LMs is getting attention. While there are studies that
seek to control high-level attributes (such as sentiment and topic) of
generated text, there is still a lack of more precise control over its content
at the word- and phrase-level. Here, we propose Content-Conditioner (CoCon) to
control an LM's output text with a content input, at a fine-grained level. In
our self-supervised approach, the CoCon block learns to help the LM complete a
partially-observed text sequence by conditioning with content inputs that are
withheld from the LM. Through experiments, we show that CoCon can naturally
incorporate target content into generated texts and control high-level text
attributes in a zero-shot manner.