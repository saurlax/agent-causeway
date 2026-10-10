# Deployment reference

Follow [AGENTS.md](AGENTS.md) for repository guidance.

## Zeabur deployment

- Project: a13n
- Project ID: `6abb56df55583bfbdf1beb87`
- Service: agentcauseway
- Service ID: `6aca42e54873e494859cef83`
- Environment ID: `6abb56df4fc8a0a35a5dda61`
- Public URL: `https://agentcauseway.zeabur.app`
- Persistent volume: `ac-data` mounted at `/data`

Reuse this service ID when redeploying. See [container deployment](docs/deployment.md)
for persistent storage and proxy configuration. Credentials are local ignored
configuration and must never be committed.
