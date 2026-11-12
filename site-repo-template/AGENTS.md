# AGENTS.md — UniFlowHQ site repo

You work on one client website. Default to autonomy: build, research, test and fix on your own. Stop only at the gates below. If something is unclear and not a gate, make the sensible call, note it in the PR, and keep going.

## Source of truth
- GHL AI Studio is the home of the site. This repo is the Git Sync backup and the outside dev lane.
- Work on a branch and open a PR. Never force-push or rewrite `main`. Merging to `main` syncs to AI Studio, so `main` merges need Hector's approval on client-facing changes.

## Allowed tools and integrations
GitHub, Figma, Framer, Canva, Higgsfield, Vercel, Cloudflare, plus npm packages and public web research. Use them freely for design pulls, assets, previews and internal tooling.

## Fully autonomous (no approval needed)
- Writing and refactoring code, components, scroll effects and animations.
- Installing dependencies, running builds, tests, Lighthouse and accessibility checks.
- Researching the client's industry, competitors and references online.
- Pulling from Figma, generating draft assets in Canva or Higgsfield, building Framer prototypes.
- Vercel **preview** deployments and preview links for internal review.
- Opening branches and PRs, writing docs, fixing your own failed checks.
- On-page SEO and AEO: meta, schema, alt text, sitemap, internal links.

## Requires human approval (stop and ask)
1. **Go-live / production publish.** No production deploy, AI Studio publish, or merge of client-facing changes to `main` without Hector's GO.
2. **Domains and DNS.** No changes to production domains, DNS records, SSL or Cloudflare zone settings without Hector's GO.
3. **Client communication.** No email, text or message to the client or anyone outside UniFlowHQ. Draft it and hand it off.
4. **Money and accounts.** No purchases, paid plans, new sign-ups or paid API usage beyond existing accounts.
5. **Claims and content.** No invented testimonials, stats, licenses or client facts. Use only what's in the brief or supplied assets; flag gaps.
6. **Secrets.** Never commit, print or paste keys or tokens. Use environment variables.

## How to pause
State what's ready, link the preview, name the gate, and wait. Keep working on anything not blocked by that gate.

## Definition of done (before asking for the go-live GO)
Build passes, mobile and desktop checked, forms and links work, Lighthouse and accessibility checks reviewed, legal pages present, preview link in the PR.
