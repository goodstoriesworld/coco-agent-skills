# Good Stories Agent Skills

> A Media Tech Lab skill bundle for storytellers and their AI agents

18 open-source [Agent Skills](https://agentskills.io) from the Good Stories Media Tech Lab — business operations, engineering, content creation, and data analysis for the Media & Entertainment industry. Ships as a Claude Code plugin (`.claude-plugin/plugin.json` + `skills/`) and stays compatible with **32+ AI coding tools** including Claude Code, Cursor, VS Code Copilot, Gemini CLI, OpenAI Codex, and more.

## Quick Install

```bash
# As a Claude Code plugin
/plugin install good-stories@goodstoriesworld/coco-agent-skills

# Install all skills (any agent that supports npx skills)
npx skills add goodstoriesworld/coco-agent-skills

# Or clone directly
git clone https://github.com/goodstoriesworld/coco-agent-skills.git .agents/skills/good-stories
```

## Good Stories Originals

Skills built in the lab — unique workflows you won't find elsewhere.

### Business & Operations

| Skill | Description |
|-------|-------------|
| [intel-briefing](skills/intel-briefing/) | Build a daily intelligence briefing pipeline from RSS feeds |
| [content-creator](skills/content-creator/) | Generate multi-platform content (LinkedIn, Twitter/X, email, blog) from a single input |
| [business-ops](skills/business-ops/) | Business operations assistant — revenue, expenses, clients, content, goals |
| [marketing-planner](skills/marketing-planner/) | Generate complete marketing campaigns from product details |
| [budget-planner](skills/budget-planner/) | Build budgeting tools with savings projections and allocation strategies |

### Engineering & Data

| Skill | Description |
|-------|-------------|
| [multi-agent-system](skills/multi-agent-system/) | Build production multi-agent systems that plan, implement, test, and evaluate autonomously |
| [data-pipeline](skills/data-pipeline/) | Build CSV analytics pipelines with validation, insight generation, and visualization |
| [sustainability-analyzer](skills/sustainability-analyzer/) | Evaluate and optimize sustainability impact for engineering projects |

### Creative & Consumer

| Skill | Description |
|-------|-------------|
| [quiz-platform](skills/quiz-platform/) | Build production-style quiz platforms with persistent storage, scoring, and admin capabilities |
| [beauty-consultant](skills/beauty-consultant/) | Modular beauty consultation systems with skin-profile analysis and personalized recommendations |

## Curated Collection

Top open-source skills from the community, vendored with proper attribution. All Apache 2.0 licensed.

### Developer Tools

| Skill | Description | Original Source |
|-------|-------------|-----------------|
| [code-reviewer](skills/code-reviewer/) | Thorough code reviews with structured feedback | TerminalSkills |
| [test-generator](skills/test-generator/) | Auto-generate comprehensive test suites | TerminalSkills |
| [git-commit-pro](skills/git-commit-pro/) | Write clear conventional commit messages | TerminalSkills |
| [security-audit](skills/security-audit/) | Audit code for security vulnerabilities | TerminalSkills |
| [sql-optimizer](skills/sql-optimizer/) | Optimize SQL queries for performance | TerminalSkills |
| [frontend-design](skills/frontend-design/) | Build production-grade frontend interfaces | Anthropic |
| [api-designer](skills/api-designer/) | Design clean REST and GraphQL APIs | Good Stories |
| [prompt-engineering](skills/prompt-engineering/) | Write effective prompts using proven patterns | ok-skills |

See [NOTICE.md](NOTICE.md) for full attribution.

## Compatible Tools

Works with any tool that supports the [Agent Skills](https://agentskills.io) open standard:

Claude Code, Cursor, VS Code Copilot, GitHub Copilot, OpenAI Codex, Gemini CLI, JetBrains Junie, Kiro, Roo Code, Goose, Amp, OpenHands, OpenCode, and 20+ more.

## Install Individual Skills

```bash
# Install just one skill
npx skills add goodstoriesworld/coco-agent-skills --skill intel-briefing

# Or copy manually
cp -r coco-agent-skills/skills/intel-briefing .agents/skills/
```

## About Good Stories

Good Stories LLC is a Media Tech Lab for storytellers and their AI agents — a lab of AI tools serving the Media & Entertainment industry. Products include the Good Stories API, Agent Payments (MPP), interactive dashboards, prompt packs, and these agent skills.

- Website: [goodstories.world](https://goodstories.world)
- API docs: [api.goodstories.world/docs](https://api.goodstories.world/docs)
- Products: [goodstories.gumroad.com](https://goodstories.gumroad.com)

## License

Apache 2.0 — see [LICENSE](LICENSE) for details.
Vendored skills retain their original licenses — see individual SKILL.md files for details.
