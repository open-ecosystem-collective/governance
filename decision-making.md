# Decision Making

**Open Ecosystem Collective – How We Decide**

We make decisions the way mature open source communities do:  
transparently, with low friction, and with a clear bias toward action.

The model is **Lazy Consensus**, the same approach used by the  
Apache Software Foundation since its founding.

**Version:** 1.0  
**License:** CC-BY-SA 4.0

---

## The core principle

> *Silence means agreement. Objection requires a reason and an alternative.*

This is not passive decision-making. It is efficient decision-making.
We assume good faith. We assume that if something is wrong, someone will say so.
And we create the conditions where saying so is easy.

---

## Lazy Consensus – how it works

**Step 1 – Propose**  
Anyone in the collective can make a proposal. Post it in the shared channel
or open a GitHub issue. State clearly:
- What you are proposing
- Why you are proposing it
- What happens if no one objects

**Step 2 – Wait 72 hours**  
The proposal is open for 72 hours. Anyone can comment, ask questions,
or raise an objection.

**Step 3 – Silence = yes**  
If no objection is raised within 72 hours, the proposal is accepted
and can be implemented.

**Step 4 – Objection = discussion**  
If someone objects, they must provide:
- A clear reason why the proposal is problematic
- An alternative suggestion or a request for more time

An objection without reasoning is not valid.

**Step 5 – Resolution**  
If an objection is raised, the proposer and the objector work toward
a modified proposal. If agreement cannot be reached within 7 days,
the matter is escalated to Tania as founder for a final decision.

---

## What decisions use Lazy Consensus

| Decision type | Process |
|---|---|
| Adding a new document or playbook to the methodology | Lazy Consensus (72h) |
| Updating an existing document (minor change) | Lazy Consensus (72h) |
| Accepting a new collective member | Lazy Consensus (72h) + peer review |
| Advancing a member to a higher maturity level | Lazy Consensus (72h) + peer review |
| Changing the revenue split | Supermajority (2/3 active members) |
| Changing a core value | Supermajority (2/3 active members) + founder review |
| Removing a member from the collective | Tania decision after peer review |

---

## Supermajority decisions

Some decisions are significant enough that Lazy Consensus is not sufficient.
These require explicit agreement from at least **two thirds of active members**.

Active member = anyone who has completed at least one mandate in the
previous 6 months or made a meaningful contribution to the methodology
repository.

Supermajority decisions must be open for **at least 7 days** before closing.

---

## The founder period (2026–2029)

During the first three years, Tania Vonarburg-Romero holds a **founder veto**
on changes to the core values (the 7 values defined in the Values Charter).

This veto exists to protect the foundational character of the collective
during the period when governance is still being established.
It is time-limited and will not be renewed.

On all other decisions, Tania participates as a regular member –
one voice, one vote.

---

## Versioning of governance documents

All governance documents follow **Semantic Versioning**:

```
v1.0  →  Initial release
v1.1  →  Minor clarification or improvement (no structural change)
v1.2  →  Additional content within the existing structure
v2.0  →  Significant structural change or new core element
```

**Every version is permanently tagged** in the GitHub repository.  
A document can never be quietly changed without a record.

If you are using a specific version of the methodology or charter,
you can always find it by tag.

---

## How to propose a change

**For small changes** (typos, clarifications, examples):
- Submit a Pull Request directly
- If no one requests changes within 72 hours, it is merged

**For significant changes** (new section, changed process, new value):
- Open a GitHub Issue first
- Describe the change and the reasoning
- Lazy Consensus runs in the issue thread (72h)
- Once accepted, submit the Pull Request

**For core value changes:**
- Open a GitHub Issue
- 7-day discussion period (not 72h)
- Supermajority required
- Tania reviews before merging

---

## What happens when things go wrong

**A member violates the values:**  
The matter is raised directly with the member first (Courage, value 05).
If unresolved, it is brought to the collective for a peer review.
Tania makes the final decision on membership status.

**A mandate goes badly:**  
The delivering member, Tania, and the client have a structured retrospective.
Findings are documented (anonymised) and used to improve the methodology.
Revenue split adjustments for failed mandates are handled case by case.

**Two members disagree:**  
Direct conversation first. If unresolved after 7 days, either party
can request a structured mediation with Tania as facilitator.

---

## The decision log

Significant decisions are recorded in `CHANGELOG.md` with:
- Date
- What was decided
- Who proposed it
- Whether it passed by Lazy Consensus or Supermajority
- Version number if it triggered a document update

This log is public and permanent.

---

## Why this model

The Apache Software Foundation has used Lazy Consensus for over 25 years
across hundreds of projects and thousands of contributors. It works because:

- It creates a **bias toward action** – things happen unless someone stops them
- It **distributes responsibility** – everyone is accountable for speaking up
- It **scales** – it works the same way whether there are 3 members or 30
- It **builds trust** – every decision is visible and traceable

We did not invent this. We borrowed it from people who got it right.

---

*Open Ecosystem Collective · CC-BY-SA 4.0 · v1.0*  
*github.com/open-ecosystem-collective/governance*
