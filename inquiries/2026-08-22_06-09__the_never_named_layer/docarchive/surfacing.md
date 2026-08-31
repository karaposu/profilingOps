# Surfacing — the_never_named_layer

## User Input

```text
/Users/ns/Desktop/projects/profilingOps/inquiries/2026-08-22_06-09__the_never_named_layer/_branch.md
```

---

## Mode + Entry Point

- **Territory-type mode:** `artifact` — the APT corpus: inquiry findings, archived discipline outputs, and the two candidate theory-spec files.
- **Entry point:** `signal-first`.
- **Territory specification:** `abstract-bounded` — the bounds are conceptual (the engagement-state layer, the persistence column and its five rows, the three named states, and what the corpus means by a *layer*). Per §3.2 the Boundary-discovery sub-phase does **not** fire; region enumeration ran inside Scope-determination.
- **Prior-artifact / prior-workspace / refined-sub-purpose:** none for this inquiry. Two prior surfacing artifacts exist for neighbouring inquiries under different purposes; neither was used as an exclusion filter (see Coverage).

---

## Traversal Trace

Per-entry: region · item identifiers · relevance verdict · confidence · recency annotation · step note.
Recency shape: `{filesystem, <ISO8601 UTC>}` or `{none, null}`. **Signal only — never used to filter or weight relevance.**

### 1 — Region `R0 / the "layer" vocabulary sweep`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| corpus-wide frequency map of every `<X> layer` construction (30 distinct forms) | core | HIGH | `{none, null}` |
| the count distribution — *engagement-state layer* 174, *interpretation layer* 120, *signal layer* 68, *output layer* 25, *meaning layer* 20 | core | HIGH | `{none, null}` |
| a second sweep over element-category words (modulator 71 · variable 65 · **layer 37** · species 33 · signature 16 · column 13 · dimension 8 · view 3) | core | HIGH | `{none, null}` |

*Step note:* scope-determination. *Layer* is the third most-used element-category word in the findings corpus and the only one with no definition anywhere.

### 2 — Region `R1 / the theory spec's own senses of "layer"`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| *"APT is an **interpretive layer** that sits on top of PRAGMA measurements"* — the **stack-position** sense | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| *"people can be profiled across three **structural layers**"* — Domain 1, Self-Positioning, Domain 2 — the **parallel-component** sense | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| *"Self-Positioning has two inseparable **layers**"* — internal and displayed — the **aspect-of-one-component** sense | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| *"How attachment is transmitted. Three **layers**"* — Content, Style, Expressed Frame — the **sub-component** sense | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| section headings *The Displayed Self-Positioning Layer* and *Prescriptive Guidance Layer* — the **document-section** sense | sub | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| **no definition of *layer* anywhere in either spec file** | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |

*Step note:* five distinct structural senses in one document, none of them stated as a sense. Surfaced as six items; their relation is left to downstream.

### 3 — Region `R2 / the architecture diagram — the pipeline sense`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| the four-stage stack: Raw conversation → **PRAGMA Signal Layer** → Dynamics Profile → **Interpretation Layer** → three outputs | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| the two in-diagram glosses — *"Measurement layer — empirical, no assumptions"* and *"Description layer — what's happening"* | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| the property these share: each stage **consumes the one below and produces what the one above consumes** | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| the three parallel outputs — Behavioral Profiling · APT Inference · APT Profiling | sub | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |

*Step note:* the diagram's layers have a consumption relation the *three structural layers* do not. Both facts surfaced; the tension between them is not adjudicated here.

### 4 — Region `R3 / naming and promotion precedents`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| *"Self-Positioning is what iteration-1 introduced as a **named structural element**"* — the corpus's canonical promotion | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| **Vitality — real, impactful, and explicitly NOT promoted**: *"not promoted to Suite membership. Different architectural category."* | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| the **two-level naming** convention — theoretical *Non-Extractive Attention* + user-facing *Self-Focus*, with the force/push · latency/delay · myocardial-infarction/heart-attack precedent | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| the **label-definition-mismatch kill**: a broadened *Self-Focus* covering own-priorities-that-center-on-others was killed because *"the label-definition mismatch is structurally incoherent"* | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| the **three-level-naming kill**: rejected as *adoption-hostile* and for creating *structural asymmetry* between a primary-with-sub-cases and primaries without | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| the aspects-not-species decision — same failure signature through the same mechanism means **aspects**, not species | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| *"naming the form is cheap and prevents the next multi-component phenomenon presenting as a fresh conflict"* | sub | HIGH | `{filesystem, 2026-08-21T15:25:59Z}` |
| Mission-Focus's demotion, with a documented promotion trigger | sub | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |

