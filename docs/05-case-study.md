# 5. Case study: building a 300+ person AI-enabled delivery organisation

> This case study summarises results and approaches from my résumé, written generally. It contains no confidential data, client names or internal documents. Where I give numbers, they are the ones on my résumé.

## Context

I built and ran the India delivery centre of a Series B AI SaaS company: a distributed organisation of 300+ people serving US clients across time zones, reporting to global leadership. I led a team of about 250 through team leads and managers, and owned the centre's budget.

## The starting problem

Delivery quality at **76%**, in an organisation that needed to grow volume. Quality and productivity usually pull against each other.

## What I did

| Area | Action |
|---|---|
| **Leadership** | Built the organisation from zero to 300+, set one consistent management approach across team leads, and developed leads into a second line of managers who ran day-to-day operations. |
| **Quality** | Rebuilt quality gates, calibrated reviewers, and ran root-cause reviews on recurring errors. Treated defects as process problems. |
| **Automation** | Built agentic AI workflows (n8n, Zapier, Asana AI Studio) for intake, routing, quality checks and reporting. Defined what each automation handled alone, where a person had to approve, and how exceptions reached the right owner. |
| **Capability** | Built an onboarding assistant from recorded expert walkthroughs that new joiners question by voice (see [onboarding](04-onboarding-system.md)). Designed onboarding and training programmes, SOPs and playbooks. |
| **Economics** | Owned the budget, forecast demand into capacity and hiring plans, tracked utilisation, and rebalanced when pressure built. |
| **Rhythm** | Ran a daily, weekly and monthly review cadence with dashboards for capacity, utilisation, service levels and cost. |
| **Governance** | Worked with auditors, finance and legal counsel on compliance; served on the workplace committee for harassment prevention. |

## Results (from my résumé)

- Delivery quality from **76% to 95%+**, while productivity rose by more than **200%**. Both moved up together.
- Experts regained about **2 hours a day**, and new joiners became about **60% more productive** with the onboarding assistant.
- Recognised 15 times: 8x Best Leader, 4x Process Excellence, 3x Gold Star.

## The ideas the approach rests on

1. **Quality improves through the system.** Rebuilt gates, calibrated reviewers and root-cause reviews address causes, rather than asking people to try harder.
2. **Automation is bounded.** Each workflow has a defined scope, an approval point where needed, and an exception owner, so nobody has to guess who handles an error.
3. **One management approach across team leads** was a deliberate focus at this size.
4. **Statistical monitoring** (control charts, reviewer agreement) is the natural formalisation of this approach. The companion repo implements it: [`ai-quality-and-evals`](https://github.com/MohitBhatnnagar/ai-quality-and-evals).

## How this repo relates to that experience

The companion repositories are **reference implementations and frameworks I built from that experience**, using synthetic data. They show how I think about the same problems: which work agents should do ([playbook](https://github.com/MohitBhatnnagar/ai-workforce-design-playbook)), how autonomy is enforced ([`agentflow-hitl`](https://github.com/MohitBhatnnagar/agentflow-hitl)), how output is measured ([`ai-quality-and-evals`](https://github.com/MohitBhatnnagar/ai-quality-and-evals)), how it is governed ([`ai-governance-framework`](https://github.com/MohitBhatnnagar/ai-governance-framework)) and how it is justified ([`automation-business-case`](https://github.com/MohitBhatnnagar/automation-business-case)).
