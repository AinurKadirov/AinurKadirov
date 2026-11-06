# Ainur Kadirov

**Backend developer · NestJS / TypeScript · marketplaces**

~5.5 years commercial Node.js. I build seller APIs, catalogs, parsers, and checkout/delivery edges that stay up when the provider lags.

Based in **Turkey**. Open to **remote / contract from Turkey**, or relocation. Russian native, English **B2**.

Hire me for NestJS production work — not landing pages.

---

## Для рекрутера (RU)

Backend на **Node.js / NestJS / TypeScript**, Middle/Senior, **~5 лет 5 месяцев** коммерческого опыта (на сентябрь 2026). Собрал backend маркетплейса стройматериалов: каталог, офферы, парсеры поставщиков, Excel-прайсы, заказы, TBank и CDEK. Параллельно — высоконагруженный SaaS для селлеров Wildberries и Ozon: модуль A/B карточек с нуля, синк порядка **10 млн** карточек, ClickHouse около **6 ТБ**. До этого — PostgreSQL-домен корпоративной TMS на Fastify и GraphQL в BARS Group. Сам веду кабинеты на WB/Ozon. Ищу следующий шаг, не «убегаю». Формат: remote/контракт из Турции или релокация. Резюме: [hirify.me/aynurkadirov](https://hirify.me/aynurkadirov).

---

## Public code

| Repo | What to look at |
| --- | --- |
| **[ozon-seller-tools](https://github.com/AinurKadirov/ozon-seller-tools)** | Personal Ozon shops: unit economics, min prices, promo exit, ads, FBO supply, card-profit UI. Live costs and keys are not in git. |
| **[shop-ledger](https://github.com/AinurKadirov/shop-ledger)** | Day close for a physical store: cash, safe, expenses, timesheet. Money in integer kopecks, roles, multi-store. Demo users in README. |
| **[night-desk-web](https://github.com/AinurKadirov/night-desk-web)** | Ambient workspace mixer. Guest plays with no login; accounts get a Postgres kanban. Docker, Prisma, tests. |
| **[crypto-parser](https://github.com/AinurKadirov/crypto-parser)** | Go backtester on public Binance candles. Research tool: no keys, no live orders. |

Employer code is not here. Company internals stay private.

---

## Production work (code private)

**Marketplace platform (Stroymega Market).** I assembled the backend of a live building-materials marketplace: catalog and offers, supplier-site parsers, Excel pricelists and bulk publish, orders, TBank webhooks, CDEK. NestJS microservices talking over AMQP (RPC/events). On the parser side: **33** suppliers wired to the registry, **291k** product–supplier links, anti-bot/proxies, article matching — not a one-off Cheerio script. Excel is the catalog protocol (streamed ExcelJS), not “export a report”.

**Seller-analytics SaaS (Wildberries / Ozon).** Current role, Oct 2024 – present. Platform: 100k+ users, ~37k shops. Designed the card/media **A/B** module from scratch (API, rotation, stats, scheduler, ads link). WB/Ozon API syncs: products, stock, campaigns, analytics. Incremental sync of ~**10M** product cards (TTL, batches of 100, concurrency caps, collector writes). Daily stats: hundreds of millions of MongoDB documents (snapshot + bulk upsert). Search/shelf parse pipeline into ClickHouse (~**6 TB**). I also sell on WB/Ozon myself, so I check flows in a real seller cabinet.

**Corporate TMS (ООО «Лучшее приложение», Jun 2023 – Oct 2024).** Internal transport for NLMK: request types, catalogs, dynamic forms. PostgreSQL domain from scratch: UUID PKs, NUMERIC, soft-delete, FKs, composite UNIQUE, indexed hot queries, transactional upserts with nested entities. Idempotent Kafka consumer. Fastify/TypeScript microservices, Excel catalog import, factory TMS HTTP integration.

**BARS Group (Jul 2021 – Jun 2023).** GraphQL APIs on NestJS (schemas, resolvers, types). Junior → developer in the same company.

---

## Hire me for

- **Marketplace APIs** — products, stock, prices, orders, webhooks. Wildberries, Ozon, custom REST. Map provider payloads into business status.
- **Catalog / parsers / Excel** — supplier sites → card → registry → storefront. Dirty pricelists, bulk publish, article matching, LLM-assisted Excel split (structured JSON, not a chat UI).
- **NestJS on prod** — hanging requests, broken webhooks, queues, live Mongo/Postgres. I read logs.

Not a frontend-first hire. Not a tech-lead/CTO ask.

---

## Stack

**Use in production:** Node.js, NestJS, Fastify, TypeScript, REST, GraphQL, PostgreSQL, MongoDB, ClickHouse, Redis, Kafka, RabbitMQ / AMQP, Docker, JWT, Nginx, MinIO, ExcelJS, Linux.

**Personal / secondary:** React + Vite, Prisma, Go (crypto-parser), Telegram bots. Cursor + coding agents with repo rules; architecture and prod logic I review myself.

**Do not assume:** AWS/GCP/Terraform as my core, Stripe/StoreKit, commercial React as a job, Python/Scrapy as the parser stack, 6+ years Node, staff/principal.

---

## Contact

| | |
| --- | --- |
| Resume | [hirify.me/aynurkadirov](https://hirify.me/aynurkadirov) |
| Email (applications) | [ainur.kadirov.backend@gmail.com](mailto:ainur.kadirov.backend@gmail.com) |
| Email (CV) | [kadirovajnur238@gmail.com](mailto:kadirovajnur238@gmail.com) |
| Telegram | [t.me/kadirov_ar](https://t.me/kadirov_ar) |
| GitLab | [gitlab.com/kadirovajnur238](https://gitlab.com/kadirovajnur238) |

Write in Russian or English. Full-time backend roles, or a focused marketplace contract.
