# RMP.1 — Decide Whether a Question Needs Research and When to Stop {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Research Method Practice Principles Framework* (27 September 2026), `Engineering DPF Suite/RESEARCH-METHOD-PRACTICE-PRINCIPLES-FRAMEWORK.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

> **Type:** Research Method Practice practitioner method pattern


## RMP.1:0 - Use This When {#use-this-when}

Use this pattern when a practitioner receives a request to research an issue and needs to decide whether existing knowledge is enough or a new study is needed. Begin with the question, its intended use and the available material. Use a suitable existing source answer, or prepare one through §4.3, and stop when it is sufficient. If the request belongs to routine professional work, use §4.4 to identify the needed result and who can supply it. Produce a **ResearchQuestionBrief** only when all four research-membership conditions pass.

Recognition cues include a favored answer looking for support, a request for “more data,” a surprising observation, a test whose relation to field use is disputed, a literature search that may already be sufficient, or a question that survives routine recovery. These cues justify opening the boundary question; they do not establish research. Affiliation, job title, grant, venue, publication plan, tool choice, or information collection establishes none of the four conditions.

The practical gain is an answer from existing knowledge or a research question that states what remains to be learned and when enough has been learned. Use `RMP.2` only after a compatible `ResearchQuestionBrief` and qualified current frame exist and the design disposition is still open.

Do not use RMP.1 to select a research design, prescribe an instrument, authorize access or risk, decide an engineering or policy action, or repair a reusable professional Method. Those decisions remain with their direct owners.

## RMP.1:0.1 - Working Terms {#working-terms}

| Name in this pattern | What it denotes |
| --- | --- |
| receiving question and use | The practical or epistemic question for which an answer may matter, the receiver who needs it, and the bounded use the receiver proposes. The receiver retains value and decision authority. |
| qualified current frame | An account of what the sources support for the receiving question, the conditions under which they apply, and which important alternatives or gaps remain. It may be supplied or prepared through §4.3. |
| unresolved knowledge question | A question whose materially different answer or criticism could revise, retain, reject, narrow, or add an exact episteme for the named receiving use. Novelty to the performer alone is insufficient. |
| criticism demand | The kind of error, rival explanation, invalid source use, dependence, bias, missing context, or unsupported transfer that a defensible answer must be able to expose. It states what has to be challenged; it does not preselect a design. |
| answer condition | What the evidence must establish to answer the bounded question for its intended use, with the uncertainty that use permits. |
| useful stop | Completion with an adequate answer, or completion of the present work with a refusal, retained uncertainty or a missing-input return. In the latter case, state which answer condition remains unmet and what could reopen the work. |
| ResearchQuestionBrief | The passing RMP.1 result: a bounded question, current frame, intended episteme change, criticism demand, constraints, answer condition, work-stop and return conditions suitable for RMP.2. It is not a protocol or completed design. |
| exact supplied-result return | A current source, comparison, evidence-use, or retrieval result that already answers the receiving question within its stated scope and limits. It exits RMP.1 without asserting new research Work. |
| exact non-research return | The question, available material, expected result kind, direct owner, and reopen condition for adjacent Work such as qualification, monitoring, troubleshooting, audit, evaluation, or ordinary Method application. |
| research-boundary hold | A named missing or stale source/result, the question it prevents RMP.1 from deciding, its owner or supplier interface, and the condition for retry. “More research needed” is not a hold specification. |

Work that changes an episteme and Work that changes an operating, physical, social, or administrative state can be connected, but they are not the same Work. A research result may inform a later action; it neither performs nor authorizes that action.

## RMP.1:1 - Problem Frame {#problem-frame}

Many activities appear on both sides of the research boundary. A laboratory test can execute an already qualified engineering Method or challenge the mechanism that makes the test relevant. Repeated stream measurements can implement routine monitoring or investigate an unexplained pattern and rival causes. Reading sources can retrieve an already available answer or form one part of a criticism-bearing synthesis. Interviews can support routine evaluation or a situated inquiry whose interpretations and negative cases remain open.

