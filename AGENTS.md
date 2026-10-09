# Yorkstead Development Operating System

This repository uses specification-first, interruption-tolerant development.

## Source of truth

- Product behavior is defined by the active specification in `specs/`.
- Architecture decisions belong in the specification plan and decision records.
- Tasks are small, independently verifiable slices. Keep task status current.
- Do not make product changes without updating the relevant spec or recording why the change is out of scope.

## Working agreement

1. Start with `docs/handoffs/SESSION-START.md`.
2. Read the active spec, plan, and task list before editing.
3. Prefer the smallest reversible change.
4. Run the repository verification commands documented in `docs/verification.md`.
5. End with `docs/handoffs/SESSION-END.md`; leave the next action explicit.

## Agent boundaries

Agents may inspect, plan, implement, test, and review within the current task. They must not silently change product scope, secrets, deployment settings, or data without explicit task authorization. See `docs/agent-roles.md` for provider-neutral role guidance.

## Local skills

Reusable playbooks live under `.agents/skills/`. Each skill must state its inputs, procedure, verification, and handoff output.