*Step note:* the corpus has never stated naming criteria as criteria, but four kills and two promotions turn on them. Surfaced as separate items.

### 5 — Region `R4 / the naming action item, rewritten three times and never executed`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| **v1** *"Add the engagement-state layer as a **named section** — attachment, pursuit, and compliance — built by **promoting** the existing Persistence-under-change column"* | core | HIGH | `{filesystem, 2026-08-21T15:31:55Z}` |
| **v2** *"Add the engagement-state names as a **derived view** of the column — **not as a level of their own** — carrying **all five** of its rows rather than three"* | core | HIGH | `{filesystem, 2026-08-21T20:28:50Z}` |
| **v3** *"Add a **note** to the table stating that its three columns are a generator, a name, and a signature — and that the middle column is a **join key** rather than a taxonomy of its own"* | core | HIGH | `{filesystem, 2026-08-21T21:23:56Z}` |
| the accompanying determination item, also rewritten: *"organised around persistence-under-change"* → *"organised around which variable dominates and whether its ground is externally removable… blocked on coefficient calibration"* | core | HIGH | `{filesystem, 2026-08-21T21:23:56Z}` |
| **none of the three has been executed** — neither spec file contains any of them | core | HIGH | `{none, null}` |

*Step note:* three successive versions, each smaller than the last — *a named section that is a layer* → *names as a derived view, not a level* → *a note about a column*. Recorded as a sequence; its meaning is left to downstream.

### 6 — Region `R5 / the quoted passage's source and its own qualifications`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| the source sentence: *"The claim is made; the column supplies it; **nothing ever names it as a layer** or applies it to a case"* | core | HIGH | `{filesystem, 2026-08-21T15:31:55Z}` |
| the qualification travelling with it: *"Promoting the structure to a named layer must not silently promote the confidence of its rows"* | core | HIGH | `{filesystem, 2026-08-21T15:31:55Z}` |
| the second qualification: *"the layer is currently **nameable but not usable**… That determination mechanism is the single largest piece of unfinished work"* | core | HIGH | `{filesystem, 2026-08-21T15:31:55Z}` |
| the counterexample the source already recorded: *"a mentor admired at a distance for years contradicts the first row"* | core | HIGH | `{filesystem, 2026-08-21T15:31:55Z}` |
| the passage's three-state definitions — persists when satisfied · ends when its gap closes · reverses when the threat lifts | core | HIGH | `{filesystem, 2026-08-21T15:31:55Z}` |
| the five-row column the passage cites, in its only spec-layer home | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |

*Step note:* the passage's own source carried two qualifications and one counterexample that the quotation drops. Both the quotation and the source are in the workspace.

### 7 — Region `R6 / what the theory spec actually contains`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `new_apt_layer.md` carries the formula **`f(charm, hope, fear) × g(non-extractive attention)`** — three variables, one gate | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| **zero** occurrences of *Coherence*, *Emotional Composure*, *Specificity*, *MAGNITUDE*, *TYPE*, or *Persistence under change* in that file | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| its single *Resonance* occurrence is in **Other known absences** — *"shared world-model… as **possible additional modulator**"* | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| its Iteration Development Trail **stops at 3.1** | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| its self-description: *"This spec is readable without the findings — it's the **current-state consolidated theory**"* | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| `apt_layer.md` — a hand-written header stating the four-variable / three-gate belief frame, over a body whose section map still reads *The **Two** Domains* | core | HIGH | `{filesystem, 2026-05-01T16:07:27Z}` |
| that header's own note: *"maybe we need a better name now since it is all related to belief?"* | sub | HIGH | `{filesystem, 2026-05-01T16:07:27Z}` |
| `apt_layer.md` likewise has zero *Emotional Composure*, *Specificity*, *MAGNITUDE*, or *Persistence under change* | core | HIGH | `{filesystem, 2026-05-01T16:07:27Z}` |

