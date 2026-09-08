# Contributing to Customer Outreach Suite

## Setup

```bash
git clone https://github.com/0utLawzz/Customer-Outreach-Suite.git
cd Customer-Outreach-Suite
pnpm install
# Set DATABASE_URL, then:
pnpm --filter @workspace/db run push
pnpm --filter @workspace/api-server run dev
pnpm --filter @workspace/whatsapp-dashboard run dev
```

## Guidelines

- Use **pnpm** only (npm/yarn are blocked by preinstall).
- After OpenAPI changes: `pnpm --filter @workspace/api-spec run codegen`
- Run `pnpm run typecheck` and `pnpm run build` before opening a PR.
- Prefer focused PRs; do not commit production client PII.

## Security

See [SECURITY.md](SECURITY.md).
