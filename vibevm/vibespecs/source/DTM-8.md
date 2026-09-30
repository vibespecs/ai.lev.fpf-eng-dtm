# DTM.8 - Compare Protective Actions against Continuing or Spreading Activity by Target and Remaining Effects: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## DTM.8:5 - Archetypal Grounding {#archetypal-grounding}

### DTM.8:5.1 - Fewer contacts and fewer errors are different changes {#fewer-contacts-and-fewer-errors-are-different-changes}

Consider a hypothetical network in which 20 teams already use procedure B. Each performs 10 runs per week. Under the stated conditions, a run has probability 0.25 of producing an erroneous result. The expected number of new erroneous results is therefore 50 per week.

The following actions address different targets:

- Reducing recommendations may reduce new adopting teams. It does not by itself change the 200 weekly runs already performed.
- Stopping half of the established runs, with all other assumptions unchanged, reduces expected generated errors to 25 per week. The needed work those runs served must still be considered.
- An available independent review that catches 80% of generated errors before delivery reduces expected erroneous deliveries to 10 per week. It leaves 50 generated errors, consumes review effort and does not by itself change transmission of the procedure.
- Correcting earlier erroneous results reduces the unresolved stock. It does not by itself change the current rate of new errors.

Combining the halving of established runs with review of every remaining result leaves 100 runs, 25 expected generated errors and 5 expected erroneous deliveries per week. This requires capacity to review all 100 results at the stated performance without displacing other needed work. If capacity permits only 50 uniformly selected reviews, expected detections are 50×0.25×0.8=10, leaving 15 erroneous deliveries rather than 5. Use OPS to resolve that capacity question.

The error probability and review performance are assumptions for illustration, not empirical claims. If review changes future learning or recommendations, that additional feedback belongs in the model.

### DTM.8:5.2 - The same unresolved stock can hide a different source {#the-same-unresolved-stock-can-hide-a-different-source}

Let L be the expected number of unresolved erroneous results, e the expected arrival rate and r the resolution rate per unresolved result. Under the illustrative approximation L'=e−rL, the stationary stock is e/r.

At e=50 per week and r=1 per week, the stock is 50. Halving e or doubling r gives a stationary stock of 25, but through different actions. In the latter case 50 new erroneous results still arrive each week.

The approximation assumes the resolution capacity supports a rate proportional to L. If a fixed-capacity correction team becomes saturated, that assumption fails; an OPS model is needed. The equal stationary stocks do not establish equal cost, delay, external consequence or further spread.

### DTM.8:5.3 - Protecting exchange without rejecting a useful new method {#protecting-exchange-without-rejecting-a-useful-new-method}

A group receives work represented in a new format. Restricting admission of incompatible records can preserve the current exchange function while also obstructing a useful method.

Possible changes include a verified adapter, a more informative compatibility check or a bounded migration of the receiving work. Their subject engineering methods establish whether exchange succeeds. DTM.2/.6 examine how compatibility affects adoption; DTM.9 becomes relevant if the checking response itself changes useful participation.

Calling the new format an infection would conceal the actual problem. Continuing the old arrangement, converting at the boundary and changing the arrangement are alternatives with different costs and consequences.

## DTM.8:6 - Bias-Annotation {#bias-annotation}

“More protection” can sound preferable without identifying a target. It may instead impose a costly restriction while leaving the relevant source unchanged.

A second bias treats restoration as making the participant self-sufficient. The required result may be dependable access to a contribution, not possession of every underlying method.

## DTM.8:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

**Fewer new users means the established problem is gone.** Keep the already installed activity in the account.

**Less local damage means less transmission.** Recover the actual link; it may be unchanged or even increase.

**A successful repair ends the source.** Compare ongoing impairment with restoration.

**The model has a selective intervention, so we can implement it.** Establish the distinction, means and authority used by that intervention.

## DTM.8:10 - Rationale {#rationale}

The location of an intervention determines which relations it can change. Keeping the locations distinct prevents an improvement in one observed result from being mistaken for removal of every relevant cause. Connecting them to transmission and the method vertical makes the distinction useful beyond its biological origins.

## DTM.8:11 - SoTA-Echoing {#sota-echoing}

[Medzhitov, Schneider and Soares, *Disease Tolerance as a Defense Strategy* (2012)](https://pmc.ncbi.nlm.nih.gov/articles/PMC3564547/) are a historical source for distinguishing reduction of an agent's amount from reduction of its damaging consequences. This pattern adapts the causal distinction to named activities and functions; it does not equate disease tolerance with social tolerance.

[Tang, Mou and Xu, *Defense strategies for plant health: Disease resistance and tolerance* (2025)](https://academic.oup.com/plcell/article/37/8/koaf186/8215596) also distinguish protective effects from damage caused by the response. That distinction informs the comparison of residual effects and response costs in :4.3–.5; the receiving practice must establish the effects of its actual actions.

Compared with one generic suppression target, the four-target account can show why a locally successful action leaves spread or impaired function unresolved. Compared with a complete protection model, it can stop after the smallest relation sufficient to distinguish feasible choices. Existing subject methods establish intervention effects; existing decision methods compare their outcomes.


## DTM.8:End {#end}