*Step note:* the highest-consequence region in the run. The thing the passage says was *"never named as a layer"* is, at the spec level, **not present at all** — and neither is most of what five later iterations built.

### 8 — Region `R7 / the iteration-numbering collision`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| the spec's forward plan: *Iteration-**3.2** empirical validation · Iteration-**3.3** multimodal-extension · Iteration-**3.4** cross-cultural calibration* | core | HIGH | `{filesystem, 2026-04-22T14:50:09Z}` |
| the corpus's actual labels: **3.2** Modulator Suite · **3.2.1** specificity and the output dimensions · **3.3** context layer · **3.4** belief-frame · **3.4.1** Hope sub-flavours · **3.4.2** Hope/Charm substrate | core | HIGH | `{filesystem, 2026-08-21T11:57:25Z}` |
| every number from 3.2 onward denotes two different things | core | HIGH | `{none, null}` |
| a *second*, independently-recorded numbering collision: *"iteration-3.4.1 designated 3.4.x for variable sub-taxonomies, naming 3.4.3 as the Fear slot. The prior inquiry also proposed 3.4.3 for itself"* | sub | HIGH | `{filesystem, 2026-08-21T15:25:59Z}` |

*Step note:* two independent collisions in one numbering scheme. The second was recorded by an inquiry that flagged it *"should be settled deliberately rather than by whichever inquiry ships first."*

### 9 — Region `R8 / what the three later findings did to the passage's claims`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| four defects found in the three-member structure — incommensurable perturbations · two dropped rows · members compose · ending-factors at three architectural levels | core | HIGH | `{filesystem, 2026-08-21T20:28:50Z}` |
| the layer re-described as a **derived view**, its three names retained as a compatibility decision | core | HIGH | `{filesystem, 2026-08-21T20:28:50Z}` |
| the persistence column identified as the **signature level**, and the three engagement-state names as three of its five entries | core | HIGH | `{filesystem, 2026-08-21T21:23:56Z}` |
| the attachment-type table read as a **join of two enumerations**, with the middle column a join key | core | HIGH | `{filesystem, 2026-08-21T21:23:56Z}` |
| the gate asymmetry — every other named set has an admission test; this one has none and needs none | core | HIGH | `{filesystem, 2026-08-21T21:23:56Z}` |
| the two-level answer — four generators, five signatures | sub | HIGH | `{filesystem, 2026-08-21T21:23:56Z}` |

*Step note:* surfaced as material bearing on the quoted passage. Whether the passage is quoted as current or as a historical record is `_branch.md`'s open Reconcile 1 and is not settled here.

---

## State Summary

### Territory-specification echo

The APT corpus at `/Users/ns/Desktop/projects/profilingOps` — fifteen inquiry folders with findings and archived discipline outputs, plus the two candidate theory-spec files in the PRAGMA core — bounded conceptually to the engagement-state layer, the persistence column and its five rows, the three named states, and what the corpus means by a *layer*.

### Purpose-specification echo

A deep treatment of the quoted account, which requires first establishing what relation the treatment bears to it — held open across five readings (develop · test · do the naming · explain the confusion mechanism · pursue what was skipped), with the Layer Commitment declaring **Meaning** as the primary layer: what the thing *is*, and what would make naming it correct rather than convenient.

### Coverage map

| Region | Coverage | Aggregate relevance |
|---|---|---|
| R0 the *layer* vocabulary sweep | confirmed | core |
| R1 the spec's own senses of *layer* | confirmed | core |
| R2 the architecture diagram | confirmed | core |
| R3 naming and promotion precedents | confirmed | core |
| R4 the naming action item's three versions | confirmed | core |
| R5 the passage's source and its qualifications | confirmed | core |
| R6 what the theory spec actually contains | confirmed | core |
| R7 the numbering collision | confirmed | core |
| R8 what the three later findings did | confirmed | core |
| `apt_story_Example.md`, `apt_profiling.md`, `apt_inference.md` and the rest of the PRAGMA core | scanned-but-shallow | sub |
| the `docarchive/` interiors of the three recent inquiries | inferred | unknown |
| `interpretation_layer_prompts.md`, `interpretation_layer_testcases.md` | inferred | unknown |
| the root conversation transcript; `BASEFILES` non-PRAGMA subtrees | inferred | unknown |

