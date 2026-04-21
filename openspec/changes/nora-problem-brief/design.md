## Context

NORA is a healthcare technology startup focusing on clinical communication efficiency. The current state is "pre-deployment," requiring a professional web presence to establish credibility with stakeholders (investors, judges, hospital pilots). The goal is a high-signal, low-noise "one-pager" that emphasizes the problem's evidence base and the team's international validation.

## Goals / Non-Goals

**Goals:**
- Establish NORA as an evidence-based clinical solution.
- Highlight the Harvard Global Hackathon win.
- Introduce the founding team and their credentials.
- Capture pilot interest via a simple contact mechanism.
- Project "deliberate restraint" through a clean, sparse aesthetic.

**Non-Goals:**
- Detailed technical explanation of how NORA works (outcome-level only).
- Multi-page navigation or complex user accounts.
- Proprietary data disclosure.

## Decisions

### 1. Single-Page Architecture
**Decision**: Use a single-scroll landing page layout.
**Rationale**: Keeps the narrative focused and ensures visitors see all critical credibility signals (Harvard win, Team, Problem) without needing to click around.
**Alternatives**: A multi-page site was considered but rejected to maintain the "sparse/credible" aesthetic requested.

### 2. Styling Strategy
**Decision**: Use Vanilla CSS with a focus on typography and whitespace.
**Rationale**: Reflects "deliberate restraint." High-quality typography (e.g., system fonts or a single high-quality serif/sans-serif pair) and generous padding signal professional maturity.
**Alternatives**: TailwindCSS was considered but rejected to avoid the "generic startup" look and keep the implementation lightweight.

### 3. Contact Mechanism
**Decision**: A simple "mailto" link or a basic HTML form capturing Name, Facility, and Email.
**Rationale**: Minimizes friction for pilots while avoiding the need for a complex backend or database at this stage.
**Alternatives**: Integrating a CRM like HubSpot was considered but is overkill for a "coming soon" page.

## Risks / Trade-offs

- **[Risk]** Sparse design may be interpreted as "under construction" rather than "deliberate restraint." → **Mitigation**: Use high-quality visual elements (Harvard logo, professional team photos) and polished typography to signal intentionality.
- **[Risk]** Absence of technical details might frustrate some visitors. → **Mitigation**: Frame the lack of details as "safety" and "proprietary protection" while emphasizing the outcome: "Nurse arrives prepared."
