# DTM.3 - Couple Change Within Carriers to Spread Between Them: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## DTM.3:5 - Archetypal Grounding {#archetypal-grounding}

### DTM.3:5.1 - Equal average readiness can imply different spread {#equal-average-readiness-can-imply-different-spread}

Consider an illustrative readiness x between 0 and 1. Suppose a relevant demonstration occurs once per period and produces the receiving event with probability q(x)=x². This law is a declared hypothesis for the example, not a general law of learning.

In population A every source has readiness 0.5, giving q=0.25. In population B half have readiness 0.1 and half 0.9. Both have mean readiness 0.5, but population B has mean contribution (0.01+0.81)/2=0.41.

A model using only mean readiness would treat both populations identically. If the comparison is about transmitted successful practice, that reduction loses the effect. Preserve the readiness distribution or sufficient classes. If the actual event law were linear and contact opportunities equal, the same particular loss would disappear.

This case also separates evidence obligations. Measurements of readiness do not establish q(x)=x²; that link requires observations of the chosen receiving event.

### DTM.3:5.2 - Growth can reduce the support available to each learner {#growth-can-reduce-the-support-available-to-each-learner}

Suppose local readiness follows the conditional model:

~~~text
x' = α(f)(1−x) − δx
α(f) = α₀/(1+kf).
~~~

Here f is the fraction adopting, α is the effective support rate per learner, δ a loss rate, and k specifies how adoption loads the support arrangement. The signs and functional form express the assumed sharing mechanism; they would have to change if adoption added support faster than demand.

For α₀=1, δ=0.25 and k=3 in the chosen time unit, the stationary readiness is α/(α+δ). It is about 0.714 at f=0.2 and 0.541 at f=0.8. If q=x² remains the receiving-event law, the corresponding contributions are about 0.510 and 0.292.

The loop is now visible: adoption changes support per participant, readiness changes the receiving-event rate, and that rate changes adoption. These stationary substitutions are useful only when readiness adjusts fast enough. Immediately after a large influx of beginners, replacing their states with these equilibria can be wrong.

A trial to increase adoption might therefore need additional teaching support. The equation does not prove that such support exists or how to teach the missing operation; those are provider questions.

### DTM.3:5.3 - Spread changes compatibility without changing a learner {#spread-changes-compatibility-without-changing-a-learner}

Consider a group comparing two exchange standards. Let f be the share of its relevant partners on the new standard. Over the same horizon, the group compares switching with continuing. Suppose it pays conversion costs while its old-standard partners keep their process unchanged. Its gain from switching is b−c−l(1−f): improvement b, switching cost c and conversion cost l for the remaining old-standard partner share.

Here the feedback is through compatible exchanges. No readiness state or training equation is needed. DTM.2 constructs the actual adoption event; the resulting adoption changes f and thus the gain available to later groups. A broadcast announcement is not the same as an authorized, affordable transition.

Use ECO.8 to retain the coordination and cost-bearing relations. Use the engineering compatibility method to establish that an adapter actually works. The spread model couples those supplied results rather than replacing them.

### DTM.3:5.4 - Repeated opportunities do not create repeated first uptake {#repeated-opportunities-do-not-create-repeated-first-uptake}

For one initially eligible recipient, suppose two independent comparable opportunities each succeed with probability 0.8. The probability of first uptake during those opportunities is 1−0.2²=0.96. It can also be obtained as 0.8+0.2×0.8: the second term includes only the recipients still eligible after the first opportunity.

The product 2×0.8=1.6 instead gives the expected number of successes when both attempts are actually performed and success is repeatable. It is not a first-uptake probability. Either quantity can be useful, but they feed different receiving models. The participant-state coupling must preserve that distinction even when the same internal readiness supplies both probabilities.

## DTM.3:6 - Bias-Annotation {#bias-annotation}

A biological source can make “within” suggest a single organism and “between” a population of organisms. Recover the actual participant boundaries instead. A shared provider or a network may cross organizational boundaries.

A detailed internal model can also attract attention away from the only output the receiving question needs. Detail is justified by a changed prediction or decision, not by anatomical or organizational completeness.

## DTM.3:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

**Everyone transmits like the average participant.** Average the event contributions under the relevant contact weights and compare with the proposed reduction.

**A vertical of methods is a contact hierarchy.** Separate the simultaneously enacted operations from the network through which another participant encounters the practice.

**Fast equilibrium from the first moment.** Check newcomers and changed conditions before discarding internal time.

**Always draw two arrows.** Keep one-way coupling where justified; construct reverse influence only from an actual mechanism.

## DTM.3:10 - Rationale {#rationale}

Cross-level modeling becomes useful when one process supplies a quantity that another process changes in return. The subject method must identify those quantities; general mathematical composition cannot choose them from a shared vocabulary alone. Explicit aggregation and time assumptions make the connection revisable.

## DTM.3:11 - SoTA-Echoing {#sota-echoing}

[Zilio et al. (2026)](https://doi.org/10.1016/j.tree.2025.12.002) motivate separating within-carrier interaction from co-circulation and the feedback through transmission conditions. Their biological mechanisms are not used as universal cultural laws. The readiness and compatibility examples above are separate conditional constructions.

The historical [Katz–Shapiro model of compatibility and network effects (1985)](https://idv.sinica.edu.tw/kongpin/teaching/io/KatzShapiro1.pdf) supplies a contrasting mechanism in which others' adoption changes a user's outcome. Its equilibrium approach does not by itself provide the adoption or learning dynamics used here.

MMP.18 provides general coupling and reduction methods. C.32.MWA preserves distinctions between structures. DTM adds the construction connecting participant state, transmission contribution and conditions changed by spread.


## DTM.3:End {#end}