The boundary is therefore relational. It depends on what is unresolved relative to a qualified current frame, what episteme may change for which use, which non-routine choice and criticism are required, how the Work will remain inspectable, and what kind of result will be returned. Neither a prestigious venue nor an informal citizen setting changes those relations.

A useful entry pattern must be permissive enough to inspect an ambiguous request and strict enough not to relabel every uncertainty as research. It must also preserve a cheap exit: if current source work already answers the question, starting a new study is a defect, not diligence.

## RMP.1:2 - Problem {#problem}

Activity lists and institutional labels create false positives: searching, measuring, experimenting, coding, surveying, or publishing is treated as research even when it only applies a qualified Method or returns an established result. Institutional gates create false negatives: independent practitioners and community groups are excluded even when they pose a genuine unresolved question and preserve a criticism-ready trace.

A vague “not research” answer is no better. It strands useful Work without identifying the result that is actually needed, the owner who can supply it, or the condition under which a knowledge question would reopen. A vague “needs more research” answer hides the same defect in the opposite direction.

Without a useful stop, the topic expands indefinitely. Without a qualified current frame, novelty means only “new to me.” Without a named receiving use, a question can accumulate evidence without ever stating what episteme change would be useful. Without a criticism demand, a favored answer can dictate the search.

## RMP.1:3 - Forces {#forces}

- A broad topic is easy to announce, while an answerable question needs a named receiver, phenomenon, unit or case, contrast, constraints, and stop.
- A quick source answer saves Work, while a weak or stale source cut can create false closure.
- A familiar protocol feels systematic, while routine execution does not establish an unresolved knowledge question.
- A surprising observation can open inquiry, while surprise to one performer is not qualified novelty.
- A concrete decision motivates research, while research must not inherit the receiver's value or authority.
- Criticism must be planned early enough to matter, while selecting the actual design belongs to RMP.2.
- Traceability supports inspection, while a checklist or repeated measurement alone does not make Work research.
- Communicability makes a result criticizable, while publication, unrestricted openness, and institutional recognition are not membership conditions.
- Holder-neutral access admits corporate, public, independent, and citizen practice, while ethics, safety, rights, confidentiality, access, and domain competence remain binding.

## RMP.1:4 - Solution {#solution}

Start with the receiving question and attempt a sufficient answer from existing material. Use the four membership conditions when a knowledge question remains unresolved. Return the answer in the current exchange or work product; create a ResearchQuestionBrief only when all four conditions pass.

### RMP.1:4.1 - Pattern-Use Unfolding {#pattern-use-unfolding}

1. **Fix the receiver and use.** Name who needs an answer, the exact claim, model, corpus contribution, or explanation that could change, the action or later inquiry for which it may matter, and the owner of that later decision. Keep the proposed evidence use separate from permission, release, safety, policy, maintenance, or adoption authority.
2. **Find what existing material can answer.** Reuse an applicable source answer when one is available. Otherwise follow §4.3 from the question and accessible texts: locate relevant passages, recover their meaning and applicability, and show what they change in the answer. Compare alternatives when their differences could change that answer or the need for a study.
3. **Try the source-answer stop.** If the material resolves the receiving question within its intended scope, return the answer with the sources and limits needed to use it, and stop. Use the remaining steps when a research question survives.
4. **Form the candidate episteme change.** State what exact claim or corpus contribution could be retained, narrowed, rejected, qualified, or added. Name the phenomenon, unit, case, population or corpus, relevant relation or contrast, constraints, and smallest useful answer. A topic, task label, desired conclusion, or data-collection plan is not yet a research question.
5. **Apply the four conditions independently.** Establish unresolvedness, non-routine choice under genuine uncertainty, a systematic criticism-ready trace, and a bounded communicable episteme return. All four must pass. Record why the nearest plausible non-member does or does not fit.
6. **Name the criticism demand, answer condition and work stops.** Identify the error or rival that a useful answer must be able to expose, without choosing a design family. State what the evidence must establish for this use, which result would defeat or narrow the proposed claim, and what remains outside the inquiry. Separately state when the present work can finish with uncertainty, refusal or a missing-input return, for example because further inquiry lacks value or authority. Such a stop preserves any unmet answer condition.
7. **Return one exact disposition.**
   - return the already-sufficient source/result and stop;
   - return the adjacent non-research Work and its expected result to its direct owner;
   - return a research-boundary hold naming the unavailable source or owner result and retry condition; or
   - when every condition passes, return a ResearchQuestionBrief to RMP.2.
