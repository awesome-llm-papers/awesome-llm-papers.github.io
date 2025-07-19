---
layout: publication
title: The Role Of Conversation Context For Sarcasm Detection In Online Interactions
authors: Ghosh Debanjan, Fabbri Alexander Richard, Muresan Smaranda
conference: Proceedings of the 18th Annual SIGdial Meeting on Discourse and Dialogue
year: 2017
bibkey: ghosh2017role
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.06226'}]
tags: [Model Architecture, Attention Mechanism]
---
Computational models for sarcasm detection have often relied on the content
of utterances in isolation. However, speaker's sarcastic intent is not always
obvious without additional context. Focusing on social media discussions, we
investigate two issues: (1) does modeling of conversation context help in
sarcasm detection and (2) can we understand what part of conversation context
triggered the sarcastic reply. To address the first issue, we investigate
several types of Long Short-Term Memory (LSTM) networks that can model both the
conversation context and the sarcastic response. We show that the conditional
LSTM network (Rocktaschel et al., 2015) and LSTM networks with sentence level
attention on context and response outperform the LSTM model that reads only the
response. To address the second issue, we present a qualitative analysis of
attention weights produced by the LSTM models with attention and discuss the
results compared with human performance on the task.