# CCC - Claude Code Collection

A comprehensive collection of **Claude Code skills, agents, and plugins** that extend Claude's capabilities with specialized workflows, document processing, creative design, and productivity tools.

## Quick Start

```bash
# Add the marketplace
/plugin marketplace add arush/ccc

# Install skills
/plugin install ccc-skills@ccc

# Install the product management plugin
/plugin install product-management@ccc
```

## What's Inside

### Skills (19)

#### Document Processing
| Skill | Description |
|-------|-------------|
| **xlsx** | Create, edit, and analyze Excel spreadsheets with formulas, formatting, and charts |
| **docx** | Generate and edit Word documents with precise XML-based formatting |
| **pptx** | Build and edit PowerPoint presentations with markdown extraction |
| **pdf** | Read, merge, split, watermark, OCR, and fill PDF forms |

#### Creative & Design
| Skill | Description |
|-------|-------------|
| **algorithmic-art** | Generate p5.js generative art with seeded randomness and particle systems |
| **canvas-design** | Create visual art and posters as .pdf/.png using design philosophy |
| **frontend-design** | Build production-grade web components and pages (React, HTML/CSS) |
| **brand-guidelines** | Apply Anthropic's official brand colors and typography |
| **theme-factory** | 10 pre-set professional themes applicable to any artifact |

#### Productivity
| Skill | Description |
|-------|-------------|
| **doc-coauthoring** | Structured workflow for collaborative documentation |
| **internal-comms** | Templates for status reports, newsletters, FAQs, incident reports |
| **mcp-builder** | Guide for creating MCP servers in Python or Node.js |
| **skill-creator** | Framework for designing and building new Claude Code skills |
| **slack-gif-creator** | Generate optimized animated GIFs for Slack |
| **web-artifacts-builder** | React + Tailwind + shadcn/ui for complex HTML artifacts |
| **webapp-testing** | Playwright-based browser automation for testing web apps |
| **excalidraw** | Generate architecture diagrams with optional PNG/SVG export |
| **product-management** | Lightweight PM skill for product analysis and planning |

### Plugins

#### Product Management
AI-native product management for startups. Includes 6 slash commands and 6 specialized agents.

| Command | Purpose |
|---------|---------|
| `/pm:analyze` | Scan codebase and interview for product understanding |
| `/pm:landscape` | Research the competitive landscape |
| `/pm:gaps` | Identify and score feature gaps using the WINNING filter |
| `/pm:file` | Batch create GitHub Issues from scored gaps |
| `/pm:prd` | Generate a full PRD for a feature |
| `/pm:sync` | Sync current state with GitHub Issues |

**WINNING Score:** `Pain x Timing x Execution Capability` — 40-60 FILE, 25-39 WAIT, 0-24 SKIP

**Agents** (bundled with the plugin):

| Agent | Trigger |
|-------|---------|
| **6-pager** | Write comprehensive executive documents |
| **database-query-builder** | Generate and optimize database queries |
| **incident-investigator** | Root cause analysis and incident investigation |
| **requirements-refiner** | Iteratively refine technical requirements and specs |
| **gap-analyst** | Identify and analyze product feature gaps |
| **research-agent** | Research competitors and market landscape |

## Repository Structure

```
ccc/
├── .claude-plugin/
│   └── marketplace.json        # Marketplace configuration
├── skills/                     # 19 reusable skills
│   ├── algorithmic-art/
│   ├── brand-guidelines/
│   ├── canvas-design/
│   ├── doc-coauthoring/
│   ├── docx/
│   ├── excalidraw/
│   ├── frontend-design/
│   ├── internal-comms/
│   ├── mcp-builder/
│   ├── pdf/
│   ├── pptx/
│   ├── product-management/
│   ├── skill-creator/
│   ├── slack-gif-creator/
│   ├── theme-factory/
│   ├── web-artifacts-builder/
│   ├── webapp-testing/
│   └── xlsx/
└── plugins/
    └── product-management/     # Full PM plugin with commands & agents
```

## Technologies

- **Documents:** openpyxl, python-docx, python-pptx, pypdf, reportlab
- **Creative:** p5.js, ReportLab, React, Tailwind CSS, shadcn/ui
- **Automation:** Playwright, GitHub CLI
- **Integration:** MCP (Model Context Protocol), Slack API

## Author

**arush** - arush361@gmail.com
