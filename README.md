# Conversion Rate Optimization — SKILL.md files for AI agents

[![13 skills](https://img.shields.io/badge/skills-13-0b7285)](#whats-inside)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Works with Claude Code & Codex](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Codex%20%7C%20Claude.ai-1c7ed6)](#install)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free, ready-to-run **conversion rate optimization** skills for **Claude, Claude Code, OpenAI Codex** and any agent
that reads the [Agent Skills](https://agentskills.io/specification) format. Audits, research, landing pages, forms,
checkout, pricing pages, sign-up flows, mobile conversion, social proof, test planning and honest reporting. Each
skill is a single `SKILL.md`: a senior practitioner's workflow — when to use it, the inputs to ask for, a numbered
process, decision rules, an output template and sources — loaded only when a task needs it.

Part of the [Marketing Skills library](https://github.com/afeezadebayo/marketing-skills) by
[Afeez Adebayo](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/marketing/conversion-rate-optimization/)

## Install

Each skill is its own folder with a `SKILL.md`, so you can drop any folder straight into an agent.

**Claude Code**
```bash
git clone https://github.com/afeezadebayo/conversion-rate-optimization-skills.git
cp -r conversion-rate-optimization-skills/cro-audit ~/.claude/skills/        # all projects
# or  .claude/skills/   inside one project
```

**OpenAI Codex**
```bash
cp -r conversion-rate-optimization-skills/cro-audit ~/.agents/skills/         # all repos
```

**Claude.ai / Desktop** — zip a skill folder, then **Settings → Capabilities → Skills → Upload skill**
(code execution must be enabled). To bulk-load the whole category into a Claude Project, custom GPT or
knowledge base, grab the single-folder `.zip` from the
[library page](https://afeezadebayo.com/skills-md/marketing/conversion-rate-optimization/).

Then start a new session and ask your agent which skills it can use.

## What's inside

| Skill | What it does |
|---|---|
| [`cro-audit`](cro-audit/SKILL.md) | Audit a website or app conversion journey end to end, with hypotheses separated into fixes, tests and research. The entry point. |
| [`conversion-research`](conversion-research/SKILL.md) | Plan and run conversion research that produces strong hypotheses: recordings, surveys, user testing. |
| [`landing-page-optimisation`](landing-page-optimisation/SKILL.md) | Optimise homepages and landing pages: five-second clarity, message match, proof, objections. |
| [`form-optimisation`](form-optimisation/SKILL.md) | Improve sign-up, lead, quote and application forms: field justification, validation, mobile. |
| [`checkout-optimisation`](checkout-optimisation/SKILL.md) | Reduce cart and checkout abandonment: cost transparency, guest checkout, payment methods. |
| [`pricing-page-optimisation`](pricing-page-optimisation/SKILL.md) | Improve pricing pages so visitors choose a plan with confidence: clarity, recommendation, FAQs. |
| [`signup-flow-optimisation`](signup-flow-optimisation/SKILL.md) | Optimise sign-up and early onboarding from click to activation, judged on activated users. |
| [`social-proof-trust`](social-proof-trust/SKILL.md) | Use social proof and trust signals where visitors doubt, placed at the point of hesitation. |
| [`mobile-conversion`](mobile-conversion/SKILL.md) | Close the gap between mobile and desktop conversion: speed, layout, forms, payments. |
| [`popups-onsite-messaging`](popups-onsite-messaging/SKILL.md) | Plan on-site popups and messaging that help rather than annoy, measured against holdouts. |
| [`cro-test-planning`](cro-test-planning/SKILL.md) | Build a CRO test roadmap: hypotheses, traffic estimates, scoring, scheduling and a learning log. |
| [`cro-reporting`](cro-reporting/SKILL.md) | Report CRO programmes credibly: outcomes, test velocity, honest impact estimates with ranges. |
| [`conversion-copywriting`](conversion-copywriting/SKILL.md) | Write and test conversion copy from customer language: headlines, CTAs, microcopy. |

## How these skills work

Agents use *progressive disclosure*: they read each skill's `name` and `description` (~100 tokens) at the start
of a session and load the full `SKILL.md` only when your request matches — so you can install many without
filling the context window.

## Author & licence

By [**Afeez Adebayo**](https://afeezadebayo.com) — Marketing, SEO & Growth (SEO & Organic Growth at Grey, YC W22).
[LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon) · [Newsletter](https://afeezadebayo.com/newsletter/)

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) — use, share and adapt, including
commercially, with credit to Afeez Adebayo and a link to the source page in each file.

<sub>Keywords: CRO skills, conversion rate optimization, SKILL.md, Agent Skills, Claude skills, Claude Code skills,
Codex skills, AI agent skills, A/B testing, landing page optimisation, form optimisation, checkout optimisation,
pricing page, sign-up flow, mobile conversion, social proof, CRO reporting, conversion copywriting.</sub>
