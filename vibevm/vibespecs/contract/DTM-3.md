# DTM.3 - Couple Change Within Carriers to Spread Between Them {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

**Type:** Method
**Status:** Stable

## DTM.3:1 - Problem frame {#problem-frame}

**Use this when** a practice changes its participants, and those changes affect whether, what or how they pass it on—or when wider adoption changes the conditions under which participants can use it.

A learner becomes able to demonstrate a method only after practice. Growing adoption can overload shared teaching support. An installed standard changes which exchanges need conversion. A model that holds these conditions fixed can therefore predict the wrong continuation even if its separate local descriptions are reasonable.

The first result is a coupled account: which participant state changes which transmission or uptake event, and which population change feeds back to participants. It may be two connected ordinary sentences or a small mathematical model. Use MMP.18 for the general work of reconciling mathematical descriptions once these subject relations have been identified.

If participant change has no material effect on the receiving question over its horizon, retain the simpler transmission model.

## DTM.3:2 - Problem {#problem}

Two common reductions erase the relation that drives the result. One treats every carrier as an unchanged source of identical transmission. Another computes a detailed participant trajectory but assumes its population consequences are just that trajectory multiplied by the number of participants.

“Carrier” here names the person, group, device or other participant in which the relevant variant is realized or retained for this model. It does not imply disease. A carrier's state, its resources, the method it uses and the contact network remain different objects.

## DTM.3:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| A participant model can be detailed | The receiving spread model may need only one output, but it must be the right output. |
| A mean makes computation cheaper | Nonlinear uptake and unequal contact can make the mean misleading. |
| Events unfold at different speeds | Replacing a process with its equilibrium can erase startup, delay or memory. |
| One vertical of methods supports performance | That vertical is not the same structure as transmission between participants. |

## DTM.3:4 - Solution {#solution}

**Find the relation crossing each modeling boundary, construct its effect on an event, then test what the chosen aggregation loses.**

### DTM.3:4.1 - Identify the participant state that can change transmission {#identify-the-participant-state-that-can-change-transmission}

Start from a receiving event defined by DTM.2. Ask what changes its occurrence or resulting variant: the source's capability, time available to teach, quality of a demonstrated result, retention, equipment compatibility, or the receiver's current preparation, for example.

Keep a state only if it can change the receiving outcome. Recover how that state changes through use, learning, wear, recovery, support or another mechanism of the actual practice. Describe the process before choosing its equation.

A person's ability to coordinate a turn and a robot controller's learned parameters can each affect a demonstration. That does not give them the same learning law. Obtain the internal process from the relevant human-development, movement or engineering methods.

### DTM.3:4.2 - Convert the state into a transmission contribution {#convert-the-state-into-a-transmission-contribution}

Determine the quantity delivered to the next model. Examples include demonstrations per period that meet a performance criterion, an uptake probability conditional on readiness, the composition of reconstructed variants, or the cost of exchange with an adopter.

Preserve the event selected in DTM.2. If each encounter is eligible for a repeatable success, the expected success count is the sum of its event probabilities. With n comparable encounters and common probability p, that count is np; this expectation does not require independence.

First uptake by a recipient is different: after it occurs, later encounters cannot create that recipient's first uptake again. For n independent comparable opportunities before such uptake, its probability is 1−(1−p)^n. More generally, let p_k be the chance of first uptake at opportunity k conditional on no earlier uptake and the stated history. Compose those conditional chances along that history; if histories vary, also account for their probabilities. Alternatively, update the eligible recipient set as events occur.

Aggregate first-uptake probabilities over distinct eligible recipients, not encounters. For a continuous-time model, sum their hazards to obtain the population flow as in DTM.2. This preserves the quantity passed to DTM.4.

Use DTM.2's conditional factors and resulting-variant rule where needed. Do not multiply a capability score by a contact count without explaining how that score changes the selected event probability or rate.

