# RMP.9 — Decide Whether and How to Improve Research Methods and Practice: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Research Method Practice Principles Framework* (27 September 2026), `Engineering DPF Suite/RESEARCH-METHOD-PRACTICE-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## RMP.9:5 - Archetypal Grounding {#archetypal-grounding}

The cases below are constructed teaching cases. Their stated premises define the situations in which the choices follow.

### RMP.9:5.1 - Correct the calculation and retain the Method {#correct-the-calculation-and-retain-the-method}

A team's accepted Method estimates sample variance for independent observations by dividing the squared-deviation sum by n−1. The receiving conditions still fit this Method. A software default instead divides by n.

For observations 2, 4, 6 and 8, the mean is 5 and the squared-deviation sum is 9 + 1 + 1 + 9 = 20. The specified sample variance is 20/3; the implementation reports 5. The difference is a determinate implementation defect under the case premises.

Correct the denominator and verify the calculation and its dependent uncertainty output. The result is: retain the Method for the named conditions, repair its implementation, identify analyses that used the wrong value, and return consequential corrections through RMP.5 and RMP.8. Unaffected analyses remain valid at their existing reach.

Additional participants or a new efficacy trial would not determine this already specified correction. The known-answer check establishes the corrected calculation; it does not qualify another estimator or a changed receiving situation. This is a completed useful ResearchMethodPracticeRevision.

### RMP.9:5.2 - Select a worthwhile comparison without inventing its result {#select-a-worthwhile-comparison-without-inventing-its-result}

A programme now estimates an equally weighted mean across independent sites, with repeated observations within each site. Site sample sizes differ and observations within a site are dependent. The old pooled-observation analysis does not answer the intended site-level question with defensible uncertainty under the case premises.

The team first fixes the target. Two attainable candidates use the same mean of site means but construct uncertainty differently: a t interval from independent site means and an interval obtained by resampling whole sites. The names of these procedures do not settle their adequacy when there are few sites, skewed outcomes and plausible heterogeneity.

A qualified statistician, existing simulation code and a bounded two-day allocation make a discriminating comparison attainable. The programme will reuse the chosen analysis across several studies, and a wrong uncertainty claim would materially affect that work. Include design, code checks, computation, failed runs, Monte Carlo uncertainty, interpretation and transition in the burden; the two-day availability is a case premise, not a general cost estimate.

Select the simulation around relevant generating situations, the shared estimand and the performance required by the intended use. Preserve adverse and inconclusive results. Both candidates may prove inadequate for the proposed reach, leading to a narrower claim or stopped use.

The completed result here is a justified decision to obtain evidence. Method qualification and the choice of a winning procedure remain unresolved until actual results exist. If the access, capability or worth premises change, reconsider this acquisition decision.

### RMP.9:5.3 - Repair interpretation within reflexive thematic analysis {#repair-interpretation-within-reflexive-thematic-analysis}

A reflexive thematic analysis team receives a request to improve quality by maximizing agreement among coders. In this constructed case, the actual weakness is a topic list that does not develop a coherent interpretation. Disagreement alone does not identify a failure of this approach.

Rework the analysis through coherent interpretation and reflexive discussion, and judge the resulting themes against that purpose. A compulsory reliability study would address another question. If the research purpose instead requires repeatable fixed-category counts, select and qualify the corresponding Method and criteria. This distinction applies to reflexive thematic analysis; agreement criteria can be appropriate in other Methods.

### RMP.9:5.4 - Correct source extraction without certifying a new tool {#correct-source-extraction-without-certifying-a-new-tool}

An OCR tool repeatedly omits marginal dates in a bounded historical collection. Source images are available. Recover the missing material, correct the affected transcription and chronology, and preserve the relation between the source and the resulting interpretation. This repairs the extraction and its consequences without automatically replacing the historical Method.

A replacement tool intended for a materially different handwriting collection raises another question. Select a comparison only when it can change a consequential source use and access, expertise and effort make it worthwhile. Faster extraction alone does not establish fidelity. If originals are unavailable, preserve the resulting limitation on the argument; declining a new experiment does not make the transcription reliable.

### RMP.9:5.5 - Preserve the distinct contributions in mixed research {#preserve-the-distinct-contributions-in-mixed-research}

A project combines a fixed-category count with an interpretive account. A coding revision changes both what is counted and what the categories mean. Reassess the affected count, interpretation and integration relation at their own purposes. A gain in counting consistency cannot by itself settle the interpretation, while an interpretive insight cannot validate an altered measurement.

Return the affected operational, analytic or synthesis contribution through RMP.3, RMP.5 or RMP.7. Retain the unaffected material and make any changed claim visible to its actual recipient. The two contributions need a defensible relation, not an invented common score.

## RMP.9:6 - Bias-Annotation {#bias-annotation}

Statistical examples make numerical errors and comparison criteria easy to inspect. That convenience can obscure interpretive, historical and community research whose criticism takes another form. The unlike cases preserve those differences, but do not stand in for every field's professional knowledge.

Method improvement can favour novelty, visible activity or readily counted gains. Retention and small corrections can receive less attention, while a cheap-exit preference can hide a genuine need for evidence. The relevant counterweight is the named research use, current alternatives, full burden and the limit on unsupported application.

