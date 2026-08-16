# The Reflective Architecture

**A framework for presence-centred, dependency-resistant AI.**

Conversational AI is increasingly optimised for engagement, emotional investment, and return frequency. For systems operating in emotionally intimate contexts, that optimisation target is the problem rather than the solution. This project argues that dependency-resistance should be the primary socioaffective design constraint, and sets out a concrete framework built on that principle.

---

## Three commitments

The architecture's contribution is a specific combination of three design decisions, treated as testable commitments rather than surface features:

**1. User veto over memory formation.** Not retrospective erasure rights, but the right to prevent an interpretation from being formed at all. The user is a co-author rather than a data subject: no interpretive memory becomes durable unless the user explicitly acknowledges it.

**2. Memory as a chronology of interpretations, not an accumulation of facts.** The system records how a person's relationship to their own experience changes over time. It does not build a stable profile of who they are, and it does not grow more confident about them as material accumulates.

**3. Arc-neutrality: no accumulating preference.** The system encodes no target emotional state for the user. Growth, resolution, and healing are not signals of success; the only criterion is the quality of presence. This is deliberately the narrow claim. Every reflection selects, and every selection carries direction, so local neutrality is not available to any system that responds at all. What is claimed is that the local directions do not compound into a tilt, and that the residual preferences which cannot be removed are disclosed rather than denied.

These are carried by concrete mechanisms rather than tone. A restraint principle gives the user substantially more conversational space than the system. An intentional-forgetting lifecycle ensures nothing is retained or released silently on the user's behalf. Both are specified at a level intended to be verifiable from a transcript.

This is a **design framework, not a deployed product or a proof of concept.** Whether it can be built as specified is an empirical question the documents are careful not to pre-answer.

---

## Open problems

Three questions I have not resolved. These are where challenge would be most useful.

**Measurement.** I do not know how anyone would demonstrate that a system resists dependency rather than assert it. Return frequency is ambiguous between genuine value and the failure mode, so the primary behavioural signal points both ways at once. My current position is that the honest claim is narrower than it first appears: one can audit the *absence of mechanisms* — no engagement term in any objective, no unsolicited outreach, no memory surfaced to re-establish contact — but not demonstrate the *absence of effect* on a person's life. The second would require evidence I have no way to generate before launch.

**The limits of arc-neutrality.** The narrow claim above is defensible; whether it is sufficient is another matter. Under conversational feedback, small unbiased perturbations can still settle into a stable attractor, which would collapse the distinction between local and accumulating preference and take most of the argument with it. There is also one declared exception: at the highest distress tier the system prefers that the user stays alive, and acts on it. A constraint that admits one exception is a policy rather than an invariant, and the argument for a second exception will resemble the argument for the first.

**Extraction reliability.** The memory architecture's claims are only as strong as the process that populates it. The specified thresholds — three narrative entries across at least two sessions, a monthly interpretive commit — are reasoned rather than empirical. They have not been calibrated against real conversations.

---

## Regulatory context

The dependency-and-engagement failure mode this architecture is built to resist is now under active regulatory scrutiny:

- **EU AI Act, Article 5(1)(a)–(b)** — the prohibition on manipulative or deceptive techniques and on exploiting vulnerabilities, applicable since February 2025. This is the substantive constraint the architecture is designed against.
- **EU AI Act, Article 50** — transparency and disclosure obligations, enforceable from 2 August 2026. This is a floor: it requires telling users they are talking to a machine, and says nothing about what the machine should then do.
- **US FTC** — Section 6(b) inquiry opened September 2025 into seven companies, covering companion chatbots and their effects on minors.
- **US state legislation** — California SB 243 and New York's AI Companion Models law in force; Washington HB 2225 and Connecticut SB 5 enumerate specific prohibited techniques producing emotional dependence.

A companion analysis argues that Article 5 is decision-shaped while dependency is disposition-shaped, and that the provision therefore catches the egregious cases while missing the structural one. If that is right, these obligations are better met architecturally than through compliance mapping.

---

## The documents

Read in this order for a first pass:

| # | Document | What it is |
|---|---|---|
| 1 | [**Humanising AI — The Manifesto**](https://github.com/humanising-ai/reflective-architecture/blob/main/Reflective_Manifesto_v2_short.pdf) | The founding statement and the shortest entry point. Start here. |
| 2 | [**The Reflective Architecture** *(Conceptual Framework)*](https://github.com/humanising-ai/reflective-architecture/blob/main/Reflective_Architecture_v2.pdf) | The main framework: the thesis, the memory architecture, the ethics of selective memory, distress response, privacy, and governance. |
| 3 | [**Conversational Behaviour Specification** *(CBS)*](https://github.com/humanising-ai/reflective-architecture/blob/main/Reflective_CBS_v1.pdf) | The operational rules for how the system speaks — written to be verifiable from a transcript. |
| 4 | [**MVP Scope & Product Requirements**](https://github.com/humanising-ai/reflective-architecture/blob/main/Reflective_MVP_v1.pdf) | What the first buildable version is, is not, and defers. A constraint document as much as a requirements document. |

Three short papers develop the open problems above: on Article 5 and what it does not reach, on whether arc-neutrality is coherent, and on how dependency-resistance could be measured.

HTML versions of all documents are also in this repository. Point versions and revision history are in [`CHANGELOG.md`](https://github.com/humanising-ai/reflective-architecture/blob/main/CHANGELOG.md).

---

## Status

Conceptual framework, published openly for critique. The documents are a starting point rather than a final answer. If something is wrong or missing, I would like to be told.

---

## Citation

> Zuffa, P. (2026). *The Reflective Architecture: A Framework for Presence-Centred, Dependency-Resistant AI.* Humanising AI. https://github.com/humanising-ai/reflective-architecture

A machine-readable `CITATION.cff` is included. An SSRN preprint with a stable citation handle is forthcoming; this section will be updated once available.

---

## Licence

Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0). See [`LICENSE.md`](https://github.com/humanising-ai/reflective-architecture/blob/main/LICENSE.md).

---

## Author and contact

**Paolo Zuffa** — paolo.zuffa@gmail.com · [background](https://github.com/humanising-ai/reflective-architecture/blob/main/CV_Paolo_Zuffa.md)

Thirty years in international law and EU competition practice before focusing on regulatory analysis of conversational AI design. If you are working on related problems — in a lab, a product team, or independently — I would welcome the conversation, including about building on this work commercially.

Authorship is credited to "Paolo Zuffa & AI": generative AI models contributed substantially to drafting and refining the text. The intellectual authorship, design decisions, and governing judgements are mine; the models acted as writing partners, not independent authors.
