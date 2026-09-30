# DTM.2 - Build a Transmission Law from Exposure and Uptake: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## DTM.2:5 - Archetypal Grounding {#archetypal-grounding}

### DTM.2:5.1 - Transmission can reconstruct the practice {#transmission-can-reconstruct-the-practice}

Suppose 100 eligible groups face a modeled one-period uptake probability of 0.3. Among their accepted source encounters, 60% carry A and 40% carry B. The accepted flows are therefore 18 and 12.

Assume the recipient retains A after an A encounter with probability 0.9, while a B encounter yields A with probability 0.2. The other outcomes yield B. The receiving flows are:

~~~text
A: 0.9 × 18 + 0.2 × 12 = 18.6
B: 0.1 × 18 + 0.8 × 12 = 11.4.
~~~

These are expected counts, not fractions of a particular person. Thirty uptakes do not mean thirty faithful copies. If accepted encounters favour one source differently, use their composition rather than the source population's composition.

An intervention that helps more recipients obtain the required tool changes uptake. An intervention that helps recipients preserve a needed operation changes K. They are different proposed effects and need different observations.

### DTM.2:5.2 - Reinforcement is a different law {#reinforcement-is-a-different-law}

In a constructed three-neighbour case, each neighbour independently provides a relevant endorsement with probability 0.4. If one endorsement is sufficient, the chance of reaching that threshold is 1−0.6³=0.784. If two are required, it is 3×0.4²×0.6+0.4³=0.352.

Both numbers concern the specified endorsement condition, not actual adoption. A recipient may still lack resources or choose not to proceed. Dependence among neighbours invalidates this binomial calculation; three repetitions from one source are not necessarily three independent endorsements.

The useful result is a choice between mechanisms to investigate, rather than adjusting one transmission coefficient until both stories appear to fit.

### DTM.2:5.3 - A demonstration reaches learners without supplying coordination {#a-demonstration-reaches-learners-without-supplying-coordination}

A dance workshop distributes a turn demonstration. A view count measures exposure. A learner's attempt, successful execution with a cue, uncued execution and later teaching provide different events.

If the learner needs a coordination method not supplied by the demonstration, raising the number of views need not increase the target performance. HCD and the relevant movement methods supply the acquisition work. The transmission model records its effect on the chosen transition, rather than treating a missing capability as unwillingness or resistance.

### DTM.2:5.4 - A recipient hazard becomes a population flow {#a-recipient-hazard-becomes-a-population-flow}

Suppose N=100, f=0.2 and β=0.5 per week. There are 80 eligible recipients, each with current hazard 0.1 per week. The instantaneous new-uptake flow is therefore 8 events per week, or 0.08 of the population per week.

For a short interval of 0.1 week with hazards approximately unchanged, the expected first-uptake count is approximately 0.8. With constant hazard throughout that interval, it is 80[1−exp(−0.01)], approximately 0.796. Counting the remaining fraction again would incorrectly reduce the instantaneous flow to 6.4 events per week. If uptake materially changes f during the interval, evolve the changing state rather than holding its initial hazard fixed.

## DTM.2:6 - Bias-Annotation {#bias-annotation}

A convenient event can displace the intended result: copied prompts and watched demonstrations are easier to count than retained competence. Preserve the receiving event even when its measurement is harder.

Do not treat every reconstruction as decay. Compare what the new variant enables before assigning a copying-error interpretation.

## DTM.2:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

**One click equals adoption.** Select the receiving event before choosing a convenient record.

**Every repetition is an independent trial.** Recover the source and history of the encounters.

**Uptake means copying.** Add the resulting-variant rule after uptake; do not hide it inside a contact count.

**A fitted rate explains the mechanism.** Retain rival mechanisms when they imply different effects of the proposed change.

## DTM.2:10 - Rationale {#rationale}

A law of transmission connects a source opportunity to a recipient change. Exposing that construction makes it possible to revise the appropriate factor when conditions change. Composing uptake with reconstruction preserves the possibility of cultural development instead of reducing it to faithful replication.

## DTM.2:11 - SoTA-Echoing {#sota-echoing}

[Centola, *The spread of behavior in an online social network experiment* (2010)](https://pubmed.ncbi.nlm.nih.gov/20813952/) is a historical experimental counterexample to universally treating social adoption as independent simple contagion. It motivates the reinforcement branch, not a universal threshold or the illustrative numbers above.

[Zilio et al., *Co-circulation and co-infection: parasite interactions across scales* (2026)](https://doi.org/10.1016/j.tree.2025.12.002) distinguish contacts, transmission and establishment and examine their coupling. The method transfers that separation of events; it does not transfer biological event probabilities into cultural practice.

C.36 supplies creation, transmission, reconstruction and selection as distinct cultural relations. MMP.7/.16 supply the observation-model work. The contribution here is to construct the subject-specific event path and compose uptake with the resulting variant, using those providers.


## DTM.2:End {#end}