8. **Preserve later authority.** The brief says why an episteme change may matter. It does not choose the receiving action, select a design, authorize Work, or promise that the answer will support the desired decision.

### RMP.1:4.2 - Four-Condition Research-Membership Test {#four-condition-research-membership-test}

| Condition | Passing question | Does not pass | Reopen cue |
| --- | --- | --- | --- |
| unresolved relative to a qualified frame and named use | Could a materially different answer or criticism revise, retain, reject, narrow, or add an exact episteme used by the named receiver? | The fact is merely new to the performer, the topic is interesting, or qualified retrieval/current-best work already supplies the answer. | A current source gap, serious rival, source limitation, or changed receiving question makes the exact episteme unresolved again. |
| non-routine design, interpretation, synthesis, or credibility choice under genuine uncertainty | Is the answer or defensible route not predetermined, and must a non-routine choice be justified against alternatives? | The Work executes an already qualified Method with supplied variables, criteria, and interpretation; only schedule, process variance, or execution risk is uncertain. | Method fit, an underlying mechanism or validity claim, or a materially new case becomes unresolved and can change the criticism logic. |
| systematic and criticism-ready | Can a critic recover the sources, premises, intended and performed moves, evidence, deviations, limits, and stops, and defeat or narrow the claim? | A checklist is completed, measurements are repeated, or records are stored without an inspectable question-to-return chain. | A recoverable trace and a defeasible claim can now be formed for the unresolved question. |
| bounded communicable episteme contribution | Is the intended result an inspectable claim or corpus contribution with applicability, limits, and a named return? | The only intended result is an immediate control action, compliance token, product acceptance, institutional recognition, private belief, or unbounded “knowledge.” | A bounded episteme change is stated separately from the later action or recognition. |

These are assurance questions for membership. Recognition cues—such as an experiment, a literature review, a laboratory, a surprising graph, an academic affiliation, or the word “research”—cannot substitute for any row.

### RMP.1:4.3 - Answer from Existing Sources before Starting a Study {#answer-from-existing-sources-before-starting-a-study}

Use this route when the question has arrived before a suitable source answer. A supplied answer can be used directly when its question, sources and applicability fit the present use. The purpose here is to establish what remains to be investigated.

#### RMP.1:4.3.1 - Find and interpret the relevant material {#find-and-interpret-the-relevant-material}

1. **Say what answer is needed.** Restate the difficulty in the receiver's terms and say how an answer could change the next action. Use the texts and search facilities available; consider time or specialist help when they limit what you can resolve. Clarify a difference in the question before spending effort on the wrong one.
2. **Locate passages that can answer it.** Start with the available texts, their contents and their own terminology. Search the words used in the question and likely synonyms; follow a relevant passage to its definitions, conditions, examples or cited basis when they affect the answer. Use F.1 to choose sources by what their claims or limitations contribute. If one identified source already answers the question, use it directly.
3. **Repair the reading where needed.** When a search misses expected material, try another expression or source. Read a found passage with the surrounding context needed to interpret it; F.0.1 helps recover a consequential expression's local meaning. A correctly understood passage may concern a different population, setting or use. State that difference and seek the material needed for this question. Show the corrected answer so the receiver can tell what the repair achieved.
4. **Return what the sources support.** Explain the answer and point to the passages and editions on which it depends. Keep omissions and uncertainty that affect its use visible. A.10 supplies the claim-bound source and provenance relations. If the answer is sufficient, stop. The explanation already being used may carry the whole result; a separate retrieval log is needed only when reproducing or diagnosing the search is itself part of the work.

