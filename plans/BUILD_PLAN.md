# MemberJunction Cowork Plugin Strategy - Build Plan

## Overview

This plan outlines the strategy for building three Claude Cowork Plugins that extend MemberJunction's capabilities:

1. **MJ Admin/Developer Plugin** — Tools for developers and administrators
2. **MJ Agent Builder Plugin** — Direct agent interaction through Cowork
3. **Association Management Plugin** — Standalone plugin for associations

All plugins reside in a single monorepo at https://github.com/MemberJunction/co-work-plugins, each with independent installation capability while sharing consistent structure.

## Key Architecture

Each plugin follows standard Cowork structure: markdown skills (domain knowledge), slash commands (user-invoked actions), MCP connectors, and sub-agents. As stated in the document: "no runtime code, no build steps."

### Plugin Structure Pattern
```
plugin-name/
├── .claude-plugin/plugin.json
├── .mcp.json
├── commands/
└── skills/
```

## Plugin Breakdown

### Association Management (Tier 1 Priority)

The standalone association plugin targets "trade associations, professional societies, chambers of commerce, standards bodies, alumni organizations." It provides 16 slash commands covering membership lifecycle, events, governance, communications, advocacy, and more.

Key value proposition: Works immediately without infrastructure. MJ integration unlocks data access and automated workflows.

**16 Commands:**
1. Member onboarding
2. Board preparation
3. Newsletters
4. Event planning
5. Advocacy briefs
6. Grant proposals
7. Sponsorship packages
8. Retention campaigns
9. Annual reports
10. Committee charters
11. Bylaws review
12. Strategic planning
13. CE programs
14. Surveys
15. RFP responses
16. Crisis communications

**12 Skills:**
1. Foundation knowledge encoding association best practices
2. Governance frameworks
3. Membership engagement strategies
4. Event management
5. Advocacy campaigns
6. Education/certification design
7. Revenue diversification
8. Chapter management
9. Volunteer engagement
10. DEI practices
11. Metrics

### MJ Admin/Developer Plugin

Transforms "Cowork into an MJ-aware development assistant" for querying entities, scaffolding migrations, triggering codegen, and managing metadata. Requires running MJ MCP Server instance.

**7 Commands:**
1. Entity lookup
2. Running queries
3. Scaffolding migrations
4. Scaffolding actions
5. Relationship mapping
6. Codegen status
7. Health checks

**8 Skills:**
1. Entity metadata systems
2. Migration patterns
3. Action design
4. Codegen workflows
5. Naming conventions
6. RunView patterns
7. MCP configuration
8. Monorepo structure

### MJ Agent Builder Plugin

Enables creation, testing, and iteration of MJ agents through Cowork. Users can create agents, configure prompts, execute agents, and monitor runs without leaving conversation.

**8 Commands:**
1. Create agent
2. Run agent
3. Multi-turn chat
4. Monitor execution
5. Debug runs
6. Tune prompts
7. List available agents
8. View analytics

**7 Skills:**
1. Agent architecture
2. Prompt engineering best practices
3. Action integration
4. Entity models
5. Conversation patterns
6. Model selection
7. Debugging approaches

## Implementation Phases

### Phase 1: Repository Setup
- Directory structure and boilerplate
- Configure monorepo layout

### Phase 2: Association Plugin (Highest Priority)
- Implement all 16 commands
- Create all 12 skills
- Test standalone functionality

### Phase 3: MJ Admin Plugin
- Implement 7 commands
- Create 8 skills
- Test MCP server integration

### Phase 4: MJ Agent Builder Plugin
- Implement 8 commands
- Create 7 skills
- Test agent lifecycle workflows

### Phase 5: Testing and Validation
- Plugin installation verification
- Command execution testing
- Cross-plugin compatibility

### Phase 6: Documentation and Release
- READMEs for each plugin
- Marketplace submission preparation

### Phase 7: Future Enhancements
- MJ integration improvements
- MCP server enhancements
- Enterprise features

## Strategic Value

**For MemberJunction:**
- Lead generation through free association plugin
- Developer productivity gains
- Platform stickiness via MCP server connections
- Market positioning as association-tech thought leader

**For Associations:**
- Immediate standalone utility
- Upgrade path to full MJ platform
- Domain expertise encoding
- Significant time savings on routine tasks

**For Cowork Ecosystem:**
- Demonstrates vertical plugin model
- Shows MCP integration patterns
- Establishes tiered value (standalone → integrated) approach
