# RMP.2 — Choose a Criticism-Bearing Research Design or Stop: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Research Method Practice Principles Framework* (27 September 2026), `Engineering DPF Suite/RESEARCH-METHOD-PRACTICE-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## RMP.2:5 - Archetypal Grounding {#archetypal-grounding}

All cases below are constructed pedagogical cases. Their supplied values distinguish the four dispositions; they do not report actual pump, stream, archive, instrument, or authority results.

### RMP.2:5.1 - Accelerated Seal-Test: Different Supplied Values {#accelerated-seal-test-different-supplied-values}

The supplied ResearchQuestionBrief asks whether a high-temperature acceleration condition preserves the field failure-mechanism relation well enough for degradation evidence to bear on the current Pump-P4 seal-life claim. Research does not choose the maintenance interval.

Compare the following relations when their supplied conditions make them serious:

| Option | Evidence and criticism relation | Principal loss or dependency |
| --- | --- | --- |
| stop on current evidence | Use an applicable result that already answers whether this acceleration condition preserves the relevant mechanism relation. | Cannot support a stronger maintenance or universal-life claim. |
| experimental/quantitative mechanism comparison | Compare degradation under the candidate accelerated and field-representative conditions using domain-admissible mechanism indicators; challenge acceleration-induced mechanism change and alternative material effects. | Requires qualified indicator relation, instrument feasibility, specimen/material comparability, safety, and authority. |
| field/observational relation | Use obtaining field exposures, failures, material batches, installation histories, and operating contexts to challenge whether the laboratory relation transfers. | Confounding, selection, sparse failure, measurement, and access may limit discrimination. |
| computational/model challenge | Test the proposed mechanism and acceleration relation through a domain-qualified model, sensitivity, calibration, and validation target. | Model-to-phenomenon relation, parameter identifiability, implementation, data, and validation can dominate. |

**EvidenceSufficientStop scenario.** A newly supplied current result already shows, with compatible materials and operating envelope, that the proposed acceleration condition changes the dominant degradation mechanism. The answer condition is met by the supported rejection of that test condition's relevance. RMP.2 returns the exact result, limitations, and reopen condition; it does not run an experiment to confirm an answer already sufficient for this use.

**ResearchDesignDecision scenario.** Domain engineering supplies the mechanism-indicator relation, measurement feasibility, material identity, safe operating envelope, and authority needed for the experimental comparison. The field and model options remain useful secondary evidence but cannot expose acceleration-induced mechanism change as directly within the current constraints. RMP.2 selects the experimental/quantitative family with that core comparison and criticism. `PostSelectionNeed` contains only the repository locator and serialization of already-required specimen, condition, observation, and deviation fields. The admissible choices change neither family nor criticism; an inability to record any required field falls outside the admitted range and reopens selection.

**ResearchDesignHold scenario.** The measurement owner has not established whether the proposed indicator distinguishes the two rival degradation mechanisms. One plausible result makes the experimental comparison discriminating; another makes it incapable of answering and favors field observation or a different model relation. RMP.2 returns a hold to the measurement/domain owner for that indicator-feasibility result, names both consequences, and begins no protocol Work. Whether to obtain the indicator-feasibility result remains a separate commitment.

**QualifiedNoNewStudy scenario.** The available evidence does not establish the relation for the bounded Pump-P4 case. The supplier confirms that the matched specimens no longer exist, and the qualified current frame shows that the obtainable field and model material cannot discriminate the competing mechanisms for that case. The present allocation answer is no new study: the relation remains unresolved. A future specimen collection would concern a different case and cannot recreate the lost comparison. If newly released, qualified field records make a relevant discriminating comparison obtainable within the available resources, reopen that choice and assess the useful study. Neither the earlier no-study answer nor a later selected design decides the maintenance interval.

### RMP.2:5.2 - Citizen Stream Salinity: Dispositions without an Affiliation Gate {#citizen-stream-salinity-dispositions-without-an-affiliation-gate}

The resident team supplies a brief asking which rival account explains a salinity increase for a named reach and period: road-salt transport, groundwater contribution, a changed outfall, seasonal hydrology, or sensor drift. Academic status, funding, and publication plans are irrelevant.

- Return `EvidenceSufficientStop` if current validated monitoring and source results already discriminate the bounded anomaly for the named use. Preserve limits; the team does not need a new project for recognition.
- Return a field/observational `ResearchDesignDecision` when measure validity, safe site access, comparison reaches/periods, and required authority are supplied and the selected spatial-temporal contrast can challenge the live rivals. An exact trace-file locator can remain a PostSelectionNeed; calibration feasibility, site access, or admissible comparison cannot.
- Return `ResearchDesignHold` when sensor validity, safe/legal access, outfall-record access, or seasonal comparison availability can still make the field strategy invalid or favor source synthesis, instrument repair, or no study. The hold names the owner and result; it is not a request for an academic sponsor.

