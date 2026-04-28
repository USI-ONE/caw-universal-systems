# caw-universal-systems

Per-client configuration and brand assets for the Universal Systems Inc. (USI) tenant of the Cyber Attainment Worksheet platform.

**This repository does not deploy.** All deployable code lives in [USI-ONE/cyber-attainment-worksheet](https://github.com/USI-ONE/cyber-attainment-worksheet). The Vercel project `caw-universal-systems` deploys *that* repo with `TENANT_SLUG=universal-systems`.

## What's here

```
caw.config.json   Tenant slug, display name, hostnames, active frameworks, contact placeholders
assets/logo.svg   Placeholder logo — replace with the real USI brand asset before launch
templates/        (empty) per-tenant board-pack PPTX templates land here
```

## USI's special status

USI is **not** a Bestige PortCo — it is the operator of this platform. USI runs its own NIST CSF 2.0 attainment program in this tenant. USI does not appear in any Bestige portfolio rollup unless USI explicitly shares a snapshot with Bestige.

This distinction is enforced by the architecture: the platform has no notion of "fund membership." There is only **explicit snapshot sharing**, tenant by tenant, snapshot by snapshot. USI never creates a share to Bestige unless it actively chooses to.

## Onboarding status

| Step | Status |
|---|---|
| Repo created | ✅ |
| Real logo committed | ⬜ Currently a placeholder SVG |
| Vercel project created | ⬜ Manual — see `docs/setup/vercel.md` in template repo |
| Supabase tenant row inserted | ⬜ Manual — see `docs/runbooks/onboard-tenant.md` |
| `tenant_frameworks` row (NIST CSF 2.0) | ⬜ |
| Editor membership granted to CIO | ⬜ |
| `domain_whitelist` row | ⬜ Recommended: `usi-one.com` or whichever domain USI uses |

## Contacts

- **Editor (CIO):** _to be filled in_
- **Viewer distribution group:** _to be filled in_
- **Viewer email domain:** _to be filled in_
