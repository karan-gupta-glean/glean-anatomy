# Anatomy of Glean AI

A visual, interactive reference page that maps out the full architecture of [Glean AI](https://www.glean.com) — presented as a developer-friendly file tree.

**Live site:** [karan-gupta-glean.github.io/glean-anatomy](https://karan-gupta-glean.github.io/glean-anatomy/)

## What is this?

This is a single-page explainer that breaks down every major component of the Glean AI platform into a tree-style diagram — the same way you'd explore a codebase. Each "folder" represents a product area, and each "file" is a specific capability with a short description.

It covers:

| Section | What it explains |
|---------|-----------------|
| **connectors/** | 100+ integrations that index company data (docs, messages, CRM, code, structured data) |
| **enterprise-graph/** | The intelligence layer — entity extraction, relationship mapping, personal graph, enterprise memory |
| **people/** | Org intelligence — org chart, expertise finder, personal graph |
| **assistant/** | Glean's third-generation AI assistant — chat, search, canvas, voice, branded slides, proactive insights |
| **model-hub/** | LLM choice across 15+ models with fast vs. thinking modes |
| **skills/** | The open Agent Skills standard — personal, company, and ecosystem-level reusable instructions |
| **agents/** | Workflow automation — no-code builder, agentic engine 2, orchestration, pre-built agents, embedded integrations |
| **agent-sandbox/** | Secure isolated runtime (AFS) with filesystem, shell, code interpreter, and programmatic tool calling (PTC) |
| **governance/** | Data scanning, infotype detection, agent permissions, security partner ecosystem |
| **mcp + api/** | MCP server/host/directory, 100+ native actions, tool search, REST API, 3rd-party agent registry |

## Who is this for?

- SEs and SAs demoing Glean's architecture
- Internal teams needing a quick visual reference
- Anyone who wants to understand how Glean's pieces fit together

## How to update

It's a single `index.html` file — just edit and push. Hosted via GitHub Pages from the `main` branch.

## Deployment

Pushes to `main` automatically deploy to GitHub Pages. No build step required.
