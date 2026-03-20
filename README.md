# Plain — Cursor Plugin

Connect [Cursor](https://cursor.com) to your [Plain](https://plain.com) workspace. Manage support threads, customers, tenants, and help center articles directly from your editor using the Plain MCP server.

## What's included

- **MCP Server** — Connects to Plain's remote MCP server (`https://mcp.plain.com/mcp`) with OAuth authentication. No API keys required.
- **Rules** — Contextual guidelines that help the AI agent use Plain tools effectively.

## Installation

Install from the Cursor plugin marketplace, or add manually:

1. Clone this repository into your Cursor plugins directory
2. Restart Cursor
3. When prompted, authenticate with your Plain account via OAuth

## Tools

Once installed, the AI agent has access to 30+ tools across these categories:

| Category | Tools | Description |
|----------|-------|-------------|
| **Threads** | 13 | Query, search, reply, assign, label, snooze, and manage support threads |
| **Customers** | 5 | Look up customers, view their threads, create/update records |
| **Tenants** | 5 | Manage tenant (company) records and custom fields |
| **Help Center** | 6 | Browse and manage help center articles and groups |
| **Labels** | 5 | Create, update, archive, and reorder label types |
| **Thread Fields** | 6 | Manage custom thread field schemas and values |
| **Workspace** | 4 | Get user profiles, workspace info, and assigned threads |

## Authentication

Plain MCP uses OAuth — no API keys needed. On first use, a browser window will open for you to select your Plain workspace and authorize access.

## Examples

Ask the agent things like:

- *"Show me my assigned threads"*
- *"Search for threads from customer@example.com"*
- *"Draft a reply to thread X"*
- *"What help center articles do we have about billing?"*
- *"Create a new customer record for Acme Corp"*

## Links

- [Plain](https://plain.com)
- [Plain MCP documentation](https://plain.com/docs/mcp-server)
- [Cursor plugin docs](https://cursor.com/docs/reference/plugins)

## License

MIT