A missing text, unknown edition or unresolved applicability limits the conclusion that depends on it. Preserve the answerable remainder and say which source or competent contribution would resolve the remaining question. Further search is useful when its possible answers could change the receiving use; the presence of an unanswered question alone does not prescribe a new study.

#### RMP.1:4.3.2 - Compare alternatives when their difference matters {#compare-alternatives-when-their-difference-matters}

Use this branch when existing sources offer materially different answers, or when the receiver needs the best-known current answer. Begin with the working question and the criteria that matter for its use.

Select sources by their answer-changing roles in F.1. When the result claims a best-known current answer, apply the stricter source comparison in F.1:4.2.1 and E.8:11, including serious alternatives, relevant failure evidence and application effort. A recent publication or a history of adoption can help identify a source without establishing that preference.

For each proposed answer, recover its assumptions, conditions and support. When an approach claims an improvement over earlier work, compare the limitation it repairs with those it retains. Consult the earlier source when that comparison needs it; keep historical influence distinct from evidence that the present answer works. State a trade-off when the answers improve different characteristics. The comparison may finish by identifying a question whose answer would distinguish the alternatives.

Say what this comparison changes: the answer, its applicability, the remaining research question or the useful stop. If establishing a new conclusion from a body of research requires appraisal and synthesis, use RMP.7 with its needed question and design. F.0.2 applies when the actual work is conceptual synthesis for a framework-authoring decision. A broader G.2 pack is useful when its declared CG-Frame and repeated-refresh use is needed. These are conditional continuations; a sufficient comparison can finish here.

### RMP.1:4.4 - Nearest Non-Members and Exact Returns {#nearest-non-members-and-exact-returns}

| Nearest non-member | Exact return | Reopen RMP.1 only when |
| --- | --- | --- |
| routine engineering qualification, verification, or validation under a qualified Method and supplied criteria | Return the test or qualification result to the domain engineering or assurance owner and the choice to its receiving authority. | A qualified frame exposes an unresolved mechanism, validity, transfer, or evidence question requiring a new criticism-bearing design. |
| routine monitoring or measurement against established variables, thresholds, and response rules | Return the observation or current-state result to Operations or the domain monitoring owner. | An unexplained pattern, rival causal account, invalid measure, or transfer question changes the epistemic task. |
| troubleshooting, incident response, or fault isolation aimed at restoring one operating result | Return the diagnosis and recovery result to the domain engineering, service, or Operations Method. | A knowledge question survives the recovery, matters beyond the episode, and passes all four conditions. |
| audit, compliance assessment, programme evaluation, or product acceptance against supplied criteria and authority | Return the verdict, evaluation, or acceptance result to the audit, governance, assurance, evaluation, or receiving-domain owner. | The validity of criteria, causal interpretation, transfer, or evidence claim itself becomes unresolved. |
| source retrieval, currentness checking, or bounded cross-source comparison sufficient for the use | Return the answer and the source, applicability and comparison limits needed by its receiver, using §4.3. | A material source gap or a new question changes what that answer can establish. |
| application of an already qualified professional Method to produce its ordinary domain result | Return the Work to that Method and domain owner. | Method fit, an underlying claim, or a materially new case creates the four-condition question. Repair of reusable Method identity, qualification, fit, trial, worth, or variants remains with Method Engineering. |

For adjacent Work or a missing result, carry forward the exact question, available material, expected result kind, owner, and reopen condition so useful Work can continue. A supplied answer returns to its receiver as a completed answer; it does not need a next owner task.

### RMP.1:4.5 - Record the Result {#record-the-result}

A passing ResearchQuestionBrief contains these positions:

| Result position | Required content |
| --- | --- |
| receiver and use | Named receiver, proposed bounded evidence use, affected decision or practice, and the authority that remains outside research. |
| intended episteme change | Exact claim or corpus contribution that could be retained, narrowed, rejected, qualified, or added. |
| bounded question | Answerable question with phenomenon, unit, case, population or corpus, relation or contrast, constraints, and effective horizon where material. |
| qualified current frame | The source answer prepared through §4.3 or supplied for the same use, with its source editions, relevant alternatives, omissions and applicability limits. |
| membership account | Separate pass reasons for all four conditions and the nearest non-member considered. |
| criticism demand | Principal error, rival, invalid source use, dependence, bias, missing context, or unsupported transfer that a defensible answer must expose. |
| constraints and owner results | Domain criteria, safety, ethics, rights, confidentiality, access, instrument, authority, resource, or other conditions already supplied or still external. |
| answer condition | What the evidence must establish for an adequate answer to the bounded question, including applicable uncertainty and scope. |
| work-stop and reopen conditions | When the present work can finish with that answer or with a refusal, retained uncertainty or missing-input return; which unmet answer condition remains and what could reopen inquiry. |
| source and result limits | What the supplied source results establish, what they do not establish, and any source/result that must be returned rather than improvised. |
| continuation | Compatible brief and frame for RMP.2. No selected design, protocol, authorization, or receiving decision is implied. |

When a supplied result already answers the current use, return that answer with the source, applicability and limitation information the receiver needs to use it correctly. The current exchange or existing work product may already contain the whole result. Stop with that answer: no ResearchQuestionBrief, unused card answers, separate form or justification for omitting a study is required.

If someone will rely on the answer later or for a different use, retain the exact source/result and the scope, currentness or uncertainty that can change that receiver's reliance. Reuse an adequate existing explanation; add only the missing limitation or reason needed for that use.

For an exact non-research return or research-boundary hold, make the following relations recoverable from the available material or a short return:

| Return position | Required content |
| --- | --- |
| current question | The unresolved wording that arrived, without silently rewriting it into a different owner problem. |
| disposition basis | Supplied-answer sufficiency, nearest non-member, or named missing/stale source or owner result. |
| available material | Exact current results and limits worth carrying to the receiver or owner. |
| return target and expected result | Direct owner or supplier interface and the result kind needed next. |
| effect and retry | What stops now, what can continue, and the condition that would reopen RMP.1. |

### RMP.1:4.6 - Frascati Criteria Mutated for This Boundary {#frascati-criteria-mutated-for-this-boundary}

The OECD Frascati criteria are a valuable cross-sector comparator for R&D. RMP.1 adapts them for holder-neutral, criticism-ready research practice; it does not copy a statistical classification or institutional gate.

| Frascati criterion | RMP.1 use |
| --- | --- |
| novel | **Adapt:** unresolved relative to a qualified current frame and named use. New-to-the-performer information is insufficient; global firstness, patent novelty, and publication priority are unnecessary. |
| creative | **Adapt:** a non-routine question, design, interpretation, synthesis, or criticism choice is required. Prestige originality and artistic creation are not required; routine protocol execution does not pass. |
| uncertain | **Adopt with precision:** the answer or defensible route is not predetermined. Schedule uncertainty, ordinary process variance, or execution risk without an unresolved knowledge claim is insufficient. |
| systematic | **Adopt:** preserve an inspectable question-to-return chain of sources, premises, intended and performed moves, evidence, deviations, limits, and stops. Repetition or checklist compliance alone is insufficient. |
| transferable and/or reproducible | **Adapt:** return a communicable criticism-ready contribution with bounded applicability and enough trace for another critic to inspect or reuse the reasoning. Do not require universal generalization, recurrence, or new-data replication from every historical, qualitative, field, citizen, or other inquiry. |

### RMP.1:4.7 - First-Hour Qualification Card {#first-hour-qualification-card}

Start with prompts 1–3, using the question and available material. If prompt 3 yields a sufficient answer, return it under §4.5 and finish the card there. Prompts 4–8 apply only while a research-membership question remains unresolved. A sentence or compact row is enough where an answer still needs to be made explicit.

