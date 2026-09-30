# DTM.6 - Model Competition and Facilitation between Variants: depth {#depth}

<status stage="spec" state="done"/>

> Source: Anatoly Levenchuk, *Defense and Transmission Modeling DPF* (23 September 2026), `Engineering DPF Suite/DEFENSE-AND-TRANSMISSION-MODELING-DPF.md` at https://github.com/ailev/FPF commit d131d30a44e7, licensed CC BY 4.0. Depth sections of the pattern; the working sections are in the contract document of the same id. See LICENSE.md for the list of changes.

## DTM.6:5 - Archetypal Grounding {#archetypal-grounding}

### DTM.6:5.1 - Restricting both variants can favor the less sensitive one {#restricting-both-variants-can-favor-the-less-sensitive-one}

Consider a hypothetical community sharing procedures. A and B denote normalized execution activity inside one group, with A+B no greater than one. Remaining capacity is R=1−A−B. A yields useful results in this case; B produces specified errors. These are descriptions of practices and outcomes, not classes of people.

Suppose a shared checking response a affects them differently:

~~~text
A' = A(2R − 0.2 − a)
B' = B(R − 0.3 − 0.2a).
~~~

These illustrative coefficients are stipulated, not measured. Two connections are now visible: both use R, and a restricts A more strongly. Holding activity fixed, an increase in a lowers both instantaneous growth rates. Over time, loss of A also releases capacity for B. The sign of B's eventual change cannot be read from its direct response term alone.

DTM.9 completes this example by modeling how a is formed and calculating the later outcome. If a real procedure catalogue does not have the assumed capacity competition or differential checking effect, this model is not its explanation. A distinguishing investigation must recover those relations.

### DTM.6:5.2 - Compatible partners can make an unfamiliar method worth adopting {#compatible-partners-can-make-an-unfamiliar-method-worth-adopting}

Suppose the proposed method gives a group a benefit of 2 units over a fixed horizon and costs 0.5 to adopt. Exchange with a partner using the old method remains possible through manual conversion. The switching group bears conversion cost 3 per unit share of old-method partners.

If f is the share of its relevant partners already using the proposed method, its gain relative to continuing is:

~~~text
g(f) = 2 − 0.5 − 3(1−f).
~~~

An independent estimate that omits partner conversion gives 2−0.5=1.5. The coupled estimate instead gives −0.9 at f=0.2 and 0.9 at f=0.8. At the lower share, ignoring compatibility therefore reverses the sign of the choice. Here other adopters facilitate adoption by reducing conversion work. No shared defensive response is needed.

An available adapter costing 0.4 over the same horizon and reducing the conversion coefficient to 0.2 changes the gain to 2−0.5−0.4−0.2(1−f), or 0.94 at f=0.2. The participants, cost allocation and horizon are unchanged. If costs instead shift to old-method partners, both parties' consequences must be recomputed.

A comparison that records conversion work and partner composition can distinguish this account from an unrelated reluctance to adopt. Adoption still requires opportunity, capability and authority; a positive gain is not a transmission event. DTM.2/.4 supply those further questions.

### DTM.6:5.3 - A notation practice can facilitate another method's transmission {#a-notation-practice-can-facilitate-another-method-s-transmission}

A group encounters a useful construction but cannot reconstruct its diagrammatic operations. A notation-learning practice may change that capability. The proposed connection is therefore capability → reconstruction of the transmitted method, not contact → uptake alone.

Compare subsequent reconstruction on suitable tasks, while retaining differences in prior knowledge and exposure. If only familiarity with the example increases, the evidence does not establish general facilitation. Human learning and AI training use their respective subject methods; this pattern does not prescribe one learning algorithm.

## DTM.6:6 - Bias-Annotation {#bias-annotation}

Resource competition is an attractive default because it readily yields equations. The intermediary may instead be compatibility, capability or audience structure.

A second bias is to treat observed dominance as intrinsic superiority. A variant can dominate because another practice changed its conditions, while producing worse results for a specified recipient.

## DTM.6:8 - Common Anti-Patterns and How to Avoid Them {#common-anti-patterns-and-how-to-avoid-them}

**Co-occurrence proves facilitation.** Check shared exposure and other common causes.

**Everything competes for one resource.** Identify what is actually limiting and how use changes availability.

**Restricting both must reduce both.** Follow indirect effects through the intermediary and later state.

**The positive gain explains adoption.** Recover the encounter, feasible execution and choice relation separately.

## DTM.6:10 - Rationale {#rationale}

Transmission and continuation change the environment in which variants act. Modeling the actual relation preserves this feedback without treating every interaction as biological competition. The same operation accommodates limiting and enabling relations while leaving their subject laws to the relevant practice.

## DTM.6:11 - SoTA-Echoing {#sota-echoing}

[Zilio et al., *Co-circulation and co-infection: parasite interactions across scales* (2026)](https://doi.org/10.1016/j.tree.2025.12.002) distinguish interaction routes that can operate within and between carriers. The adopted lesson is to recover the route; biological observations do not validate a cultural dependence.

[Ramesh and Hall (2025)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12203456/) provide a current biological treatment of competition involving shared resources and response. The illustrative activity equations here are our construction, not a reproduction or fitted application of that model.

[Katz and Shapiro, *Network Externalities, Competition, and Compatibility* (1985)](https://idv.sinica.edu.tw/kongpin/teaching/io/KatzShapiro1.pdf) are a historical source for compatibility-dependent benefit and differing incentives. Their equilibrium analysis does not supply the uptake law used by a current engineering case.

Compared with using an interaction coefficient alone, recovering the intermediary costs more but identifies what an intervention could change. When a verified subject model already supplies that dependence, reuse it.


## DTM.6:End {#end}
