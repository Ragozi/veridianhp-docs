# Veridian Health Partners — Public Documentation

Documentation for [Veridian Health Partners](https://veridianhp.com),
published at [docs.veridianhp.com](https://docs.veridianhp.com) via Mintlify.

## Structure

```
introduction.mdx                        Company hub (VeridianHP)
veridian-motion/
  product.mdx                           Flagship PT product hub
  overview.mdx                          Technical platform overview
  inmate-kiosk-flow.mdx                 Authenticated inmate intake
  provider-dashboard.mdx                Staff roster, review, messaging
  roles-and-access.mdx                  Five roles, MFA, provisioning
  ai-and-clinical-safety.mdx            Multi-LLM router, PT-review gate
  data-model-privacy.mdx                Entities, PHI, RLS, signed URLs
  deployment-and-kiosk.mdx              PWA install, kiosk hardening, MDM
security/*.mdx                          Compliance (enforced vs agency-provided)
docs.json                               Mintlify navigation
```

## Product

| Product | Status |
| --- | --- |
| **Veridian Motion** | Flagship — active PT platform (inmate kiosk + provider dashboard) at [veridianhp.com](https://veridianhp.com) |

## Local preview

```bash
npx mintlify dev
```

## Contributing

Email [docs@veridianhp.com](mailto:docs@veridianhp.com) or open a PR.
