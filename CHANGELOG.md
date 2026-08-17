# Changelog

All notable changes to The Reflective Architecture are documented here.
This project follows a simple versioning scheme tied to the core Architecture document.

## [2.6] — 2026-08-17

### Changed
- **§9 preamble expanded** to introduce the regulatory dimension of the section ("Privacy is where this obligation begins but not where it ends"), signposting §9.1 (data-protection obligations) and §9.2 (manipulation prohibition) explicitly. Makes the retitled section heading ("Ethical Boundaries, Privacy, and Regulatory Constraint") earned by the opening paragraph.
- **Companion cross-links added to body sections:** §14.3 now points to *Is Arc-Neutrality Coherent?* and §12.4 now points to *How Would You Know?*, mirroring the cross-link pattern already established in §9.2 for *The Decision-Shaped Prohibition*.
- **Abstract updated** to name the regulatory analysis: "the regulatory constraints that bind a system of this kind, including the EU AI Act's prohibition on manipulation" inserted into the enumeration of design questions, so the abstract advertises the §9.2 material rather than hiding it.

### Editorial
- These are consistency tweaks following the v2.5 review — each closes a gap between what a section now contains and how it is titled, introduced, or cross-referenced. No substantive change to the framework.

## [2.5] — 2026-08-16

### Added
- **Manipulation prohibition — EU AI Act, Article 5** (new Architecture §9.2). A new subsection sets out how Article 5(1)(a)–(b) applies to conversational AI in the emotional register: intention is not required (a system is caught by the *effect* of distorting behaviour, and the Commission's Guidelines of 4 February 2025 note that manipulative techniques may emerge through reinforcement learning without any provider intending them), and "use" extends to reasonably foreseeable misuse. The emerging American standard of care (Connecticut SB 5, Washington HB 2225) is noted as a set of auditable, mechanism-based prohibitions that the design commitments in §2, §3, and §5 already exclude. Cross-referenced to the companion analysis *The Decision-Shaped Prohibition*.

### Changed
- **Section 9 retitled** "Ethical Boundaries, Privacy, and Regulatory Constraint" (was "Ethical Boundaries and Privacy") to reflect the addition of the Article 5 material.
- **Evaluation claims reframed** (§12.4, retitled "What the evaluation can and cannot claim", was "What the evaluation must not claim"). The section now states affirmatively what the mechanism-based evaluation *can* establish, alongside its limits, rather than only what it must not claim.
- **§5.5** — "should not privilege" → "should not systematically privilege", aligning the wording with the restated arc-neutrality claim.
- **§14.3** — closing sentence revised to "These claims are architectural rather than performative, and they are stated with their limits attached."

### Editorial
- Added companion-paper cross-references to the cover: *The Decision-Shaped Prohibition* (Article 5), *Is Arc-Neutrality Coherent?*, and *How Would You Know?* (measurement).
- British-English spelling pass across the Architecture document (externalised, presence-centred, honour, localised, behaviour) and reconciliation of "present-centred" → "presence-centred" in §12.5.

## [2.4] — 2026-08-16

### Changed
- **Arc-neutrality restated** (Architecture §14.3, §5.5, §7.3). The third novelty claim is reframed as the absence of *accumulating* preference over the user's trajectory, rather than the absence of preference as such. Local directional reflection is acknowledged as unavoidable; the claim is that local tilts do not compound. The restated claim is given identifiable, testable failure conditions.
- **Disclosed residual preferences** (§14.3). A new paragraph names the three preferences the system does encode — user occupies most conversational space, reflection over advice, and (at Tier 3 distress) that the user remains alive — and frames the last as the one declared exception to arc-neutrality.
- **Implementation consequence** (§5.5). Added an explicit instruction that arc-neutrality requires actively counteracting the underlying model's built-in tilt toward resolution, not merely refraining from adding a preference.
- **Cross-reference** (§7.3). The Tier 3 distress response is marked as the single declared exception to arc-neutrality, scoped to that tier only.

### Note
- The Manifesto retains its absolute phrasing by deliberate editorial choice (a manifesto is not a specification). The README retains its shorthand and relies on the linked Architecture document for precision.

## [2.1] — 2026-07-17

### Added
- Initial public release of The Reflective Architecture.
- Four documents published: Manifesto (v1), Architecture (v2), Conversational Behaviour Standard / CBS (v1), MVP Scope & Requirements (v1).
- Repository structure, README, license (CC BY-NC 4.0), and citation metadata.

---

*Format note: dates are ISO 8601 (YYYY-MM-DD). Substantive revisions to the Architecture document will be reflected in the version number and mirrored on arXiv.*
