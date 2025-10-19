# MYRS.ai Marketplace

MYRS.ai plugin marketplace for advanced agent frameworks, marketing automation, and productivity tools.

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add jakreymyers/myrs-ai-marketplace
```

## Available Plugins

### MYRS Core

**Description:** Advanced agent framework with proven patterns for TDD, systematic debugging, collaboration workflows, and quality-driven development

**Categories:** Framework, Testing, Debugging, Collaboration, Quality Assurance

**Install:**
```bash
/plugin install myrs-core@myrs-ai-marketplace
```

**What you get:**
- Battle-tested agent skills library
- Systematic debugging and TDD workflows
- Collaboration patterns and best practices
- Quality gates and verification protocols
- Custom commands for development workflows
- Progressive development methodologies

**Repository:** https://github.com/jakreymyers/myrs-core

---

### MYRS Git Flow

**Description:** Git workflow automation and best practices for seamless version control, branching strategies, commit conventions, and collaboration workflows

**Categories:** Git, Version Control, Workflow, Automation, Best Practices

**Install:**
```bash
/plugin install myrs-git-flow@myrs-ai-marketplace
```

**What you get:**
- **Git Flow Commands** - Automated branch creation and management
  - `/myrs-git-flow:feature` - Create feature branches from develop
  - `/myrs-git-flow:release` - Create release branches with versioning
  - `/myrs-git-flow:hotfix` - Create hotfix branches from main
  - `/myrs-git-flow:finish` - Complete and merge branches automatically
  - `/myrs-git-flow:flow-status` - Comprehensive Git Flow status reporting
- **Validation Hooks** - Automatic enforcement of Git Flow best practices
  - Conventional Commits validation (feat, fix, docs, etc.)
  - Git Flow branch naming enforcement (feature/*, release/*, hotfix/*)
  - Protected branch push prevention (blocks direct pushes to main/develop)
- **Git Flow Manager Agent** - Intelligent workflow automation
  - Automated merge conflict detection
  - Conventional commit message formatting
  - Release management with changelog generation
  - Pull request generation with detailed descriptions
  - Visual status reporting with recommendations

**Key Features:**
- Complete Git Flow workflow automation
- Zero-configuration hooks that work on plugin install
- Prevents common Git mistakes before they happen
- Visual branch status and relationship diagrams
- Semantic versioning support for releases
- Integration with awesome-claude-statusline

**Repository:** https://github.com/jakreymyers/myrs-git-flow

---

### MYRS Marketing Team

**Description:** Comprehensive marketing automation suite with multi-agent orchestration for brand strategy, market research, persona development, content strategy, and digital asset creation

**Categories:** Marketing, Strategy, Automation, Branding, Content

**Install:**
```bash
/plugin install myrs-marketing-team@myrs-ai-marketplace
```

**What you get:**
- 6 specialized marketing agents
- 7-phase marketing workflow (Discovery → Strategy Synthesis)
- Market research and competitive analysis tools
- Customer persona development framework
- Brand strategy and voice definition
- Content strategy and messaging
- Website architecture and conversion optimization
- Quality gates and validation checklists
- Automated deliverable generation

**Key Agents:**
- **Marketing Orchestrator** - Workflow coordination and strategy governance
- **Research Synthesizer** - Market research and competitive intelligence
- **Persona Architect** - Customer persona and journey mapping
- **Brand Strategist** - Brand positioning and voice development
- **Content Strategist** - Content planning and messaging
- **Website Architect** - Website design and conversion strategy

**Repository:** https://github.com/jakreymyers/myrs-marketing-team

---

## Marketplace Structure

```
myrs-ai-marketplace/
├── .claude-plugin/
│   └── marketplace.json       # Plugin catalog
└── README.md                  # This file
```

## Support

- **Issues**: https://github.com/jakreymyers/myrs-ai-marketplace/issues
- **MYRS Core Plugin**: https://github.com/jakreymyers/myrs-core
- **MYRS Git Flow Plugin**: https://github.com/jakreymyers/myrs-git-flow
- **MYRS Marketing Team Plugin**: https://github.com/jakreymyers/myrs-marketing-team

## License

Marketplace metadata: MIT License

Individual plugins: See respective plugin licenses