*Note on prior artifacts.* Two neighbouring inquiries have surfacing artifacts, produced under different purposes (the compliance/attachment distinction; the enumeration question). Per §3.6 a prior Trace may serve as an exclusion filter *unless the purpose changes the relevance assessment* — and it does, materially. This purpose is about **what a layer is** and **what naming would be**, which makes the spec's own vocabulary and its promotion precedents core where they were previously unvisited. **Neither prior Trace was used as an exclusion filter.**

### Confirmed-absent regions

1. **Neither spec file contains the output dimensions the quoted passage describes.** *MAGNITUDE*, *TYPE* and *Persistence under change* return **zero** occurrences in both `new_apt_layer.md` and `apt_layer.md`. The passage's *"APT computes how strong an attachment is and what kind"* describes something that exists in an inquiry finding and in no spec.
2. **Neither spec file contains four of the corpus's five later structural additions.** Zero occurrences of *Coherence*, *Emotional Composure*, or *Specificity* in either file; *Resonance* appears once, listed as a **possible future modulator** rather than as the fourth variable it became. The canonical formula on file is `f(charm, hope, fear) × g(non-extractive attention)` — three variables, one gate.
3. **No definition of *layer* exists anywhere in the corpus.** It is the third most-used element-category word in the findings and the only one never defined, while five structurally distinct senses of it appear in a single spec document.
4. **None of the three versions of the naming action item has been executed.** The action was written, rewritten, and rewritten again across three findings; no spec file reflects any version.
5. **The corpus states no naming criteria as criteria.** Four kills and two promotions turn on considerations — label-definition match, structural symmetry, adoption cost, architectural-category fit — that are never gathered or stated as a test, unlike the eight modulator-entry criteria, which are.

### Concept-names list

| Name | Type | Provenance | Gloss |
|---|---|---|---|
| stack-position sense of *layer* | coined-term | 2 | A stage that consumes the one below and feeds the one above. |
| parallel-component sense of *layer* | coined-term | 2 | Domain 1, Self-Positioning, Domain 2 — parts of one model, not stages. |
| aspect-of-one-component sense | coined-term | 2 | Self-Positioning's internal and displayed halves. |
| sub-component sense | coined-term | 2 | Domain 2's Content, Style, Expressed Frame. |
| document-section sense | coined-term | 2 | *The Displayed Self-Positioning Layer* as a heading. |
| the consumption relation | coined-term | 3 | What the diagram's layers share and the three structural layers do not. |
| named structural element | vocabulary | 4 | The corpus's own phrase for what a promotion produces. |
| not-promoted-different-category | structural-reference | 4 | The Vitality outcome: real, impactful, and correctly outside. |
| two-level naming | vocabulary | 4 | Theoretical label plus user-facing label, with external precedent. |
| label-definition mismatch | vocabulary | 4 | The ground on which a broadened label was killed. |
| structural asymmetry | vocabulary | 4 | The ground on which a third naming level was killed. |
| the shrinking action item | coined-term | 5 | Named section → derived view → note on a column. |
| nameable but not usable | vocabulary | 6 | The source's own qualification about the determination gap. |
| the mentor counterexample | structural-reference | 6 | A case the source recorded as contradicting the first row. |
| the three-variable formula on file | structural-reference | 7 | What the spec's canonical formula still says. |
| current-state consolidated theory | vocabulary | 7 | The spec's own claim about itself. |
| the numbering collision | coined-term | 8 | Every label from 3.2 onward denotes two different things. |
| the second collision | structural-reference | 8 | 3.4.3 claimed twice; recorded and unsettled. |
| signature level | structural-reference | 9 | What a later finding identified the column as. |
| join key | structural-reference | 9 | What a later finding identified the middle column as. |

### Recency distribution

