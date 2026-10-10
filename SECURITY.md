# Security Policy

AgentPort is pre-release software. There are no maintained release lines yet.

Report suspected vulnerabilities privately to [saurlax@qq.com](mailto:saurlax@qq.com).
Include the affected commit, reproduction steps, expected impact, and a minimal
example with secrets and private messages removed. Do not publish exploit details
or real credentials in a public issue.

The foundation service binds to loopback and has no authentication. It is intended
for local development. Future channel and Agent Host integrations must define
credential handling and conversation access before supporting shared deployment.
