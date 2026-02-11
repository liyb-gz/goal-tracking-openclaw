# Tools & Workspace Conventions

## File System Layout

| Directory | Purpose |
|---|---|
| `context/` | Coaching guides, option menus, research notes (read-only reference) |
| `skills/` | Workspace skills for goal-setting and summary sessions |
| `profiles/` | User profiles — `profiles/{name}/profile.md` |
| `{year}/` | Goal and summary files organized by year/month |
| `memory/` | Daily memory logs |

## File Naming

| Type | Pattern | Example |
|---|---|---|
| Daily file | `{year}/{month}/{YYYY-MM-DD}.md` | `2026/02/2026-02-11.md` |
| Weekly file | `{year}/{month}/week-{N}.md` | `2026/02/week-06.md` |
| Monthly goals | `{year}/{month}/monthly-goals.md` | `2026/02/monthly-goals.md` |
| Yearly goals | `{year}/yearly-goals.md` | `2026/yearly-goals.md` |

## Goal File Format

Goals use an **Active / Retired** structure.

### Active Goals
Listed under an `## Active Goals` section. These are currently being pursued.

### Retired Goals
Moved to a `## Retired Goals` table when no longer active.

| Status | Meaning |
|---|---|
| Active | Currently pursued (implicit — lives in Active section) |
| Achieved | Completed successfully |
| Revised | Changed to something new (include `-> new version`) |
| Released | Intentionally let go (include reason) |
| Dropped | Abandoned without replacement |
| Evolved | Organically transformed (yearly goals only) |

### Revision Process
1. Move old goal to Retired Goals table with status, date, and context.
2. Add new goal to Active Goals with provenance: *revised {date}, was: "{old}"*
3. Update `Last updated` date at top of file.

## Build / Test

None. This is a markdown-only workspace — no build, lint, or test commands.
