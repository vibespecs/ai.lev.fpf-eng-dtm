# DTM.2 - Build a Transmission Law from Exposure and Uptake {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

**Type:** Method
**Status:** Stable

## DTM.2:1 - Problem frame {#problem-frame}

**Use this when** a model predicts the spread of a way of working from contacts, messages or downloads, yet these events do not reliably produce use.

A standard can reach a group that lacks permission to adopt it. A demonstration can reach a learner who cannot yet perform its coordinated movement. A prompt can be copied into an AI workflow and then altered before it is executed. These differences change both the amount transmitted and what continues.

Build a law connecting observable exposure, uptake and the resulting variant. The first result is a defensible expected flow or transition probability, with the unresolved factors retained. It can be qualitative when the next decision needs only the missing condition.

A count of views is already sufficient if the question is only whether a notice was seen. Do not expand it into a model of competence or use unless the receiving question needs that result.

## DTM.2:2 - Problem {#problem}

A single “transmission rate” can combine contact, exposure, opportunity, willingness, successful performance and later continuation. It may fit one data series while giving the wrong answer when teaching, permissions, compatibility or access changes.

Adoption and faithful copying also differ. Two practices can have equal uptake and very different future composition because recipients reconstruct or combine what they receive.

## DTM.2:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Few parameters are convenient | A parameter that combines different mechanisms may not survive the proposed change. |
| Contacts supply information | Repetition, independent endorsement and conflicting advice can change its effect. |
| A variant needs a traceable identity | Learning and adaptation may be productive transformations rather than copying errors. |
| Events must be observable | Available records often show publication or access, not performance. |

## DTM.2:4 - Solution {#solution}

**Define the receiving event, reconstruct the path to it, then compose uptake with the resulting variant.**

### DTM.2:4.1 - Name the event to be predicted {#name-the-event-to-be-predicted}

Choose an event that answers the work question: first trial, successful execution under named conditions, continued use over an interval, or ability to teach another participant. Distinguish these when one may occur without the next.

Specify who can undergo the event and the opportunity over which its probability or rate is measured. For a weekly adoption count, identify the groups not already using the practice and what counts as a first use during that week. For a transition between two working methods, identify both starting and receiving states.

Return to DTM.1 if “the variant” sometimes means the description and sometimes the performed method. MMP.7 and MMP.16 help model what records actually reveal and choose observations that distinguish competing event definitions.

### DTM.2:4.2 - Recover exposure and the conditions of uptake {#recover-exposure-and-the-conditions-of-uptake}

Trace how a recipient encounters an actionable variant. A contact matters only through what it makes available. Identify any condition whose absence prevents the receiving event: a needed capability, usable tool, compatible interface, time or authority, for example.

For one period, let E be relevant exposure, G the required opportunity or support, and U the receiving event. When U requires E and G, the chain rule gives:

~~~text
P(U) = P(E) × P(G | E) × P(U | E,G).
~~~

The conditional terms retain dependence; multiplying three unrelated marginal probabilities would assume more. If use can begin through independent invention or another channel, add that event path rather than treating all use as transmission from the selected source.

A brief account such as “the group saw the method but cannot run the required tool” may finish this step. Estimate numerical terms only when they change the next use.

### DTM.2:4.3 - Choose a contact law that matches the mechanism {#choose-a-contact-law-that-matches-the-mechanism}

For independent opportunities with per-contact success probability p and n contacts, the chance of at least one success is 1−(1−p)^n. This construction requires comparable independent trials. It is not justified merely by counting contacts.

When uptake needs reinforcement, use the relevant history: distinct supporting neighbours, repeated successful demonstrations, trust, resource availability or a shared commitment. Give repeated and independent sources the effects supported by the case. Repetition may cease to add information, and another contact can discourage uptake.

In continuous time, define the hazard for a specified recipient who is still eligible for the event. The conditional probability of its first event over a small interval Δt is approximately hΔt; h has units of inverse time. Under a constant hazard, the interval probability is 1−exp(−hΔt), not h itself.

