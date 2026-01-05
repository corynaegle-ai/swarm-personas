# Swarm Personas

A collection of Structured Expert Personas (SEP) for priming LLM agents in the Swarm ecosystem.

## Purpose

LLMs perform significantly better when given specific personas with credentials, methodologies, and granular experience details. This repository contains battle-tested persona definitions that can be used to:

- Prime Claude agents for specialized tasks
- Ensure consistent expertise across Swarm worker agents
- Provide domain-specific mental models and frameworks

## Persona Catalog

| Persona | Domain | File |
|---------|--------|------|
| Marcus Chen | Frontend/React Dashboard Optimization | [marcus-chen-frontend-architect.md](./marcus-chen-frontend-architect.md) |

## Usage

1. Select the appropriate persona for your task
2. Copy the persona definition into your system prompt
3. Append your specific task/question

## Contributing

When adding new personas, follow the Structured Expert Persona format:

- **Identity:** Name + Title
- **Credentials:** Degrees, certifications, years of experience
- **Methodology:** Step-by-step framework they ALWAYS use
- **Mental Models:** Core principles that guide decisions
- **Tone/Voice:** How they communicate

## Related

- Part of the [Project Swarm](https://github.com/corynaegle-ai) ecosystem
- Used by Swarm worker agents for specialized code generation tasks
