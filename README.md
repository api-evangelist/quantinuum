# Quantinuum (quantinuum)

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

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/quantinuum/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producing
- **Access:** 3rd-Party

## Tags

- Quantum Computing
- Trapped Ion
- Quantum Hardware
- Quantum Software
- Quantum Compiler
- Quantum Chemistry
- Quantum Natural Language Processing
- Quantum Random Number Generator
- QIR
- OpenQASM
- Cloud Platform

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Quantinuum Nexus

Nexus is Quantinuum's all-in-one quantum computing cloud platform — job submission, compilation, projects, teams, roles, quotas, credentials, and linked accounts — fronted by the `qnexus` Python client and a REST/OpenAPI surface.

**Human URL:** [https://docs.quantinuum.com/nexus/](https://docs.quantinuum.com/nexus/)

### Quantinuum Systems (H-Series)

The H-Series trapped-ion (QCCD) quantum computers — System Model H1, System Model H2, and the next-generation Helios — exposed via QIR and OpenQASM 2.0 program submission through Nexus.

**Human URL:** [https://docs.quantinuum.com/systems/](https://docs.quantinuum.com/systems/)

### TKET

Quantinuum's optimizing quantum compiler — `pytket` Python interface, `tket` C++ core, and the next-gen `tket2` Rust compiler built on HUGR — with backend extensions for Quantinuum, IBM Q, Amazon Braket, IQM, AQT, PennyLane, and others.

**Human URL:** [https://docs.quantinuum.com/tket/](https://docs.quantinuum.com/tket/)

### InQuanto

Enterprise quantum chemistry platform for molecular and materials simulations (VQE, QPE, advanced ansätze, error mitigation), integrated with PySCF and Quantinuum Systems.

**Human URL:** [https://docs.quantinuum.com/inquanto/](https://docs.quantinuum.com/inquanto/)

### lambeq

Open-source Python toolkit for Quantum Natural Language Processing (DisCoCat / DisCoCirc) under Apache 2.0.

**Human URL:** [https://docs.quantinuum.com/lambeq/](https://docs.quantinuum.com/lambeq/)

### Guppy

Pythonic quantum-classical programming language that compiles through the HUGR hierarchical intermediate representation to Quantinuum hardware and QIR-compatible backends.

**Human URL:** [https://docs.quantinuum.com/guppy/](https://docs.quantinuum.com/guppy/)

### Selene

Plugin-extensible emulator for hybrid quantum computation including mid-circuit measurement, conditional control flow, and QIR-defined programs.

**Human URL:** [https://docs.quantinuum.com/selene/](https://docs.quantinuum.com/selene/)

### Quantum Origin

Verifiable quantum random number generation cloud API and on-prem appliance for PKI, key generation, and security workloads.

**Human URL:** [https://docs.quantinuum.com/origin/](https://docs.quantinuum.com/origin/)

### Qermit

Python module for running error-mitigation protocols (PEC, ZNE, CDR, dynamical decoupling) on top of pytket.

**Human URL:** [https://github.com/Quantinuum/Qermit](https://github.com/Quantinuum/Qermit)

## Common Properties

- [Portal](https://www.quantinuum.com/)
- [Documentation](https://docs.quantinuum.com/)
- [GitHub Organization](https://github.com/Quantinuum)
- [Nexus Portal](https://nexus.quantinuum.com/)
- [Getting Started](https://docs.quantinuum.com/nexus/trainings/getting_started.html)
- [Blog](https://www.quantinuum.com/news)
- [Publications](https://github.com/Quantinuum/quantinuum-publications)
- [Microsoft Azure Quantum integration](https://learn.microsoft.com/azure/quantum/provider-quantinuum)

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
