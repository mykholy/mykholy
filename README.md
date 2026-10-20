<p align="center">
  <a href="https://mykholy.github.io/" title="Visit Ahmed Elkholy's engineering portfolio">
    <img src="https://mykholy.github.io/assets/profile/github-profile-banner.svg" alt="Ahmed Elkholy — Senior Backend Engineer specializing in Laravel, SaaS, Shopify, payments and reliability" width="100%" />
  </a>
</p>

<h3 align="center">Senior Backend Engineer · PHP / Laravel · SaaS &amp; Production Systems</h3>

<p align="center">
  Cairo, Egypt · Working with teams and clients worldwide
</p>

<p align="center">
  <a href="https://mykholy.github.io/"><strong>Portfolio</strong></a>
  &nbsp;·&nbsp;
  <a href="https://mykholy.github.io/assets/cv/Ahmed_Elkholy_Senior_Backend_Engineer_CV_2026.pdf">Download CV (PDF)</a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/mykholy">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:mykholys30@gmail.com">Email</a>
</p>

---

I design, build and operate **backend systems where reliability, correctness and maintainability matter**. My work spans commerce, SaaS, Shopify apps, AI/media platforms, EdTech, multi-tenant messaging, payment integrations and operational software.

I enjoy the parts of engineering that go beyond a successful demo: clear domain boundaries, authorization, state transitions, observability, hard-to-reproduce failures and a deployment path the team can maintain.

### Engineering scope at a glance

| Production scope | Where it comes from |
| :--- | :--- |
| **5+ years** | Hands-on backend engineering across product and client teams |
| **~100K requests/day** | Multi-vendor commerce workload at Jomlakwt |
| **260+ REST APIs** | Commerce, orders, finance, sellers and operational flows |
| **100+ catalog QA rules** | VeriCatalog, an embedded Shopify SaaS |
| **30+ payment integrations** | `mykholy/paymentgateway` open-source toolkit |
| **9 messaging channel types** | Multi-tenant omnichannel CRM architecture |

*These figures describe specific systems and engineering scope, not personal vanity metrics or performance guarantees.*

## Selected engineering work

### Products & production platforms

