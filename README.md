# caw-universal-systems

Per-client configuration and brand assets for the Universal Systems Inc. (USI) tenant of the Cyber Attainment Worksheet platform.

**This repository does not deploy.** All deployable code lives in [USI-ONE/cyber-attainment-worksheet](https://github.com/USI-ONE/cyber-attainment-worksheet). The Vercel project `caw-universal-systems` deploys *that* repo with `TENANT_SLUG=universal-systems`.

## What's here

```
caw.config.json   Tenant slug, display name, hostnames, active frameworks, brand theme
assets/logo.svg   Yin-yang S mark in the Juniper-to-Nebula gradient (per 2026 USI brand book)
templates/        (empty) per-tenant board-pack PPTX templates land here
```

## Brand

Per the 2026 USI Brand Guidelines:

| Token | Hex | Use |
|---|---|---|
| Juniper | `#458C5E` | Primary accent (replaces the platform default gold) |
| Nebula | `#3B697A` | Secondary accent / gradient pair |
| Desert | `#A68A56` | Warm tertiary accent |
| Void | `#3C3C3C` | Primary text on light backgrounds |
| Salt | `#E5E5E5` | Light surface |
| Gradient | Juniper → Nebula | Feature treatment (logo, headers) |

Tagline: **"Proudly serving for 37 years."**

The platform's dark navy chrome is retained for now; the USI palette is injected via `brand_config.theme` and applied as CSS custom properties at the layout level. A deeper light-theme rework (white surfaces, Aptos typography, mountain imagery) is a future project.

## USI's special status

USI is **not** a Bestige PortCo — it is the operator of this platform. USI runs its own NIST CSF 2.0 attainment program in this tenant. USI does not appear in any Bestige portfolio rollup unless USI explicitly shares a snapshot with Bestige.

## Onboarding status

| Step | Status |
|---|---|
| Repo created | ✅ |
| Real logo committed | ✅ Yin-yang S mark (gradient) |
| Brand theme set | ✅ Juniper / Nebula / Desert in `caw.config.json` |
| Vercel project created | ✅ |
| Supabase tenant row inserted | ✅ |
| `tenant_frameworks` row (NIST CSF 2.0) | ✅ |
| Editor membership granted to CIO | ✅ via domain whitelist (`usicomputer.com` → viewer; promoted) |
| `domain_whitelist` row | ✅ `usicomputer.com` |
| Cloned data from CL baseline | ✅ Phase 3 |

## Contacts

- **Editor (CIO):** Chris Wall (`cwall@usicomputer.com`)
- **Viewer distribution group:** _to be defined_
- **Viewer email domain:** `usicomputer.com` (auto-grants viewer on signup)