1. Who needs what answer for which bounded use, and who retains the later decision?
2. What do the available sources already answer? Use §4.3 when the answer still needs to be recovered or compared; retain the sources and limitations that matter for this use.
3. Does that source answer resolve the receiving question? If yes, return it with the sources and limits needed for this use, and stop here.
4. What exact episteme could change, and what phenomenon, unit, case, corpus, relation, or contrast bounds it?
5. Why is the question unresolved relative to the frame rather than merely unfamiliar?
6. Which non-routine choice and genuine uncertainty prevent ordinary Method execution from being enough?
7. How could a critic inspect and defeat or narrow the claim?
8. What would make the answer adequate for this use? Separately, when should the present work finish with uncertainty or refusal, and what would reopen it?

If an answer still needed to decide the current branch depends on an unavailable source or owner result, name that hold immediately. If a nearest non-member fits, return it immediately. An unused later prompt is neither a missing input nor a reason to reopen a completed answer.

### RMP.1:4.8 - What Changes in Practice {#what-changes-in-practice}

The practitioner stops asking, “Is this activity called research?” and asks, “What exact episteme remains unresolved for this use, why does it need a non-routine criticism-bearing route, and what is the cheapest honest stop?” The output either closes the request from current evidence, moves ordinary Work to its real owner, exposes a precise supply gap, or gives RMP.2 a question it can actually design for.

## RMP.1:7 - Conformance Checklist {#conformance-checklist}

Apply these questions to the branch actually taken. The episteme-change and membership questions govern a ResearchQuestionBrief; a supplied answer, adjacent-Work return or research-boundary hold does not complete unused brief positions.

- [ ] **RMP1-01:** A recognizable ambiguous request, first move, practical gain, stop, and non-use boundary are visible before the detailed method.
- [ ] **RMP1-02:** The named receiver, bounded use, and separate later-decision authority are explicit.
- [ ] **RMP1-03:** The current frame is question-relative and records exact supplied results, source snapshot, omissions, and currentness limits.
- [ ] **RMP1-04:** Serious rivals or lineage are present when they can change the question; a source count is not used as coverage.
- [ ] **RMP1-05:** A sufficient supplied answer completes both the method and the card before unused brief positions; it retains the source and limits needed for the receiving use without a separate no-study form.
- [ ] **RMP1-06:** The intended episteme change is exact enough to be retained, narrowed, rejected, qualified, or added.
- [ ] **RMP1-07:** The bounded question names the phenomenon, unit, case, population or corpus, relevant relation or contrast, constraints, and useful answer.
- [ ] **RMP1-08:** Unresolvedness is established relative to the qualified frame and named use, not to the performer's memory.
- [ ] **RMP1-09:** A non-routine design, interpretation, synthesis, or credibility choice and genuine route/answer uncertainty are explicit.
- [ ] **RMP1-10:** The intended trace can expose sources, premises, performed moves, evidence, deviations, limits, and stops to criticism.
- [ ] **RMP1-11:** The intended result is a bounded communicable episteme contribution, not only action, compliance, acceptance, recognition, or private belief.
- [ ] **RMP1-12:** All four membership conditions pass independently before a ResearchQuestionBrief is returned.
- [ ] **RMP1-13:** The nearest plausible non-member is named and its difference is stated.
- [ ] **RMP1-14:** Routine qualification, monitoring, troubleshooting, audit/evaluation, source use, and ordinary Method application have exact owner/result returns and reopen conditions.
- [ ] **RMP1-15:** Missing or stale source/results produce a named hold with blocked question, owner/interface, and retry condition.
- [ ] **RMP1-16:** From the available question and source texts, the practitioner can follow §4.3 to a supported answer, a useful comparison or a named remaining gap. Source search, interpretation and applicability failures lead to the corresponding repair.
- [ ] **RMP1-17:** The application preserves the meanings and conditions of its FPF contributions. A comparison claimed as SoTA meets F.1:4.2.1 and E.8:11; ordinary source use follows its narrower question.
- [ ] **RMP1-18:** The criticism demand names an error or rival to expose without selecting a design family.
- [ ] **RMP1-19:** The brief distinguishes the evidence needed for an adequate answer from conditions for finishing with refusal or uncertainty; any unmet answer condition and reopen condition remain visible.
- [ ] **RMP1-20:** Domain truth, instruments, safety, ethics, rights, access, assurance, and authority remain with their direct owners.
- [ ] **RMP1-21:** RMP.2 receives only a compatible brief and frame; no design, protocol, authorization, or receiving decision is implied.
- [ ] **RMP1-22:** Corporate and citizen or independent cases receive the same membership test, with holder-specific constraints preserved.

