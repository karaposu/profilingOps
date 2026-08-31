# 31 · Readout — How the Theory Is Read from Real Conversations

> **Current as of:** 2026-08-25 · **Sources:** the PRAGMA core specs (`pragma.md`, `dynamics_profile.md`, `interpretation_layer_prompts.md`, `apt_inference.md`, `apt_profiling.md`, `behavioral_profiling.md` — March 2026, describing **three-variable APT**) plus iteration-3.3's pipeline and the August hazard findings · **Validation:** the instruments are specced, not deployed; **the legacy instrument specs predate iterations 3.2+ and do not know Resonance, Coherence, EC, Specificity, MAGNITUDE/TYPE, or the species/level vocabulary** — this file describes the interface as it stands and marks every known gap.

## 1 · Where BDA sits in PRAGMA

*(Naming note: "APT Inference" and "APT Profiling" below are retained as the proper names of the legacy spec artifacts; a future implementation's components would be BDA Inference / BDA Profiling — `RENAME.md`.)*

```
raw conversation → PRAGMA Signal Layer (per message: involvement, control, density, intent, investment, function, temporal structure)
                → Dynamics Profile (per segment; LLM-composed DESCRIPTION — what is happening)
                → Interpretation Layer (tension checks; INTERPRETATION — what it means)
                → APT Inference (per pair, per segment)  → APT Profiling (per person, cross-conversation)
```

Epistemic ladder, kept strict by the specs themselves: facts → measurements → descriptions → interpretations. BDA lives at the interpretation level — one framework among possible others — and **interprets composed outputs only; it never extracts signals**. Its raw material is the tension analysis (pursuit/withdrawal, hidden competition, asymmetric investment, intent-behaviour mismatch) plus the Dynamics Profile text.

## 2 · APT Inference — the per-pair reading contract

- **Directional:** A→B and B→A are independent readings; the asymmetry IS the dynamic ("A admires, B needs").
- **Categorical, five levels:** absent / low / moderate / high / very_high — deliberately not floats ("Charm: 0.73" would be false precision; "Charm: high" states the real confidence).
- **Per-field grounded reasons required:** every score cites specific observed dynamics ("A's involvement increases when B demonstrates expertise, and A shifts to querying") — never impressions ("A seems impressed").
- **Cumulative:** each segment's reading receives the prior readings; confidence grows low → moderate → high across segments; early reads can be wrong (presenting-as-charmed may be qualifying).
- **Post-3.2 output shape** (per the iteration-3.2 finding; not yet in the frozen inference spec): directional C/H/F/R + Non-Extractive-Attention **species** + **level** (high/calibrated/low/collapsed) + outcome-independence estimate + displayed-signal signature + presentation readings + overall dynamic.
- **What it does NOT do:** profile (that's Profiling), prescribe, guarantee accuracy, or extract.

## 3 · APT Profiling — the per-person aggregation contract

Answers "what moves this person?" across conversations. **Aggregates REASONS and PATTERNS, never averages levels.**

- **Attachment bearings** per variable: **triggers / blockers / non-triggers** with evidence counts ("charmed by intellectual depth; blocked by condescension; wealth is a non-trigger").
- **Self-Positioning bearings** (post-3.2 shape): species tendency per context; baseline outcome-independence; collapse conditions ("collapses to Supplication under high-status counterparties").
- **Presentation tendencies:** condition → behaviour ("when challenged → over-explains; frame fragile, recovers slowly").
- Confidence by observation count (very_low @1 → very_high @16+); counter-evidence recorded, never deleted.
- Behavioral Profiling is the parallel output outside the attachment readings (how they communicate, no why); the two never feed each other.

## 4 · The iteration-3.3 detection pipeline (the unified design)

1. **Channel classifier** → θ(context) band (cold DM … physical proximity).
2. **Evidence aggregator** → distributes signals into C/H/F/R from four source-channels (interaction / prior experience / social proof / channel prior) — f as cumulative belief state made operational.
3. **Specificity gate** → effective_magnitude = nominal × specificity if ≥ θ, else 0.
4. **Mode classifier** → selective-engagement vs withholding SP → H_a realized or suppressed (the highest-cost, still-undesigned classifier).
5. **Approach-act contribution** → simultaneous f_Charm + H_a + g₁ credit, scaled by specificity.
6. **Output** → MAGNITUDE + TYPE per `10`/`30`.

Steps 1–2 are bounded extensions of existing capability; step 4 is genuinely new work; a source-independence classifier (for the multi-source prediction) is a further medium-cost item.

## 5 · Known readout hazards (each with its mechanism)

- **Coerced over-report.** Fear's four detection signals (asymmetric control unchallenged · reluctance to disengage · careful word choice · confrontation-avoidance) **all fire on a routine employee–manager exchange**; Specificity does not mitigate (it scales magnitudes; TYPE reads *relative* weights). A naive implementation reports ordinary hierarchy as coerced attachment, constantly — and the theory has **no term ranking an attachment as worth having** to qualify the reading. Do not operationalize TYPE before this is addressed.
- **Ties are routine.** Five-level categoricals + uncalibrated coefficients → no weighted argmax; the mixed row is itself a tie category. Signature determination is blocked on calibration (`80`).
- **Fear's instrument mismatch.** The detector is cost-of-loss-shaped while the belief statement is threat-shaped (`11` §4) — until the fork is settled, Fear scores measure an ambiguous construct.
- **Species is the only readable coordinate.** `attention-object` appears nowhere in the detection specs; the display catalog is species-shaped. The five-axis predication corrections (`21` §2) fix *addresses*, not detection — object-side and observer-side detection do not exist yet.
- **Per-message vs trajectory.** Compliance-vs-attachment discrimination and the anger cases' temporal criteria (does it terminate? how fast is recovery?) need trajectory data the theory currently discards at its own boundary (`30` §7).
- **Spec staleness.** The frozen inference/profiling prompts still describe two-domain, three-variable APT. Any implementation building from `BASEFILES/` alone inherits a formula the theory abandoned (`81`).

## 6 · What implementation would need (the standing order)

Extend inference/profiling schemas to the four-variable, three-gate, species+level shape → build the channel classifier and evidence aggregator → the mode classifier → per-sub-flavor Hope weights (basis output, nesting-consistent) → Coherence's longitudinal aggregation and EC's stress-responsive metrics → the Coerced-over-report mitigation decision → then, and only with calibration, anything numeric. Calibration, if it ever lands, revives numeric **reading of other people only** — never numeric conduct (`60` §4).
