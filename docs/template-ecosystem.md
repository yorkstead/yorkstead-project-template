# Yorkstead template ecosystem

| Repository | Role | Install and run |
| --- | --- | --- |
| yorkstead-project-template | Canonical methodology; no application | Node 24; npm run yorkstead:check; npm test |
| ys-base-template | Next.js/Neon/Drizzle/Better Auth web starter | npm ci; configure .env.local; npm run dev |
| ys-commerce-template | Shopify/Hydrogen + Next.js + Eve storefront | Node 24/pnpm 12.8.2; pnpm install --frozen-lockfile; configure Shopify values; pnpm dev |
| ys-mobile-template | Expo/React Native Android and iOS starter | Node 24; npm ci; npm run web, or native SDKs plus npm run android/ios |

The mobile repository requires owner creation because the integration lacks repository-create permission. The application template flags also require owner administration. Review implementation PRs before generating a client project; no changes are merged automatically.

All projects use the versioned development contract in docs/yorkstead-contract.md. Start with README, complete the profile, initialize a numbered feature, clarify spec/plan/tasks, verify task slices, and maintain CURRENT/SESSION handoffs. Keep one implementer per task and use independent review for substantial/high-risk work. Provider adapters preserve one source of truth.

Preserve application framework ownership, licenses, platform skills and lockfiles. Dependency advisories and manual native/hosted-service checks are tracked per starter; this standardization is not production release approval.
