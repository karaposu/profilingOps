---
status: active
model: claude-fable-5
effort: max
---
# Finding: attachment_formation

## Question

How does attachment **form and deepen over time**? The user's spoken prompt raised this from lived cases, as a set of facets:

- **A "generating" quantity and a "spoon."** Two people can end up attached via a four-year school friendship (long exposure, mild intensity) or a one-month military room (short exposure, huge intensity — "you need each other's things… I did things I would normally not do for other people"). So formation seems to have a *rate* ("spoon depthness" — how much attachment one unit of exposure delivers) and a *duration*, trading off.
- **Conditions beyond exposure.** "It is not as simple as just spending exposure time" — availability without contact (phones, internet: "you are not even talking, but you can still be kind of available"), common activities, mutual need.
- **The indirect route.** Kids don't make friends by asking for friendship; they want to play the game, gather around it, and "due to the game… they end up attached to each other." "We don't form attachment to the personality directly… unless it's the charm… it revolves around the outcomes, expectations, hope."
- **Common fear as fast bonding.** Exam-season students with a "common enemy" (the exam, the teacher) bond unusually fast — sharing notes, asking help, needing each other.
- **Per-person decay profiles.** The user keeps bonds formed in bad times and remembers those people; other people bond during bad times but "once it's finished, this attachment doesn't stay long" — they go where the fun, hope, and resources are.
- **Two regimes.** A salesperson has one short exposure and "should act differently" than a restaurant owner with years of repeat contact.

With an explicit bound, in the user's words: *"try to expand our understanding and uncover new frontiers to dive deep, rather than enforcing premature definitions — we are not in a hurry… branch in each."* So the deliverable is an **expansion**: frontiers named and well-posed, none settled.

## Reader's key

This inquiry lives inside **BDA (Belief-Driven Attachment)** — this project's theory of attachment, kept in the `BDA/` folder of this repository. What you need to follow this finding:

- **The core claim.** Attachment is on the *receiver's* side and is built from the receiver's **beliefs about the sender** (the person they may attach to). Roughly: Attachment ≈ f(Charm, Hope, Fear, Resonance) × gate(Self-Positioning) × gate(Coherence) × gate(Emotional Composure).
- **The four variables** (property-beliefs — they *add up*):
  - **Charm** — "this person is high-status, competent, impressive — I look up to them."
  - **Hope** — "good things for me can come through this person" (forward-looking; it comes in flavors — doing things together, attention, validation, a shared future, growth, return on what I invested, safety).
  - **Fear** — "this person could bring about an outcome I dread" (what they could do, or losing them).
  - **Resonance** — "they see the world the way I do" — a shared way of seeing, built by attending to the same things together.
- **The three gates** (stance-beliefs — they *multiply*; any one at zero collapses the whole):
  - **Self-Positioning** — they hold their own ground; not begging, not extracting.
  - **Coherence** — their story hangs together; what they show matches what they feel.
  - **Emotional Composure** — they hold themselves steady.
- **How beliefs move** (`BDA/10_ARCHITECTURE.md`): the belief-side is **cumulative** — it builds from evidence over history, can be pre-loaded by reputation, moves slowly against strong priors, ignores evidence below a quality threshold, and updates faster from *independent* sources than from one source repeating. Every signal counts in proportion to its **specificity** (how unmistakably it is about *this* person/pair). The gates, by contrast, are read in **seconds** — that is the corpus's "temporal precedence" rule.
- **The open register** (`BDA/80_OPEN_REGISTER.md`) — the corpus's list of open problems. Two of its entries own this territory:
  - **FR2, the static/dynamic boundary:** the theory deliberately states *levels*, not change-over-time; every dynamics observation must be **composed out of static machinery**, never admitted as a new "modulator" term (a prior attempt to add a decay-modulator was killed for exactly this). FR2 already carries three dynamics parameters — **contact-frequency, context-breadth, perturbation-rate**.
  - **FR3, the deepening question:** "can a Transactional attachment deepen into a Bonded one?"
