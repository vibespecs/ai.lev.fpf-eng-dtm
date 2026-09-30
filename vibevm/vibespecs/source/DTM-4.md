# DTM.4 - Find Conditions for Variant Invasion, Persistence and Return: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## DTM.4:5 - Archetypal Grounding {#archetypal-grounding}

### DTM.4:5.1 - Rare growth and persistence give different answers {#rare-growth-and-persistence-give-different-answers}

Consider a constructed reversible uptake model for the share f using a practice. The modeled adoption flow is s f²(1−f): encounters must provide the reinforcement represented by f². The modeled abandonment flow is s θ f(1−f): access to alternative users contributes to departure. Thus:

~~~text
f' = s f(1−f)(f−θ),    0≤f≤1,    s>0,    0<θ<1.
~~~

The two flows are nonnegative on the stated region. Their forms are hypotheses for this example, not universal properties of social learning. With θ=0.4 and s=1 per chosen time unit, the fixed points are 0, 0.4 and 1.

For 0<f<0.4 the derivative is negative; for 0.4<f<1 it is positive. The endpoint regimes attract interior states on their respective sides, while 0.4 separates them. At f=0.2 the rate is −0.032; at f=0.6 it is +0.048.

The rare-variant test reports decline near zero. It does not establish that an existing majority will disappear. The model instead gives persistence from the higher initial range. The first useful result is this distinction, before any choice of intervention.

### DTM.4:5.2 - A temporary reduction can be followed by return {#a-temporary-reduction-can-be-followed-by-return}

In the same model, suppose an admissible action temporarily changes f from 0.8 to 0.5. When the action ends and the old law resumes, f increases again because 0.5 remains above 0.4. A displacement to 0.3 would instead place the trajectory in the lower range.

These statements do not establish an available or legitimate way to change f. They tell the project what a claimed temporary intervention would need to achieve under the model. Changing ongoing support would require a revised law, not a fictitious one-time jump.

The endpoints in this model are invariant: departure is absent at f=1 and uptake absent at f=0. If the actual practice permits independent departure, outside introduction or invention, add those processes before using the endpoint predictions. A change in the underlying event account may remove the threshold or replace the two regimes.

### DTM.4:5.3 - Compatibility changes a threshold but does not guarantee uptake {#compatibility-changes-a-threshold-but-does-not-guarantee-uptake}

Suppose a switching group bears conversion costs while old-standard partners keep their process unchanged. Over one horizon, its gain relative to continuing is g(f)=2−0.5−3(1−f), where f is the adopter share. Assume equally weighted encounters in a homogeneous population, so f also gives the group's relevant partner share on the new standard. The gain is positive only above f=0.5.

An available adapter costing 0.4 and reducing the conversion coefficient to 0.2 gives gₐ(f)=2−0.5−0.4−0.2(1−f). At f=0.2, g=−0.9 while gₐ=0.94.

This is a threshold of the group's comparison, not yet a population stability result. Add the explicit event rule that a fraction e of the remaining groups receive a feasible, authorized offer and adopt when the gain is positive. Then one step gives:

~~~text
f_next = f + (1−f)e × indicator(g>0).
~~~

For f=0.2 and e=0.25, the share remains 0.2 without the adapter and becomes 0.4 with it. For e=0, neither positive gain nor a favorable threshold produces uptake.

This constructed rule omits departure, unequal partners and changing expectations. To conclude persistence or reversibility, supply those mechanisms where they matter and repeat the corresponding question. ECO.8 retains the coordination and allocation of costs; the engineering method establishes compatibility.

## DTM.4:6 - Bias-Annotation {#bias-annotation}

The term “invasion” denotes growth from a small positive presence in a specified model. It assigns neither moral value nor an instruction to spread something.

An attractive tipping-point narrative can encourage modelers to choose reinforcement in advance. Compare a simpler uptake law when the evidence does not establish it, and preserve the resulting difference in continuation.

## DTM.4:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

**A positive trend proves inevitability.** Recover the surrounding regime and test the continuation that the claim actually needs.

**Rare decline proves eventual disappearance.** Examine persistence from established states when reinforcement or compatibility supplies a different regime.

**One successful reduction proves durable change.** Follow the post-action law and reachable state.

**A profitable transition occurs automatically.** Include exposure, means and authority in the event rule.

## DTM.4:10 - Rationale {#rationale}

Establishment, persistence and return are related questions on one dynamic account, but they use different evidence. Keeping them together prevents a local calculation from answering a more expansive question by implication. Mathematical methods supply the analysis; the subject method keeps its conditions connected to the intended change in practice.

## DTM.4:11 - SoTA-Echoing {#sota-echoing}

[Solé et al. (2026 preprint)](https://arxiv.org/abs/2609.03344) provide a current example of reinforcement producing multiple stable coupling regimes. This motivates examining establishment and persistence separately; the one-variable construction above is a different illustrative model, not a reduction or empirical validation of that paper.

The historical [Katz–Shapiro compatibility analysis (1985)](https://idv.sinica.edu.tw/kongpin/teaching/io/KatzShapiro1.pdf) shows why outcomes may depend on other adopters. A gain comparison does not supply an adoption process. The worked adapter construction adds its own explicit event rule and leaves stronger dynamic claims open.

The pattern uses existing mathematical stability and continuation methods. Its contribution is the linked subject inquiry from rare growth through maintained regimes to feasible return.


## DTM.4:End {#end}
