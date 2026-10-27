# Carlos Gracia

I'm an engineer who makes complex technical systems work for the customers who depend on them. Robots first, on customer sites. More recently the operations and the AI around them.

As Head of Customer Support at [Korial](https://korial.com) (Energy Robotics GmbH), I built the 24/7 global support function for a fleet of around 100 safety-critical inspection robots, from one person to eleven. Inside it I introduced and ran AI-assisted triage, knowledge and investigation workflows: automated investigation and context on every ticket, hybrid retrieval over vector search and a knowledge graph, multi-model routing, an eight-dimension evaluation harness, cost and quality observability. Copilot-first by design, because safety-critical B2B support is the wrong place for full automation, and each capability had to earn its autonomy. Ticket volume doubled in the first half of 2026 with no increase in headcount.

Before that I deployed warehouse robots at Magazino and commissioned AGV systems at ASTI, which is where I learned how complex systems fail at the customer.

## What I build

- **[Job Radar](projects/job-radar.md)** · private, deployed. Two-stage LLM triage over about 1,400 job postings a day under a fixed API-call budget: cheap batched scanning for recall, deep classification only where it pays. Runs unattended on a k3s cluster. The engineering, including a measured failure and a withdrawn result, is written up in the case study.
- **[opsflow](https://github.com/cgracia/opsflow)** · public alpha. Incident investigation layer: converges alerts, deployment history, telemetry and past tickets into one governed investigation over an entity graph, with humans in control of execution. Runs on synthetic data today; connecting it to a real self-hosted service estate is the planned next step. [Architecture diagrams](https://cgracia.github.io/opsflow/).
- **Bounded autonomy for coding agents** · private, in development. A control plane for what an agent may decide alone and what has to come back to a person.
- **An AI game master for small tabletop RPG groups** · private prototype.

### Open-source utilities

- [ratchet-method](https://github.com/cgracia/ratchet-method): evidence-driven development for humans and coding agents; observations, evidence, hypotheses, decisions and authorised implementations kept as distinct states.
- [praxis](https://github.com/cgracia/praxis): local-first CLI for structured thinking and AI-workflow observability, Rust and DuckDB, all local. Parked: complete and working.
- [writeflow](https://github.com/cgracia/writeflow): multi-agent writing pipeline. A strategist plans, a writer drafts, a workflow-defined panel of specialist reviewers critiques in parallel, and a synthesiser reconciles the feedback with a decision log. Working prototype.

## Private by design

Most of what I build is private because the repositories hold personal and job-search data. Instead I publish case studies, and clean public code once it is ready. More detail on request.

## Stack

Python, FastAPI, REST; a heavy GraphQL consumer (fleet APIs, schema debugging against live deployments). Retrieval and agents: Qdrant, FalkorDB/Graphiti knowledge graphs, LiteLLM multi-model routing, Langfuse observability, MCP tooling. Operations: n8n, Docker, k3s, evaluation harnesses.

## Elsewhere

- [LinkedIn](https://linkedin.com/in/carlosgraciasola)
- [CV (PDF)](https://github.com/cgracia/cgracia/raw/master/cv.pdf)

## What I'm thinking about

Most teams putting AI into production will do it for the first time with real people depending on the result. The hard part is deciding what a system may do on its own and what has to come back to a person, and then knowing what evidence should move that line.