- **"Occasion"** — one contact in which something can actually be evidenced. **"Object"** — whatever joint attention is on (a game, an exam, a task, a topic; scale doesn't matter).
- **Prior findings consumed here:** `inquiries/2026-08-31_16-25__charm_persistence/finding.md` (how attachments are *kept*: each variable has a maintenance source and a removal event; re-encountering the record of someone is itself an occasion) and `inquiries/2026-08-31_17-16__fear_as_outcome/finding.md` (the Fear variable = dread of a *sender-mediated* outcome × dependency; fear of a shared third party is a different thing).

## Finding Summary

- **The corpus had no formation account.** Its belief machinery says beliefs accumulate (the rise side); its sequence machinery (the five insistence mechanisms, wear-in) is written for the *sender who returns*. The receiver's own formation under shared activities — where every one of the user's cases lives — was unwritten. Formation is also the theory's founding question returning: the project began as "how do you make someone keep talking to you."
- **The spine (an observation, not a definition):** attachment forms as **evidence is delivered through shared objects** — *formation runs where attention is joint on something; it stalls where attention is on the relation's outcome.* This is falsifiable: a bond formed by sustained attention on the relation itself ("do you like me?", "what are we?") with no shared object anywhere would refute it.
- **The "spoon" is not a new quantity.** It decomposes into quantities the corpus already has: **occasions × specificity × cost visibly paid × independence of sources × perturbation** — with duration only the *container* of occasions. Three of the five factors are FR2's own dynamics parameters, so one triple may govern three dynamics at once (detection speed, frame-settling, formation-rate) — a prediction-grade candidate, deliberately not asserted.
- **A shared object does two jobs at once:** attention on it is non-extractive (it keeps the Self-Positioning gate open) *and* co-attention on it generates Resonance. That is why formation is indirect by default, and why the direct route ("will you be my friend?") tends to fail — it puts attention on the counterparty's response, which is the gate's failure pole.
- **Charm is not an exception to the indirect route.** Its evidence also arrives through an object — the person seen *at their own work*. The belief is about the person; the evidence is still object-mediated.
- **"Common fear" bonding is not the theory's Fear variable.** Nobody dreads the classmate; the teacher is a third party outside the bond. It is the **fastest delivery configuration** the frame can describe — shared object + need + perturbation + costs paid at high specificity — and hardship *also* settles the gates early (stress is when composure and coherence get actually read). The complement: **calm-formed bonds are untested** — high belief, thin gate evidence — and re-price at the first crisis.
- **Deepening looks like conversion through a generative object.** The four-year school friendship starts as exchange around shared classes and ends as a shared way of seeing — the corpus's deepening question (FR3) generalizes into a **conversion table** (which variable's evidence turns into which, over time), all rows candidates.
- **The decay profiles are receiver-side, with three candidate mechanisms:** what the bond was made of (need-based Hope dissolves when the need ends; Resonance persists) × how the receiver weights *past-conditioned* belief (the return-on-what-I-invested flavor of Hope — the corpus's only past-conditioned flavor, used here for the first time) × **debt-avoidance** (devaluing a helper to escape an unpayable ledger).
- **Availability without contact mostly maintains rather than forms** — with one forming face (safety: "they'd be there if I called") — and yields a prediction candidate: continuous low-specificity contact (the modern phone-tether) *keeps* bonds but *builds* little.
- **Nothing was settled — deliberately.** The output is a frontier field: **sixteen branchable routes** mapped in this inquiry's `routelister.md`, with one core action — registering the field under FR2/FR3 in the open register — and the rest pickable in any order.

## Finding

The user's prompt is the theory's own origin returning. The project began as a retention question ("how do you make someone keep talking to you"), and the corpus then grew a deliberately *static* theory: it tells you what attachment is made of at a moment, and it polices its own boundary (FR2) so that change-over-time never sneaks in as a cheap extra term. So when the user asks "how does attachment form, and what are its generation attributes?", the honest starting state is: the corpus has the **rise-side law** (beliefs accumulate from evidence), a **group-scale** mechanism for bonds forming around shared things, and a **sender-side** sequence account — and nothing about rate, nothing about the receiver's formation under shared activities, and no per-person profile. This run's job was to expand that gap into named, well-posed frontiers without settling any of them.

### 1 · The spine: formation is evidence delivery through shared objects

Everything in this field organizes around one observation:

> **Formation runs where attention is joint on something; it stalls where attention is on the relation's outcome.**

- The kids at the school break do not ask for friendship; they want the *game*, gather around it, and the attachment happens as a by-product. The user called this the indirect route and suspected it is "usually correct with people."
- The corpus agrees from its own commitments, and adds *why* (see §3 below): a shared object serves the gate and a variable at the same time.
- The claim earns its keep by being falsifiable. Its contrast class is real conduct: the kid who walks up and asks "will you be my friend?" (attention on the response); the pitch that talks about yourself instead of demonstrating on the customer's case; the partner who keeps asking "what are we?". If a bond were observed to form by *sustained* relation-outcome attention with no shared object anywhere, the spine breaks.
- Two edge cases are placed, not hidden:
  - **The null-object bond** — comfortable co-presence, saying nothing. Under the frame the co-presence itself is what attention rests on (the corpus's Rhythm-Comfort case).
  - **The relation as its own object** — two people genuinely examining "us" as a shared inquiry (Dialogue-Focus). That is still joint attention on a thing; it differs from demanding a verdict about the relation.
- Deeper than the object is **co-attention**: the object is not prior to the pair — it is *whatever joint attention lands on*. The kids do not choose the game first; the game is where attention landed. This re-words the practical move everywhere from "find a shared object" to **"attend together — the object appears."** For a seller: get their attention onto what your attention is on.

### 2 · The spoon decomposed: the delivery rate

The user proposed two parameters — a generating rate ("spoon depthness") and exposure time. The shape is right; the content reduces entirely to quantities the corpus already owns:

- **What one unit of exposure delivers** is not a new "intensity" quantity. It is a composition of:
  - **occasions** — how many contacts actually happen (contact-frequency);
  - **specificity** — how unmistakably each occasion's evidence is about this person/pair (a generic "hey" delivers ~nothing; covering for a roommate delivers a lot);
  - **cost visibly paid** — what each side gives up, seen by the other;
  - **independence** — evidence from different contexts/sources updates beliefs faster than the same channel repeating;
  - **perturbation** — stress and disruption, which is when backing (what's really there) gets revealed.
- **Duration is only the container of occasions.** "Spending time" is not a variable: duration with no occasions is absence; duration with repetitive low-content occasions is *correlated* evidence (updates almost nothing — the corpus's discount); duration with new, specific, costly occasions is formation. The strongest counter — mere-exposure (familiarity alone attaches) — was tested and keeps one point: raw occasion *density* may do more work than any per-occasion richness, and the *ordering* of the factors (density vs perturbation vs cost) is genuinely open. That ordering question is the rate frontier's first sub-question.
- **The military month vs the four school years, literally:** the month maxes every factor (24-hour contact, every context, constant perturbation, costs paid daily, many independent situations) — the highest delivery rate the frame can describe; the school years run at low values for long, with breadth and consistency doing the work. Both reach attachment; the *mix* differs (see §6).
- **The parameter-identity extension (the field's cleanest structural bet):** FR2 already claims that contact-frequency, context-breadth, and perturbation-rate govern both detection speed and frame-settling. Three of the rate's five factors are exactly that triple. If the same triple also governs formation-rate, **one set of levels governs three dynamics** — stamped as a prediction-grade candidate (its siblings carry the same honest "derived, not validated" label), not asserted.
- **The independence advantage:** many small, frequent, low-cost occasions may out-form one intense block — they are more independent, consistency needs repetitions, and manufactured intensity risks being priced as display. The corpus's marriage doc already says small daily costs outweigh grand gestures; this is its formation-side twin, also prediction-grade.
- **The two regimes are this composition at two settings** — no new mechanism:
  - *Short exposure* (the pitch, the approach): the gates dominate (they read in seconds — temporal precedence); belief can be **pre-loaded** (reputation, social proof) and must be delivered at maximum specificity and visible cost in the one encounter (demonstrate on *their* case); continuation runs through third parties.
  - *Long exposure* (the restaurant, the team): frequency, breadth, consistency-accrual, the running ledger of exchanges, and keeping the object generative (bring new things) do the work.
  - Which parameters each regime *can and cannot move* is the application frontier — deferred, per the user's "in the future, not now."

### 3 · The object's double job — why the indirect route is the default

Two commitments the corpus already holds, never before joined:

- Attention on a shared object is **non-extractive by construction** — so it keeps the Self-Positioning gate open. (The gate's failure pole is attention on the counterparty's response: begging, checking, extracting.)
- Co-attention on the same object **generates Resonance** — the corpus states this for groups (the shared term; the "Sid-function" that manufactures shared attention-objects) and this inquiry extends it as a *frontier claim* to dyads: two kids, one game — the Sid-function without a Sid.

So one shared object simultaneously protects the multiplier and feeds an adder. That is *why* formation is indirect by default: the indirect route is not a detour around attachment — it is the only route that does not collapse the gate while building.

- **The user's Charm exception dissolves.** "We don't form attachment to the personality directly… unless it's the charm" — but Charm's evidence is demonstration, never claims: the admirer sees the person *at their work*. The belief is about the person; the evidence still arrives through an object — the person's own work. All four variables' evidence is object-mediated; all four beliefs are about the person. Route and object-of-belief are different things.
- **A registrable absence:** the corpus's object condition is stated only at group scale; no dyad-scale statement exists. The extension is flagged as a frontier claim, not assumed.

### 4 · Shared stakes — what "common fear" bonding actually is

The exam group with the common enemy bonds fast. Two things had to be untangled:

- **It is not the theory's Fear variable.** That variable (per the fear_as_outcome finding) is a belief about the *attached-to person* — "this person could bring about an outcome I dread." The classmate threatens nothing; the teacher is a third party who is not the object of the bond. (The *teacher* may earn a Fear-dominant attachment from the students — a different dyad.)
- **What it is: the fastest delivery configuration the frame can describe.** Shared object (the exam) + need (help, notes, support — the safety/exchange/return flavors of Hope) + perturbation (stress reveals backing) + costs paid at high specificity, all at once. Every factor of §2's rate is maxed simultaneously.

Plus one genuinely new mechanism, from the corpus's backing machinery:

- **Hardship is a gate-test accelerator.** The gates are *read hard* under stress — composure and coherence show their real values in bad moments. So hardship bonds carry **front-loaded gate evidence**: they are "tested" from birth. That is a second, independent reason shared hardship bonds fast — the gates settle fast, not only the beliefs rising fast.
- **The complement: untested bonds.** A bond formed entirely in calm carries high belief with *thin* gate evidence — a specific, checkable profile whose known failure is the first crisis re-pricing everything (the friendship doc's crisis-absence rule).
- **The dark twin is priced, not banned:** engineered shared adversity (hazing, cults' shared enemies, "bonding" retreats, love-bombing's manufactured intensity) is the manufactured version of this configuration; the corpus's honest/manufactured line extends to *objects*.
- **The user's military bond, placed:** it looks need-shaped (can't leave; need each other) — but it persisted for years *after* the dependency ended, with no relief at exit. By the fear inquiry's own signature (relief-at-exit marks the coerced form), it was not fear-based: the need was scaffolding for the fastest honest delivery configuration, and what remained was Resonance and reciprocity.

### 5 · Deepening: conversion through the object, and the object's lifecycle

- **Deepening is a change of kind, not just more of the same.** The four-year friendship's late bond persists through absence; its early shared-classes bond would not have. That is exactly the corpus's open FR3 ("can Transactional deepen to Bonded?").
- **The candidate mechanism: conversion through a generative object.** Exchange-flavored Hope *around the object* (we do classes/games together) becomes, with enough co-attention, Resonance *with the person* (a shared way of seeing). Some exam-bonds persist (they became Resonance); some dissolve (they stayed need-Hope around an object that ended).
- **FR3 generalizes into a conversion table** — which variable's evidence converts into which, over time. Candidate rows only:
  - exchange-Hope → Resonance, through a generative shared object (FR3 itself — the first row);
  - need-Hope → Fear, under dependency (from the fear inquiry);
  - Charm → cost-of-loss, under irreplaceability (from the fear inquiry).
  - Each row owes its own evidence; the table is a map of questions, never a committed taxonomy.
- **The object's generativity is the pair's clock.** A game gets old; an exam ends; a startup keeps producing. When an object exhausts, the pair must **convert** (to Resonance), **succeed** (find the next object), or **plateau**. The long friendship is a *chain* of objects (classes → games → work → children); the war buddies are a one-object bond (survival) with nothing to say in peacetime unless a successor object is found. Prediction-shaped: persistence tracks the chain, not any single object.
- **The route leaves a signature in the type:** fast-perturbed formation over-weights gate evidence and safety-Hope; slow-calm formation over-weights exchange and accumulated Resonance — and a mix formed for one context may not transfer out of it.

### 6 · The decay profiles — why the same bond persists for one person and dissolves for another

The user's observation: they keep bad-time bonds; others drop them the moment the bad time passes and go where the hope, charm, and fun are. Three candidate mechanisms, none promoted:

- **The mix** (what the bond was made of): need-flavored Hope dissolves when the need ends — "dissolves when exchange ends" is already canon; Resonance persists through absence. A bad-time bond persists to the extent it *became* Resonance rather than staying need-Hope.
- **The bearing** (the receiver's weighting): the corpus has exactly one **past-conditioned** Hope flavor — reciprocity, "a return on what I invested" (`BDA/11_VARIABLES.md` calls it uniquely past-positive-conditioned; this is that clause's first consumer). The person who "doesn't care about the people who helped them" weights past-conditioned belief low and future-conditioned flavors high; the user weights it high. Also: *which objects* each person's Resonance forms around (struggle vs fun).
- **Debt-avoidance** (a third candidate, held at MEDIUM): an unpayable obligation is a *standing cost* — and devaluing or dropping the helper ends it. The fear inquiry's dependency logic in reverse: here the receiver escapes the ledger by leaving the bond. Its profiling-layer test: who avoids their helpers.
- **The home for all of this is the profiling layer** (`BDA/31` — attachment bearings), which today has no persistence dimension: *what a person's bonds survive* is a per-person dimension waiting to be sketched, with the user's own profile as case one and the opposite type as case two.

### 7 · Availability, the receiver's own costs, and the pair

- **Availability without contact** is mostly a *keep-side* channel: felt reachability maintains continuity-Hope and makes the next occasion cheap. It has exactly one forming face: **safety-Hope by standing possibility** ("they'd be there if I called") — a belief formed without any exchange. The extrapolation to the modern condition gives the field a prediction candidate: **continuous low-specificity contact maintains but forms little** — formation still needs high-specificity occasions. (The phone-tether keeps bonds alive; it does not build them.)
- **The receiver's own paid costs are evidence the corpus never modeled.** The user: "I did things I would normally not do for other people." That is a cost paid by the *receiver* — evidence to the other (in a symmetric bond both parties are senders) and to themselves ("I wouldn't have done that for anyone" — self-evidence about what the bond is). The corpus models costly signals only on the sender's side; **symmetric costs** is a registrable gap.
- **The pair itself** — "what we are" — is partially covered by existing machinery (the pair-frame; default crystallization; declarations as verdict-events) and partially not: the pair's *joint record* (shared history as a first-class object) and the receiver's costs above have no owner. The frontier is the gap list, not a new element.
- **Direct moves seal; they don't form.** Declarations, vows, and asks are verdict-events: before formation they force a premature no; after formation they crystallize what exists. The object route forms; the direct move seals — a sequencing rule joining this field to the corpus's verdict-timing doctrine, not a new mechanism.

### 8 · What the field's registration looks like — and what was deliberately not done

- **Four registrable absences** (verified against the artifacts): no receiver-side formation account anywhere in canon; no dyad-scale statement of the object condition; "occasion" defined only in a table row-note of `BDA/30_STATES_AND_SIGNATURES.md`; no persistence dimension in the attachment bearings.
- **The container is FR2/FR3, entered by composition.** Everything above composes static machinery — cumulative belief, specificity, costs, the gates, the persistence column. Three alternative shapes were generated and rejected (see Reasoning): writing a dynamics account into FR2 now, adding a formation column to the type table, and dissolving formation into persistence-read-backwards.
- **Deliberately not done, per the user's bound:** no formation modulator or rate term; no timeframes or half-lives (the corpus's B5 block); no settled conversion taxonomy; no new vocabulary entering canon (the run's coinages — "delivery rate," "the object's double job," "shared-stakes configuration" — are glosses, not terms); no re-opening of the Fear field (consumed by inheritance); no application run for the sales/restaurant regimes (posed, deferred).
- **The onward field is mapped:** sixteen routes in `routelister.md` (kept beside this finding, not archived) — one core (register the field), three high-priority unblockers (test the contrast-class spine; pose the rate composition + the identity extension; draft the conversion table as candidates), twelve supporting/peripheral.

## Inherited Commitments Re-test

This inquiry declared a Synthesis Trigger over six priors; each commitment is re-tested:

- **Commitment:** the belief-side is cumulative and history-dependent — pre-loadable, prior-resistant, thresholded, independence-sensitive, specificity-scaled.
  **Source:** `BDA/10_ARCHITECTURE.md` §3–§4.
  **Re-test status:** RE-TESTED — commitment confirmed.
  **Evidence:** the entire rate decomposition (§2) runs on it; the strongest counter (mere-exposure — familiarity alone attaches) was pressed against it and held structurally: familiarity without new specific evidence is correlated evidence (near-zero update); what exposure does add — occasions and threshold-crossing — is already committed machinery. The counter kept one point (the factor-ordering question), which became a frontier, not a revision.

- **Commitment:** costly signals carry belief (visible cost → inferred reliability), and the gates read in seconds while beliefs accumulate (temporal precedence).
  **Source:** `BDA/21_SELF_POSITIONING.md` §5–§6.
  **Re-test status:** RE-TESTED — commitment confirmed.
  **Evidence:** temporal precedence is what makes the short regime lawful (§2: gates dominate the pitch); costly signals ground the rate's cost factor. The re-test surfaced a *gap beside* the commitment, not against it: costs are modeled sender-side only, and the receiver's own paid costs (the user's military testimony) are unmodeled evidence — registered as the symmetric-costs frontier.

- **Commitment:** Resonance emerges when both parties hold the same attention-object; shared objects can be manufactured (the Sid-function); generative objects keep relations open, exhaustible ones complete.
  **Source:** `BDA/11_VARIABLES.md` §5 + `BDA/40_GROUPS_AND_LEADERSHIP.md` §4 (+ `40` §1 on generativity).
  **Re-test status:** RE-TESTED — commitment confirmed but frame revised.
  **Evidence:** the commitment holds and became the field's engine — but the re-test found it (a) stated only at *group* scale, so the dyad-scale use here is flagged as a frontier claim rather than assumed; and (b) derivative of a deeper primitive: co-attention is prior, and the object is whatever joint attention lands on — which re-words the mechanism ("attend together" rather than "find an object") without changing its content.

- **Commitment:** persistence = maintenance-source × removal-event per variable; Resonance is internally maintained; re-encountering the record is itself an occasion; expression waits for occasions.
  **Source:** `inquiries/2026-08-31_16-25__charm_persistence/finding.md` + `BDA/30_STATES_AND_SIGNATURES.md` §3.
  **Re-test status:** RE-TESTED — commitment confirmed.
  **Evidence:** consumed load-bearingly three times — the keep/form distinction for availability (§7), the between-occasion channels (record re-encounter as a committed occasion; the channel-less remainder placed outside), and the decay reading (§6: Resonance persists, need-Hope dissolves). No strain observed; formation and persistence stayed distinct fields.

- **Commitment:** the Fear variable = dread of a sender-mediated outcome × dependency; a shared third-party threat is not the Fear variable; trauma bonding and intermittent reinforcement are adjacent mechanisms, not instances.
  **Source:** `inquiries/2026-08-31_17-16__fear_as_outcome/finding.md`.
  **Re-test status:** RE-TESTED — commitment confirmed.
  **Evidence:** pressed hard by the exam case (the teacher *can* fail them — isn't that Fear?): held, because the teacher is not the object of the classmate-bond — the dyads separate cleanly, and the commitment's own instrument (relief-at-exit) retroactively cleared the military bond of the coerced reading. The commitment's stakes layer and dependency logic were additionally consumed (debt-avoidance as its reversal; relationship-specific investment as stake + shared model).

- **Commitment:** the static bound — dynamics arrive disguised as missing modulators; compose static machinery, never add a term; no timeframes (B5); FR2's parameter triple.
  **Source:** `BDA/80_OPEN_REGISTER.md` (FR2, B5) + the decay-modulator kill recorded there.
  **Re-test status:** RE-TESTED — commitment confirmed.
  **Evidence:** the user's "we should formalize it" pressure was the live test; three shapes that would breach the bound were generated on purpose and each failed on its own terms (Reasoning below). The bound then *produced* content rather than blocking it: the composition reading of the spoon, and the parameter-identity extension as FR2's candidate spine.

## Next Actions

### MUST
- **What:** register the formation frontier field in the corpus — a formation-side customer block under FR2 (the sub-questions per frontier; the parameter-identity extension stamped prediction-grade; the retention note recording the origin's founding question), FR3 re-framed as the conversion table's first row (rows as candidates), the four registrable absences, the fixed points recorded as observations, and a history entry with relation lines (this is route 1 of `routelister.md`).
  **Who:** the open register `BDA/80_OPEN_REGISTER.md` + `BDA/90_HISTORY.md` (executed by the assistant on the user's route pick).
  **Gate:** condition-bound — the user picks route 1 from the presented route map.
  **Why:** a field that lives only in a finding gets re-derived from scratch next time; registration makes the frontiers durable, branchable state — which is what "branch in each" requires.

### COULD
- **What:** test the contrast-class spine ("formation runs where attention is joint; stalls where attention is on the relation's outcome") against the corpus's own cases and name its refuting observation (route 2).
  **Who:** this inquiry's successor traverse or a direct working session.
  **Gate:** condition-bound — user picks route 2.
  **Why:** the whole map leans on the spine; the test either grades it or breaks it early.
- **What:** pose the rate composition (product / threshold / order; the mere-exposure ordering; the independence advantage) and state the parameter-identity extension's test shape (route 3).
  **Who:** successor inquiry.
  **Gate:** condition-bound — user picks route 3.
  **Why:** the field's cleanest structural bet; turns the spoon into a well-posed question.
- **What:** draft the conversion table as FR3 generalized — candidate rows with per-row evidence owed (route 4).
  **Who:** successor inquiry.
  **Gate:** condition-bound — user picks route 4.
  **Why:** the corpus's first composition-only dynamics structure; makes deepening branchable.
- **What:** sketch the persistence dimension for the attachment bearings (mix × bearing × debt-avoidance; the user's profile as case one) (route 7).
  **Who:** `BDA/31` (the profiling layer) via a successor inquiry.
  **Gate:** condition-bound — user picks route 7.
  **Why:** the user's decay observation becomes a profiling dimension — the product-facing payoff.
- **What:** write the formation worked cases (the military month; the kids' game) into the case library (route 15).
  **Who:** `BDA/70_CASES.md`.
  **Gate:** condition-bound — user picks route 15.
  **Why:** the cases stop being re-argued from memory.
- *(The remaining routes — object lifecycle/succession, hardship + untested bonds, pair-frame gap list, between-occasion channels, availability's ceiling, sealing, specific investment, route-signature, two-sided mechanisms — are mapped with priorities in `routelister.md`; none is gated on the MUST.)*

### DEFERRED
- **What:** the regimes' application run — which parameters the short regime (the pitch) and the long regime (the restaurant) can and cannot move, and the mid-regime (the outreach season) between them (route 14's application half).
  **Gate:** condition-bound — revived when the user opens the sales/outreach application work (their words: "in the future, not now").
  **Why (if revived):** turns "your spoon should be deeper" into "which factors your regime can actually move" — the user's stated future use.

## Reasoning

**Why an expansion, not an answer.** The user's bound ("expand… uncover new frontiers… rather than enforcing premature definitions") set the run's intended disposition: frontiers, with fixed points recorded as observations. The pipeline was run in its generator-weighted mode accordingly, and the critique's no-kill outcome is that mode working as designed — pressure went into *re-wording and grading* claims rather than deleting them.

**What was rejected (the three container shapes).** Three ways of "formalizing formation" were deliberately generated and each failed:
- *Write the dynamics account into FR2 now* — breaks the corpus's static bound; exactly the move the decay-modulator kill exists to prevent (a dynamics quantity admitted as an element).
- *Add a formation column to the type table* — a canon edit the user has forbidden in general (frozen/finalized layers) and a re-tabulation the previous charm inquiry already declined.
- *Dissolve formation into "persistence read backwards"* — fails structurally: the rise side runs on evidence delivery, the keep side on maintenance-sources × removal-events; different logic, different machinery.

**What was eliminated inside the analysis.** "Intensity" as a new element (every candidate content is already a committed quantity; only the composition is open) · a formation modulator or rate term · the Fear variable as the exam-bond's engine (the dyads separate) · a "gratitude trait" as a new element (the bearing + the mix + debt-avoidance cover it from canon) · "spending time" as a variable (re-located to occasions × frequency) · memory/consolidation apparatus (only committed channels admitted: the record, third-party retelling; pure rehearsal named as outside).

**The four refinements that changed content under prosecution:**
- The object-route premise survived a vacuity attack *at a price* that became the field's spine: if everything counts as an object the claim says nothing — so its real content is the contrast class (joint attention vs relation-outcome attention), stated falsifiably.
- Between-occasion "consolidation" was restated through committed channels only, with the channel-less remainder explicitly outside.
- The conversion table survived the "forbidden taxonomy" objection by demotion to candidate rows, each owing evidence.
- The pair-frame's formation survived the "already covered" objection by becoming a gap list against existing machinery instead of a new mechanism.

**What survived with graded caveats.** The parameter-identity extension and the independence advantage both carry prediction-grade labels (their siblings' honest status); debt-avoidance is held at MEDIUM with a named profiling observable; hardship-as-gate-test cites the backing finding as its mechanism's source; sealing cites the verdict-timing doctrine; relationship-specific investment carries its vocabulary-only precedent label (economics' hold-up, used as precedent, never apparatus).

**Why the assembly ranked first.** The individual frontiers compose into one map (object · rate · stakes · receiver/pair · container) whose spine is the contrast class — presented with three unblockers (the spine's test, the rate composition, the conversion table) so the field can be entered anywhere without dilution across ~18 co-equal items.

## Open Questions

### Monitoring
- **The parameter-identity extension** — one triple (contact-frequency · context-breadth · perturbation-rate) governing detection, settling, *and* formation. Observable as formation cases accumulate in the case library; blocked on data like its two stamped siblings.
- **The formation ceiling** — continuous low-specificity contact maintains but forms little. Observable against the corpus's parasocial and long-distance cases as they accumulate.

### Research Frontiers
- The full field: **sixteen routes** in `inquiries/2026-08-31_17-39__attachment_formation/routelister.md` — registration (core); the contrast-class test, the rate composition + identity extension, the conversion table (high-priority); object lifecycle/succession, hardship + untested bonds, decay profiles, pair-frame + symmetric costs, availability's two faces, the regimes' movable parameters, worked cases (supporting); between-occasion channels, sealing, specific investment, route-signature, two-sided mechanisms (peripheral).
- The **retention question** itself — the origin's "how do you make someone keep talking to you" — recorded as the field's oldest motivation, not yet its own inquiry.

### Refinement Triggers
- **The spine re-opens** if a bond is observed forming by sustained relation-outcome attention with no shared object anywhere (the named refuter).
- **The conversion table upgrades** from candidates the moment any row gets its own evidence — at which point FR3's framing (one row of a table) becomes load-bearing and should be re-checked.
- **The dyad-scale object claim** re-opens if dyad formation is found that co-attention cannot cover — it is currently an extension of a group-scale commitment, flagged as such.

## Source Input

<details>
<summary>Raw user input for this finding</summary>

```text
Also, there's really another point, which is really important. Attachment is something that's um, that forms and deepens over time. And the conditions also matter too. For example, uh, imagine a student who was in high school and 4 years he had one friend, and they get along like well, yeah. Um, and they got to them well, but It is, like, not so strong, but take it a long while. Normal way. And after 4 years, they will be still attached to each other. They have this attachment, and they will remember high school after 10 years, even if they are not communicating, they have attachments. And but, for example, uh, I remember, for example, I was in military, and we had one month training, and I had, I, I was staying with some people in the same room, and I wanted to, with them so much because you kind of need each other's things, like out of need, you won't really quickly. Yeah? And I still remember these guys, if I see them, I will be, uh, like, they will buy me food, I will buy them food. I want, like, for many years, after military, I talk with these guys. So, for me, it is something really interesting, because I spent not so long time with them, but I wanted with them. I did some things that I would normally not do for other people, for them, for example. And I met with them only one month, and I didn't see them later on, you understand? Like, it was just a short period of time. So attachment is something that says, um, like these dimensions of, um, building dimension, okay? Let's say. Or building variable, uh, not building like, um, like kind of generating, let's say, generating variable, and the 2nd variable is not, let's say, filling, I guess. I don't know, like maybe generating was okay. Second one is, um, like spoon, uh, spoon, uh, spoon, depthness or something like, but I try to say is that, um, In certain conditions, the spoon is too big, and even though the time is not so much, not so long, it can feel this attachment. It can generate so much attachment, yeah? But in some other situations, long-term exposure also creates this attachment. Um, but the spoon can be really small, but you're exposed for a long time. Imagine you go to high middle school and high school, it's same friend. And you will kind of form some kind of bomb with them and you will be, you will have some kind of attachment. Um, and It is, it is, I think, it is something important we should inspect, and we should formalize it as well. And attachment is, okay, we are trying to form an attachment. Um, but what kind of conditions we have to form an attachment? Um, And it is not as simple as just spending exposure time. It's more than that because if you keep yourself available, Um, like right now, in modern age, you have cell phones, we have internet, yeah. So you are not even talking, but you can still be kind of available. Other person can still feel this availability. And they will, and it is something interesting. And for example, in the future, not now, but for me, for instance, it's interesting when as a salesperson, you're trying to sell a product. You also use belief-driven attachment there. And you have to create some kind of attachment. Um, to you 1st and then to the outcomes you're offering. Yeah? And it's a short term exposure. So you should act differently, for sure, then if you have some, uh, like restaurant and you're trying to convince people in this restaurant to do something and you have many years, it is a different situation. Uh, like things that you prioritize is different and your, your spoon should be deeper and bigger, yeah? And like we should be able to formalize it. So I think it's extremely important. We dive deep into that and we try to understand what dimensions, what attributes, not damages, but what attributes, I guess, attachment generation has, um, like generating, Uh, you should actually, you generate something by, um, You know, like it's not just spending time. It is spending time is one form, but usually it's via some common activities, common things, I guess. And interesting, really interesting point is, um, usually when kids they start school, uh, they don't make immediate friends. Then they go for breaks. They want to play games. They want to play this game so much, they can ask each other. Let's just play this. They just, you know, share some small things, and at some point they start playing. Um, and it just happens so natural. It's not like, okay, we have to 1st attach to a attachment and then, um, Then we can play games. It just resolves, resolves around, um, results around the game, and they gather there, and due to the game, they are they, after a while, they end up attached to each other. Next break, also they will say, okay, let's go play again. And it's like now they are forming attachments, not directly, but in an indirect way. And you should, this is usually correct with people. We don't form attachment in direct to the person, personality directly, uh, unless it's the charm, maybe it's different with that, but usually it revolves around the outcomes, uh, expectations. hope, yeah? Actually, I'm just describing it back. Yeah. I understand. And another, like, thing is also, I want to also talk about fear a bit. Uh, fear is also really good way of forming attachment in terms of having a common fear. For example, students who are preparing for an exam, they suddenly bond so much more, uh, because they have common enemy, and they have a like teacher, and they're just kind of trying to bond, uh, trying to beat this enemy, this exams, and they bond so fast because they want to share the notes. They want to feel sport, they ask each other questions. They need help. They are when people are in, uh, in, in a situation where they are not really, um, and they're in doubts, they're not so comfortable. They have this fear, they have this voice. People can bond so much more, yeah? Like this is just, this is one example of it. Uh, But it doesn't mean for good attachments, people can, people should, like, envy fear. There are some other kind of people, I guess. They also can bond when they're feeling fear, and they can bond with other people who are feeling fear, but there are quite a lot of people there. They are, um, They would like to bond via positivity. This is like what matters to them. They don't really care, like they don't really care about the people who help them when they were in need. Uh, once it's finished, this attachment doesn't, uh, like doesn't stay long for them. Attachment was generated, but I guess there is this aspect. It's like another thing we just found, another maybe attribute of this attachment generation, how much it decays, yeah? And decaying off in terms of positive, like positive-based attachment, decay, and negative-based attachment decay, every person has it differently. Some people, for example, like me, I choose to form bones with people when they are also in worries and fears. And I remember them, I will think about them. And if I do some really good activity with some people, it was nice, but it's not so much important as the bad times, yeah? But for some people, it's the opposite. They can bond with some other people during some bad times, but when the bedtime passes, they don't really care about it anymore. The case is too big in that negative attachment generation thing. And they will just go and then find people who are giving them this positive attachment like hope, charm, and they don't really care about, um, they don't really, like they want to have fun, they want to party, yeah? But at the same time, I was the one who helped them during their bedtime, but they don't care. Not so much because the cave of negative attachment was too negative attachment generation was too much for them, too big in them. So they don't really care, like they don't, this attachment dissolves the case so fast. Um, they are attached to these other people who are, um, like partying, just finding them, some, uh, you know, just finding them money, finding them good resources. Um, and I think this is also an interesting thing.

lets also dive deep into this one, and try to expand our understanding and uncovering new frontiers to dive deep , rather than enforcing premature definitions, we are not in hurry and we can afford to explore these meaning and branch in each, lets focus on interesting ideas and what to explore more
```

</details>
