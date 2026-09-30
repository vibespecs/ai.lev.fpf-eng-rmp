# RMP.1 — Decide Whether a Question Needs Research and When to Stop: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Research Method Practice Principles Framework* (27 September 2026), `Engineering DPF Suite/RESEARCH-METHOD-PRACTICE-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## RMP.1:5 - Archetypal Grounding {#archetypal-grounding}

All cases below are constructed pedagogical cases. Their stipulated facts demonstrate the boundary method; they are not empirical claims about an actual pump, stream, archive, instrument, or authority.

### RMP.1:5.1 - Corporate Seal-Test Case {#corporate-seal-test-case}

A reliability engineer is asked to “research whether an accelerated seal test justifies changing the maintenance interval” for Pump-P4. The maintenance authority, safety owner, and domain engineering owner remain separate from the inquiry.

First apply the cheap branch. If the current engineering frame already supplies a qualified field failure mechanism, an applicable acceleration relation, a qualified test Method and instrument, acceptance criteria, and the exact evidence-to-use rule, then executing that test is routine qualification or validation. Return its test result to the engineering or assurance owner and the interval choice to the maintenance authority. The laboratory setting and possible publication do not make the Work research.

Suppose instead that the qualified current frame exposes this unresolved issue: the proposed high-temperature condition may change the dominant degradation mechanism, while installation damage and fluid exposure remain serious field rivals. A passing ResearchQuestionBrief can then read:

| Position | Constructed result |
| --- | --- |
| receiver and use | Reliability council needs evidence about whether the accelerated-test result can bear on the current seal-life claim. The maintenance authority retains the interval decision. |
| intended episteme change | Retain, narrow, or reject the claim that degradation observed under the selected accelerated condition is evidentially relevant to Pump-P4 field failure within the named operating envelope. |
| bounded question | Within the named Pump-P4 material, fluid, pressure, and temperature envelope, does the selected acceleration condition preserve the field failure-mechanism relation well enough for its degradation evidence to bear on the current seal-life claim? |
| current frame and rivals | Current sources support the field claim only provisionally. Acceleration-induced mechanism change, installation damage, batch/material variation, and field fluid exposure remain serious alternatives. |
| membership account | The relation is unresolved for the use; choosing how to distinguish mechanisms is non-routine; the intended Work can preserve sources, specimens, conditions, measurements, deviations, and limits; and the intended result is a bounded mechanism-to-evidence claim. |
| criticism demand | A defensible answer must be able to expose a mechanism change caused by acceleration and distinguish it from the named field rivals. RMP.1 does not choose the comparison or instrument. |
| constraints and returns | Domain engineering supplies admissible mechanism indicators and specimen identity; instrument owners supply feasibility and calibration; safety and access owners retain authority. Missing load-bearing results return to those owners. |
| answer condition | Establish whether the selected acceleration condition preserves the mechanism relation needed for the bounded seal-life claim. Qualified evidence can support, narrow or reject that relation; identifying a still-missing decisive result leaves it unresolved. |
| work-stop and reopen conditions | Finish with the supported answer or return the unresolved relation and its decisive missing result. RMP.2 distinguishes a still-needed selection from a completed allocation with no new study. A newly available result or worthwhile obtainable comparison can reopen that choice. The maintenance authority retains the interval decision. |

This case enters RMP.2 only with that brief and frame. If current retrieval already establishes that the acceleration relation is invalid for the named use, return that exact result and stop; a new study is not required merely to make the answer look experimental.

### RMP.1:5.2 - Citizen Stream-Salinity Transfer {#citizen-stream-salinity-transfer}

A resident team without academic affiliation observes an urban-stream salinity increase. If it is applying an established sampling Method, threshold, and response rule to report current state, return the observation to the domain monitoring owner. Repeated sampling and a public dashboard do not by themselves establish research.

Suppose a qualified current frame instead leaves sensor drift, road-salt transport, groundwater contribution, a changed outfall, and seasonal hydrology as serious rivals, and the community needs a bounded explanation for a named reach and period. The question may pass all four conditions: the explanation is unresolved for the use; the source, site, and comparison choices are non-routine; samples, instruments, conditions, exclusions, and interpretations can be traced and criticized; and the intended result is a communicable claim with limits rather than only an alert.

The brief names the reach, period, observations, relevant contrasts, source/currentness limits, rival accounts, criticism demand, safe access and sampling constraints, useful stop, and the public or operational receiver. Site permission, laboratory competence, environmental safety, privacy, and official response authority remain with their owners. Citizen status neither weakens nor strengthens membership. If the sensor is found invalid before the question can be qualified, return measurement repair or monitoring Work; do not hide the missing measure inside a research label.

### RMP.1:5.3 - Historical Source-Critical Contrast {#historical-source-critical-contrast}