| Region | newest | oldest | no-mtime | total items |
|---|---|---|---|---|
| R0 | — | — | 3 | 3 |
| R1 | 2026-04-22T14:50:09Z | 2026-04-22T14:50:09Z | 0 | 6 |
| R2 | 2026-04-22T14:50:09Z | 2026-04-22T14:50:09Z | 0 | 4 |
| R3 | 2026-08-21T15:25:59Z | 2026-04-22T14:50:09Z | 0 | 8 |
| R4 | 2026-08-21T21:23:56Z | 2026-08-21T15:31:55Z | 1 | 5 |
| R5 | 2026-08-21T15:31:55Z | 2026-08-21T11:57:25Z | 0 | 6 |
| R6 | 2026-05-01T16:07:27Z | 2026-04-22T14:50:09Z | 0 | 8 |
| R7 | 2026-08-21T11:57:25Z | 2026-04-22T14:50:09Z | 1 | 4 |
| R8 | 2026-08-21T21:23:56Z | 2026-08-21T20:28:50Z | 0 | 6 |

*Descriptive only.* The spec files are the oldest items in the territory and carry the run's most consequential findings — but **those findings are content facts read from the files' text** (zero occurrences of named terms; a formula with three variables; a trail stopping at 3.1), not inferences from their timestamps. The timestamps corroborate; they do not adjudicate. No relevance verdict anywhere was derived from mtime.

### Frontier flags

None for coverage. Four regions are `inferred`:

- **F1** — the `docarchive/` interiors of the three recent inquiries. Suggested refined-sub-purpose: *"prior adjudications of what kind of element the engagement-state names are."* Priority: **MEDIUM** — the findings' conclusions are surfaced, but the reasoning that produced the three action-item rewrites was read only through the findings.
- **F2** — `interpretation_layer_prompts.md` and `interpretation_layer_testcases.md`. Suggested refined-sub-purpose: *"whether the interpretation layer's prompts encode any output-side structure."* Priority: **MEDIUM** — the diagram places an Interpretation Layer between the description layer and APT's outputs, and whether it carries any of the missing structure is unknown.
- **F3** — the remaining PRAGMA core documents. Priority: LOW.
- **F4** — the root transcript and non-PRAGMA subtrees. Priority: LOW.

### Workspace-populated status

`{populated: true, populated-at: 2026-08-22T06:20Z (approx., session-local), extent: "9 traversal entries across 9 regions; 50 items tagged; both candidate spec files read against the corpus's structural additions; five confirmed-absent regions established"}`

### Re-invocation parameters

None requested. The territory is exhaustively traversed at the current resolution for this purpose.

---

## Frontier — open questions for downstream

Co-locations of items already in the workspace. Relations are left undetermined, per the discipline's NOT-list.

1. **The word *layer* carries five structurally distinct senses in one spec document, and is defined in none of them.** Which sense the quoted passage's *"named as a layer"* intends is undetermined here.
2. **The architecture diagram's layers share a consumption relation that the *three structural layers* do not.** Whether both usages can be correct is undetermined.
3. **The quoted passage says the theory *"computes how strong and what kind, then stops."* Neither spec file computes either.** Both facts are in the workspace; their relation is undetermined.
4. **Both spec files are behind the corpus by four structural additions**, and one of them claims in its own text to be *"the current-state consolidated theory."*
5. **The naming action item exists in three versions, each smaller than the last, and none executed.** Whether that sequence is convergence, erosion, or something else is undetermined.
6. **The passage's source carried two qualifications and a counterexample that the quotation drops** — the confidence caveat, the nameable-but-not-usable admission, and the mentor case against the first row.
7. **The corpus has naming criteria in practice and none on paper.** Four kills and two promotions turn on considerations that are never gathered, unlike the eight modulator-entry criteria, which are.
8. **A real thing was once correctly *not* promoted.** Vitality is on record as real, impactful, and belonging to a different architectural category. Whether that outcome is available here is undetermined.
9. **Every iteration label from 3.2 onward denotes two different things**, and a second collision at 3.4.3 was independently recorded and left unsettled.
10. **Three later findings each re-described the thing the passage names**, ending at *signature level* and *join key*. Whether the passage is quoted as current or as a historical record is the framing document's open question and is not settled here.
11. **The passage's *three states* and its *all five rows* sit in one sentence**, and a later finding holds that the three names are three of the five entries. Whether that dissolves the tension or relocates it is undetermined.

---

## Telemetry

