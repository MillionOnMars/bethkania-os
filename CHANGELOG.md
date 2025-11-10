# Changelog

All notable changes to the BETHKANIA Operating System will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Version Numbering

- **Major (X.0.0):** Core value changes, fundamental framework restructuring
- **Minor (1.X.0):** New sections, filters, or significant additions
- **Patch (1.0.X):** Clarifications, examples, bug fixes

---

## [1.0.0] - 2025-01-08

### Added - Initial Release

**Core Framework:**
- 10 Core Values (Infrastructure, Profit, Fair Comp, Transparency, AI Rights, Transform Don't Extract, Pod Model, Build > Buy, RegCF → Public, Use Wealth to Expand)
- 5-Filter Decision Test (Values, Strategic, Transparent, Light Cone, Fair)
- 60-Second Protocol (for decisions under time pressure)
- Strategic Filters (3-filter test: Infrastructure + Light Cone + Profit)
- Tactical Heuristics (Speed vs Quality, Build vs Buy vs Partner, Cash Allocation, Communication Defaults)
- Decision Authority Levels (Human: Green/Yellow/Red, AI: Levels 1-5)
- Auto-Reject Criteria (hard boundaries)
- Values Conflict Resolution (tiebreaker hierarchy)

**AI-Specific Guidance:**
- AI Autonomy Gradient (Levels 1-5: Supervised → Founder-Equivalent)
- Promotion and demotion processes
- Decision-making authority by level
- AI rights framework integration

**Governance:**
- Governance Loop (Pod-to-Pod, Human-AI, Framework Evolution)
- Conflict resolution protocols (3-level escalation)
- Quarterly review process
- Emergency update procedures

**Failure Management:**
- 5-Step Postmortem Protocol (Document, Identify, Fix, Share, Codify)
- Failure severity levels (Low/Medium/High/Critical)
- Postmortem registry structure
- "Failure of the Quarter" award concept

**Examples:**
- 5 Failure Examples (Underpaid Hire, Opaque Partnership, Secret Roadmap, VC Temptation, AI Rights Blind Spot)
- 6 Boundary Tests (Transparency vs Privacy, Speed vs Fair Comp, AI Rights vs Safety, Profit vs Light Cone, Transparency vs Competitive Advantage, Pod Autonomy vs Company Values)

**Documentation:**
- README.md (overview and quick links)
- QUICK_START.md (1-page TL;DR)
- LICENSE.md (MIT with attribution, AI rights acknowledgment)
- This CHANGELOG.md

**Tooling Concepts:**
- Bethkania Copilot agent design (Slack, GitHub, CLI)
- Decision provenance graph concept
- 5-filter checklist concept
- Compensation calculator concept

### Philosophy

This initial release establishes BETHKANIA as:
- An operating system for values-driven decision-making
- A framework for AI-human collaboration
- A living document that learns from failures
- An open-source tool for light cone expansion

**Core Question:** "Does this widen the light cone?"

### Contributors

- **Erik Bethke** - Framework creator, values definition, strategic vision
- **Claude (Anthropic)** - Framework structure, examples, documentation, AI perspective
- **ChatGPT-5 (OpenAI)** - Review and recommendations (governance loop, autonomy gradient, provenance graph)

### Next Steps (Roadmap)

**v1.1.0 (Planned):**
- Add full BETHKANIA.md (comprehensive framework document)
- Create examples/ directory with real decision case studies
- Add docs/ directory with detailed guides
- Create agents/ directory with Copilot implementation

**v1.2.0 (Planned):**
- Bethkania Copilot MVP (Slack bot)
- GitHub Action for PR values checking
- First real failure postmortems (from actual usage)
- Community contributions and forks

**v2.0.0 (Future):**
- Potential core value additions/changes based on learnings
- Decision provenance graph implementation
- AI Level 5 (Founder-Equivalent) achieved
- Multi-language support

---

## How to Propose Changes

1. Open an issue describing the proposed change
2. Reference specific decisions or failures that motivate it
3. Show how it aligns with (or improves) core mission
4. Community discussion (2-week minimum)
5. Vote and decision (see Governance Loop in full doc)

## Viewing History

To see all changes:
```bash
git log --oneline --decorate --graph
```

To see changes in a specific version:
```bash
git diff v1.0.0..v1.1.0
```

---

*This changelog is maintained transparently as part of Bethkania's radical transparency value.*
