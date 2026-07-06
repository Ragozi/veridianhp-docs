# Veridian Health Partners — Public Documentation

Documentation for [Veridian Health Partners](https://veridianhp.com),
published at [docs.veridianhp.com](https://docs.veridianhp.com) via Mintlify.

## Structure

```
introduction.mdx                        Company hub
veridian-motion/
  for-evaluators.mdx                    One-page evaluation guide
  product.mdx                           Flagship PT product hub
  overview.mdx                          Technical platform overview
  getting-started.mdx                   Facility rollout checklist
  inmate-kiosk-flow.mdx                 Authenticated inmate intake
  provider-dashboard.mdx                Staff roster, review, messaging
  facility-onboarding.mdx               Roster provisioning, SSO, onboarding runbook
  status-and-workflow.mdx               Status map and handoffs
  messaging.mdx                         Secure internal messaging
  roles-and-access.mdx                  MFA and role provisioning
  role-permissions.mdx                  Permission matrix by role
  ai-and-clinical-safety.mdx            Multi-LLM router, PT-review gate
  data-model-privacy.mdx                Entities, PHI, RLS, signed URLs
  deployment-and-kiosk.mdx              PWA install, kiosk hardening, MDM
security/*.mdx                          Compliance (enforced vs agency-provided)
docs.json                               Mintlify navigation
```

## Product

| Product | Status |
| --- | --- |
| **Veridian Motion** | Flagship — correctional PT platform (inmate kiosk + provider dashboard) at [veridianhp.com](https://veridianhp.com) |

## Local preview

```bash
npx mintlify dev
```

## Contributing

Email [docs@veridianhp.com](mailto:docs@veridianhp.com) or open a PR.
