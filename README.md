# Carlos Gracia

I work on the operating model behind AI in production: eval harnesses, governance, and the rollout judgement that move systems from demo to deployment.

Head of Customer Support at [Korial](https://korial.com) (Energy Robotics GmbH). Built the 24/7 customer operations function and the AI operations platform behind it for a fleet of ~100 safety-critical inspection robots deployed across 20+ enterprise customers in oil & gas, utilities, and industrial services. Customers include Shell, BP, Chevron, Repsol, Petrobras, Pluspetrol, and E.ON.

The platform runs in production behind the support queue: automated investigation and context on every ticket, over hybrid retrieval across vector search and a knowledge graph, with multi-model routing, an 8-dimension evaluation harness, and cost and quality observability. Humans stay in the loop throughout. That is copilot-first by design, not by default, because low-volume, safety-critical B2B support is the wrong place for full automation. It absorbed a doubling of ticket volume while headcount grew by one.

## Open-source work

### [opsflow](https://github.com/cgracia/opsflow)
AI control plane for technical support operations: multi-agent triage, SLA monitoring, fleet anomaly detection, daily briefings. A personal project exploring how hybrid retrieval, entity-aware reasoning, and policy-bounded governance compose into a system you can actually deploy. Alpha, in active development.

→ **[Architecture diagrams (LikeC4)](https://cgracia.github.io/opsflow/)**

### [ratchet-method](https://github.com/cgracia/ratchet-method)
Evidence-driven development for humans and coding agents. Commitment advances one justified step at a time, and reversal stays deliberate rather than accidental. Observations, evidence, hypotheses, decisions and authorised implementations are kept as distinct states instead of being collapsed into each other. The generalised form of the graduation gates I use in production.

### [writeflow](https://github.com/cgracia/writeflow)
Multi-agent writing pipeline. Nine specialist agents (strategist, writer, six parallel reviewers, synthesiser) collaborate through a structured triage, draft, review and synthesis workflow to produce professional communication. Working prototype.

## Elsewhere

- [LinkedIn](https://linkedin.com/in/carlosgraciasola)
- [CV (PDF)](https://github.com/cgracia/cgracia/raw/main/cv.pdf)

## What I'm thinking about

The gap between AI capability and AI in production is mostly operating model: where autonomy is earned, how it is gated, and what triggers retreat. Most teams bolt AI on top of an existing function. The interesting work is redesigning the function around what AI can credibly do, with the governance to keep it honest.
