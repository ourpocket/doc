# OurPocket documentation

This directory contains the Mintlify documentation for the OurPocket dashboard, management API, runtime wallet API, provider routing, webhooks, and operations.

## Preview locally

```bash
npx mintlify dev
```

Open `http://localhost:3000`.

## Validate

```bash
npx mintlify validate
```

## Content principles

- Document implemented behavior separately from planned behavior.
- Distinguish user JWTs, project API keys, provider credentials, and webhook secrets.
- Treat `/v1/transactions` and direct `/v1/wallets/*` operations as different persistence models.
- Do not claim outbound webhook delivery or signing until implemented.
- Keep examples free of real credentials and personal data.
