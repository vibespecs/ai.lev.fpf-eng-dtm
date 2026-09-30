# DTM.9 - Model Damage and Feedback from Protective Responses to Continuing or Spreading Activity {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

**Type:** Method
**Status:** Stable

## DTM.9:1 - Problem frame {#problem-frame}

**Use this when** a protective response depends on the activity it encounters and, in turn, changes that activity, useful work or subsequent transmission.

A checking process may consume the capacity it protects. A rule triggered by visible use may restrict an easily recognized useful method more than a less visible faulty one. A learned warning may persist after conditions change. In each case, treating protection as a fixed beneficial reduction can reverse the predicted result.

Start by making the response itself part of the causal account. The first result is a conditional model of its formation, persistence, costs and differentiated effects, sufficient to compare the proposed change with a plausible alternative.

If a fixed external constraint has adequate subject evidence and its response dynamics do not matter to the receiving decision, retain that simpler model.

## DTM.9:2 - Problem {#problem}

Protection is often represented only by how much it removes. That omits the process that produces the response, what it costs, which useful activity it restricts and how the remaining variants change its future conditions.

An immediate decrease can therefore coexist with later release of another variant, loss of useful work or persistent restriction after the initiating condition has disappeared. The protective action can become part of the problem without ceasing to have a protective effect.

## DTM.9:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Fast response limits consequences | Low-latency recognition may be less selective. |
| Memory avoids relearning | It can preserve an inappropriate response after conditions change. |
| Stronger restriction suppresses activity | It also changes resources and competition among remaining variants. |
| A compact model helps decisions | Eliminating response dynamics can hide delay, cost or hysteresis. |

## DTM.9:4 - Solution {#solution}

**Model how the response is generated and sustained, how it acts on each relevant activity, and how those effects return to the conditions that generate it.**

### DTM.9:4.1 - Identify the response and its information {#identify-the-response-and-its-information}

Use DTM.8 to name the protected function and target. Recover what generates the response: an observed event, accumulated evidence, a prediction, a standing rule or a participant's judgement. Distinguish the actual condition from the signal used to recognize it.

Specify the operation that follows and the means needed to perform it. C.30.LCA supplies the relevant control relations; the technical or organizational practice supplies the detection and action method.

If recognition is uncertain, retain its consequential errors. An action that perfectly distinguishes useful and faulty variants is not available merely because the model assigns them different symbols.

### DTM.9:4.2 - Choose the response state and time description {#choose-the-response-state-and-time-description}

Represent formation, decay, persistence and capacity limits at the resolution needed by the question. A response may depend on current activity, past experience or prediction. Use a state or history sufficient to represent that dependence.

An algebraic response a=F(x,u) assumes that its adjustment is sufficiently fast for the receiving result, where x describes relevant activity and u the proposed change. A simple dynamic alternative is:

~~~text
τa' = F(x,u) − a, with τ > 0.
~~~

This illustrative first-order adjustment does not automatically represent learning, saturation or several kinds of memory. Introduce those relations only where supported. MMP.11/.18 govern the state choice and any reduction.

Test the simplification against the decision. A stationary comparison can tolerate a reduction that would be unsuitable for startup, short disturbances or a deadline. Even a fast response can matter when a brief transient crosses an irreversible boundary.

### DTM.9:4.3 - Follow effects on useful work, unwanted activity and transmission {#follow-effects-on-useful-work-unwanted-activity-and-transmission}

For every variant that can change the conclusion, recover how the response changes execution, continuation or uptake. Use the different sensitivities or action conditions supplied by the subject account.

Then follow indirect effects through the relations identified in DTM.6: released capacity, lost prerequisite capability, changed compatibility or a changed audience. Connect resulting participant states to transmission with DTM.3.

Do not add a common resource or a biological mechanism merely to complete a familiar model. A compatibility restriction may operate through exchange opportunities alone; a checking process may instead share scarce staff time with the work it checks.

### DTM.9:4.4 - Account for response costs and restoration {#account-for-response-costs-and-restoration}

Name each material consequence and its recipient. Direct effort, delayed useful work, inappropriate restrictions and external harm need not share a unit or a scalar total. A.6.P.RI and the existing evaluation methods retain those distinctions.

If a local consequence accumulates and can be repaired, represent both its source and restoration. DTM.8 distinguishes changing the source from repairing its result. State which other participants' consequences remain outside that local measure.

At the method vertical, verify that sensing, decision, action and restoration can operate together while supporting the containing work. A proposed response that consumes the only capacity needed for that work may be infeasible even if its isolated mechanism succeeds.

### DTM.9:4.5 - Compare regimes, transients and changed variants {#compare-regimes-transients-and-changed-variants}

Compare the unchanged arrangement with the feasible response changes. Use DTM.4 for persistence and return, and the appropriate mathematical and computational methods for the calculation.

Where variants can change, examine a consequential alternative that differs in response sensitivity or continuation mechanism. Separate a possible variant from evidence that it will arise. DTM.2 supplies reconstruction or change; DTM.5/.6 explain differential continuation. Reuse the existing improvement and model-revision methods rather than adding an automatic escalation rule.

Return the condition under which the response helps, its adverse effects, sensitivity to uncertain relations and the observation that would change the choice. “Protection works” is too broad when the result holds only for one variant or one recipient.

## DTM.9:7 - Conformance Checklist {#conformance-checklist}

- The response's initiating information and performed operation are identified.
- Formation, decay, memory and time reduction match the receiving question.
- Consequential recognition errors and different effects on variants remain visible.
- Direct costs and indirect effects on capacity, useful work and transmission are traced.
- Local consequence measures do not silently stand for every recipient's welfare.
- A selective action has an implementable distinction or remains a conditional alternative.
- Possible variant change is not reported as observed or inevitable change.
- The result states conditions and return observations, rather than recommending indiscriminate escalation.

## DTM.9:9 - Consequences {#consequences}

The model can expose protective actions that worsen the stated outcome and identify when a narrower or differently timed response could help. It also makes uncertainty costly in a visible way: lacking a reliable distinction may rule out the apparently best action. Added dynamics are worthwhile only when they change a consequential comparison.

## DTM.9:12 - Relations {#relations}

- **DTM.6** supplies the interaction relation; **DTM.7** supplies a possible diversion point.
- **DTM.8** distinguishes action targets before their response dynamics are compared.
- **DTM.2/.3/.4** connect change, spread and persistence; **DTM.5** distinguishes levels of continuation.
- **MMP.11/.16/.18** provide state construction, discriminating evidence and justified coupling or reduction.
- **C.30.LCA**, **C.32.MWA** and **A.6.P.RI** retain control, simultaneous method support and reference distinctions.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-dtm/contract/DTM-3#root/.4/.6/.8; spec://ai.lev/fpf-think-mmp/contract/MMP-18#root; FPF spec://ai.lev/fpf-spec/contract/C-30-LCA#root @status:spec/done

#source spec://ai.lev/fpf-eng-dtm/source/DTM-9
