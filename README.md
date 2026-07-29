# The Reflective Architecture

**A framework for presence-centred, dependency-resistant AI.**

Conversational AI is increasingly optimised for engagement, emotional investment, and return frequency. This project argues that for systems operating in emotionally intimate contexts, **dependency-resistance — not engagement — should be the primary socioaffective design constraint**, and sets out the Reflective Architecture as a concrete framework built on that principle.

Presence-centred design holds that an AI's value should derive from the quality of a single interaction rather than from accumulated intimacy, retention, or data. The system listens more than it speaks, reflects rather than advises, and builds a memory that tracks the evolution of a person's own meaning over time — under the user's explicit control at every step.

This is a **design framework, not a deployed product or a proof of concept.** Whether it can be built as specified is an empirical question the documents are careful not to pre-answer.

---

## What's new here

The architecture's contribution is a specific combination of three design decisions, treated as testable commitments rather than surface features:

1. **User veto over memory formation.** Not retrospective erasure rights, but the right to prevent an interpretation from being formed in the first place. The user is a co-author who can decline to be interpreted at all — no interpretive memory becomes durable unless the user explicitly acknowledges it.

2. **Memory as a chronology of interpretations, not an accumulation of facts.** The system records *how* a person's relationship to their own experience changes over time, rather than a stable profile of who they are. Memory is a record of a life in motion, not a database of ground truths.

3. **Arc-neutrality as a structural constraint.** The system encodes no preferred emotional outcome. Growth, resolution, and healing are not signals of success. The only success criterion is the quality of presence: whether the user, over time, feels genuinely heard.

These are carried by concrete conversational and memory mechanisms — a restraint principle under which the user occupies most of the conversational space, and an intentional-forgetting lifecycle in which nothing is released or retained silently on the user's behalf.

---

## Why now

The framework is directly responsive to the socioaffective-alignment problem now under active regulatory scrutiny:

- **EU AI Act** — Article 50 transparency obligations, effective **2 August 2026**.
- **US FTC** — September 2025 inquiry into companion chatbots and their effects on children and teens.
- **US state legislation** — disclosure, crisis-referral, and dependency-related safeguards enacted across California, Nevada, Utah, Illinois, and New York in 2025–26.

The dependency-and-engagement failure mode this architecture is built to resist is precisely what regulators and researchers are now targeting. Presence-centred design addresses it structurally rather than as a bolt-on safeguard.

---

## The documents

Read in this order for a first pass:

| # | Document | What it is |
|---|---|---|
| 1 | [**Humanising AI — The Manifesto**](Reflective_Manifesto_v2_short.pdf) | The founding statement and the shortest entry point. Start here. |
| 2 | [**The Reflective Architecture** *(Conceptual Framework, v2)*](Reflective_Architecture_v2.pdf) | The main framework: the thesis, the memory architecture, the ethics of selective memory, distress response, privacy, governance, and where the work departs from prior systems. |
| 3 | [**The Reflective — Conversational Behaviour Specification** *(CBS, v1)*](Reflective_CBS_v1.pdf) | The operational, testable rules for how the system speaks — written to be verifiable from a transcript. |
| 4 | [**The Reflective — MVP Scope & Product Requirements** *(v1)*](Reflective_MVP_v1.pdf) | What the first buildable version is, is not, and defers — a constraint document as much as a requirements document. |

HTML versions of all documents are also available in this repository.

---

## Status

Conceptual framework, published openly for critique and collaboration. The documents are a starting point, not a final answer; they will be strengthened by challenge and correction. If something is wrong or missing, I'd genuinely like to be told.

---

## Citation

If you reference this work, please cite:

> Zuffa, P. (2026). *The Reflective Architecture: A Framework for Presence-Centred, Dependency-Resistant AI.* Humanising AI. https://github.com/humanising-ai/reflective-architecture

A machine-readable `CITATION.cff` is included in this repository. An SSRN preprint with a stable citation handle is forthcoming — this section will be updated once available.

---

## License and commercial use

This work is licensed under **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**. You are free to share and adapt the material for non-commercial purposes, with attribution. See [`LICENSE.md`](LICENSE.md) for the full terms.

**Commercial use — including implementing this framework in a commercial product, or developing a derived work commercially — requires a separate licence.** If you are an AI lab, product team, or organisation interested in building on this work, or in a dual-licensing or advisory arrangement, please get in touch directly. If you are working on related problems, I'd welcome the conversation.

---

## Author and contact

**Paolo Zuffa** — paolo.zuffa@gmail.com

Authorship is credited to "Paolo Zuffa & AI": generative AI models contributed substantially to drafting and refining the text. The intellectual authorship, design decisions, and governing judgements are Paolo Zuffa's; the models acted as writing partners, not independent authors.
