# EU AI Act: where to start

**The regulation is big, your capacity is not.** This repository answers a question most guides skip: what do you do **first** when one person handles this on the side?

[Deutsche Fassung](README.md)

---

## The situation this guide assumes

A company with 40 employees. Someone in finance or IT got the topic on top of their job, has maybe one day a month for it, and is reading a guide that lists 60 obligations without any order.

The result is usually one of two things. A policy gets written, because that looks doable. Or nothing happens, because everything seems equally urgent.

Both are avoidable, with one simple insight: **the obligations are not equally urgent, and they build on each other.**

## Four things that apply today

Regardless of risk class and regardless of any postponement:

| Obligation | Since | Effort |
|---|---|---|
| **Art. 5**: do not operate prohibited practices | 2 Feb 2025 | check once, low |
| **Art. 4**: measures for staff AI literacy | 2 Feb 2025, reworded 27 Jul 2026 | medium, recurring |
| **Art. 50**: transparency for chatbots and generated content | 2 Aug 2026 | small, technical |
| GPAI obligations | 2 Aug 2025 | concerns model providers, not you |

**High-risk under Annex III only applies from 2 Dec 2027.** The Digital Omnibus (Regulation (EU) 2026/1744) moved it by 16 months. That is the biggest relief and also the most common misreading.

## What the postponement does not postpone

It moves the **list of obligations** for high-risk systems. It does not move the two steps that come before:

1. **Knowing what you have.** Without a register you cannot tell whether you are affected.
2. **Knowing your role.** Under Art. 25 an organisation can become the **provider** of a high-risk system without noticing, with conformity assessment and technical documentation attached. That is not six weeks of work.

Whoever waits until late 2027 starts the inventory and the obligations at the same time.

## The order

| Phase | What | Why first |
|---|---|---|
| **1** | Rule out prohibited practices (Art. 5) | applies since 2025, and a hit makes everything else moot |
| **2** | Take stock | without a register every further statement is a guess |
| **3** | Implement transparency (Art. 50) | applies since August 2026, technically small |
| **4** | AI literacy (Art. 4) | applies since 2025, and oversight does not work without it |
| **5** | Classify | now with a basis |
| **6** | Obligations per class | most of it can wait until 2027 |

In detail, with effort estimates per phase (German): [compliance path](./knowledge-base/eu-ai-act/compliance-path.md)

## The eight misconceptions that cost the most time

1. "The AI Act has been postponed." Art. 50 applies since August 2026.
2. "We only use third-party tools, so we are not affected." Deployer obligations apply, and Art. 25 can turn you into a provider.
3. "First we need an AI policy." A policy for an unknown inventory regulates nothing.
4. "Our vendor is compliant, so we are." Their conformity does not replace your deployer obligations.
5. "The data protection officer will handle it." Partly, but the role question and the classification are not GDPR.
6. "We are too small." There is no threshold by headcount.
7. "A human makes the decision anyway." Only if they actually can.
8. "High-risk does not concern us, we do not do medical devices." Employment and creditworthiness are the more common cases.

Each with reasoning (German): [misconceptions](./knowledge-base/eu-ai-act/common-misconceptions.md)

## Contents (German)

| Document | Content |
|---|---|
| [What applies when](./knowledge-base/eu-ai-act/overview.md) | dates, and what to do today |
| [Terms](./knowledge-base/eu-ai-act/definitions.md) | the six terms you actually need |
| [Does it concern us](./knowledge-base/eu-ai-act/scope-and-actors.md) | role, Art. 25, territorial scope |
| [The classes](./knowledge-base/eu-ai-act/risk-logic.md) | the structure, without classification theory |
| [The path](./knowledge-base/eu-ai-act/compliance-path.md) | six phases with effort and result |
| [Misconceptions](./knowledge-base/eu-ai-act/common-misconceptions.md) | eight sentences that cost time |
| [Who does it](./knowledge-base/eu-ai-act/inventory-and-governance.md) | responsibility with limited capacity |

Template: [roadmap](./templates/compliance-roadmap-template.md), the six phases with dates, owners and effort, ready for management.

Machine-readable: [framework/simpleact-framework.json](./framework/simpleact-framework.json), [llms.txt](./llms.txt). All obligations and dates as JSON, YAML and iCalendar: [eu-ai-act-dataset](https://github.com/SimpleAct-Compliance/eu-ai-act-dataset).

## Next

- [AI inventory](https://github.com/SimpleAct-Compliance/simpleact-ai-system-inventory): phase 2 in detail
- [Risk classification](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu): phase 5
- [AI Act checklist](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist): phase 6
- [AI literacy](https://github.com/SimpleAct-Compliance/elearning): phase 4
- [Governance framework](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework): how it fits together

## In software

[SimpleAct](https://simpleact.eu) runs the phases as linked registers with deadlines and an audit trail: **[AI Act software](https://simpleact.eu/ai-act-software)**. Readable overview of the regulation: [EU AI Act explained](https://simpleact.eu/ai-act).

## Status and licence

Last updated: 2026-11-26. MIT licence, free to use, also commercially. Not legal advice.
