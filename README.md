# Agent System - 3-Layer Architecture

This repository is organized according to the 3-layer architecture defined in [AGENTE6.md](AGENTE6.md).

## Structure

- `directives/`: Contains Standard Operating Procedures (SOPs) in Markdown. These define **what** to do.
- `orchestration/`: That's the AI agent (you). Responsible for **how** to route between directives and execution.
- `execution/`: Contains deterministic Python scripts. These define **how** the work is actually performed.
- `.tmp/`: Workspace for intermediate files.

## Mirrored Instructions
The main instructions are mirrored across:
- [CLAUDE.md](CLAUDE.md)
- [AGENTS.md](AGENTS.md)
- [GEMINI.md](GEMINI.md)

## Getting Started
1. Define a new directive in `directives/`.
2. Implement the corresponding execution script in `execution/`.
3. Use the AI agent to orchestrate the process.
"# InstitutoNadar" 
