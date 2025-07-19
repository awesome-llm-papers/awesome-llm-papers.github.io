---
layout: publication
title: 'Compositionality Decomposed: How Do Neural Networks Generalise?'
authors: Hupkes et al.
conference: Journal of Artificial Intelligence Research
year: 2019
bibkey: hupkes2019compositionality
citations: 165
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.08351'}]
tags: [Model Architecture, Training Techniques, Evaluation, Transformer]
---
Despite a multitude of empirical studies, little consensus exists on whether
neural networks are able to generalise compositionally, a controversy that, in
part, stems from a lack of agreement about what it means for a neural model to
be compositional. As a response to this controversy, we present a set of tests
that provide a bridge between, on the one hand, the vast amount of linguistic
and philosophical theory about compositionality of language and, on the other,
the successful neural models of language. We collect different interpretations
of compositionality and translate them into five theoretically grounded tests
for models that are formulated on a task-independent level. In particular, we
provide tests to investigate (i) if models systematically recombine known parts
and rules (ii) if models can extend their predictions beyond the length they
have seen in the training data (iii) if models' composition operations are
local or global (iv) if models' predictions are robust to synonym substitutions
and (v) if models favour rules or exceptions during training. To demonstrate
the usefulness of this evaluation paradigm, we instantiate these five tests on
a highly compositional data set which we dub PCFG SET and apply the resulting
tests to three popular sequence-to-sequence models: a recurrent, a
convolution-based and a transformer model. We provide an in-depth analysis of
the results, which uncover the strengths and weaknesses of these three
architectures and point to potential areas of improvement.