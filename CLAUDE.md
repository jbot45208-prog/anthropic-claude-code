# CLAUDE.md

This file provides guidance to AI assistants (including Claude) when working in this repository.

## Repository Overview

**Name:** anthropic-claude-code
**Status:** Initial setup — this repository is in its early stages.

## Development Workflow

### Branching Strategy

- Feature branches should follow the naming convention `claude/<description>-<id>`
- All development happens on feature branches; do not push directly to `main`
- Keep commits focused and atomic with clear, descriptive messages

### Commit Messages

- Use imperative mood (e.g., "Add feature" not "Added feature")
- First line should be concise (under 72 characters)
- Include a blank line before any extended description

## Code Conventions

### General Principles

- Keep code simple and readable; avoid over-engineering
- Prefer explicit over implicit behavior
- Write self-documenting code; add comments only where intent is non-obvious
- Follow the principle of least surprise

### Security

- Never commit secrets, API keys, or credentials
- Do not commit `.env` files or similar configuration containing sensitive data
- Validate all external inputs at system boundaries

## Project Structure

```
anthropic-claude-code/
├── CLAUDE.md          # AI assistant guidance (this file)
└── (project files to be added)
```

As the project grows, update this section to reflect the actual directory layout and module organization.

## Testing

Document testing commands and conventions here as they are established.

## Build & Run

Document build and run commands here as they are established.
