# Executive Strategy Presentation

GitHub-native version of the final Equifax cybersecurity strategy presentation.

## Slide 1 — Equifax

Cybersecurity strategy and resilience assessment developed as a team project for MIT 5970: Cyber Strategy & Compliance.

## Slide 2 — Agenda

1. Organization & Cybersecurity Vision
2. Critical Business Functions / What Matters Most
3. Cyber Risk Landscape
4. Strategic Priority #1
5. Strategic Priority #2
6. Strategic Priority #3
7. Strategic Priority #4
8. How the Strategy Fits Together
9. Strategic Roadmap
10. Executive Recommendation

## Slide 3 — Organization & Cybersecurity Vision

**Who is Equifax?**  
Equifax supports global economic decision-making through credit reporting, data analytics, and verification services.

**What should be protected?**

- Integrity of consumer information
- Availability of essential decision services
- Data and analytics pipelines
- Privileged identities and access pathways

**Major risk areas**

- Third-party partner compromise
- Decision-service disruption
- AI-agent / machine-identity misuse
- Sensitive data compromise or manipulation

**Strategic direction**  
A phased 36-month roadmap prioritizing Zero Trust, predictive risk practices, operational resilience, and stronger third-party oversight.

## Slide 4 — Critical Business Functions

### Business Functions

- Credit reporting and dispute resolution
- Identity, employment, and income verification
- 24/7 decision APIs supporting automated decisions
- Enterprise data services and pipelines

### Critical Assets and Capabilities

- Credit and personally identifiable information
- Data Fabric and analytics integrity
- Decision-service availability
- Privileged access, IAM roles, root keys, and admin consoles

### Potential Implicit-Trust Exposures

- Persistent service-account permissions
- Excessive administrative privileges
- Third-party access
- Machine identities with limited oversight

These were assessment hypotheses and design risks, not verified findings from an internal Equifax audit.

## Slide 5 — Cyber Risk Landscape

The team used an outside-in + Equifax-specific forecasting approach. External evidence was adjusted for Equifax's exposure, architecture, controls, resilience, and dependencies.

## Slide 6 — Four Main Risks: 12-Month Team Forecasts

| Risk | Planning Range |
| --- | ---: |
| Sensitive Data Compromise | 5–15% |
| Critical Service Disruption | 8–20% |
| Third-Party Partner Compromise | 12–30% |
| AI / Machine-Identity Misuse | 10–25% |

Forecasting logic: **outside-in evidence → Equifax factors → planning range**.

## Slide 7 — Reasoning Behind the Forecast Ranges

### Data Compromise — 5–15%

- Vulnerability exploitation remains a common breach path.
- Equifax holds large volumes of sensitive data.
- Security maturity, detection, and cloud controls lower the likelihood of a major incident.

### Service Disruption — 8–20%

- Ransomware and disruptive attacks remain common.
- Always-on services depend on cloud infrastructure, data feeds, and vendors.
- Cloud resilience and recovery exercises reduce exposure.

### Third-Party Compromise — 12–30%

- Trusted vendors are frequently used as entry points.
- Equifax has a large external dependency surface.
- The range is widest because Equifax can assess partners but cannot fully control them.

### AI / Machine-Identity Misuse — 10–25%

- AI and non-human identities can act quickly and at scale.
- Use of AI and automation is expanding.
- Governance, automated checks, and human oversight reduce risk, but uncertainty remains higher because the area is newer.

## Slide 8 — Strategic Priority 1: Zero Trust & Identity

**Risk addressed:** Sensitive data compromise / manipulation

- Audit privileged access and over-permissioned service accounts
- Deploy Privileged Access Management (PAM)
- Replace standing administrative access with time-limited approvals
- Apply continuous access validation and microsegmentation

**Goal:** 90% of critical privileged access is time-limited and approved.

## Slide 9 — Strategic Priority 2: Operational Resilience

**Risk addressed:** Critical service disruption

- Deploy immutable, air-gapped backups
- Test failover capabilities
- Map critical dependencies and eliminate single points of failure
- Conduct recovery exercises with business owners

**Goal:** 90% of recovery exercises meet approved targets.

## Slide 10 — Strategic Priority 3: Third-Party Risk

**Risk addressed:** Trusted partner compromise

- Rank partners by data access, dependency, and business impact
- Apply least-privilege and time-limited access
- Strengthen contractual security controls
- Establish joint incident-response plans for tier-1 partners

**Goal:** 100% of critical partners are assessed, scoped, and assigned clear ownership.

## Slide 11 — Strategic Priority 4: AI & Machine Identities

**Risk addressed:** AI-agent / machine-identity misuse

- Maintain a central inventory of high-risk AI workflows and machine identities
- Assign a business owner to each
- Apply least privilege to machine credentials
- Require human sign-off for high-impact outputs
- Continuously monitor for behavioral drift

**Goal:** 100% of high-risk workflows have owners, verified permissions, and monitoring.

## Slide 12 — How the Strategy Fits Together

The strategy is designed to protect three outcomes:

- Consumer trust
- Data integrity
- Service availability

Four major strategic pillars support those outcomes:

- Zero Trust & Identity
- Operational Resilience
- Third-Party Risk
- AI & Machine Identity

They are enabled by predictive risk practices, automation, governance, and compliance. The overall model is intended to be risk-based, predictive, and business-owned.

## Slide 13 — Strategic Roadmap

### 0–6 Months

- Baseline critical access and AI identities
- Map service and partner dependencies
- Set risk appetite and reporting expectations

### 6–18 Months

- Expand least privilege and vendor oversight
- Run coordinated recovery exercises
- Automate risk triage and prioritization

### 18–36 Months

- Validate cross-service recovery
- Refine risk forecasts and AI oversight
- Independently assess results and refresh priorities

**Sequencing principle:** Address high-impact access and dependencies first, then scale after baselines and accountable owners are established.

## Slide 14 — Executive Recommendation

### Endorse Priorities
Approve the four strategic outcomes and the phased 36-month sequence.

### Assign Accountability
Name executive sponsors and business owners for critical services, identities, and partners.

### Fund the First Phase
Authorize access baselining, dependency mapping, critical-access governance, and recovery planning.

### Require Evidence
Review risk forecasts, exceptions, recovery results, and measurable outcomes each quarter.

---

## Team Project Note

This was a team project. Afnan Rafid's primary presentation responsibility was the **Cyber Risk Landscape**, including the four 12-month forecast ranges and the reasoning behind them.
