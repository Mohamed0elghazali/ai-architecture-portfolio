# AI Architecture Portfolio

A structured portfolio documenting AI system architecture decisions, design patterns, and learning sessions. Each folder captures a different layer of the work — from initial framing through to a final capstone deliverable.

## Repository Structure

```
ai-architecture-portfolio/
├── README.md                      # This file — scenario, assumptions, and how to read the repo
├── docs/
│   ├── 01-session-ADD.md          # Session 01: governance pack (principles, ADRs, ARB, guardrails)
│   └── 02-building-blocks.md      # Session 02: building blocks
├── diagrams/
│   ├── 01-session-1.drawio        # Draw.io source file
│   ├── 01-session-1-as-is.png     # As-Is architecture diagram
│   └── 01-session-to-be.png       # To-Be architecture diagram
├── ADR/
│   └── 0001-model-hosting.md      # ADR: LLM hosting decision
└── capstone/                      # Final architecture document — PDF and/or presentation slides
```

## How to Read This Repo

1. **Start with `docs/`** — session notes are numbered and build on each other. Read them in order to follow the reasoning.
2. **Check `ADR/`** for key decisions. Each ADR explains the context, the options considered, and the rationale behind the chosen approach.
3. **Browse `diagrams/`** alongside the docs. Diagrams are referenced from session notes where relevant.
4. **The `capstone/`** folder brings everything together into a final deliverable.

