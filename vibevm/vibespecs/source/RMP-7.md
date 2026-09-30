# RMP.7 - Synthesize a Research Evidence Corpus: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Research Method Practice Principles Framework* (27 September 2026), `Engineering DPF Suite/RESEARCH-METHOD-PRACTICE-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## RMP.7:5 - Archetypal Grounding {#archetypal-grounding}

These constructed cases illustrate the Method; they report no performed study.

### RMP.7:5.1 - Two compatible tests among four reports {#two-compatible-tests-among-four-reports}

A seal engineer receives reports A, A2, B and C. A/A2 describe the same randomized accelerated test; A2 supplies its fuller outcome account. B describes an independent test of the same material contrast under compatible stress and measurement conditions. C describes in-service replacement choices under different conditions.

The synthesis question is the difference in mean time to the defined laboratory failure between the new and comparison seal under the specified accelerated conditions. Assume complete observed lifetimes, suitable approximately normal estimates, independent study estimates and a domain-justified common effect. The four-report map retains A2's useful information without adding another independent estimate; C cannot estimate this laboratory contrast.

The recovered study estimates are 14 hours with standard error 4 for A/A2, and 8 hours with standard error 3 for B. Inverse-variance weights are 1/16 and 1/9. Their weighted estimate is 10.16 hours; its standard error is 2.4 hours, giving an approximate normal 95% interval of 5.46 to 14.86 hours.

The returned answer is a positive mean difference under the named laboratory conditions and assumptions. The study-specific estimates remain visible. The synthesis does not establish that the acceleration relation transfers to service or that a maintenance interval should change. C remains useful material for a different service-use question. An inadequate common-effect premise would reopen this calculation's interpretation, even if the arithmetic were correct.

### RMP.7:5.2 - A refusal with useful content {#a-refusal-with-useful-content}

Another supplied corpus reports leakage after one hour, failure time under another stress and technicians' replacement decisions. The requested answer is a common percentage reduction in 500-hour failure risk.

RMP.7 shows each result with its actual outcome, contrast, conditions and uncertainty. No supplied relation converts them to the requested risk. The result therefore says that this corpus does not establish that percentage and preserves the narrower comparisons it does support. It supplies neither a pooled number nor a conclusion of no effect. If the receiver asked only whether this corpus establishes the percentage, that question is complete.

### RMP.7:5.3 - Situated participation and a mixed question {#situated-participation-and-a-mixed-question}

A resident group asks what impedes participation in water monitoring. One interview study links distrust to withheld feedback. Another interpretive study relates continued participation to community authority over the question. A survey reports stated reasons within its own sampled group.

Under a justified same-question mixed design, the synthesist retains the survey's counts and denominator, the qualitative contexts and the source authors' interpretations. A comparison suggests that control over both the question and returned information may matter. That explanatory connection is the synthesist's contribution; it is not a measured population prevalence. A contrary case with continued participation despite withheld feedback qualifies the explanation.

For a separate question about the monitoring intervention's effect on water quality, these accounts and any effect studies need their own syntheses before their relationship is examined. Agreement about participation is not an estimated effect on water quality.

### RMP.7:5.4 - Shared memoir and contrary chronology {#shared-memoir-and-contrary-chronology}

Several later histories attribute a factory's decision to close to a public protest. Their references lead to one retrospective memoir. An authenticated record dates that decision before the protest.

The historian separates the shared evidential source from the later interpretations and examines what the decision record establishes. The protest cannot have caused that earlier decision. The decision's cause and any effect on later implementation remain unresolved. The chronology is a useful completed corpus answer; counting the later histories would have concealed its decisive contradiction.

## RMP.7:6 - Bias-Annotation {#bias-annotation}

The numerical example makes statistical combination unusually easy: compatible targets, recovered dependence and justified assumptions are supplied. Real corpora may require domain expertise, additional source recovery or a narrower answer. The historical and participation cases expose different criteria; neither makes this pattern an exhaustive handbook for those traditions.

Publication and access practices can privilege certain institutions, languages or surviving sources. Interpret silence and corpus coverage in that setting. Reusing a convenient synthesis remains appropriate only for the question and qualifications it actually covers.

## RMP.7:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Failure | What changes in practice |
| --- | --- |
| More reports are treated as more independent studies. | Recover the underlying contributions and model or remove double counting while retaining supplementary information. |
| Everything numerical is pooled. | Recover the target and transformation; use a supported narrower synthesis when they do not justify the requested aggregate. |
| Only significant findings count as agreement. | Synthesize the relevant estimates or other justified contribution, retaining uncertainty and missing evidence. |
| A theme becomes a population percentage. | Preserve the qualitative interpretation and use actual sampling and measurement support for a prevalence claim. |
| A single confidence label covers the whole corpus. | Tie appraisal and uncertainty to the finding and the approach whose criteria supply that judgment. |
| Disagreement prevents any useful answer. | State the supported distinctions or the precise refusal, including what remains unresolved. |