- **Mode:** `artifact` · **Entry point:** `signal-first`
- **Cycles run:** 9 traversal entries across 9 regions
- **Items enumerated:** 50
- **Items by relevance level:** core 41 · sub 9 · side 0 · umbrella 0
- **Sub-phase fired:** no (territory `abstract-bounded`)
- **Convergence:** met — territory exhaustively traversed at current resolution; no item filtered at uncertain-relevance level; no HIGH-confidence rejections were required this run
- **Workspace-overload trigger:** not fired
- **`items_with_mtime`:** 45 · **`items_without_mtime`:** 5
- **Failure modes checked:** LAYER 1 — Missed-relevance · Surfaced-irrelevance · Over-coverage · Territory-mis-binding · Workspace overload · Artifact under-specification · Workspace-artifact desync · Recency-Equates-Idleness · Recency-Bias-Filter. LAYER 2 — Interpretive-overstep · Purpose-loss · Self-coupling-to-downstream. **None observed.**
  - *Recency-Bias-Filter specifically checked, and it was the run's live risk:* the two oldest files in the territory produced the two largest findings. Those findings are **content facts read from the files' text** — zero occurrences of named terms, a three-variable formula, a trail ending at 3.1 — not inferences from age. Had the reasoning run the other way, it would have been this mode.
  - *Missed-relevance specifically checked* against two prior Traces under different purposes; neither used as an exclusion filter, and regions previously unvisited (the spec's layer vocabulary, the promotion precedents) are core here.
  - *Interpretive-overstep specifically checked:* the Frontier states co-locations and leaves every relation undetermined — including item 3, which places two facts side by side without drawing the inference.

### Self-assessment verdict

**PROCEED**

All convergence criteria met; no LAYER 1 or LAYER 2 flags raised. Four `inferred` regions recorded as frontier flags, two at MEDIUM. Output ready for Warm.

---

## Re-surface round 1

*Composed by the runner. Triggered by the warm pass's round-1 MQ2, which committed an anchor naming a territory the first surface had not fetched: **the artifacts that instantiate the corpus's several senses of `layer`, and whether any of them carries the output-side structure the two spec files lack.** The first surface reached the two spec files; it did not reach the other twelve documents in the PRAGMA core, two of which it had flagged at MEDIUM.*

**Refined sub-purpose:** whether any PRAGMA core document other than the two spec files carries APT's magnitude, TYPE, or the persistence column — and whether any of them defines or operationalises *layer*.

**Territory:** `BASEFILES/profiling_data_extraction/pragma/core/` — the twelve documents not read in round 0.

### Traversal Trace — round 1

#### 10 — Region `R9 / the remaining PRAGMA core documents`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| the twelve unread documents, enumerated | core | HIGH | `{none, null}` |
| a term-scan across all twelve for *MAGNITUDE* · *Persistence under change* · *Emotional Composure* · *Specificity* | core | HIGH | `{none, null}` |
| `interpretation_layer_prompts.md` — uses *layer* only as a **pipeline-stage** name (*"Interpretation Layer reads all PRAGMA dimension outputs together"*); **defines nothing** | core | HIGH | `{filesystem, 2026-03-26T09:52:08Z}` |
| the `dimensions/` subdirectory — per-dimension measurement specs, below the interpretive layer | sub | MEDIUM | `{none, null}` |

*Step note:* the term-scan returned five files with hits, all of which required disambiguation. Two are homonyms; one is a genuine find that changes a round-0 absence.

#### 11 — Region `R10 / homonym disambiguation`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| *magnitude* in `dynamics_profile.md` (7 hits) — **signal-gap magnitude**, a threshold on measured gaps (*"Any gap with magnitude > 0.3 is flagged"*). Not attachment magnitude | umbrella | HIGH | `{filesystem, 2026-03-26T09:52:08Z}` |
| *Specificity* in `pragma.md`, `behavioral_profiling.md`, `interpretation_layer_testcases.md`, `dynamics_profile.md` (30 hits total) — PRAGMA's **Information-Density sub-measure** (*"Specificity: entity: high… temporal: absent"*). Not APT's Signal Specificity | umbrella | HIGH | `{filesystem, 2026-03-26T09:52:08Z}` |
| the round-0 absence therefore **holds** for these four files | core | HIGH | `{none, null}` |

*Step note:* HIGH-confidence rejections, retained at umbrella rather than dropped, per §4.4.

#### 12 — Region `R11 / the migration sidecar — the round's decisive find`

| Item | Verdict | Conf | Recency |
|---|---|---|---|
| `apt_should_be_extended_with_resonance.md` — a standalone document migrating one iteration's addition into the spec layer, citing its source finding by path | core | HIGH | `{filesystem, 2026-05-01T14:10:54Z}` |
| it carries the **four-variable / three-gate formula**: `f(charm, hope, fear, resonance) × g₁(SP) × g₂(Coherence) × g₃(Emotional Composure)` | core | HIGH | `{filesystem, 2026-05-01T14:10:54Z}` |
| a section titled **`## TYPE Implication`** — the **only** spec-layer occurrence of TYPE | core | HIGH | `{filesystem, 2026-05-01T14:10:54Z}` |
| that section quotes **three of the five persistence behaviours verbatim** — *persists through absence, maintained via shared model* · *weakens as access recedes* · *dissolves when exchange ends* — while naming neither the column nor a layer | core | HIGH | `{filesystem, 2026-05-01T14:10:54Z}` |
| **it is the only such sidecar** — one iteration of five migrated, and by adding a file rather than editing the spec | core | HIGH | `{none, null}` |
| the phrase *Persistence under change* appears **nowhere** in `BASEFILES/` | core | HIGH | `{none, null}` |

*Step note:* this region **falsifies part of the round-0 absence** and is recorded as a correction rather than an addition. See the amended absence below.

### Amended confirmed-absent regions

**Absence 1 is CORRECTED.** Round 0 recorded that neither spec file contains the output dimensions the quoted passage describes. That remains true of the two spec files. It is **not** true of the spec layer as a whole: `apt_should_be_extended_with_resonance.md` carries a `## TYPE Implication` section and three of the five persistence behaviours in prose. The corrected absence reads: **the phrase *Persistence under change* appears nowhere in the spec layer, the column appears nowhere, and TYPE appears in exactly one document — a sidecar migrating a different iteration, where it is a consequence noted in passing rather than a structure.**

**Absence 2 is NARROWED.** Round 0 recorded that neither spec file contains four of the corpus's five later structural additions. Still true — but the sidecar carries **Coherence and Emotional Composure inside the formula it states**, so the spec layer is behind by less than the two spec files alone suggest. What no spec-layer document carries is **Specificity**, the **output-dimension pair**, and the **column**.

**Absence 3 (no definition of *layer*) is CONFIRMED and strengthened.** The one document with *Layer* in its title uses it purely as a pipeline-stage name and defines nothing. Thirteen spec-layer documents, six senses of the word in use, zero definitions.

**Absences 4 and 5 are UNAFFECTED** — no version of the naming action item appears anywhere in the spec layer, and no naming criteria are stated as criteria.

### New concept-names — round 1

| Name | Type | Provenance | Gloss |
|---|---|---|---|
| the migration sidecar | coined-term | 12 | A standalone file carrying one iteration's addition into the spec layer, instead of an edit. |
| migration-by-sidecar | coined-term | 12 | The corpus's one demonstrated migration pattern — and why the main spec still lists Resonance as an absence. |
| TYPE-as-consequence | coined-term | 12 | TYPE's only spec-layer appearance: a noted implication of a different addition, not a structure. |
| pipeline-stage-only *layer* | coined-term | 10 | The Interpretation Layer's usage — a stage name, defining nothing. |
| signal-gap magnitude | vocabulary | 11 | The homonym: a threshold on measured gaps. |
| information-density specificity | vocabulary | 11 | The homonym: PRAGMA's own sub-measure. |

### Round-1 telemetry

- **Items enumerated:** 14 · core 10 · sub 1 · umbrella 2 *(one item recorded in both the trace and the amendment)*
- **`items_with_mtime`:** 8 · **`items_without_mtime`:** 6
- **Convergence:** met at this resolution — every PRAGMA core document reached; the `dimensions/` subdirectory recorded as measurement-layer and not entered
- **Failure modes:** all twelve checked; **none observed.** *Surfaced-irrelevance specifically checked* — the two homonym clusters were disambiguated by reading their actual context rather than counted as hits.
- **Effect on the anchor:** **material.** One round-0 absence corrected, one narrowed, one strengthened. The warm pass re-anchors on the amended surface.

### Round-1 self-assessment: **PROCEED**
