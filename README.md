# Northstar Goods

Northstar Goods is a thoughtful everyday goods storefront with product browsing, category filters, Clerk authentication, a PostgreSQL/Drizzle catalog and cart, and a provider-aware checkout handoff.

## Stack

- React + Vite storefront
- Express + TypeScript API
- PostgreSQL + Drizzle ORM
- Clerk authentication
- pnpm workspace

## Development

Install dependencies with `pnpm install`, then run the storefront and API workflows:

```bash
pnpm --filter @workspace/api-server run dev
pnpm --filter @workspace/ecommerce-store run dev
```

Checkout remains provider-aware until a payment provider is connected.
