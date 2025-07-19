---
layout: publication
title: 'You Can REST Now: Automated Specification Inference And Black-box Testing
  Of Restful Apis With Large Language Models'
authors: Decrop et al.
conference: 2020 IEEE 13th International Conference on Software Testing, Validation
  and Verification (ICST)
year: 2024
bibkey: decrop2024you
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.05102'}]
tags: [RAG, Training Techniques, Prompting, Tools, Evaluation, Reinforcement Learning,
  Fine Tuning]
---
RESTful APIs are popular web services, requiring documentation to ease their
comprehension, reusability and testing practices. The OpenAPI Specification
(OAS) is a widely adopted and machine-readable format used to document such
APIs. However, manually documenting RESTful APIs is a time-consuming and
error-prone task, resulting in unavailable, incomplete, or imprecise
documentation. As RESTful API testing tools require an OpenAPI specification as
input, insufficient or informal documentation hampers testing quality.
  Recently, Large Language Models (LLMs) have demonstrated exceptional
abilities to automate tasks based on their colossal training data. Accordingly,
such capabilities could be utilized to assist the documentation and testing
process of RESTful APIs.
  In this paper, we present RESTSpecIT, the first automated RESTful API
specification inference and black-box testing approach leveraging LLMs. The
approach requires minimal user input compared to state-of-the-art RESTful API
inference and testing tools; Given an API name and an LLM key, HTTP requests
are generated and mutated with data returned by the LLM. By sending the
requests to the API endpoint, HTTP responses can be analyzed for inference and
testing purposes. RESTSpecIT utilizes an in-context prompt masking strategy,
requiring no model fine-tuning. Our evaluation demonstrates that RESTSpecIT is
capable of: (1) inferring specifications with 85.05% of GET routes and 81.05%
of query parameters found on average, (2) discovering undocumented and valid
routes and parameters, and (3) uncovering server errors in RESTful APIs.
Inferred specifications can also be used as testing tool inputs.