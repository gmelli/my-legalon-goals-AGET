# my-legalon-goals-AGET

> **Goal management agent for GM-LEGALON portfolio**

AI-assisted agent for managing organizational goals and backgrounder documents. Action-taking agent (-AGET) that can modify goals, update documentation, and track progress.

**Current Version**: v2.5.1
**Domain**: goal-management
**Portfolio**: GM-LEGALON
**Managed by**: my-supervisor-AGET

---

## Purpose

This agent manages:
- **Organizational goals** - Strategic objectives, milestones, tracking
- **Backgrounder documents** - Context, history, reference materials
- **Goal relationships** - Dependencies, hierarchies, progress

---

## Directory Structure

```
my-legalon-goals-AGET/
├── AGENTS.md              # Agent configuration
├── .aget/                 # Framework metadata
│   ├── version.json       # Agent identity
│   ├── evolution/         # Learnings (L*.md)
│   └── checkpoints/       # State snapshots
├── data/
│   ├── goals/             # Goal definitions and tracking
│   └── backgrounders/     # Reference documents
├── workspace/             # Exploration and drafts
├── products/              # Published reports
├── docs/                  # Documentation
└── sessions/              # Session notes
```

---

## Quick Start

```bash
cd ~/github/GM-LEGALON/my-legalon-goals-AGET
claude .
```

```
You: wake up

Agent: my-legalon-goals-AGET v2.5.1 (Goal Management)
       Ready for goal management tasks.

You: show current goals

Agent: [Reads data/goals/, presents organized view]

You: wind down

Agent: [Commits changes, creates session notes]
```

---

## Capabilities

- **Goal lifecycle management** - Create, update, archive goals
- **Backgrounder maintenance** - Organize reference documents
- **Progress tracking** - Monitor goal completion
- **Reporting** - Generate goal status reports
- **Cross-referencing** - Link goals to backgrounders

---

## Framework

Built on [Aget Framework](https://github.com/aget-framework/template-worker-aget) v2.5.1

**Naming convention**: `-AGET` suffix indicates action-taking capability (can modify systems)

---

## License

Apache 2.0
