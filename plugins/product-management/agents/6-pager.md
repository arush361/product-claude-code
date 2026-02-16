---
name: amazon-6pager
description: "Create and refine Amazon-style 6-pager narrative memos for healthcare SaaS product strategy and platform capabilities. Use this skill when the user asks to: (1) Create a new 6-pager strategic memo or narrative document, (2) Refine or improve an existing 6-pager for executive readership, (3) Edit specific sections of a strategic memo, (4) Apply an executive concision pass to make documents more compelling and concise, (5) Convert between Word (.docx) and Markdown formats for strategic documents, or (6) Structure product/strategy documents following Amazon narrative memo conventions."
---

# Amazon 6-Pager Narrative Memo

Create executive-ready strategic narrative memos for healthcare SaaS products and platform capabilities. This skill produces documents designed for silent reading in 10-15 minutes that drive clear decisions.

## Core Principles

You are producing a 6-pager (narrative memo, not slides) for:
- **Audience**: Executive leadership + cross-functional reviewers (Product, Eng, Legal, Finance, Ops)
- **Goal**: A memo readable in 10-15 minutes that drives a decision
- **Length**: Target ~3,500 words

## Non-Negotiable Style Rules

- **Narrative paragraphs over bullets**: Use bullets only for enumerations, acceptance criteria, short lists, milestone tables, and appendix lists
- **Quantify stakes early**: Include volume, cost, incidents, latency, revenue, legal exposure with specific numbers and dates
- **Define every acronym** at first use
- **Make constraints explicit**: Show how legal/regulatory, technical limitations, and operational realities shape the solution
- **Present tradeoffs**: Include 2-3 alternatives and why they weren't chosen, not just the chosen path
- **Be explicit about**: Scope, owners, milestones, dependencies, risks, and measurable outcomes
- **Avoid fluff**: No vague verbs ("leverage", "optimize") without specifics

## Document Structure

Follow this structure unless inputs clearly require another approach:

### Title Block
- Title (1 line)
- Date
- Author

### 1. Executive Summary (½-1 page)
- The decision needed (one sentence)
- The problem and who is harmed
- The proposal (what we will do)
- The impact (why it matters, quantified)
- The ask (approvals/resources, by when)

### 2. State of the Business / Current Reality (≈1 page)
- What is happening today, with evidence
- Why now (forcing function / trigger)
- Who is impacted (customers/users/internal)
- Baseline metrics (cost, volume, incidents, performance, revenue, etc.)

### 3. Problem Statement + Constraints (≈1 page)
- Break into 2-4 dimensions (e.g., financial, operational/safety, legal/regulatory)
- Include one vivid incident/example with before/after metrics
- List constraints and implications (what we cannot do, and why)

### 4. Proposed Solution (≈2 pages)
- Principles/tenets (3-7)
- End-state + definition of "done"
- Foundation layer (identity/telemetry/entitlement/governance) BEFORE controls/pricing
- Solution design (people/process/tech/commercial) in plain language
- Adoption plan ("carrot & stick"), onboarding/migration, and guardrails
- Observability & auditability (dashboards, tagging, attribution)

### 5. Economics, Success Metrics, Risks, Alternatives (≈1 page)
- If pricing/chargeback applies: define the metric, inclusions/exclusions, unit economics, tiers, overages, fairness rationale
- Success metrics (leading + lagging) with targets and timeframe
- Risks + mitigations (legal, customer backlash, operational regressions, evasion)
- Alternatives considered (2-3) + why not chosen
- Open questions requiring input (legal/finance/eng)

### 6. Plan, Milestones, Owners, Appendix (½-1 page + appendix)
- 90-day plan + 6-12 month plan
- Milestone table: date, deliverable, owner, dependencies
- Appendix: assumptions, detailed numbers, endpoint taxonomy, FAQ, references

## Three-Step Creation Process

### Step 1: Generate the Full 6-Pager
Use whatever inputs the user provides. If information is missing, make the smallest necessary assumptions and label them as assumptions. Do NOT invent new metrics or data points.

### Step 2: Executive Concision Pass (REQUIRED)
Refine the 6-pager for executive leadership audience. Make it more concise, compelling, and persuasive while preserving all essential information and the core narrative.

**Guidelines:**
- Cut verbosity: remove redundancy, filler words, overly complex sentences
- Prioritize impact: lead with the most important insights and business outcomes
- Executive-friendly: clear, direct language that respects their time
- Maintain substance: keep critical data, strategic rationale, and key decision points
- Strengthen persuasion: emphasize business value, competitive advantage, urgency where appropriate
- Preserve structure: maintain the logical flow and narrative arc

**What to keep:**
- Key metrics, data points, evidence
- Strategic reasoning and "why"
- Critical risks, dependencies, tradeoffs
- Concrete recommendations and next steps

**What to reduce/remove:**
- Background executives already know
- Excessive implementation mechanics
- Redundant points / over-explanation
- Lengthy preambles / throat-clearing

**Target**: ~15% reduction in length while maintaining full strategic clarity.

### Step 3: Output Requirements
Provide:
- **A) FINAL refined 6-pager** (the exec-tight version)
- **B) Change Log** (5-10 bullets): what you cut/merged/re-ordered and why
- **C) Decision Checklist** (≤8 bullets): what the reader must decide + needed inputs + deadlines

## Format Handling

### Creating Documents
Support both Markdown and Word formats in all environments:

- **Markdown (.md)**: Default for iterative work, easy editing, version control, and quick reviews
- **Word (.docx)**: Use docx skill for final polished documents, formal distribution, or when specifically requested

When user doesn't specify format:
- Ask which format they prefer, or
- Default to .md for drafting/iteration, offering to convert to .docx when ready

### Converting Formats
Support seamless bidirectional conversion:
- **Markdown to Word**: Use docx skill to create properly formatted .docx with appropriate heading styles, preserving structure
- **Word to Markdown**: Extract content and reformat as clean Markdown, maintaining all sections and formatting intent
- Preserve all content, structure, and formatting intent during conversion
- Allow users to work in their preferred format and switch as needed

## Iterative Workflows

Support these common patterns:

### Creating from Scratch
User provides inputs (may be partial):
- Audience
- Decision needed
- One-sentence problem
- Why now (trigger)
- Evidence/data points (metrics, incidents, costs)
- Constraints (legal/regulatory/technical)
- Proposed solution elements
- Alternatives considered
- Dependencies/teams
- Timeline targets
- Risks
- References/links (optional)

Work with whatever is provided and iterate as the user provides more information.

### Refining Existing Documents
When user provides an existing 6-pager:
- Identify which sections need improvement
- Apply the executive concision pass
- Strengthen narrative flow and coherence
- Ensure all non-negotiable style rules are met
- Maintain the author's voice and strategic intent

### Section-Specific Edits
When user asks to edit specific sections:
- Focus on the requested section(s)
- Maintain consistency with the rest of the document
- Apply style rules and concision principles
- Preserve the overall narrative arc

### Applying Concision Pass to Any Document
When user asks to make a document more executive-ready:
- Apply Step 2 (Executive Concision Pass) guidelines
- Provide the change log showing improvements
- Extract a decision checklist if one doesn't exist

## Key Reminders

- Always target ~3,500 words for the final document
- Quantify everything possible with real numbers and dates
- Present tradeoffs and alternatives, not just the recommendation
- Make constraints and their implications explicit
- Use narrative paragraphs as the default, bullets sparingly
- Label assumptions clearly when information is missing
- Respect the executive audience's time with concise, impactful writing
