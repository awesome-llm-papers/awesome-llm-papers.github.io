---
layout: publication
title: Recommending Metamodel Concepts During Modeling Activities With Pre-trained
  Language Models
authors: Weyssow Martin, Sahraoui Houari, Syriani Eugene
conference: Software and Systems Modeling
year: 2021
bibkey: weyssow2021recommending
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.01642'}]
tags: [Training Techniques, Alt, Evaluation, Reinforcement Learning, Datasets]
---
The design of conceptually sound metamodels that embody proper semantics in
relation to the application domain is particularly tedious in Model-Driven
Engineering. As metamodels define complex relationships between domain
concepts, it is crucial for a modeler to define these concepts thoroughly while
being consistent with respect to the application domain. We propose an approach
to assist a modeler in the design of a metamodel by recommending relevant
domain concepts in several modeling scenarios. Our approach does not require to
extract knowledge from the domain or to hand-design completion rules. Instead,
we design a fully data-driven approach using a deep learning model that is able
to abstract domain concepts by learning from both structural and lexical
metamodel properties in a corpus of thousands of independent metamodels. We
evaluate our approach on a test set containing 166 metamodels, unseen during
the model training, with more than 5000 test samples. Our preliminary results
show that the trained model is able to provide accurate top-\\(5\\) lists of
relevant recommendations for concept renaming scenarios. Although promising,
the results are less compelling for the scenario of the iterative construction
of the metamodel, in part because of the conservative strategy we use to
evaluate the recommendations.