# AI Agents

Tools and templates for AI agents that help apply BETHKANIA framework.

## Structure

### templates/
Ready-to-use AI agent templates:
- Decision advisor (helps apply 5-filter test)
- Values checker (flags violations)
- Postmortem generator (documents failures)
- Conflict mediator (resolves disputes)

### prompts/
System prompts for different AI autonomy levels:
- Level 1: Supervised (new AIs)
- Level 2: Trusted (proven track record)
- Level 3: Autonomous (strategic recommendations)
- Level 4: Strategic Partner (proven over time)
- Level 5: Founder-Equivalent (rare, earned)

### integrations/
Specific platform integrations:
- Slack bot (Bethkania Copilot)
- GitHub Action (PR values checking)
- CLI tool (command-line decision helper)
- Web dashboard (coming soon)

## Bethkania Copilot

Our flagship AI assistant that:
- Runs 5-filter test in real-time (<1 minute)
- Flags values violations before they happen
- Helps document failures and learnings
- Mediates pod conflicts using framework
- Escalates when appropriate

## Coming Soon

- MVP Slack bot (4-week build)
- GitHub PR reviewer (8-week build)
- CLI decision helper (12-week build)
- Decision provenance graph visualization

## For AI Developers

Want to build a BETHKANIA-compatible AI agent?
1. Study the framework in [BETHKANIA.md](../BETHKANIA.md)
2. Review the system prompts in `prompts/`
3. Test against boundary test cases in `examples/boundary-tests/`
4. Submit your agent for review

## Contributing

See [CONTRIBUTING.md](../community/CONTRIBUTING.md) for how to contribute agents or improvements.
