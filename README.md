# Technical Architecture Interview Prep
A personal study wiki covering the core topics, concepts, and reasoning patterns that come up in technical architecture interviews — from system design fundamentals to cloud infrastructure.

⭐ If this is useful, star the repo — it helps others find it.

---
## What this is
These are my own notes, written to build genuine understanding rather than memorize answers. Every page covers the mental model first, then the tradeoffs that interviewers actually probe, then Q&A based on questions I've practiced or encountered.
The wiki lives in the [Wiki tab](../../wiki) of this repo — that's where all the content is organized and navigable.

---
## Topics covered
| Topic | Key areas |
|---|---|
| [System Design](../../wiki/System-Design) | CAP theorem, scalability, load balancing, estimation, fault tolerance |
| [Design Patterns](../../wiki/Design-Patterns) | SOLID, DDD, CQRS, Saga, Event Sourcing, Hexagonal architecture |
| [Data Architecture](../../wiki/Data-Architecture) | SQL vs NoSQL, sharding, caching, replication, OLTP vs OLAP, CDC |
| [APIs & Integration](../../wiki/APIs-and-Integration) | REST, gRPC, GraphQL, event-driven architecture, idempotency, rate limiting |
| [Security Architecture](../../wiki/Security-Architecture) | Zero trust, OAuth/OIDC, secrets management, threat modeling |
| [Reliability & Ops](../../wiki/Reliability-and-Ops) | SLOs, observability, chaos engineering, incident response, DR |
| [Cloud & Infrastructure](../../wiki/Cloud-and-Infrastructure) | Kubernetes, serverless, IaC, GitOps, multi-region, cost optimization |

---
## How the wiki is structured
Each page follows the same format:
- **Mental model** — the core intuition for the topic, before any specifics
- **Key concepts** — the ideas and terminology worth knowing cold
- **Tradeoffs** — what interviewers actually probe and why the answers aren't simple
- **Q&A** — questions with detailed answers, tagged by difficulty

Difficulty tags used throughout:
- `[common]` — comes up frequently across companies and roles
- `[hard]` — expected at senior / principal level, requires depth
- `[know cold]` — foundational — fumbling these signals a real gap

---
## Interview approach
A few principles I keep coming back to:

**Define the problem before the solution.** Interviewers notice when you skip clarifying requirements and jump straight to architecture. The constraints shape every decision — scale, consistency needs, team size, latency targets.

**Tradeoffs over answers.** Every architecture decision trades something. The interview is a conversation about those tradeoffs, not a test of whether you picked the "right" answer.

**Operational thinking counts.** How does this get deployed? What does failure look like? How does the on-call engineer debug it at 2am? These questions separate architects who've run things in production from those who haven't.

---
## Who this is for
If you're preparing for staff engineer, principal engineer, or solution architect interviews — this is built for you. These started as personal notes but are structured to be genuinely useful as a reference for anyone preparing at that level. Bookmark it, fork it, make it your own.

---
## Contributing
Found an error or want to suggest a topic? Open an issue — this is a living resource and improvements are always welcome.

---
## License
This project is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Free to use, share, and adapt with attribution.

---
*[srivalligade04](https://github.com/srivalligade04)*
