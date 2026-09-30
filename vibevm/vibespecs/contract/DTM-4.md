# DTM.4 - Find Conditions for Variant Invasion, Persistence and Return {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

**Type:** Method
**Status:** Stable

## DTM.4:1 - Problem frame {#problem-frame}

**Use this when** early growth, a fitted trend or a single threshold is being used to claim that a practice will establish itself, disappear, or return after an intervention.

A method may decline when few groups use it yet persist once compatible partners or supporting capabilities become common. A brief reduction can be followed by return to the same regime. A favorable gain from switching may still produce no uptake when no capable, authorized recipient receives the proposal.

The first result is a conditional account of possible continuation: whether a rare variant grows in a specified environment, what can maintain it, and what would change the reachable regime. Use the relevant mathematical methods to establish the properties of the chosen model; this pattern selects and connects the questions that a spread claim must answer.

For an immediate one-off choice with no reliance on persistence or later return, a comparison of the available actions may be sufficient.

## DTM.4:2 - Problem {#problem}

“Increases now,” “can establish,” “persists under present conditions” and “cannot be reversed” are different claims. Local growth does not settle long-term coexistence. A stable regime need not attract every admissible initial condition. A mathematical equilibrium at zero remains possible even when a nonzero introduction would grow.

A threshold without its governing event law, surrounding state and admissible initial conditions can therefore support the wrong intervention.

## DTM.4:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| A decision needs a useful prediction | The available model may establish only a conditional possibility. |
| A rare-variant test is inexpensive | Reinforcement or several interacting variants can require a finite introduction. |
| Local stability summarizes nearby behavior | Large changes and delayed feedback can cross its boundary. |
| A response changes current prevalence | It may also change the environment in which another variant can establish. |

## DTM.4:4 - Solution {#solution}

**Specify the surrounding regime, test growth from rarity, find maintained regimes, then examine reachable change and return.**

### DTM.4:4.1 - Preserve the law and the surrounding conditions {#preserve-the-law-and-the-surrounding-conditions}

Recover the transmission and uptake construction from DTM.2 and the relevant feedback from DTM.3. Identify the variables being varied and those held fixed, the feasible state region, units of time and the environmental conditions. Keep the counted event and eligible population unchanged across that handoff. A per-recipient probability or hazard, a repeatable-event count and a population flow are different inputs; convert them using the stated receiving event before analyzing regimes.

State the practical question before solving: establishment from a small introduction, persistence of an existing variant, coexistence, reduction to a desired range, or return after a temporary change. “What happens?” is too broad when those questions depend on different initial conditions.

If a capability, permission or resource required for uptake is absent, preserve that absence in the law. A favorable comparison is not itself an event.

### DTM.4:4.2 - Test a rare variant in a specified resident regime {#test-a-rare-variant-in-a-specified-resident-regime}

Place the proposed variant at a small positive amount in an otherwise specified regime. Determine its initial growth from the modeled receiving events and losses.

For one rare quantity y, a local form y'=r y plus smaller terms gives growth when r>0 and decline when r<0. r concerns this surrounding regime and these assumptions. If r=0 or the neglected terms can dominate at the relevant scale, the first-order test does not decide.

With several linked rare states, use the appropriate coupled linearization or generation-to-generation operator supplied by the mathematical modeling method. Do not assign one scalar “reproduction number” until its construction and threshold apply to that model.

A zero initial amount can remain zero in a deterministic model with no external introduction. The rare-variant test asks about a small positive amount; it does not predict that an introduction will occur.

### DTM.4:4.3 - Find what can maintain the variant {#find-what-can-maintain-the-variant}

Find admissible stationary or recurring regimes and determine their relevant stability. Retain coexistence, oscillation or continued replacement if the model supports those forms; persistence need not mean a constant population share.

Where reinforcement or compatibility matters, examine finite initial amounts as well as rarity. A rare variant can decline while a sufficiently established variant persists. In that case, identify what separates the continuations and whether the proposed action can cross that boundary.

Use analytical reasoning, validated numerical calculation or a justified qualitative argument at the formality needed by the decision. A solver's last point alone is not evidence of an attracting regime; check the event law, feasible region and behavior under relevant nearby conditions.

### DTM.4:4.4 - Distinguish a temporary displacement from a changed law {#distinguish-a-temporary-displacement-from-a-changed-law}

Model what the contemplated action changes. A one-time alteration of current use changes an initial condition. Continuing support, a compatibility adapter or a revised recognition rule can change a rate or a dependence. A newly available variant changes the candidate set.

Follow the trajectory during the action and after its removal. Ask whether the post-action state remains in the same region of attraction, enters another one, or encounters a different law because capabilities, resources or variants have changed.

For an intended return, identify the route and means needed to realize it. Lowering a parameter is insufficient if a necessary alternative has been lost or an endpoint is invariant under the model. Use C.36.RP and the relevant domain method to obtain an unavailable contribution; do not invent it as a free change in the state variable.

### DTM.4:4.5 - Express the result as conditional continuations {#express-the-result-as-conditional-continuations}

Give the conditions and their consequences together:

- the surrounding regime in which a rare variant grows or declines;
- the maintained regimes relevant to the question;
- initial conditions or interventions that distinguish reachable continuations;
- the observations or changed assumptions that would defeat the account.

Use the existing comparison and portfolio methods when several actions remain viable. DTM.1 preserves whose consequences are being compared. DTM.6/.9 reopen the law when another variant or protective response changes the surrounding regime.

Stop with the weakest supported claim that answers the practical question. A useful conditional threshold need not become an unconditional prediction, and a qualitative return may be enough to reject an ineffective intervention.

## DTM.4:7 - Conformance Checklist {#conformance-checklist}

- The practical question distinguishes establishment, persistence and return.
- The resident state, feasible region and event law are identifiable.
- A rare-variant result is conditional on a specified surrounding regime and a nonzero introduction.
- Maintained regimes are distinguished from a trajectory's transient values; finite-introduction effects are examined where relevant.
- The proposed action changes an initial condition, law, resource or variant set explicitly.
- The result after action removal and any unavailable return contribution remain visible.
- A comparison threshold is not presented as proof of uptake, stability or authority.

## DTM.4:9 - Consequences {#consequences}

The result can reject an intervention that only displaces the state temporarily, or reveal that a failed small introduction does not rule out persistence under different conditions. Its value depends on the event law and feasible actions; precise calculation cannot repair a missing mechanism.

## DTM.4:12 - Relations {#relations}

- **DTM.1** preserves the participants and consequence comparison.
- **DTM.2/.3** supply the event law, internal change and feedback.
- **DTM.5/.6** can change the resident composition or selection conditions.
- **DTM.8/.9** supply protective actions and their dynamic effects.
- **MMP**, relevant mathematical and computational methods perform the selected analysis; **C.36.RP** helps recover a contribution needed for an otherwise unavailable return.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-dtm/contract/DTM-2#root/.3; mathematical analysis @status:spec/done

#source spec://ai.lev/fpf-eng-dtm/source/DTM-4
