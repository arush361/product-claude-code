# Product Claude Code

**A PM's toolkit for Claude Code**, built over 3 months of hands-on product management. Turn Claude into your product co-pilot — run competitive analysis, score feature gaps, write PRDs, generate stakeholder decks, and draft exec-ready documents, all from your terminal.

## Product Management Plugin

Your day-to-day PM workflows, automated. Six slash commands that take you from codebase to shipped issues.

| Command | What it does |
|---------|-------------|
| `/pm:analyze` | Scan the codebase and build product context through guided interviews |
| `/pm:landscape` | Research competitors — pulls positioning, pricing, and feature sets |
| `/pm:gaps` | Identify feature gaps and score them with the WINNING filter |
| `/pm:file` | Turn scored gaps into GitHub Issues in bulk |
| `/pm:prd` | Generate a full PRD for any feature |
| `/pm:sync` | Keep your local state in sync with GitHub Issues |

**WINNING Score:** `Pain x Timing x Execution Capability` — 40-60 FILE, 25-39 WAIT, 0-24 SKIP

## Specialized Agents

Agents that handle the heavy lifting so you can focus on decisions.

| Agent | When to use it |
|-------|---------------|
| **6-pager** | Write Amazon-style narrative memos for leadership reviews |
| **requirements-refiner** | Turn vague ideas into detailed, testable requirements |
| **gap-analyst** | Deep-dive into product feature gaps with structured analysis |
| **research-agent** | Competitive and market research with sourced findings |
| **incident-investigator** | Root cause analysis when production breaks |
| **database-query-builder** | Pull the data you need without writing SQL from scratch |

## Quick Start

```bash
# Add the marketplace
/plugin marketplace add arush361/product-claude-code

# Install everything
/plugin install product-management@arush-claude-toolkit
/plugin install document-skills@arush-claude-toolkit
/plugin install creative-skills@arush-claude-toolkit
/plugin install productivity-skills@arush-claude-toolkit
```

## Document & Deck Creation

Create the artifacts PMs live in — decks, docs, spreadsheets, and PDFs — without leaving Claude.

| Skill | Use case |
|-------|---------|
| **pptx** | Build stakeholder decks, sprint reviews, and pitch presentations |
| **docx** | Write specs, memos, and strategy docs with proper formatting |
| **xlsx** | Create prioritization matrices, roadmap spreadsheets, and data analysis |
| **pdf** | Merge docs, fill forms, extract data from PDFs |

## Communication & Storytelling

| Skill | Use case |
|-------|---------|
| **internal-comms** | Status reports, leadership updates, newsletters, FAQs, incident reports |
| **doc-coauthoring** | Structured co-writing workflow for specs, proposals, and decision docs |
| **excalidraw** | Architecture diagrams and system visualizations with PNG/SVG export |
| **slack-gif-creator** | Animated GIFs for Slack — celebrate launches, explain features |

## Design & Prototyping

| Skill | Use case |
|-------|---------|
| **frontend-design** | Prototype landing pages, dashboards, and UI components |
| **canvas-design** | Create posters, visual assets, and one-pagers |
| **theme-factory** | Apply 10 professional themes to any artifact |
| **brand-guidelines** | Keep everything on-brand with Anthropic's design system |
| **algorithmic-art** | Generative art for presentations and marketing |
| **web-artifacts-builder** | Complex interactive prototypes with React + Tailwind + shadcn/ui |

## Developer-Facing Skills

| Skill | Use case |
|-------|---------|
| **webapp-testing** | Validate features with Playwright browser automation |
| **mcp-builder** | Build MCP servers to integrate external tools |
| **skill-creator** | Create new Claude Code skills for your team |

## Repository Structure

```
product-claude-code/
├── .claude-plugin/
│   └── marketplace.json          # Marketplace configuration
├── skills/                       # 19 skills organized by category
│   ├── xlsx/
│   ├── docx/
│   ├── pptx/
│   ├── pdf/
│   ├── frontend-design/
│   ├── canvas-design/
│   ├── theme-factory/
│   ├── brand-guidelines/
│   ├── algorithmic-art/
│   ├── doc-coauthoring/
│   ├── internal-comms/
│   ├── excalidraw/
│   ├── slack-gif-creator/
│   ├── web-artifacts-builder/
│   ├── webapp-testing/
│   ├── mcp-builder/
│   ├── skill-creator/
│   └── product-management/
└── plugins/
    └── product-management/       # Full PM plugin with commands & agents
```

## Author

**Arush** — [GitHub](https://github.com/arush361) | [LinkedIn](https://www.linkedin.com/in/sharma-arush/)
