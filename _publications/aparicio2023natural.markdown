---
layout: publication
title: Natural Language To SQL In Low-code Platforms
authors: Aparicio et al.
conference: Proceedings of the VLDB Endowment
year: 2023
bibkey: aparicio2023natural
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.15239'}]
tags: [Prompting, Tools]
---
One of the developers' biggest challenges in low-code platforms is retrieving
data from a database using SQL queries. Here, we propose a pipeline allowing
developers to write natural language (NL) to retrieve data. In this study, we
collect, label, and validate data covering the SQL queries most often performed
by OutSystems users. We use that data to train a NL model that generates SQL.
Alongside this, we describe the entire pipeline, which comprises a feedback
loop that allows us to quickly collect production data and use it to retrain
our SQL generation model. Using crowd-sourcing, we collect 26k NL and SQL pairs
and obtain an additional 1k pairs from production data. Finally, we develop a
UI that allows developers to input a NL query in a prompt and receive a
user-friendly representation of the resulting SQL query. We use A/B testing to
compare four different models in production and observe a 240% improvement in
terms of adoption of the feature, 220% in terms of engagement rate, and a 90%
decrease in failure rate when compared against the first model that we put into
production, showcasing the effectiveness of our pipeline in continuously
improving our feature.