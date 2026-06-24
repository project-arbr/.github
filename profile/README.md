# Project Arbr

Open infrastructure for AI deployment.

Project Arbr is a collection of open source tools for teams building on top of large language models — from request routing and cost governance to user-facing chat interfaces and developer SDKs.

## Products

| Project | Description | Install |
|---------|-------------|---------|
| [Arbr Control Plane](https://github.com/project-arbr/arbr-control-plane) | AI gateway · multi-provider routing · spend tracking · budget governance | `docker pull ghcr.io/project-arbr/arbr-control-plane` |
| [Arbr Chat](https://github.com/project-arbr/arbr-chat) | Open source chat UI (LibreChat-style, connects to the Control Plane) | _coming soon_ |
| [@arbr/client](https://www.npmjs.com/package/@arbr/client) | JavaScript / TypeScript SDK | `npm install @arbr/client` |
| [arbr-client](https://pypi.org/project/arbr-client) | Python SDK | `pip install arbr-client` |

## Quickstart

```bash
# Run Arbr Control Plane with Docker (demo mode, no config needed)
docker compose up
```

Then open [http://localhost:4100](http://localhost:4100) for the dashboard, or point any OpenAI-compatible client at `http://localhost:4100/v1`.

## Links

- [Documentation](https://github.com/project-arbr/arbr-control-plane/tree/main/docs)
- [Contributing](.github/CONTRIBUTING.md)
- [Security](.github/SECURITY.md)