## RMP.1:9 - Consequences {#consequences}

The receiver gains either a question fit for design comparison or a cheaper, more honest result. Unnecessary studies stop early. Routine engineering, Operations, assurance, audit, evaluation, source work, and Method application keep their own results and authority. Independent and citizen practitioners are admitted by the quality of the question-to-return relation rather than institutional status.

The cost is disciplined source qualification before attractive study activity begins. Some requests remain held because a current frame, rival map, measure, domain criterion, access result, or authority result is unavailable. Some highly visible “research” work returns as ordinary practice. These are useful losses: they make the missing value and next action explicit.

RMP.1 also constrains downstream overreach. RMP.2 receives a criticism demand but no preselected design, and the eventual receiver receives evidence relevance without surrendered decision authority.

## RMP.1:12 - Relations {#relations}

- **`F.1` — Question-Relative Source Selection:** supplies a question-relative `SourceCutNote`; it does not decide research membership or relate every source meaning.
- **`F.0.1` — Source-Local Meaning Recovery:** supplies only the source-local meanings needed by the question.
- **`A.10` — Evidence Graph Referring:** supplies exact evidence-use and provenance paths and limits; it does not create truth, assurance, authority, or Work.
- **`F.0.2` and `G.2`:** supply conceptual synthesis for a framework-authoring decision and a broad refreshable SoTA pack respectively, when those uses are current. Ordinary source-answer preparation follows §4.3.
- **`E.8:11`:** defines SoTA and its comparison roles. Section 4.3.2 applies those distinctions to what the existing research can answer; its practical consequence is a changed answer, applicability, research question or stop.
- **Current Method Engineering:** owns reusable Method identity, repertoire, requirements, qualification, trial, fit, worth, variants/provenance, and introduction or revision. RMP.1 owns only the research-specific boundary and question semantics.
- **`RMP.2` — Choose a Criticism-Bearing Research Design or Stop:** consumes a compatible ResearchQuestionBrief and qualified current frame. RMP.1 does not select its design disposition.
- **Domain engineering, Operations, assurance, audit, evaluation, safety, ethics, rights, access, instrument, governance, and receiving authorities:** supply their own results and retain their own decisions.
- **OECD Frascati Manual 2015:** supplies the five-criterion comparator, adapted here rather than treated as a statutory or institutional gate.
- **UNESCO Recommendation on Open Science:** supports holder-neutral citizen and community participation while leaving legitimate restrictions and authority intact.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): receiving question and available sources; spec://ai.lev/fpf-spec/contract/F-1#root, spec://ai.lev/fpf-spec/contract/F-0-1#root and spec://ai.lev/fpf-spec/contract/A-10#root for source use; spec://ai.lev/fpf-spec/contract/E-8#root for SoTA comparison; applicable domain contributions @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-mkt/contract/MKT-12#root, spec://ai.lev/fpf-eng-rmp/contract/RMP-2#root, spec://ai.lev/fpf-eng-rmp/contract/RMP-3#root, spec://ai.lev/fpf-eng-rmp/contract/RMP-4#root, spec://ai.lev/fpf-eng-rmp/contract/RMP-5#root @status:spec/done

#source spec://ai.lev/fpf-eng-rmp/source/RMP-1
