# Hi, I'm Luis Hernández 👋

### Software Engineer · Backend Architecture · Legacy Modernization

I build and modernize business software with a strong focus on **Clean Architecture, transactional integrity, API design, automated verification, and maintainable delivery workflows**.

My recent work spans **.NET/C#**, **TypeScript/Node.js**, **React**, **PHP/WordPress**, **PostgreSQL**, and **MySQL**, with projects designed as real engineering case studies rather than isolated code samples.

---

## What I focus on

- **Backend & API engineering** with explicit domain and application boundaries
- **Clean Architecture + Ports & Adapters**
- **Legacy modernization** without pretending old systems can be replaced overnight
- **Transactional workflows**, idempotency, concurrency control, audit and outbox patterns
- **Contract-first APIs**, integration testing and CI evidence
- **Frontend integration** with React and business-facing interfaces
- **Brownfield delivery** where modernization must coexist safely with existing software

---

## Selected work

### 🛡️ Insurance Claims Legacy Modernization
**TypeScript · NestJS · React · PostgreSQL · Clean Architecture**

A complete modernization MVP built as a governed case study around insurance-claims workflows.

Highlights:
- three accepted web slices: digital intake, customer tracking and claims backoffice
- REST API plus separate read-only MCP surface
- PostgreSQL-backed authoritative workflow
- idempotency, RBAC, audit, concurrency and RFC 9457 error handling
- browser, responsive, accessibility, backup/restore and observability evidence
- full governed lifecycle through Release Gate and Operations

➡️ [Explore InsuranceClaims](https://github.com/LuisHdezE/InsuranceClaims)

---

### 🧾 eFactura
**C# · .NET 10 · PostgreSQL · MySQL · Clean Architecture**

A brownfield modernization of an electronic-invoicing and transactional-sales platform for Uruguay.

Highlights:
- modernization from a legacy codebase toward explicit Domain, Application, Infrastructure and Web API boundaries
- dual-provider PostgreSQL/MySQL persistence verification
- Sales, Inventory, CAE, Finance and fiscal-calculation foundations
- CFE 25.2 arithmetic boundary
- idempotency, audit, outbox, optimistic concurrency and transactional rollback guarantees
- accepted validation baseline with 264 represented automated tests passing
- public API work is kept separate from unfinished XML signing and DGI/provider transport

➡️ [Explore eFactura](https://github.com/LuisHdezE/efactura)

---

### 🛒 ZoFloridane
**PHP · WordPress · WooCommerce · JavaScript · UI/UX modernization**

A real-world storefront modernization focused on improving a WordPress/WooCommerce purchasing experience while preserving existing business behavior.

Highlights:
- mobile-first UI/UX redesign
- custom storefront work around an existing WordPress architecture
- cart, locality, delivery and Zelle-oriented purchase flows
- safe repository boundaries that exclude production credentials and customer/order data
- Git-based workflow with local validation before deployment

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

## Current direction

I am packaging my strongest software projects as reproducible engineering case studies: clear problem framing, architecture decisions, implementation evidence, CI results, screenshots, limitations and next steps.

The goal is simple: when someone opens a repository, they should be able to understand **what problem was solved, how the system is structured, what has been proven, and what has deliberately not been claimed**.

---

## Contact

GitHub: [@LuisHdezE](https://github.com/LuisHdezE)

Portfolio website: **EliasWorks refresh in progress**

---

<sub>Most portfolio repositories are active engineering projects. README claims are intentionally bounded to capabilities already implemented and evidenced in each repository.</sub>
