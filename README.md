# parallel_f-kicklang-wrapper

Thin OCS-compliant wrapper + C++ code generator for KickLang v4.2 Parallel DAG syntax.

Bridges your mature `parallel_f` C++ task-parallel library with the evolving KickLang / Orion Collective System (OCS) meta-infrastructure.

**Version:** 0.2.0-OCS

## Features

- Consumes KickLang `task_list`, `make_task`, `⫻flow/parallel` syntax
- Runtime delegation to `parallel_f`
- **C++ code generation** from KickLang DAGs (new in v0.2)
- Full OCS compliance (TAS lifecycle, three-agent core, consent gates, CoherenceMonitorBridge)
- Thin by design — heavy lifting stays in `parallel_f`

## Quick Start

See `SKILL.md` for full specification and examples.

## Repository

Part of Denis Oliver Kropp's meta-infrastructure evolution (2026).

Generated via `kicklang-evolution-predictor` + `ocs-skill-builder`.