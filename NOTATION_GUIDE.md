# IBC notation guide — working snapshot v1.1

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


These definitions and examples are proposals, not fitted results or validated natural laws. See [the audit](NOTATION_AUDIT.md) for original expressions and hidden assumptions.
