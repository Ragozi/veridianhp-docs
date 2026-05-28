# Veridian Health Partners — Public Documentation

This repository contains the public-facing documentation for the
[Veridian Health Partners](https://veridianhp.com) platform, published at
[docs.veridianhp.com](https://docs.veridianhp.com) via Mintlify.

## What's here

- `mint.json` — Mintlify site configuration
- `introduction.mdx`, `quickstart.mdx`, `concepts.mdx` — getting started
- `bridge/*.mdx` — Veridian Bridge product documentation
- `api/*.mdx` — REST API reference
- `security/*.mdx` — security and HIPAA posture
- `troubleshooting.mdx`, `faq.mdx`, `changelog.mdx` — support
- `logo/` — brand assets used by the site

## What's NOT here

This is **only** the public documentation. None of the following live in
this repository:

- Veridian platform source code
- Internal compliance evidence (SOC 2 controls, risk register, IR runbook)
- Customer data of any kind
- Operational runbooks

Those live in private repositories under appropriate access control.

## Local preview

```bash
npm install -g mintlify
mintlify dev
```

Mintlify renders the site locally at http://localhost:3000.

## Contributing

This repository is currently maintained by the Veridian team. If you've
spotted an error, an unclear section, or a missing topic, please email
[docs@veridianhp.com](mailto:docs@veridianhp.com) or use the in-page
suggestion link.

## License

See [LICENSE](./LICENSE). All rights reserved. Documentation is provided as
reference material for Veridian customers and partners; redistribution
requires written permission.
