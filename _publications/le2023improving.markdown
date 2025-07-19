---
layout: publication
title: Improving Open-domain Dialogue Evaluation With A Causal Inference Model
authors: Le et al.
conference: Political Research Quarterly
year: 2023
bibkey: le2023improving
citations: 220
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.13372'}]
tags: [Alt, Evaluation, Transformer, Model Architecture, Reinforcement Learning]
---
Effective evaluation methods remain a significant challenge for research on
open-domain conversational dialogue systems. Explicit satisfaction ratings can
be elicited from users, but users often do not provide ratings when asked, and
those they give can be highly subjective. Post-hoc ratings by experts are an
alternative, but these can be both expensive and complex to collect. Here, we
explore the creation of automated methods for predicting both expert and user
ratings of open-domain dialogues. We compare four different approaches. First,
we train a baseline model using an end-to-end transformer to predict ratings
directly from the raw dialogue text. The other three methods are variants of a
two-stage approach in which we first extract interpretable features at the turn
level that capture, among other aspects, user dialogue behaviors indicating
contradiction, repetition, disinterest, compliments, or criticism. We project
these features to the dialogue level and train a dialogue-level MLP regression
model, a dialogue-level LSTM, and a novel causal inference model called
counterfactual-LSTM (CF-LSTM) to predict ratings. The proposed CF-LSTM is a
sequential model over turn-level features which predicts ratings using multiple
regressors depending on hypotheses derived from the turn-level features. As a
causal inference model, CF-LSTM aims to learn the underlying causes of a
specific event, such as a low rating. We also bin the user ratings and perform
classification experiments with all four models. In evaluation experiments on
conversational data from the Alexa Prize SocialBot, we show that the CF-LSTM
achieves the best performance for predicting dialogue ratings and
classification.