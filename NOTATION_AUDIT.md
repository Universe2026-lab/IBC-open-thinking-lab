# IBC mathematical notation: scope and epistemic audit

Audit date: 21 October 2026. Status: proposed editorial revision, not an established theory or empirical validation.

## Source and scope

Audited the public default-branch files in [Universe2026-lab/IBC-open-thinking-lab](https://github.com/Universe2026-lab/IBC-open-thinking-lab):

| File | Retrieved file blob SHA |
| --- | --- |
| [README.md](https://github.com/Universe2026-lab/IBC-open-thinking-lab/blob/main/README.md) | `1afff7c64342d5699701692f1ef9e175ec2c48e4` |
| [IBC_v1.md](https://github.com/Universe2026-lab/IBC-open-thinking-lab/blob/main/IBC_v1.md) | `9f799392c5833058a7ebc769e842eb59c528d891` |
| [CHANGELOG.md](https://github.com/Universe2026-lab/IBC-open-thinking-lab/blob/main/CHANGELOG.md) | `737ffef776b64c32f773b5401c47268682f92a50` |
| [OPEN_QUESTIONS.md](https://github.com/Universe2026-lab/IBC-open-thinking-lab/blob/main/OPEN_QUESTIONS.md) | `f4eec1f8b556926c4d33b9bcbaa518afbb9883cc` |
| [DEVELOPMENT_NOTES.md](https://github.com/Universe2026-lab/IBC-open-thinking-lab/blob/main/DEVELOPMENT_NOTES.md) | `54ed10f0e5673e960e33d61555d2d005cd48f15f` |

These are file identifiers, not a claimed repository commit. Public files retrieved for this audit remain v1. X-IB is absent from these sources; its notation below is explicitly a proposed extension. The statement that equations are thinking tools rather than natural laws appears in IBC_v1 §28 and the changelog; the README states that the work is not a finished theory.

## Finding

The public notation is primarily definitions, metaphors, hypotheses, and open placeholders. None of the retrieved expressions specifies a complete measurable model with operational variables, domain, observation process, estimable parameters, and a validation procedure. Some could become such models. Their current mathematical appearance must not be mistaken for that status.

The largest problems are type mixing, overloaded symbols, unearned additivity and causality, and universal-looking statements whose intended scope is conditional. A general disclaimer does not resolve these local ambiguities.

## Status convention for every expression

| Label | Meaning | Appropriate notation |
| --- | --- | --- |
| D — Definition | A stipulated term or bookkeeping choice; judged for clarity and usefulness | `:=`, named tuples, explicitly defined sets |
| M — Metaphor | A thinking aid, analogy, or narrative | Prose or labeled diagrams; no arithmetic implied |
| H — Hypothesis | A contingent claim that could fail within a stated domain | Named H1, H2, etc.; conditional predictions once operationalized |
| MM — Measurable model | An operational specification linking recorded observations to predictions | Units/scales, domain, data protocol, parameters, uncertainty, validation |
| O — Open placeholder | An unresolved definition, property, category, or mechanism | Explicit unknown/not assessed status or an open-questions register |

Labels can coexist: a defined container may hold unresolved properties. Definitions do not prove that their referents exist. A hypothesis is not automatically measurable, and a measurable model is not automatically supported by evidence. Normative preferences should also be marked as value commitments rather than empirical results.

## Expression-by-expression audit

Repeated expressions in README and IBC_v1 are consolidated below. Section numbers refer to IBC_v1 unless otherwise stated. Each row states current status, hidden assumptions, and the proposed replacement.

| Source / existing expression or category | Status and hidden assumptions | Proposed rewrite |
| --- | --- | --- |
| §1: human intelligence → AI → superintelligence | M: an intentionally questioned ladder. Could still imply an inevitable trajectory and a single ordering. | Keep as a labeled example of the **ladder metaphor being questioned**, not an evolutionary sequence. |
| README; §2: B = {B_human, B_animal, B_cellular, B_HMHI, R} | D/O: mixes types, beings and ignorance. Humans are animals; cells occur within humans and animals; HMHI may describe a distributed system. Category membership does not establish intelligence under a common criterion. | Define a nonexclusive vocabulary L_v and a set-valued assignment ℓ_v(b;Π); keep unknown categories in U_cat, outside the list of identified kinds. See replacement block. |
| §§2, 29–30; OPEN_QUESTIONS: R as unknown intelligence kinds | O: treats ignorance as though it were an identified kind; assumes a well-defined universe if read as a set complement. | U_cat,v := register of unresolved classification questions and candidates. Do not claim it is an enumerated set of all unknown beings. |
| §3: HMHI = Human–Machine Hybrid Intelligence | D: a naming convention; “hybrid” can mean human-derived training or simultaneous human–machine collaboration. Those are different claims. | HMHI := the project's provisional label for current machine-implemented AI; state whether a given use concerns provenance or an active joint workflow. |
| §3: human knowledge + architecture + human data + feedback + machine computation | M/H: implies additive separability, completeness, and human-only data origins. | “Illustrative contributors include training data of stated provenance, architecture, training/feedback procedures, computation, and deployment context.” Use a provenance record, not a sum. |
| §4: B_i = (I_i,E_i,W_i,C_i,V_i,R_i,…) | D/O: vector appearance implies common scales and defined coordinates; may imply every entity has emotion, wisdom and values. Intelligence and capability may overlap. | P_b,v := (descriptions, operational measures where available, status of each property, U_dim,b,v). A listed field does not assert that property exists. |
| §4: Intelligence ⊂ Intelligent Being | M/type error: a property is not a subset of an entity. | “Intelligence is one proposed attribute in the description of a candidate being/system.” In notation, I_b is a field of P_b, not a subset of b. |
| §5: I = {I(λ)} | M/O: a wavelength suggests a continuous, ordered, measurable axis with comparable values. None is specified. | Retain “spectrum” only as a labeled metaphor. For potential measurement use a task/context-indexed profile p_b(d,e,t;Π), defined only where a protocol exists. |
| §5: I_human(λ) ≠ I_animal(λ) ≠ I_HMHI(λ) | H: suggests universal group differences at every coordinate and ignores within-group variation; chained inequalities do not establish all pairwise differences. | “Profiles may differ on specified tasks and overlap on others.” Compare protocol-specific distributions, not category essences. |
| §5: I_b(λ) = I_known,b(λ) + R_b(λ) | O disguised as decomposition: assumes a measurable total and additive unknown dimensions in a shared space. | (p_b on assessed domains, U_dim,b). An unknown dimension is not a numerical remainder. Reserve empirical residual e := y − ŷ for a specified observable and model. |
| §6: task substitution ≠ being replacement | D/H distinction: scope of task and meaning of replacement unresolved; a task result cannot entail a social outcome. | “Performance on task d alone does not establish replacement of entity b in system S over horizon T.” |
| §6: specialization + overlap + competition + coordination; alternative “one intelligence replaces all others” | M/H: implies exhaustive alternatives and arithmetic. | Label as two nonexhaustive **scenarios to investigate**, with conditions and counterexamples. |
| §7: C1 = Competition; C2 = Coordination | D: names do not make scalar quantities; “forces” can imply physical force. | Use Comp and Coord as concepts. Use c_comp and c_coord only for protocol-defined indicators; call them interaction processes. |
| README; §7: Future = F(C1,C2,…) | H/O: unspecified output, mechanism, time, boundary and omitted inputs; determinism and causal sufficiency may be inferred. Unrestricted F can fit any outcome. | H1: within a specified S and horizon, competition and coordination may help explain defined outcomes, conditional on context. Replace F with a specified candidate model only when variables and predictions are available. |
| §7: competition → variation/experimentation/selection/specialization; coordination → complementarity/division of labor/capability/synergy | H presented through M lists: outcomes need not follow and can be adverse. | State separate conditional mechanism hypotheses. Record outcomes individually; do not sum them or infer synergy from coexistence. |
| §7: max C1 ⇏ best outcome; max C2 ⇏ best outcome | H/normative caution: “max” lacks a feasible set; “best” lacks stakeholder and criterion. | “Do not assume increasing either indicator improves a specified outcome monotonically.” Testing requires an outcome, range and decision criterion. |
| §8: list of competition, coordination, rules, adaptation, etc. | D/M: a list can appear exhaustive or explanatory. | “Illustrative concepts considered by IBC”; no mathematical display needed. |
| §8: observe → patterns → summarize → questions | M: an idealized research workflow, not inference validation. | Present as an iterative workflow, permitting failed patterns and return to observation. |
| §9: S = (M,B,I,R,O,T) | D: analyst selects boundary and objectives; may imply one shared objective; R collides with residual and I with intelligence. | S_v := (M_v,∂_v,J_v,K_v,{O_a,v},T_v). J = interactions; K = rules/constraints; objectives may conflict. Explicitly record analyst, inclusion rules and version. |
| §9: competition in one system ≠ competition in every system | H/logical scope caution: identity symbols are inappropriate for contextual dependence. | “An observation in S1 does not establish the same relation in S2.” Compare boundary-indexed observations. |
| §10: (interests,rules,environment,feedback) → (C1,C2) | H: one-way causality, omitted variables, no feedback from coordination to rules. | “Candidate influences on Comp and Coord; reciprocal effects and confounding remain open.” Any causal graph belongs to a separately specified model. |
| §11: different opinion ≠ core-interest conflict; competition ≠ hostility | D: distinct concepts can coexist or correlate. | Define each separately; “does not necessarily entail” expresses the intended distinction better than numerical inequality. |
| §11: interest conflict + shared rules → structured competition | H: shared rules may be unenforced, unequal or ineffective. | H2: specified rules and enforcement may alter the probability of bounded competition, under stated incentives and power relations. Test against conflict, avoidance and rule violation. |
| §12: C_coord = C_passive + C_proactive | D/H: assumes exclusive, exhaustive, commensurable, additive components; intentionality may be unknown. | Describe coordination mode as a set of labels: {emergent, intentional, mixed, undetermined}. Quantify components only after an explicit coding and aggregation protocol. |
| §§12–13: passive adaptation → problem → threshold → proactive coordination; inertia → damage → threshold → response; “lazy systems” | M/H: fixed sequence, universal threshold and teleology. | “Candidate pathway; alternatives include early coordination, fragmentation, no response and collapse.” “Lazy” remains an analogy, never a system mechanism. |
| §13: T_survival ↑ ⇒ P(C_proactive) ↑ | H: threat confused with time T, event undefined, unconditional monotonicity assumed; severe threats may impair coordination. | H3: within a stated threat range and context, perceived shared threat is associated with a specified change in probability of a defined coordination event. Use z_threat, not T. Causality requires separate identification. |
| §14: S_humanity; boundary-dependent interaction statement | D/H: assumes humanity can be treated as one operative system; salient and analytical boundaries can differ. | S_humanity is a candidate analytical boundary. Separately record B_sali,a(t), the boundary salient to actor a, if ascertainable. Test boundary dependence rather than assuming it. |
| §15: Capability = what can be done; Intelligence = learning/reasoning/etc.; Wisdom = judgment about what should be done | D/O: overlapping constructs; definitions of wisdom include value judgments; common scales absent. | Retain as provisional verbal definitions. Specify each indicator and normative criterion separately before measuring. Rename capability A_b to avoid collision with C1/C2. |
| §15: C ↑ ⇏ I ↑ ⇏ W ↑ | H/logical caution: chained nonimplications obscure which relation is denied and assume scalar increases. | “Increased measured capability does not by itself establish increased measured intelligence or wisdom; intelligence gains do not by themselves establish wisdom gains.” No universal independence claim. |
| §16: recognizing emotion ≠ experiencing emotion | D/O: behavioral recognition and subjective experience are different evidential targets. | Keep verbal distinction; record recognition performance separately from unresolved affective-experience status. Do not assign experience from output alone. |
| §17: need/threat → response; unknown → exploration | M/H: unknowns may be avoided; curiosity has competing explanations. | “Possible mechanisms to compare: instrumental need, novelty/information seeking, reward, and other causes.” Behavioral curiosity measures do not establish subjective curiosity. |
| §18: question → views → exploration → revision → questions | M/H: sequence may fail; “smooth” is also evaluative, despite avoiding “successful.” | Label workflow schematic. Define friction, participation, revision quality and conflict measures if testing curiosity-associated coordination. |
| §19: positive generation → rigorous verification | M plus H: a method preference and a claim about creativity, not evidence that positivity improves validity. | “Proposed practice: open generation followed by explicit verification, with iteration.” Test attitude effects separately using specified conditions and blinded outcome assessment where feasible. |
| §20: biology + history + society + interests; V_human = V_universe | M/O: additive origins, a unified human value vector, and an identifiable universe-level valuer are assumed. | Describe possible influences in prose. Use V_a,context for stated actor values. Leave universal values an open philosophical question; neither equality nor inequality is established. |
| §21: Q = Q(S,t,criteria,position,uncertainty) | D/O: self-named function has no evaluation rule; uncertainty can be mistaken for another outcome determinant. | Q_q(y;S,a,T) := evaluation under explicitly chosen rule q. Report evidence uncertainty separately via a justified interval/distribution or an explicit unknown status. |
| §21: specify for whom/system/criterion/horizon | D/methodological rule: a useful reporting convention, not a law. | Retain as prose instruction and include it in every empirical model card. |
| §22: diversity + competition + coordination; coordination ≠ uniformity | M/H/normative: diversity metric and “healthier” unspecified; benefits may be context-dependent. | “H4: defined diversity and interaction patterns may affect specified resilience/adaptation outcomes.” Define uniformity separately; coordination need not entail it. |
| §23: intelligence ≠ consciousness ≠ agency ≠ moral status | D/O: could be misread as proof of independence or absence of relationships. | “These are distinct constructs; no one is treated here as sufficient evidence for another. Relationships and normative implications remain open.” |
| §24: AI → same output → fewer workers | M/H: one economic scenario with assumed constant demand, output and organization. | Label **labor-saving scenario**, conditional on adoption, demand, constraints and horizon; measure employment changes rather than infer them from technical capacity. |
| §24: human + HMHI → capability → product/service → demand → activity | M/H: assumes joint benefit, viable markets and each causal link. | Label **complementarity scenario**. Each link needs evidence; include failed adoption, demand limits and displacement as alternatives. |
| §25: question → HMHI → experiment → nature → data → joint interpretation | M: a workflow, not evidence of scientific gain; omits failed experiments and verification loops. | Show an illustrative iterative workflow with independent verification, negative results, provenance and stopping decisions. |
| §26; DEVELOPMENT_NOTES Method: question → views → disagreement → reconstruction → revision → synthesis | M plus case claim: selected narratives can omit failed exchanges; no comparison group. | Label “reported dialogue pattern.” Support with preserved, time-ordered raw dialogue and a coding protocol; no general causal conclusion. |
| §27: humans vs AI; humans ↔ animals ↔ cells ↔ HMHI ↔ R ↔ environment | M/H: a chain falsely imposes topology; R becomes an interacting entity; arrows imply observed links and reciprocity. | For a specific case define an interaction graph G := (N,E_obs), with dated, typed evidence for each edge. Keep proposed edges separate; unknown categories belong in U_cat, not as a node. |
| §29: boxed question about what becomes possible | O: research question, not an equation. | Retain in prose as an open question. |
| §§31–32: Protect the question; question space; current framework; exploration > ownership | M/normative: `>` suggests an ordered quantity or empirical comparison. | Present as project principles in prose. The question → dialogue → revision → new model → new questions chain is a process schematic, not a guaranteed sequence. |
| DEVELOPMENT_NOTES: O_collective = O_H + O_M + S_interaction − L_coord | M/H: common units, additivity, comparable baselines and separable synergy/loss assumed. S and L are not identifiable from one outcome. | Use matched performance differences Δ_HM,Π := E[Y_HM] − max(E[Y_H],E[Y_M]) under protocol Π. Positive difference establishes an advantage under that protocol, not separately identified synergy or a universal hybrid advantage. |

## Proposed replacement notation for conceptual sections

The following is ready to adapt into the framework. It defines a description language, not an ontology or natural law.

**[D/O] Candidate entities and nonexclusive labels**

\[
\mathcal L_v := \{\mathrm{human},\mathrm{nonhuman\ animal},\mathrm{cellular},\mathrm{HMHI}\},
\qquad
\ell_v(b;\Pi)\subseteq\mathcal L_v.
\]

Here b is a candidate entity or system selected for study, v is the framework version, and Π specifies the inclusion criteria and level of analysis. Labels may overlap. The cellular label opens a question about intelligence-like behavior; it does not settle the definition of intelligence. Membership makes no assertion about consciousness, subjective experience or rights. ℓ can be empty or unresolved. Uncertainty about category assignment must be recorded.

**[D/O] Entity descriptions and unknown dimensions**

\[
P_{b,v}:=(D_{b,v},M_{b,\Pi},\sigma_{b,v},\mathcal U_{\mathrm{dim},b,v}).
\]

D contains verbal descriptions; M contains only operational measures actually available; σ records property status (measured, inferred, unknown, not assessed, or justified as not applicable); U_dim records unanswered dimensional questions. These statuses are not interchangeable and unknown is never encoded as zero. Proposed fields may include intelligence, capability, affect, wisdom and preferences, with separate definitions and evidence requirements. No Euclidean vector space, independence, common units or exhaustive list is assumed.

**[O] Split the old R by purpose**

\[
\mathcal U_{\mathrm{cat},v}:=\text{unresolved category questions},\qquad
\mathcal U_{\mathrm{dim},b,v}:=\text{unresolved property questions about }b.
\]

Use K for rules/constraints. Use e only for measured model error. These registers preserve unanswered questions, unexplained observations and competing interpretations; they do not assert that an unknown entity exists. Keep entries with provenance and revision history. Resolve or reject an entry only with an explicit reason. Do not absorb unexplained data into a freely adjustable U term to protect a model.

**[D] System description**

\[
\mathcal S_v:=(M_v,\partial_v,J_v,K_v,\{O_{a,v}\}_{a\in M_v},T_v).
\]

Record members, boundary, interactions, constraints, actor-specific objectives and horizon. Objectives may be unknown or incompatible. The tuple is an analyst's representation and can omit relevant features; boundary sensitivity must remain open.

**[M] Spectrum**

“Intelligence spectrum” is a metaphor for heterogeneous and potentially overlapping capabilities. It implies no physical wavelength, common axis, continuity, total ordering or numerical total. In a defined study use:

\[
p_b(d,e,t;\Pi):=\text{recorded performance under protocol }\Pi
\]

only on assessed task/domain d and environment e at time t. This is an operational performance profile, not a complete measure of intelligence or the being. Missing domains remain unmeasured. Do not combine scores without a justified aggregation rule.

**[H/O] Future systems**

“Competition, coordination and other contextual processes may influence specified outcomes in particular evolving systems. Their effects, interactions and directions are unresolved.”

This replaces the unrestricted Future = F(…) expression. It offers a research question without suggesting a predictive theory already exists.

**[O] X-IB extension — proposed, absent from audited public v1**

\[
\mathcal X_v:=\{x^{\mathrm{hyp}}_j:j\in J_v^{\mathrm{scenario}}\}.
\]

X-IB_j denotes an imagined or hypothesized candidate beyond the present classification, not a detected being, guaranteed future stage or ranked generation. An index identifies a scenario, not evolutionary superiority. Existence, autonomy, subjective curiosity, consciousness, goals, substrate and rights remain separate questions. If evidence later supports a candidate, document the identification criteria and revise its status rather than retrospectively presenting the placeholder as a prediction. Keep unimagined possibilities in U_cat; X-IB does not exhaust them.

## A possible measurable model, explicitly new and unvalidated

This illustrates how one small IBC question could become testable. It is not a replacement universal equation.

Define experimental units as research teams conducting the same class of bounded tasks. Let Π specify team composition, AI version, budget, time, randomization, coding rules and independent outcome evaluation. Define c_comp as a competition indicator and c_coord as a coordination indicator measured on stated scales over an initial window. They are not assumed to sum to one. Let Y be a later, prespecified outcome, such as independently verified task quality; let x contain measured context variables.

**[MM candidate / H; not fitted or validated]**

\[
Y_{u,t+\Delta}=\beta_0+\beta_1c_{\mathrm{comp},u,t}
+\beta_2c_{\mathrm{coord},u,t}
+\beta_3c_{\mathrm{comp},u,t}c_{\mathrm{coord},u,t}
+\gamma^\top x_{u,t}+e_{u,t+\Delta}.
\]

This is a deliberately restricted regression candidate, appropriate only if Y's scale and the sampling structure permit it. Its linearity, product interaction, covariate selection, dependence structure and observation error require assessment. It does not assume positive coefficients. Alternatives include no useful contribution, nonlinearity and context-dependent effects.

Specify the estimand and minimum practically meaningful predictive gain before analysis. Compare with a baseline model lacking the competition/coordination terms, using held-out teams or tasks and uncertainty estimates suitable for the dependence structure. Failure to generalize challenges this operational version of H1. It does not disprove every conceivable interaction claim. Success supports only the tested domain, protocol and horizon. Observational coefficients are associations; causal claims require randomized manipulation or another justified identification strategy.

The empirical residual is:

\[
e^{\mathrm{obs}}_{u,t+\Delta}:=Y^{\mathrm{obs}}_{u,t+\Delta}-\widehat Y_{u,t+\Delta}.
\]

It can reflect measurement error, misspecification, omitted variables or stochastic variation. Its existence is not evidence for X-IB, an unknown intelligence dimension or a new natural law. Preserve residual patterns, including negative results, instead of forcing their interpretation.

For H3, define a binary event A = “team initiates a specified coordination behavior within Δ” and perceived shared threat z. A testable association might be P(A=1 | z_high,x,Π) > P(A=1 | z_low,x,Π) for prespecified z_high and z_low in a stated range. This is a hypothesis to test, not an established inequality. Null, reversed and nonmonotonic effects must remain possible; resources, trust and threat perception may modify the relation.

For the dialogue outcome expression, define Y_H, Y_M and Y_HM using matched tasks, comparable total resources, the same AI version where relevant, repeated trials and independent scoring. Report uncertainty for the stronger-solo comparison and avoid reusing the same noisy observations to select and evaluate the baseline. A single naturalistic dialogue cannot estimate this contrast. Joint improvement can coexist with coordination costs; the contrast does not separate them.

## Suggested public framing and change record

Suggested framing:

> IBC uses explicitly labeled definitions, metaphors, hypotheses, candidate measurable models and open placeholders. Definitions stipulate language; metaphors organize questions; hypotheses may fail; candidate models require operationalization and validation; placeholders preserve what is unresolved. Mathematical symbols do not establish the existence of a category, an additive decomposition, a causal relationship, consciousness, or a natural law. Evidence from one system does not automatically generalize to another.

Suggested changelog entry, to be recorded only if adopted:

- Marked each notation item by epistemic status and scope.
- Replaced property/entity subset notation and additive conceptual expressions.
- Separated unknown categories, unknown dimensions, rules and empirical residuals.
- Kept spectrum language explicitly metaphorical and categories nonexclusive.
- Distinguished workflow arrows, mechanism hypotheses and measured causal effects.
- Added a bounded, unvalidated model example with possible failure conditions.
- Identified X-IB notation as a proposed scenario extension, not present public v1 content.
- Retained the original public expressions in history with reasons for revision.

No public files were modified by this audit. The existing public snapshot remains the historical source; this document supplies reviewable replacements while preserving uncertainty.
