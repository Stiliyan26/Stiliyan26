<h1 align="center">Stiliyan Nikolov</h1>
<p align="center">
  <b>Software Engineer</b> &nbsp;·&nbsp; TypeScript &amp; Java &nbsp;·&nbsp; Sofia, Bulgaria 🇧🇬
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/stiliyan-nikolov-36a0a8270" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:stiliyan.nikolov02@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

I build full-stack systems in **TypeScript** and **Java**, and I've been doing it professionally since 2023 — Latona, HedgeServ, and client work in between.

Most of what I care about sits in the seams: how services talk without losing messages, what happens on the retry, and how you diagnose a Node process that got OOM-killed with no stack trace. When a project needs an Angular or React frontend, I write those too.

<br>

<h3 align="center">Core</h3>
<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" width="42" height="42" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" title="TypeScript" width="42" height="42" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" title="React" width="42" height="42" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nestjs/nestjs-original.svg" alt="NestJS" title="NestJS" width="42" height="42" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" width="42" height="42" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" title="Docker" width="42" height="42" />
</p>

<h3 align="center">Also work with</h3>
<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/apachekafka/apachekafka-original.svg" alt="Kafka" title="Kafka" width="38" height="38" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" alt="Redis" title="Redis" width="38" height="38" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/angular/angular-original.svg" alt="Angular" title="Angular" width="38" height="38" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-original.svg" alt="Kubernetes" title="Kubernetes" width="38" height="38" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" title="AWS" width="38" height="38" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/azure/azure-original.svg" alt="Azure" title="Azure" width="38" height="38" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" title="Java" width="38" height="38" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" alt="Spring" title="Spring" width="38" height="38" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#" title="C#" width="38" height="38" />&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dotnetcore/dotnetcore-original.svg" alt="ASP.NET Core" title="ASP.NET Core" width="38" height="38" />
</p>

<br>

## Where I've gone deep

**Resilience in production.** At Latona I owned the failure path for an invoice pipeline handling **10K+ documents a day at 99.8% reliability** — exponential backoff, a cron retry queue, circuit breaker, dead letter queue — then replaced 700+ one-off validation rules with an annotation-based engine. I later extracted Circuit Breaker and Retry into [Resilience-Kit](https://github.com/Stiliyan26/Resilience-Kit), a small C# library I wrote to understand the internals rather than just call a package.

**Distributed real-time systems.** My TU-Sofia thesis is a [7-microservice chat platform](https://github.com/Stiliyan26/Distributed-Chat-System) — NestJS, Kafka with per-channel partition ordering, Redis Pub/Sub fan-out, WebSockets, and atomic Lua scripts for multi-device presence. The interesting problems were the ones tutorials skip: user-disconnect races, idempotent writes, and an API gateway with circuit breaker and bulkhead isolation.

**Production debugging.** At HedgeServ I shipped heap snapshots for OOM-killed Node pods — PVC + S3 across 5 Kubernetes environments — so post-crash memory diagnosis took minutes instead of guesswork, and an atomic Mongo cascade delete across 10K+ dashboards so navigation, groups, and viz overrides couldn't drift out of sync.

<br>

## Currently

On a client contract building **HRise**, a custom HR platform (NestJS, PostgreSQL, React). In parallel I'm going further into system design and AI engineering — the decisions that come before the code, and systems built on top of foundation-model APIs.

<br>

## Education

**BSc, Computer and Software Engineering** — Technical University of Sofia (graduated June 2026)

**Software Engineering** — SoftUni (2021–2023)

<br>

---

<p align="center">
  <sub>Happy to talk about distributed systems, resilience, and full-stack architecture.</sub><br>
  <sub><a href="mailto:stiliyan.nikolov02@gmail.com">stiliyan.nikolov02@gmail.com</a></sub>
</p>
