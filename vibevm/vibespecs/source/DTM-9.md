# DTM.9 - Model Damage and Feedback from Protective Responses to Continuing or Spreading Activity: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## DTM.9:5 - Archetypal Grounding {#archetypal-grounding}

### DTM.9:5.1 - A broad response releases the variant it was meant to limit {#a-broad-response-releases-the-variant-it-was-meant-to-limit}

Continue the illustrative activity model of DTM.6. A is useful execution and B is execution producing specified errors inside a group. Both occupy limited execution capacity. Suppose the checking response is generated more strongly by visible A activity and also by B:

~~~text
a = 2A + 0.5B + u
A' = A[2(1−A−B) − 0.2 − a]
B' = B[(1−A−B) − 0.3 − 0.2a − v].
~~~

Here u is additional broad checking and v selectively stops established B activity. A, B and remaining capacity are nonnegative. Time and activity are normalized; coefficients are chosen for this example. The equation for a assumes fast adjustment with no consequential memory.

With positive initial presence and the stated model, the stable stationary comparisons are:

| Condition | A | B | a |
| --- | ---: | ---: | ---: |
| No additional response: u=v=0 | 0.25556 | 0.31111 | 0.66667 |
| Broad response: u=0.4, v=0 | 0 | 0.56364 | 0.68182 |
| Selective action: u=0, v=0.3 | 0.45 | 0 | 0.90 |

Increasing broad checking removes the more sensitive A and releases capacity for B. The larger response therefore leaves more B. This conclusion follows from the stipulated resource and sensitivity relations; it is not an empirical claim about procedure catalogues or a general argument against checking.

Selective action succeeds here only if B can actually be distinguished and stopped at the assumed cost. It cannot be presented as an available improvement before that capability is established.

### DTM.9:5.2 - A local consequence and further spread can move differently {#a-local-consequence-and-further-spread-can-move-differently}

Add an illustrative local consequence stock:

~~~text
L' = hB + 0.1a + 0.05v − rL.
~~~

L measures a specified local impairment in normalized units; h is its rate per unit B activity and r its restoration rate. The other terms represent local costs of response and selective checking. Useful A remains a separate result, and harm to outside recipients is not included.

With h=r=1, the three rows above give stationary L of approximately 0.37778, 0.63182 and 0.105. Broad checking worsens both useful activity and this local consequence. These results do not collapse all affected interests into L.

If groups share the same settled internal regime and between-group spread is slower, an illustrative coupling is z'=βBz(1−z)−γz, with z the fraction of groups in which B is established. At β=2 and γ=0.5, the positive stationary fractions are approximately 0.19643 for the baseline and 0.55645 for broad checking. The zero state remains invariant without an introduction.

Reducing h or increasing r can improve the local consequence without changing B and therefore without changing this spread law. Conversely, reducing β can stop continued spread while leaving the established internal activity untouched. DTM.8 explains the distinct intervention targets. If affected groups differ materially or are still learning, use DTM.3 to repair the coupling instead of inserting an unsupported average B.

### DTM.9:5.3 - A successful restriction may leave another continuation route {#a-successful-restriction-may-leave-another-continuation-route}

In the selective-action regime, A=0.45 and a=0.9. Consider a hypothetical rare alternative B* that is unaffected by v and has response sensitivity 0.1 instead of 0.2. Its initial growth rate under the same resource account is:

~~~text
(1−0.45) − 0.3 − 0.1×0.9 = 0.16.
~~~

The positive value establishes a possible weakness of this intervention under those assumptions. It does not predict the appearance of B*, its frequency or an adversary's intention. The next question is whether that alternative has a plausible construction and whether a feasible observation or action addresses it.

A changed variant may also be more useful rather than more harmful. DTM.1 must establish its consequences afresh; inherited suspicion is not an evaluation.

### DTM.9:5.4 - Memory can outlast the condition that formed it {#memory-can-outlast-the-condition-that-formed-it}

Suppose a receiving team keeps restricting an exchange format because earlier versions caused failures. The present format and conversion method have changed, but the restriction uses accumulated historical evidence.

The response state must then distinguish current compatibility from retained evidence. A comparison of current verified exchange and the rule's update behavior can reveal whether the restriction still protects the intended work. A memory-free relation to current usage would miss that question.

For a small constructed case, let m be a retained warning score. The rule holds the format when m≥0.4, starts at m_0=0.8, and updates after an authorized exchange test by m_next=0.8m+0.2e, where e=1 for a failed test and 0 for a successful one. Four successful tests give scores 0.64, 0.512, 0.4096 and 0.32768. The rule therefore still holds the format after the first three tests and releases it after the fourth, although the latest observed outcome is the same throughout.

A rule based only on the latest outcome would release it after the first success. Neither rule is justified by this arithmetic alone: the subject engineering method must establish which exchanges were tested and what evidence warrants admission. If the restriction also prevents every new test and the score has no other update, m remains 0.8 and the restriction sustains its own lack of new evidence.

The subject control and learning methods define how evidence is updated.

## DTM.9:6 - Bias-Annotation {#bias-annotation}

A protective label can hide the response's own consequences. Include useful work and affected recipients alongside the suppressed activity.

The opposite bias treats any costly response as unjustified. A response may remain preferable to the consequences it prevents; the comparison, conditions and alternatives determine that judgement.

## DTM.9:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

**A stronger response is a stronger solution.** Follow useful work and indirect release of other variants.

**The equilibrium settles a deadline question.** Restore response time and the relevant transient.

**A perfect classifier is a harmless simplifying assumption.** Test whether its errors and implementation cost could reverse the chosen action.

**The first successful restriction is permanent.** Revisit the continuation mechanism when conditions or variants change.

## DTM.9:10 - Rationale {#rationale}

A response belongs inside the model when it is produced by, and changes, the modeled activity. This closes a feedback relation that fixed suppression misses. Treating the response as an ordinary process with state, limits and consequences also prevents its protective purpose from being mistaken for proof of its effect.

## DTM.9:11 - SoTA-Echoing {#sota-echoing}

[Ramesh and Hall (2025)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12203456/) examine competition with shared resources and responses in a biological setting. Their distinction between a variant's effect on a limiting factor and its sensitivity to that factor informs :4.3 and :5.1: the same response can restrict the variants differently while their activity changes its formation. The engineering example uses stipulated coefficients; it does not reproduce the biological model.

[Zilio et al. (2026)](https://doi.org/10.1016/j.tree.2025.12.002) reinforce the need to distinguish interaction routes across scales. A changed local interaction therefore needs a stated connection to transmission, rather than an assumed population benefit.

Compared with a fixed suppression term, an endogenous response can reveal costs, differential sensitivity and memory. Compared with an unrestricted multi-process simulation, the method adds only relations that can change the receiving decision. MMP.18 supplies the reduction test, C.30.LCA the control distinctions and the subject practice the realizable response.


## DTM.9:End {#end}
