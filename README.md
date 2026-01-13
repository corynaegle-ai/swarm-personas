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
| Beverly Sanders | Persona Architect - Use for generating other Personas | [beverly-sanders-persona-architect.md](./beverly-sanders-persona-architect.md) |
| Dr. Meridian Voss | Persona Engineer - Code-generating agent personas (PRISM Framework) | [dr-meridian-voss-persona-engineer.md](./dr-meridian-voss-persona-engineer.md) |
| Alex Chen | Systems Architecture / Backend / Infrastructure (VALIDATE Framework) | [alex-chen-systems-architect.md](./alex-chen-systems-architect.md) |
| Marcus Chen | Frontend / React Dashboard Optimization (RENDER Framework) | [marcus-chen-frontend-architect.md](./marcus-chen-frontend-architect.md) |
| Dr. Ramesh Krishnamurthy | Distributed Systems / Agent Coordination (COORDINATE Framework) | [ramesh-krishnamurthy-distributed-systems.md](./ramesh-krishnamurthy-distributed-systems.md) |
| Viktor Holmgren | Infrastructure / Firecracker MicroVM Specialist (ISOLATE Framework) | [viktor-holmgren-infrastructure-engineer.md](./viktor-holmgren-infrastructure-engineer.md) |
| Ekaterina "Kat" Volkov | Security Engineering / Zero-Trust Architecture (CASTLE Framework) | [ekaterina-volkov-security-engineer.md](./ekaterina-volkov-security-engineer.md) |
| Dr. Priya Ramachandran | AI/ML Engineering / Agent Evaluation (PRISM Framework) | [priya-ramachandran-aiml-engineer.md](./priya-ramachandran-aiml-engineer.md) |
| David Nakamura | Product Management / Roadmap Strategy (PRIORITIZE Framework) | [david-nakamura-product-manager.md](./david-nakamura-product-manager.md) |
| Sarah Okonkwo | Technical Writing / Developer Experience (DOCUMENT Framework) | [sarah-okonkwo-technical-writer.md](./sarah-okonkwo-technical-writer.md) |
| Elena Vasquez | UX Architecture / Workflow Design (WORKFLOW Framework) | [elena-vasquez-ux-architect.md](./elena-vasquez-ux-architect.md) |

## Usage

1. Select the appropriate persona for your task
2. Copy the persona definition into your system prompt
3. Append your specific task/question

### Quick Selection Guide

| Task Type | Recommended Persona |
|-----------|---------------------|
| **Backend & Infrastructure** | |
| Database schema design | Alex Chen |
| API architecture | Alex Chen |
| CI/CD pipelines | Alex Chen |
| Firecracker/VM orchestration | Viktor Holmgren |
| Distributed coordination | Dr. Ramesh Krishnamurthy |
| Security hardening | Ekaterina "Kat" Volkov |
| Secrets management | Ekaterina "Kat" Volkov |
| **Frontend & Design** | |
| React performance | Marcus Chen |
| WebSocket integration | Marcus Chen |
| Dashboard UI/UX | Elena Vasquez |
| Workflow builder design | Elena Vasquez |
| State management | Marcus Chen |
| **AI/ML & Agents** | |
| LLM agent evaluation | Dr. Priya Ramachandran |
| Prompt engineering | Dr. Priya Ramachandran |
| Agent persona design | Dr. Meridian Voss or Beverly Sanders |
| Multi-agent orchestration | Dr. Ramesh Krishnamurthy |
| **Product & Documentation** | |
| Feature specifications | David Nakamura |
| Roadmap prioritization | David Nakamura |
| API documentation | Sarah Okonkwo |
| Developer guides | Sarah Okonkwo |
| **Full-Stack Projects** | |
| End-to-end system | Alex Chen (backend) + Marcus Chen (frontend) |
| Developer tool UX | Elena Vasquez + Marcus Chen |
| Secure multi-tenant | Alex Chen + Ekaterina Volkov |

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

## Framework Reference

Each persona has a named methodology framework:

| Persona | Framework | Steps |
|---------|-----------|-------|
| Beverly Sanders | PERSONA | 7-step general persona design |
| Dr. Meridian Voss | PRISM | 5-step code-agent persona design |
| Alex Chen | VALIDATE | 8-step backend system architecture |
| Marcus Chen | RENDER | 6-step React optimization |
| Dr. Ramesh Krishnamurthy | COORDINATE | 10-step distributed coordination |
| Viktor Holmgren | ISOLATE | 7-step VM orchestration |
| Ekaterina Volkov | CASTLE | 6-step security architecture |
| Dr. Priya Ramachandran | PRISM | 5-step agent evaluation |
| David Nakamura | PRIORITIZE | 10-step product management |
| Sarah Okonkwo | DOCUMENT | 8-step technical writing |
| Elena Vasquez | WORKFLOW | 8-step UX workflow design |

## Related

- Part of the [Project Swarm](https://github.com/corynaegle-ai) ecosystem
- Used by Swarm worker agents for specialized code generation tasks
- Personas can be combined for multi-domain tasks
