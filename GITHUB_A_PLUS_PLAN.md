# GitHub A+ Plan

> This is an internal Cod3Black portfolio rubric, not an official GitHub grade.

## Objective

Make the **wizelements** GitHub profile credible within 30–60 seconds to a prospective client, technical reviewer, partner, or collaborator.

An A+ profile should make five things obvious:

1. **What we build**
2. **Which systems are real and current**
3. **How strong the engineering standard is**
4. **Where the proof lives**
5. **How to start a commercial conversation**

## Current assessment

### Strengths already verified

- The account has a real profile README and a curated portfolio repository.
- Historical coursework and many obsolete projects have already been archived.
- The public portfolio includes current business/client systems, not only demos.
- **Gratog** documents a live production commerce system with Square, Resend, Twilio, cron jobs, tests, and Vercel deployment.
- **ASCA PWA** documents security boundaries, quality gates, Playwright E2E, deployment discipline, and a current architecture.
- **Ownly**, **SD Studio Web**, and **Family Powerhouse** show CI/CodeQL and stronger open-source-style documentation.
- Private systems such as **OPEE**, **Cod3Black Signal**, and **MusiCards** support a broader capability story while allowing proprietary implementation to remain private.

### Main blockers to A+

1. **Repo discovery metadata is inconsistent.** Several public repositories have weak or missing descriptions, homepages, and domain-specific topics.
2. **Community health is inconsistent.** Important public repos do not consistently expose LICENSE, SECURITY, CONTRIBUTING, issue templates, or PR templates.
3. **Visual proof is uneven.** Many repos explain features but do not immediately show screenshots, architecture diagrams, or short demos.
4. **Maturity language is inconsistent.** Some older READMEs use phrases like “production-ready” or “live” while also listing major unfinished items.
5. **Portfolio focus needs stronger pins.** GitHub allows up to six pinned repositories/gists; the six should represent the strongest commercial and technical proof.
6. **Public proof is fragmented.** CI, security, deployment, live URLs, and business outcome evidence should be easier to scan.
7. **Some active public repos are retained assets, not current product centers.** Their status should be labeled consistently so visitors do not confuse experiments, templates, client systems, and production products.
8. **Commercial conversion is not yet instrumented on GitHub.** The profile has a CTA, but GitHub-origin lead capture and attribution are not yet visibly measured.

## A+ rubric

| Area | A+ condition | Weight |
| --- | --- | ---: |
| Positioning | Clear identity, offer, audience, and outcome in the first screen | 15 |
| Proof of work | 4–6 strong projects with demos, screenshots, architecture, and status | 20 |
| Repo quality | Accurate README, setup, tests, deployment, limitations, ownership | 15 |
| Security & quality | CI, security policy, dependency scanning/CodeQL where appropriate | 15 |
| Discoverability | Strong descriptions, homepages, topics, social previews, pins | 10 |
| Portfolio governance | Archived legacy work, canonical repos, maturity labels | 10 |
| Contribution health | LICENSE/CONTRIBUTING/templates where open contribution makes sense | 5 |
| Commercial conversion | Clear CTA, portfolio link, lead attribution, next step | 10 |
| **Total** |  | **100** |

**A+ target: 95+/100 on this rubric.**

## Priority execution plan

### P0 — Profile and pins

- [x] Replace the profile README with a proof-first, professional version.
- [x] Add this A+ scorecard to the profile repository.
- [ ] Pin exactly six high-signal public repositories.
- [ ] Recommended pin order:
  1. **Gratog**
  2. **asca-pwa**
  3. **c3bai**
  4. **cod3blackagency-portfolio**
  5. **Ownly**
  6. **sd-studio-web** or **jds-horse-ranch-pwa** depending on target audience
- [ ] Enable private contribution visibility if appropriate so current private development activity is represented without exposing private details.
- [ ] Confirm profile bio, website, and social links match the Cod3Black positioning.

### P1 — Featured repo standard

Apply the following to each pinned repo:

- [ ] One-sentence outcome-oriented description
- [ ] Correct homepage/demo URL
- [ ] 5–10 useful, specific topics
- [ ] Screenshot or product image above the fold
- [ ] Architecture diagram for non-trivial systems
- [ ] Status badge only when backed by a real workflow
- [ ] “Current status / known limitations” section
- [ ] Setup instructions tested from a clean checkout
- [ ] Test commands documented and passing
- [ ] Deployment path documented
- [ ] Security expectations documented
- [ ] License decision explicit
- [ ] No fake testimonials, invented metrics, or unverified performance claims

### P2 — Repository health

For public repositories intended for reuse or contribution:

