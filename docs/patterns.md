# EVE Design Patterns

EVE Design Patterns describe **repeatable value flows** that can be reused across systems.

They are not UI patterns.
They are not business models.

They are **behavioral and economic patterns** that make value legible.

---

## How to use patterns

1. Choose a pattern that matches your context
2. Identify which SATE signals are involved
3. Decide whether incentives are needed
4. Select a verification method
5. Test, iterate, simplify

---

## Pattern: Value Inversion

**When participation creates value, reward it instead of charging for access.**

Problem:
Systems assume users must pay, even when their actions reduce costs or create shared benefit.

Pattern:
Invert the value flow so contributors are rewarded for participation.

SATE:
Attention · Time · Ecology

Typical incentives:
Level 2 → Level 3

Verification:
Two-sided confirmation, contextual validation

Common failure:
Over-rewarding → spam

Examples:
PARKIFY, energy shifting, waste sorting

---

## Pattern: Discovery Creates Value

**Finding something valuable is itself a valuable act.**

Problem:
Discovery work is invisible and unrewarded.

Pattern:
Treat discovery as a first-class contribution.

SATE:
Attention · Skill · Time

Typical incentives:
Level 1 → Level 2

Verification:
Peer confirmation, time-bound proofs

Examples:
PARKIFY spotters, Sonic Spots, local knowledge sharing

---

## Pattern: Pause as Infrastructure

**Sometimes the most valuable action is stopping.**

Problem:
Systems optimize for speed, output, and engagement.

Pattern:
Design intentional pauses where presence is the contribution.

SATE:
Attention · Time

Typical incentives:
Level 0 → Level 1

Verification:
Session completion, self-attestation

Examples:
prezns (Alice), reflection tools, coaching flows

---

## Pattern: Authorship Matters

**Value carries meaning when authorship is preserved.**

Problem:
Aggregation flattens individual contribution.

Pattern:
Preserve attribution, intent, and provenance.

SATE:
Skill · Attention · Time

Typical incentives:
Level 1 → Level 2

Verification:
Peer review, attribution chains

Examples:
STYL, remix tools, knowledge platforms

---

## Pattern: Participation Without Surveillance

**Participation should be voluntary, visible, and consent-based.**

Problem:
Participation is measured through passive tracking.

Pattern:
Use explicit signals instead of surveillance.

SATE:
Attention · Time

Typical incentives:
Level 0 → Level 1

Verification:
Opt-in reporting, voluntary check-ins

Examples:
Civic systems, public services, trust-sensitive domains

---

## Explicit Responsibility Anchor

**Preserving human accountability as systems scale.**

Problem
As systems scale, responsibility tends to diffuse. Incentives reward activity, engagement, and output — while ownership becomes abstract ('the system,' 'the process,' 'the platform'). When outcomes degrade or harm occurs, no single person remains clearly accountable. This erosion undermines trust, even when systems are technically effective.

Core Insight

Responsibility cannot be automated or delegated to systems. It remains irreducibly human. Systems should not attempt to be responsible. They should be designed to prevent responsibility from disappearing as scale, incentives, and abstraction increase.

Solution

Design systems so that: a named human owner is always associated with meaningful intent; ownership persists across time, not just at creation; responsibility cannot quietly dissolve into abstraction; when things become ambiguous or costly, someone is still clearly accountable. The role of the system is to make responsibility visible, durable, and hard to evade — not to replace it.

Implementation Signals

1. Explicit ownership fields tied to intent or decisions

2. Time-aware responsibility (who owned what, and when)

3. Provenance and authorship metadata attached to outputs

4. Clear escalation paths that preserve named accountability

5. No 'system-owned' decisions without a human sponsor

When to use

AI-assisted creation or decision systems, governance or moderation platforms, high-scale content or automation pipelines, any system where trust matters more than throughput

Anti-Patterns

1. 'The system decided'

2. Anonymous or rotating ownership

3. Engagement metrics substituting for accountability

4. Responsibility disappearing at scale boundaries

5. Provenance without a responsible human owner

**Reference Implementations (Non-Prescriptive)**

Some open standards demonstrate how responsibility and authorship can be made legible in digital systems. These are examples, not requirements.

Content Authenticity Initiative (CAI)
Learn more here: https://contentauthenticity.org/

Shows how attribution and intent can travel with content across systems.

C2PA (Coalition for Content Provenance and Authenticity)
Learn more here: https://c2pa.org/

Defines open technical specifications for cryptographically verifiable provenance metadata.

**Boundary**

These mechanisms help reduce plausible deniability and support human accountability — but responsibility itself always remains human.
