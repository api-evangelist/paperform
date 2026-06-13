# Paperform

Paperform is an online form and payment platform offering a REST API for accessing form submissions, managing products and coupons, processing payments, configuring webhooks, and automating form-based workflows. The API supports two access tiers — Standard and Business — gated by subscription plan, with Papersign document signing available as an additional API surface.

## APIs

- **Paperform API** — Manage forms, submissions, partial submissions, products, coupons, webhooks, spaces, and translations. Standard API on Pro plan; Business API endpoints on Business/Enterprise plans.
- **Papersign API** — Manage electronic signature documents, folders, spaces, and webhooks (separate Papersign API plan required).

## Links

- [Website](https://paperform.co)
- [API Documentation](https://paperform.readme.io/reference/getting-started-1)
- [Pricing](https://paperform.co/pricing/)
- [GitHub Org](https://github.com/paperform-co)
- [Blog](https://paperform.co/blog/)
- [Status Page](https://paperform.statuspage.io/)
- [LinkedIn](https://www.linkedin.com/company/paperformco)
- [X / Twitter](https://x.com/paperformco)

## Authentication

All API requests require a Bearer token in the `Authorization` header. Generate your API key at [https://paperform.co/account/developer](https://paperform.co/account/developer).

## Rate Limits

Paperform enforces per-minute request limits. Exceeding the limit returns `429 Too Many Requests`. Monitor `X-RateLimit-Limit`, `X-RateLimit-Remaining`, `X-RateLimit-Reset`, and `Retry-After` response headers to manage backoff.

## Maintainer

Kin Lane — kin@apievangelist.com
