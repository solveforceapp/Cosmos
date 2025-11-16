# Copilot Instructions for cosmos.solveforce.com

## Project Overview
This project is a structured knowledge base organized as a content repository, likely for a documentation site or digital encyclopedia. The main content is under `content/`, divided into thematic subfolders:
- `communication/` — Data, language, networks, text, and voice
- `cosmos/` — Foundational concepts, laws, and semantic architecture
- `cybernetics/` — Bio, ethical, and machine cybernetics
- `glossary/` — Definitions of key terms
- `infrastructure/` — Cloud, data centers, edge, energy, quantum
- `intelligence/` — AI, ML, NLP, deep learning, recursion
- `services/` — Telecom, cloud, security, connectivity

## Key Patterns & Conventions
- **All content is in Markdown (`.md`) files.**
- Each subfolder represents a domain or topic area. Files are atomic knowledge units.
- File and folder names are lowercase, hyphen-separated, and descriptive.
- No code, build, or test automation is present—this is a pure content repository.
- Cross-referencing between files is likely done via Markdown links (e.g., `[see glossary](../glossary/cosmos.md)`).
- Glossary entries are single-term files for easy linking and lookup.

## Authoring Guidelines
- **Add new topics as new `.md` files** in the appropriate subfolder.
- **Update existing topics** by editing the relevant Markdown file. Keep each file focused on a single concept.
- **Link related concepts** using relative Markdown links to other files in the repo.
- **Follow the existing naming conventions** for files and folders.
- **Do not add code, scripts, or non-Markdown files.**

## Examples
- To add a new AI concept, create `content/intelligence/new-concept.md`.
- To reference the definition of "cosmos" in another file: `[cosmos](../glossary/cosmos.md)`

## Key Files & Directories
- `content/` — Root of all knowledge content
- `content/glossary/` — Canonical definitions
- `content/cosmos/semantic-architecture.md` — Explains the structural philosophy

## What Not To Do
- Do not introduce programming code, build systems, or automation.
- Do not change file/folder naming conventions.
- Do not add non-content files (e.g., images, PDFs, scripts).

---
For questions about structure or content, review the `content/` directory and its subfolders for examples.

---
Contact: Cosmos Knowledge Base — SolveForce  
Email: contact@solveforce.com  
For corrections or suggestions, please open an issue in the repository.
---