The environmental or operational receiver retains response authority. A research result may change the bounded explanation and evidence limits, not order remediation.

### RMP.2:5.3 - Historical Source-Critical Case {#historical-source-critical-case}

An archive group asks whether a maintenance-practice change followed Directive-D or emerged earlier. Serious options are: stop on a current authenticated dated record; use a historical/source-critical design comparing provenance, chronology, workshop records, silences, and rival interpretations; or synthesize an already traced contested corpus when the question is corpus-level.

If the archive owner confirms access and provenance for the discriminating records, a historical/source-critical decision may be completed with only non-selection-changing transcription and locator conventions left. If provenance or access to the decisive record family remains unresolved and one result supports a chronology comparison while another eliminates it, that still-needed selection receives ResearchDesignHold. Do not substitute an experimental hierarchy or treat a reporting checklist as the design.

For a narrow chronology question, suppose one authenticated workshop series is the only presently accessible material that could distinguish practice before and after the directive. An online index and another scan format expose the same records and do not supply further design relations. A source-critical examination fits the two available investigator-days, its provenance and access are qualified, and an earlier or later dated entry would change the bounded chronology claim. This one serious research option can warrant ResearchDesignDecision; two invented designs add nothing. If that examination instead needs twenty investigator-days, supplied resource limits leave only two, and no feasible reduction preserves the discriminating relation, retain the unresolved chronology and return QualifiedNoNewStudy for that current allocation. A newly accessible independent ledger could change both the worthwhile comparison and the choice.

### RMP.2:5.4 - PostSelectionNeed Counterfactual {#postselectionneed-counterfactual}

Consider two remaining values after a field design appears selected:

| Remaining value | Counterfactual test | Disposition |
| --- | --- | --- |
| exact directory and identifier syntax for already-required observations and deviations | Every admissible syntax preserves the field family, spatial-temporal contrast, rival accounts, and criticism; an invalid non-recoverable syntax is outside the admitted range. | PostSelectionNeed |
| whether the only available sensor can discriminate salinity from temperature-dependent drift at the required scale | A positive result preserves the field comparison; a negative result requires another instrument, another evidence relation, or a stop. | ResearchDesignHold |

The difference is not how late the team plans to resolve the item. It is whether its value can change selection.

## RMP.2:6 - Bias-Annotation {#bias-annotation}

| Recurring bias | Likely drift | Repair |
| --- | --- | --- |
| favorite-method bias | The practitioner's familiar design defines the question and rivals. | Hold the brief fixed and compare actual answer-changing relations with the relevant no-new-study outcome. |
| hierarchy bias | One design family is presumed strongest regardless of claim and threat. | Compare the specific evidence relation and criticism each option enables. |
| novelty-of-tool bias | A new sensor, model, AI workflow, or platform is treated as an informative design. | State the answer-changing contrast, threats, and validation relation independently of the tool. |
| false-stop bias | Constraint, fatigue, low priority, or desired certainty is called evidence sufficiency. | Tie EvidenceSufficientStop to the brief's answer condition and qualified current evidence; an allowed uncertainty return does not meet that condition. |
| provisional-design bias | A selected label is retained while a load-bearing value is “TBD.” | Run the counterfactual; if the family or criticism can change, return ResearchDesignHold. |
| hold-everything bias | Harmless record, naming, or schedule details prevent selection. | Bound admissible values and prove that the family and criticism remain invariant. |
| reporting-as-design bias | A reporting guideline or protocol template is treated as design evidence. | Use it later for transparency where applicable; select the question-to-criticism relation here. |
| mixed-method accumulation | More methods are assumed to triangulate or strengthen automatically. | Give every component an irreducible evidence role and specify integration, disagreement, and partial-failure logic. |
| information-gain theater | A number is assigned without a defensible outcome model or decision use. | State which live uncertainty can change and how; use qualitative bounds when they are the honest resolution. |
| authority leakage | Selection is treated as ethics, safety, access, funding, or downstream-action approval. | Consume exact owner results and return the decision without transferring authority. |

