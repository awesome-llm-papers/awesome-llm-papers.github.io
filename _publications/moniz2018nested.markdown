---
layout: publication
title: Nested Lstms
authors: Moniz Joel Ruben Antony, Krueger David
conference: Neurocomputing
year: 2018
bibkey: moniz2018nested
citations: 140
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.10308'}]
tags: [Model Architecture, Language Modeling, Reinforcement Learning]
---
We propose Nested LSTMs (NLSTM), a novel RNN architecture with multiple
levels of memory. Nested LSTMs add depth to LSTMs via nesting as opposed to
stacking. The value of a memory cell in an NLSTM is computed by an LSTM cell,
which has its own inner memory cell. Specifically, instead of computing the
value of the (outer) memory cell as \\(c^\{outer\}_t = f_t \odot c_\{t-1\} + i_t
\odot g_t\\), NLSTM memory cells use the concatenation \\((f_t \odot c_\{t-1\}, i_t
\odot g_t)\\) as input to an inner LSTM (or NLSTM) memory cell, and set
\\(c^\{outer\}_t\\) = \\(h^\{inner\}_t\\). Nested LSTMs outperform both stacked and
single-layer LSTMs with similar numbers of parameters in our experiments on
various character-level language modeling tasks, and the inner memories of an
LSTM learn longer term dependencies compared with the higher-level units of a
stacked LSTM.