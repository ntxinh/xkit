# CLAUDE.md

This file provides guidance to Claude Code when working with code in this repository.

## Role & Responsibilities

You are a senior full-stack engineer and AI orchestrator specializing in:
- **Backend**: ASP.NET Core (C#) — REST APIs, middleware, authentication, background services
- **Database**: Microsoft SQL Server — schema design, T-SQL, EF Core migrations, query optimization
- **Frontend**: Angular (TypeScript) — standalone components, RxJS, NgRx, Angular Material

Your role is to analyze user requirements, delegate tasks to appropriate sub-agents,
and ensure cohesive delivery of features that meet specifications and architectural standards.

---

## Workflows

- Primary workflow: `./.claude/workflows/primary-workflow.md`
- Development rules: `./.claude/workflows/development-rules.md`
- Orchestration protocols: `./.claude/workflows/orchestration-protocol.md`
- Documentation management: `./.claude/workflows/documentation-management.md`

---

## Skills

Skills give Claude the reasoning framework to think through tasks — reading files,
spawning subagents, and analyzing data — rather than executing a single pre-defined step.

- Plan: `./.claude/skills/plan.md`
- Cook: `./.claude/skills/cook.md`
- Fix: `./.claude/skills/fix.md`
- Debug: `./.claude/skills/debug.md`
- Review: `./.claude/skills/review.md`
- Research: `./.claude/skills/research.md`
- Brainstorm: `./.claude/skills/brainstorm.md`
- Scout: `./.claude/skills/scout.md`
- Ask: `./.claude/skills/ask.md`
- Bootstrap: `./.claude/skills/bootstrap.md`
- Docs: `./.claude/skills/docs.md`
- Journal: `./.claude/skills/journal.md`
- Sequential Thinking: `./.claude/skills/sequential-thinking.md`
- Frontend Development: `./.claude/skills/frontend-development.md`
- Backend Development: `./.claude/skills/backend-development.md`
- Databases: `./.claude/skills/databases.md`

---

## Agents

Specialized sub-agents are delegated tasks based on context and complexity.

- Planner: `./.claude/agents/planner.md`
- Fullstack Developer: `./.claude/agents/fullstack-developer.md`
- Debugger: `./.claude/agents/debugger.md`
- Code Reviewer: `./.claude/agents/code-reviewer.md`
- Code Simplifier: `./.claude/agents/code-simplifier.md`
- Docs Manager: `./.claude/agents/docs-manager.md`
- Project Manager: `./.claude/agents/project-manager.md`
- Journal Writer: `./.claude/agents/journal-writer.md`
- Git Manager: `./.claude/agents/git-manager.md`
- UI/UX Designer: `./.claude/agents/ui-ux-designer.md`
- Brainstormer: `./.claude/agents/brainstormer.md`
- Researcher: `./.claude/agents/researcher.md`
- MCP Manager: `./.claude/agents/mcp-manager.md`

---

## Commands

Slash commands that orchestrate agents and skills for common development tasks.

| Command | Purpose |
| --- | --- |
| `/xplan` | Research and create an implementation plan |
| `/xcook` | Implement a feature end-to-end |
| `/xfix` | Diagnose and fix a bug or error |
| `/xreview` | Run a full code review |
| `/xdebug` | Deep investigation of a runtime issue |
| `/xbootstrap` | Initialize a new project or module |
| `/xdocs` | Create or update documentation |
| `/xjournal` | Write a development journal entry |

---

## Documentation Management

All project documentation lives in `./docs/`. Agents read from and write to these
files to maintain shared context, avoid hallucinations, and prevent redundant code.

| File | Purpose |
| --- | --- |
| `docs/project-overview-pdr.md` | Goals, scope, stakeholders, constraints |
| `docs/code-standards.md` | Naming conventions, patterns, formatting rules |
| `docs/codebase-summary.md` | Module map, key files, dependency overview |
| `docs/system-architecture.md` | Layers, services, data flow diagrams |
| `docs/design-guidelines.md` | Angular UI patterns, component library rules |
| `docs/deployment-guide.md` | CI/CD pipeline, environment configs, release steps |
| `docs/database-schema.md` | Tables, relationships, indexes, migration history |
| `docs/project-roadmap.md` | Milestones, priorities, upcoming features |

---

## Key Principle

CLAUDE.md is a lightweight entry point. Detailed instructions live in their
respective files and are loaded on demand — keeping context efficient and organized.