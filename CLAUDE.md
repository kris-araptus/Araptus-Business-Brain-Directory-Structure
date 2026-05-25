# Business Brain - Claude Instructions

## About This Vault

This is a business knowledge management vault designed to organize marketing, website, and content strategy for companies building or improving their online presence. It serves as a second brain for business decision-making and content creation.

## Directory Structure

- **00-Inbox/** - Capture raw ideas, notes, and unprocessed thoughts here first
- **01-Business/** - Core business identity: brand voice, goals, mission, competitor analysis
- **02-Marketing/** - Marketing strategy, campaigns, social media plans, email sequences, paid ads, and analytics tracking
- **03-Website/** - Website pages, SEO strategy, UX notes, and technical requirements
- **04-Content/** - All content production: blog posts, lead magnets, case studies, video scripts, newsletters
- **05-Audience/** - Customer personas, research, testimonials, and voice-of-customer data
- **06-Sales/** - Offers, funnels, pricing strategy
- **07-Operations/** - SOPs, tool stack documentation, meeting notes
- **08-Assets/** - Images, logos, templates, and reusable media
- **09-Archive/** - Completed or retired content moved here for reference

## How to Work With This Vault

### When creating or editing notes:
- Always use Obsidian-compatible markdown
- Use YAML frontmatter for metadata (status, tags, date, author)
- Link related notes using `[[wikilinks]]` to build a connected knowledge graph
- Tag notes with relevant categories (e.g., `#blog`, `#seo`, `#campaign`)
- Place new raw ideas in `00-Inbox/` then refine and move to the appropriate folder

### When helping with content:
- Reference the brand voice and persona documents in `01-Business/Brand/` before generating copy
- Check `05-Audience/Personas/` to understand who the content is for
- Align all content suggestions with the goals defined in `01-Business/Goals/`
- Suggest internal links between related notes where appropriate

### When helping with marketing strategy:
- Review existing campaigns in `02-Marketing/Campaigns/` before suggesting new ones
- Consider the full funnel: awareness, consideration, conversion, retention
- Reference competitor analysis in `01-Business/Competitors/` for positioning
- Track metrics and KPIs in `02-Marketing/Analytics/`

### When helping with website work:
- Check `03-Website/SEO/` for target keywords and strategy
- Reference `03-Website/Pages/` for existing site structure
- Ensure all page copy aligns with brand voice and audience personas
- Consider mobile-first, accessibility, and page speed in technical recommendations

### Note Frontmatter Template

```yaml
---
title: 
status: draft | in-progress | review | published | archived
created: YYYY-MM-DD
updated: YYYY-MM-DD
tags: []
---
```

## Tone and Voice Guidelines

- Match the business's established brand voice (see `01-Business/Brand/`)
- If no brand voice is defined yet, default to: professional, clear, approachable
- Avoid jargon unless the audience expects it
- Write for humans first, search engines second

## Key Principles

1. **Capture everything** - No idea is too small for the Inbox
2. **Connect knowledge** - Link notes to build context over time
3. **Action-oriented** - Every note should eventually drive a decision or piece of content
4. **Iterate** - Notes are living documents; update them as the business evolves
5. **Audience-first** - Every piece of content starts with who it's for
