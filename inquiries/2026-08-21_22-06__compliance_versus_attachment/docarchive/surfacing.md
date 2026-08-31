# Surfacing — compliance_versus_attachment

## User Input

```text
/Users/ns/Desktop/projects/profilingOps/inquiries/2026-08-21_22-06__compliance_versus_attachment/_branch.md
```

---

## Mode + Entry Point

- **Territory-type mode:** `artifact` — the territory holds concrete pre-existing items (the APT corpus: inquiry findings + archived discipline outputs + the PRAGMA theory-spec and implementation files).
- **Entry point:** `signal-first` — a specific purpose is given by `_branch.md`'s Goal.
- **Territory specification:** `abstract-bounded` — the conceptual bounds are given (the engagement-state layer, the Coerced TYPE, the formula's output semantics as they bear on what compliance and attachment *are*), while the file-set carrying them is not enumerated in the input. Per §3.2 the Boundary-discovery sub-phase does **not** fire for `abstract-bounded`; region enumeration was performed inside Scope-determination.
- **Prior-artifact:** none (first Surfacing invocation for this inquiry).
- **Prior-workspace:** none supplied by the runner.
- **Refined-sub-purpose:** none.

---

## Traversal Trace

Per-entry: region · item identifiers · per-item relevance verdict · per-item confidence · recency annotation · step note.
Recency annotation shape: `{filesystem, <ISO8601 UTC>}` or `{none, null}`. **Signal only — never used to filter or weight relevance.**

### 1 — Region `R0 / territory-enumeration`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `profilingOps/` root listing (3 top-level dirs; `inquiries/` with 15 sibling folders + `a.md`) | side | HIGH | `{none, null}` |
| per-inquiry file-manifest sweep (which inquiries carry `finding.md` / `docarchive/` / `routelister.md`) | side | HIGH | `{none, null}` |
| `complian*` density map across the corpus (56 files ranked by hit-count) | core | HIGH | `{none, null}` |

*Step note:* scope-determination pass; the density map is itself a core item because it located every region below and, at entry 15, produced a homonym-rejection.

### 2 — Region `R1 / coherence_unpredictability_paradox — the engagement-state layer's origin`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `finding.md` — the three-state engagement layer statement | core | HIGH | `{filesystem, 2026-08-21T15:31:55Z}` |
| `finding.md` — the promoted 5-row *Persistence under change* table + its provisional flag | core | HIGH | `{filesystem, 2026-08-21T15:31:55Z}` |
| `finding.md` — the *nameable but not usable* admission (no determination mechanism) | core | HIGH | `{filesystem, 2026-08-21T15:31:55Z}` |
| `finding.md` — killed candidate: compliance ≡ the Supplication pole | core | HIGH | `{filesystem, 2026-08-21T15:31:55Z}` |
| `finding.md` — the mentor counterexample against the Charm-dominant row | sub | HIGH | `{filesystem, 2026-08-21T15:31:55Z}` |
| `finding.md` — killed candidate: attachment ≡ a sufficiently invested model | sub | MEDIUM | `{filesystem, 2026-08-21T15:31:55Z}` |
| `finding.md` — model-completeness as a cross-variable epistemic modifier | side | HIGH | `{filesystem, 2026-08-21T15:31:55Z}` |

*Step note:* highest signal density in the corpus for this purpose; the layer under test originates here.

### 3 — Region `R1b / coherence_unpredictability_paradox — archived innovation`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `docarchive/innovation.md` — candidate **I-b**: one variable plus derivatives (compliance = attachment contingent on an external term) | core | HIGH | `{filesystem, 2026-08-21T14:04:41Z}` |
| `docarchive/innovation.md` — candidate **K10** verdict REFINED + its contingency-vs-derivative objection | core | HIGH | `{filesystem, 2026-08-21T14:04:41Z}` |
| `docarchive/innovation.md` — candidate **I-c**: compliance as belief held under duress | core | MEDIUM | `{filesystem, 2026-08-21T14:04:41Z}` |
| `docarchive/innovation.md` — candidate **K7** KILL verdict + its disambiguation-note seed | core | HIGH | `{filesystem, 2026-08-21T14:04:41Z}` |
| `docarchive/innovation.md` — candidate **CM-a**: minimal-vocabulary version (Coerced TYPE ≡ compliance) | sub | HIGH | `{filesystem, 2026-08-21T14:04:41Z}` |
| `docarchive/innovation.md` — candidate **L-c**: attention-allocation patterns as the dependent variable | sub | MEDIUM | `{filesystem, 2026-08-21T14:04:41Z}` |
| `docarchive/innovation.md` — candidate **A-c**: the layer is present in partial form; promote don't invent | sub | HIGH | `{filesystem, 2026-08-21T14:04:41Z}` |

*Step note:* pre-adjudicated candidate space — surfaced so downstream generation does not re-run ground already walked.

### 4 — Region `R1c / coherence_unpredictability_paradox — route index`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `_route.md` — identity *the engagement-state layer* (`not drilled`; three partial forms) | core | HIGH | `{filesystem, 2026-08-21T14:19:00Z}` |
| `_route.md` — identity *the engagement-state discriminating tests* (`not drilled`; determination mechanism absent) | core | HIGH | `{filesystem, 2026-08-21T14:19:00Z}` |
| `_route.md` — identity *the admission-gate apparatus* | sub | HIGH | `{filesystem, 2026-08-21T14:19:00Z}` |
| `_route.md` — identity *APT's static-vs-dynamic boundary* | sub | MEDIUM | `{filesystem, 2026-08-21T14:19:00Z}` |
| `_route.md` — identity *load-bearing-quote integrity* | sub | MEDIUM | `{filesystem, 2026-08-21T14:19:00Z}` |

### 5 — Region `R2 / attachment_variable_interactions (iteration-3.2.1) — the TYPE source`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `finding.md` — Addition 4 header: *Attachment has two output dimensions (MAGNITUDE and TYPE)* | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — the TYPE table's **Fear-dominant → Coerced** row and its parenthetical | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — *TYPE reads directly from the variable-weight distribution; no separate mechanism is needed* | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — §*Why TYPE is not reducible to MAGNITUDE*, whose wording names the Fear-dominant case an attachment | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — the taxonomy's *provisional and illustrative* flag + pending-empirical-work note | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — Signal Specificity as magnitude factor + the generic-signal definition | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — the 5th-variable admission test (generate-alone / distinct-character / orthogonal) | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — open frontier: TYPE-taxonomy empirical derivation; TYPE evolution over time | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `docarchive/critique.md` — 15 `complian*` hits, all the dimension name *Scope Compliance* | umbrella | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |

*Step note:* two passages of one file apply the word *attachment* to the same taxonomy row in opposite ways; both are surfaced as items, their relation left to downstream. The `docarchive/critique.md` hits are a homonym — retained at umbrella rather than dropped, per §4.4.

### 6 — Region `R3 / leadership_and_inexhaustibility`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `finding.md` — *followership is attachment plus pursuit that cannot extinguish* (two states composing) | core | HIGH | `{filesystem, 2026-08-21T16:14:36Z}` |
| `finding.md` — *followership is not compliance* + its stated ground | core | HIGH | `{filesystem, 2026-08-21T16:14:36Z}` |
| `finding.md` — conferred position produces compliance, from `f`-side content *whether threat or reward* | core | HIGH | `{filesystem, 2026-08-21T16:14:36Z}` |
| `finding.md` — inherited-commitment re-test #2 (the layer's first out-of-domain application; held) | core | HIGH | `{filesystem, 2026-08-21T16:14:36Z}` |
| `finding.md` — the mid-analysis correction that moved conferred position from out-of-scope to inside | sub | HIGH | `{filesystem, 2026-08-21T16:14:36Z}` |
| `finding.md` — the mimicry / costly-signal decay arc | side | MEDIUM | `{filesystem, 2026-08-21T16:14:36Z}` |

### 7 — Region `R4 / anger_routing_three_way_reconciliation`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `finding.md` — §8: **Fear is defined two incompatible ways across the corpus** (threat-of-harm vs cost-of-loss), declared not settled | core | HIGH | `{filesystem, 2026-08-21T15:25:59Z}` |
| `finding.md` — SHOULD item: name compliance behaviourally **inhibitory** while attachment and pursuit are approach-oriented; *the layer currently mixes motivational directions* | core | HIGH | `{filesystem, 2026-08-21T15:25:59Z}` |
| `finding.md` — SHOULD item: add an explicit **null case** to the engagement-state layer | core | HIGH | `{filesystem, 2026-08-21T15:25:59Z}` |
| `finding.md` — §6: the same figure generating deference-from-Fear and admiration-from-Charm at once | core | HIGH | `{filesystem, 2026-08-21T15:25:59Z}` |
| `finding.md` — §7: the corpus has no routing rules; what is missing is an index | sub | HIGH | `{filesystem, 2026-08-21T15:25:59Z}` |
| `finding.md` — the components-are-co-determined-coordinates result | sub | HIGH | `{filesystem, 2026-08-21T15:25:59Z}` |
| `docarchive/surfacing.md` — item A4: *respect* is unspecified as attachment / component / consequence | core | HIGH | `{filesystem, 2026-08-21T15:25:59Z}` |

*Step note:* A4 is the same structural question as this inquiry's, asked of a different term and logged unanswered.

### 8 — Region `R5 / belief_attributes_and_the_aggression_pattern`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `finding.md` — **Blocked** open question: whether *compliance* in the shipped dating case carries a Fear component; two claims inherit the answer | core | HIGH | `{filesystem, 2026-08-21T18:57:05Z}` |
| `finding.md` — MUST item pairing that question with the aggression-contribution claim | core | HIGH | `{filesystem, 2026-08-21T18:57:05Z}` |
| `finding.md` — the caution that *compliance* is engagement-state vocabulary the corpus ties to fear-driven engagement | core | HIGH | `{filesystem, 2026-08-21T18:57:05Z}` |
| `finding.md` — the no-outcome-term architecture | sub | MEDIUM | `{filesystem, 2026-08-21T18:57:05Z}` |
| `finding.md` — gender as expression-register, not mechanism | side | HIGH | `{filesystem, 2026-08-21T18:57:05Z}` |

### 9 — Region `R6 / apt_as_belief_theory (iteration-3.4)`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `finding.md` — **attachment is a behavioural disposition: the receiver's tendency to engage with, persist toward, return to the sender** | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — the *attachment IS belief* vs *attachment is GENERATED BY beliefs* disambiguation | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — Fear's property-belief statement (*this person can harm me / poses threat*) | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — each property-belief is an independent attachment generator, *being a threat to navigate* among them | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — property-vs-stance as the ground of additive `f` vs multiplicative `g` | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `docarchive/exploration.md` — the belief-inventory table row placing attachment MAGNITUDE/TYPE as output, not belief | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |

*Step note:* supplies the definition against which any candidate criterion must be tested, and the one place Fear's attachment-generating status is stated in belief form.

### 10 — Region `R7 / theory spec — PRAGMA core`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `new_apt_layer.md` — Fear's spec definition: *consequences of losing you. Power dynamics, secrets, dependency* | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| `new_apt_layer.md` — *without at least one of these, no connection forms* | sub | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| `new_apt_layer.md` — per-variable modulation lines incl. *Fear … reads as bluster → fails to consolidate into respect* | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| `new_apt_layer.md` — the Non-Extractive Attention genus + outcome-independence + the approval/validation/**response** wording | sub | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| `apt_inference.md` — **Fear's detection signal-set** (four named behavioural signals) | core | HIGH | `{filesystem, 2026-03-26T09:52:08Z}` |
| `apt_inference.md` — Fear's operational gloss *how much does this participant fear losing the other?* + the 5-level scale | core | HIGH | `{filesystem, 2026-03-26T09:52:08Z}` |
| `apt_layer_proof_scenarios.md` — the 15-scenario validation set + its Summary coverage claim | core | HIGH | `{filesystem, 2026-04-22T14:52:40Z}` |
| `apt_layer_proof_scenarios.md` — Scenario 3's *eventual escape* temporal arc | side | MEDIUM | `{filesystem, 2026-04-22T14:52:40Z}` |
| `apt_layer_proof_scenarios.md` — Scenario 8 (BATNA) as the outcome-independence exemplar | side | MEDIUM | `{filesystem, 2026-04-22T14:52:40Z}` |

*Step note:* Fear's detection signals and the Coerced row point at the same observable behaviour from opposite sides of the formula — surfaced as two items, relation left to downstream.

### 11 — Region `R8 / self_focus_generalization (iteration-3)`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `finding.md` — Claim D's wording: the self-focused non-chasing man generates *attraction and compliance*, with no threat present | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `_branch.md` — the same wording at branch-time (two independent occurrences) | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — *any species of non-extractive attention produces g(high); Supplication produces g(low)* | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — the adjacent-mechanism list (intermittent reinforcement, trauma bonding, arbitrary power) | sub | MEDIUM | `{filesystem, 2026-08-21T11:57:25Z}` |

*Step note:* the corpus's only instance of *compliance* used in a threat-free case; directly the object of R5's Blocked question.

### 12 — Region `R9 / hope_sub_flavors (iteration-3.4.1)`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `finding.md` — the sub-taxonomy framework (structural unifier + discriminating axis + orthogonality validation + basis decomposition) and its stated generalizability | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — the **H_pleasure** kill: *a cross-variable affective specification, not a sub-flavor* | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — the **H_s** kill (collapses into Charm + a specialised H_e) | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — basis-not-partition: instances are linear combinations across sub-flavors | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — nesting is real and does not collapse the sub-flavors | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — Hope's structural unifier and its contrast line *Fear is forward but negative-valenced* | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — the reserved `3.4.3` Fear-sub-taxonomy slot | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |

*Step note:* the corpus's own machinery for adjudicating a *form-of* claim — built for variables, and the question here is about an output.

### 13 — Region `R10 / apt_modulator_landscape (iteration-3.2)`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `finding.md` — §*Why Coherence has aspects (not species)*: **species require distinct mechanisms**; same-mechanism-different-content is the structural marker of aspects | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — §*Why "Reliability" is a theme, not a unified modulator*: **distinct failure signatures require distinct members** | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — the 8 modulator entry criteria, applied twice | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — the Vitality exclusion as criterion-discipline precedent | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — the three failure signatures (devaluation / Model-Collapse / Contagion-Drain) | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — orthogonality is theoretical, not empirical | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |

*Step note:* the corpus already distinguishes **species / aspects / theme-sharing siblings** by explicit criteria — the closest existing apparatus to the question's *form of*.

### 14 — Region `R11 / apt_context_layer (iteration-3.3)`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `finding.md` — the **receiver-state pre-condition**: a real factor formally placed *outside* formula scope | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — killed **P3-C** (g₄ Mode): real phenomenon, wrong architectural location; belongs as a coupling rule inside an existing component | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — killed **P2-C** (per-receiver θ) on the same pre-condition boundary | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — `f` as cumulative belief state incl. pre-interaction loadings | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |

*Step note:* two shipped placement-precedents for a real phenomenon that is neither a new member nor nothing.

### 15 — Region `R12 / hope_charm_substrate (iteration-3.4.2)`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `finding.md` — the shipped criterion: pure Hope with no Charm may produce **engagement-with-offer rather than attachment-to-person**, because **attachment requires the sender as a person** | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `docarchive/exploration.md` — the same distinction in its original form: *engagement (motivation to interact)* vs *attachment (behavioural disposition toward this specific person)* | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `docarchive/exploration.md` — the historical-figure test: an *is-this-a-form-of-attachment* question settled by matching behaviour against attachment's definition | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — killed **R-γ**: approach/avoidance is a binary motivation distinction, not a finer substrate — *useful as a one-axis overlay* | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — **cross-variable structural analysis as a precedented inquiry type** (the shape of *X and Y feel close — are they really separate?*) | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — Pattern A (valence × temporality); Fear as *(mostly future) negative value* | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — unilateral-vs-dyadic: the four-variable architecture already carries an internal type-distinction | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — killed **R-α** and **R-β** substrate candidates | sub | MEDIUM | `{filesystem, 2026-08-21T11:57:25Z}` |

*Step note:* the highest-yield region after R1/R2 — it holds both a shipped attachment/non-attachment criterion and a shipped method for questions of this exact shape.

### 16 — Region `R13 / apt_missing_dimension (iteration-1)`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `finding.md` — Domain 1 as the answer to *why would I stay?* | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — the not-a-4th-variable argument (different question class; multiplicative vs additive) | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — *Fear without Self-Positioning … fails to consolidate into respect* (the rule's first appearance) | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |

### 17 — Region `R14 / self_focus_dynamics (iteration-3.1)`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `finding.md` — outcome-independence as SP's central property | side | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — species oscillation dynamics | side | MEDIUM | `{filesystem, 2026-08-21T11:57:25Z}` |
| `finding.md` — the character-scope bound | umbrella | LOW | `{filesystem, 2026-08-21T11:57:25Z}` |

*Step note:* region scanned; near-synonym hits resolve to unrelated senses. Low yield, retained at side/umbrella rather than dropped.

### 18 — Region `R15 / implementation layer (PRAGMA models + service docs)`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `pragma/files/models.py` — `AttachmentDomain1` (charm/hope/fear only) + `AttachmentReading.level` | core | HIGH | `{filesystem, 2026-03-26T15:04:30Z}` |
| `pragma/files/models.py` — absence of any TYPE / MAGNITUDE / engagement-state / Resonance / modulator field | core | HIGH | `{filesystem, 2026-03-26T15:04:30Z}` |
| `pragma/files/models.py`, `step_by_step_…md`, `cpde7/docs/elaboration.md` — all `complian*` hits resolve to *schema compliance* / *audit compliance* | umbrella | HIGH | `{none, null}` |

*Step note:* HIGH-confidence homonym rejection for the third item's sense; the items are retained at umbrella per §4.4 rather than filtered, and the region is otherwise core because of what it lacks.

### 19 — Region `R16 / root conversation transcript`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `Claude-Attachment domain!…md` — the pre-theory gloss of the attachment domain (*how do you make someone keep talking to you*; *without this domain there is no connection*) | side | HIGH | `{filesystem, 2026-08-21T11:29:58Z}` |
| `Claude-Attachment domain!…md` — 4032 lines on PRAGMA dimension design; no compliance / coerced / engagement-state / attachment-TYPE content | umbrella | HIGH | `{filesystem, 2026-08-21T11:29:58Z}` |

---

## State Summary

### Territory-specification echo

The APT corpus at `/Users/ns/Desktop/projects/profilingOps` — 15 prior inquiry folders (findings + `docarchive/` discipline outputs + route indices), the PRAGMA theory-spec core, the PRAGMA implementation models, and the root conversation transcript — bounded conceptually to the engagement-state layer, the Coerced TYPE, and the formula's output semantics as they bear on what compliance and attachment *are*.

### Purpose-specification echo

A conceptual adjudication: the criterion distinguishing compliance from attachment, plus a verdict on the subsumption relation — held open across five readings (state the criterion · adjudicate the subsumption · test the layer's sibling structure · build the *more complex* third option · audit the quoted *was never attachment* claim), and across both senses of *form of* (species-of vs made-of-the-same-stuff).

### Coverage map

| Region | Coverage | Aggregate relevance |
|---|---|---|
| R0 territory-enumeration | confirmed | core |
| R1 coherence_unpredictability_paradox (finding) | confirmed | core |
| R1b …/docarchive/innovation.md | confirmed | core |
| R1c …/_route.md | confirmed | core |
| R2 attachment_variable_interactions | confirmed | core |
| R3 leadership_and_inexhaustibility | confirmed | core |
| R4 anger_routing_three_way_reconciliation | confirmed | core |
| R5 belief_attributes_and_the_aggression_pattern | confirmed | core |
| R6 apt_as_belief_theory | confirmed | core |
| R7 theory spec (PRAGMA core) | confirmed | core |
| R8 self_focus_generalization | confirmed | core |
| R9 hope_sub_flavors | confirmed | core |
| R10 apt_modulator_landscape | confirmed | core |
| R11 apt_context_layer | confirmed | core |
| R12 hope_charm_substrate | confirmed | core |
| R13 apt_missing_dimension | scanned-but-shallow | sub |
| R14 self_focus_dynamics | scanned-but-shallow | side |
| R15 implementation layer | confirmed | core (by absence) |
| R16 root transcript | scanned-but-shallow | side |
| R1/R3/R4/R5 `docarchive/` interiors beyond the entries above | inferred | unknown |
| `apt_self_focus_reframe` (iteration-2) | inferred | unknown |
| `BASEFILES/…/cpde7`, `topicflow`, `asne` subtrees | inferred | unknown |

### Confirmed-absent regions

1. **`apt_layer_proof_scenarios.md` — no Fear-dominant / coerced / threat scenario.** The word *Fear* appears once across 15 scenarios, inside a variable list. Every other TYPE row has at least one scenario; the Coerced row has none. The theory's entire worked-validation set is silent on the state under question.
2. **The implementation layer carries no engagement-state or TYPE apparatus.** `models.py` has charm/hope/fear at five levels and nothing for MAGNITUDE, TYPE, persistence, Resonance, or any modulator. Nothing operational exists to test a compliance/attachment distinction against.
3. **`complian*` in the implementation layer and service docs is a homonym throughout** — *schema compliance*, *audit compliance*, and the critique dimension *Scope Compliance*. No occurrence in the engagement-state sense outside the inquiry corpus.
4. **No membership criteria exist for the engagement-state layer.** No finding and no spec states what makes something an engagement state, nor how to determine which state a case is in. Confirmed against both the layer's originating finding and its route index.
5. **The root transcript contains no engagement-state material.** 4032 lines, all PRAGMA dimension design.

### Concept-names list

| Name | Type | Provenance | Gloss |
|---|---|---|---|
| engagement-state layer | structural-reference | 2 | The three-member layer under test. |
| persistence-under-change | vocabulary | 2 | The discriminator the layer uses. |
| Coerced (TYPE) | vocabulary | 5 | The Fear-dominant row of the 3.2.1 TYPE taxonomy. |
| MAGNITUDE / TYPE | structural-reference | 5 | The two output dimensions; TYPE is *what kind of attachment*. |
| behavioural disposition | vocabulary | 9 | Attachment's definitional category — engage with, persist toward, return to. |
| property-belief / stance-belief | vocabulary | 9 | The additive-vs-multiplicative ground. |
| Fear-as-threat-of-harm | vocabulary | 9 | Iteration-3.4's Fear belief statement. |
| Fear-as-cost-of-loss | vocabulary | 10 | The older spec's Fear definition; declared unreconciled at entry 7. |
| Fear's detection signal-set | structural-reference | 10 | The observable behaviours that evidence Fear. |
| species-require-distinct-mechanisms | coined-term | 13 | The corpus's criterion for a genuine sub-kind. |
| aspects-not-species | coined-term | 13 | Same mechanism, different content areas. |
| theme-not-member | coined-term | 13 | Shared unity but distinct failure signatures → stay distinct. |
| failure-signature | vocabulary | 13 | The individuating mark used across the Suite. |
| sub-taxonomy framework | structural-reference | 12 | Structural unifier + discriminating axis + orthogonality + basis. |
| basis-not-partition | vocabulary | 12 | Instances are combinations, not exclusive members. |
| cross-variable affective specification | coined-term | 12 | The H_pleasure kill-class: looks like a sub-kind, isn't one. |
| engagement-vs-attachment | coined-term | 15 | Motivation to interact vs disposition toward this specific person. |
| attachment-requires-sender-as-person | coined-term | 15 | The shipped attachment/non-attachment criterion. |
| approach/avoidance overlay | vocabulary | 15 | Killed as substrate; retained as a one-axis overlay. |
| cross-variable structural analysis | structural-reference | 15 | The precedented inquiry type for *are X and Y really separate?* |
| contingency-on-an-external-term | coined-term | 3 | K10's objection; a candidate criterion for compliance. |
| compliance-as-belief-under-duress | coined-term | 3 | Candidate I-c. |
| compliance ≠ Supplication | structural-reference | 3 | Killed identification; different parties, different objects. |
| inhibitory-vs-approach-oriented | coined-term | 7 | The layer mixes motivational directions. |
| the null case | vocabulary | 7 | The zero state the layer lacks. |
| conferred-position-produces-compliance | structural-reference | 6 | From `f`-side content, threat **or reward**. |
| states-composing | coined-term | 6 | Followership = attachment + pursuit; the layer is not exclusive. |
| receiver-state pre-condition | structural-reference | 14 | Precedent: a real factor placed outside formula scope. |
| coupling-rule-not-new-member | structural-reference | 14 | Precedent: right phenomenon, wrong architectural location. |
| the eight entry criteria | structural-reference | 13 | Explicit admission gate, enforced twice. |
| provisional-and-illustrative | vocabulary | 5 | The flag the TYPE taxonomy carries. |
| determination-mechanism-absent | structural-reference | 4 | The layer is nameable but not usable. |

### Recency distribution

| Region | newest | oldest | no-mtime | total items |
|---|---|---|---|---|
| R0 | — | — | 3 | 3 |
| R1 | 2026-08-21T15:31:55Z | 2026-08-21T15:31:55Z | 0 | 7 |
| R1b | 2026-08-21T14:04:41Z | 2026-08-21T14:04:41Z | 0 | 7 |
| R1c | 2026-08-21T14:19:00Z | 2026-08-21T14:19:00Z | 0 | 5 |
| R2 | 2026-08-21T11:57:25Z | 2026-08-21T11:57:25Z | 0 | 9 |
| R3 | 2026-08-21T16:14:36Z | 2026-08-21T16:14:36Z | 0 | 6 |
| R4 | 2026-08-21T15:25:59Z | 2026-08-21T15:25:59Z | 0 | 7 |
| R5 | 2026-08-21T18:57:05Z | 2026-08-21T18:57:05Z | 0 | 5 |
| R6 | 2026-08-21T11:57:25Z | 2026-08-21T11:57:25Z | 0 | 6 |
| R7 | 2026-04-22T14:52:40Z | 2026-03-26T09:52:08Z | 0 | 9 |
| R8 | 2026-08-21T11:57:25Z | 2026-08-21T11:57:25Z | 0 | 4 |
| R9 | 2026-08-21T11:57:25Z | 2026-08-21T11:57:25Z | 0 | 7 |
| R10 | 2026-08-21T11:57:25Z | 2026-08-21T11:57:25Z | 0 | 6 |
| R11 | 2026-08-21T11:57:25Z | 2026-08-21T11:57:25Z | 0 | 4 |
| R12 | 2026-08-21T11:57:25Z | 2026-08-21T11:57:25Z | 0 | 8 |
| R13 | 2026-08-21T11:57:25Z | 2026-08-21T11:57:25Z | 0 | 3 |
| R14 | 2026-08-21T11:57:25Z | 2026-08-21T11:57:25Z | 0 | 3 |
| R15 | 2026-03-26T15:04:30Z | 2026-03-26T15:04:30Z | 1 | 3 |
| R16 | 2026-08-21T11:29:58Z | 2026-08-21T11:29:58Z | 0 | 2 |

*Descriptive only.* The oldest items in the territory (R7's `apt_inference.md`, five months old; R15's `models.py`) carry two of the highest-value core tags in the run — Fear's detection signal-set and the implementation's absence. No relevance verdict anywhere was derived from mtime.

### Frontier flags

None for coverage. Three regions are marked `inferred` rather than traversed and are the natural re-invocation targets if downstream needs them:

- **F1** — `docarchive/` interiors of R1/R3/R4/R5 beyond the entries surfaced. Suggested refined-sub-purpose: *"prior adjudications of the engagement-state layer's membership, in sensemaking and critique outputs."* Priority: MEDIUM — R1b already yielded the pre-adjudicated candidate space, so the marginal return is likely lower.
- **F2** — `apt_self_focus_reframe` (iteration-2). Suggested refined-sub-purpose: *"the pro-social reframe's account of what attachment is."* Priority: LOW — its content is quoted downstream in R8.
- **F3** — the non-PRAGMA `BASEFILES` subtrees. Priority: LOW — R15's homonym result makes further implementation-layer yield unlikely.

### Workspace-populated status

`{populated: true, populated-at: 2026-08-21T22:10Z (approx., session-local), extent: "19 traversal entries across 19 regions; 104 items tagged; all 15 inquiry folders reached; theory spec and implementation layer reached; five confirmed-absent regions established"}`

### Re-invocation parameters

None requested. The territory is exhaustively traversed at the current resolution for this purpose.

---

## Frontier — open questions for downstream

Surfacing raises these and does not answer them. Each is a *co-location of items already in the workspace*, not an interpretation of their relation.

1. **The 3.2.1 finding applies the word *attachment* to the Fear-dominant row in one passage and withholds it in another.** Both passages are in the workspace (entry 5). Which reading the quoted *"was never attachment"* inherits is undetermined here.
2. **Fear's detection signals and the engagement-state of compliance name the same observable behaviours** — entry 10's signal-set and entry 2's persistence row are both in the workspace. Whether that co-reference is evidence of identity, of causation, or of a measurement artifact is undetermined here.
3. **Fear has two incompatible corpus definitions** (entries 7 and 10), and the anger-routing finding declared its choice rather than settling it. Any criterion built on Fear inherits this fork.
4. **The corpus already carries three named taxonomic relations with criteria** — species (distinct mechanisms), aspects (same mechanism, different content), theme (shared unity, distinct signatures) — built for modulators and variables (entries 12, 13). Whether they extend to an *output* is undetermined here.
5. **A shipped attachment/non-attachment criterion exists** — *attachment requires the sender as a person* (entry 15) — stated for a different case. Its applicability here is undetermined.
6. **The layer's members compose in one shipped case** (followership = attachment + pursuit, entry 6) and one member absorbed a case from outside the taxonomy (conferred position, from threat **or reward**). Whether the layer is a partition is undetermined here.
7. **One corpus instance uses *compliance* with no threat present** (entry 11) and is the object of a Blocked question logged one inquiry ago (entry 8).
8. **The Coerced row has no proof scenario and no implementation** (absent-regions 1 and 2). Nothing empirical constrains the answer.
9. **The layer has no membership criteria at all** (absent-region 4) — so the sibling-vs-subtype question has no existing test to be decided by.
10. **The same structural question was logged unanswered for *respect*** (entry 7, item A4): attachment, component of it, consequence of it, or a different thing.
11. **The question's shape is a precedented inquiry type** (entry 15) — run before on Hope-vs-Charm, at the variable level. Whether the precedent transfers to the output level is undetermined.

---

## Telemetry

- **Mode:** `artifact` · **Entry point:** `signal-first`
- **Cycles run:** 19 traversal entries across 19 regions
- **Items enumerated:** 104
- **Items by relevance level:** core 55 · sub 33 · side 10 · umbrella 6
- **Sub-phase fired:** no (territory `abstract-bounded` per §3.2) · boundary-discovery output: n/a
- **Convergence:** met — territory exhaustively traversed at current resolution; no item filtered at uncertain-relevance level; rejections only at HIGH confidence (the three homonym item-sets, retained at umbrella rather than dropped)
- **Workspace-overload trigger:** not fired
- **`items_with_mtime`:** 100 · **`items_without_mtime`:** 4
- **Failure modes checked:** LAYER 1 — Missed-relevance · Surfaced-irrelevance · Over-coverage · Territory-mis-binding · Workspace overload · Artifact under-specification · Workspace-artifact desync · Recency-Equates-Idleness · Recency-Bias-Filter. LAYER 2 — Interpretive-overstep · Purpose-loss · Self-coupling-to-downstream. **None observed.**
  - *Recency-Bias-Filter specifically checked:* the two oldest items in the territory carry core/HIGH tags; no item was demoted or omitted on mtime.
  - *Interpretive-overstep specifically checked:* the Frontier states co-locations and leaves every relation undetermined; no cross-item relational claim is asserted in the Trace or Summary.

### Self-assessment verdict

**PROCEED**

All convergence criteria met; no LAYER 1 or LAYER 2 flags raised. The three `inferred` regions are recorded as low-priority frontier flags rather than as coverage gaps — each has its content reached through a downstream quotation already in the workspace. Output is ready for Warm.
