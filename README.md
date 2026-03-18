# AI-Subagents

A collection of reusable AI agent definitions for use with Claude Code and similar tools.

## Agents

| Agent | Description |
|-------|-------------|
| `codebase-explorer` | Explore and understand codebases without making changes |

## Usage

Place agent `.md` files in the `agents/` directory. Each agent follows the frontmatter format with name, description, model, and configuration fields, followed by the system prompt.

## Structure

```
agents/
  codebase-explorer.md   # Read-only codebase analysis agent
```
