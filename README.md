# LogRocket Plugin for Claude Code

Connect Claude Code to [LogRocket](https://logrocket.com) to query session replays, metrics, issues, and user behavior using natural language — powered by the [LogRocket MCP Server](https://docs.logrocket.com/docs/mcp) and [Ask Galileo](https://docs.logrocket.com/docs/ask-galileo).

## What's Included

| Component | Description |
|-----------|-------------|
| **MCP Server** | Connects Claude Code to the LogRocket API via the `use_logrocket` tool |
| **Use LogRocket Skill** | Teaches your AI agent how to query LogRocket on your behalf |

## Setup

1. Add the marketplace: `/plugin marketplace add logrocket/logrocket-claude-plugin`
2. Install the plugin: `/plugin install logrocket@logrocket`
3. Connect to the MCP server when prompted to authenticate.

## Example Prompts

- "User X reported a problem with checkout. Can you use LogRocket to watch their sessions and figure out the root cause?"
- "I'm about to work on the search feature — can you use LogRocket to help me understand how it's currently being used?"
- "Can you look at LogRocket for new issues from the past week, try to figure out their root causes, and then suggest which ones I can fix?"
- "Look at all commits from last week, and check LogRocket data to ensure they didn't introduce any regressions."
- "Use LogRocket to watch sessions and look at issues to figure out what is highest priority that I work on next."

## Learn More

- [LogRocket MCP Server Docs](https://docs.logrocket.com/docs/mcp)
- [Ask Galileo Docs](https://docs.logrocket.com/docs/ask-galileo)

## Validation

Validate the plugin structure using Claude Code's built-in validator:

```sh
claude plugin validate .
```