**[VeriCatalog — Shopify catalog QA SaaS](https://mykholy.github.io/#work)**  
Founder / Lead Engineer. An embedded Shopify app for auditing catalog quality with deterministic rules across pricing, identifiers, media, shipping, content and localization. I designed cursor-based scans, Redis-backed queues and locks, retries, auditability and guarded remediation flows, including preflight and verification stages.  
`Laravel` · `Shopify Admin GraphQL` · `Redis` · `MySQL` · `SaaS`

**[Tik Video — AI media generation platform](https://mykholy.github.io/#work)**  
Backend architecture spanning 11 domains including identity, projects, media, subscriptions, orders and payments. Integrations with multiple media providers, asynchronous generation pipelines, webhooks/polling, credit settlement and failure recovery.  
`Laravel 12` · `Nuxt 4` · `Queues` · `S3` · `Payments` · `AI APIs`

**[Jomlakwt — multi-vendor commerce](https://jomlakwt.com/)**  
Backend engineering for catalog, sellers, checkout, delivery, wallets, installments and refunds. Work included a 260+ API surface, payment/BNPL integrations, database tuning, production incident diagnosis and system recovery.  
`Laravel` · `MySQL` · `REST APIs` · `Payments` · `Nginx`

**[Culture Bridges — events & registration](https://culturebridgesa.com/)**  
Coordinated API, administrative, organizer and public-facing workflows for registration, event operations, permissions, check-in and background processing.  
`Laravel` · `Nuxt` · `API Design` · `Event Workflows`

**Omnichannel CRM — multi-tenant messaging**  
Provider-driver architecture covering WhatsApp, Messenger, Instagram, Gmail/email, Telegram, SMS, web chat, local CRM and custom APIs. Focused on webhooks, tenant isolation, deduplication, conversation resolution, queues and delivery recovery.  
`Laravel` · `Meta Graph API` · `Gmail API` · `Twilio` · `Redis`

**Other systems:** TrippleStock (POS and inventory correctness), Dorosak / IBAL / eMicroLearn (EdTech, subscriptions and integrations), Sajah (events and ticketing), gym management with biometric reconciliation, financial workflows and electronic invoicing.

[Explore all 17 projects and technical case studies →](https://mykholy.github.io/#work)

## Open source & reusable engineering

My public repositories focus on problems I repeatedly encounter in production applications.

| Project | Why it exists |
| :--- | :--- |
| **[Laravel FlowGuard](https://github.com/mykholy/laravel-flowguard)** | Guarded operations, idempotency, webhook inbox/outbox and reconciliation of uncertain outcomes. |
| **[Laravel AccessProof](https://github.com/mykholy/laravel-accessproof)** | HTTP-based authorization regression tests for IDOR/BOLA and cross-tenant isolation. |
| **[Laravel LeakProof](https://github.com/mykholy/laravel-leakproof)** | Catch sensitive fields and accidental data exposure in Laravel JSON API responses. |
| **[Laravel FailureLab](https://github.com/mykholy/laravel-failurelab)** | Deterministic fault injection and recovery assertions for integration tests. |
| **[Mavvix Safe Actions](https://github.com/mykholy/mavvix-safe-actions)** | Safer, reviewable high-impact admin actions for Laravel and Filament. |
| **[Laravel PaymentGateway](https://github.com/mykholy/paymentgateway)** | Integration surface for 30+ payment providers. |
| **[Laravel Paymob](https://github.com/mykholy/laravel-paymob)** | Reusable Paymob card and wallet payment flows. |

If you are evaluating one of these libraries, start with its **README, examples, tests and release notes**. Feedback, bug reports and contributions are welcome.

## Technical focus

| Area | Tools & practices |
| :--- | :--- |
| **Backend & architecture** | PHP 8.x, Laravel, SOLID, modular domains, REST, GraphQL, OpenAPI, multi-tenancy, webhooks |
| **Data & reliability** | MySQL, PostgreSQL, Redis, transactions, locks, queues, retries, idempotency, reconciliation, caching |
| **Authentication & security** | Sanctum, JWT, OAuth, RBAC, tenant isolation, webhook signatures, secure integrations |
| **Integrations** | Shopify Admin GraphQL, payment providers, Meta, Twilio, Gmail, AI/media APIs |
| **Infrastructure** | Docker, Linux, Nginx, AWS/S3, DigitalOcean, Cloudflare, Laravel Forge, CI/CD |
| **Testing & quality** | PHPUnit, Pest, PHPStan/Larastan, code review, incident RCA, observability |
| **Collaboration** | Nuxt / Vue, Filament, Livewire, Flutter-facing APIs, architecture and API documentation |

## Experience

- **Grids Apps — Senior Backend Engineer (2021–present):** Backend delivery and technical ownership across enterprise learning, SaaS, commerce and operational platforms.
- **Arrays — Senior Backend Engineer (2025–2026, part-time):** AI/media, event workflows, payment and asynchronous provider integrations.
- **Jomlakwt — Senior Backend Engineer (2023–2025, part-time):** High-volume commerce APIs, payment operations, performance and reliability.

**Education:** Bachelor of Computer Science, Menoufia University, Egypt.

## How I work

1. **Understand the business boundary.** Clarify actors, permissions, state transitions and failure modes before writing APIs.
2. **Build for recoverability.** Treat retries, idempotency, reconciliation, structured logs and observability as engineering requirements.
3. **Keep the implementation understandable.** Favor explicit contracts, maintainable modules, tests and documented trade-offs.
4. **Own the production outcome.** Profile performance, investigate incidents, fix root causes and leave a system the next engineer can safely operate.

---

### Building something that needs to work in production?

I work on **Laravel backend development, SaaS architecture, Shopify integrations, payment workflows, technical reviews and production reliability**.

**[Portfolio & project case studies](https://mykholy.github.io/)** · **[Professional CV](https://mykholy.github.io/assets/cv/Ahmed_Elkholy_Senior_Backend_Engineer_CV_2026.pdf)** · **[Email me](mailto:mykholys30@gmail.com?subject=Backend%20engineering%20inquiry)**

<sub>Selected product work includes private/client codebases. Public GitHub repositories are linked explicitly above; the remaining descriptions refer to engineering work rather than published source code.</sub>