# DTM.8 - Compare Protective Actions against Continuing or Spreading Activity by Target and Remaining Effects {#root}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Working sections of the pattern; its depth sections live in the source document named by the last line. See LICENSE.md for the list of changes.

**Type:** Method
**Status:** Stable

## DTM.8:1 - Problem frame {#problem-frame}

**Use this when** several proposed protective actions promise a similar improvement but act on different parts of a continuing or spreading practice.

Reducing exposure does not necessarily stop an already established activity. Reducing its consequences does not necessarily stop its further transmission. Restoring a useful function does not necessarily restore the old arrangement. These differences determine what the action can accomplish and what must accompany it.

Start with the function and affected party to be protected, then locate what each feasible action changes. The first result is a comparison of intervention targets, their direct effects, important remaining effects and implementation conditions.

For an already understood isolated hazard with no continuation or transmission question, use the relevant subject protection method. This pattern does not supply clinical, biological or other technical intervention procedures.

## DTM.8:2 - Problem {#problem}

A single label such as prevention, resistance or resilience can hide several causal changes. A decline in observed damage can result from fewer new contacts, less continuing activity, lower consequences of the same activity, or faster restoration after damage.

Treating these as interchangeable produces false completion claims. A local improvement can leave the source of harm to others unchanged, and a restriction that stops one activity can also prevent a needed contribution.

## DTM.8:3 - Forces {#forces}

| Force | Tension |
| --- | --- |
| Prompt protection is valuable | The nearest available action may act on the wrong target. |
| Local consequences are visible | Continued transmission or costs to others may be missed. |
| Combining actions can help | Their effects and resource demands may interfere. |
| Restoration is desirable | Rebuilding the previous arrangement may be unnecessary or infeasible. |

## DTM.8:4 - Solution {#solution}

**Identify the protected function, separate the intervention targets, follow their remaining effects and compare feasible combinations.**

### DTM.8:4.1 - Restore the reference of protection {#restore-the-reference-of-protection}

State which system or participant performs the relevant work, who receives its result, what adverse consequence is at issue and over what horizon. Use DTM.1 before treating an unfamiliar or dependent practice as harmful.

Ask separately about harm entering the considered system and harm its operation can impose on others. This directional contrast can help clarify a discussion of security and safety, but the two words have wider, context-dependent definitions. Accidental versus intentional action is another distinction; it does not follow from the direction.

A.6.P.RI restores the standpoint of the claim. A reduction in the operator's cost is not automatically a reduction in harm to a customer, neighboring group or constituent participant.

### DTM.8:4.2 - Locate each proposed change {#locate-each-proposed-change}

Follow the current account from encounter through established activity to consequence and restoration. Distinguish four target kinds:

| Target | What the action changes | What can remain |
| --- | --- | --- |
| Contact or admission | Opportunity to encounter, receive or establish the variant | Activity already established inside participants |
| Continuing activity | Amount, intensity or occurrence of the unwanted activity after establishment | Past damage, other sources and possible re-establishment |
| Consequence of activity | The effect on a specified function at comparable continuing activity | The activity and its potential for further transmission |
| Restoration | Recovery or replacement of an impaired function | The source of new impairment and continuing exposure |

These targets distinguish causal changes. Their quantities come from the subject practice: failed executions, unauthorized operations, incompatible exchanges or another specified event. There is no universal scalar “burden” shared by all these cases.

One action can affect several targets. Record those actual connections rather than giving it one exclusive label.

### DTM.8:4.3 - Construct the change and its residual effects {#construct-the-change-and-its-residual-effects}

For each feasible action, specify which relation in DTM.2/.3 or the subject model changes. Keep the comparison at the same recipient, horizon and relevant initial conditions.

For reduced contact, retain what happens in already affected participants. For reduced established activity, retain earlier consequences and possible return. For reduced consequence, check whether the variant can still be transmitted. For restoration, compare the restored function with the continuing rate of new impairment.

When a numerical model is warranted, vary the corresponding parameters or operations rather than replacing every protective action with a common reduction factor. MMP supplies the model change and analysis. DTM.4 examines persistence or return; DTM.9 includes response formation and indirect effects.

### DTM.8:4.4 - Check implementation across the method vertical {#check-implementation-across-the-method-vertical}

Recover the component operations, resources and capabilities needed while the protective action is performed, and the larger work it is meant to sustain. C.32.MWA supplies this simultaneous method-vertical question.

For example, “exclude an unreliable procedure” requires an available way to distinguish it under relevant conditions, authority to change admission, and an alternative means to continue needed work. A hypothetical perfect distinction is a model assumption, not an implemented capability.

Use the existing development and operational methods to obtain missing contributions. Restoring a capability can use a different tool, partner or division of work; C.36.RP helps avoid equating cultural recovery with a return to the old arrangement.

### DTM.8:4.5 - Compare combinations and the unchanged option {#compare-combinations-and-the-unchanged-option}

Pass the distinct outcomes, costs, uncertainties and feasibility conditions to the existing portfolio and decision methods. Retain the unchanged option and a smaller bounded change.

Check combinations for shared resource use and inconsistent assumptions. A result-checking operation can both stop faulty work and consume capacity needed for valid work. A repair activity can fail to catch up if new impairment continues faster than it restores function.

The first sufficient result may be a justified exclusion: “reducing new encounters alone cannot meet this deadline because the affected work is already installed.” A complete population model is unnecessary when that conclusion follows from the established causal account.

## DTM.8:7 - Conformance Checklist {#conformance-checklist}

- Protection has a named function, recipient, comparison and horizon.
- Harm to the considered system and harm from its operation are not silently combined.
- Contact or admission, established activity, consequences and restoration are distinguished where they change the choice.
- Each proposed action changes an identified relation and retains material residual effects.
- Required recognition, authority, component operations and supporting capabilities are feasible or explicitly unresolved.
- Combinations are checked for resource conflicts and feedback; existing choice methods perform the comparison.

## DTM.8:9 - Consequences {#consequences}

Protective choices become comparable without pretending that they act in the same way. The method can reveal the need for a combination or a simpler sufficient action. It also exposes costs that a single protection score would conceal. Subject-specific feasibility and value judgements remain indispensable.

## DTM.8:12 - Relations {#relations}

- **DTM.1** supplies the consequence comparison; **DTM.2/.3** locate transmission and established activity.
- **DTM.4** investigates persistence and return; **DTM.6** adds effects through other variants.
- **DTM.7** identifies a diversion point when relevant; **DTM.9** models the protective response and its feedback.
- **A.6.P.RI** restores the standpoint of protection; **C.32.MWA** recovers simultaneous method support.
- **C.36.RP** supports recovery through available cultural means; **MMP** and the existing portfolio methods retain modeling and choice.


## Dependencies {#dependencies}

- @fact:DEPENDS-ON Dependencies (as published): spec://ai.lev/fpf-eng-dtm/contract/DTM-1#root–3; FPF spec://ai.lev/fpf-spec/contract/C-32-MWA#root @status:spec/done

#source spec://ai.lev/fpf-eng-dtm/source/DTM-8
