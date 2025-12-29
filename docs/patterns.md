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

**Make responsibility visible, durable, and hard to quietly offload as systems scale.**


**Problem**

As systems grow, responsibility tends to diffuse:

- decisions are abstracted into workflows

- outcomes are attributed to “the system”

- accountability erodes under scale, speed, and automation



This creates high activity with low ownership — especially in AI-mediated systems.


**Insight**

Responsibility cannot be automated.

But interfaces can be designed so responsibility is harder to avoid.


The goal is not control — it’s clarity.


**Solution**


Introduce an Explicit Responsibility Anchor at critical moments in a system:

- clearly identify who owns a decision, artifact, or outcome

- keep that ownership visible over time

- make handoffs explicit, not implicit



The anchor lives in the interface, not in policy.


**Design Principles**


- Named ownership
Someone (or a defined role) is visible and attributable.

- Durable over time
Ownership persists beyond creation, launch, or automation.

- Survives scale and pressure
Responsibility does not disappear when volume increases.

- No behavioral enforcement


The system does not punish or compel — it reveals.


**Where this applies**


- AI-generated content and media

- Automated decision systems

- Shared dashboards and reporting tools

- Open platforms and marketplaces

- Governance-adjacent systems without central authority

<br>

**Related standards & implementations**


This pattern aligns with (but does not mandate):


- <a href="https://contentauthenticity.org/">Content Authenticity Initiative (CAI)</a>

- <a href="https://c2pa.org/">C2PA (Coalition for Content Provenance and Authenticity)</a>

<br>


These provide technical mechanisms for attribution and provenance that can act as responsibility anchors.


---

**Why this is not governance**

- It does not define rules, policies, or enforcement

- It does not assign moral or legal judgment

- It does not replace institutions or accountability structures
<br>
This pattern answers one question only:

<em>“Who is still responsible when things get messy?”</em>



**Failure modes to watch for**


- Anonymous defaults

- Responsibility hidden behind automation

- Ownership erased by aggregation

- “The system decided” narratives

---

**In the EVE framework**

Explicit Responsibility Anchors support:


- Authorship — clear provenance and intent

- Trust — visible ownership under pressure

- Participation — accountability without coercion


They help systems scale without dissolving meaning.


---

**Boundary**

These mechanisms help reduce plausible deniability and support human accountability — but responsibility itself always remains human.
