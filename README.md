# Antonio Antenore

**AI Engineer · Software Architect · Open-source builder**

[LinkedIn](https://www.linkedin.com/in/antonio-antenore-a9b44a107/) · Turin, Italy

**I help product and engineering teams turn useful AI ideas into dependable products: private when they need to be, efficient enough to run in the real world, and clear enough for people to understand and trust.**

## A simple way to see my work

Imagine a team building an assistant for sensitive documents. It should keep private work on the right device, choose an expensive model only when a smaller local one is not enough, survive an approval or restart without doing the same work twice, avoid loading the same model in every browser tab, and leave a readable record of what it decided and changed.

My projects explore each part of that journey as an independent, replaceable building block. They can be used separately: the goal is not one closed platform, but practical foundations that let teams change models, providers, policies, and infrastructure without rebuilding everything.

## How these projects happen

When an idea crosses my mind, I build it. Not because I am sure it will work, but because that is the fastest way to find out where it breaks. Every repository here is a small lab: an idea, an implementation, and a pile of problems I only discovered by trying.

Fair warning: I cannot promise that everything you find here works. I can promise that every problem I ran into while building them got solved, and whatever is still unproven is spelled out in each project's maturity notes. Think of these projects less as finished products and more as maps of the traps, drawn by someone who stepped on most of them first.

## Selected work

| Project | Real-world impact | Maturity |
| --- | --- | --- |
| [myMoE](https://github.com/aantenore/myMoE) | Helps a coding assistant send suitable tasks to local models, accept only results that pass a deterministic check, and keep control of exactly which local program and model were launched. It will not silently reuse an existing server and verifies that its own process and network port are closed afterward. | Installable alpha (v0.16.0-alpha.1). Routing, receipts, and process supervision are contract-tested; a real macOS canary verified launch, process/model identity checks, and cleanup without running inference. The checks are sampled observations on POSIX systems, not a security sandbox: another program running as the same user is outside the guarantee, and the runtime's network silence is not proved. Live model quality and end-to-end token or cost savings remain unproven. |
| [AgenticStrata](https://github.com/aantenore/AgenticStrata) | Turns an AI run into a checkable record of what was requested, allowed, changed, and observed; its optional Sigstore verifier can confirm that a trusted signer signed that exact record. | Executable alpha reference architecture. Unsigned records prove consistency, not identity; each deployment still owns its trust roots, revocation, and production policy. |
| [SemWitness](https://github.com/aantenore/semwitness) | Measures token-saving transformations while preserving protected instructions, code, schemas, and reproducible evidence. | Experimental alpha; it does not prove natural-language equivalence or authorize cache hits. |
| [PauseMesh](https://github.com/aantenore/pausemesh) | Lets a long-running assistant survive approval waits, disconnects, restarts, and duplicate callbacks without continuing twice. | Alpha runtime; external effects still need the documented idempotency contract. |
| [TabLoom](https://github.com/aantenore/tabloom) | Lets browser tabs share one on-device AI runtime instead of loading a separate model in every tab. | Installable alpha (v0.4.0-alpha.1). The real WebLLM path is verified on Chrome/WebGPU only. |
| [TruthLease](https://github.com/aantenore/truthlease) | Stops an AI agent from acting on a plan after the facts or target it depended on have changed. | Installable alpha (v0.3.0-alpha.1). It fences the final commit and supports stale-safe LangGraph resume; external systems still require their own transaction and idempotency controls. |

## Active experiments

- [StageFabric](https://github.com/aantenore/stagefabric) plans each AI step across browser, local, edge, or cloud locations while blocking forbidden data movement. It is an experimental alpha planner, not a globally optimal scheduler.
- [LocusMesh](https://github.com/aantenore/LocusMesh) checks whether a distributed AI route stays within an operator-approved boundary. It is experimental alpha and does not yet prove that a peer performed the claimed computation.
- [IntentABI](https://github.com/aantenore/intentabi) measures whether differently worded requests can converge on the same typed intent before anyone enables semantic caching. It is alpha, shadow-only, and never serves a cached answer.
- [WITShift](https://github.com/aantenore/witshift) turns a narrow TypeScript MCP tool into a reviewable WebAssembly Component candidate and compares its behavior with the original. It is alpha and intentionally rejects tools outside its bounded source subset.
- [Semantic Junkyard](https://github.com/aantenore/semantic-junkyard) connects knowledge in files, databases, and Git while keeping the original sources authoritative. It is a local-first reference product, not a production multi-tenant platform.
- [reinloop](https://github.com/aantenore/reinloop) lets a team define an AI agent, or a team of agents, as a Markdown file and run it on any model, with budgets, permissions, crash-safe resume, and MCP built in. It is a 0.x release with no runtime dependencies; its shell tool is confined to a directory but is not a sandbox.
- [IMPOSBRO Search](https://github.com/aantenore/imposbro-search) gives an application one search API over separate Typesense clusters, with durable indexing, safe routing migrations, and recovery controls. It does not claim that a deployment is certified, highly available, or compliant by itself; that depends on the operator's infrastructure and evidence.
- [ThreadSwarm](https://github.com/aantenore/ThreadSwarm) splits a complex local job into a validated graph of small steps, runs independent steps in parallel worker processes, and records retries and outcomes. It is a single-machine runtime, not a distributed scheduler or an autonomous agent swarm.

## Working product experiments

- [MoveBeta](https://github.com/aantenore/movebeta-mobile) helps indoor climbers review one measurable movement signal on-device and compare a focused repeat without uploading video. The PWA is a private beta; its pose signals are not coaching or medical advice.
- [FreeJoy](https://github.com/aantenore/FreeJoy) turns phones into up to four Windows game controllers through one QR code. Host and controller links stay separate, and each phone receives a revocable reconnect lease, so a refresh can recover its slot without gaining room administration. It is a CI-tested Windows/Ryujinx prototype; a real PC-and-phone latency and reconnect session is still required before calling it consumer-ready.

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
