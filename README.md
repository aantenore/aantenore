# Antonio Antenore

**AI Engineer · Software Architect · Open-source builder**

[LinkedIn](https://www.linkedin.com/in/antonio-antenore-a9b44a107/) · Turin, Italy

**I help product and engineering teams turn useful AI ideas into dependable products: private when they need to be, efficient enough to run in the real world, and clear enough for people to understand and trust.**

## A simple way to see my work

Imagine a team building an assistant for sensitive documents. It should keep private work on the right device, choose an expensive model only when a smaller local one is not enough, survive an approval or restart without doing the same work twice, avoid loading the same model in every browser tab, and leave a readable record of what it decided and changed.

My projects explore each part of that journey as an independent, replaceable building block. They can be used separately: the goal is not one closed platform, but practical foundations that let teams change models, providers, policies, and infrastructure without rebuilding everything.

## Selected work

### [AgenticStrata](https://github.com/aantenore/AgenticStrata) — prove what an AI system actually did

It gives teams a reference architecture for AI agents whose actions must be understandable after the fact. Its contracts, evidence receipts, replay, plain-language explanations, and conformance checks help answer: *What was requested? Who or what was allowed to act? What happened? What evidence supports the result?*

**Maturity:** alpha reference implementation. It checks declared rules against supplied evidence; it is not a regulatory certification.

### [myMoE](https://github.com/aantenore/myMoE) — use the right amount of intelligence for each task

It routes work among replaceable local models, keeps chat and memory local by default, applies explicit budgets and fallbacks, and can prepare a minimal handoff to a premium assistant only when policy and evidence justify it. The aim is to avoid paying the highest cost—or exposing data—for every request.

**Maturity:** alpha local control plane. Results are supported for its documented profiles and evaluations, not claimed as a universal win over every single-model setup.

### [StageFabric](https://github.com/aantenore/stagefabric) — keep each AI step in the right place

It turns a multi-step AI task into an explainable plan across the browser, a local machine, the edge, or the cloud. Privacy rules can block forbidden data movement, fallbacks explain why another location was chosen, and content-free records show where successful work ran without copying the underlying data.

**Maturity:** experimental alpha with a deterministic planner and optional real-runtime execution. It is a reference planner, not a globally optimal scheduler.

### [PauseMesh](https://github.com/aantenore/pausemesh) — let an AI task pause safely and continue once

It gives long-running agents a durable place to stop for a person, another system, or a later event. After a disconnect, restart, duplicate callback, or retry, the same continuation can be claimed and resumed exactly once instead of repeating a payment, message, or other side effect. Its adapters keep MCP, A2A, and AG-UI at the boundary so the core workflow is not tied to one agent protocol.

**Maturity:** alpha durable-execution runtime with SQLite and PostgreSQL stores, protocol adapters, and multi-replica integration tests. It does not make an arbitrary external side effect exactly-once unless that effect also follows the documented idempotency contract.

### [TabLoom](https://github.com/aantenore/tabloom) — let browser tabs share one on-device AI runtime

Instead of every tab loading another copy of the same model, TabLoom coordinates one active owner. It manages queues, streaming, cancellation, safe takeover, and compatibility checks so sibling pages can share scarce device memory without becoming tied to one inference provider.

**Maturity:** alpha library. Its real WebLLM path is verified on Chrome with WebGPU, not across every browser, GPU, or model.

### [SemWitness](https://github.com/aantenore/semwitness) — reduce AI token waste without blindly trusting compression

It lets teams test a smaller representation of repeated AI context before trusting it. It preserves the original, checks that protected instructions, code, schemas, and data survive exactly, measures the real token saving after overhead, and leaves reproducible evidence of every check.

**Maturity:** experimental alpha verification layer. It does not claim to prove natural-language meaning, automatically enable compression, or authorize semantic-cache hits.

## Engineering principles

- **Configuration over hardcoding** — models, providers, policies, and infrastructure should be replaceable without redesigning the product.
- **Explicit contracts** — clear boundaries and verifiable outcomes make complex systems safer to change.
- **Local-first where it matters** — privacy, cost control, reproducibility, and offline use are product capabilities.
- **Evidence before claims** — tests, evaluations, and operational records should support every important guarantee.
- **Useful to people** — technical novelty matters only when its real-world benefit can be explained plainly.

## Broader experience

My background spans full-stack development, microservices, distributed systems, data engineering, cloud-native architecture, and applied AI. I also have a research background in security and privacy for IoT systems.

Current interests: `Agentic AI` · `Local AI` · `Distributed Inference` · `MCP` · `Data Platforms` · `Cloud Native` · `Python` · `TypeScript` · `Java / Spring` · `React`

## Connect

The best place to reach me and follow my professional work is [LinkedIn](https://www.linkedin.com/in/antonio-antenore-a9b44a107/).