Then name the observation that could establish or challenge the proposed state-to-event relation. If two mechanisms predict different outcomes for the same state, retain both until the receiving decision warrants discrimination by MMP.16.

### DTM.3:4.3 - Recover the feedback from wider spread {#recover-the-feedback-from-wider-spread}

Ask what changes for a participant when more, fewer or different others use the variant. Common possibilities include access to compatible partners, demand on shared support, availability of teachers, recognition rules and a protective response.

Build only the feedback supported by the case. For example, increasing adoption may create more teachers and also consume their time. The net effect is a question about those quantities, not an automatic positive feedback.

Where the influence is one-way over the chosen horizon, state that reduction and its reason. A diagram with arrows in both directions is not a requirement to invent the second mechanism. Where both directions matter, trace the loop far enough to see which state or event the returning effect changes.

C.32.MWA helps keep the structures separate: the vertical of methods enacted in one performance, resource provision, control, contacts and units of selection need not share the same boundaries.

### DTM.3:4.4 - Choose an aggregation that preserves the needed effect {#choose-an-aggregation-that-preserves-the-needed-effect}

Choose among individual states, a few relevant classes, a distribution over state or age since adoption, and a justified common state. Use the least detail that preserves the comparison.

When event contribution is q(x), the relevant population quantity is the appropriately weighted average of q(x), not automatically q of the average x. Weights come from the modeled events: an individual making many demonstrations can contribute more exposure than an individual making none. Population shares alone need not be the weights.

A time-since-adoption description is useful when newcomers and experienced users produce materially different events. An average state is more defensible when the effect is approximately linear over the relevant range or when variation is small enough for the decision. Test that approximation, rather than choosing a fixed number of classes.

Return to MMP.18 if shared quantities, units, conservation, state boundaries or incompatible assumptions prevent composition.

### DTM.3:4.5 - Decide whether a fast process may be reduced {#decide-whether-a-fast-process-may-be-reduced}

If local adjustment is much faster than changes in adoption, a local equilibrium may provide the needed output. First identify the relaxation time and the population-change time over the conditions being compared. Examine startup and interventions, not only a final stationary point.

Retain the local dynamic state when learning delay, fatigue, memory, periodic loading or loss of support changes the prediction. A fast measured response does not establish the absence of slower memory.

The result states what is passed across the boundary, the conditions under which it can be summarized, and the change that would require restoring detail. DTM.4 then investigates persistence and return using that coupled model.

## DTM.3:7 - Conformance Checklist {#conformance-checklist}

- The account names the event whose law changes and the participant state that changes it.
- Each boundary-crossing quantity has a subject interpretation, units where relevant, and an identified receiving use.
- Any feedback from spread is a stated mechanism; an omitted feedback has a bounded reason.
- Event-weighted contributions are distinguished from unweighted participant averages.
- A stationary reduction has a timescale and startup boundary; material delay or memory remains represented.
- A change in aggregation or participant boundary returns to the relevant modeling provider.

## DTM.3:9 - Consequences {#consequences}

The model can explain why a locally successful method fails to spread, or why its spread changes the conditions that made it successful. The cost is additional state or data when simple aggregation fails. Some cases become simpler after the correct interface quantity is identified.

## DTM.3:12 - Relations {#relations}

- **DTM.2** identifies receiving events and variant changes; **DTM.4** examines the resulting regimes.
- **DTM.6** supplies interaction mechanisms that can change local or population conditions.
- **DTM.8/.9** add protective interventions and response dynamics where they matter.
- **MMP.18**, **MMP.16** and **C.32.MWA** supply mathematical composition, distinguishing observations and structural correspondence.
- **HCD**, relevant movement methods and engineering methods supply their own acquisition or physical mechanisms; DTM does not replace them.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-dtm/contract/DTM-2#root; spec://ai.lev/fpf-think-mmp/contract/MMP-18#root @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-dtm/contract/DTM-9#root @status:spec/done

#source spec://ai.lev/fpf-eng-dtm/source/DTM-3
