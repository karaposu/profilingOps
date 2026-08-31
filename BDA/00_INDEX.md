# BDA — Canonical Theory Layer · Index & Charter

**What this folder is.** The single current-state home of **BDA (Belief-Driven Attachment)** — the theory named APT (Attachment & Presentation Theory) until 2026-08-25; the rename and its scope are recorded once, in `RENAME.md`. The legacy spec layer (`BASEFILES/profiling_data_extraction/pragma/core/`) is frozen as a historical snapshot (March–May 2026) and is **never edited**; the findings chain (`inquiries/*/finding.md`) remains the *argument record* — the derivations and evidence. This folder is the *state record*: what the theory currently commits to, one claim in one place, with provenance and status attached. When populated, a reader should never need the legacy files, and should need a finding only to see *why* something is true, not *what* is true.

**Status:** architecture committed 2026-08-25 · **all 17 content files populated 2026-08-25** from a full fresh read of the complete corpus (14 core files + 21 findings, per the reading manifest below). Validation status of the content: structural-only throughout — the theory itself remains empirically unvalidated and uncalibrated, and every file's header says so.

---

## The design rules (each one encodes a documented failure of the old layer)

1. **Single source of truth.** Every claim is *owned* by exactly one file; every other file links to the owner instead of restating. *(Lesson: "Mission-Focus amplifies Hope" lived in two legacy places; its correction reached neither.)*
2. **Topic files, never iteration files.** Content files are organized by subject and updated in place. Iteration history lives only in `90_HISTORY.md`. *(Lesson: sidecar files like `apt_should_be_extended_with_resonance.md` and the never-created `apt_iteration_3_4_1.md` companions are how divergence starts.)*
3. **Status stamps.** Every file opens with a header: `Current as of: <date> · Sources: <findings/iterations> · Validation: <structural-only | ...>`. Sections that rest on a specific finding cite it inline. *(Lesson: the legacy "current-state" spec silently presented an outdated 3-variable formula as current.)*
4. **Plain language first.** Every term is defined in `01_OVERVIEW.md`'s glossary and glossed at first use in each file; corpus shorthand never appears bare. *(Lesson: the 2026-08-25 clarity revision of the leadership-as-calculation finding — "the term", "the catalog".)*
5. **Descriptive and prescriptive kept visibly separate.** Advisory content lives only in `60_PRESCRIPTIVE.md` under an explicit "guidance, not description" banner. *(The theory's own iteration-3.1 principle.)*
6. **Forks stay forks.** Genuinely unsettled questions (Fear's two definitions above all) are presented as unsettled, with both readings and their consequences — never silently picked. *(Lesson: the teacher-scenario's "or" that no document ever engaged.)*
7. **Coverage is auditable.** `02_REGISTRY.md` lists every named element with its kind, admission rule, and owning file. A claim that cannot be addressed in the registry has no home — which is the signal to either extend the registry deliberately or reject the claim. *(The registry proposed by the forms-of-attachment and artifacts findings, made real.)*

**Split trigger:** a file exceeding ~600 lines splits along its own top-level headings; the index and registry update in the same edit.

**Flat, not folders:** the decade prefixes are the grouping (`0x` meta, `1x` core, `2x` gates, …) — they deliver what subfolders would (category structure) *plus* what subfolders lose: the whole theory visible in one sorted listing (rule 7's audit surface, and a new reader's orientation), a built-in reading order, and links that never break from a move. The one thing folders would add is namespace room for many more files — and resisting file-count growth is rule 2's whole point; needing a new number is deliberate friction. Revisit only if the folder passes ~30 files or one decade accretes 4+ files; then that decade promotes to a subfolder, with links updated in the same edit.

---

## The files

### 0x — Meta

| File | Charter |
|---|---|
| `00_INDEX.md` | This file: the map, the rules, the maintenance contract, the population plan. |
| `01_OVERVIEW.md` | BDA in plain language for a new reader: what the theory is and is for; the formula in one screen; the full glossary (every term this folder uses, defined the way a newcomer needs); the epistemic banner (receiver-side; structural, not empirically validated; uncalibrated). |
| `02_REGISTRY.md` | The element registry — one row per named thing: what kind (variable / sub-flavor / modulator / species / signal / output / derived view / residual / instrument), what admits a member to its set, primitive or derived, its predication address where relevant, and its owning file. The coverage-audit backbone. |
| `03_METHODS.md` | The theory's own epistemic instruments, stated once: the generate-alone test (variable admission); the eight modulator criteria (pointer to `20`); the two-way dissociation test with its runs to date and its one-step extension to predication questions; the bearer/relocation discipline (bearers are tested, never asserted; the recurring pair-predication pattern); the external-anchoring convention (vocabulary-only imports, with the precedent list); the iteration-label convention; and Cluster 4 — the standing "should attachment be re-grounded in attention?" question — with its reopening conditions, its review count (never triggered), and the piecewise-satisfaction hypothesis. |

### 1x — Architecture and the four variables

| File | Charter |
|---|---|
| `10_ARCHITECTURE.md` | The current formula and its logic: the four additive variables × the three multiplicative gates; the belief-frame (everything is receiver-side belief; variables = property-beliefs about the sender, gates = stance-beliefs; attachment is *generated by* beliefs, not itself one — including the open naming question); why additive vs multiplicative; the outputs (magnitude and type, with type as a read-off/projection, not an independent taxonomy); Pattern A (valence × temporality) and the unilateral-vs-dyadic split; Signal Specificity (per-variable expression-quality scaling — explicitly not a fifth variable); the context layer (θ per channel; display-mode coupling; receiver availability as pre-condition); and one section of pointers to what is deliberately *outside* the formula (`50`). |
| `11_VARIABLES.md` | **The four variables as one system-file** — kept together deliberately, because their load-bearing content is relational (orthogonality is established pairwise; Pattern A organizes three of them jointly; the unilateral-vs-dyadic split cross-cuts them) and single-sourcing that content beats scattering it across four thin files; per-element coverage-audit is `02_REGISTRY`'s job, not a file-boundary's. Contents: the system-level facts first (the pairwise orthogonality evidence with its decisive cases; Pattern A — valence × temporality; unilateral-evaluation vs dyadic-emergence; the killed substrate-reframes), then one major section per variable: **Charm** (current-positive value: status / competence / impressiveness; the dead-composer orthogonality case; the competence-legibility limit at medium confidence; the named-but-deferred interior split; the Validation-Hope boundary) · **Hope** (the structural unifier's four primitives; the seven sub-flavors in full with nesting and basis-not-partition; the killed candidates and why; access-Hope, and why mission-participation is *not* Hope) · **Fear** (**the fork, first-class**: threat-of-harm vs cost-of-loss, the belief-statement/detection-signal mismatch, which findings each reading is load-bearing for, declared-not-settled; Specificity applied to Fear; the over-report hazard) · **Resonance** (dyadic emergence; why its admission grounds differ; the internally-maintained persistence family; networks as composed dyads; the open maintenance question). Splits per the ~600-line trigger only if a section outgrows the file — Hope's sub-taxonomy is the likely first candidate. |

### 2x — The gates

| File | Charter |
|---|---|
| `20_MODULATORS.md` | The Modulator Suite: multiplicative gating (any zero collapses the product); the eight entry criteria and how they have bitten; **Coherence** in full (stability + alignment; Model-Collapse; the "reliable, not finished" repair of its belief statement); **Emotional Composure** in full (regulation; Contagion-Drain; its discriminating role in the anger cases); the exclusions with their reasoning (Vitality; the decay-modulator class; model-completeness — pointer to `50`); the open single-failure-pole question. |
| `21_SELF_POSITIONING.md` | The largest element, in full: the genus (non-extractive attention) and the Supplication pole; the species with their **attention-objects** tabulated (the object column), generativity and externality marked; the five-axis predication scheme (species / genus / level / object / observer) with species-as-proxy and its one recorded naming-failure; levels (high / calibrated / low / collapsed); **the display catalog** (the five signals, each defined behaviorally, Withholding's double-edge and coupling rule); backed-versus-performed displays (the distinction; decay arc owned by `30`); oscillation dynamics; bearing and character-attribution; the 2×2 diagnostic. Owns the descriptive definition of outcome-independence (the operational marker of non-extraction). |

### 3x — States, signatures, time

| File | Charter |
|---|---|
| `30_STATES_AND_SIGNATURES.md` | What the outputs do over time: the type taxonomy as a projection (generator level and signature level; the join-table reading; Collaborative; derived-but-predictive); the persistence-under-change column (five rows, provisional flag carried verbatim); the engagement-states (attachment / pursuit / compliance) as a **derived view**, not sibling states — with the three jobs the word "compliance" does; the two-family reading (externally-grounded Charm/Hope/Fear vs internally-maintained Resonance); the mimicry/costly-signal **decay arc** and partial decay (contraction to a backed core). |
| `31_READOUT.md` | **How the theory is read out in practice** — the operational interface, added after the full-corpus read showed the architecture had no home for it. Contents: where BDA sits in PRAGMA (consumes the Dynamics Profile + tension analysis; interprets, never extracts); **APT Inference**'s output contract (directional per-pair readings; the 5-level categorical scale — absent/low/moderate/high/very_high — with the why-categorical rationale; per-field grounded reasons; species + level + outcome-independence estimate; cumulative cross-segment confidence); **APT Profiling**'s bearings schema (trigger / blocker / non-trigger patterns per variable; presentation tendencies as condition→behavior; aggregate-reasons-never-average-levels); the unified iteration-3.3 detection pipeline (channel classifier → evidence aggregator → specificity gate → mode classifier → approach-act contribution → MAGNITUDE + TYPE); and the **known readout hazards** (Coerced over-report — Fear's four signals fire on ordinary hierarchy and Specificity doesn't mitigate; ties are routine on categorical levels; coefficients uncalibrated so no weighted argmax; species is the only instrument-readable coordinate — no object-side detection exists). Descriptive of the instruments as specced; implementation itself stays outside this folder. |

### 4x — Phenomena

| File | Charter |
|---|---|
| `40_GROUPS_AND_LEADERSHIP.md` | The group-scale results, composed from dyads (the theory's own ceiling stated): followership defined (attachment + pursuit that cannot extinguish); **the two-clause criterion** (owned here: generative object, outside the receiver — with the partial-inclusion extension); leadership's mechanism (Resonance-primary + access-Hope; the leader as access-point to the shared object); movements as follower-follower dyad networks; shareability (movements vs devoted individuals); the **roles table** (leader / adhesive glue / catalyst glue / technical founder / strategic broker) with removal-signatures; the removal test and its two-cause note (glue-loss vs term-loss); glue-ness as person × group pair-predication; conferred position → compliance; importance ≠ leadership (the two axes). |
| `41_PHENOMENA_INDEX.md` | The phenomenon-to-coordinates index (the artifact type the anger finding proposed): for each worked phenomenon, the values every component takes. Anger (deployed / leaked / performed; the four-coordinate table; the translated bluster rule). The dating case. The narcissist-followers / cults / demagogues layered cases (displayed vs genuine species; backing). The folk-attribute bridge (five leader-attributes onto four layers; people-gathering as effect; the softness narrowing; "masculine" as expression-register). The Jobs decomposition (harshness compatible-not-causal; the follower/employee/supporter split). |

### 5x — Boundaries

| File | Charter |
|---|---|
| `50_RESIDUALS_AND_BOUNDARIES.md` | What is real but deliberately outside the formula, each with its distinct role: Vitality (degradation factor); receiver availability (pre-condition); model-completeness (cross-variable epistemic modifier — governs pursuit, not attachment); the null case (behavior under a collapsed gate). The nine adjacent mechanisms (scoped outside; social proof; the social-norm-violation question). The hard boundaries: **no outcome term** (the theory never scores results); receiver-side by construction; groups only by composition from dyads; character-in-full beyond scope; business outcomes beyond scope. |

### 6x — Guidance

| File | Charter |
|---|---|
| `60_PRESCRIPTIVE.md` | **Banner: guidance, not description.** The prescriptive layer, updated by its first field test: outcome-independence as the cultivation target (definition pointer to `21`); the species-context-fit table; the practice-protocol references (Stoic dichotomy; performance-psychology process cues; Rogers' congruence — with the note that the backing requirement appears inside the traditions themselves); the tiered calibration audit; the two-halves feasibility result (slow half precedented; fast half = the one move, entry and recovery); the priced display-path and the boundary zone; the calculation card; the backing gate on display-targeted training. |

### 7x — Evidence

| File | Charter |
|---|---|
| `70_CASES.md` | The worked-case library, **restated with corrections applied and a status column** (this is where errata stop propagating): the fifteen validation scenarios — including Scenario 9 *as corrected* (Resonance + access-Hope, not Hope-amplification), Scenario 4 with its genus-license note and the never-engaged fork, Scenario 12's role as the Task-Focus attachment evidence, Scenario 10 (pre-verbal display), Scenario 15 (bearing/character) — plus the August cases (the Sid classification; the teacher fork; the Jobs decomposition; the technical-person audit). Every case marked: validation pending / corrected-from-legacy / partially evidencing an open test. |

### 8x — The living edges

| File | Charter |
|---|---|
| `80_OPEN_REGISTER.md` | All open questions, consolidated from every finding and route-map, typed (monitoring / blocked / research frontier / refinement trigger), each with its owning finding, its trigger, and what closing it unblocks. Headliners: the Fear fork; backing-observables (the single gate in the prescriptive program); the predication census (pool + the nine adjacent mechanisms — Cluster 4's determination procedure); the Task-Focus followership test (attachment half evidenced, followership half open); legibility's independent ground; the glue-census; Resonance's maintenance mechanism; the single-failure-pole question; the group-dynamics extension; calibration (scoped in advance: revives numeric reading, never numeric conduct). |
| `81_ERRATA_LEGACY.md` | The warning file for anyone reading the frozen legacy layer: known wrong-as-written content there, with the correction's owner-file here. Initial entries: "Mission-Focus amplifies Hope" (amplification table + Scenario 9 — corrected, see `70`/`12`); the three-variable formula presented as current (see `10`); "the corpus has no Task-Focus devotion case" in the leadership finding (Scenario 12 exists — see `70`/`80`); the bluster rule's pre-refactor vocabulary (translated, see `41`). |

### 9x — Provenance

| File | Charter |
|---|---|
| `90_HISTORY.md` | The iteration ledger: 1 → 2 → 3 → 3.1 → 3.2 → 3.2.1 → 3.3 → 3.4 → 3.4.1 → 3.4.2 → the August cluster (the eleven findings of 2026-08-21…25), one paragraph each on what changed; the iteration-label convention; the findings index with relation links (refines / corrects chains); the record of Cluster 4 reviews. History lives here and only here. |

---

## Ownership decisions for shared concepts (single-source assignments)

- The **two-clause criterion** → `40` (it is a followership-support criterion; `21` links).
- The **display catalog** and **backed-vs-performed** → `21` (`60` and `30` link; `30` owns the decay *arc*).
- **Outcome-independence** → defined in `21`, prescribed in `60`.
- The **dissociation test** and all admission instruments → `03` (the registry `02` records which rule governs which set).
- **Persistence / engagement-states / type** → `30` (`40` links for follower-persistence).
- **Model-completeness** → `50` (`30` links where pursuit is discussed).
- **Shareability** → `40` (flagged in `80` as the census's species-column candidate).

## The maintenance contract (how a new finding lands here)

1. Its spec-relevant MUSTs map to the owning files above; edits happen there, in place.
2. Its Open Questions merge into `80` (and close items there when they answer them).
3. Any correction of prior material lands in the owning file, and — if the wrong text lives in the frozen legacy layer or an unedited finding — gets an `81` entry.
4. If it adds, kills, or re-kinds a named element, `02_REGISTRY.md` updates in the same edit.
5. `90_HISTORY.md` gets its ledger paragraph.

## Population plan (executed 2026-08-25 in this order; retained as the re-population order for any future rebuild)

- **Wave 1 — the spine:** `90` (the ledger anchors everything), `02` (the registry from the findings' own element inventory), `03` (the instruments), `01` (overview + glossary).
- **Wave 2 — the core debt:** `10`, `20`, `21` — this is where the unperformed iteration-3.2 migration's content actually lives; populating these discharges that debt's *intent* without touching the legacy files.
- **Wave 3 — the variables and states:** `11`, `30`, `31`.
- **Wave 4 — phenomena and boundaries:** `40`, `41`, `50`.
- **Wave 5 — guidance and evidence:** `60`, `70`.
- **Continuous:** `80` and `81` start in wave 1 and grow with every wave.

Primary sources per file are the findings named in each charter; the frozen legacy layer is consulted read-only (chiefly for the fifteen scenarios and the species/context tables, which `70` and `60` restate with corrections).

**Reading manifest (user directive, 2026-08-25):** population work in any session must begin from a **full fresh read** — every file in `BASEFILES/profiling_data_extraction/pragma/core/` and every `inquiries/*/finding.md`, complete, no sampling, no memory-grade recall. Compacted-session summaries do not qualify. The origin chat export at repo root (`Claude-Attachment domain!…md`) is an optional additional source for `90`'s origin section only.
