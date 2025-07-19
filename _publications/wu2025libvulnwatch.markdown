---
layout: publication
title: 'Libvulnwatch: A Deep Assessment Agent System And Leaderboard For Uncovering
  Hidden Vulnerabilities In Open-source AI Libraries'
authors: Wu et al.
conference: 2015 IEEE International Conference on Software Maintenance and Evolution
  (ICSME)
year: 2025
bibkey: wu2025libvulnwatch
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.08842'}]
tags: [RAG, Agentic, Tools, Evaluation, Security, Datasets]
---
Open-source AI libraries are foundational to modern AI systems, yet they present significant, underexamined risks spanning security, licensing, maintenance, supply chain integrity, and regulatory compliance. We introduce LibVulnWatch, a system that leverages recent advances in large language models and agentic workflows to perform deep, evidence-based evaluations of these libraries. Built on a graph-based orchestration of specialized agents, the framework extracts, verifies, and quantifies risk using information from repositories, documentation, and vulnerability databases. LibVulnWatch produces reproducible, governance-aligned scores across five critical domains, publishing results to a public leaderboard for ongoing ecosystem monitoring. Applied to 20 widely used libraries, including ML frameworks, LLM inference engines, and agent orchestration tools, our approach covers up to 88% of OpenSSF Scorecard checks while surfacing up to 19 additional risks per library, such as critical RCE vulnerabilities, missing SBOMs, and regulatory gaps. By integrating advanced language technologies with the practical demands of software risk assessment, this work demonstrates a scalable, transparent mechanism for continuous supply chain evaluation and informed library selection.