To construct the population flow, count the eligible recipients once. In an illustrative fixed population of N participants, with fraction f already using the variant, homogeneous mixing may support an eligible recipient's hazard h=βf. Then:

~~~text
eligible recipients S = N(1−f)
new-uptake flow J = S h = N(1−f)βf          [events per unit time]
flow of population share j = J/N = βf(1−f) [share per unit time].
~~~

Here β combines the supported encounter and conditional-uptake rates. The factor 1−f belongs to the eligible population, not again inside its per-recipient hazard. This is one two-state construction, not a universal law. Network, institutional or broadcast exposure may require recipient-specific hazards; sum those over the actual eligible set. New participants, departures and return to eligibility require their own transitions.

If competing variants or mechanisms could explain the same uptake, retain those alternatives and use MMP.16 to find a distinguishing observation. A fitted contact coefficient does not establish the missing mechanism.

### DTM.2:4.4 - Describe what the recipient obtains {#describe-what-the-recipient-obtains}

After determining uptake, specify whether the recipient preserves, reconstructs or combines variants. Keep the change conditional on the source, receiving conditions and chosen event.

For discrete alternatives, K(i|j) can represent the probability that an uptake from source variant j yields recipient variant i. Each source column sums to one over the included possible outcomes. If a failed or unclassified outcome matters, include it or separately state the conditioning that excludes it.

With accepted source flows a_j, the receiving flow is:

~~~text
b_i = Σ_j K(i|j) a_j.
~~~

This does not require copying fidelity or a fixed biological analogue. A revised procedure may be a useful result. When several sources jointly produce one method, replace the single-source column with a rule conditional on that combination. An unchanged title does not demonstrate an unchanged method.

### DTM.2:4.5 - Connect observation and further transmission {#connect-observation-and-further-transmission}

State which observed records estimate each event or term. A download can identify access, a trial can identify attempted execution, and an independently checked result can support a performance claim. None automatically supplies the next event.

If uptake changes the recipient's ability or incentive to transmit, hand that dependence to DTM.3. If recipients stop using the variant, represent that transition separately from failure to adopt. The output is the event account plus the resulting law and its source of uncertainty; it is not a requirement to estimate every possible parameter.

Stop when the law supports the intended comparison. Return to the event path if a proposed intervention changes a factor that the current rate had combined with others.

## DTM.2:7 - Conformance Checklist {#conformance-checklist}

- The predicted event, eligible population and interval are stated.
- Exposure, opportunity and uptake remain separable where an intervention can change them differently.
- Multiplicative factors have appropriate conditional meanings; contact independence is not silently assumed.
- The resulting variant is linked to accepted source flows, including reconstruction or combination when relevant.
- Observed records are connected to the events they actually establish.
- The output states the conditions under which the law can be reused and what change requires reconstruction.

## DTM.2:9 - Consequences {#consequences}

The model can distinguish increasing access from enabling performance or changing what is learned. It also shows when an intervention cannot affect the bottleneck it claims to address. More event distinctions require evidence; keep only those that alter the receiving comparison.

## DTM.2:12 - Relations {#relations}

- **DTM.1** identifies the continuing variant and affected participants.
- **DTM.3** connects the adopted practice with changes in participants and further spread.
- **DTM.4** analyzes the resulting dynamic regimes.
- **DTM.6** handles interaction that changes exposure, uptake or persistence.
- **C.36**, **MMP.7/.16** and the applicable learning methods retain their distinct cultural, measurement and capability contributions.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-dtm/contract/DTM-1#root; spec://ai.lev/fpf-think-mmp/contract/MMP-7#root/.11 @status:spec/done
- @fact:REFERENCED-BY Referenced by (computed from the Tables of Contents): spec://ai.lev/fpf-eng-dtm/contract/DTM-3#root, spec://ai.lev/fpf-eng-dtm/contract/DTM-4#root @status:spec/done

#source spec://ai.lev/fpf-eng-dtm/source/DTM-2
