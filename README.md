# QED Proof docs

This is the source of [docs.qedproof.site](https://docs.qedproof.site), built with [Mintlify](https://mintlify.com).

## This repository is a one-way export

This repository is published from a private, upstream repository by a gated export. Each release here is a snapshot
commit, tagged `docs-vX.Y.Z`. It is not developed against directly — see [CONTRIBUTING.md](CONTRIBUTING.md) for how a
fix or a gap gets in.

## Local preview

```bash
npx mint@4.2.939 dev
```

Requires Node.js 20.17 or later. Before opening a pull request, check for broken links:

```bash
npx mint@4.2.939 broken-links
```

## Layout

```
index.mdx              landing page
quickstart.mdx          first claim, end to end
concepts/               claims, verdicts, receipts, the Merkle log, anchoring, trust levels, checking a receipt
connectors/             GitHub, http.url.status, Meta, Slack, X, what's coming
clients.mdx             client overview
sdks/                   Python and TypeScript SDK install guides
cli.mdx                 terminal client install guide
mcp.mdx                 local and hosted MCP server setup
alerts.mdx              Discord alerts
pipelines.mdx           planned: user-defined proof
self-hosting/           running your own node
security.mdx            data handling and vulnerability reporting
api-reference/          the HTTP API (openapi.json is generated from the server's code — don't edit it by hand)
docs.json               Mintlify navigation and site configuration
```

## License

- **Prose** (everything under `*.mdx` and `*.md`, and the images alongside them) is licensed
  **[CC-BY-4.0](LICENSE)** — reuse it, adapt it, just credit QED Proof.
- **Code samples** embedded in these docs are licensed **[Apache-2.0](LICENSE-CODE)**.
- Copyright © 2026 **Nuraveda Lab**.

## Links

- **[The app](https://qedproof.site/app)**
- **[qed-proof-core](https://github.com/Nuraveda/qed-proof-core)** — the open protocol and self-hostable node these docs describe
- **[Discord](https://discord.gg/9yhJs3EdCx)**
