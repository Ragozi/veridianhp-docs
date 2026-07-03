# Veridian Health Partners — Public Documentation

This repository contains the public-facing documentation for
[Veridian Health Partners](https://veridianhp.com), published at
[docs.veridianhp.com](https://docs.veridianhp.com) via Mintlify.

## Structure

```
introduction.mdx              Company hub — product family overview
veridian-health/*.mdx           Veridian Health (PT consults for inmates)
veridian-billing/overview.mdx   Veridian Billing (coming soon)
security/*.mdx                  Shared security & HIPAA (all products)
troubleshooting.mdx, faq.mdx, changelog.mdx
docs.json                       Mintlify site configuration
logo/                           Brand assets
```

## Products

| Product | Status | Docs |
| --- | --- | --- |
| **Veridian Health** | In development | `/veridian-health/*` |
| **Veridian Billing** | Coming soon | `/veridian-billing/overview` |

## Local preview

```bash
npx mintlify dev
```

Mintlify renders the site locally at http://localhost:3000.

## Contributing

Spotted an error, unclear section, or missing topic? Email
[docs@veridianhp.com](mailto:docs@veridianhp.com) or open a PR.

## License

See [LICENSE](./LICENSE). Documentation is provided as reference material
for Veridian customers and partners.
