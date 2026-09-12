# Praveen Yadav

**Full-Stack Product Engineer** · Mumbai, India

I build products from interface to infrastructure — React applications, Node.js services, the databases behind them, realtime systems, and the servers they run on. Most of my work is multi-tenant platforms where the hard part isn't the screen: it's authorization that fails closed, realtime that survives contact with reality, and knowing what happens after deployment.

Currently a Full Stack Developer at **Informatic Connecting Tech Pvt. Ltd.**, working across an enterprise HRMS platform — React and Node modules, database migrations, realtime services, code reviews, releases and production troubleshooting.

---

## Selected work

### [SOL Assists](https://solassists.com) · multi-tenant education platform
Six services behind one application, serving office staff, teachers, students and guardians — each seeing a different product, from one server-enforced authorization model. Every request resolves identity → active access → permission → data scope, and the tenant context comes from the session, never the request.
`72 data models` · `246 REST routes` · `~1,180 tests` · [solassists.com](https://solassists.com) · [app](https://app.solassists.com)
<sub>React 19 · Node 24 · Express · Prisma · PostgreSQL · Redis · SSE · WebRTC · Oracle Cloud · Cloudflare · Prometheus/Grafana/Loki</sub>

### [QA Flow](https://qaflow.projectdock.in) · delivery & QA platform
Where a feature, its acceptance criteria, its tests, its defects and the conversation about them are one linked graph — enforced by an 11-stage workflow engine written as pure functions. Includes audio/video calling built from scratch on Socket.IO signalling, no Twilio or Agora.
`93 REST endpoints` · `271 automated tests` · `~46k lines` · solo-built over 9 months · [qaflow.projectdock.in](https://qaflow.projectdock.in)
<sub>React 19 · Vite · Node · Express · MongoDB · Socket.IO (2 namespaces) · WebRTC · COTURN · AWS S3</sub>

### TheRookieTraders · market research platform
A live NSE feed turned into a multi-user research workspace: twelve explainable scanners, open-interest analytics and candlestick charts. Every analytic is computed **once per minute** by a data service and served from precomputed tables, so cost doesn't grow with users.

It is **read-only by design and cannot place a trade** — the broker adapter exposes a frozen allowlist of read operations, and a test sweeps every source path for order methods and fails the build if one is reachable. Research and data only; not investment advice.
`12 scanners` · `50 tests` · `~1% CPU at 5,000 concurrent viewers`¹ · deployment rolling out
<sub>React 19 · Node 24 · SQLite (node:sqlite) · Server-Sent Events · Auth.js · nginx · PM2</sub>

### OrgzStack · enterprise HRMS *(professional work)*
A multi-tenant workforce platform — attendance, payroll and statutory reporting, leave, loans, approvals, RBAC, audit trails, live location. I'm a **major contributor** to the React SPA and core API within a team, and **sole author** of three services inside it: the socket/notification/location microservice, the internal admin console, and the observability stack.
`11 provisioned Grafana dashboards` · `Redis-backed socket fan-out` · `Haversine geofencing with batched persistence`
<sub>React · Node · MongoDB · Socket.IO · Redis · WebRTC · FCM · Docker · Terraform · AWS · Prometheus/Grafana/Loki</sub>

### Candidate Search & Relevance Engine · search service *(internal)*
A search service that ranks candidates against a requisition on five weighted factors and returns, with every result, the breakdown of *why* it scored what it did. Scores normalise against the criteria actually supplied — so a skills-only search stays comparable to a fully-specified one.
`222 curated synonym groups` · `typo tolerance` · `scheduled + queued index sync`
<sub>Node · Express · MongoDB · self-hosted Meilisearch</sub>

### [IPS Tech US](https://ipsincorp.com) · corporate staffing website *(professional work)*
Sole frontend developer. Nineteen detail pages — seven services, twelve industries — generated from a content layer and shared templates, on a Tailwind v4 token design system with no config file.
<sub>React · Vite · React Router · Tailwind v4 · Cloudflare · GitHub Actions</sub>

### [AITOM](https://ai-tom.com) · AI recruitment marketing site *(professional work)*
Sole frontend developer — design implementation, architecture, build and deployment of the marketing website. The recruitment product it markets was built by others.
<sub>React · Vite · React Router · Tailwind · Vercel</sub>

<sub>¹ Measured on Apple silicon against an isolated instance with a 14-symbol catalogue — a lab benchmark, not production telemetry.</sub>

---

## What I work with

**Frontend** — React · TypeScript · Next.js · Vite · Redux Toolkit · TanStack Query · Tailwind · MUI
**Backend** — Node.js · Express · REST · Socket.IO · WebRTC · SSE · JWT/RBAC · multi-tenancy
**Data** — MongoDB · PostgreSQL · Prisma · Mongoose · Redis · SQLite · Meilisearch · migrations & indexing
**Cloud & DevOps** — AWS · Oracle Cloud · Cloudflare · Docker · Terraform · GitHub Actions · Nginx · PM2 · Linux
**Observability** — Prometheus · Grafana · Loki · structured logging · health checks

---

## How I work

I try to build past the happy path. Before I call something done I want to know what happens when the API fails, whether another tenant can reach this record, what a partial migration leaves behind, how a release rolls back, and what shows up in the logs at 2am.

Three of my projects have gone through a deliberate self-audit — going looking for my own mistakes and then writing down what I found. That habit has caught more real problems than any code review I've sat in.

Before engineering I spent several years around Nifty options and the markets. It's the reason TheRookieTraders exists and why it refuses to display a number it can't stand behind — but it's domain context, not engineering experience, and I don't count it as such.

---

## Reach me

[![Email](https://img.shields.io/badge/Email-ypraveen760@gmail.com-B4650E?style=flat-square&logo=gmail&logoColor=white)](mailto:ypraveen760@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-praveen760-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/praveen760)
[![YouTube](https://img.shields.io/badge/YouTube-TheRookieTraders-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@therookietradersofficial)

---

<details>
<summary>GitHub stats</summary>

![](https://github-readme-stats.vercel.app/api?username=ypraveen760&theme=tokyonight&hide_border=true&include_all_commits=false&count_private=false)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=ypraveen760&theme=tokyonight&hide_border=true&layout=compact)

<sub>Most of my substantial work lives in private and company repositories, so public contribution graphs tell only part of the story.</sub>

</details>
