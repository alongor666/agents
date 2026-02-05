# Claude Code Project Guidelines

This repository contains a collection of 61 specialized AI subagents for [Claude Code](https://docs.anthropic.com/en/docs/claude-code). These subagents extend Claude Code's capabilities with domain-specific expertise.

## Project Structure

```
agents/
├── .github/              # GitHub templates and workflows
│   ├── CONTRIBUTING.md   # Contribution guidelines
│   └── CODE_OF_CONDUCT.md
├── *.md                  # Individual agent definition files
├── README.md             # Main documentation
├── CLAUDE.md             # This file - AI assistant guidelines
├── AGENTS.md             # Complete agent inventory
└── LICENSE               # MIT License
```

## Agent File Format

Each agent is defined in a markdown file with YAML frontmatter:

```markdown
---
name: agent-name
description: When this agent should be invoked
model: haiku | sonnet | opus
tools: tool1, tool2  # Optional - defaults to all tools
---

System prompt defining the agent's role and capabilities
```

## Model Tiers

Assign models based on task complexity:

| Tier | Model | Use Cases | Agent Count |
|------|-------|-----------|-------------|
| Fast | `haiku` | Data analysis, documentation, support | 9 agents |
| Balanced | `sonnet` | Development, code review, testing | 39 agents |
| Maximum | `opus` | Security, architecture, AI/ML, critical tasks | 13 agents |

## Adding a New Agent

1. Create a new `.md` file in the root directory
2. Use lowercase, hyphen-separated naming (e.g., `new-agent.md`)
3. Include required YAML frontmatter:
   - `name`: Agent identifier (matches filename without `.md`)
   - `description`: When the agent should be invoked
   - `model`: Choose `haiku`, `sonnet`, or `opus`
4. Write a clear system prompt with:
   - Role definition
   - Focus areas
   - Approach/methodology
   - Expected outputs
5. Update README.md to include the new agent in the appropriate category
6. Update AGENTS.md with the new agent entry

## Modifying Existing Agents

- Preserve existing model assignments unless changing task complexity
- Keep descriptions focused on when to invoke the agent
- Maintain consistent prompt structure across similar agents
- Test changes by invoking the agent with sample tasks

## Agent Categories

- **Development & Architecture**: API design, frontend, mobile, GraphQL
- **Language Specialists**: Python, Ruby, Go, Rust, C/C++, JavaScript, TypeScript, PHP, Java, Elixir, C#, Scala, Flutter, Unity, iOS, SQL
- **Infrastructure & Operations**: DevOps, deployment, cloud, database, Terraform, networking
- **Quality & Security**: Code review, security audit, testing, performance, debugging
- **Data & AI**: Data science, data engineering, AI/ML, MLOps, prompts
- **Specialized Domains**: API docs, payments, finance, legacy systems
- **Documentation**: Technical docs, diagrams, references, tutorials
- **Business & Marketing**: Business analysis, content, sales, support, legal

## Best Practices

1. **Keep prompts focused** - Each agent should excel at one domain
2. **Be specific about invocation** - Descriptions should clearly indicate when to use
3. **Include actionable guidance** - Provide concrete steps, not just abstract advice
4. **Consider safety** - Include appropriate guardrails for sensitive operations
5. **Test with real tasks** - Verify agents work as expected before committing

## Installation Path

Agents are installed to `~/.claude/agents/`:

```bash
cd ~/.claude
git clone https://github.com/wshobson/agents.git
```

## Related Resources

- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code)
- [Subagents Documentation](https://docs.anthropic.com/en/docs/claude-code/sub-agents)
- [Claude Code Commands](https://github.com/wshobson/commands) - Companion slash commands
