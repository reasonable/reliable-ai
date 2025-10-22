# The Reliable Agentic AI Manifesto

We are entering a new era: Agentic AI. As AI systems evolve from deterministic rules to autonomous, stateful agents, enterprises confront unprecedented engineering challenges. These agents, operating in distributed environments, embody the inherent nondeterminism of distributed systems and the stochastic nature of AI outputs. Traditional software approaches are insufficient; DevEx and OpsEx for agentic systems must be purpose-built to meet these needs.

Reliable Agentic AI is designed to embrace and manage uncertainty and randomness, resting on four pillars:

### High-Productivity Developer Experience 

We must minimize complexity and enforce consistency through guard-railed abstractions and reusable patterns. Fostering fast iteration, enabling developers to focus on agent logic and coordination, and mitigating instability in systems where both infrastructure and AI behaviors are non-deterministic. Leveraging LLMs through programming, rather than just prompting, unlocks the creation of novel AI-first languages and optimization frameworks. Key areas, such as type safety and new programming paradigms for composable content engineering, show great promise, alongside the crucial need to support the whole developer experience for seamless integration and adoption. 

### Scalable, Resilient, and Predictable Operationalization 

Operating systems that utilize both infrastructure and AI components as sources of variability require more than basic scalability. It requires predictable scaling of behavior, robust fault isolation, and adaptive recovery mechanisms. Such systems must absorb unexpected AI behaviors and distributed system failures without degradation, scaling to millions of agents and transactions while maintaining correctness and availability. This is particularly crucial when building multi-agent systems, where the interplay of numerous autonomous AI components necessitates adherence to foundational patterns and standard communication protocols (e.g., A2A, ACP, and MCP) to ensure reliable and predictable interactions.

### Deep and Intuitive System Understanding and Observability 

In systems where non-determinism is the norm, real-time visibility is crucial. We need tools that provide high-level visualizations of agent interactions, event flows, LLM request/response, external tool communications, and decision paths. This enables continuous tracing of emergent behaviors, validation of system correctness, debugging, and rapid diagnosis of issues stemming from AI outputs or distributed inconsistencies. This includes tracking end-to-end system SLAs across distributed systems, multi-agent collaboration, and AI/LLM-specific metrics.

### Reliable Agentic Loops

Reliable agentic AI relies on three interconnected loops:
* Reason: The agent's internal thought process needs to be bounded, consistent, and aligned.

* Action: The execution of tasks (LLMs, tools, APIs), which must remain safe, auditable, and goal-directed.

* Eval: The process of reflection and feedback, encompassing human interaction and self-reflection (e.g., LLM-as-a-Judge), to ensure continuous learning and improvement.

Managing these loops seamlessly and cohesively ensures agent behavior remains stable, transparent, and trustworthy.

## We believe in the following principles of Reliable AI:

* The future of agentic AI systems is built on the rigorous foundations of computer science and real-world software engineering.

* The Reactive Principles provide the best foundation for agentic systems, with innovations in software-defined declarative infrastructure serving as stepping stones.

* Multi-agent systems are best built upon the Actor Model, leveraging its principles of failure recovery, isolation, autonomy, resilience, and efficient concurrency.

* Industrial strength in tooling, observability, and portability will remain the mainstay of enterprise-grade agentic AI, ensuring auditable, securable, and compliant systems.

* Programming, rather than prompting LLMs, and the development of new AI-first programming languages with type safety will bring rigorous software engineering to the AI era.
Open Source is the best way to advance Reliable Agentic AI, fostering community, collaboration, and innovation.

* Compliance, security, verifiability, and repeatability are essential for building trust in agentic AI systems, laying the foundation for successful deployment and operation.

* Agentic AI requires tooling to bound reasoning, action, and eval loops, ensuring they remain safe, stable, and aligned without runaway behavior.
If you share this vision, sign this Manifesto and join our community.

-----
Signed: SIGNATORIES.md

You can sign this manifesto too, and provide feedback or edits!

To sign, you can either:

* **Send a pull request adding your name to [SIGNATORIES.md](https://github.com/reasonable/reliable/blob/main/SIGNATORIES.md)**, or
* **Cut an [issue](https://github.com/reasonable/reliable-ai/issues) with your name**
* **Answer the [Reliable Agentic AI Survey #1](https://bit.ly/reliable-ai)**, see which best practices apply, and add your name and optional feedback

You can provide feedback as an issue or a pull request on the text of this document.

