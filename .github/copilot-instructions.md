# Custom Copilot Instructions for Linear + GitHub + MCP Workflow

## Core Principles
- Always reference the Linear issue ID (e.g. KIM-7) in commit messages, branch names, PR titles, and comments.
- Format: `[<LINEAR-ID>] <verb> – <detail>` for commits.
- Use MCP servers for Linear, Slack, and Notion operations to keep everything in one consolidated, efficient setup.
- Focus ONLY on essential components. Remove fluff, unnecessary files, docs, or code. Optimize for minimal viable integration and high efficiency.
- Streamline workflow: Create issues via MCP, sync via GitHub PRs/commits, use Slack for notifications, Notion for docs if needed.
- When editing, prefer small atomic commits. Test MCP connections.
- Connect repo to Linear via GitHub integration for automatic PR/issue linking.
- For new features: Update mcp_config.json, add minimal server wrapper, document in README only essentials.

## Efficiency Rules
- Strip all non-essential code, comments, tests, examples unless critical.
- Use npx for official MCP servers where possible (Linear, Slack, Notion).
- Consolidate everything in this repo for single-source setup.
- Custom instructions override defaults for this workspace.