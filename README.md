# Antonio Antenore

**AI Engineer · Software Architect · Open-source builder**

[LinkedIn](https://www.linkedin.com/in/antonio-antenore-a9b44a107/) · Turin, Italy

**I help product and engineering teams turn useful AI ideas into dependable products: private when they need to be, efficient enough to run in the real world, and clear enough for people to understand and trust.**

## A simple way to see my work

Imagine a team building an assistant for sensitive documents. It should keep private work on the right device, choose an expensive model only when a smaller local one is not enough, avoid loading the same model in every browser tab, and leave a readable record of what it decided and changed.

My projects explore each part of that journey as an independent, replaceable building block. They can be used separately: the goal is not one closed platform, but practical foundations that let teams change models, providers, policies, and infrastructure without rebuilding everything.

## Selected work

### [AgenticStrata](https://github.com/aantenore/AgenticStrata) — prove what an AI system actually did

It gives teams a reference architecture for AI agents whose actions must be understandable after the fact. Its contracts, evidence receipts, replay, plain-language explanations, and conformance checks help answer: *What was requested? Who or what was allowed to act? What happened? What evidence supports the result?*

**Maturity:** alpha reference implementation. It checks declared rules against supplied evidence; it is not a regulatory certification.

### [StageFabric](https://github.com/aantenore/stagefabric) — keep each AI step in the right place

It turns a multi-step AI task into an explainable plan across the browser, a local machine, the edge, or the cloud. Privacy rules can block forbidden data movement, fallbacks explain why another location was chosen, and content-free records show where successful work ran without copying the underlying data.

**Maturity:** experimental alpha with a deterministic planner and optional real-runtime execution. It is a reference planner, not a globally optimal scheduler.

### [myMoE](https://github.com/aantenore/myMoE) — use the right amount of intelligence for each task

It routes work among replaceable local models, keeps chat and memory local by default, applies explicit budgets and fallbacks, and can prepare a minimal handoff to a premium assistant only when policy and evidence justify it. The aim is to avoid paying the highest cost—or exposing data—for every request.

**Maturity:** alpha local control plane. Results are supported for its documented profiles and evaluations, not claimed as a universal win over every single-model setup.

### [TabLoom](https://github.com/aantenore/tabloom) — let browser tabs share one on-device AI runtime

Instead of every tab loading another copy of the same model, TabLoom coordinates one active owner. It manages queues, streaming, cancellation, safe takeover, and compatibility checks so sibling pages can share scarce device memory without becoming tied to one inference provider.

**Maturity:** alpha library. Its real WebLLM path is verified on Chrome with WebGPU, not across every browser, GPU, or model.

### [Agentic SDLC Codex Plugin](https://github.com/aantenore/agentic-sdlc-codex-plugin) — make coding-agent work readable and reviewable

It records what a person asked for, which assumptions and boundaries were agreed, what the agent decided and changed, and how the result was checked. The bundled Change Observatory turns that evidence into a visual timeline that product owners and technical reviewers can inspect together.

**Maturity:** installable, working Codex plugin. Its lineage covers work performed through the governed workflow; it does not make activity outside that boundary auditable.

### [MoveBeta](https://github.com/aantenore/movebeta-mobile) — private movement feedback for indoor climbers

It analyzes a short bouldering video on the device, points to one measurable movement to review, and helps the climber compare a focused repeat of the same climb. The video is not sent to a remote inference service, and the user can challenge, export, or delete the derived feedback.

**Maturity:** functional private beta based on 2D pose signals. It is not a coach or medical tool, and public store release still depends on real-device and human validation.

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