## RMP.2:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Why it fails | Repair |
| --- | --- | --- |
| “Use the gold-standard design” | Strength is question-, threat-, and feasibility-relative; one family cannot expose every error. | Compare serious options by the exact criticism demand. |
| “The protocol is the design” | A template can serialize choices without justifying them. | Record the question-to-evidence relation, alternatives, threats, and selection rule first. |
| “Evidence is incomplete, therefore study” | An unresolved claim does not select a useful obtainable acquisition. | Compare the whole burden and contribution; return QualifiedNoNewStudy when the current allocation closes without a new study. |
| “No budget, therefore evidence sufficient” | Resource refusal is not an epistemic conclusion. | Preserve the bounded answer or unresolved question in QualifiedNoNewStudy when no current study is selected; resource and receiving decisions remain with their owners. |
| “Select provisionally and validate later” | A missing mechanism, measure, access, safety, or authority result may overturn the family. | Return ResearchDesignHold with the exact owner result and forked consequences. |
| “Everything must be fixed before selection” | Some implementation details cannot change the selected relation. | Prove invariance across the bounded admissible values and record PostSelectionNeed. |
| “Two software packages are two designs” | Tool variation may leave evidence and criticism unchanged. | Require an answer-changing relation, threat, or refusal difference. |
| “Mixed means stronger” | Components can disagree, duplicate bias, or lack a warranted integration relation. | Name each component's irreducible role and the rule for disagreement or failure. |
| “A rerun is a replication” | Code/data/environment reproduction, new-data replication, validation, and robustness test different claims. | Name the live threat and select the credibility move that bears on it. |
| “The selected design authorizes the study” | Design justification does not grant access, safety, ethics, rights, resources, or receiving authority. | Keep every external owner result and later decision separate. |

## RMP.2:10 - Rationale {#rationale}

Design is justified by criticism, not ceremony. A useful strategy creates a relation between the question and observations or sources that can make a material error visible. Comparing serious alternatives exposes what the preferred strategy cannot learn and prevents a familiar apparatus from defining the question.

The PostSelectionNeed counterfactual protects a selected design. If every admissible value and joint combination preserves the family, criticism and feasibility, later elaboration can proceed without reopening selection. If plausible values fork a selection still needed, calling that design complete would be false; ResearchDesignHold makes the missing dependency explicit. A completed current allocation choosing no new study can retain that same unknown as a limitation and reopen condition.

EvidenceSufficientStop preserves completion by an already adequate answer. QualifiedNoNewStudy separately preserves completion of the current allocation when evidence remains insufficient but no worthwhile obtainable study is selected. Keeping owner results external prevents RMP.2 from manufacturing domain truth, instrument validity, access, safety, ethics, or authority merely to finish a form.

## RMP.2:11 - SoTA-Echoing {#sota-echoing}

The working question is: **How should a practitioner choose among unlike research designs—or stop—so that the selected strategy bears on the live criticism and no missing load-bearing result is concealed?**

The selected current line is design-plural and uncertainty-led. The MRC/NIHR [framework for developing and evaluating complex interventions](https://doi.org/10.1136/bmj.n2061) selects among efficacy, effectiveness, theory-based, and systems perspectives from what is already known, which uncertainty matters, and what evidence would be most useful; its phases can be entered, revisited, repeated, or stopped rather than treated as one compulsory sequence. RMP.2 generalizes that selection discipline without importing health-intervention phases into every domain.

Unlike source families constrain criticism differently. The [Standards for Reporting Qualitative Research](https://doi.org/10.1097/ACM.0000000000000388) emphasize transparent qualitative reporting while preserving flexibility across paradigms and methods; RMP.2 uses them as a warning that reporting completeness is not design selection. The American Historical Association's [Statement on Standards of Professional Conduct](https://www.historians.org/resource/statement-on-standards-of-professional-conduct/) foregrounds careful source use, methods and assumptions, evidence-interpretation relations, bias awareness, and alternative interpretations in historical work. The current [Cochrane Handbook](https://training.cochrane.org/handbook/current/chapter-02) makes the review question govern eligibility, search, collection, and synthesis rather than treating “review” as a carrier label. The National Academies' [Reproducibility and Replicability in Science](https://doi.org/10.17226/25303) keeps computational reproduction and new-data replication distinct, supporting threat-specific credibility choices rather than one repeatability ladder.

A serious alternative is a universal evidence hierarchy or linear “scientific method”: choose the highest-ranked feasible design, operationalize it, collect data, and report. That route can be efficient for a narrow recurring question, but as a universal selector it suppresses historical source criticism, qualitative reflexivity, observational constraints, model validation, corpus synthesis, and legitimate stops. RMP.2 retains domain hierarchies only when a qualified domain use makes them decision-bearing and compares their actual criticism and losses.

The selected sources do not supply domain truth, universal validity criteria, instrument feasibility, rights, access, safety, ethics, or authority. Reopen this pattern when a stronger design-selection source changes the serious families or criticism relation, when a family is systematically misrouted by the counterfactual test, or when a domain-specific evidence rule changes one candidate. Reopen only the affected comparison and disposition.


## RMP.2:End {#end}
