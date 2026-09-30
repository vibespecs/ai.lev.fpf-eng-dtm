# DTM.7 - Locate Diversion of a Shared Control or Cooperation Mechanism {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

**Type:** Method
**Status:** Stable

## DTM.7:1 - Problem frame {#problem-frame}

**Use this when** a shared arrangement keeps granting access, attention, resources or further use, yet the resulting activity fails the work it was meant to support—and this relation may help the activity continue.

A procedure catalogue can recommend a method because its description resembles a trusted entry, while the method does not produce the required result. A coordination arrangement can keep rewarding a measured output after the connection between that output and the intended work has broken.

Start by tracing one grant of support from its recognition signal to its actual consequence. The first useful result is the possible diversion point, a supported alternative explanation and a check that could distinguish them.

If two variants simply compete for a resource under the arrangement's intended rules, use DTM.5/.6. Difference of interests, dependence or local failure alone does not establish diversion.

## DTM.7:2 - Problem {#problem}

Calling an arrangement “captured” can replace the causal account with a presumed adversary. Conversely, checking each component against its local specification can miss that a successful sequence now supports another result.

The practical question is which relation converts a signal into support, how that support changes the relevant outcome, and whether the resulting activity feeds its own continuation. Intention is a separate claim.

## DTM.7:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Shared arrangements reduce coordination cost | One weak recognition relation can affect many uses. |
| Proxies make decisions affordable | Their relation to the intended result can fail or change. |
| Local participants may follow their instructions | Their combined activity can sustain an unwanted result. |
| Defensive change can stop diversion | It can also block legitimate use or move costs to others. |

## DTM.7:4 - Solution {#solution}

**Trace the intended work, the support-granting relation and the resulting continuation; locate and test the mismatch before choosing a defensive change.**

### DTM.7:4.1 - Recover the intended result and affected parties {#recover-the-intended-result-and-affected-parties}

Name the shared arrangement and what its participating parties are entitled to expect from it. Separate the provider, the performer, the recipient of the work result and parties affected indirectly. A.6.P.RI helps restore the standpoint of each claim.

Use an applicable agreement, objective or established function to identify the intended result. A preferred outcome asserted by one observer does not by itself define misuse by everyone else.

DTM.1 supplies the consequences and dependence account. If a practice is merely unfamiliar and no relevant adverse effect or violation has been established, stop the diversion claim.

### DTM.7:4.2 - Follow one grant of support {#follow-one-grant-of-support}

Recover the relation in ordinary terms:

~~~text
observed signal → recognition or decision
                → granted operation or resource
                → work actually performed
                → result for the named parties.
~~~

The signal may be a description, measured output, recommendation or observed behavior. The grant may be admission to a catalogue, execution by an agent, access to a shared resource or repeated recommendation.

For each arrow, ask what makes it operate. Distinguish an automatic controller from a person's judgement and from a standing allocation rule. C.30.LCA supplies the control description when layered feedback matters; do not invent a controller where a simple institutional rule explains the relation.

### DTM.7:4.3 - Locate the mismatch and the continuation feedback {#locate-the-mismatch-and-the-continuation-feedback}

Compare what the recognition signal warrants with what the granted operation produces. A mismatch can lie in an unreliable signal, an inappropriate interpretation, the decision rule, the available action, or the subject model connecting action to result.

Ask why the signal and result have separated. Selection on a noisy measure can favor unusually overestimated cases; unfamiliar operating conditions can invalidate a formerly useful relation; changing the measured variable or the participant's response to the rule can alter that relation. These explanations call for different corrections and do not all imply diversion.

Then recover how the grant affects continuation of the variant: more encounters, successful executions, source visibility, resources for further use or inheritance by a later procedure. DTM.2/.3 construct that continuation relation.

Keep three possibilities separate:

- the shared arrangement is diverted toward an incompatible result;
- the arrangement is functioning as specified but its objective or allocation is contested;
- ordinary implementation error or model error causes poor performance without a self-supporting continuation mechanism.

Only the first warrants the diversion account as stated. The others can still require action through their own methods.

### DTM.7:4.4 - Compare a causal change with a serious alternative {#compare-a-causal-change-with-a-serious-alternative}

Choose a feasible comparison that changes the suspected relation while preserving enough of the work to interpret the result. Examples include checking the work result independently of the familiar description or testing whether recommendations still differ when subject performance is comparable.

Observe the activity in conditions where the signal actually governs support, and check the work result independently. If a separate test removes the relevant incentive or opportunity, good performance there does not by itself establish that the ordinary support relation is sound. Retain that difference in the comparison instead of inferring a permanent disposition of the agent.

The comparison must not assume the distinction it is meant to establish. If the only reason a method is labeled unreliable is that it is unfamiliar, filtering that label cannot validate the diagnosis.

Consider an alternative such as unequal resources, unsuitable tasks, changed operating conditions or a conflict over the intended objective. Use MMP.16 and the subject research method to distinguish it. A single sequence of events can locate a hypothesis without confirming its cause.

### DTM.7:4.5 - Design the smallest consequential correction {#design-the-smallest-consequential-correction}

Once the relation is supported, consider changing the signal, its interpretation, the grant rule, the available operation or feedback from the actual result. Recover the required authority and practical means separately.

DTM.8 compares these actions with reducing consequences or restoring the function. DTM.9 examines their costs, false restrictions and feedback on other variants. Test whether the correction still admits legitimate use and whether another route would reproduce the same mismatch.

Return the mechanism and conditions, not a permanent classification of an agent as a parasite. Evidence of deliberate manipulation may matter to the receiving practice, but is not needed to model an unintentional diversion and cannot be inferred from benefit alone.

## DTM.7:7 - Conformance Checklist {#conformance-checklist}

- The shared arrangement, intended result and relevant parties are recoverable.
- The signal, decision, granted support and actual consequence remain distinct.
- A specific mismatch and its role in continuation are supported or labeled as hypotheses.
- Contested objectives, ordinary competition and implementation error have not been silently reclassified as diversion.
- A feasible comparison can distinguish a consequential alternative.
- Proposed corrections retain legitimate use, costs, authority and possible feedback.
- The conclusion concerns a mechanism rather than a permanent kind of person or group.

## DTM.7:9 - Consequences {#consequences}

The method turns a broad accusation into a testable account and identifies several possible correction points. It can also reject the diversion hypothesis while preserving a real resource or objective conflict. Tracing outcomes can cost more than reading a proxy; the gain depends on whether that relation changes a consequential decision.

## DTM.7:12 - Relations {#relations}

- **DTM.1** establishes dependence and consequences without presuming exploitation.
- **DTM.2/.3** explain how granted support changes continuation.
- **DTM.5/.6** supply selection and interaction alternatives to diversion.
- **DTM.8/.9** compare corrections and their response feedback.
- **A.6.P.RI** restores the standpoint of claims; **C.30.LCA** supplies layered control distinctions when applicable.
- **MMP.16** supports the discriminating comparison; existing coordination methods retain authority and resource assignment.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-dtm/contract/DTM-1#root/.2; FPF spec://ai.lev/fpf-spec/contract/C-30-LCA#root; spec://ai.lev/fpf-think-mmp/contract/MMP-16#root @status:spec/done

#source spec://ai.lev/fpf-eng-dtm/source/DTM-7
