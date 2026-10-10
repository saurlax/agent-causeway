# AgentCauseway Server

FastAPI management service, OneBot v11 ↔ a13n text bridge, SQLite persistence,
conversation-scoped MCP tools, and a bundled shadcn management console.

See [the bridge setup guide](../../docs/onebots-a13n.md) and the
[technical contracts](../../spec/README.md). Management needs
`AGENTCAUSEWAY_ADMIN_TOKEN` (at least 32 characters). State is stored under
`AGENTCAUSEWAY_DATA_DIR`, defaulting to `.agentcauseway`; use one process/replica.

From the repository root, `make serve` builds the console and starts the service.
`make dev-api` starts the backend without requiring a frontend build. Run
`agentcauseway serve --help` for listen options.

Build the frontend before packaging to include it in the wheel and source
archive. Headless packages remain usable without frontend assets or Node.js.
