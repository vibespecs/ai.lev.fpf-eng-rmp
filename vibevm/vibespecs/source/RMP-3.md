# RMP.3 - Operationalize the Research Design without Replacing the Question: depth {#depth}

<status stage="spec" state="work"/>

> Source: Anatoly Levenchuk, *Research Method Practice Principles Framework* (27 September 2026), `Engineering DPF Suite/RESEARCH-METHOD-PRACTICE-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## RMP.3:5 - Archetypal Grounding {#archetypal-grounding}

The following cases are constructed examples with supplied domain premises. Their identifiers and counts illustrate records and dependence; they are not recommended sample sizes, scientific thresholds or performed studies.

### RMP.3:5.1 - Pump-P4: from a mechanism question to an executable comparison {#pump-p4-from-a-mechanism-question-to-an-executable-comparison}

The brief asks whether the accelerated condition preserves the field seal-degradation mechanism within a specified material/fluid envelope. The selected design compares accelerated and field-representative conditions. Assume the domain owner supplies a valid mechanism marker, qualified measurement procedure, safe conditions and an adequate specimen plan.

The team adds these entries to its existing protocol:

| Protocol choice | Question-relative reason and required record |
| --- | --- |
| Give each seal a specimen ID and retain its material batch and assigned condition. | The comparison concerns degradation under the two conditions; material and allocation must remain recoverable. |
| Measure the supplied mechanism marker at the design's specified exposure points with the qualified procedure. | A difference must bear on mechanism, not merely on total visible wear. Retain the procedure version, calibration basis, time and uncertainty. |
| Treat three readings from one seal as repeated observations of that seal. | Repetition can characterize measurement variation; it does not triple the independent specimen count in the supplied comparison. |
| Preserve missing observations and departures before preparing the comparison data. | A critic needs to distinguish material behaviour from allocation, handling and selection effects. |

This is an operationalization of the selected design because each choice preserves the mechanism question and names the material needed to challenge it. The team does not obtain permission or a maintenance decision merely by completing the protocol.

Now change one premise: the measurement owner reports that the marker cannot distinguish thermal degradation from the competing field mechanism under these conditions. The appropriate result is an RMP.2 return carrying that report and the lost discrimination. Substituting a more convenient wear score would require a justified new evidence relation. The brief and unaffected specimen information can remain useful.

On the valid-marker branch, specimen P4-07 is later damaged in handling before an observation. The protocol's planned missingness treatment tells the team what intention to consult; RMP.4 records what actually happened and what was decided. Whether the remaining data support an inference is a later analytical question.

### RMP.3:5.2 - ResidentStream-S17: a missing comparison is not a scheduling detail {#residentstream-s17-a-missing-comparison-is-not-a-scheduling}

Residents have a compatible brief and a selected spatial-temporal comparison of salinity-related observations. The measurement and site owners supply a valid method, the calibration and uncertainty basis, permissible access and a feasible plan for informative hydrological conditions.

The operational specification identifies the reach and sampling point, the condition triggering the observation, the time relation between reaches, the qualified measurement result to obtain, and the weather, access and calibration records needed to interpret the comparison. A laboratory may supply the measurement result; residents need not recreate its internal Method.

If the reference reach becomes inaccessible during the informative thaw event while downstream observations remain possible, the original paired comparison has lost a required observation. Record the site, period and access failure, preserve the downstream material, and return to RMP.2. A later dry-weather reference is a different comparison premise, not routine completion of the old schedule. A narrower use can proceed only under the question/design that justifies it.

## RMP.3:6 - Bias-Annotation {#bias-annotation}

Operational choices determine whose cases and which phenomena become visible. Inspect convenience sampling, survivorship, accessible-source bias and exclusions that protect a favoured explanation. A well-documented restriction can remain an answer-changing bias.

Also inspect the researcher's position. Prompt wording, relationships, technical competence and access can shape encounters and interpretations. Preserve the contribution that matters to the chosen approach; do not impose one philosophy of interpretation or universal coder-agreement requirement.

Instrument familiarity and organizational pressure favour choices that are easy to execute and report. Ask whether an inconvenient rival would still be observable under the completed arrangement. In mixed inquiry, check whether apparently different components rely on the same selected cases or assumptions.

## RMP.3:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Failure | Why it fails | Repair |
| --- | --- | --- |
| “We use the standard scale.” | Familiarity conceals whether administration, scoring or the construct relation fits this inquiry. | Recover the qualified relation and actual use; obtain a domain result or return the defeated design premise. |
| Three readings become three specimens. | The information claim silently changes its unit and dependence. | Keep observation and inference units distinct and use the applicable sampling and analysis rationale. |
| A completed reporting checklist is treated as a justified protocol. | Reporting detail cannot select or validate the research relation. | Connect each consequential choice to the question and supplied Method. |
| Every adaptation is either forbidden or hidden. | The first suppresses legitimate inquiry; the second removes criticism of selection and timing. | State justified commitments and preserve actual reasons, timing and scope of change. |
| A lost comparison is annotated but its original claim survives. | The record becomes more transparent while the design remains defeated. | Return the failed dependency to RMP.2 and identify what narrower work is still supported. |
| Each remaining need is tested with all others favourable. | The combined arrangement may be infeasible or incapable of criticism. | Apply the joint-input test to admissible combinations. |
| The protocol substitutes for permission or a scientific conclusion. | Research preparation does not supply either result. | Obtain the exact owner decision or the later analysis and criticism. |

## RMP.3:10 - Architectural Rationale {#architectural-rationale}

Separating design selection from operationalization protects two useful decisions. RMP.2 can compare evidence strategies without pretending every local detail is settled. RMP.3 can make one selected strategy executable without being allowed to change its criticism silently. The joint-input condition connects them: unresolved details are acceptable only inside the selected design's admitted bounds.

The operational specification and the actual trace remain distinct because an intention and an account of conduct answer different questions. They can occupy one notebook and can develop together. RMP.4 also supports inherited work whose prospective specification no longer exists.

The cheaper alternative is often best: use a competent domain protocol and adequate records directly. The RMP contribution is needed when the question-to-operation connection, change consequence or research-use limitation remains unresolved. A universal form would add burden while obscuring differences among measurement, interpretation and source criticism.

## RMP.3:11 - SoTA-Echoing {#sota-echoing}

**Practice question.** How much and what kind of advance specification preserves a research question while allowing the inquiry its justified flexibility?

**Selected line.** Adapt question-relative, method-sensitive specification with inspectable commitments and amendments. Compared with either a universal protocol checklist or an unrestricted evolving notebook, this preserves both methodological fit and the timing needed for criticism. It deliberately requires reasons for consequential choices; it does not require more documentation where an adequate domain protocol already supplies them.

| Comparison and source role | Adopt, adapt or reject; effect on the Method and limit |
| --- | --- |
| Flake and Fried's [Measurement Schmeasurement](https://doi.org/10.1177/2515245920952393) is a methodological candidate against unexplained measure selection. Goos et al.'s [2026 measurement study](https://doi.org/10.1371/journal.pone.0356070) supplies bounded failure evidence from Many Labs measures. | **Adapt** the recoverable construct–measure relation and actual administration/scoring choices in §4.2. Reject publication or replication status as sufficient qualification for a changed measurement use. The sources neither validate the local instrument nor establish a universal research failure rate. |
| Lakens's [Sample Size Justification](https://doi.org/10.1525/collabra.33267) compares quantitative justifications tied to inferential aims and constraints. | **Adapt** its question-relative rationale in §4.2. Reject an unexplained inherited count and the treatment of a resource-limited sample as automatically sufficient. Applicable statistical calculations remain supplied Methods; power analysis is not a universal standard for qualitative or historical adequacy. |
| [SPIRIT 2025](https://www.bmj.com/content/389/bmj-2024-081477) is a bounded reporting comparator; [TOP 2025](https://www.cos.io/initiatives/top-guidelines) distinguishes registration, protocol and analysis-plan practices. | **Adapt** consequential specification and separate timed commitments in §§4.2–4.4. Reject the checklist or preregistration label as proof of design quality. Trial-specific objects apply where that design has them, not to every inquiry. |
| Haven et al.'s [qualitative preregistration study](https://doi.org/10.1177/1609406920976417) supplies a candidate starting account. Braun and Clarke's [RTARG argument and review](https://doi.org/10.1177/02692163241234800) challenges generic qualitative reporting and assessment defaults. | **Adapt** explicit starting commitments with approach-appropriate evolution in §4.4. Reject universal pre-data freezing and universal coder agreement. The Delphi consensus and reflexive-TA critique do not establish one procedure for all qualitative traditions. |
| AHA's [professional standards](https://www.historians.org/resource/statement-on-standards-of-professional-conduct/) and the [Cochrane Handbook, chapter 2](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-02) supply source-critical and question-led selection comparators. | **Adapt** provenance, contrary material and question-relative selection in §§4.2 and 4.4. These practices cannot restore a lost archive or supply the actual historical or synthesis conclusion. |

The combined arrangement is a reasoned methodological synthesis, not a demonstrated universal improvement over every research practice. Reopen the affected choice when a changed construct, approach, source corpus or access condition defeats its research connection, or when a better domain procedure preserves that connection and its criticism with less burden.


## RMP.3:End {#end}
