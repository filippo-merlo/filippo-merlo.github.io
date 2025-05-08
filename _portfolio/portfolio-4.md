---
title: "Prototyping with Generative Agents"
excerpt: "This project builds on two studies by Joon Sung Park and collaborators to improve the prototyping of social computing systems. The first study, 'Social Simulacra: Creating Populated Prototypes for Social Computing Systems' (Park et al., UIST 2022), introduces a technique called social simulacra, which generates realistic simulations of online communities based on a designer’s input (e.g., community goals, rules, and member personas) to expose potential social dynamics—both constructive and disruptive—at scale. The second study, 'Generative Agents: Interactive Simulacra of Human Behavior' (Park et al., CHI 2023), presents generative agents, an architecture built around large language models enhanced with memory and reflective reasoning, enabling agents to simulate more coherent and human-like behavior over time. This project proposes integrating generative agents into the social simulacra framework to increase the realism and interpretability of simulated interactions. By giving each agent a distinct memory, personality, and ability to reflect, the system not only better mimics plausible social behavior but also supports qualitative analysis of interactions through agents’ internal perspectives.<img src='/images/gen_ag.png' width='500' style='display: block; margin-left: auto; margin-right: auto;'>"
collection: portfolio
---

The idea for this project originated from two recent studies by Joon Sung Park. The first study, titled ”Social
Simulacra: Creating Populated Prototypes for Social Computing Systems”, focuses on a prototyping technique
called ”social simulacra.” This technique is employed to investigate and understand the social behaviors that may
emerge in a proposed design for a social computing system, examples of which could be platforms such as Reddit
or Discord. The primary issue addressed in this study is that current prototyping methods for social computing
systems typically involve recruiting small groups of people, which may not reveal all the challenges that can arise
when the system is scaled up. Social simulacra is introduced as a solution to this limitation. It takes input in
the form of a designer’s description of a community’s design, including its goals, rules, and member personas, and
generates a realistic instance of that design with simulated social behaviors. These behaviors encompass various
activities such as posts, replies, and even anti-social behaviors. The objective is to assist designers in comprehending
how a social system might behave when populated, enabling them to make necessary adjustments to the design to
mitigate potential challenges before they become problematic. The study also contributes techniques for instructing
a large language model to generate thousands of distinct community members and simulate their social interactions,
leveraging the model’s training data, which includes a wide range of positive and negative behaviors on social media
platforms.
The second study, which was the subject of my paper review, is titled ”Generative Agents: Interactive Simulacra
of Human Behavior”. It introduces the concept of ”generative agents,” which consist on an architecture built
around a language model that enables it to better simulate human behavior by reasoning about a broader set of
experiences than what can be described in a simple prompt. This is achieved by using a memory stream to surface
relevant memories, allowing the generative agent to provide more informative and specific responses. Specifically,
this approach enhances the generative agents’ ability to answer questions about their experiences by avoiding the
limitation of summarizing all experiences within a confined context window. Instead, it relies on relevant memories
to provide responses. Additionally, it improves the generative agents’ ability to generalize and make inferences by
drawing from higher-level reflections based on observational memory.
The idea proposed by this project is to use the ”generative agents” described in the second study to enhance
the believability of the social interaction simulation used in the prototyping technique of ”social simulacra.” As
we will demonstrate, the utility of this choice extends beyond the credibility of the simulation because equipping
each agent with its own personality, memory, and reflective abilities makes it possible to gather insights on the
interaction directly from individual agents.


[Document](../../files/HLT_project_report___Filippo_Merlo.pdf)  [Code](https://github.com/filippo-merlo/socSimulacra_with_genAgents.git)