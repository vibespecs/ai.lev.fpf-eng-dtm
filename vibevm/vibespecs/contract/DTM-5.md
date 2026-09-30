# DTM.5 - Separate Selection Within and Among Collectives {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

**Type:** Method
**Status:** Stable

## DTM.5:1 - Problem frame {#problem-frame}

**Use this when** a variant becomes more common within each participating group, yet its overall prevalence changes differently—or when a claimed advantage of a collective is being used to explain which variants continue.

A shortcut can gain users inside every team while teams that use it less contribute more of the next period's procedures. Conversely, a practice can be costly to a current member while supporting a group's continued operation. These situations require distinguishing units of continuation and the processes that change their weights.

The first result is a decomposition of the observed or modeled change, followed by an account of which parts have a supported selection mechanism. The decomposition alone does not establish causation or justify privileging a higher level.

For comparing the current performance of two organizations without a question about differential continuation, use the existing evaluation and choice methods.

## DTM.5:2 - Problem {#problem}

An overall mean mixes changes within groups with changes in the groups' contributions to what continues. Calling either component “group success” leaves its unit unclear: more copied methods, more learners, survival of the same organization, or more successor organizations.

The same arithmetic can also arise without selection. Reconstruction, unequal exposure, recruitment or a changed measurement can alter the mean. A useful account must therefore distinguish the bookkeeping identity from the causal explanation.

## DTM.5:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Groups influence continuation | A chosen grouping can create an apparent group effect without a group-level cause. |
| Aggregate change is observable | Its contributing events may have different sources or mixed parentage. |
| Within-group advantage matters | It may conflict with what makes a collective continue or contribute. |
| Selection language is compact | It can conceal changes of counted unit and normative recipient. |

## DTM.5:4 - Solution {#solution}

**Choose the unit of continuation, trace its sources, separate the changes, then investigate the mechanisms behind them.**

### DTM.5:4.1 - Decide what the next population counts {#decide-what-the-next-population-counts}

Name the earlier population, the receiving population and the interval or transition connecting them. Specify the continuing unit: an executed method variant, a learner retaining it, a transmitted procedure instance, or a collective with an identified successor relation.

A group can contribute many transmitted instances without producing a new group. Use the first kind of count for variant continuation and the second for collective reproduction. Survival, revenue or an externally assigned quality score does not automatically measure either.

C.36 supplies the cultural relations; DTM.1 identifies the variant and affected work. Return to DTM.2 if the available record shows only copies of descriptions while the claim concerns continued execution.

### DTM.5:4.2 - Recover contribution weights and within-group change {#recover-contribution-weights-and-within-group-change}

For each source group, identify how much of the receiving population derives from it and how the relevant property changes along that contribution. Use the actual source relation, rather than assuming that every present member contributes equally.

When multiple groups contribute to one resulting method, choose an allocation supported by the receiving question or retain unresolved source shares. A convenient attribution convention is not evidence of biological or cultural inheritance.

Account for every receiving unit once. Mark the part attributed to the identified source groups and any external or unresolved part; shared source attribution must not count the same unit twice. If the record covers only part of the receiving population, retain that coverage in the result.

Keep differences due to reconstruction, recruitment and observation visible. For example, a transmitted procedure may omit a check during reconstruction even if no recipient deliberately selected the unchecked variant.

### DTM.5:4.3 - Decompose the aggregate change {#decompose-the-aggregate-change}

For a scalar property, let π_g be the source population's weight in group g, z_g its initial mean, w_g its contribution per source unit to the covered part of the receiving population, and Δz_g the change in the corresponding transmitted mean. Weights π_g sum to one; the mean contribution w̄ is positive. The source-attributed contributions must cover that part without omission or double counting.

The covered mean and its difference from the initial mean satisfy:

~~~text
z_cov = Σ_g π_g w_g (z_g + Δz_g) / w̄
z_cov − z_old
  = Cov_π(w,z) / w̄ + Σ_g π_g w_g Δz_g / w̄.
~~~

