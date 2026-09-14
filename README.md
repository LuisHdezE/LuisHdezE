# Hi, I'm Luis Hernández 👋

### Software Engineer · Backend Architecture · Legacy Modernization

I design and modernize business software with a focus on **Clean Architecture, transactional integrity, API contracts, automated verification, and maintainable delivery workflows**.

My strongest work sits at the intersection of backend engineering and system modernization: taking complex business flows, defining explicit boundaries, moving authority to the right layer, integrating real persistence, and proving behavior through tests, CI, and governed releases.

**Based in Uruguay · Open to backend / software engineering opportunities**

---

## Flagship case study

### 🛡️ Insurance Claims Legacy Modernization — v0.3.0
**TypeScript · NestJS 12 · React 19 · PostgreSQL 18 · Clean Architecture + Ports & Adapters**

A full insurance-claims modernization case study built as a governed greenfield product with simulated legacy coexistence.

The project demonstrates not only application code, but the complete engineering path from requirements and architecture through API evolution, browser integration, provider-real QA, release governance, and technical case-study packaging.

**R3 at a glance**

- **90 REST operations** across **76 paths** and **16 operation families**;
- **22 productized web surfaces** across public, operator, customer, policy, financial, administration, analytics, import and recovery journeys;
- deterministic runtime reconciliation at **90/90**;
- OpenAPI zero drift and Postman semantic coverage at **90/90**;
- PostgreSQL 18 provider-real API and integration QA;
- JWT authentication, API-side RBAC, Argon2id, idempotency, concurrency protection, RFC 9457 Problem Details, durable audit correlation and rate limiting;
- browser responsive/accessibility journeys plus offline/degraded behavior;
- governed release publication with an annotated **v0.3.0** tag and preserved historical evidence.

The repository is intentionally explicit about what is implemented, what is simulated, what is excluded, and what evidence supports each claim.

➡️ [Explore InsuranceClaims](https://github.com/LuisHdezE/InsuranceClaims)  
🏷️ [Published v0.3.0 release](https://github.com/LuisHdezE/InsuranceClaims/releases/tag/v0.3.0)  
📘 [Read the R3 case study](https://github.com/LuisHdezE/InsuranceClaims/blob/main/documentation/portfolio/CASE_STUDY.md)

---

## Engineering focus

- **Backend & API engineering** with explicit Domain, Application, Infrastructure and Presentation boundaries
- **Clean Architecture + Ports & Adapters**
- **Legacy modernization** through controlled coexistence and replaceable adapters
- **Transactional workflows**, rollback guarantees, idempotency, concurrency control, audit and outbox patterns
- **Contract-first APIs** with OpenAPI, runtime reconciliation and integration testing
- **Relational persistence** with PostgreSQL and MySQL
- **Frontend integration** with React and API-authoritative business behavior
- **Evidence-driven delivery** where architecture, QA, limitations and release state are visible in the repository

---

## Selected work

### 🧾 eFactura
**C# · .NET 10 · ASP.NET Core · PostgreSQL · MySQL · Clean Architecture**

A governed brownfield modernization of an electronic-invoicing and transactional-sales platform for Uruguay.

Current engineering evidence includes:

- incremental migration toward explicit Domain, Application, Infrastructure and Web API boundaries;
- provider-neutral EF Core write paths validated against PostgreSQL 16 and MySQL 8.4;
- Sales, Catalog, Inventory, CAE/fiscal numbering and Finance foundations;
- idempotency, audit, outbox, optimistic/unique concurrency and transactional rollback guarantees;
- **264 / 264 represented automated tests PASS** at the accepted transaction-foundation checkpoint;
- explicit separation between implemented local fiscal foundations and later external signing/provider transport.

➡️ [Explore eFactura](https://github.com/LuisHdezE/efactura)

---

### 🛒 ZoFloridane
**PHP · WordPress · WooCommerce · JavaScript · UI/UX modernization**

A real-world storefront modernization focused on improving an existing WordPress/WooCommerce purchasing experience without casually replacing working business behavior.

The repository documents:

- mobile-first UI/UX modernization;
- existing custom-plugin and child-theme boundaries;
- cart, locality, delivery and Zelle-oriented purchase flows;
- repository isolation from production credentials, customer data, order exports and database dumps;
- Git-based delivery with local functional validation before deployment.

➡️ [Explore ZoFloridane](https://github.com/LuisHdezE/ZoFloridane)

---

### 📱 KMP Zero-Cost Lab
**Kotlin Multiplatform · Compose Multiplatform · Android · iOS · GitHub Actions**

A reference pilot exploring a **USD 0 development workflow** for Android and iOS from Windows/WSL without a locally owned Mac.

The pilot is intentionally phased. Its current build-baseline work isolates Android/iOS toolchain validation before Room/SQLite persistence is introduced.

➡️ [Explore KMP Zero-Cost Lab](https://github.com/LuisHdezE/KMP-Zero-Cost-Lab)

---

## How I work

```text
Understand the domain before coding.
Keep business authority out of controllers and clients.
Put external systems behind replaceable ports.
Make critical writes transactional.
Make retries safe.
Treat architecture boundaries as executable constraints where practical.
Test negative paths, not only happy paths.
Keep CI evidence tied to the exact reviewed commit.
State limitations as clearly as capabilities.
```

---

## Core technologies

**Backend**  
`C#` · `.NET` · `ASP.NET Core` · `TypeScript` · `Node.js` · `NestJS` · `PHP`

**Frontend / client**  
`React` · `TypeScript` · `JavaScript` · `Kotlin` · `Compose Multiplatform` · `WordPress` · `WooCommerce`

**Data**  
`PostgreSQL` · `MySQL` · `SQLite` · `Entity Framework Core` · `Prisma`

**Architecture & delivery**  
`Clean Architecture` · `Ports & Adapters` · `REST` · `OpenAPI` · `CI/CD` · `GitHub Actions` · `Automated Testing` · `Release Governance`

---

## What I want a repository to prove

A strong engineering repository should make four things obvious without requiring a private explanation:

1. **What problem is being solved?**
2. **Where does business authority live?**
3. **What has actually been verified?**
4. **What has deliberately not been claimed?**

That is how I am packaging my current work: as reproducible engineering case studies rather than isolated code samples.

---

## Contact

GitHub: [@LuisHdezE](https://github.com/LuisHdezE)  
Portfolio: **eliaswork.uy — refresh in progress**

<sub>Portfolio claims are intentionally bounded to capabilities already implemented and evidenced in the referenced repositories.</sub>
