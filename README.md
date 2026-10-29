# Week 5: Building AI Agents

This five-day project explores how LLM-powered agents are built, from a hand-written tool-calling loop to higher-level orchestration frameworks and a human-reviewed application.

## Learning roadmap

| Day | Focus | What you will practice |
| --- | --- | --- |
| [Day 1](./Day1/) | Agent fundamentals in raw Python | Implement tool schemas, tool execution, message handling, and agent working state directly. |
| [Day 2](./Day2/) | LangChain | Use model/tool integrations, agent execution, composable pipelines, and memory; compare framework abstractions with the manual loop. |
| [Day 3](./Day3/) | LangGraph | Build graph-based workflows with conditional routing, cycles, human-in-the-loop pauses, and persistence. |
| [Day 4](./Day4/) | CrewAI | Design role-based multi-agent systems, sequential and hierarchical task flows, and consider evaluation and cost. |
| [Day 5](./Day5/) | Client-intake and proposal agent | Apply LangGraph and FastAPI to classify inquiries, draft proposals, pause for human approval, and evaluate the workflow. |

## Skills covered

- Tool calling, agent loops, message state, and memory
- Comparing direct orchestration with LangChain abstractions
- Graph-based routing, checkpoints, and human approval
- Multi-agent roles, task design, and delegation
- API integration, evaluation, failure handling, and monitoring

## Getting started

Work through the notebooks in day order. The final-day project includes a README with its own installation, evaluation, and API instructions. LLM provider keys are optional for some exercises and must be supplied through local environment variables or an untracked `.env` file—never commit real credentials.

## Repository hygiene

The accompanying `.gitignore` protects credentials, local environments, caches, runtime databases, and logs. Review datasets and generated outputs before publishing, and keep `.env.example`-style files limited to placeholder values.
