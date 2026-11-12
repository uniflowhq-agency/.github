# Website repo conventions (UniFlowHQ)

**Source of truth:** each client site lives in GHL AI Studio inside the client's UniFlow sub-account.
GitHub is the backup and the outside-developer lane (Cursor), connected through AI Studio Git Sync.

## Naming
- Client sites: `site-<client-slug>` (lowercase, hyphens), e.g. `site-sol-y-cielo`
- Internal agency tools: `uniflow-<tool>` (moved in later; website workflows come first)

## How a site repo is created
1. Client is sold and set up in GHL; domain bought in the client sub-account.
2. AI Studio project created in that sub-account.
3. AI Studio > Git tab > Connect GitHub > choose this organization. AI Studio creates a NEW private repo (it cannot import an existing one). Rename it to `site-<client-slug>` if needed.
4. Sync is two-way: edits in AI Studio and pushes to `main` stay in step.

Starter files for each new site repo: [`site-repo-template/`](site-repo-template/README.md).

## Rules
- All site repos are private.
- Never commit secrets; use AI Studio Secrets.
- Teams: `web-builders` (write on site repos), `ops` (read/triage). Org owners: Hector.
