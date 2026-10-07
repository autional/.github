# Autional

**Open-core identity infrastructure** — authentication, accounts, multi-tenancy, and access control. Open-source portals and SDKs; commercial core. Build with AI, ship with confidence.

## Portals

| Portal | URL | About |
| --- | --- | --- |
| Sign In | [auth.autional.com](https://auth.autional.com) | Login, registration, multi-factor authentication, and single sign-on |
| User Center | [user.autional.com](https://user.autional.com) | Profile, security settings, devices, sessions, and authorization (sign-in required) |
| Admin Console | [admin.autional.com](https://admin.autional.com) | Centralized management of tenants, users, applications, and policies (sign-in required) |
| Security Center | [security.autional.com](https://security.autional.com) | Risk events, login audit, and security posture overview (sign-in required) |
| Platform Console | [platform.autional.com](https://platform.autional.com) | Platform-level tenant operations and global configuration (sign-in required) |
| Authenticator | [authenticator.autional.com](https://authenticator.autional.com) | TOTP- and passkey-based two-step verification (sign-in required) |
| Brand Portal | [brand.autional.com](https://brand.autional.com) | Tenant brand selection entry point |
| Trust Center | [trust.autional.com](https://trust.autional.com) | Security practices, data protection, and compliance progress |
| System Status | [status.autional.com](https://status.autional.com) | Real-time availability and incident history for all services |

## Sites

| Site | URL | About |
| --- | --- | --- |
| Website | [www.autional.com](https://www.autional.com) | Product overview, features, and pricing |
| Demo | [demo.autional.com](https://demo.autional.com) | Interactive demos of Autional services |
| Documentation | [docs.autional.com](https://docs.autional.com) | Product and integration docs |
| Developer Portal | [developer.autional.com](https://developer.autional.com) | SDK guides, quickstarts, and migration paths |
| API Reference | [reference.autional.com](https://reference.autional.com) | Interactive OpenAPI 3.0 reference for all 22 microservices |
| API Wiki | [wiki.autional.com](https://wiki.autional.com) | Endpoint documentation for every service |
| API | [api.autional.com](https://api.autional.com) | Unified backend entry point (BFF reverse proxy) |
| SDK on npm | [@autional/core](https://www.npmjs.com/package/@autional/core) | Core, framework adapters, and typed API clients |

## Repositories

| Group | Repositories | Stack |
| --- | --- | --- |
| Portals | [auth](https://github.com/autional/auth) · [user](https://github.com/autional/user) · [admin](https://github.com/autional/admin) · [security](https://github.com/autional/security) · [platform](https://github.com/autional/platform) · [authenticator](https://github.com/autional/authenticator) · [brand](https://github.com/autional/brand) · [trust](https://github.com/autional/trust) · [status](https://github.com/autional/status) | React 19 + Vite + TypeScript + Tailwind CSS |
| Sites | [web](https://github.com/autional/web) · [docs](https://github.com/autional/docs) · [developer](https://github.com/autional/developer) · [reference](https://github.com/autional/reference) · [wiki](https://github.com/autional/wiki) | Astro 5 + Tailwind CSS |
| SDK | [sdk](https://github.com/autional/sdk) | TypeScript · pnpm workspace · Changesets |
| Infrastructure | [api](https://github.com/autional/api) · [demo](https://github.com/autional/demo) · [cdn](https://github.com/autional/cdn) | Vercel reverse proxy and static asset CDN |
| Brand | [ui](https://github.com/autional-cn/ui) | Logos, favicons, design tokens, and UI guidelines — canonical design system (supersedes the archived `autional/ui`) |

Push to `main` deploys each site via Vercel.

## License

Open-source components (portals, design system, docs): [AGPL-3.0](https://github.com/autional/.github/blob/main/LICENSE) · SDK packages: MIT · Core identity services: commercial license

---

© 2026 Autional. All rights reserved.
