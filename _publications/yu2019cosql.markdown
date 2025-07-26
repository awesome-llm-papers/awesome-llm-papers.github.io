---
layout: publication
title: 'Cosql: A Conversational Text-to-sql Challenge Towards Cross-domain Natural
  Language Interfaces To Databases'
authors: Tao Yu, Rui Zhang, He Yang Er, Suyi Li, Eric Xue, Bo Pang, Xi Victoria Lin,
  Yi Chern Tan, Tianze Shi, Zihan Li, Youxuan Jiang, Michihiro Yasunaga, Sungrok Shim,
  Tao Chen, Alexander Fabbri, Zifan Li, Luyao Chen, Yuwen Zhang, Shreya Dixit, Vincent
  Zhang, Caiming Xiong, Richard Socher, Walter S Lasecki, Dragomir Radev
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: yu2019cosql
citations: 103
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.05378'}]
tags: []
short_authors: Yu et al.
---
We present CoSQL, a corpus for building cross-domain, general-purpose
database (DB) querying dialogue systems. It consists of 30k+ turns plus 10k+
annotated SQL queries, obtained from a Wizard-of-Oz (WOZ) collection of 3k
dialogues querying 200 complex DBs spanning 138 domains. Each dialogue
simulates a real-world DB query scenario with a crowd worker as a user
exploring the DB and a SQL expert retrieving answers with SQL, clarifying
ambiguous questions, or otherwise informing of unanswerable questions. When
user questions are answerable by SQL, the expert describes the SQL and
execution results to the user, hence maintaining a natural interaction flow.
CoSQL introduces new challenges compared to existing task-oriented dialogue
datasets:(1) the dialogue states are grounded in SQL, a domain-independent
executable representation, instead of domain-specific slot-value pairs, and (2)
because testing is done on unseen databases, success requires generalizing to
new domains. CoSQL includes three tasks: SQL-grounded dialogue state tracking,
response generation from query results, and user dialogue act prediction. We
evaluate a set of strong baselines for each task and show that CoSQL presents
significant challenges for future research. The dataset, baselines, and
leaderboard will be released at https://yale-lily.github.io/cosql.