A local archive group asks whether a change in maintenance practice followed one directive or emerged earlier across workshop records. The question can be research without an experiment and without academic affiliation when the current frame is incomplete, rival chronologies matter, source provenance and silences need non-routine criticism, the trace is inspectable, and the result is a bounded historical claim. If one current authenticated record already answers the narrow date question, return that source result instead. Access, rights, conservation, and institutional interpretation authority remain external.

### RMP.1:5.4 - Retrieval-Sufficient Stop {#retrieval-sufficient-stop}

A product team asks to “research whether the current standard still permits configuration X.” A current question-relative source cut, needed source-local meanings, and exact evidence-use path establish the applicable edition and clause for that use, including its jurisdiction and effective-date limits. RMP.1 returns the answer and those source limits in the current exchange; the card ends at prompt 3. No membership account, interviews, survey or test is needed to complete that question.

A later team receives the answer for a proposed use in another jurisdiction. The retained edition, clause and jurisdiction limit show what the answer covers and make the new applicability question explicit. Obtain the missing applicability result from its competent source; the earlier answer does not become universal and the changed use does not by itself commission research. If the team instead disputes the clause's empirical adequacy for a materially new case, that new question needs its own current frame and four-condition test.

### RMP.1:5.5 - Recover an Answer from the Texts {#recover-an-answer-from-the-texts}

A product team asks to research whether instruction M still permits configuration X on housing V2. It has a 2021 instruction, the 2025 revision and a 2025 correction notice. All are stipulated source texts for this constructed case.

Searching the old instruction for "permitted configurations" returns X for V1. The new contents instead use "installation combinations"; its table lists X with V2. The adjacent note limits that row to dry service. The correction notice changes a different combination. Reading the table and its note changes the answer from "only V1" to "the 2025 instruction includes X with V2 for dry service." The answer identifies the edition, table and note. No experiment is needed to establish what that instruction says.

The team then reveals that it means wet service. The earlier answer remains useful within its dry-service scope; it does not resolve this new applicability question. The next useful result is the applicable instruction or an engineering judgement about wet service. If the team instead asks whether the instruction's claim holds in a materially new operating setting, qualify that empirical question under the four conditions before choosing a study.

### RMP.1:5.6 - Compare the Answers that Existing Reports Can Supply {#compare-the-answers-that-existing-reports-can-supply}

Return to the seal-test question in §5.1. One stipulated report supports a temperature-acceleration relation for a named material in water. A later report concerns another fluid and reports a different dominant degradation mechanism. Both are relevant to the receiving question; their different conditions prevent a direct ranking by publication date or test duration.

The comparison retains the first report's supported relation in water and the second report's warning about mechanism change in the other fluid. It changes "Which report gives the best acceleration factor?" into "Does the proposed test preserve the field mechanism for our material and fluid?" If an applicable existing study answers that question, return its answer and stop. Otherwise the remaining mechanism question and the criticism it requires become inputs to the research-membership test. A new study is chosen only through the subsequent design decision.

## RMP.1:6 - Bias-Annotation {#bias-annotation}

| Recurring bias | Likely drift | Repair |
| --- | --- | --- |
| institutional-status bias | Academic employment, a grant, or a journal is treated as necessary or sufficient. | Apply the same four conditions to corporate, public, independent, academic, and citizen holders. |
| activity-label bias | Searching, testing, measuring, interviewing, coding, or publishing is classified by appearance. | Recover the intended episteme change, uncertainty, criticism, trace, and return. |
| novelty-to-me bias | Missing personal knowledge is called a novel question. | Qualify the current frame and attempt the supplied-answer stop first. |
| favored-answer bias | The desired conclusion sets the question and source cut. | State materially different answers and the criticism that could defeat or narrow the favored claim. |
| protocol bias | Use of a standard protocol is treated as creativity and systematicity. | Ask whether a non-routine choice remains and whether the trace connects question to criticism and return. |
| uncertainty inflation | Schedule, access, process variance, or ordinary execution risk is called epistemic uncertainty. | Name the exact unresolved claim or return the operational constraint to its owner. |
| data-volume bias | More observations are assumed to create a better question. | Define the answer-changing contrast and useful stop before requesting more data. |
| publication bias | Communication through a recognized carrier is treated as proof of research or truth. | Inspect the Work and result relations; keep publication and recognition separate. |
| openness absolutism | Unrestricted release is made a membership condition. | Require a criticism-ready trace and bounded communicability while preserving ethics, rights, confidentiality, safety, security, and community governance. |
| authority leakage | Evidence production is allowed to choose maintenance, policy, release, or personal action. | Name the receiver and use while leaving the decision and values with their direct owner. |
| AI/tool bias | Tool sophistication or fluent synthesis substitutes for source verification and criticism. | Recover exact sources, transformations, human/tool contributions, unsupported claims, and limits. |

