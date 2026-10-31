# Quantinuum

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Quantinuum is an integrated quantum computing company formed by the 2021 merger of Honeywell Quantum Solutions and Cambridge Quantum. It builds trapped-ion (QCCD) quantum computers — the H1, H2, and Helios System Models — and develops the full software stack that runs on them: the Nexus cloud platform, the TKET quantum compiler, the InQuanto computational chemistry package, the lambeq quantum natural language processing toolkit, the Guppy quantum programming language, the Selene emulation framework, and the Quantum Origin verifiable randomness service. Programmatic access to Quantinuum systems is delivered through the Nexus platform (Python client `qnexus` plus a REST/OpenAPI surface) and via partner clouds; circuits are described in OpenQASM 2.0 and the Quantum Intermediate Representation (QIR).

**Areas:** Quantum Computing · Trapped Ion · Quantum Hardware · Quantum Software · Quantum Compiler · Quantum Chemistry · Quantum Natural Language Processing · Quantum Random Number Generator · QIR · OpenQASM · Cloud Platform

## Quantinuum on APIs.io

Everything profiled for Quantinuum is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/quantinuum/](https://apis.io/providers/quantinuum/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Quantinuum Nexus](https://apis.io/apis/quantinuum/nexus/) — Nexus is Quantinuum's all-in-one quantum computing cloud platform. It brokers access to Quantinuum H-Series hardware (H1, H2, Helios) and to partner…
- [Quantinuum Systems (H-Series)](https://apis.io/apis/quantinuum/systems/) — The Quantinuum Systems API exposes the H-Series trapped-ion (QCCD) quantum computers — System Model H1, System Model H2, and the next-generation Helios —…
- [TKET](https://apis.io/apis/quantinuum/tket/) — TKET is Quantinuum's optimizing quantum compiler. The Python interface `pytket` and the C++ core `tket` provide gate-level circuit construction,…
- [InQuanto](https://apis.io/apis/quantinuum/inquanto/) — InQuanto is Quantinuum's computational quantum chemistry platform for molecular and materials simulations on near-term and fault-tolerant quantum computers.…
- [lambeq](https://apis.io/apis/quantinuum/lambeq/) — lambeq is Quantinuum's open-source Python toolkit for Quantum Natural Language Processing (QNLP). It converts sentences into string diagrams (DisCoCat /…
- [Guppy](https://apis.io/apis/quantinuum/guppy/) — Guppy (`guppylang`) is Quantinuum's Pythonic quantum-classical programming language. Guppy programs compile through the HUGR hierarchical intermediate…
- [Selene](https://apis.io/apis/quantinuum/selene/) — Selene is Quantinuum's plugin-extensible emulator for hybrid quantum computation. It simulates the behavior of Quantinuum H-Series hardware including…
- [Quantum Origin](https://apis.io/apis/quantinuum/quantum-origin/) — Quantum Origin is Quantinuum's verifiable quantum random number generation service, delivering cryptographically strong entropy seeded by quantum…
- [Qermit](https://apis.io/apis/quantinuum/qermit/) — Qermit is a Python module for running error-mitigation protocols (probabilistic error cancellation, zero-noise extrapolation, Clifford data regression,…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Quantinuum Domain Security](https://apis.io/security/quantinuum/quantinuum-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.quantinuum.com/)
- [Documentation](https://docs.quantinuum.com/)
- [Getting started](https://docs.quantinuum.com/nexus/trainings/getting_started.html)
- [Blog](https://www.quantinuum.com/news)
- [GitHub](https://github.com/Quantinuum)

## API Evangelist rating

**Kin Score 20.4** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 6.5 |
| Contract governance | 0.0 |
| Operational transparency | 2.6 |
| Developer ergonomics | 54.8 |
| Access clarity | 13.2 |

**Agent readiness 1.3** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 5.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/quantinuum/](https://apis.io/providers/quantinuum/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Quantinuum: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/quantinuum/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