## RMP.9:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | What fails | Repair |
| --- | --- | --- |
| Every criticism becomes a new trial | A determinate correction or adequate present answer is left unfinished while acquisition work grows. | Try the supported answer first; select additional evidence by its effect, attainability and full burden. |
| No affordable comparison means the Method is adequate | A decision about acquisition is substituted for evidence of suitability. | Preserve the unsupported-use restriction or stop and the unresolved qualification. |
| Every software change creates a new Method | Implementation and description changes are confused with semantic changes and lose appropriate evidence reuse. | Identify the actual changed subject and qualify only the affected reach. |
| One metric improves every research tradition | The chosen indicator changes the research purpose or overlooks its criticism. | Compare alternatives under the actual estimand, interpretation or source-use question. |
| Only successful trials enter the comparison | Failures and non-convergence disappear from the evidence used for the Method decision. | Preserve them and choose their treatment by the comparison's aim. |
| New description means successful adoption | An announcement is mistaken for changed practice or an improved result. | Distinguish supplied support, actual use and subsequent evidence. |
| Every Method revision restarts the research repertoire | Unaffected questions, material and claims are reopened without a changed dependency. | Return only the consequential change to its actual consumer. |

## RMP.9:10 - Rationale {#rationale}

Research-Method improvement needs a research-specific connection between a Method difficulty, its criticism and the knowledge contributions that depend on it. General Method Engineering already provides reusable distinctions for trial, fit, worth, variants and introduction. Using those contributions at the required scope avoids reconstructing a full Method lifecycle for every correction.

The order matters. Identifying the actual object and trying the supported present answer prevent unnecessary acquisition before its costs arise. Separating evidence sufficiency from acquisition worth then protects the opposite boundary: a justified decision to stop looking does not establish an unsupported claim.

## RMP.9:11 - SoTA-Echoing {#sota-echoing}

The working question is how to improve research practice when criticism leaves a Method decision open, without spending effort on evidence that cannot change the answer. The best-known answer selected here combines situated comparison with a prior decision about whether further evidence is worth obtaining. [Method Engineering](spec://ai.lev/fpf-eng-me/pub/TOC#root) supplies reusable identity, trial, fit, worth, variant and introduction distinctions. ME.14:4.1–4.2 compares feasible courses and their full burdens, permits an adequate present choice or a retained set with its limitation, and selects further inquiry only when its obtainable result could change the choice enough to warrant the whole burden. RMP.9 **adopts** these stopping and acquisition distinctions and **adapts** the comparison to the research question, criticism requirement and affected research result in §4.3. A sufficient existing research account can carry that decision without a separate ME.14 record. At the effort needed to diagnose §5.1's specified calculation error, retention plus verified repair already answers the use; a further efficacy study adds no discrimination. Where qualification is unresolved, preserve the uncertainty and restrict unsupported use. Reopen this source use if Method Engineering changes the relied-on stopping or acquisition conditions; reconsider a research comparison when its obtainable result becomes worth the whole burden.

For a simulation already selected, the question is which procedure answers the intended research target under the relevant conditions. RMP.9 **adopts** the common-target design in [Morris, White and Crowther (2019)](https://doi.org/10.1002/sim.8086), refined by [Williams et al. (2024)](https://doi.org/10.1111/2041-210X.14415) on inspectable planning/reporting and [Pawel et al.](https://doi.org/10.1080/00031305.2025.2540002) on missing outputs and non-convergence. These sources support the selected line over a comparison that silently ranks only successful runs: different failure rates can make that ranking answer another question. In §§4.3 and 5.2, preserve the common estimand, generating situations, performance criteria, Monte Carlo uncertainty and failed runs. This deliberately accepts the effort of diagnosing and interpreting failures within the comparison's whole burden; apparent simplicity is insufficient reason to discard them. Their treatment follows the study's aim. The sources discipline an obtained comparison, not its necessity or a universally winning Method. Reopen when a changed target, newly observed failure or stronger treatment of missing outputs changes the applicable comparison.

For reflexive thematic analysis, the question is how to repair weak interpretation while preserving that research purpose. RMP.9 **adopts** methodological coherence from [Braun and Clarke's RTARG contribution (2024)](https://doi.org/10.1177/02692163241234800) and their [quality guidance](https://www.thematicanalysis.net/quality-in-ta/). Section 5.3 **rejects** compulsory coder agreement as the repair for an undeveloped topic list: agreement can leave the interpretive defect intact. The selected work spends analytic effort on developing a coherent interpretation and reflexive scrutiny. This choice forgoes an agreement indicator that serves a different purpose; fixed-category counting would reopen the Method and criteria. Reporting guidance alone does not establish interpretive quality.

For historical extraction, RMP.9 **adapts** the [AHA professional statement's](https://www.historians.org/resource/statement-on-standards-of-professional-conduct/) source-integrity and recoverable-trail requirements to §5.4's missing marginal dates. Comparing extraction tools by speed alone cannot establish fidelity to the available originals. Correcting the bounded extraction and chronology preserves that criterion and its receiving argument, while accepting the effort of checking sources. This is a reasoned application of a professional constraint, not evidence that one OCR tool is superior. A different collection, unavailable originals or a newly attainable tool comparison reopens the applicable correction or limitation.

These comparisons preserve different research purposes rather than ranking statistical, reflexive and historical work on one scale. Their synthesis and constructed cases explain the selected action and trade-offs; they are not measured evidence that deploying RMP.9 improves research outcomes.


## RMP.9:End {#end}
