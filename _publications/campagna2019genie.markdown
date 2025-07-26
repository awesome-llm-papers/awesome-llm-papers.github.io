---
layout: publication
title: 'Genie: A Generator Of Natural Language Semantic Parsers For Virtual Assistant
  Commands'
authors: Giovanni Campagna, Silei Xu, Mehrad Moradshahi, Richard Socher, Monica S.
  Lam
conference: Proceedings of the 40th ACM SIGPLAN Conference on Programming Language
  Design and Implementation
year: 2019
bibkey: campagna2019genie
citations: 65
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.09020'}]
tags: []
short_authors: Campagna et al.
---
To understand diverse natural language commands, virtual assistants today are
trained with numerous labor-intensive, manually annotated sentences. This paper
presents a methodology and the Genie toolkit that can handle new compound
commands with significantly less manual effort. We advocate formalizing the
capability of virtual assistants with a Virtual Assistant Programming Language
(VAPL) and using a neural semantic parser to translate natural language into
VAPL code. Genie needs only a small realistic set of input sentences for
validating the neural model. Developers write templates to synthesize data;
Genie uses crowdsourced paraphrases and data augmentation, along with the
synthesized data, to train a semantic parser. We also propose design principles
that make VAPL languages amenable to natural language translation. We apply
these principles to revise ThingTalk, the language used by the Almond virtual
assistant. We use Genie to build the first semantic parser that can support
compound virtual assistants commands with unquoted free-form parameters. Genie
achieves a 62% accuracy on realistic user inputs. We demonstrate Genie's
generality by showing a 19% and 31% improvement over the previous state of the
art on a music skill, aggregate functions, and access control.