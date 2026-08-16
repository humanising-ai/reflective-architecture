# Changelog

All notable changes to The Reflective Architecture are documented here.
This project follows a simple versioning scheme tied to the core Architecture document.

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
