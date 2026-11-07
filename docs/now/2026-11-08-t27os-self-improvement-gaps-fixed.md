# NOW -- t27os self-improvement gaps fixed (2026-11-08)

## t27os self-improvement gaps fixed

Letter A and letter S gaps closed per `specs/t27os/evolve.t27` decision rule:

- **Letter A (Architecture / ADR / SOUL)** — got its first instrument: an ADR index card widget at `specs/t27os/agents/adr_index.t27`, registered as widget 195 in `agent_parts.t27`, with `docs/adr/` added to letter A's `KEY_FILES` in `specs/agents/a.t27`. `G_NO_INSTRUMENT` gap closed for letter A.
- **Letter S (Specs / Standardization)** — now owns previously unowned paths: `external/`, root-level docs (`CONTRIBUTING.md`, `SECURITY.md`, `OWNERS.md`, `TASK.md`), `.claude/rules/`, and `gen/json/`. `G_UNOWNED` gap closed (priority 4); every path resolves to one owning letter.

What this does **not** establish:
- Widget health isn't ownership — lamps still need to be read from `domain_pulse.t27`.
- `gen/json/` is generated output, not hand-editable (L2).
- External vendored code isn't t27c-compiled.

## Related commits

- `7b3cd3e604` — letter A first instrument (ADR index card)
- `531663a374` — letter S owns unowned paths (G_UNOWNED)
