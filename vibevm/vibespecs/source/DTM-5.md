# DTM.5 - Separate Selection Within and Among Collectives: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## DTM.5:5 - Archetypal Grounding {#archetypal-grounding}

### DTM.5:5.1 - Within-group increase is canceled by changing contribution weights {#within-group-increase-is-canceled-by-changing-contribution}

Take two equally weighted source groups. Their initial shares of variant B are 0.2 and 0.8. Along each group's transmitted contribution the B share increases by 0.1. The groups supply relative transmitted-instance counts of 2 and 1.

The initial overall B share is 0.5. The receiving share is:

~~~text
(2 × 0.3 + 1 × 0.9) / 3 = 0.5.
~~~

The contribution-weight change is −0.1; the within-contribution change is +0.1. They cancel. An unchanged aggregate would therefore conceal two material changes.

The weights count transmitted instances, not new organizations and not usefulness. The result does not establish why the low-B group supplied twice as much. Better results, broader access or a sampling difference are possible explanations requiring different follow-up.

If the two groups instead supply equal counts, the new B share becomes 0.6. This changed condition shows which contribution the aggregate depended on.

### DTM.5:5.2 - A copied method can change without being selected {#a-copied-method-can-change-without-being-selected}

Suppose every teaching group sends one equally weighted procedure, but recipients reconstruct it with a different timing convention. A change in the receiving mean belongs to the within-contribution term. There is no differential contribution in this stipulated case.

The next action is to study reconstruction with DTM.2 and the relevant learning or notation method. Calling the change selection would direct attention away from how the recipient obtained the new variant.

### DTM.5:5.3 - Counting successor collectives answers another question {#counting-successor-collectives-answers-another-question}

A project network may form successor teams with different arrangements. If the question is which arrangement becomes common among successor teams, count those teams and recover their formation relations. If the question is which procedure most workers later use, count the corresponding use and contribution relations.

One prolific source team can dominate the latter count without dominating the former. The choice of unit is part of the question, not a defect to remove by finding one universal fitness number.

### DTM.5:5.4 - External arrival changes the receiving mean {#external-arrival-changes-the-receiving-mean}

One procedure instance A continues from the identified source, with B-share z_old = z_cov = 0. One instance B arrives from outside that source set. The receiving population has two instances, so c=1/2 and z_ext=1. Its B-share is (1/2)×0 + (1/2)×1 = 1/2. A source-only calculation would return zero because it answers only for the covered part.

If the external instance's variant is unknown, the whole-population B-share lies between 0 and 1/2. Additional source tracing is needed only if that uncertainty changes the receiving decision. Neither result attributes the external arrival to selection within the original source.

## DTM.5:6 - Bias-Annotation {#bias-annotation}

Grouping by a striking label can make an accounting effect look like a collective cause. Recover the source relations and plausible alternatives before asserting that causal level.

The phrase “higher-level success” also invites a value judgement. Name what continues and who benefits separately.

## DTM.5:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

**The aggregate did not change, so nothing happened.** Recover both components and their possible cancellation.

**A profitable team has higher reproductive success.** Establish the continuation unit and contribution relation; profit may explain one, but does not define it.

**A covariance proves group selection.** Investigate the mechanism and a consequential competing explanation.

**Every inherited change is selection.** Keep reconstruction and transformation distinct from differential continuation.

## DTM.5:10 - Rationale {#rationale}

Multilevel change is not simply the same selection calculation repeated at larger scales. The objects counted, their contribution relations and the causal mechanisms can differ. An explicit decomposition makes those differences inspectable.

## DTM.5:11 - SoTA-Echoing {#sota-echoing}

[Bourrat, *Multilevel selection 1, multilevel selection 2, and the Price equation: a reappraisal* (2023)](https://doi.org/10.1007/s11229-023-04285-1) sharpens the distinction between contributions of particles from collectives and reproduction of collectives. This method adopts the unit distinction without resolving the paper's broader interpretation of multilevel selection.

Compared with following only aggregate prevalence, the decomposition can reveal offsetting changes at modest additional calculation cost. Compared with treating every group association as causal selection, it requires the source and causal relation that would change intervention. Existing mathematical and research methods supply those tests; DTM retains the units and continuation question.


## DTM.5:End {#end}
