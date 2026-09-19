# OurPocket developer documentation

This Mintlify site is the user-facing guide for the normalized OurPocket financial API. It covers Sandbox and Production, provider connections, payments and refunds, wallets and simulated transfers, events and webhooks, routing, inspection, and the private TypeScript source SDK.

## Preview and validate

```bash
npx mintlify dev
npx mintlify validate
```

The backend is the source of truth for routes and behavior (`infra/src/financial`, project/provider controllers, and `/docs`). The TypeScript client is `ourpocket/packages/sdk/src/index.ts`. Keep the site factual: catalog visibility is not execution support, the SDK is not published, and pricing or future domains are not API features.
