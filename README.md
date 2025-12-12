# Hi, I'm Benedikt Eickhoff (@Contexter)

MIDI 2.0 + GPU builder and lead for the Fountain-Coach org (FountainAI stack).

- Running Fountain-Coach (63 repos; 56 public; Swift-first with Python glue) focused on the MIDI 2.0 backplane, GPU rendering, and stage/runtime instruments.
- Current builds: `midi2-gpu-fabric` (GPU-resident MIDI 2.0 runtime), `midi-backplane` (IDL + telemetry contract), `FountainKit`/`LocalAgent` (offline LLM + store/runtime loop), `Fountain-Store` (embedded store) and stage clients (teatro-stage-web, stage-native).
- Tooling bias: Swift 6, Python, SwiftPM, Metal/MTK, MIDI 2.0 UMP+CI/PE, Typesense; telemetry-first runtime loops with chunk tracking, budgets, and resume tokens on by default.

## Org snapshot — Fountain-Coach

- Inventory: 63 repos (56 public / 7 private / 3 archived); primary languages: Swift (33), Python (11), then small HTML/Shell/C/C++/TypeScript.
- Latest pushes center on `midi2-gpu-fabric`, `midi-backplane`, the org site, and rig/scene tooling; stage/semantic daemons stay active for telemetry + awareness.
- Operating principles: contract-first via `@fountain-coach/midi-backplane@1.0.0`, no OpenAPI for backplane topics, telemetry wired to FountainStore, strict resume + chunk sequencing.

## Personal footprint — @Contexter

- 54 repos (42 public / 12 private / 6 archived); most in Python and Swift spanning orchestration proxies, FastAPI/Vapor bridges, and MIDI/Teatro experiments.
- Recent work: Teatro/TeatroKit, FastAPI-SwarmUI, and codex-driven FountainAI automation.

## What I'm shipping now

- Finalizing the GPU MIDI 2.0 fabric with backplane-aligned telemetry and budget enforcement.
- Keeping stage clients (web/native) green with render snapshots and scene telemetry.
- Hardening the semantic daemon + store seeding so new instruments stay discoverable.

## Links

- Org: https://github.com/Fountain-Coach
- Projects: https://github.com/Fountain-Coach/midi2-gpu-fabric | https://github.com/Fountain-Coach/midi-backplane | https://github.com/Fountain-Coach/FountainKit
- Personal: https://github.com/Contexter