- [ ] LICENSE
- [ ] SECURITY.md
- [ ] CONTRIBUTING.md
- [ ] CODE_OF_CONDUCT.md when community contribution is invited
- [ ] .github/ISSUE_TEMPLATE/
- [ ] .github/pull_request_template.md
- [ ] Dependabot configuration where appropriate
- [ ] CodeQL or equivalent security scanning where appropriate
- [ ] Branch protection / required checks on consequential production repos
- [ ] Delete merged branches and prefer a consistent merge strategy

For client or portfolio repos that are public but not open-source:

- [ ] State that status clearly.
- [ ] Do not add an open-source license unless reuse is actually intended.
- [ ] Keep secrets, customer data, and private operating details out of the repository.

### P3 — Proof layer

For each featured system, add a compact proof block:

- **Outcome**
- **Users**
- **Live/demo URL**
- **Architecture**
- **Verification**
- **Production status**
- **Known limitations**
- **Business value**

Add screenshots for:

- [ ] Gratog storefront / checkout / admin or order flow
- [ ] ASCA public PWA + admin workspace
- [ ] Cod3Black Agency funnel / admin
- [ ] Ownly dashboard
- [ ] SD Studio Web generation UI
- [ ] One additional client system

### P4 — Consistency cleanup

- [ ] Audit every non-archived public repository.
- [ ] Classify each as one of:
  - Production system
  - Active client system
  - Active product
  - Retained asset
  - Reference/example
- [ ] Archive anything that does not deserve a current classification.
- [ ] Fix README contradictions, stale dates, placeholder text, and invalid links.
- [ ] Remove generic topics such as only `canonical` / `active-development` when more useful product/domain topics can be added.
- [ ] Standardize default branch naming on new repositories.
- [ ] Add repository social-preview images to featured projects.

### P5 — Commercial conversion

- [ ] Add GitHub-specific UTM attribution to the portfolio/project inquiry link.
- [ ] Route inquiries into Cod3Black Signal.
- [ ] Capture source = GitHub, repo/profile origin, problem, desired outcome, authority, and next step.
- [ ] Add a short “Start a project” form instead of relying only on mailto.
- [ ] Track profile → portfolio → inquiry conversion.
- [ ] Turn the best case studies into productized offers with clear entry points.

## Repo-by-repo immediate recommendations

### Gratog

- Keep as a top pin.
- Add screenshots and a compact architecture diagram.
- Reconcile any stale README details against current production behavior.
- Decide whether the repo is intentionally open source; it currently has no license.
- Add/verify SECURITY and contribution guidance appropriate to a production commerce system.

### ASCA PWA

- Keep as a top pin.
- Preserve its strong truth/limitations language.
- Add screenshots of public and admin surfaces.
- Add an architecture diagram.
- Decide license/contribution posture explicitly.

### c3bai

- Keep as a top pin.
- Replace the minimal technical README with a stronger product/case-study README.
- Show the funnel, admin/dashboard, architecture, live URL, and verified capabilities.
- Add modern auth/security notes; the current MVP README still describes simple env-based admin auth.
- Add CI/security/community files appropriate to its role.

### cod3blackagency-portfolio

- Keep as a top pin.
- Use it as the canonical public index of projects, status, and evidence.
- Add links to screenshots/case studies as they are created.
- Keep its MIT license only if that licensing choice is intentional for the repository content.

### Ownly

- Strong reusable-asset candidate.
- Verify every “production-ready” claim against the current code.
- Remove any example testimonials unless they are real and attributable.
- Reconcile documented database configuration details if any section contradicts the actual stack.

### SD Studio Web

- Strong technical breadth candidate.
- Keep CI, CodeQL, SECURITY, license, demo, and roadmap visible.
- Add one screenshot/GIF and verify demo health periodically.

### SaaS Opportunity Bot

- Add repository description and homepage/demo if one exists.
- Clarify whether the ottomator integration is current.
- Add CI/security/license if the project remains public and maintained.
- Treat as a retained asset unless it becomes an active product again.

## Definition of done

The GitHub profile reaches A+ only when:

- the six pins are intentional and current;
- every featured repo is understandable in under two minutes;
- every live/production claim has a verifiable path;
- every featured repo has clean metadata and visual proof;
- security/testing posture is appropriate and visible;
- stale or contradictory READMEs are removed;
- the profile routes serious prospects into a measurable Cod3Black lead flow;
- an external reviewer can distinguish **production**, **active**, **prototype**, **retained**, and **private/proprietary** work without guessing.

## Review cadence

Run this audit monthly or after any major product launch:

**Profile → Pins → Metadata → README → Demo → CI → Security → Status → Conversion**

The goal is not more GitHub activity. The goal is a GitHub presence that converts technical capability into trust, opportunities, customers, and reusable leverage.
