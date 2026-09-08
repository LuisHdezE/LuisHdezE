# Hi, I'm Luis Hernández 👋

### Software Engineer · Backend Architecture · Legacy Modernization

I build and modernize business software with a strong focus on **Clean Architecture, transactional integrity, API design, automated verification, and maintainable delivery workflows**.

My recent work spans **.NET/C#**, **TypeScript/Node.js**, **React**, **PHP/WordPress**, **PostgreSQL**, and **MySQL**, with projects structured as engineering case studies rather than isolated code samples.

---

## Featured release

### 🛡️ Insurance Claims Legacy Modernization — v0.2.0
**TypeScript · NestJS · React · PostgreSQL · Clean Architecture + Ports & Adapters**

A governed modernization case study showing how a new claims experience can evolve while remaining decoupled from a simulated legacy dependency.

Current release highlights:

- published **Claims Operations Experience v0.2.0**;
- operations Dashboard, Claims Workspace, Claim Detail and Tasks Workspace;
- real `ClaimTask` lifecycle, Claim Timeline and Evidence Attention projections;
- explicit separation between task completion and authoritative Claim lifecycle transitions;
- `api-v1-r2`: **15 effective operations**, composed as 10 immutable base operations + 5 additive operations;
- PostgreSQL-backed authoritative modern workflow;
- separate REST and read-only MCP presentation boundaries;
- fresh Chrome 152 desktop/mobile review with 12 committed screenshots;
- human-governed release publication with preserved historical MVP evidence.

➡️ [Explore the repository](https://github.com/LuisHdezE/InsuranceClaims)  
🏷️ [View the published v0.2.0 release](https://github.com/LuisHdezE/InsuranceClaims/releases/tag/v0.2.0)

---

## What I focus on

- **Backend & API engineering** with explicit Domain, Application and Infrastructure boundaries
- **Clean Architecture + Ports & Adapters**
- **Legacy modernization** through controlled coexistence and replaceable adapters
- **Transactional workflows**, idempotency, concurrency control, audit and outbox patterns
- **Contract-first APIs**, OpenAPI, integration testing and CI evidence
- **Frontend integration** with React and business-facing interfaces
- **Evidence-driven delivery** where architecture, QA, limitations and release state are visible in the repository

---

## Selected work

### 🧾 eFactura
**C# · .NET 10 · PostgreSQL · MySQL · Clean Architecture**

A modernization effort around an electronic-invoicing and transactional-sales platform for Uruguay.

Engineering themes include:

- explicit Domain, Application, Infrastructure and Web API boundaries;
- PostgreSQL/MySQL persistence verification;
- Sales, Inventory, CAE and Finance foundations;
- fiscal-calculation boundaries;
- idempotency, audit, outbox, optimistic concurrency and transactional rollback guarantees;
- unfinished external signing/provider transport kept clearly separated from implemented capabilities.

➡️ [Explore eFactura](https://github.com/LuisHdezE/efactura)

---

### 🛒 ZoFloridane
**PHP · WordPress · WooCommerce · JavaScript · UI/UX modernization**

A real-world storefront modernization focused on improving a WordPress/WooCommerce purchasing experience while preserving existing business behavior.

Engineering themes include:

- mobile-first UI/UX redesign;
- custom storefront work around an existing WordPress architecture;
- cart, locality, delivery and Zelle-oriented purchase flows;
- repository boundaries that exclude production credentials and customer/order data;
- Git-based workflow with local validation before deployment.

➡️ [Explore ZoFloridane](https://github.com/LuisHdezE/ZoFloridane)

---

## Engineering principles

```text
Domain rules belong in the domain.
Infrastructure is replaceable.
External systems sit behind ports.
The client does not become the source of truth.
Critical writes are transactional.
Retries must be safe.
Tests should prove boundaries, not only happy paths.
CI evidence matters.
```

---

## Core technologies

**Backend**  
`C#` · `.NET` · `TypeScript` · `Node.js` · `NestJS` · `PHP`

**Frontend**  
`React` · `TypeScript` · `JavaScript` · `WordPress` · `WooCommerce`

**Data**  
`PostgreSQL` · `MySQL` · `Entity Framework Core` · `Prisma`

**Architecture & delivery**  
`Clean Architecture` · `Ports & Adapters` · `REST` · `OpenAPI` · `CI/CD` · `GitHub Actions` · `Automated Testing`

---

## How I present engineering work

I am packaging my strongest projects as reproducible case studies with:

- clear problem framing;
- explicit architecture decisions and boundaries;
- implementation and API evidence;
- CI and QA results;
- screenshots and runnable verification paths;
- honest limitations and non-claims;
- governed release history where appropriate.

The goal is simple: when someone opens a repository, they should quickly understand **what problem was solved, how the system is structured, what has been proven, and what has deliberately not been claimed**.

---

## Contact

GitHub: [@LuisHdezE](https://github.com/LuisHdezE)

Portfolio website: **EliasWorks refresh in progress**

---

<sub>Portfolio claims are intentionally bounded to capabilities already implemented and evidenced in the referenced repositories.</sub>