## RMP.1:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

| Anti-pattern | Why it fails | Repair |
| --- | --- | --- |
| “Everything uncertain is research” | Operational uncertainty may contain no unresolved knowledge claim. | Name the exact episteme change or return the constraint to its owner. |
| “Research happens only in research institutions” | Institution is neither a necessary nor a sufficient relation. | Apply the holder-neutral four-condition test. |
| “A literature search is the study” | Retrieval may already answer the question, or it may be only one supplied input. | Return the exact source result or form a separate criticism-bearing question. |
| “Choose the method, then write the question” | A favored apparatus or design can manufacture its own problem. | Qualify the frame, episteme change, and criticism demand before RMP.2. |
| “Run the standard test to be safe” | Routine qualification can be useful without being research. | Return the test result to its domain owner; reopen only on an unresolved mechanism, validity, transfer, or evidence question. |
| “Systematic means a checklist exists” | Administrative regularity does not make a defeasible question-to-return chain. | Preserve premises, performed moves, deviations, evidence, limits, and stops. |
| “No source result, so explore freely” | A missing load-bearing frame prevents honest membership and question qualification. | Return the exact source/currentness/comparison need and retry condition. |
| “One scientific method fits every question” | Historical, qualitative, observational, computational, experimental, and synthesis questions expose unlike errors. | State the criticism demand here and let RMP.2 compare design families. |
| “The research result decides the action” | Evidence relevance does not transfer values, permission, or authority. | Return the bounded episteme contribution to the receiving owner. |
| “Not research” | The label discards useful routing and hides reopen conditions. | Return the expected result, owner, available material, and exact retry condition. |
| “Apply Frascati as a legal or prestige gate” | Its R&D-statistics purpose and sector rules do not define all holder-neutral research practice. | Use the five criteria as explicitly adapted assurance questions with stated limits. |

## RMP.1:10 - Rationale {#rationale}

The four conditions separate the reason to inquire from the activity used. Unresolvedness prevents personal ignorance from masquerading as novelty. Non-routine choice distinguishes epistemic design from ordinary Method execution. Criticism-ready systematicity makes defeat and narrowing possible. A bounded communicable result distinguishes an episteme contribution from an immediate action, token, or private update.

The supplied-answer stop has equal standing with the passing branch. Research is not improved by repeating a question that qualified current evidence already answers. Exact non-member returns avoid the opposite error: adjacent practices remain valuable and can reopen RMP.1 when they expose a new mechanism, validity, transfer, measurement, source, or evidence question.

Beginning with the receiver but withholding its authority preserves relevance without advocacy capture. Stating the criticism demand before design comparison prevents a favored apparatus or prestige hierarchy from choosing the question.

## RMP.1:11 - SoTA-Echoing {#sota-echoing}

The working question is: **How can a practitioner distinguish a genuine criticism-bearing research question from adjacent professional Work without making institutional status or one universal design the gate?**

The selected current line adapts the five criteria in the OECD's [Frascati Manual 2015](https://doi.org/10.1787/9789264239012-en)—novel, creative, uncertain, systematic, and transferable and/or reproducible—while respecting that the Manual is principally a methodology for R&D statistics. RMP.1 mutates “novel” into unresolved relative to a qualified frame and use, “creative” into a non-routine epistemic choice, “uncertain” into uncertainty about the answer or defensible route, “systematic” into a criticism-ready trace, and “transferable/reproducible” into a bounded communicable contribution that does not force every inquiry into replication or universal generalization.

UNESCO's [Recommendation on Open Science](https://www.unesco.org/en/legal-affairs/recommendation-open-science) supports participation by citizen and community actors and recognizes research contributions beyond a narrow institutional holder. RMP.1 uses that line to remove affiliation as a membership condition. It does not turn unrestricted openness into a requirement: ethics, safety, rights, confidentiality, security, access, and community authority continue to govern what may be done or shared.

A serious alternative is an institutional or activity-list gate: classify Work by employer, funding, venue, laboratory setting, publication intent, or use of familiar “research methods.” That gate is cheap to administer but creates both false positives and false negatives and cannot tell a routine test from a mechanism challenge. RMP.1 retains those features only as discovery cues and decides membership from the question, route uncertainty, criticism-ready trace, and intended episteme return.

These sources do not decide claim truth, supply domain instruments, authorize Work, or identify one universal design. Reopen this pattern's boundary claims when a stronger cross-sector research-classification source changes a criterion, when evidence shows that one condition misroutes a design family or holder, or when a source/currentness rule changes the qualified-frame result. Reopen only the affected claim or return, not every prior use.


## RMP.1:End {#end}
