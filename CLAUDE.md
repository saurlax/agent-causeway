# Deployment reference

Follow [AGENTS.md](AGENTS.md) for repository guidance.

## Zeabur deployment

- Project: a13n
- Project ID: `6abb56df55583bfbdf1beb87`
- Service: channel-gateway
- Service ID: `6aca42e54873e494859cef83`
- Environment ID: `6abb56df4fc8a0a35a5dda61`
- Public URL: `https://channel-gateway.zeabur.app`
- Persistent volume: `ac-data` mounted at `/data`
- Container image: `ghcr.io/saurlax/channel-gateway`
- Deployment tags: `sha-<full commit SHA>` from the successful CI publication

Reuse this service ID and update its GHCR image tag when deploying. See [container deployment](docs/deployment.md)
for persistent storage and proxy configuration. Credentials are local ignored
configuration and must never be committed.
