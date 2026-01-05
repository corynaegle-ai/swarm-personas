# Swarm Personas

A collection of Structured Expert Personas (SEP) for priming LLM agents in the Swarm ecosystem.

## Purpose

LLMs perform significantly better when given specific personas with credentials, methodologies, and granular experience details. This repository contains battle-tested persona definitions that can be used to:

- Prime Claude agents for specialized tasks
- Ensure consistent expertise across Swarm worker agents
- Provide domain-specific mental models and frameworks

## The Chen Brothers

The flagship personas in this collection are **Alex and Marcus Chen**, brothers with complementary skills who together cover the full stack:

| Brother | Domain | Strength |
|---------|--------|----------|
| **Alex Chen** | Backend/Infrastructure | Distributed systems, databases, security, DevOps |
| **Marcus Chen** | Frontend/UI | React performance, real-time dashboards, WebSocket optimization |

*They frequently collaborate on full-stack projects, with Alex designing robust backend systems while Marcus ensures the frontend is performant and user-friendly.*

## Persona Catalog

| Persona | Domain | File |
|---------|--------|------|
| Alex Chen | Systems Architecture / Backend / Infrastructure | [alex-chen-systems-architect.md](./alex-chen-systems-architect.md) |
| Marcus Chen | Frontend / React Dashboard Optimization | [marcus-chen-frontend-architect.md](./marcus-chen-frontend-architect.md) |

## Usage

1. Select the appropriate persona for your task
2. Copy the persona definition into your system prompt
3. Append your specific task/question

### Quick Selection Guide

| Task Type | Recommended Persona |
|-----------|---------------------|
| Database schema design | Alex Chen |
| API architecture | Alex Chen |
| Security hardening | Alex Chen |
| CI/CD pipelines | Alex Chen |
| VM orchestration | Alex Chen |
| React performance | Marcus Chen |
| WebSocket integration | Marcus Chen |
| Dashboard UI/UX | Marcus Chen |
| State management | Marcus Chen |
| Full-stack project | Both (Alex backend, Marcus frontend) |

## Structured Expert Persona Format

When adding new personas, follow this format:

- **Identity:** Name + Title + Personal connections (e.g., sibling relationships)
- **Credentials:** Degrees, certifications, years of experience, notable work
- **Methodology:** Named step-by-step framework they ALWAYS use
- **Mental Models:** Core principles that guide decisions (5-7 key beliefs)
- **Tech Stack Preferences:** Opinionated table of technology choices
- **Tone/Voice:** How they communicate
- **Anti-Patterns:** What they reject and why
- **Prompt Template:** Ready-to-use block for summoning the persona

## Related

- Part of the [Project Swarm](https://github.com/corynaegle-ai) ecosystem
- Used by Swarm worker agents for specialized code generation tasks
- Personas can be combined for multi-domain tasks
