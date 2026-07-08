# CaseCloud ↔ QuickBooks Online — Integration Guide

A client-facing reference tool explaining how the CaseCloud (Advologix) matter-management platform connects to QuickBooks Online via the DBSync middleware. Built and maintained by Advocate Cloud Solutions.

## Live URL

Deployed via Vercel. Production: `https://casecloud-qb.advocatecloudsolutions.com`

## Contents

- `index.html` — Self-contained single-page HTML tool. No build step required.

## Tool structure

A nine-section navigable guide:

1. **Overview** — the CaseCloud ↔ DBSync ↔ QuickBooks flow (with diagram)
2. **Object map** — what CaseCloud object maps to what QuickBooks record
3. **What syncs** — what flows and what deliberately does not
4. **Cost lifecycle** — expenses paid by operating, reimbursed by trust
5. **Write-offs** — the Non-Ledger path and write-off fields
6. **Settlement distribution** — the automated disbursement waterfall (with diagram)
7. **Key fields** — the fields we configure
8. **Golden rules** — the do's and don'ts
9. **Setup process** — the ACS implementation phases

## Maintenance

Vercel deploys automatically on push to `main`.

---

© 2026 Advocate Cloud Solutions · *Supercharging Legal Efficiency*
