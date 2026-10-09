# Yorkstead Project Template

A provider-neutral, spec-driven development scaffold for Yorkstead projects.

## Bootstrap

1. Create or copy the application into this repository.
2. Complete `docs/project-profile.md`.
3. Replace the placeholders in `docs/verification.md`.
4. Add the real lint, typecheck, test, and build commands to `package.json` and `.github/workflows/verify.yml`.
5. Create the first feature under `specs/` using `.specify/templates/`.
6. Update `docs/handoffs/CURRENT.md` before the first implementation session.

Run `bun run yorkstead:check` after the project package manager and scripts are configured.

See `docs/instructions/` for new-project and existing-project migration guidance, and `docs/model-routing.md` for provider/model selection.
