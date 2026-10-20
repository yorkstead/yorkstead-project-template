# Yorkstead Project Template

A provider-neutral, spec-driven development scaffold for Yorkstead projects.

## Bootstrap

1. Create or copy the application into this repository.
2. Complete `docs/project-profile.md`.
3. Replace the placeholders in `docs/verification.md`.
4. Add the real lint, typecheck, test, and build commands to `package.json` and `.github/workflows/verify.yml`.
5. Create the first feature under `specs/` using `.specify/templates/`.
6. Update `docs/handoffs/CURRENT.md` before the first implementation session.

Run `npm run yorkstead:check` after the project package manager and scripts are configured.

See `docs/instructions/` for new-project and existing-project migration guidance, and `docs/model-routing.md` for provider/model selection.

## Shared development contract

Read [the versioned contract](docs/yorkstead-contract.md) before adapting this methodology. Use the base starter for Next.js/Neon, commerce for Shopify, and mobile for Expo; this canonical repository is the process scaffold. No AI provider CLI is required.

Run `npm run yorkstead:init -- 001-first-slice` to create draft specification, plan and tasks safely. Repeating the command preserves existing work. Run `npm run yorkstead:check` and `npm test`; then record the active task and next action in `docs/handoffs/CURRENT.md`.
