# Antonio Antenore

**AI Engineer · Software Architect · Open-source builder**

[LinkedIn](https://www.linkedin.com/in/antonio-antenore-a9b44a107/) · Turin, Italy

**I help product and engineering teams turn useful AI ideas into dependable products: private when they need to be, efficient enough to run in the real world, and clear enough for people to understand and trust.**

## A simple way to see my work

Imagine a team building an assistant for sensitive documents. It should keep private work on the right device, choose an expensive model only when a smaller local one is not enough, survive an approval or restart without doing the same work twice, avoid loading the same model in every browser tab, and leave a readable record of what it decided and changed.

My projects explore each part of that journey as an independent, replaceable building block. They can be used separately: the goal is not one closed platform, but practical foundations that let teams change models, providers, policies, and infrastructure without rebuilding everything.

## Selected work

| Project | Real-world impact | Maturity |
| --- | --- | --- |
| [myMoE](https://github.com/aantenore/myMoE) | Tests the normal AI route against an option that uses fewer paid-model calls, then keeps the normal route unless separate checks and a human-approved trial allow the alternative. | Alpha and installable. Missing or invalid evidence always keeps the normal route; no real paired test has yet demonstrated savings, so no live trial has been approved. |
| [AgenticStrata](https://github.com/aantenore/AgenticStrata) | Turns an AI run into a checkable record of what was requested, allowed, changed, and observed; its optional Sigstore verifier can confirm that a trusted signer signed that exact record. | Executable alpha reference architecture. Unsigned records prove consistency, not identity; each deployment still owns its trust roots, revocation, and production policy. |
| [SemWitness](https://github.com/aantenore/semwitness) | Measures token-saving transformations while preserving protected instructions, code, schemas, and reproducible evidence. | Experimental alpha; it does not prove natural-language equivalence or authorize cache hits. |
| [PauseMesh](https://github.com/aantenore/pausemesh) | Lets a long-running assistant survive approval waits, disconnects, restarts, and duplicate callbacks without continuing twice. | Alpha runtime; external effects still need the documented idempotency contract. |
| [TabLoom](https://github.com/aantenore/tabloom) | Lets browser tabs share one on-device AI runtime instead of loading a separate model in every tab. | Alpha library; the real WebLLM path is verified on Chrome/WebGPU only. |
| [IMPOSBRO Search](https://github.com/aantenore/imposbro-search) | Gives applications one reliable search API across separate data clusters; indexing survives restarts and partial failures stay visible. | Self-hosted alpha with live multi-service recovery gates; a tagged public release is still pending. |

## Active experiments

- [StageFabric](https://github.com/aantenore/stagefabric) plans each AI step across browser, local, edge, or cloud locations while blocking forbidden data movement. It is an experimental alpha planner, not a globally optimal scheduler.
- [LocusMesh](https://github.com/aantenore/LocusMesh) checks whether a distributed AI route stays within an operator-approved boundary. It is experimental alpha and does not yet prove that a peer performed the claimed computation.
- [IntentABI](https://github.com/aantenore/intentabi) measures whether differently worded requests can converge on the same typed intent before anyone enables semantic caching. It is alpha, shadow-only, and never serves a cached answer.
- [WITShift](https://github.com/aantenore/witshift) turns a narrow TypeScript MCP tool into a reviewable WebAssembly Component candidate and compares its behavior with the original. It is alpha and intentionally rejects tools outside its bounded source subset.
- [Semantic Junkyard](https://github.com/aantenore/semantic-junkyard) connects knowledge in files, databases, and Git while keeping the original sources authoritative. It is a local-first reference product, not a production multi-tenant platform.

## Working product experiments

- [MoveBeta](https://github.com/aantenore/movebeta-mobile) helps indoor climbers review one measurable movement signal on-device and compare a focused repeat without uploading video. The PWA is a private beta; its pose signals are not coaching or medical advice.
- [FreeJoy](https://github.com/aantenore/FreeJoy) turns phones into up to four Windows game controllers through one QR code. Separate host and controller links keep player access away from room administration, while disconnects, timeouts, resets, and shutdown return active controllers to neutral. It is a working local-network prototype, not a broadly benchmarked or packaged consumer release.

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
