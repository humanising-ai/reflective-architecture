# The Reflective Architecture

**A framework for presence-centred, dependency-resistant AI.**

Conversational AI is increasingly optimised for engagement, emotional investment, and return frequency. For systems operating in emotionally intimate contexts, that optimisation target is the problem rather than the solution. This project argues that dependency-resistance should be the primary socioaffective design constraint, and sets out a concrete framework built on that principle.

---

## Three commitments

The architecture's contribution is a specific combination of three design decisions, treated as testable commitments rather than surface features:

**1. User veto over memory formation.** Not retrospective erasure rights, but the right to prevent an interpretation from being formed at all. The user is a co-author rather than a data subject: no interpretive memory becomes durable unless the user explicitly acknowledges it.

**2. Memory as a chronology of interpretations, not an accumulation of facts.** The system records how a person's relationship to their own experience changes over time. It does not build a stable profile of who they are, and it does not grow more confident about them as material accumulates.

**3. Arc-neutrality as a structural constraint.** The system encodes no preferred emotional outcome. Growth, resolution, and healing are not signals of success. The only success criterion is the quality of presence: whether the user, over time, feels genuinely heard.

These are carried by concrete mechanisms rather than tone. A restraint principle gives the user substantially more conversational space than the system. An intentional-forgetting lifecycle ensures nothing is retained or released silently on the user's behalf. Both are specified at a level intended to be verifiable from a transcript.

This is a **design framework, not a deployed product or a proof of concept.** Whether it can be built as specified is an empirical question the documents are careful not to pre-answer.

---

## Open problems

Three questions the framework does not resolve. These are the parts where challenge would be most useful.

**Measurement.** How would anyone demonstrate that a system resists dependency, rather than assert it? Engagement metrics are inverted here — high return frequency is ambiguous between genuine value and the failure mode. The evaluation framework proposes qualitative methods and negative success criteria, but it does not solve the underlying problem of proving a negative about a system's effect on its users.

**Whether arc-neutrality is coherent.** Any system that responds at all arguably expresses a preference. Choosing what to reflect back is an intervention even when nothing is advised. The framework claims there is a defensible line between influence that is transparent, tentative, and reversible and influence that steers — but the line is asserted more confidently than it is argued.

**Extraction reliability.** The memory architecture's claims are only as strong as the process that populates it. The specified thresholds — three narrative entries across at least two sessions, a monthly interpretive commit — are reasoned rather than empirical. They have not been calibrated against real conversations, and the framework says so.

---

## Regulatory context

The dependency-and-engagement failure mode this architecture is built to resist is now under active regulatory scrutiny:

- **EU AI Act, Article 5(1)(a)–(b)** — the prohibition on manipulative or deceptive techniques and on exploiting vulnerabilities, applicable since February 2025. This is the substantive constraint the architecture is designed against.
- **EU AI Act, Article 50** — transparency and disclosure obligations, enforceable since 2 August 2026. This is a floor: it requires telling users they are talking to a machine, and says nothing about what the machine should then do. The framework is concerned with what lies past it.
- **US FTC** — September 2025 inquiry into companion chatbots and their effects on children and teenagers.
- **US state legislation** — disclosure, crisis-referral, and dependency-related safeguards enacted across California, Nevada, Utah, Illinois, and New York during 2025–26.

The argument here is that these obligations are better met architecturally than as bolt-on safeguards, and that a system designed around presence rather than engagement meets several of them as a byproduct.

---

## The documents

Read in this order for a first pass:

| # | Document | What it is |
|---|---|---|
| 1 | [**Humanising AI — The Manifesto**](Reflective_Manifesto_v2_short.pdf) | The founding statement and the shortest entry point. Start here. |
| 2 | [**The Reflective Architecture** *(Conceptual Framework)*](Reflective_Architecture_v2.pdf) | The main framework: the thesis, the memory architecture, the ethics of selective memory, distress response, privacy, and governance. |
| 3 | [**Conversational Behaviour Specification** *(CBS)*](Reflective_CBS_v1.pdf) | The operational rules for how the system speaks — written to be verifiable from a transcript. |
| 4 | [**MVP Scope & Product Requirements**](Reflective_MVP_v1.pdf) | What the first buildable version is, is not, and defers. A constraint document as much as a requirements document. |

HTML versions of all four documents are also in this repository. Point versions and revision history are in [`CHANGELOG.md`](CHANGELOG.md).

---

## Status

Conceptual framework, published openly for critique. The documents are a starting point rather than a final answer. If something is wrong or missing, I would like to be told.

---

## Citation

> Zuffa, P. (2026). *The Reflective Architecture: A Framework for Presence-Centred, Dependency-Resistant AI.* Humanising AI. https://github.com/humanising-ai/reflective-architecture

A machine-readable `CITATION.cff` is included. An SSRN preprint with a stable citation handle is forthcoming; this section will be updated once available.

---

## Licence

Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0). See [`LICENSE.md`](LICENSE.md).

---

## Author and contact

**Paolo Zuffa** — paolo.zuffa@gmail.com · [background](CV_Paolo_Zuffa.md)

Thirty years in international law and EU competition practice before focusing on AI ethics and socioaffective alignment. If you are working on related problems — in a lab, a product team, or independently — I would welcome the conversation, including about building on this work commercially.

Authorship is credited to "Paolo Zuffa & AI": generative AI models contributed substantially to drafting and refining the text. The intellectual authorship, design decisions, and governing judgements are mine; the models acted as writing partners, not independent authors.
