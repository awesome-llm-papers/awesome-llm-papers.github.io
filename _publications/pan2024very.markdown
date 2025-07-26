---
layout: publication
title: Very Large-scale Multi-agent Simulation In Agentscope
authors: Xuchen Pan, Dawei Gao, Yuexiang Xie, Zhewei Wei, Yaliang Li, Bolin Ding,
  Ji-rong Wen, Jingren Zhou
conference: No Venue
year: 2024
bibkey: pan2024very
additional_links: [{name: Code, url: 'https://github.com/modelscope/agentscope'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/66a31f3aa74b20aad777e82e'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2407.17789'}]
tags: ["Agentic"]
short_authors: Pan et al.
---
Recent advances in large language models (LLMs) have opened new avenues for applying multi-agent systems in very large-scale simulations. However, there remain several challenges when conducting multi-agent simulations with existing platforms, such as limited scalability and low efficiency, unsatisfied agent diversity, and effort-intensive management processes. To address these challenges, we develop several new features and components for AgentScope, a user-friendly multi-agent platform, enhancing its convenience and flexibility for supporting very large-scale multi-agent simulations. Specifically, we propose an actor-based distributed mechanism as the underlying technological infrastructure towards great scalability and high efficiency, and provide flexible environment support for simulating various real-world scenarios, which enables parallel execution of multiple agents, centralized workflow orchestration, and both inter-agent and agent-environment interactions among agents. Moreover, we integrate an easy-to-use configurable tool and an automatic background generation pipeline in AgentScope, simplifying the process of creating agents with diverse yet detailed background settings. Last but not least, we provide a web-based interface for conveniently monitoring and managing a large number of agents that might deploy across multiple devices. We conduct a comprehensive simulation to demonstrate the effectiveness of the proposed enhancements in AgentScope, and provide detailed observations and discussions to highlight the great potential of applying multi-agent systems in large-scale simulations. The source code is released on GitHub at https://github.com/modelscope/agentscope to inspire further research and development in large-scale multi-agent simulations.

https://huggingface.co/discussions/paper/66a31f3aa74b20aad777e82e