## RMP.7:10 - Rationale {#rationale}

A source collection supplies material; the research synthesis establishes a further relation among its contributions. That relation needs its own design and criticism. Keeping it distinct from RMP.5's individual inference makes dependence, coverage and integration visible without making synthesis compulsory after every analysis.

A useful refusal is informative when it identifies the missing relation and preserves the supported answer. It protects both legitimate combination and honest completion.

## RMP.7:11 - SoTA-Echoing {#sota-echoing}

**What counts as independent support?** The selected line recovers the underlying studies and source relationships while retaining additional information from their reports. The cheap default is to count publications or discard all apparent duplicates. The former inflates support; the latter can lose follow-up detail. **Adapt:** 4.2 combines information at the appropriate contribution and preserves consequential overlap, as illustrated by A/A2 in 5.1. Cochrane [chapter 5](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-05) supplies the best-known-line candidate for these report/study distinctions because it resolves both failures, not because it is an institutional handbook. This recovery adds work when relationships are unclear; it is needed only where they can change the finding. New overlap, provenance or supplementary results reopen the affected contribution.

**Which numerical answer can this corpus support?** The selected line chooses a synthesis for a stated quantity and dependence model, with explicit alternatives when that quantity is unsupported. The serious alternatives are pooling every numerical result or refusing all heterogeneous material. The first invents comparability; the second can discard a warranted combined estimate. **Adapt:** 4.4 and 5.1–5.2 preserve justified combination and an informative narrower answer. Cochrane [chapter 10](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-10) supplies the quantitative best-known-line candidate; [chapter 12](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-12) supplies the competing non-meta-analysis route when its conditions fit. Their substantive question and interpretation rules justify the choice; intervention-review conventions do not govern every research family. The trade-off is model and grouping judgment in exchange for an interpretable answer. A changed target, dependence relation or defensible alternative model reopens that choice.

**How should missing contributions affect a finding?** The selected line locates what is missing and the particular inference it can change. Treating an available corpus as complete is cheaper but can hide selective results; rejecting every incomplete corpus would also erase bounded useful answers. **Adapt:** 4.1 and 4.3 retain question-relative coverage and distinguish unavailable, unreported, unsought and lost material. Cochrane [chapter 13](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-13) is a best-known-line candidate for these missing-evidence questions; its meta-analysis tools retain that scope. New eligible material, an identified selective omission or a stronger model of its effect reopens the affected finding.

**How can situated and mixed findings be related?** The selected line preserves context and finding-specific confidence, integrating transformed contributions only when they answer a shared question. The serious rival is separate synthesis of all quantitative and qualitative contributions; a different default would merge everything into one theme. Cochrane [chapter 21](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-21) supplies a best-known qualitative line and the separate-contribution choice; JBI [§8.3](https://jbi-global.atlassian.net/wiki/spaces/MANUAL/pages/355829259/8.3%2BThe%2BJBI%2Bapproach%2Bto%2Bmixed%2Bmethod%2Bsystematic%2Breviews) supplies the serious question-relative integration alternative. **Adapt:** 4.4 and 5.3 select between them by the question. This permits a useful shared answer while keeping different aspects separate and transformation losses recoverable. [GRADE-CERQual](https://www.cerqual.org/what-is-the-grade-cerqual-approach2/) supplies an applicable finding-level confidence candidate, not a numerical truth scale. The accepted cost is explicit interpretation and method choice. A changed tradition, question or stronger account of what transformation loses reopens the comparison.

**What can historical agreement establish?** The selected line compares source dependence, dating, purpose, contrary material and rival explanations. Narrative count is an attractive cheap default, but copied accounts cannot supply independent causal support. **Adapt:** 4.2–4.4 and 5.4 recover the shared memoir and the different contribution of the decision record. AHA [professional standards](https://www.historians.org/resource/statement-on-standards-of-professional-conduct/) supplies the best-known-line candidate for source integrity and evidence/interpretation discipline here; it supplies no verdict about the particular factory. The extra source criticism preserves the useful chronology while leaving the unsupported cause open. New provenance, dating or a substantive rival explanation reopens that inference.

These comparisons support different research traditions. Their combination here is question-relative guidance, not evidence that one synthesis procedure works universally.


## RMP.7:End {#end}