The first term expresses the effect of different contribution weights associated with the earlier property. The second expresses changes along those contributions. If those contributions cover the whole receiving population, z_new = z_cov.

Otherwise let c be the covered fraction of the receiving population and z_ext the mean property in the rest, using the same counted unit and weighting convention. Include that contribution:

~~~text
z_new = c z_cov + (1−c) z_ext
z_new − z_old = c (z_cov − z_old) + (1−c)(z_ext − z_old).
~~~

An unknown external composition remains unknown; it is not zero. For a binary variant share and known c, the possible new share lies between c z_cov and c z_cov + 1−c until the external composition is constrained. When no receiving unit derives from the identified sources, omit their decomposition and calculate from the other contribution. MMP and the relevant mathematical methods supply the calculation.

This identity does not tell why w or Δz has the observed value. Call them between-source and within-contribution changes until the causal interpretation is established. If the units are collectives, redefine z and w for collective continuation; do not carry over a particle count while silently changing the claim.

For a question needing no scalar aggregate, retain the corresponding source and change table. Do not invent a total score solely to use the formula.

### DTM.5:4.4 - Test the proposed selection mechanisms {#test-the-proposed-selection-mechanisms}

For within-group selection, identify the process by which variants contribute differently under the group's conditions. For a between-group explanation, identify what group property changes survival, contribution, recruitment or successor formation.

Consider an alternative that could reproduce the same decomposition: groups may encounter different audiences, receive unequal support, have different ages, or be observed with different completeness. Choose the distinguishing observation or comparison with MMP.16 and the applicable research method.

The response to a change must follow the mechanism. If a group's larger contribution comes from privileged broadcast access, altering an internal learning method may leave that advantage unchanged. If the advantage comes from reliable results that others adopt, changing access alone can hide the relevant production difference.

### DTM.5:4.5 - Return the decomposition to the work question {#return-the-decomposition-to-the-work-question}

State the units, contribution relation, covered population and any external contribution, distinct components of change, supported causes and consequential unknowns. If coverage or external composition is unresolved, return the supported range or restrict the claim to the covered part. Then ask which feasible change addresses the problematic relation.

A practice favored within teams but associated with lower total contribution can persist locally. A collective's growth can also coexist with costs to its members. D.3/D.4 and the existing decision methods retain those conflicts; no arithmetic term grants moral priority to its level.

Use DTM.3/.4 to examine dynamic continuation and DTM.6 when another variant changes the contribution mechanism. Stop with the descriptive decomposition when causality remains unresolved and that description is sufficient for the receiving use.

## DTM.5:7 - Conformance Checklist {#conformance-checklist}

- The earlier and receiving populations, interval and counted unit are identified.
- Group contribution is not confused with reproduction of the group itself.
- Source weights and changes along contributions can be reconstructed or their uncertainty is stated.
- The receiving population is covered without omission or double counting; external contributions enter the mean, or the result is explicitly bounded to the covered part.
- The decomposition uses consistent units and does not serve as its own causal explanation.
- Reconstruction and differential exposure remain alternatives where they could change the answer.
- The practical conclusion retains conflicts among affected participants instead of assigning automatic priority to a level.

## DTM.5:9 - Consequences {#consequences}

The method exposes conflicts hidden in a population mean and prevents intervention at the wrong mechanism. It also limits overclaiming: a valid decomposition may leave the causal question open. Source attribution and comparable observations can be costly; their required precision follows the receiving decision.

## DTM.5:12 - Relations {#relations}

- **DTM.1/.2** supply the variant, consequences, uptake and reconstruction distinctions.
- **DTM.3/.4** investigate coupled continuation and persistence.
- **DTM.6** models interactions that can change contribution weights.
- **C.36**, **MMP.16**, **D.3/D.4** retain cultural relations, discrimination of explanations and conflicts between interests.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-dtm/contract/DTM-1#root/.2; spec://ai.lev/fpf-think-mmp/contract/MMP-16#root @status:spec/done

#source spec://ai.lev/fpf-eng-dtm/source/DTM-5
