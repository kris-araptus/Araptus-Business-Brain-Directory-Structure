# Business Brain — Obsidian Vault Starter Template

A ready-to-deploy Obsidian vault directory structure for businesses building or improving their online presence. Clone it, open it in Obsidian, and start organizing your marketing, website, and content strategy immediately.

Built for use with **Claude Code** and AI-assisted workflows, but works just as well as a standalone second brain.

---

## What Is This?

This is a **Business Brain** — a pre-built [Second Brain](https://www.buildingasecondbrain.com/) vault template purpose-built for companies that need to get their marketing, website, and content organized fast.

It's designed for:

- Businesses launching a website for the first time
- Companies redesigning or rebuilding their online presence
- Marketing teams that need a single source of truth for strategy, content, and brand
- Agencies deploying a repeatable knowledge structure to client machines
- Anyone using Obsidian + AI (Claude Code, etc.) to accelerate content creation

This is **not** a personal knowledge management system. It's a focused, business-oriented vault structure optimized for marketability and online growth.

## Why Use a Starter Vault?

Starting with an empty Obsidian vault leads to decision fatigue — *where do I put this? what folder do I need? how should I tag things?* Most people abandon their vault within weeks.

A good directory structure:

- **Eliminates decision fatigue** — every note type has a home
- **Creates consistency** — across team members, across clients, across time
- **Accelerates AI workflows** — Claude Code reads the `CLAUDE.md` and understands context immediately
- **Scales with the business** — from solo founder to full marketing team

## Directory Structure

```
00-Inbox/              → Raw ideas, links, and unprocessed thoughts
01-Business/
  ├── Brand/           → Brand voice, identity, mission, values
  ├── Goals/           → Business objectives and OKRs
  └── Competitors/     → Competitor analysis and positioning
02-Marketing/
  ├── Strategy/        → Marketing plans and quarterly goals
  ├── Campaigns/       → Individual campaign planning and tracking
  ├── Email/           → Email sequences, newsletters, drip campaigns
  ├── Social-Media/    → Platform strategies, content calendars
  ├── Paid-Ads/        → Ad copy, targeting, budgets
  └── Analytics/       → KPIs, reports, performance tracking
03-Website/
  ├── Pages/           → Page copy, wireframes, sitemap
  ├── SEO/             → Keyword strategy, on-page optimization
  ├── UX-Notes/        → User experience observations and improvements
  └── Technical/       → Hosting, performance, technical requirements
04-Content/
  ├── Blog-Posts/      → Blog drafts, outlines, published posts
  ├── Lead-Magnets/    → Ebooks, checklists, downloadable assets
  ├── Case-Studies/    → Client stories and results
  ├── Video-Scripts/   → YouTube, social video, webinar scripts
  └── Newsletters/     → Newsletter editions and planning
05-Audience/
  ├── Personas/        → Ideal customer profiles
  ├── Customer-Research/ → Surveys, interviews, VOC data
  └── Testimonials/    → Reviews, quotes, social proof
06-Sales/
  ├── Offers/          → Product/service descriptions and positioning
  ├── Funnels/         → Conversion paths and landing page strategy
  └── Pricing/         → Pricing models and competitive pricing
07-Operations/
  ├── SOPs/            → Standard operating procedures
  ├── Tools-Stack/     → Software, platforms, and integrations
  └── Meeting-Notes/   → Internal meeting notes and decisions
08-Assets/
  ├── Images/          → Photos, graphics, screenshots
  ├── Logos/           → Brand logos and variations
  └── Templates/       → Reusable note and content templates
09-Archive/            → Completed or retired content
```

## Included Templates

The vault ships with starter templates so you're not staring at blank pages:

| Template | Location | Purpose |
|----------|----------|---------|
| Brand Voice Guide | `01-Business/Brand/` | Define tone, personality, do's and don'ts |
| Competitor Analysis | `01-Business/Competitors/` | Profile competitors and find opportunities |
| Marketing Plan | `02-Marketing/Strategy/` | Channels, cadence, budget, quarterly goals |
| Keyword Strategy | `03-Website/SEO/` | Primary, secondary, and question keywords |
| Blog Post Template | `04-Content/Blog-Posts/` | Outline, SEO notes, CTA, draft space |
| Customer Persona | `05-Audience/Personas/` | Demographics, psychographics, messaging |

## How to Use

### Quick Start

1. **Clone or download** this repository
2. **Open the folder** as a vault in [Obsidian](https://obsidian.md/)
3. **Fill in `01-Business/Brand/brand-voice.md`** first — this anchors everything else
4. **Create your first persona** in `05-Audience/Personas/`
5. **Start capturing** ideas in `00-Inbox/` and refine from there

### With Claude Code

This vault includes a `CLAUDE.md` file that gives Claude context about the vault structure, note conventions, and how to reference brand/audience documents before generating content.

To use it:

1. Open a terminal in the vault directory
2. Run `claude` to start Claude Code
3. Ask Claude to help draft blog posts, refine strategy, analyze competitors, or build content calendars — it will use the vault structure and your filled-in templates as context

### For Agencies Deploying to Clients

1. Fork or clone this repo as your base template
2. Customize the `CLAUDE.md` with any client-specific instructions
3. Pre-fill the brand voice and persona templates during onboarding
4. Deploy to the client's machine — they open it in Obsidian and start working

### Workflow

The recommended workflow follows a simple capture-and-refine loop:

```
Capture → Inbox → Refine → Move to correct folder → Link related notes → Review weekly
```

- **Daily**: Dump thoughts into `00-Inbox/`
- **Weekly**: Process inbox, move notes to proper folders, add tags and links
- **Monthly**: Review strategy docs, update analytics, archive completed campaigns
- **Quarterly**: Revisit goals, personas, and marketing plan

## Design Principles

This structure is inspired by proven knowledge management methods:

- **[PARA Method](https://fortelabs.com/blog/para/)** (Projects, Areas, Resources, Archive) — organizing by actionability, not topic
- **Second Brain** (Tiago Forte) — capture, organize, distill, express
- **AI-Native** — structured for machine-readability with consistent frontmatter, wikilinks, and a `CLAUDE.md` entry point

Key differences from generic second brain templates:

- **Business-focused** — no personal journals, reading lists, or recipe folders
- **Marketing-first** — the structure prioritizes content that drives revenue
- **Deployable** — designed to be cloned and dropped onto any machine
- **AI-ready** — `CLAUDE.md` provides instant context for AI-assisted workflows

## Note Conventions

All notes use YAML frontmatter for metadata:

```yaml
---
title: Page Title
status: draft | in-progress | review | published | archived
created: 2026-05-24
updated: 2026-05-24
tags: [marketing, seo, blog]
---
```

Use `[[wikilinks]]` to connect related notes and build a knowledge graph over time.

## Requirements

- [Obsidian](https://obsidian.md/) (free, available on Mac, Windows, Linux, iOS, Android)
- Optional: [Claude Code](https://claude.ai/claude-code) for AI-assisted content workflows

## Contributing

Found a folder missing? Have a better template? Open an issue or submit a PR.

## License

MIT — use it, fork it, deploy it to every client machine you've got.
