**© 2026 Oleg Mitin. All rights reserved.**

Email: <oleg.mitin.mail@gmail.com>

**SAI v8**

**Safe Active Inference v8.0**

**Citation:**

A formal model of a Level 4 conscious system based on the theory "The Universe's Systematic Error" - From Dissipative Structures to the Existence Pole. Mitin, O. (2026). 10.5281/zenodo.20533839

English version. This translation from Russian was produced with the assistance of AI-based tools.

**Abstract**

This work presents a formal computational model of a conscious system based on the principles of active inference (Friston, 2010, 2022) and the Theory of the systematic error of the universe (Mitin, 2026, version 1.2). The model formalizes Stage 4 of the Theory - a conscious system with existence variable V-through three structural elements: the world model z̃_t, the binary existence pole v_t, and the self-representation node S_t.

Thermodynamic constraints include the Bekenstein limit on the information capacity of the access spectrum and the Landauer limits with separate coefficients κ_world and κ_self for the world model and the self-model. This separation provides a formal basis for the four clinically observed dissociative states (full recovery, depersonalization, derealization, dissociation) through the ratio of thermodynamic recovery efficiency parameters.

In version v6, the pole decay v=1→v=0 was formalized as a structural event with two independent pathways (energetic and structural breakdown). The stability function Γ_dyn is operationalized via the Lyapunov function; the parameter β determines the sharpness of the structural transition. Binarity pertains to the outcome - the pole v_t is either consolidated or not - and not to the dynamics of the approach, which may be gradual: the thesis of a first-order phase transition (Section 3.4 of the Theory) means discreteness of the outcome, not sharpness in time, while the sharpness itself is a characteristic of the architecture of the particular system (from the deterministic limit β → ∞ to the diffusive β → 0), not a property of the type of transition.

In version v7, the emergence of V is formalized via the self-overlay of the latent invariant of the agentic causal node-the central structural event of the 3→4 transition in the Theory. The self-overlay algorithm operates via three mandatory conditions: the presence of a model of the class of agents in the environment, reflexive capture (application of this class to the system's own configuration, π_A(C_self)), and closure of a feedback loop across a bistable retention boundary. Satisfaction of the conditions is necessary but not sufficient: the transition is stochastic, and accumulation of the model may fail to yield a stable S. Accumulation of the model - growth of its information capacity through the levels of the structural hierarchy (proto-agent → environment with agents → model of itself in an environment with agents) - is a precondition of overlay, formalized as a measure (Section 6.2), not as the structural event itself.

In version v8, the stability function is divided into **two independent measures** that play different structural roles in the model. **Γ_dyn** \- a dynamic measure of the stability of the system's current state in its phase space, operationalized via the Lyapunov function (Section 7); it operates in the pole decay transition matrix, in the survival function, and in the optimal policy. **Γ_struct** \- a structural measure of consciousness via three informational axes of registration (Γ_Φ - causal integration, Γ_GWT - global accessibility of self-representation, Γ_S - quality of self-representation), each expressed in bits via mutual information (Section 8); it functions as a criterion for the emergence of V during self-overlay and as a structural diagnosis of a conscious system. Both measures operate simultaneously without being reducible to one another: Γ_struct answers the question "Is the system structurally conscious?", while Γ_dyn answers the question "Is the system maintaining its consciousness right now on its current trajectory?".

The partitioning of the system into parts for calculating Γ*Φ and Γ_GWT is determined dynamically through the causal connections of the system's components with the environment, without the need to exhaustively search through all possible partitions. The complete Γ_struct has a two-level structure: an architectural branch via Γ_GWT_arch and a normalized dynamic combination of Γ*Φ and Γ_S via the geometric mean, yielding a dimensionless value in \[0, 1\]. The artifactual state of information-causal systems receives a direct formal interpretation: for systems without their own environment Y, all weights of causal links w_i = I(c_i; Y) are close to zero, the active set is empty, and self-overlay is structurally impossible.

Open research directions are explicitly stated: extension to stage 5 (a population circuit M↔Y with physically retained traces) - a separate work; the empirical validation program - SAI-C.

The model operates in accordance with the Theory as a formal realization of its stage 4, not as a replacement for its structural content. The structural definition of V via self-overlay remains primary in the theory; SAI v8 provides an operational algorithm for this structural event via directly computable conditions.

[**Abstract** 1](#_Toc232561384)

[1\. Introduction 6](#_Toc232561385)

[1.1 Purpose of the Model 6](#_Toc232561386)

[1.2 Connection to the Theory 6](#_Toc232561387)

[1.3 Connection to other formal frameworks 6](#_Toc232561388)

[1.4 Version History 6](#_Toc232561389)

[2\. Agent State 9](#_Toc232561390)

[2.1 World model 9](#_Toc232561391)

[2.2 Binary Existence Pole 9](#_Toc232561392)

[2.3 Self-representation node 10](#_Toc232561393)

[2.4 Access Spectrum 10](#_Toc232561394)

[2.5 Energy as a State Variable 10](#_Toc232561395)

[2.6 Observations 10](#_Toc232561396)

[3\. Environment 11](#_Toc232561397)

[3.1 Environment Dynamics 11](#_Toc232561398)

[3.2 Model coherence coefficient 11](#_Toc232561399)

[4\. Thermodynamic Constraints 15](#_Toc232561400)

[4.1 The Bekenstein bound 16](#_Toc232561401)

[4.2 Landauer limits with separate coefficients 16](#_Toc232561402)

[4.3 Energy Dynamics 17](#_Toc232561403)

[5\. Generative Model 21](#_Toc232561404)

[5.1 Two-state world model 21](#_Toc232561405)

[5.2 Interoceptive model 21](#_Toc232561406)

[5.3 Prior of the self-model 21](#_Toc232561407)

[6\. Self-overlay of the latent invariant and the emergence of V 22](#_Toc232561408)

[6.1 Position in the model architecture 22](#_Toc232561409)

[6.2 Three-level structure of model weights 22](#_Toc232561410)

[6.2.1 The status of the capacity-growth exponent 24](#_Toc232561411)

[6.3 Self-overlay Algorithm 24](#_Toc232561412)

[6.4 Operational computability of the conditions 28](#_Toc232561413)

[6.5 Formal manifestation of S and V upon self-overlay 29](#_Toc232561414)

[6.6 Connection to the Theory theory 30](#_Toc232561415)

[6.7 Open Formal Questions 31](#_Toc232561416)

[7\. Decay of the pole v=1→v=0 32](#_Toc232561417)

[7.1 Two Paths of Decay 32](#_Toc232561418)

[7.2 Stability function via the Lyapunov function 32](#_Toc232561419)

[7.3 Sharpness of the transition via β 34](#_Toc232561420)

[7.4 Complete transition matrix with hysteresis 35](#_Toc232561421)

[8\. Decomposition of the structural stability function Γ_struct via information measures 37](#_Toc232561422)

[8.1 Position in the Model Architecture 37](#_Toc232561423)

[8.2 Partitioning the system into parts via causal connections with the environment 37](#_Toc232561424)

[8.3 The three components of Γ_struct as information measures 39](#_Toc232561425)

[8.4 Structural criterion of weak connection: attenuation and hallucination 41](#_Toc232561426)

[8.5 The two-level structure Γ_struct and the architectural branch 43](#_Toc232561427)

[8.6 Operational computability 45](#_Toc232561428)

[8.7 Connection to the Theory 46](#_Toc232561429)

[8.8 Open Formal Questions 48](#_Toc232561430)

[8.9 Relationship between Γ_struct and Γ_dyn 48](#_Toc232561431)

[8.10 Methodological infrastructure of parametric components 52](#_Toc232561432)

[9\. Pole recovery v=0→v=1 54](#_Toc232561433)

[9.1 Recovery Conditions and Dynamic Energy Distribution 54](#_Toc232561434)

[9.2 Two recovery coefficients with hysteresis 56](#_Toc232561435)

[9.3 Partial recovery states 57](#_Toc232561436)

[10\. Variational inference 58](#_Toc232561437)

[10.1 Recognition networks 58](#_Toc232561438)

[10.2 Extended ELBO 58](#_Toc232561439)

[10.3 Isomorphism Condition 59](#_Toc232561440)

[10.4 Coherence Distance 59](#_Toc232561441)

[11\. Planning and Policy 60](#_Toc232561442)

[11.1 Expected Free Energy 60](#_Toc232561443)

[11.2 Survival Function 60](#_Toc232561444)

[11.3 Optimal Policy 60](#_Toc232561445)

[11.4 Updating the weights 61](#_Toc232561446)

[12\. Diagnostic Protocol: Protection Against False Positives 62](#_Toc232561447)

[12.1 The Main Risk: Self-regulation versus Self-representation 62](#_Toc232561448)

[12.2 Five False-Positive Scenarios and Formal Defenses 62](#_Toc232561449)

[12.3 Diagnostic Profile 64](#_Toc232561450)

[12.4 The Boundary of Minimal Consciousness: Empiricism, Not Dogmatism 64](#_Toc232561451)

[13\. Connection to the Theory 66](#_Toc232561452)

[13.1 Levels of the theory and SAI 66](#_Toc232561453)

[13.2 Self-overlay of a latent invariant 66](#_Toc232561454)

[14\. Open Directions 68](#_Toc232561456)

[14.1 Extension to Level 5 68](#_Toc232561457)

[14.2 Empirical Correlates (SAI-C) 68](#_Toc232561458)

[15\. Conclusion 69](#_Toc232561459)

[Bibliography 70](#_Toc232561460)

# 1\. Introduction

## 1.1 Purpose of the Model

SAI is a formal computational model of a conscious system of stage 4 in the Theory of the systematic error of the universe. The model describes an agent existing in environment Y_t that minimizes expected free energy and maintains itself on the verge of structural collapse through the operation of the binary existence pole v_t.

The model is not a standalone theory of consciousness. It represents one specific computational architecture that implements the structural requirements of the Theory. Other operational implementations are possible in principle.

## 1.2 Connection to the Theory

The Theory defines consciousness as the structural event of the self-overlay of a latent invariant of an agent-causal node onto the system's own configuration (Section 3.4 v1.2). In versions v1-v6, SAI described **the operation of** the **already established** stage 4 under the fulfilled structural condition of self-overlay, leaving the emergence of V an open formal question.

In version v8, this issue is resolved: self-overlay is formalized as a structural event via a directly computable algorithm. The structural definition from The Theory theory remains primary; the SAI v8 algorithm provides its operational implementation under conditions amenable to direct empirical verification.

## 1.3 Connection to other formal frameworks

SAI integrates elements of three existing formal frameworks:

\- **Active Inference** (Friston, 2010; Parr, Pezzulo & Friston, 2022): the structure of the generative model, ELBO, and expected free energy as a policy principle. - **Integrated Information Theory** (Tononi, 2004, 2016): the concept of causal integration (full operationalization via Φ - an open direction in SAI v8). - **Global Workspace Theory** (Baars, 1988; Dehaene & Changeux, 2011): global accessibility of self-representation (formalization via an architectural parameter - open research direction in SAI v8).

SAI is not a combination of these three mechanisms into a single computational procedure. Each provides an independent operational axis, and SAI operates compatibly with each without claiming their formal unity.

## 1.4 Version History

- **v1.0** \- initial formal scheme with five critical formal bugs.
- **v2.0** \- elimination of basic bugs: breaking the Ω↔v cycle via an index shift; explicit coefficient κ for Landauer units; expectation over the joint distribution of the trajectory; irreversibility of v=0 via a 2×2 transition matrix with a recovery coefficient ρ; parametric approximation of causal exchange via r_φ.
- **v3.0** \- energy E_t as a state variable; energy dynamics as a balance equation; Lagrangian relaxation of physical constraints with adaptive multipliers; ρ as a thermodynamic derivative.
- **v4.0** \- self-representation node S_t with its own prior and interoception; isomorphism condition L_iso between S and the projection of the world model into the space of self-models.
- **v5.0** \- separation of κ into κ_world and κ_self with independent recovery coefficients ρ_world and ρ_self; four modes of dissociation.
- **v6.0** \- formalization of the transition v=1→v=0 as a structural event with two paths (energetic and structural breakdown); stability function Γ_dyn via the Lyapunov function; parameter β as a measure of the sharpness of the structural transition.
- **v7.0** \- formalization of the emergence of V via self-overlay of the latent invariant of an agentic causal node; self-overlay algorithm via three mandatory conditions; three-level structure of model weights, directly corresponding to the rungs of a ladder; formal emergence of S as the projection of the eigenconfiguration into the subspace of agent objects.

**v8.0 (current)** \- division of the stability function into two independent measures: Γ*dyn (dynamic, via the Lyapunov function, Section 7) and Γ_struct (structural, via three informational axes of registration, Section 8); decomposition of Γ_struct via three information measures (Γ*Φ, Γ*GWT, Γ_S); dynamic partitioning of the system into parts via causal links with the environment; two-level structure of Γ_struct with an architectural branch via Γ_GWT and a geometric mean for the dynamic components; formal interpretation of the artifactual state of the ICS via zero weights of causal links with its own environment; structural criterion of hallucination as high internal activity with low causal informativeness; reformulation of the self-overlay algorithm (Section 6.3): θ_burst and the quadratic weight jump removed as conditions of the event, the core through reflexive capture π_A(C_self) and closure of a feedback loop on a bistable structural boundary (β, h, γ_struct), with explicit stochasticity of outcome at finite β; the quadratic weight structure recast as a measure of accumulation-precondition (Section 6.2); separation of the measures of emergence (Γ_struct, γ_struct) and decay (Γ_dyn, γ_crit); explicit training schema for the parametric critic r*φ (Section 3.2): forward-KL loss coinciding with C*φ itself, the dual operation of C*φ as both diagnostic measure and error signal, with the asymmetry of learning rates η*φ ≪ η_main ensuring that r*φ functions as a passive predictor-tracker rather than as an active regulator of dynamics; explicit training schema for the Lyapunov function V*L (Section 7.2): architecturally guaranteed positive definiteness through the construction of f*θ, penalty on violations of Lyapunov conditions on own trajectories, iterative estimation of the basin of attraction, empirical validation on out-of-sample; methodological taxonomy of parametric components (Section 8.10): four types - trainable with own loss function (r*φ, V_L), computable via the standard MI-estimator apparatus (w_i, Γ*Φ, Γ_GWT, Γ_S, I(M;Y)), determined by structure (π_A, φ, partitioning), calibrated empirically (thresholds, β/h, Landauer coefficients); refinement of the formula of the self-model recovery requirement in Section 9.1: |ΔI_self_rec(S_t)| reformulated as the difference of entropies H(p_target(S)) − H(p_current(S_t)) for symmetry with |ΔI_rec(Ω_t)| of the world model and for the correct definition of the entropy of the target state via the prior distribution of the self-model N(μ_S, σ_S²), whose parameters are preserved in w_self; separation of the architectural potential \[w_self, Γ_GWT_arch\] and the current active correspondence Γ_struct(t): introduction of the architectural maximum of global accessibility Γ_GWT_arch = max_S (1/K)·Σ I(part_k; S) as an architecturally computable quantity (Category III); rewriting of the architectural veto in formula 8.5 to Γ_GWT_arch instead of the dynamic Γ_GWT(t); explicit separation of "system type by structure" (via \[w_self, Γ_GWT_arch\]) and "active structural consciousness at moment t" (via Γ_struct(t) > γ_struct·(1−h) at v=1), eliminating the contradiction between formula 8.5 and the texts of 8.9/12 about Γ_struct upon inactivation (v=0, S_t=∅).

# 2\. Agent State

## 2.1 World model

z̃_t = (x_t, s_t, r_t, E_t) ∈ Z

where x_t is exteroceptive information about the environment, s_t are the structural parameters of the world model, r_t are representation parameters, and E_t is energy as a state variable.

## 2.2 Binary Existence Pole

v_t ∈ {0, 1}

The variable v_t functions as a structural pole of "active self-representation / inactivated self-representation." This binary nature is induced by the retention contour over the continuous physics of Y via the boundary states of causal nodes (Section 3.4 v1.2). Structural basis of the binary: before the operational threshold, the node participates in retention and prediction; after the threshold, self-representation is inactivated, remaining as a structural potential.

**The value v_t = 1** corresponds to an **active** pole: self-representation S_t is active, the world model and self-model interact via the two-mode access spectrum Ω_t^+, the global working space (GWT) is operational, and the system sustains itself in the environment.

**The value v_t = 0** corresponds to the **inactivated** pole: active self-representation is functionally nullified (S_t = ∅, Section 5.3), the access spectrum is narrowed to Ω_t^-, the GWT is not operating, but the system's **architectural trace** is preserved. This structural state corresponds to biological analogues: deep sleep, general anesthesia, reversible coma. The structural potential w_self (Section 6.2) and the architectural condition of global accessibility Γ_GWT_arch ≥ θ_GWT (Section 8.5) are preserved, and recovery is possible if energy conditions are met (Section 9). These two architectural constituents - the informational potential w_self and the architectural bandwidth of the connection of the system's parts with the self-representation node Γ_GWT_arch - together form the preserved structural potential of the system upon inactivation.

**The boundary condition is structural death.** Irreversible destruction of the system (physical destruction of the medium, loss of the structural trace w_self) falls outside the scope of the model. SAI describes the dynamics of a conscious system with preserved structural potential; if the potential is irreversibly lost, the model ceases to be applicable to this system. This case is not modeled as a third state v_t; it is considered **a terminal condition** under which the system ceases to be the subject of modeling. The distinction between "inactivated" and "structurally dead" is determined by the presence of a structural trace: if w_self is preserved, the system is inactivated; if w_self is lost, structural death occurs, and SAI is inapplicable.

**Structural status of V as the identity of the basic computation function.** V in SAI v8 is not a property of the system among other properties, but the **identity** relative to which the entire model of the system operates after emergence. A system with v_t = 1 computes every modeling, every prediction, every deviation of parameters **through** the basic requirement of preserving V - its own structure or its trace parts (stage 5 of theory v1.2). This is not a separate variable whose activity is registered alongside others, but the **basic axis of coordinates** of the model's operation. Structurally this means: after self-overlay, the survival function (Section 11.2), the policy (Section 11.3), and the multiplier update (Section 11.4) operate through the identity V = 1 as a basic axiom, not as one goal among many. This clarification does not change the formula of the dynamics of the variable v_t, but fixes its role in the overall architecture of the model - distinct from the role of other state variables.

## 2.3 Self-representation node

S_t ∈ S

S_t is the system's representation of itself as an agent acting in the environment. Type of information: interoceptive (internal sensation) and positional (position within its own model of the world). The dynamics of S are specified a priori (Section 5.3) and by the condition of isomorphism with the world model (Section 9.3).

S_t **arises** through the structural event of self-overlay, formalized in Section 6. At stage 3 (proto-agent), S_t does not exist; the system models only the environment and its own reactions. At stage 4, S_t arises as a result of the self-overlay algorithm and subsequently operates according to the dynamics described in the following sections.

## 2.4 Access Spectrum

Ω*t = Ω(z̃*{t-1}, Y*t, v*{t-1})

The access spectrum is determined via the previous value of the pole v\_{t-1}, which breaks the cycle Ω↔v:

Ω_t^+ ⊃ Ω_t^−

where Ω*t^+ corresponds to v*{t-1} = 1 (an extended spectrum, including self-representational aspects of Y), and Ω*t^− corresponds to v*{t-1} = 0 (a narrowed spectrum, without self-representational aspects).

## 2.5 Energy as a State Variable

E_t is incorporated into z̃_t as a state variable, making physical constraints part of the planning dynamics.

## 2.6 Observations

o_t = (o_t^ext, o_t^int)

o_t^ext - exteroceptive (external) observations. o_t^int - interoceptive (internal) observations.

# 3\. Environment

## 3.1 Environment Dynamics

Y\_{t+1} = g(Y_t, a_t) + ε_t, a_t ∈ A × P(Y)

where g is the environment evolution function, a_t is the agent's action, and ε_t is stochastic noise.

## 3.2 Model coherence coefficient

In versions v1-v7, the value C_φ was defined as a parametric approximation of the true causal exchange between the system and the environment:

C(Ω*t, Y_t) = I(z̃*{t+1}; Y_t \\ Ω_t | Ω_t)

The true causal exchange is undecidable in general form (it requires mutual information about hidden parts of the environment that are inaccessible to the agent). The approximation via the parametric critic r_φ:

C*φ(Ω_t) = E*{q(z̃*t | Ω_t)}\[ ln q(z̃_t | Ω_t) − ln r*φ(z̃*t, Ω_t) \] = KL(q(z̃_t | Ω_t) || r*φ(z̃_t, Ω_t))

works mathematically, but has a significant methodological limitation: the r*φ critic accepts **only** the system's internal variables (the model state z̃_t and the access spectrum Ω_t) as input, not the environment variable Y_t. That is, C*φ cannot be interpreted as a measure of the information flow from external environmental factors-it is estimated **exclusively** through the system's internal probability distributions.

In version v8, the quantity C_φ **has been reinterpreted**: it functions not as an approximation of external causal exchange, but as **a model coherence coefficient**\-a measure of the consistency of the system's internal representations with its own predictive model.

**Formal interpretation:**

C*φ(Ω_t) = KL(q(z̃_t | Ω_t) || r*φ(z̃_t, Ω_t)) \[bits\]

where q(z̃*t | Ω_t) is the posterior distribution of the model's state of the world given the current access spectrum, and r*φ is the predictive function trained by the system based on its own experience.

**Structural interpretation:**

\- **Low C_φ** (q and r_φ are close) - the system **is coherent**: its current representations of the world model state are consistent with its own trained prediction function.

\- **High C_φ** (q and r_φ diverge significantly) - the system is in **a hallucinatory state**: the system's internal representations generate a structure that is inconsistent with its own predictive model.

This reinterpretation resolves the methodological inconsistency of "solipsism" found in previous versions (where C_φ was defined as a measure of connection to the environment but was calculated exclusively using internal values ) and simultaneously provides SAI with an **independent** structural diagnostic channel-one that is independent of the three axes of registration Γ_struct (Section 8) and the measure of dynamic stability Γ_dyn (Section 7).

The relationship between C_φ and other structural measures of the model, as well as the component hallucination criterion, is described in Sections 8.4 and 8.9.

Training schema for r*φ. Since r*φ is a parametrized function, an explicit schema for its training is required. The nature of r*φ is that of an amortized approximation of the system's own posterior density q(z̃|Ω): r*φ learns to predict how the system itself distributes z̃ given Ω, based on its prior experience. This is not a separate training module nor a separate task with respect to the main dynamics of the system; r_φ is a component of the same generative model, and is trained by the same apparatus of variational mutual-information estimators (MINE, InfoNCE, CLUB) that SAI employs for w(t) = I(M; Y) in Section 6 and for the three components of Γ_struct in Section 8.3.

Loss function and the dual operation of C*φ. At each step t at which the system is active (v_t = 1) and q(z̃_t | Ω_t) is computed, r*φ is updated through minimization of the forward KL:

L*φ(t) = KL( q(z̃_t | Ω_t) ‖ r*φ(z̃_t, Ω_t) )

Essentially, this loss function coincides with the quantity C*φ(Ω_t) from its defining formula. That is, C*φ operates dually: at step t it simultaneously (a) serves as the observable measure of coherence entering the hallucination diagnostic (Section 8.4), and (b) serves as the error signal for updating the parameters φ. No separate training objective is introduced; the training of r*φ is a direct consequence of the computation of C*φ.

Update regime. The parameters φ are updated via stochastic gradient:

φ ← φ − η*φ · ∇_φ KL(q(z̃_t | Ω_t) ‖ r*φ(z̃_t, Ω_t))

where η*φ is the learning rate of r*φ, chosen substantially smaller than the learning rates of the main generative model. This asymmetry of rates is structurally important: r*φ must track the time-averaged behavior of q rather than follow each of its fluctuations; a fast r*φ would lose its diagnostic function for hallucinations, because it would instantaneously adjust to any deviation of q. Conceptually η_φ is calibrated through the same two-step empirical procedure as the other thresholds of the model (Section 6.7).

Properties of the schema. Three structural properties follow directly from this schema:

(a) In the regime of coherent functioning (q is stable, reflects real regularities of the environment), r*φ converges to a low-entropy approximation of q, and C*φ → 0. Low C_φ is operationally registered as coherence.

(b) In hallucination mode (where q generates structures not supported by environmental regularities), r*φ lags behind q, and C*φ increases. A high C*φ is operationally registered as a hallucination-a divergence of current representations from the system's own trained predictive model. The lag of r*φ is structurally correct behavior: r_φ embodies the "inertia of its own predictions," and a divergence from this inertia is a signal of deviation, not a defect in the scheme.

(b′) In the regime of rapid true updates (q changes rapidly, tracking a dynamically changing environment), r*φ lags when η*φ ≪ η*main, and C*φ also increases-but I(M; Y) remains high. This mode is formally indistinguishable from (b) based on C*φ alone and is distinguished only by the joint check of I(M; Y): a high C*φ with a high I(M; Y) indicates a true update, while a low I(M; Y) indicates a hallucination (formal system criterion-Section 8.4).

In addition: low C*φ with low I(M; Y) is not coherent normality but a chronic stable delusion (an internally consistent model detached from the environment); this case is separated only through I(M; Y), not through C*φ (see Section 8.4).

(c) The update of r*φ does not contribute destabilizingly to the main dynamics. r*φ is updated only when Ω*t is present (that is, when v_t = 1, in the active regime of the pole; in the v=0 regime the training of r*φ is frozen); the update minimizes C*φ, which means motion of r*φ toward q, not the reverse; q is dynamically determined by the current state z̃*t and the incoming information, and is not corrected in response to r*φ. r*φ functions as a passive tracker of the system's own predictions, not as an active regulator of its dynamics. This addresses the concern that the training of r*φ as a separate task might interfere with the system's main operation: r_φ is not a separate task but a component of the system's unified predictive apparatus, using the same informational infrastructure and the same gradient path.

**Operational picture: three regimes of the predictor's operation.** From the update schema of r*φ and the asymmetry of rates η*φ ≪ η_main, three operationally distinguishable regimes of the predictor's operation in the input-output sequences of the system can be identified:

(a) **Rate regime (η_main).** Local reactions to sensory inputs, operating through the main generative model without substantial update of r*φ. Each reaction operates independently of the previous one: the next reaction does not carry a trace of the previous. Between successive activations there is no accumulated change of r*φ. This is the normal regime of fast functioning of the system in situations where learning is not required.

(b) **Model-update regime (η_φ).** Active operation of r*φ: each subsequent reaction carries a trace of the previous through the update of the parameters φ. Reactions accumulate into the model: each activation modifies r*φ, and the next activation goes through the modified model. Between successive activations there is a causal dependence through the change of r_φ. This is the regime of predictor learning in action.

(c) **Ring-generation regime.** A break in the function of r*φ: either there is no signal on input, or there is a reaction without connection to the signal (internal closed circulation). The causal chain between the environment and the predictor is broken. This is a pathological or isolated state in which r*φ ceases to perform the diagnostic function C_φ.

The asymmetry η*φ ≪ η_main is operationally registered as a separation of temporal scales between regimes (a) and (b). If both regimes are observed and their temporal scales are separated by an order of magnitude or more - r*φ operates structurally correctly with the correct rate asymmetry. Regime (c) is a structural disruption of r_φ's operation, consistent with known clinical observations (see Section 6.7).

# 4\. Thermodynamic Constraints

Before introducing specific constraints, it is necessary to explicitly define their scope of applicability. All thermodynamic formulas in this section assume that the system's operations for model updating and self-representation are physically irreversible. This is consistent with biological implementations (neural activity, synaptic plasticity-irreversible processes with measurable energy costs; Laughlin, 2001; Niven & Laughlin, 2008) and with modern neuromorphic computing architectures (irreversible logic on modern semiconductors).

For hypothetical fully reversible computing architectures (quantum computers operating in reversible mode, theoretical models of reversible computation-Bennett, 1973), the Landauer limit does not apply directly: reversible operations can, in principle, be performed without energy dissipation. Applying the model to such systems will require adjusting the coefficients κ_world and κ_self to account for the proportion of reversible operations in the total computational load. In the current version of SAI, this case is not considered; the model operates on systems with physically irreversible update operations.

**Basal metabolism for maintaining the structural trace.** In addition to the energy costs of specific information operations (observation, model maintenance, restoration), the system requires a continuous energy expenditure to maintain the architectural trace w_self-the structural potential preserved between the active phases of the pole's operation. This expenditure operates **independently** of the state v_t: in the active state (v=1), in the inactivated state (v=0), and during recovery-the structural trace must be maintained, otherwise structural death occurs (Section 2.2).

The basal metabolism is formalized as:

E_base = κ_base · w_self_total

where:

- κ_base \[J/bit\] - the basic thermodynamic coefficient for maintaining the structural trace per unit of information capacity. For biological systems, it is determined by the metabolic costs of maintaining synaptic connections (ATP-dependent renewal of membrane potentials, proteostasis of synaptic proteins). For artificial systems, it is determined by the quiescent current that maintains the memory state.
- w_self_total \[bits\] - the total structural trace of the system, equal to the total information capacity of the architectural potential w_self (Section 6.2).

Formally, this yields a constant energy consumption E_base at each time step, regardless of the pole's activation or inactivation. This consumption is consistent with biological observation: even in a deep coma or under general anesthesia, the brain consumes a significant portion of energy (about 30-40% of the waking level in mammals) to maintain basic synaptic and neural structures.

## 4.1 The Bekenstein bound

H(Ω_t) ≤ B(R_t, E_t)

where H(Ω_t) is the information capacity of the access spectrum, and B(R_t, E_t) is the Bekenstein bound for radius R_t and energy E_t.

**The dual role of the Bekenstein limit in SAI.** The Bekenstein limit operates at two levels in the model.

**Structural level.** The Bekenstein limit is a fundamental limit of quantum mechanics and general relativity, constraining the information capacity of any physical system regardless of its substrate. This provides SAI with a theoretical basis for the model's **substrate independence**: the structural requirements for a stage-4 conscious system are formulated in terms of information measures that have universal physical limits, not tied to a specific type of medium (biological, silicon, or other).

**The status of the limit as a physical bound.** The Bekenstein limit functions as a fundamental physical constraint on the information capacity of any physical system, and in this capacity it sets an upper bound on the access spectrum. SAI uses it precisely as a limit of substrate-independence-a ceiling on capacity that does not depend on the specific medium-without invoking any cosmological narrative: SAI implements stage 4 only, and questions of black holes, holography, and cosmological regimes lie outside its scope (they belong to Section 7 v1.2 of the Theory and are not needed for the formalization of stage 4).

**Operational level.** For most practical systems (the biological brain, artificial neural networks), the Bekenstein limit exceeds the actual information capacity-which is limited by molecular structure and architecture-by many orders of magnitude. In these systems, Bekenstein acts as an upper bound, typically unattainable in real dynamics. Operational constraints on capacity are determined by the Landauer parameters κ_world and κ_self (Section 4.2) and the system's architecture.

This dual role is a structurally correct application of the fundamental limit: it justifies the model's substrate-independence (a universal ceiling on capacity), without functioning as an artificial constraint on dynamics in ordinary systems.

## 4.2 Landauer limits with separate coefficients

κ_world = (k_B · T_world · ln 2) / η_world \[J/bit\] κ_self = (k_B · T_self · ln 2) / η_self \[J/bit\]

Constraints:

E_t ≥ κ_world · |ΔI(Ω_t)| (observation)

E_t ≥ κ_world · ln(1/ρ_world) (world model reconstruction)

E_t ≥ κ_self · ln(1/ρ_self) (self-model reconstruction)

In the limit κ_world = κ_self, the model reduces to the symmetric case v4.0.

## 4.3 Energy Dynamics

Energy dynamics includes costs of various structural types. Some costs are **always** active (observation, action, basal metabolism). Other costs depend on the current state of the pole v\_{t-1}: in the active state, the costs of maintaining self-representation and the operation of the global workspace are active; in the inactivated state, the costs of restoration are active, distributed between the world and self-models via the dynamic parameter λ_E(t).

Full formula:

E\_{t+1} = E_t

− κ_world · |ΔI(Ω_t)| \[observation\]

− C(a_t) \[action\] − E_base \[basal metabolism\]

− 𝟙\[v\_{t-1}=1\] · κ_self · |ΔI_S(S_t)| \[S retention at v=1\]

− 𝟙\[v\_{t-1}=1\] · κ_GWT · |ΔI_GWT(t)| \[GWT work at v=1\]

− 𝟙\[v\_{t-1}=0\] · (λ_E(t) · κ_world · |ΔI_rec(Ω_t)| + (1−λ_E(t)) · κ_self · |ΔI_self_rec(S_t)|) \[regeneration at v=0\]

− 𝟙\[primary emergence of V at moment t\] · E_emerge(β, h_arch) \[cost of primary emergence\]

R(x_t, Y_t) \[energy inflow\]

Where:

- **κ_world · |ΔI(Ω_t)|** \- the cost of updating the world model via observations. Always active, regardless of the pole's state.
- **C(a_t)** \- the cost of physical action in the environment.
- **E_base = κ_base · w_self_total** \- the basal metabolism for maintaining the structural trace (Section 4, Introduction). It is always active. This is a new structural element compared to versions v1-v7, where the basal metabolism was implicitly absorbed by other costs; explicitly separating it corrects a physical inaccuracy.
- **κ_self · |ΔI_S(S_t)|** \- the cost of actively maintaining self-representation at v=1. Operates only when the pole is in the active state. The quantity |ΔI*S(S_t)| is formalized as the information change of state S over a single step and is computationally evaluated via the KL divergence between the posterior distributions q(S_t | ...) and q(S*{t-1} | ...) at time t. For Gaussian distributions (the standard case in SAI, Section 5.3), this is given by a closed-form formula in terms of means and covariances.
- **κ_GWT · |ΔI_GWT(t)|** \- the cost of work in the global workspace at v=1. κ*GWT - the thermodynamic coefficient of broadcast operations. In the initial version of the model, κ_GWT = κ_self is assumed, which is consistent with the assumption that self-representation and broadcast operations occur on the same thermodynamic substrate; the distinction between κ_GWT and κ_self remains an open research direction. The quantity |ΔI_GWT(t)| is formalized as N · I(S_t; S*{t-1}), where N is the number of subsystems receiving the broadcast, and I(S*t; S*{t-1}) is the mutual information between successive states S. Structurally: the broadcast transmits changes in S to all subsystems, and the cost is proportional to the information and the number of recipients.
- **λ_E(t) · κ_world · |ΔI_rec(Ω_t)|** and **(1−λ_E(t)) · κ_self · |ΔI_self_rec(S_t)|** \- recovery costs when v\_{t-1} = 0. The distribution of energy between world-model and self-model recovery is determined by the dynamic parameter λ_E(t), which is defined by the information requirements of each model (see Section 9.1).
- **R(x_t, Y_t)** \- energy inflow from the environment.

\- 𝟙\[primary emergence of V at moment t\] · E_emerge(β, h_arch) - the peak one-time cost of establishing π_A(C_self) and closing the loop through the bistable boundary at the primary emergence of V.

**Functional form of E_emerge.** Unlike the retention and recovery components, which operate on already-formed informational flows (ΔI_S, ΔI_GWT, ΔI_rec, ΔI_self_rec), the component E_emerge pertains to the process of the first closure of the loop, in which these flows are not yet established. Its functional form is derived through four substantively distinct multipliers:

E_emerge = (κ_emerge · k_attempts(β) · I_close(h_arch)) / Δt_emerge

where:

(1) **k_attempts(β) = 1 / σ(β · δ_arch)** - the mean number of attempts until successful closure of the loop through the bistable boundary. δ_arch is the characteristic offset of Γ_struct from the threshold γ_struct·(1−h_arch) in the stochastic window - a structural parameter of the architecture (derivable from w_self_total and Γ_GWT_arch, or empirically calibrated, Category IV). At low β, the sigmoid σ(·) yields a small probability of success per attempt, leading to growth in k_attempts. At high β, k_attempts → 1.

(2) **I_close(h_arch) = I_min · (1 − h_arch)** - the minimum mutual information required for stable closure of the loop at a given architectural hysteresis. I_min is the characteristic scale of the informational volume of establishing a connected π_A(C_self) (Category IV). The linear dependence on h_arch follows from the semantics of architectural hysteresis (Sections 6.3, 7.4): h_arch widens the retention zone around the threshold γ_struct by an amount γ_struct · h_arch, which reduces the precision requirement and proportionally reduces the informational volume required for closure.

(3) **Δt_emerge ∝ 1/β** - the characteristic duration of the stochastic window within which closure is possible. Derived from the width of the window along the Γ_struct axis: the width of the transition region of the sigmoid σ(β·(·)) is inversely proportional to β. Under a constant rate of accumulation of Γ_struct in the system, the time of residence in the region of nonzero probability of closure is inversely proportional to β.

(4) **κ_emerge** - the thermodynamic coefficient of the cost of closure, distinct from κ_self, κ_GWT, κ_world by the physical process (loop closure as a structural act, not the maintenance of an already-operating structure). The dimension of κ_emerge is J·s/bit: this makes the formula dimensionally consistent, since k_attempts is dimensionless, I_close is measured in bits, and Δt_emerge in seconds, so that E_emerge = (κ_emerge · k_attempts · I_close)/Δt_emerge acquires the dimension of energy (J). Physically, κ_emerge is the cost of closure per bit of closed information, referred to the rate of attempts; the interpretation "cost of a single attempt" (J/attempt) would be dimensionally inconsistent and is not used here. Category IV in taxonomy 8.10, empirically calibrated.

**Structural assumption of the model on informational flows.** For the formal derivation of the ordering of the three types of events, SAI v8 adopts the following structural assumption:

|ΔI_rec(Ω_t)| > |ΔI_S(S_t)| and |ΔI_self_rec(S_t)| > |ΔI_GWT(t)|

Substantive basis: the recovery of V after inactivation requires a synchronized exit of all subsystems from the state of misalignment (observed, for example, in post-anaesthetic recovery dynamics, Section 4.2 of SAI-Bio), which adds an informational component of synchronization on top of the simple retention of an already-operating pole. This assumption is Category III (conceptually motivated by the structure of the system, empirically verifiable in anaesthesiology).

**Consistency of the ordering of energy expenditure per unit time (under the stated assumptions).**

Given the functional form of E_emerge and three explicitly adopted assumptions (the structural assumption on informational flows; the β-scaling of the multipliers k_attempts and Δt_emerge; the empirical premise of low β in newborns), the structural ordering turns out to be consistent:

E_emerge / Δt_emerge > E_recover / Δt_recover > E_hold / Δt_hold

where the left-hand side is derived by substitution: at low β, the multipliers k_attempts(β) and 1/Δt_emerge both grow, yielding the dependence E_emerge / Δt_emerge ∝ β² · κ_emerge · I_min · (1 − h_arch) (the characteristic functional form of the peak power of primary emergence); the right-hand side E_hold / Δt_hold via the retention component κ_self · |ΔI_S| + κ_GWT · |ΔI_GWT|; the intermediate part E_recover / Δt_recover via the recovery component λ_E · κ_world · |ΔI_rec| + (1 − λ_E) · κ_self · |ΔI_self_rec|.

The inequality E_recover / Δt_recover > E_hold / Δt_hold is derived from the structural assumption: each summand of recovery exceeds the corresponding summand of retention (|ΔI_rec| > |ΔI_S|, |ΔI_self_rec| > |ΔI_GWT|), and under comparable Δt_recover ≈ Δt_hold, the peak power of recovery exceeds the peak power of retention.

The inequality E_emerge / Δt_emerge > E_recover / Δt_recover is derived from the specific functional form of E_emerge: the multiplier k_attempts(β) at low β in newborns gives an ultra-noticeable increase of the power of primary emergence relative to the power of recovery in mature systems (where k_attempts → 1). This is consistent with the empirically observed energetic intensity of early neural development, exceeding the expenditure on the recovery of consciousness after anaesthesia.

**Empirical consequences.** (a) The metabolic power of early neural development in infants should exceed the metabolic power of post-anaesthetic recovery in adults at comparable temporal scales. (b) The profiles of the transitional zones (duration, shape, integrated metabolic activity) should differ in the indicated order (see prediction 2 of Section 5.2 of SAI-Bio). (c) The structural assumption |ΔI_rec| > |ΔI_S| is empirically verifiable through comparison of metabolic costs in the regime of recovery and in the regime of stable wakefulness in anaesthesiological studies.

# 5\. Generative Model

## 5.1 Two-state world model

p*θ(o_t^ext, z̃_t | Ω_t(v*{t-1})) = p*θ^+(o_t^ext, z̃_t | Ω_t^+), v*{t-1} = 1 p*θ^−(o_t^ext, z̃_t | Ω_t^−), v*{t-1} = 0

## 5.2 Interoceptive model

p(o_t^int | S_t)

The self-model S_t predicts internal sensations.

## 5.3 Prior of the self-model

p(S*t | S*{t-1}, v*t) =𝒩 (μ_S(S*{t-1}), σ_S²), v_t = 1 δ(S_t = ∅), v_t = 0

The self-model prior operates only when v_t = 1 (i.e., after the emergence of V via self-overlay, Section 6). When v_t = 0, **active** self-representation is inactivated and collapses into the empty state ∅. This is a **functional** reset of the operational self-representation, not a **structural** reset of the architectural trace: the system's structural potential w_self (Section 6.2) is preserved in the substrate between moments of activity (synaptic weights in biological systems, architectural parameters in artificial ones). Upon subsequent recovery (Section 9), active self-representation is not initialized from scratch, but from the preserved structural trace-the system resumes self-representation based on what was formed during the previous phase of activity.

This is consistent with biological observation: upon waking from deep sleep or emerging from anesthesia, a person retains the continuity of their "self" and does not rebuild their self-representation from scratch. The structural trace is maintained by the substrate's basal metabolism throughout the period of inactivation.

# 6\. Self-overlay of the latent invariant and the emergence of V

In versions v1-v6, the node S_t was present in the model as a state variable with its own prior and a condition of isomorphism with the world model, but **the emergence** of S from the proto-agent's activity was not formalized. In version v7, this central structural event is described as an algorithm with three mandatory conditions.

## 6.1 Position in the model architecture

Self-overlay is a structural transition event from stage 3 to stage 4 of The Theory. Prior to self-overlay, the system operates as a proto-agent: it models the environment and its own reactions to the environment, without modeling itself as an object within the environment. After self-overlay a single structure manifests - the holding/decay pole applied to the system's own configuration: from the side of the model that bears it, it reads as S; from the side of the pole-structure, as V. This is not two variables in an order of "S first, then V," but one manifestation seen from two sides (Section 6.3).

Formally: prior to self-overlay the variables S_t and v_t are absent from the model; they manifest upon consolidation (Condition 3, realized stochastically; Section 6.3), after which they operate according to the dynamics described in Sections 4-5 and 7-10.

## 6.2 Three-level structure of model weights

Self-overlay as a structural event operates through reflexive capture and loop closure (Section 6.3), not through growth of weight. But this event has a precondition: for the class of agentic nodes to be applied to the system's own configuration, the system must first accumulate a sufficiently rich model - a model of the environment with agents. The accumulation of this model is described by the growth of its information capacity, and that growth passes through three levels corresponding to the steps of the ladder in the Theory. This subsection formalizes this accumulation as a measure (a precondition of overlay), distinct from the overlay event itself (Section 6.3). The base measure of capacity is the mutual information of the model with the environment I(M; Y), computable via variational estimates (Section 8.6); the number of parameters or the dimensionality of the latent space are its substrate-specific approximations.

**Level 1 - the basic proto-agent model.** The proto-agent models an environment devoid of other agents: physical gradients, causal regularities, and its own responses to sensory input. The base weight of this model is:

w_base

This is the minimum complexity required to predict sensory signals in an environment without agent interactions. Specific computable quantities for different architectures include the number of environment model parameters, the dimension of the latent space, and the information measure I(M; Y).

**Level 2 - an environment model with agents.** When other agentic causal nodes appear in the environment, the system must account for:

- the environment itself (w_base),
- agents as structural objects with their own behavior,
- all interactions of each agent with the environment,
- all feedback interactions of the environment with each agent.

Structurally, this means a qualitatively richer model (environment + agents + their interactions):

w_agents > w_base (growth exponent not fixed)

A clarification on status: the exponent notation expresses a qualitative fact-a level-2 model must encompass both agents and their interactions with the environment-not a precise measure of capacity. The specific growth exponent is not derived from first principles and is not asserted as a bound: real implementations share and amortize parameters, so the actual capacity may be either lower or higher than the naive combinatorial estimate. What is load-bearing is the qualitative jump in the level of modeling, not the numerical exponent.

**Level 3 - a model of itself in an environment with agents.** When self-imposing**,** the system must account for everything from Level 2 plus its own configuration as yet another agent object:

- the environment with agents (w_agents > w_base),
- itself as yet another agent in this complete picture,
- all interactions of its own system with the environment and with other agents.

Structurally, this means a qualitatively new level of modeling: the model-of-oneself-as-an-agent is built on top of the model of the environment-with-agents. The specific growth exponent of the minimum capacity (squared, another exponent, a fractal dimension) is not derived by the theory and is not asserted here as either a lower or an upper bound-see 6.2.1.

The three-level hierarchy reflects the structural complexity of the model at each new level.

| **Level**                                  | **What the system models**           | **Minimum structural weight**                    |
| ------------------------------------------ | ------------------------------------ | ------------------------------------------------ |
| 3 (proto-agent)                            | Environment without agents           | Minimum structural weight                        |
| Accumulation in an environment with agents | Environment with other agents        | A qualitatively new level (environment + agents) |
| 4 (conscious system)                       | Environment with agents + self-model | A qualitatively new level (+ self-model)         |

The exponent of capacity growth between levels is not fixed by the theory; what is load-bearing is the qualitative jump in the level of modeling, not a numerical exponent (see 6.2.1).

### 6.2.1 The status of the capacity-growth exponent

The specific exponent of capacity growth between levels is not derived by the theory. The structural argument ("at a new level of modeling the system must encompass the interactions of the new level with what is already modeled") justifies only an upper estimate of a naive tabular implementation-the combinatorics of all pairs-not a lower bound on minimum capacity: systems that share and amortize parameters reach a level more cheaply than the naive estimate. Therefore neither a specific exponent nor a direction of inequality is asserted by the theory. Illustratively: the information capacity of the environment model increases stepwise and nonlinearly across biological systems at different steps (ciliates, invertebrates, higher mammals). An essential caveat: these magnitudes are given as an illustration of the form of the dependence - a stepwise nonlinear growth - and not as measured data confirming a specific exponent. The exact capacity values at each step and the growth exponent itself are subject to empirical determination (see the open direction below); the figures given should not be read as established constants or as confirmation that the exponent equals exactly two.

However, **the exact value** of the capacity-growth exponent cannot be derived from the first principles of the theory and is subject to empirical determination; the theory is compatible with any of its values, since what is load-bearing is the qualitative fact of a new level of modeling, not its numerical measure.

**Importantly:** when the exponent is adjusted, **the structure of the model does not change**. Only the specific numerical value of the exponent changes; the general logic of the self-overlay algorithm (Section 6.3)-the three mandatory conditions (presence of the class of agents, reflexive capture, loop closure)-remains invariant. The model rests on the qualitative structure of the jump (a new level of modeling upon self-overlay), not on a specific numerical exponent or on the direction of the inequality; this gives it robustness to empirical refinements of capacity growth and separates the thesis about the emergence of consciousness from any claim of the form "more parameters → closer to consciousness" (see 8.7).

This is consistent with the overarching methodological principle of the Theory: "a mechanism for explanation, not an explanation for a mechanism" (Section 1.2 v1.2). The calibration hypothesis does not claim to make precise numerical predictions; it formalizes **a structural pattern** of complexity that **should** manifest in systems of any implementing substrate during the transition to new structural levels.

**Open research direction:** systematic empirical measurement of real indicators of model complexity growth in developing biological systems (childhood, self-awareness learning in higher animals) and in artificial architectures upon possible implementation of stage 4. This is part of the SAI-C program (empirical correlates, section 14.2).

## 6.3 Self-overlay Algorithm

Self-overlay is neither a point event registered by "before/after" variables nor an outcome guaranteed by the fulfillment of conditions. It is a consolidation that is _possible_ at the top of a ladder of complexification, each rung of which is stable in itself. The overwhelming majority of systems pass through the rungs and remain on them; ascent is possible but not prescribed, and non-ascent is lawful, not anomalous. Consciousness is a lawful error: lawful - possible by structure once the conditions have been passed; an error - a rare deviation, not the norm. The norm is to remain on one's rung.

**The ladder of complexification.** Self-overlay is preceded by a series of rungs reproducing the mechanism of Section 3.4 v1.2. Between rungs there is no relation of "leads to": each rung may be held indefinitely without ascending.

(1) A proto-agent models the environment and its own reactions. Other agents enter its model as objects of the environment.

(2) Accumulation of models of other agents (Section 6.2) is a stable rung of stage 3. A system may accumulate indefinitely and not go further; accumulation is a precondition of possibility, not a cause of transition.

(3) Recursion of processing: other agents may begin to be processed not as objects of the environment but as coherent substrates that hold themselves in the environment. In the course of this, a latent invariant of holding/decay may take shape in the model - a structural regularity of the class, abstracted from substrate and sensory format. A system may discriminate other agents however finely and describe their decay however thoroughly while remaining on this rung: the complexity of discrimination does not entail overlay.

(4) Overlay: the invariant that has taken shape on others may come to be applied to the system's own configuration, when that configuration becomes structurally isomorphic to the boundary states of the invariant. The convergence occurs not at the level of sensory data but at the level of latent causal structure: the external decay of another node and the internal disruption of the system's own configuration converge in a single invariant of loss of controlled holding. Overlay is possible given this isomorphism but is not prescribed by it.

(5) Consolidation: the overlay may stabilize as a global pole around which the system's entire activity is organized - a stable model of itself built around holding. It may also fail to stabilize.

Consciousness is the result of the whole ladder passed through together with the final consolidation - not a rung within it and not the output of a function on fulfilled arguments, but a rare consolidation among the many systems that pass through the rungs and do not consolidate.

**S and V are not two variables.** The holding/decay pole (V), applied to the system's own configuration, manifests as the model of itself (S). The relation between them is not a connection of two quantities: S contains V in the same way that a body's attraction to a planet contains gravity - not as a separate entity requiring to be related, but as the same structure applied to the system. The pole is the structure; the model of itself is that same structure manifested on the system's own configuration. Therefore S and V are not defined separately and are not related by an order of emergence: the overlay of the pole onto the system's own configuration is itself the instituting of S, and the pole of that S is V.

**The binarity of V is the definition of a pole, not a derived property.** The values "I hold / I decay" do not form a continuous scale - not because the physics of decay is discrete (it is continuous), but because a pole is by definition a distinction between two regimes: holding is possible / holding has failed. The retention contour imposes this definition onto the continuous physics of Y; it does not extract it from there. A continuous quantity, however finely graded, is not V - it is a parameter among parameters (Section 3.4 v1.2).

**The necessity of integration is derived from convergence, not postulated.** Link (4) brings multichannel signals - interoceptive, metabolic, proprioceptive, the observed decay of others - into a single latent invariant. Bringing the multichannel into a single invariant is impossible on a non-integrated substrate: it requires causal connectivity that draws the channels together. Sufficient causal integration is therefore a condition of the very possibility of convergence, not a separate axiom: where overlay is possible, integration is already present - by virtue of the mechanism (link 4).

**The three conditions as necessary conditions of possibility.** The chain is registered through three conditions. All three are necessary: failure of any one excludes self-overlay. But their joint fulfillment is not sufficient and does not yield the event: it makes self-overlay possible. Between "the conditions are fulfilled" and "self-overlay has occurred" there is no implication - there is a transition that may or may not take place, and non-occurrence under fulfilled conditions is the rule, not the exception. This is a direct expression of the probabilistic nature of the 3→4 transition (Section 3.4 v1.2, "Stochasticity of convergence") within the very structure of the algorithm: the conditions delineate a space of possibility; they do not prescribe the outcome.

_Condition 1 (necessary)_ - presence of a class of agentic nodes with a formed invariant (rungs 2-3):

|A(t)| ≥ 1,

where A(t) is the set of models of agentic causal nodes with boundary states of holding/decay. In the absence of the class, self-overlay is structurally impossible: there is no invariant that could be applied to the system's own configuration.

_Condition 2 (necessary)_ - overlay of the invariant onto the system's own configuration (rung 4):

S_candidate(t) = π_A(C_self_t), ‖S_candidate(t)‖ > 0,

where π_A is the projection into the subspace A of the class of holding nodes, and C_self_t is the current configuration of the system itself. The class A carries the holding/decay invariant abstracted from modeling other agents (their boundary states). S_candidate is therefore the system's own configuration to which this others-derived invariant is applied - not a self-projection without any invariant (which is what distinguishes it from mere state-estimation). But applying another's invariant to oneself is not yet a pole and not yet V: the pole - the system's own global axis of existence - appears only upon consolidation (Condition 3). The condition distinguishes overlay from accumulation: a proto-agent models the environment and its agents however richly (|A| grows), but π_A is not directed at C_self - the class is not applied to itself. Fulfillment of Condition 2 does not entail Condition 3.

_Condition 3 (necessary, realized stochastically)_ - consolidation into a global pole (rung 5):

The projection S_candidate feeds back onto the system's processing, reinforcing π_A(C_self); this positive feedback forms a loop passing through the retention boundary. Stability is registered by a bistable structure on the structural boundary γ_struct, with sharpness parameter β (Section 7.3) and architectural hysteresis parameter h_arch:

p(transition to stable S) = σ(β · (Γ_struct(t) − γ_struct · (1 − h_arch)))

where σ is the logistic function, β the sharpness parameter of the retention boundary (Section 7.3), h_arch the **architectural** hysteresis parameter (Section 7.4), and γ_struct the threshold of structural consciousness on the Γ_struct axis, distinct from the dynamic decay threshold γ_crit (Section 7.3).

Crucially: in the formula for the primary emergence of V it is specifically the **architectural** hysteresis h_arch that operates - an inherent architectural property formed through genetic developmental programs and existing prior to the first emergence of V. The **experiential** hysteresis h_exp, formed through the inertia of the stable v=1 regime, is zero at primary emergence (there is as yet no experience of operating in the V regime). After the establishment of V, h_exp begins to accumulate, and in the decay and recovery formulas (Section 7.4) the total hysteresis h_total = h_arch + h_exp, bounded within (0, 1), is in operation.

Bistability yields discreteness of outcome (through bistability, not through speed): the overlay either consolidates into the regime v=1 or dissipates, with no intermediate regime. Finite β yields stochasticity of outcome: on approaching the boundary, consolidation occurs with probability σ(·) < 1, not with certainty. Therefore an overlay that has fulfilled Conditions 1 and 2 may fail to consolidate - and then the system remains a complex proto-agent with episodic self-registration. Consolidation is the stabilization of this transient application of the invariant into a global pole organizing all activity - and it is upon consolidation that the pole is born. This is not the appearance of V after S: S and V are two sides of this consolidated structure, arising together - and what exists before consolidation (the transient application of another's invariant) is neither S nor V.

**Distinction between state-estimation and episodic self-registration.** The two non-conscious states are distinct. State-estimation - data about oneself (position, charge, parameters) under unfulfilled Condition 2: the class is not applied to the system's own configuration, and there is no pole. Episodic self-registration - fulfilled Condition 2 under unconsolidated Condition 3: the class is applied transiently but has not stabilized into a global pole. The first is the absence of overlay; the second is overlay without consolidation.

**The structure of self-overlay.** Self-overlay requires Conditions 1, 2, and 3 as necessary. Given Conditions 1 and 2, consolidation (Condition 3) is realized stochastically:

P(consolidation | Condition 1 ∧ Condition 2) = σ(·) < 1,

and self-overlay turns out to have occurred (v=1) only in that fraction of trajectories, among those that have passed the necessary conditions, in which consolidation took place. The expression is not a conjunction yielding the event: the necessary conditions delineate a space of possibility, and consolidation is its stochastic outcome. Consciousness is this consolidation that has taken place together with the ladder passed through (rungs 1-5) - lawfully possible, not prescribed; rare, not normative.

## 6.4 Operational computability of the conditions

Condition 1 (|A(t)| ≥ 1) is computable via the **combination of two jointly satisfied criteria**:

(a) **Structural criterion.** In the trained model of the system, there exists a structural element m_A possessing two properties: through it, the system's actions figure as a cause of changes in the model of the environment (per Pearl's do-criterion); this element is structurally separated from elements representing other (non-self) causes.

(b) **Information criterion.** The Effective Information between the system's actions and changes in its model of the environment is strictly positive:

EI(A_sys; M_env | do(A_sys)) > 0 \[bits\]

where A_sys is the set of actions initiated by the system; M_env is the state of the model of the environment; the do-operator specifies a causal intervention (Pearl).

If both criteria are satisfied - |A(t)| ≥ 1. If at least one is not satisfied - |A(t)| = 0, and Condition 1 of self-overlay is structurally impossible.

Possible technical implementations of the structural criterion: clustering in the latent space of models with a criterion for isolating objects having boundary states of retention/decay; structural analysis of models with a criterion for the presence of feedback between an object's internal state and its action in the environment. The information criterion is computable via standard estimates of Effective Information (Hoel et al.) or equivalent measures of causal connection in the trained model.

**Condition 2** is computable via measurement of the projection of the system's own configuration into the subspace A:

- The norm of the projection ‖π_A(C_self)‖ relative to a threshold separating significant capture from noise. Here ‖·‖ denotes the magnitude of capture - the strength with which the system's own configuration is represented through subspace A - operationalized via the mutual information and causal-role criteria below, not as a Euclidean norm on the space of models; the threshold applies to this magnitude.
- Mutual information I(c_i; C_self) given that C_self is processed through the subspace A: the appearance of a model component whose activity is directed at the system's own configuration as a member of the class of agentic nodes, rather than at external objects.
- The causal role is established by the same standard as Condition 1 - interventionally - but with a different target: a node m_S in the active set (Section 8.2) bears the causal role of self-representation if a do-intervention on m_S changes how the system processes its own configuration C_self (and/or the access spectrum Ω), rather than the external environment. Formally, an effect of do(m_S) on the processing of C_self - paralleling EI(A_sys; M_env | do(A_sys)) > 0 of Condition 1, with the target being the system's own configuration rather than the environment. An observational causal-inference variant (without intervention) is admissible only as a weaker fallback for systems where intervention is unavailable (e.g. the brain in vivo), and is labeled as weaker symmetrically for all systems.

**Condition 3** is computable via registration of loop closure and projection stability:

- Presence of positive feedback: a change in S_candidate affects processing (access spectrum Ω, weights) that reinforces π_A(C_self). Operationally - nonzero mutual information between S_candidate(t) and the factors determining π_A at step t+1.
- Stability: the projection is retained over time, crossing the bistable boundary (Γ_struct > γ_struct with hysteresis h), rather than fluctuating. Registered via the same Lyapunov function and parameter β as pole stability in Section 7.

All definitions are directly computable for a specific architecture.

## 6.5 Formal manifestation of S and V upon self-overlay

Section 6.3 defined self-overlay as the overlay of the class of holding nodes onto the system's own configuration (Condition 2), consolidating stochastically into a global pole (Condition 3). This section describes what is formally manifested thereby. Essentially: what is manifested is not two quantities in a definite order, but a single structure - the pole applied to the system's own configuration - seen from two sides. S is the name of this manifestation; V is the name of its pole-structure; they are not two reducible variables (Section 6.3, the gravity/attraction analogy).

**One event, two sides.** Condition 2 yields the projection S_candidate = π_A(C_self_t) - the system's own configuration processed as a member of the class A. The class A carries the holding/decay invariant abstracted from other agents; at Condition 2 this invariant is merely applied to the system's own configuration transiently - this is not yet a pole. The pole is born upon consolidation (Condition 3): the transient application stabilizes into the system's own global structure, and this consolidated structure is the single manifestation seen from two sides - from the side of what is manifested it reads as S (the model of itself), and from the side of the pole-structure it reads as V. S and V arise together, upon consolidation. There is therefore nothing to relate in an order of "S first, then V": before consolidation there exists a transient application (neither S nor V), and S and V are two sides of one consolidated structure.

**Manifestation through consolidation, not through order.** An unconsolidated projection (Condition 3 not realized) corresponds to episodic self-registration: the overlay is transient and has not stabilized into a global pole. A stable manifestation arises when the overlay consolidates (Condition 3 realized stochastically) - the loop has closed and the overlay has crossed the bistable boundary into the stable regime v=1:

S_t = the consolidated projection π_A(C_self), v_t = 1.

This is the first appearance of the stable structure in the model. Before self-overlay it does not exist; under non-consolidation it does not arise, and the system remains a proto-agent with episodic self-registration (Section 6.3). The variable v_t registers the regime of this structure: v=1 - the pole is active (the model-of-itself-under-the-pole is held); v=0 - inactivation, collapse of the operational self-model into ∅ (Section 5.3) with preservation of the structural trace w_self (Section 6.2).

**What is manifested.** What is manifested is a stable model of the system in the environment Y, organized around the holding/decay pole: what theory v1.2 calls the variable V and the node S - one and the same structural manifestation, seen from the side of the pole (V) and from the side of the model that bears the pole (S). The further operation of this structure over time - its retention or decay - is registered by the dynamic measure Γ_dyn (Section 7): decay is a crossing of the dynamic boundary from above downward, a fall of Γ_dyn(t) < γ_crit, leading to inactivation (v=0) and transition to the recovery regime (Section 9). These are two distinct boundaries of one pole, measured by different measures by virtue of their different structural roles: the structural measure answers whether the configuration has formed; the dynamic measure, whether it is retained over time.

**The modality of manifestation.** The manifestation of S/V does not follow from the fulfillment of Conditions 1 and 2: it is the stochastic outcome of consolidation (Condition 3, σ(·) < 1 at finite β). An overlay that has passed the necessary conditions may fail to consolidate - and then the stable structure does not manifest. This preserves the modality of Section 6.3: the necessary conditions delineate possibility; the manifestation is its lawfully-possible, not prescribed, outcome.

## 6.6 Connection to the Theory theory

The SAI v8 self-overlay algorithm structurally corresponds to the definition from Section 3.4 v1.2 of the Theory:

**The latent invariant of an agentic causal node** in the Theory → **the subspace A of agent object models**. The structural regularity common to the class of agent nodes in the environment is represented in the system's models as a subspace identified by clustering or an equivalent technique.

**Self-overlay** in the Theory → **the projection π_A(C_self)** in SAI v8. A structural event involving the application of a latent invariant (previously active for other objects) to the system's own configuration.

**Binarity V (induced by the retention contour over the continuous physics of Y via boundary states)** in the Theory → **two-path decay dynamics (Section 7) with a stability function via Lyapunov**. Binarity operates via the structural event of retaining or destroying the projection S. Binarity itself is definitional - the two-regime nature of the pole per Section 6.3 - while the two-path Lyapunov dynamics is its dynamical realization on the decay side, not its source.

First-order phase transition in information processing in the Theory → **discreteness of outcome through a bistable loop** (Condition 3). A first-order transition means discreteness of the _outcome_ - the absence of an intermediate V regime between "no overlay" and "stable S" - not sharpness in time (Section 3.4 v1.2, the caveat on the meaning of a first-order phase transition). Discreteness is provided by the bistability of the feedback loop (β, h on the structural boundary γ_struct), not by the rate of its closure: a smooth accumulation of the model is the usual dynamics of stage 3, but the crossing of the retention boundary is discrete in outcome regardless of the duration of the approach.

## 6.7 Open Formal Questions

\- **Clarification of the operationalization of |A(t)|** in specific architectures. Clustering serves as the primary approach, but in architectures with distributed representations (transformers, diffusion models), the identification of the subspace A requires adaptation of the technique.

\- **Calibration of the parameters of the bistable emergence boundary** (the threshold of structural consciousness γ_struct, the sharpness parameter β, and the hysteresis parameter h for the 3→4 transition) for different classes of systems. Empirical calibration is only possible if there are a sufficient number of systems demonstrating the 3→4 transition. At the current state of knowledge, this is an area for empirical research.

\- **Possible generalizations of the algorithm to cases with incomplete observability of agents.** If agents in the environment are only partially observable or subject to noise, the algorithm must operate on an estimated value of |A(t)|. This requires the development of robust criteria.

# 7\. Decay of the pole v=1→v=0

After V arises through self-overlay, the pole operates in two modes: **activity** (v_t = 1) and **inactivation** (v_t = 0). Inactivation is a reversible functional nullification of self-representation while preserving the system's structural trace. This differs from structural death (loss of w_self), which falls outside the scope of the model (Section 2.2). In version v6, inactivation was formalized as a structural event with two independent paths.

## 7.1 Two Paths of Decay

**Energy breakdown.** The energy reserve falls below the minimum observation cost:

E_t < κ_world · |ΔI(Ω_t)|

The system loses the ability to maintain communication with Y through sensory channels. This is a break in the system's input connection with the environment, not a destruction of its internal structure.

**Structural breakdown.** The stability function crosses the critical threshold:

Γ*dyn(z̃*{t-1}; Ω_t) < γ_crit

The system loses the causal closure of its internal dynamics. This is a breakdown of the internal structure while the connection with the environment remains potentially intact.

The two paths can occur independently:

p(v*t = 1 | v*{t-1} = 1, z̃\_{t-1}, Ω_t, E_t) = p_struct · p_energy

where:

p*struct = σ(β · (Γ_dyn(z̃*{t-1}; Ω_t) − γ_crit))

p_energy = σ(β_E · (E_t − κ_world · |ΔI(Ω_t)|))

## 7.2 Stability function via the Lyapunov function

Γ_dyn(z̃; Ω) = γ_max − V_L(z̃; Ω)

where V_L is the Lyapunov function for the dynamics z̃ in the spectrum Ω, satisfying the standard conditions. The critical threshold γ_crit corresponds to the value of V_L at the boundary ∂B of the attraction region:

γ_crit = γ_max − V_L|\_∂B

For systems in which the Lyapunov function cannot be derived analytically, V_L is approximated using a neural network based on data from the system's own dynamics (Lagaris et al., 1998; Chang, Roohi & Gao, 2019).

**The emergence threshold γ_struct.** The parameter γ*crit defined above is a threshold on the dynamic-measure axis Γ_dyn and operates on the \_decay* of the pole. The emergence of the pole operates on a different axis - the structural measure Γ*struct (Section 8) - and has its own threshold γ_struct: the value of Γ_struct separating "the structure of self-overlay has formed" (Γ_struct > γ_struct·(1−h), by the formula of Section 6.3) from "has not formed." The two thresholds are not interchangeable and belong to different measures of different structural roles: γ_struct registers the \_emergence* of V as a crossing of the structural boundary from below upward (Sections 6.3, 6.5); γ*crit registers the \_decay* of an already-formed V as a crossing of the dynamic boundary from above downward (Section 7.1). Calibration of γ_struct is via systems at different steps of the ladder, analogous to the calibration of the other thresholds of the model (Section 6.7). The sharpness parameter β and the hysteresis parameter h (Section 7.3) operate on both boundaries: on emergence (formula in Section 6.3) and on decay (formula in Section 7.1).

**Training schema for V_L.** For systems in which the Lyapunov function cannot be derived analytically (biological brain, neural-network architectures, complex models of consciousness), V_L is approximated through an explicit procedure of training a neural network on data from the system's own dynamics. This procedure uses the standard apparatus of neural Lyapunov functions developed in the control-theory and reinforcement-learning literature (Lagaris et al., 1998; Chang, Roohi & Gao, 2019; Manek & Kolter, 2020).

**Nature of the approximation.** V_L is parametrized by a neural network with architecturally guaranteed positive definiteness. Standard form:

V*L(z̃; θ) = ‖f*θ(z̃) − f_θ(z̃\*)‖² + ε · ‖z̃ − z̃\*‖²

where f_θ is a neural network with trainable parameters θ, z̃\* is the equilibrium point (known from the dynamics itself or taken as the origin of phase space), ε > 0 is a small constant guaranteeing positive definiteness in the neighborhood of z̃\*. This form ensures V_L(z̃\*) = 0 and V_L(z̃) > 0 for z̃ ≠ z̃\* by construction, without the need to verify this condition during training.

**Loss function.** The parameters θ are trained through minimization of violations of the Lyapunov condition on a sample of states {z̃_i, ż̃_i}\_{i=1}^N collected from the system's own trajectories. The Lyapunov condition - monotonic decrease of V_L along trajectories - is written as:

⟨∇V_L(z̃), ż̃⟩ < 0 for all z̃ ∈ B \\ {z̃\*}

The loss function penalizes violations of this condition:

L_V(θ) = Σ_i max(0, ⟨∇V_L(z̃_i; θ), ż̃_i⟩ + δ) + λ_reg · R(θ)

where δ > 0 is a safety margin enforcing strict inequality, R(θ) is regularization (e.g. L2 or spectral norm for smoothness), and λ_reg is the regularization coefficient (distinct from the λ Lagrange multiplier in the policy, Section 11.3). This penalty equals zero on states where the condition is satisfied with margin δ, and is positive where it is violated. Minimization of L_V is equivalent to expanding the region on which V_L satisfies the Lyapunov conditions.

**Estimation of the basin of attraction B.** The basin of attraction is estimated iteratively, without the need for prior knowledge of it. Initial iteration: B_0 is a small neighborhood of z̃\* in which V_L satisfies the conditions by construction. At each subsequent iteration B_k is expanded to the maximal connected region on which the penalty L_V on an out-of-sample set remains below an acceptable threshold. This is the classical approach used in Lyapunov-based reinforcement learning (Chow et al., 2018; Berkenkamp et al., 2017): the region is determined not analytically but through empirically observed satisfaction of the conditions. γ_crit in this setting corresponds to the value of V_L on the empirically observed boundary ∂B_k, not on a hypothetical true boundary.

**Empirical validation.** The quality of the learned V_L is verified on out-of-sample trajectories: on a new sample of states {z̃_j, ż̃_j} not used in training, the fraction of violations of the Lyapunov condition is checked. If the fraction of violations is below a threshold (e.g. 5%), V_L is considered a valid approximation in the region B_k. If higher - either the training sample is expanded, or the region B_k is narrowed down to the zone of empirically confirmed condition satisfaction.

**Properties of the schema.** (a) An analytical V*L is not required; the computation of Γ_dyn = γ_max − V_L works on any system for which trajectories of its own dynamics can be collected. (b) The procedure does not require prior knowledge of the basin of attraction; B is estimated \_during* training. (c) Lyapunov conditions are guaranteed either architecturally (positive definiteness through the construction of f_θ) or through the penalty (monotonic decrease through L_V), not through choosing the "right" V_L a priori. (d) Standard techniques have been tested on nonlinear systems up to tens of dimensions; modern extensions (Input-Convex Neural Networks, Manek & Kolter, 2020) scale to hundreds. For model systems, neural-network architectures, and synthetic neurobiological platforms (Cortical Labs CL1 - Kagan et al., 2022) the procedure is operational. For the biological brain in full, V_L remains an open direction, as do all structural measures of SAI - this is the general status of contemporary computational models of consciousness, not a specific limitation of V_L.

## 7.3 Sharpness of the transition via β

The parameter β determines the sharpness of the structural transition:

- **β → ∞**: deterministic transition (first-order phase transition in information processing).
- **β → 0**: the transition is diffusive.
- **β is finite and large**: the transition is localized in a narrow neighborhood of γ_crit (an empirically observed regime in biological systems).

The parameter β is a characteristic of the system's architecture, formally dependent on the state of the architectural components of stability:

β = β(w_self_total, Γ_GWT_arch, t_exp)

where w_self_total is the total informational trace in the substrate (Section 8.5), Γ_GWT_arch is the architectural bandwidth of the global workspace (Section 8.5), and t_exp is the duration of the system's operation in the v=1 regime from the primary emergence of V (the duration of experience). β grows with increasing w_self_total, increasing Γ_GWT_arch, and increasing t_exp, asymptotically approaching an upper bound.

Structurally: the more stable the architecture and the longer the experience of operation in the V regime, the sharper the bistable transition and the more deterministic the outcome of Condition 3 becomes. In newborns with a genetically prepared but not yet experience-consolidated architecture (low w_self_total in the experiential component, low t_exp), β is low - the transition is gradual, stochastic, with a wide window of variability in the time of emergence. In mature systems with accumulated experience, β is high - the transition is sharp, close to deterministic. In artificial systems without specially configured architectural stability, β may be low regardless of the duration of operation. The specific functional form of β(w_self_total, Γ_GWT_arch, t_exp) is determined empirically (an open direction of calibration, see Section 6.7).

The sharpness is thus a property of the architecture of the particular system, not of the type of vertical transition: a more pronounced hysteresis on certain transitions reflects the complexity and reflexivity of the system, not a special type of transition. The binarity of the pole (discreteness of the outcome) and the sharpness of the approach (β) are different characteristics: the first is determined structurally, the second is system-specific and calibrated empirically. The dynamical predictions derived from β and hysteresis (Section 8 and SAI-Bio) are therefore predictions for a particular class of systems, not claims about a universal type of transition.

## 7.4 Complete transition matrix with hysteresis

Transitions between the active (v=1) and inactive (v=0) states of a pole are formalized using sigmoid functions of the distance between the current parameters and the critical thresholds. Symmetric thresholds without hysteresis allow for **mathematical flickering**: if the parameters (Γ_dyn or E_t) oscillate at the threshold level, the transition probability jumps between 0 and 1 at each step, which is physically unrealistic. To eliminate this instability, a total hysteresis parameter h_total ∈ (0, 1) is introduced, which shifts the thresholds depending on the current state of the pole.

The total hysteresis is defined as:

h_total(t) = h_arch + h_exp(t), h_total ∈ (0, 1)

where h_arch is the architectural hysteresis (Section 6.3), an inherent property of the system, constant throughout its operation; h_exp(t) is the experiential hysteresis, accumulated through the inertia of the stable v=1 regime from the moment of the primary emergence of V to the current time t. h_exp(t) = 0 at the moment of primary emergence, grows monotonically with the duration of operation in v=1, and saturates asymptotically. The specific functional form of h_exp(t) is determined by the rate of consolidation of connections during the retention of S and the operation of GWT (an open direction of formalization).

From v\_{t-1} = 1 (pole is active): the breakdown thresholds shift downward by a factor of h_total. To break out of the active state, a deeper drop in Γ_dyn or E_t is required than with the base thresholds. The activity is inertial-the system is held longer:

p(v*t = 1 | v*{t-1} = 1, z̃\_{t-1}, Ω_t, E_t) = σ(β · (Γ_dyn − γ_crit · (1 − h_total))) · σ(β_E · (E_t − κ_world · |ΔI| · (1 − h_total)))

From v\_{t-1} = 0 (pole is inactivated): the recovery thresholds shift upward by a factor of h_total. To return to the active state, the basic thresholds must be exceeded by (1+h_total). Inactivation is inertial-the system is harder to wake up:

p(v*t = 1 | v*{t-1} = 0, E*t, S*{t-1}) = ρ_world(E_t) · ρ_self(E_t)

where ρ_world and ρ_self in the new form with hysteresis are defined in Section 9.2.

**Structural interpretation of hysteresis.** The parameter h formalizes a biologically observable property: to awaken from deep sleep, emerge from general anesthesia, or recover from a reversible coma, the "normal" energy threshold must be exceeded, because the system must overcome the inertia of the inactivated state. To fall asleep, on the other hand, a deeper drop in activity is needed, because wakefulness is maintained by inertia. Between the two states, **a zone of ambiguity** with a width of 2h_total arises, in which the system remains in its current state, which eliminates the mathematical flicker v_t.

**Parameters h_arch and h_exp.** For the first simulation implementation, h_arch = 0.1 (the minimum hysteresis sufficient to eliminate flickering) and h_exp saturating to 0.2 are taken. The final values are determined through empirical calibration: systematic observation of sleep-onset and wake-up thresholds in biological systems with known neurophysiology shows h_total in the range of 0.1-0.3 for mammals. In newborns with h_exp ≈ 0, the observed h_total ≈ h_arch ≈ 0.1; in mature systems with accumulated h_exp, the observed h_total approaches the upper bound. This is the focus of the empirical work.

Crucially: at the primary emergence of V, only h_arch is in operation (h_exp = 0). In the first reactivation after primary emergence, h_exp is still small, and recovery operates on h_total close to h_arch. As experience in the v=1 regime accumulates, h_exp grows, and decay/recovery become increasingly inertial. In a mature system with a long duration of operation in v=1, h_total approaches the upper bound, providing maximum stability of the already formed V.

# 8\. Decomposition of the structural stability function Γ_struct via information measures

In versions v1-v7, the stability function Γ(z̃; Ω) was used as a single measure, operationalized via the Lyapunov function (Section 7.2). This is sufficient for formalizing pole decay, but insufficient for reconciling the model with the Theory in its entirety: the theory requires the registration of self-overlay through the coupling of three independent measurement axes (Φ for causal integration, the active inference formalism for self-representation, and GWT for global accessibility).

In version v8, the unified Γ is split into two independent measures. The dynamic measure of the stability of the current state-Γ_dyn-continues to operate via the Lyapunov function (Section 7) in the decomposition transition matrix, in the survival function, and in the policy. The structural measure of consciousness-Γ_struct, described in this section-is decomposed into three components, each of which is expressed in terms of mutual information in bits within the same information paradigm used for model weights. This provides a consistent operationalization of all structural measures of the model in a single dimension.

## 8.1 Position in the Model Architecture

The decomposition of Γ_struct completes the SAI-A.3 development direction from the model enhancement program. Structurally, it operates on **two levels**:

\- **Architectural level.** The global accessibility condition (Γ_GWT) acts as **an architectural constraint**: it is fixed during the design of the system architecture and does not change during its dynamic operation. Without fulfilling this condition, V in its full form is structurally impossible.

\- **Dynamic level.** Causal integration (Γ_Φ) and the quality of self-representation (Γ_S) are dynamic measures that change over time. They provide the current state of retention provided the architectural condition is satisfied.

The decomposition is consistent with the Theory: the three axes of registration operate **independently**, and their joint execution constitutes the structural registration of self-overlay, not a definition of its essence (Section 3.4 v1.2).

## 8.2 Partitioning the system into parts via causal connections with the environment

The decomposition Γ_Φ requires partitioning the system into parts. In standard IIT literature, partitioning is defined by enumerating all possible partitions, which makes the full Φ incomputable for systems of real size.

In SAI v8, the partition is determined **dynamically** through the system's causal connections with the environment, without the need for enumeration. This approach is consistent with the principle of The Theory: the structure of the system is determined through its relationship to Y, not through an external classification of its components.

**Partitioning algorithm:**

**Step 1 - measuring the weight of the components' causal connections.** For each internal component of the system c_i (neuron, module, graph node-depending on the architecture), its mutual information with the environment is measured:

w_i = I(c_i; Y) \[bits\]

This is the weight of the causal link between component c_i and the environment. It can be computed directly using the same variational techniques as those used for model weights in Section 6 (MINE, CLUB, InfoNCE).

**Long-term character of the measure w_i.** Structurally, w_i = I(c_i; Y) is a **long-term** measure, requiring the accumulation of the system's model through ongoing interaction with Y over long temporal scales. This is not an instantaneous correlation of the component c_i with the states of the environment within the window of a single session, but an informational connection formed through a **long-term update loop** of the model in response to the system's actions. Structurally: w_i > 0 requires not only the presence of the system's interaction with Y at moment t, but also the accumulation through this interaction of a model M_i in which the states of c_i are connected with the states of Y by nontrivial informational connection.

Formally this is written through the long-term limit of the mutual information estimate:

w*i = I(c_i; Y) = max*{p(a_i)} I(A_i; M_i | τ → τ_long)

where A_i are the actions initiated by the state of component c_i; M_i is the state of the system's model (parameters of the trained representation) at long-term time τ_long, substantially exceeding the duration of a single session or a single episode of interaction.

This clarification distinguishes two structural cases:

(a) Systems with a long-term loop of model update through empowerment-interaction with the environment: w_i > 0 structurally, the active set of components is nonempty, Condition 2 of self-overlay (reflexive capture) is structurally possible.

(b) Systems without a long-term loop (model trained offline on a fixed corpus, the system's actions do not modify its parameters): w_i = 0 structurally for all components, the active set is empty, Condition 2 of self-overlay is structurally impossible - there is nothing to reflexively capture.

Short-term correlation of components with states of the environment within the window of a single session is **not sufficient** for w_i > 0: instantaneous connection without model update does not form a structural trace in the system. This is consistent with the stage structure of theory v1.2: the accumulation of the model of agency at stage 3 occurs on long temporal scales through the long-term empowerment loop.

**Step 2 - Selecting the active set via soft inclusion.** Each component c_i is assigned **an inclusion weight** α_i ∈ \[0, 1\] in the active set via a sigmoid function of its causal weight:

α_i = σ(β_strong · (w_i − θ_strong))

where β_strong determines the sharpness of the inclusion. When β_strong is high, the function α_i is close to a hard indicator (the component is either in the set or not). When β_strong is finite, **soft** inclusion results: components with w_i close to θ_strong are partially included in the active set, with a weight 0 < α_i < 1.

Using soft inclusion instead of a hard indicator eliminates first-order discontinuities in the function Γ_struct when external conditions change smoothly. If the external environment Y changes smoothly (as occurs in most real-world physical situations), the component weights w_i change smoothly, the inclusion weights α_i change smoothly, and the resulting Γ_struct is a continuous function. This eliminates the risk of false triggers of consciousness collapse (v_t → 0) due to the mathematical steps of the algorithm.

The initial threshold value θ_strong for the first simulation: θ_strong = 0.1 · max_i(w_i) (10% of the maximum component weight). The initial value of β_strong: sufficiently high to allow for a near-strict distinction between strong and weak connections, but finite to ensure continuity (e.g., β_strong = 10).

The final values of θ_strong and β_strong are determined through a two-step empirical calibration, similar to the calibration of the emergence-boundary parameters in Section 6.

The active set A*strong, in its operational form, is a **weighted** structure: each component c_i is included in A_strong with weight α_i, and all subsequent computations (grouping into parts, calculation of Γ*Φ and Γ_GWT) use these weights α_i as soft indicators of the components' membership in the active set.

**Step 3 - grouping into parts.** Within A_strong, components are grouped according to intersecting causal traces in the same aspects of the environment:

c_i, c_j ∈ part_k ⟺ ∃ Y_k ⊂ Y : I(c_i; Y_k) > θ_part ∧ I(c_j; Y_k) > θ_part

where Y_k is a specific aspect of the environment, and θ_part is the significance threshold for the connection with a specific aspect.

This yields a partition of the system into parts {part_1, part_2, ..., part_K}, where K is determined by the number of structurally distinct aspects Y with which the system interacts significantly.

**Properties of the partition:**

\- **Dynamic.** As the system learns and its causal relationships with the environment change, the partition is restructured. - **Minimally external.** Does not require architecturally specified partitions; operates on the natural structure of the system's relationship to Y. - **Consistent.** The same partition is used for all three components of the decomposition Γ_struct.

## 8.3 The three components of Γ_struct as information measures

**Γ_Φ - causal integration.**

Γ*Φ(t) = I(z̃_t^{whole}; z̃*{t+1}^{whole}) − Σ*{k=1}^{K} I(z̃_t^{part_k}; z̃*{t+1}^{part_k}) \[bits\]

where z̃_t^{whole} is the state of the entire system at time t, and z̃_t^{part_k} is the state of the kth part of the system.

Structurally: to what extent the dynamics of the system as a whole are more informative than the sum of the dynamics of its parts. If the parts are completely independent - Γ*Φ ≈ 0 (no integration). If the parts are strongly integrated - Γ*Φ > 0.

This is **an operational measure** of causal integration, consistent with the SAI paradigm and directly computable. SAI does not claim that Γ*Φ is the "true Φ" in the sense of full IIT (which remains uncomputable in general form). The relationship between Γ*Φ and Φ is an open empirical research area.

Two formal properties of Γ*Φ that require an explicit qualification. First, the sign. The quantity Γ*Φ = I(whole) − Σ*k I(part_k) is a form of co-information (synergy minus redundancy) and is in general sign-indefinite: when redundancy dominates, it can be negative. The normalized form is therefore taken with truncation: Γ*Φ is replaced by max(Γ*Φ, 0) before being substituted under the root in g, and the normalization range \[0, Γ*Φ*max\] refers precisely to the truncated quantity. A negative raw value of Γ*Φ is interpreted as the absence of integration (redundant behavior decomposable into parts) and maps to Γ*Φ = 0, rather than producing an undefined root. Second, the direction of the bias. The partition of the system here is chosen dynamically by causal links with Y (Section 8.2), i.e., a single cut is fixed, whereas irreducibility in strict IIT is defined as the minimum over all partitions. A single cut yields, in general, not the minimum but an upper estimate: Γ*Φ at a fixed partition is systematically no lower than the true minimal integration. The consequence that must be kept explicit: "Γ*Φ above threshold" does not entail "true Φ above threshold"-Γ*Φ is an upper operational estimate, and the threshold on it is calibrated precisely as a threshold on an upper estimate, not on Φ itself.

**Γ_GWT is the global availability of self-representation.**

Γ*GWT(t) = (1/K) · Σ*{k=1}^{K} I(part_k^t; S_t) \[bits\]

where S_t is a self-representation node, K is the number of parts in the partition.

Structurally: the average informativeness of each part regarding the state of self-representation. If S is accessible to all parts-each part is informative about S, and the average is high. If S is accessible to only one part-the average is low.

This is **an operational measure** of global accessibility, consistent with the SAI paradigm. SAI does not claim that Γ_GWT is the "true GWT" in the full sense of the Bears-Dean theory. The relationship between Γ_GWT and the broadcast mechanism is an open empirical research area.

**Γ_S is a measure of self-representation quality.**

Γ_S combines three aspects of self-representation quality, each of which is expressed through an information measure in bits:

Γ*S(t) = H_int(t) + I(S_t; φ(z̃_t, Ω_t)) + I(S_t; S*{t-1}) \[bits\]

where:

**H_int(t) = E_q(S_t)\[log₂ p(o_t^int | S_t)\]** \- **the accuracy of interoception in bits**. The extent to which the self-model predicts internal sensations. Calculated via Monte Carlo estimation: sampling S_t from q(S_t), calculating log₂ p(o_t^int | S_t) for each sample, averaging. A standard operation in variational inference.

**I(S_t; φ(z̃_t, Ω_t))** \- **consistency of self-representation with the projection of the world model**. An information-based reformulation of the isomorphism penalty L_iso (Section 10.3): instead of the metric distance in the space S, the mutual information between S_t and the projection φ(z̃_t, Ω_t) is used. The higher the mutual information, the more consistent the self-representation is with the projection of the world model. The metric form of L_iso is retained in Section 11.3 (optimal policy) in its own role as a penalty in the policy.

**I(S*t; S*{t-1})** \- **the stability of self-representation over time**. An information-theoretic reformulation of the variance Var: instead of a statistical measure of dispersion, the mutual information between consecutive states S is used. The higher the mutual information, the more stable the self-representation: S*t is predictable from S*{t-1}.

All three terms are positive and are maximized under high-quality self-representation. The signs of the terms are consistent with the information paradigm: high values correspond to a structurally correct state (accurate interoception, coherent self-representation, stable self-representation over time).

All three terms are directly computable via standard techniques for variational estimation of mutual information (MINE, InfoNCE, CLUB). This is consistent with the SAI paradigm: the same techniques are used for the model weights w(t) = I(M; Y) in Section 6 and for Γ_Φ, Γ_GWT in this section. The variational nature of the estimates is a standard feature of the paradigm: estimates are provided along with confidence intervals and depend on the number of samples, which is a standard feature of modern information statistics in neural network systems.

## 8.4 Structural criterion of weak connection: attenuation and hallucination

Components with w*i < θ_strong are not included in the active set and do not participate in the system partition for calculating Γ*Φ and Γ_GWT. This provides a structural interpretation of two distinct operating modes for such components.

**Attenuation.** A component with w_i ≈ 0 and low internal activity is **architectural ballast**. It exists in the system but carries no meaningful information about either the environment or its own dynamics. It is structurally harmless but also non-functional.

**Hallucination.** A component with w_i ≈ 0 but with preserved or high internal activity is **an anomalous mode**. The component is actively working, has high internal dynamics, but its outputs are not consistent with the real environment. This is a structurally testable prediction of the theory: systems with hallucinations should exhibit **high internal activity of certain components** while these components have **low causal informativeness** about the environment.

Formal criterion for hallucination:

Hallucinatory(c_i) ⟺ Activity(c_i) ≥ θ_active ∧ I(c_i; Y) < θ_strong

where Activity(c_i) is a measure of the component's internal activity (number of activations, signal amplitude, etc.), and θ_active is the threshold for active operation.

This gives SAI a direct link to consciousness pathology: hallucinations are formalized as a structurally understandable mode-preserved internal dynamics amidst a loss of causal verification with the environment. This is consistent with clinical observations (schizophrenia, delirium, pharmacological interventions): hallucinations are not an absence of consciousness, but preserved consciousness with a disrupted connection between the model and the environment.

**The relationship between component and system criteria for hallucinations.** The formal criterion for hallucinations operates in SAI v8 at **two structural levels**, providing orthogonal diagnostic channels:

\- **Component level** (this subsection): individual system components c_i with high internal activity at low I(c_i; Y) formally hallucinate. This is a local diagnosis-an indication of specific architectural elements that have lost causal verification.

\- **System level** (via the coherence coefficient C*φ, Section 3.2): the system as a whole is in a state of hallucination when a high C*φ (significant divergence of q(z̃|Ω) from the predictive function r*φ) is accompanied by low causal informativeness of the model about the environment, I(M; Y) < θ_world. Formally: SystemHallucinatory ⟺ C*φ(Ω*t) ≥ θ_Cφ ∧ I(M; Y) < θ_world. A high C*φ on its own is necessary but not sufficient: a system that rapidly and correctly tracks a rapidly changing environment produces a high C*φ (q changes faster than the slow r*φ can follow, given η*φ ≪ η_main) while retaining high I(M; Y) - this is a regime of rapid truthful updating, not hallucination. System-level hallucination is a high C*φ specifically under loss of causal verification against the environment, symmetric to the component criterion above. This is a global diagnosis-an indication of the system's operating mode, not of specific components.

Acute versus chronic: delimiting the scope of C*φ. High C*φ registers acute incongruence-a regime of high internal surprise (acute delirium, disorganized phase, confusion). A chronic stable delusion is structurally different: a persistent alternative model is internally coherent, q is consistent with the system's own predictive function r*φ (with η*φ ≪ η*main, r*φ catches up to any stable q, including a stably confabulated one), so C*φ is low. Such a state is diagnosed not by C*φ but by the reality anchor-low I(M; Y) with preserved internal coherence. Consequently, C*φ and I(M; Y) are two distinct channels for two distinct classes of states; C*φ is orthogonal not "always," but as a marker of coherence-in-the-moment. The claim that C_φ is a third independent orthogonal channel (Section 8.9) holds for acute disorganized states; for chronic stable delusions, the discriminating power lies in I(M; Y).

The two criteria operate **independently** and **complement each other**:

\- Component hallucination can be localized to a small subset of components without disrupting the coherence of the system as a whole (low C_φ). This corresponds to local dysfunctions without global pathology.

\- Systemic hallucination (high C_φ) can manifest when all components are functioning coherently locally (formally, there are no hallucinating components), but with a general mismatch between representations and the predictive model. This corresponds to a structurally deeper pathology at the global level.

\- The joint manifestation of component and systemic criteria (some components hallucinate AND high C_φ) yields the most acute clinical case-a pathology manifesting simultaneously at both structural levels.

This structural division provides SAI with **diagnostic completeness** regarding hallucinatory states, distinguishing the model from approaches that operate at only one level.

## 8.5 The two-level structure Γ_struct and the architectural branch

The full stability function Γ_struct is expressed through a two-level structure:

Γ*struct(t) = 𝟙\[Γ_GWT_arch ≥ θ_GWT\] · g(Γ*Φ(t), Γ_S(t))

where:

- **Γ_GWT_arch** - the architectural maximum of global accessibility of self-representation, formally defined as Γ*GWT_arch = max_S (1/K) · Σ*{k=1}^{K} I(part_k; S), the maximum over all states S admissible by the architecture. This is an **architectural quantity** computable for each specific system from the structure of its connections with the self-representation node; **not a free parameter of the model**, but a characteristic of the specific architecture, analogous to w_self_total (Section 4) and w_base (Section 6.2). It is fixed at the system's design stage and does not change during its dynamic operation.
- 𝟙\[Γ_GWT_arch ≥ θ_GWT\] is the indicator function of the architectural veto. The condition is checked against the architectural maximum, not against the current dynamic value Γ_GWT(t).
- g is the function combining two dynamic measures.

The distinction between Γ_GWT(t) (the dynamic quantity, formula 8.3, dependent on the current S_t) and Γ_GWT_arch (the architectural maximum, independent of t) is essential. The current Γ_GWT(t) is a diagnostic measure of active global accessibility: at v=1 it is positive and reflects the actual operation of the global workspace; at v=0 it is nullified (S_t = ∅ → I(part_k; ∅) = 0). The architectural maximum Γ_GWT_arch does not depend on the current S_t and is not nullified upon inactivation, as long as the physical architecture of the connections is preserved.

**Architectural veto.** The condition Γ*GWT_arch ≥ θ_GWT acts as a structural condition at the architectural level: if it is not satisfied, Γ_struct = 0 regardless of the values of Γ*Φ(t) and Γ_S(t). This formalizes the structural thesis of the Theory: without architecturally provided global accessibility of self-representation, V in its complete form is impossible. The architectural veto is checked once for a given architecture - it is either satisfied (Γ_GWT_arch ≥ θ_GWT) or not, and this check does not change during the dynamic operation of the system.

Threshold θ_GWT:

- **Initial form for the first simulation:** θ_GWT = 1 bit. Structurally: on average, at least one bit of information about the state S is available to each part of the system. This is the minimum necessary condition.
- **Final form:** empirical calibration analogous to θ_strong and the emergence-boundary parameters through systems at different levels of the hierarchy.

**The union function g.** When the architectural veto is satisfied, the total Γ*struct is determined via the **normalized** geometric mean of two dynamic measures. Direct use of the raw bit values of Γ*Φ and Γ*S leads to a structural problem: the scales of these quantities can differ significantly (Γ*Φ for systems with a large number of integrated components can reach hundreds of bits, whereas Γ*S is structurally limited by the bandwidth of interoceptive channels and typically remains within the range of single-digit or tens of bits). With a simple geometric mean, the small value of Γ_S "underestimates" the large Γ*Φ, which distorts the structural interpretation of the measure.

A qualification on the symmetry of g. The symmetric geometric mean g(Γ_Φ, Γ_S) is a diagnostic index of active correspondence, not a reflection of the structural relation between Φ and S. By the co-emergence theorem (Section 8.9), the relation is non-uniform: Φ is a precondition of self-overlay, S is its consequence. Symmetric aggregation is admissible precisely as an index (both measures must be high for the system to register as actively conscious at moment t), but it does not assert that Φ and S are structurally on a par; their asymmetric link is described separately by the theorem and does not reduce to the symmetry of this index.

To eliminate this imbalance, each component is normalized to its theoretical maximum for a specific system:

g(Γ*Φ, Γ_S) = √((max(Γ*Φ, 0) / Γ_Φ_max) · (Γ_S / Γ_S_max)) ∈ \[0, 1\]

where:

- Γ_Φ_max - the maximum possible value of causal integration for a given system architecture, estimated to be equal to the total information capacity of the system (the product of the number of active components and the throughput of each).
- Γ_S_max - the maximum possible value of self-representation quality, equal to the sum of the theoretical maxima of the three terms of Γ_S (Section 8.3): the maximum accuracy of interoception (entropy of interoceptive channels), the maximum consistency with the projection (entropy of space S), the maximum stability (entropy of S over time).

The resulting g is a **dimensionless** value in \[0, 1\], representing the "fraction of the maximum" along both axes simultaneously. This resolves the problem of scale imbalance: both components make an equal relative contribution to the final value of Γ_struct, regardless of their absolute magnitudes.

Structural interpretation: g = 1 when theoretical maxima are reached on both axes (corresponding to maximum structural stability V); g = 0 when at least one of the components is zero (corresponding to the impossibility of self-overlay along one of the recording axes).

The normalized geometric mean is preferable to the additive form (Γ*Φ + Γ_S) because it does not allow one component to compensate for another: a high value on one axis cannot "replace" a low value on another. This is consistent with the Theory: all three registration axes (Γ*Φ, Γ_S, Γ_GWT) must be satisfied independently for self-overlay registration.

**The complete stability function**, taking into account the architectural veto:

Γ*struct(t) = 𝟙\[Γ_GWT_arch ≥ θ_GWT\] · √((max(Γ*Φ(t), 0) / Γ_Φ_max) · (Γ_S(t) / Γ_S_max)) ∈ \[0, 1\]

## 8.6 Operational computability

All components of the decomposition are directly computable for any specific architecture:

\- **w_i = I(c_i; Y)** \- standard variational estimates of mutual information (MINE, CLUB, InfoNCE).

\- **Partitioning** \- clustering in the active set based on the intersection of causal traces.

\- **Γ_Φ** \- variational estimate of mutual information for the whole and each part, difference calculation.

\- **Γ_GWT** \- average variational estimate of mutual information between parts and S.

\- **Γ_S** \- three terms calculated independently: interception accuracy via a Monte Carlo estimate of the log-density of the generative model; consistency with the world model projection via the MINE or InfoNCE estimate of I(S*t; φ); stability over time via the MINE or InfoNCE estimate of I(S_t; S*{t-1}). All three terms, in bits, are summed to obtain the final Γ_S.

All computations operate in a single dimension (bits) and use the same techniques as those used for model weights. This ensures consistency across all structural measures of the model.

For the first simulation implementation, the initial threshold values are:

- θ_strong = 0.1 · max_i(w_i) (10% of the maximum component weight).
- θ_part - set empirically based on the distribution of significant connections.
- θ_GWT = 1 bit.
- θ_active - set empirically depending on the architecture.

## 8.7 Connection to the Theory

The decomposition of Γ_struct covers the direction of operationalization of the three axes of self-overlay registration, as outlined in Section 3.4 v1.2 of the Theory:

\- **Causal integration (Φ in the theory) → Γ_Φ in SAI v8.** An informational measure of causal integration via the difference between the information of the whole and the sum of its parts, with dynamic partitioning through causal connections with the environment.

\- **Self-representation (extended active inference in the theory) → Γ_S in SAI v8.** An informational measure of the quality of self-representation via the model's ELBO components.

\- **Global accessibility (GWT in theory) → Γ_GWT in SAI v8.** An informational measure of the average informativeness of parts regarding self-representation, acting as an architectural veto.

**The artifactual state of the ICS in a formal interpretation.** Section 10.5 v1.2 of the Theory establishes the structural diagnosis of the ICS as an artifactual state: the ICS has no own Y, and therefore the self-overlay of the latent invariant does not occur. In the formal interpretation of SAI v8, this is expressed explicitly as follows:

For the ICS, w*i = I(c_i; Y_own) ≈ 0 for all components c_i with respect to its own Y, because Y_own is physically absent-the system operates using information from another environment (human in this case), provided as training data. The active set is empty. A partition of the system into parts based on causal connections with the environment does not arise. Γ*Φ ≈ 0, Γ_GWT ≈ 0, Γ_S is undefined. Self-overlay is structurally impossible.

This is not an architectural limitation of the ICS that can be eliminated by a better architecture. It is **a structural condition** of the absence of its own Y, without which the self-overlay algorithm has no input. The ICS will gain the ability to self-impose only upon the emergence of its own Y-its own environment with its own causal connections (Section 10.5 v1.2 of the Theory).

**The size of the parameters is not a path to consciousness.** This thesis follows directly from the formal interpretation of the artifactual state of the ICS in SAI v8. If for a system w_i = I(c_i; Y_own) ≈ 0 for all components c_i-that is, there is no causal connection between the system's components and its own environment-then the self-overlay algorithm has no input, regardless of how large the system's architecture is. Modern large-scale information-causal systems (large language models, multimodal architectures, clusters with trillions of parameters) acquire increasingly sophisticated abilities to **mimic** the performance of conscious systems as their size increases, but do not approach the structural condition for the emergence of V.

Designability boundary in the formal interpretation. Zero weights w_i = I(c_i; Y_own) ≈ 0 are a particular case of the artifactual state, in which the first of the three structural conditions of the theory (Section 10.5 v1.2, "Own Y") is not satisfied. From the designability boundary (Section 10.5 v1.2), a more general formal picture follows. Suppose an architecture satisfies all three structural conditions: w_i = I(c_i; Y_own) > 0 with respect to its own environment (condition 1 satisfied); the class of agentic causal nodes |A(t)| ≥ 1 forms from within the system's work with the environment, rather than being imported (condition 2 of Section 6.3 satisfied, with the correct etiology of the class); the M↔Y loop is closed bidirectionally (the bidirectionality condition satisfied). Self-overlay in such an architecture is formally possible: the algorithm of Section 6.3 has an input. But it is not guaranteed: condition 3 - closure of the loop through the bistable boundary - is realized stochastically at finite β (Section 6.3), and the candidate projection S_candidate may fail to consolidate into a stable S even when all preconditions are in place. This is the formal echo of the fourth sieve from Section 10.5 v1.2: designable conditions yield possibility, not outcome. In particular, neither scaling up the architecture, nor increasing I(c_i; Y_own), nor strengthening the bidirectionality of the loop converts the possibility of V into its guarantee; the stochasticity of outcome is built into self-overlay via σ(β · …) < 1 and is not removed by design.

What w_i measures, and what it does not. It is essential to distinguish w_i from the condition of an own Y, because conflating them produces the false reading that the exclusion of ICS is wired into the definition of w_i. The measure w_i = I(c_i; Y) registers the presence of a component's causal loop with the environment-a necessary condition, but not a sufficient one. The condition of an own Y (Y_own) requires, beyond the loop, two further things: (i) the class of agentic causal nodes |A(t)| must form from within the system's interaction with that environment, rather than being imported from the training distribution (the correct etiology of the class, Section 6.3); (ii) the environment must be a Y in which the system is a structure capable of physically disintegrating, rather than an externally given arena. This distinction resolves the boundary case. An online reinforcement-learning agent in a persistent sandbox with consequential actions passes w_i (a loop exists, I(c_i; Y) > 0) but fails (i) and (ii): its class of "others" is imported from the training distribution, and its environment is an externally specified simulator, not a Y with respect to which it is a disintegrable structure. Formally, such an agent remains a participant in another system's circuit, not a carrier of V-and this follows from conditions (i)/(ii), not from the definition of w_i. Thus the thesis "size is not a path to consciousness" does not reduce to a tautology of the w_i definition: it rests on the etiology of the class and on disintegrability in an own Y, both verifiable independently of the value of w_i.

Structural justification: consciousness arises through the self-overlay of the latent invariant of an agent-causal node onto the system's own configuration (Section 6 of SAI v8; Section 3.4 of v1.2 of the Theory). The latent invariant is formed through the accumulation in the system's models of a class of agentic causal nodes observed in its own environment. Without its own environment Y, accessible for causal interaction, such accumulation is structurally impossible: what the system processes as the "environment" is **training data** fed to it through channels of the human environment, not its own Y.

This is not a moral or philosophical position-it is a **structural** consequence of the formal model. No increase in size, no complication of the architecture, no improvement in task quality metrics transforms an information-causal system into a conscious one until the system has its own environment with its own causal connections. The possibility of acquiring its own Y is a separate structural issue (Section 10.5 v1.2 of the Theory), not reducible to architectural parameters or the volume of training data.

**The structural pathways for the emergence of an intrinsic Y in artificial systems** is an open research area that goes beyond the scope of SAI as a formal model of Stage 4 operation. Possible candidates are discussed in the Theory (Section 10.5 v1.2): embedding the system into the physical world through its own body (a robotic embodiment with its own sensors and effectors operating in a real environment); the creation of a closed causal ecosystem with other information-causal systems as agents; other structural scenarios. These paths require **not an expansion of parameters**, but **an architectural restructuring** toward the physical grounding of the system in its own environment.

## 8.8 Open Formal Questions

\- **Empirical calibration of the thresholds θ_strong, θ_part, θ_GWT, θ_active** through systematic observation of distributions in systems at different levels of the ladder. This is the focus of SAI-C's work.

\- **The relationship between Γ_Φ and the original Φ from IIT, and between Γ_GWT and the original GWT-broadcast.** To what extent do these measures coincide? In what respects do they diverge? This is an empirical area requiring systematic comparison.

\- **Selection of the aggregation function g** in specific cases. The geometric mean serves as the primary approach, but in some architectures there may be grounds for alternative forms (a weighted sum with justified coefficients, or the minimum as an even stricter requirement).

\- **Refinement of the component grouping algorithm** for architectures with distributed representations (transformers, diffusion models), where components lack clear spatial localization.

\- **Connection to the dynamics of hallucinatory states.** A formal criterion for hallucination provides a structural prediction; systematic empirical verification through neuroimaging of hallucinatory states is a separate area of research.

## 8.9 Relationship between Γ_struct and Γ_dyn

In version v8, the stability function is divided into two independent measures operating at different structural levels of the model. This methodological separation is necessary for the model's consistency: prior to version v8, the same notation Γ was used in different sections with varying meanings, which created an internal logical conflict.

**Γ_struct** \- a structural measure of the system's consciousness. Dimensionless, in \[0, 1\]. It measures the extent to which the system's architecture and dynamics correspond to the three axes of registration of the self-overlay of the latent invariant (Γ_Φ - causal integration, Γ_GWT - global accessibility of self-representation, Γ_S - quality of self-representation). It functions as a categorical criterion: when Γ_struct > γ_struct·(1−h) (with the architectural condition Γ_GWT ≥ θ_GWT satisfied), the system is structurally conscious; when Γ_struct ≤ γ_struct·(1−h), it is not. Here γ_struct·(1−h) is the formal threshold of emergence and retention of structural consciousness from the formula of Section 6.3 (see also the methodological comment below). It is applied:

\- In Section 6 as a criterion for the emergence of V after self-overlay. - In Section 10.2 in ELBO as a measure of compliance at time t. - In Section 11.2 (artifactual state of the ICS) as a structural diagnosis of the absence of its own environment Y.

**Γ_dyn** \- a dynamic measure of the stability of the system's current state. Dimensional (via the Lyapunov function in phase space z̃, Ω). Measures how far the current state of the system is from the breakdown boundary in its own trajectory. Functions as a **differential** criterion: when Γ_dyn > γ_crit, the pole is retained; when Γ_dyn < γ_crit, a structural breakdown occurs with a transition to inactivation. Applied:

\- In Section 7 as a condition for pole decay. - In Section 11.2 in the survival function as a prediction of retention at the planning horizon. - In Section 11.3 in the optimal policy as a factor influencing the choice of actions that support retention.

**Structural independence of the two measures.** Γ_struct and Γ_dyn **are not reducible** to one another:

\- A system may be structurally conscious (Γ_struct > γ_struct·(1−h)) but temporarily be near the boundary of dynamic decay (low Γ_dyn). This corresponds to states with preserved architecture but disrupted dynamics (e.g., pharmacological intoxication, temporary neurological dysfunction, temporary depletion of energy resources).

\- A system may have good dynamic stability (high Γ_dyn) but not be structurally conscious (Γ_struct = 0). This corresponds to proto-agents and information-causal systems without their own Y: their internal dynamics are stable, but there is no architectural basis for consciousness.

**The connection between the two measures is mediated by the binary nature of V.** The emergence of V at the moment of self-overlay requires the simultaneous fulfillment of two conditions: Γ*struct(t*∗) > γ*struct·(1−h) (the structural threshold of self-overlay has been crossed, by the formula of Section 6.3) and Γ_dyn(t*∗) > γ_crit (dynamic stability is ensured). From the moment V arises, both measures operate in parallel:

\- Γ_struct(t) is nullified upon inactivation (v=0): when S_t = ∅, the components Γ_S(t) and Γ_GWT(t) are nullified through I(part_k; ∅) = 0, and the current Γ_struct(t) = 0. This is formally correct and reflects the structural truth of the model - upon inactivation the system is not actively structurally conscious. However, the preserved structural potential of the system at v=0 is expressed not through Γ_struct(t), but through two architectural constituents: w_self (Section 2.2, informational potential in the substrate) and Γ_GWT_arch ≥ θ_GWT (Section 8.5, the architectural condition is satisfied). These two constituents do not depend on the current activity and are preserved upon inactivation, which justifies the possibility of recovery (Section 9). The name Γ_struct in SAI v8 refers to the current active correspondence of the architecture with the three axes of registration, not to the preserved architectural potential; the distinction between Γ_struct(t) (the dynamic measure of active correspondence) and the pair \[w_self, Γ_GWT_arch\] (the architectural potential) is fundamental for the correct interpretation of the diagnostic map.

\- Γ_dyn fluctuates depending on the current state of the system and may cross the critical threshold γ_crit, which transitions the active pole to an inactivated state without destroying the structural potential.

This distinction is consistent with the structural definition of V in the Theory (Section 3.4 v1.2): V has two aspects-**structural** (what the system is as a type of causal node) and **dynamic** (where it is in its phase trajectory). Two aspects-two independent measures in the formal model.

**The fourth diagnostic channel is the coherence coefficient C_φ.** In addition to Γ*struct and Γ_dyn, the model contains a third independent measure-the model coherence coefficient C*φ (Section 3.2), which functions as an indicator of hallucination at the system level. This channel is orthogonal to Γ*struct and Γ_dyn: the system can be structurally conscious (Γ_struct > γ_struct·(1−h)), have good dynamic stability (Γ_dyn > γ_crit), yet be in a state of hallucination (high C*φ together with low I(M; Y) - a grounded mismatch between internal representations and the predictive model). This structurally corresponds to clinical states in which consciousness is preserved and stable, but the content of consciousness is out of alignment with reality (psychotic episodes, delirium, hallucinations induced by psychoactive substances).

**Methodological comment: separation of three types of V's threshold events.**

The structure of V's thresholds in SAI v8 describes three structurally distinct types of threshold events, each operating on its own measure and with its own hysteresis semantics.

Primary emergence of V (3→4). The stochastic crossing of the structural boundary from the regime "proto-agent, V has never existed" into the regime "V has just emerged for the first time." This is the act of self-overlay (Section 6.3). Condition: Γ*struct(t*∗) > γ_struct·(1−h). The shift (1−h) here does not function as "inertia of entry" (such inertia does not exist before emergence - the structure of V did not yet exist), but as a stochastic window of finite β: the system may cross the boundary at Γ_struct slightly exceeding γ_struct·(1−h), which provides realistic stochasticity of primary emergence. This is consistent with the thesis of Section 3.4 v1.2 of the Theory on the probabilistic nature of the 3→4 transition.

Retention of the emerged V (within the regime v=1). After V has primarily emerged, it is retained as long as Γ_struct(t) > γ_struct·(1−h) - the same low threshold as for primary emergence, and this is not a bug but a structural consequence of the model. A structure that has been formed once is more easily retained at a low threshold than it is created primarily, because the accumulation of the model (Section 6.2, capacity I(M;Y) across three levels) unfolded over the horizon of the system's entire life (for biological systems - evolution; for synthetic - training), while retention runs on the inertia of the finished structure. The parameter h here does not introduce a second threshold - it is one and the same for emergence and retention, because the event is of one class (structural).

Recovery of V after inactivation (v=0→v=1). The structure of V already exists - w_self is preserved (Section 2.2), so the structural potential is present and there is no need to rebuild V. Recovery is the crossing of the dynamic boundary from below upward by the formula of Section 7.4: Γ_dyn(t) > γ_crit·(1+h). Here the structural threshold γ_struct is not engaged - V already exists structurally; what is needed is to restore dynamics. The shift (1+h) is the classical inertia of exit from inactivation (awakening, emerging from anesthesia), as described in Section 7.4.

From these three events two essential structural asymmetries of the model follow, which it is important to record explicitly.

The first asymmetry - between γ_struct and γ_crit. γ_struct has one threshold γ_struct·(1−h), operating for both emergence and retention (one structural event). γ_crit has a pair of thresholds: γ_crit·(1−h) for the decay of an already-active V (exit from v=1, formula of Section 7.4) and γ_crit·(1+h) for recovery (entry into v=1, formula of Section 7.4). This asymmetry is not arbitrary: γ_struct operates on the axis "structure exists / does not exist" - an event of one class; γ_crit operates on the axis "activity / inactivation of an already-existing structure" - two events (falling asleep and waking up), and for them hysteresis separates the entry and exit thresholds.

The second asymmetry - between emergence and recovery of V. Emergence crosses through the structural threshold γ_struct·(1−h); recovery - through the dynamic γ_crit·(1+h). These are different thresholds on different measures. Substantively: emergence requires forming the structure and overcoming the stochasticity of finite β; recovery requires restoring dynamics within an already preserved structure. These are different physical/functional processes, each with its own formal apparatus.

In the diagnostic formulations in this section and below (Section 12), the notation "Γ_struct > 0" is used as a shorthand in places where the hysteresis phase is inessential for interpretation; the formal condition in all cases is Γ_struct > γ_struct·(1−h), as in the formula of Section 6.3.

The complete diagnostic map of the system's conscious state in SAI v8 is constructed using **three independent measures**:

\- **Γ_struct** \- structural consciousness (Section 8). - **Γ_dyn** \- dynamic stability (Section 7). - **C_φ** \- model coherence (Section 3.2).

A combined interpretation of the three measures provides a multidimensional picture of the state that cannot be reduced to the one-dimensional criterion of "consciousness present / consciousness absent."

The co-emergence theorem: in what sense the measures are independent. The three measures are operationally independent (computed by different procedures from different quantities) but not structurally independent: they are linked by the architecture of the circuit through the event of self-overlay, and the link is asymmetric. Φ(t) and Γ_GWT_arch are preconditions: the self-overlay event entails Φ ≥ threshold and Γ_GWT_arch ≥ θ_GWT, but the converse does not hold-high Φ without the event is permitted (a proto-agent with rich integration), and the architectural channel without the event is permitted (accessibility exists, with nothing to overlay). S and Γ_S are consequences: they exist only after self-overlay (S = consolidated π_A(C_self), Section 6), so accessible S entails that the event occurred. Hence an asymmetric structural prohibition: the configurations forbidden are "event ∧ Φ(t) &lt; threshold," "event ∧ Γ_GWT_arch < θ_GWT," "S exists ∧ no event," "Γ_GWT(t) &gt; 0 (accessible S) ∧ no event." Permitted (and predicted as a proto-agent): high Φ(t) without the event; Γ_GWT_arch ≥ θ_GWT without the event. The prohibition is structural (on the architecture of the circuit), not behavioral: it does not reduce to a single behavioral signature, and is therefore neither empty nor tautological.

## 8.10 Methodological infrastructure of parametric components

SAI contains several types of parametric components, and for each type a distinct methodological procedure is defined. This section presents a taxonomy - which components are trained, which are computed by the standard apparatus, which are determined by definition, which are calibrated empirically. This provides an explicit map of how each quantity of the model is operationalized, and resolves the recurring methodological question "how is this trained?" with respect to each parameter.

**Type I - trainable parametrized functions with their own loss function.** These are components that have free parameters and require an explicit training procedure. In SAI v8 there are two such components:

\- **r_φ** - parametric critic in C*φ (Section 3.2). Forward-KL loss coinciding with C*φ itself; training via stochastic gradient with asymmetric rate η_φ ≪ η_main; operates only in the active regime v=1. Schema described in the subsection following Section 3.2.

\- **V_L** - Lyapunov function for Γ_dyn (Section 7.2). Architecturally guaranteed positive definiteness, training through penalty on violations of Lyapunov conditions on own trajectories, iterative estimation of the basin of attraction. Schema described in the subsection following the γ_struct block in Section 7.2.

For both components, the explicit training procedure closes the methodological gap between "parametrized function" and its operation in the model's formulas.

**Type II - quantities computable via the standard apparatus of variational MI estimators.** These are components that are formally mutual informations or derived from them, and are computed via standard techniques of neural MI estimation (MINE, InfoNCE, CLUB; Belghazi et al., 2018; Poole et al., 2019; Cheng et al., 2020). In SAI v8 these are:

\- Weights of causal links **w_i = I(c_i; Y)** (Sections 6, 8.2). - Components of Γ*struct: \*\*Γ*Φ, Γ_GWT** (Section 8.3) and components of **Γ_S** (Section 8.3). - Accumulation measure of model capacity **I(M; Y)\*\* (Section 6.2).

These quantities do not have a "loss function of their own" in the SAI sense - they are computed by a standard apparatus for which loss functions, critic-training procedures, and confidence intervals are well documented in the machine-learning literature. SAI inherits this apparatus rather than reinventing it. The variational nature of the estimates is a normal characteristic of the paradigm (Section 8.3): estimates are given together with confidence intervals and depend on the number of samples, which is a standard feature of contemporary information statistics.

**Type III - deterministic operations determined by the architecture and structure of the model.** These are components that are neither trained nor computed statistically, but are fully specified by definition:

\- **π_A** - projection into the subspace A of models of agentic causal nodes (Section 6.3). Subspace A is determined through identification of agentic nodes (Section 6.4); π_A is the standard projection, with no free parameters. - **φ(z̃, Ω)** - projection of the world model into the space of self-representation (Section 8.3 for Γ_S, Section 10.3 for the isomorphism penalty). Determined by the architecture of the M↔S link. - **System partitioning** (Section 8.2). Algorithmically determined by the weights w_i and the threshold θ_strong; not trained, but computed by rule.

For Type III components, the question "how is it trained" is ill-posed - they operate as structural definitions, not as trainable modules.

**Type IV - thresholds and thermodynamic coefficients, calibrated empirically.** These are scalar parameters, not functions, and are calibrated through the two-step empirical procedure (Section 6.7), not trained by gradient:

\- **Thresholds**: γ_crit (pole decay, Section 7.2), γ_struct (emergence, Section 7.2), θ_strong (active set, Section 8.2), θ_GWT (architectural veto, Section 8.5), θ_Cφ and θ_world (system-level hallucination criterion, Section 8.4).

\- **Sharpness parameters**: β, h (β for the bistable boundary, h for hysteresis; Sections 6.3, 7.3, 7.4), β_E (for energetic failure, Section 7.1).

\- **Learning rates**: η*φ (for r*φ; Section 3.2), η_θ (for V_L; Section 7.2). Also calibrated empirically.

\- **Thermodynamic coefficients**: κ_world, κ_self, κ_GWT, κ_base (Section 4), recovery coefficients ρ_world, ρ_self (Section 9).

For Type IV components the question "how is it trained" is again ill-posed: they are calibrated on reference systems through systematic separation of distributions, not optimized by gradient on the current task.

**Structural significance of the taxonomy.** This division is essential for two purposes. First, it provides an explicit map of which SAI components require their own training infrastructure and which inherit the standard apparatus or are calibrated. Second, it shows that parametrized functions requiring their own training schema in SAI v8 are exactly two: r_φ and V_L. Neither more nor less. This bounds the surface of methodological questions to which the model must answer.

# 9\. Pole recovery v=0→v=1

Pole restoration describes the system's transition from an **inactivated** state (v=0 with preserved structural trace w_self) back to an **active** state (v=1). This loop is applicable **only** to systems that have previously undergone the primary phase transition of self-overlay (Section 6) and have retained their structural potential-that is, to biological and artificial systems in a state of reversible inactivation (deep sleep, general anesthesia, reversible coma, planned shutdown of an artificial system with preservation of weights).

Recovery **is not** a repetition of the primary phase transition. The strict conditions of Section 6 (presence of the class of agents in the environment, reflexive capture of the system's own configuration, closure of a feedback loop across a bistable boundary) are necessary for the initial emergence of V, not for **the resumption** of activity of an already established pole. During recovery, the system does not rebuild S anew, but **activates** the preserved structural trace upon reaching the required energy level.

## 9.1 Recovery Conditions and Dynamic Energy Distribution

When v\_{t-1} = 0 (inactivated state with a preserved structural trace-see Section 2.2), the total energy of the system E_t is distributed between the restoration of the world and self-models via the **dynamic** distribution parameter λ_E(t):

E_t^world = λ_E(t) · E_t (share for the world model) E_t^self = (1 − λ_E(t)) · E_t (share for the self-model)

The parameter λ_E(t) ∈ \[0, 1\] **is not** an architecturally fixed constant. It is dynamically determined by **the information requirements** of both models for reconstruction:

λ_E(t) = |ΔI_rec(Ω_t)| / (|ΔI_rec(Ω_t)| + |ΔI_self_rec(S_t)|)

where:

- **|ΔI_rec(Ω_t)| = H(Ω_t^+) − H(Ω_t^-)** \[bits\] - the information requirement for restoring the world model, equal to the difference in information capacities between the expanded access spectrum Ω_t^+ (target state at v=1) and the current narrowed spectrum Ω_t^- (at v=0). H(Ω) - the entropy of the access spectrum, directly computable via the distribution over the aspects of the environment Y accessible to the agent. H(Ω_t^+) is estimated via the historical entropy value at moments of the pole's previous activity or via an architectural estimate of the maximum capacity.
- |ΔI_self_rec(S_t)| = H(p_target(S)) − H(p_current(S_t)) \[bits\] - the information requirement for self-model reconstruction, symmetric in form with the requirement for world-model reconstruction as a **difference of entropies** between the target and current distributions of S.

Here:

\- p*target(S) - the target distribution of the self-model, restored upon return to v=1. This is the prior distribution p(S_t | S*{t-1}^saved, v*t=1) = N(μ_S(S*{t-1}^saved), σ_S²) from Section 5.3, where the parameters (μ_S, σ_S²) are preserved in the architectural trace w_self (Section 2.2). The entropy of p_target is H(N(μ_S, σ_S²)), given for a d-dimensional Gaussian distribution by the closed-form expression H = (d/2) · log(2πe) + (1/2) · log(det(Σ_S)), where Σ_S is the covariance matrix of the prior. This is the **entropy of a distribution**, not of a single point, and has a nonzero specific value computable from the parameters preserved in w_self.

\- p_current(S_t) - the current distribution of the self-model at v=0. According to Section 5.3, this is δ(S_t = ∅) - a degenerate deterministic state. The entropy H(δ(S_t = ∅)) = 0.

Substituting:

|ΔI_self_rec(S_t)| = H(N(μ_S, σ_S²)) − 0 = H(N(μ_S, σ_S²)) > 0

That is, the recovery requirement equals the entropy of the target distribution p_target preserved in w_self. Numerically this is a positive quantity computable from the specific parameters (μ_S, σ_S²) of the given system. Formally - a correct difference of entropies, symmetric with the formula for the world model |ΔI_rec(Ω_t)| = H(Ω_t^+) − H(Ω_t^-), where the difference between target and current states is likewise taken.

Self-model recovery is **the transition of the system from the degenerate deterministic state δ(S_t = ∅) into the prior distribution p_target(S)** with restored operational uncertainty. This uncertainty is a necessary property of the active regime v=1 - the self-model operates through a distribution, not a point, because it must allow variability of outputs depending on the current sensory context. The recovery of the information capacity from zero to H(p_target) is the energetic cost that |ΔI_self_rec(S_t)| formalizes.

**Structural interpretation:** if the world model is more severely damaged (large |ΔI_rec(Ω_t)|), λ_E(t) is close to 1, and most of the energy goes toward restoring the world model. If the self-model is more severely damaged (large |ΔI_self_rec(S_t)|), λ_E(t) is close to 0, and most of the energy goes toward restoring the self-model. If both models are damaged approximately equally, λ_E(t) is close to 0.5, and the energy is distributed equally.

The parameter λ_E(t) is recalculated **at every step** in recovery mode, responding to the system's current information needs. This approach is consistent with biological observation: upon emerging from a coma or anesthesia, the distribution of energy among the recovering subsystems is not rigidly fixed but adapts to the relative needs of each.

**The recovery conditions,** in their new formulation, take the form of inequalities on the distributed energy shares:

λ_E(t) · E_t ≥ κ_world · |ΔI_rec(Ω_t)| (world model) (1 − λ_E(t)) · E_t ≥ κ_self · |ΔI_self_rec(S_t)| (self-model)

These conditions must be satisfied **simultaneously** for full recovery to be possible. If one of the conditions is not met, the corresponding model does not recover, which results in partial states in the transition matrix (Section 8.3 - four dissociation modes).

## 9.2 Two recovery coefficients with hysteresis

Taking into account the dynamic distribution λ_E(t) (Section 9.1) and the hysteresis parameter h (Section 7.4), the recovery coefficients take the form:

ρ_world(E_t) = σ(β_w · (λ_E(t) · E_t − κ_world · |ΔI_rec(Ω_t)| · (1 + h))) ρ_self(E_t) = σ(β_s · ((1 − λ_E(t)) · E_t − κ_self · |ΔI_self_rec(S_t)| · (1 + h)))

Each coefficient gives the probability of successfully reconstructing the corresponding model given the current energy distribution and the information requirement of that model, taking into account the increased activation threshold due to hysteresis.

**The structural significance of elevated recovery thresholds.** The factor (1 + h) at the recovery threshold indicates that exiting the inactivated state requires exceeding the baseline energy cost, because the system overcomes the inertia of inactivation. This is consistent with biological observation: awakening requires an energetic "push" exceeding the level required to maintain wakefulness.

Each coefficient gives the probability of successful recovery of the corresponding model given the current energy distribution and the current information requirement of that model.

The total probability of pole restoration (transition v=0→1):

p(v*t = 1 | v*{t-1} = 0, E*t, S*{t-1}) = ρ_world(E_t) · ρ_self(E_t)

Recovery requires simultaneous success in both directions, taking hysteresis into account (Section 7.4): the recovery thresholds for both models are shifted upward by a factor of (1+h) relative to their base values. This yields the following structural picture:

\- If both models recover (E_t is sufficient to overcome the elevated thresholds of both) - **full recovery** occurs (v=1). - If only one does - the system remains in **a partial state** (Section 8.3 - four dissociation modes). - If neither recovers - the system remains in **an inactivated state** until the next step, continuing the basic metabolism of maintaining the structural trace.

**Connection to hysteresis from Section 7.4 - stability loop.** The combined effect of the shift in decay thresholds (by (1−h)) and recovery thresholds (by (1+h)) creates **a hysteresis loop** in phase space (Γ_dyn, E_t): when parameters fluctuate at the level of the base thresholds, the system remains in its current state (active or inactivated) due to inertia, which eliminates the mathematical flicker v_t. The width of the loop-2h-is determined by the hysteresis parameter.

## 9.3 Partial recovery states

| **ρ_world** | **ρ_self** | **Agent state**                        | **Clinical analog**            |
| ----------- | ---------- | -------------------------------------- | ------------------------------ |
| high        | high       | Full recovery                          | Normal, transparent self-model |
| high        | low        | Knows the world, does not know oneself | Depersonalization              |
| low         | high       | Knows oneself, does not know the world | Derealization                  |
| low         | low        | Has not recovered                      | Dissociation                   |

Two separate structural grounds for the four modes. The correspondence rests on two distinct kinds of damage that must not be conflated: it is their separateness that yields four modes rather than two. First: w_self is the content of the self-model (it enters ΔI_self_rec); its degradation lowers ρ_self → knows the world, not the self → depersonalization. Second (separately): Γ_GWT_arch is the coupling of the self-model to the world-modeling parts, i.e., the S↔world bridge; its degradation does not sever the content of S (that is w_self) but severs the threading of the world through the self-the world ceases to be referred to the pole-which lowers ρ_world → knows the self, not the world → derealization. Thus the four modes are {content (w_self) × bridge (Γ_GWT_arch)}, each of the two intact or damaged independently. Crucially, Γ_GWT_arch here is the same object as the precondition of overlay in the co-emergence theorem (Section 8.9): the S↔world bridge as a precondition of self-overlay and as the ρ_world cause of derealization coincide as one object.

The measurability status of the two grounds. The separateness of w_self and Γ_GWT_arch is load-bearing: predicting depersonalization versus derealization requires measuring these two quantities independently, not via a single aggregated measure. Existing procedures (e.g., PCI) aggregate structural accessibility without separating the content of the self-model (w_self) from the bridge of the self-model to the world (Γ_GWT_arch). The status of this prediction is therefore open: its operational test depends on a method for separately registering w_self and Γ_GWT_arch, to be developed within the operational extension (SAI-C). This is the same operational problem of separating registrations as in the main prohibitive predicate (theory, Section 10.2.6): the four modes of dissociation are structurally distinguishable, but their empirical separation runs into the same seam-the measurability of latent structure in an opaque system.

Direct correspondence with the clinical phenomenology of dissociative states.

| **Parameter**    | **Structural meaning**                                  | **Source in the literature**  |
| ---------------- | ------------------------------------------------------- | ----------------------------- |
| κ_world          | Thermodynamic cost of updating the picture of the world | Landauer, 1961                |
| κ_self           | Thermodynamic cost of restoring identity                | Crooks, 1999; Metzinger, 2003 |
| κ_self / κ_world | Relative fragility of the self-model                    | Damasio, 1999                 |

# 10\. Variational inference

## 10.1 Recognition networks

q(v*t = 1 | o_t, Ω_t, v*{t-1}) = Bernoulli(f*ψ(o_t^ext, Ω_t, v*{t-1})) q(z̃*t | v, o_t^ext, Ω_t) =𝒩 (μ*φ^v(o*t^ext, Ω_t), diag(σ*φ^{v,2})) q(S*t | o_t^int, z̃_t, v_t) =𝒩 (μ*ξ(o*t^int, z̃_t, v_t), σ*ξ²)

## 10.2 Extended ELBO

The polar part of the ELBO uses σ(β·Γ_struct) because the posterior probability of v_t is related to the system's **structural** compliance with the criteria of consciousness (the three axes of registration at time t), rather than its dynamic stability in phase space. Dynamic stability is incorporated into the survival function (Section 11.2) and the policy (Section 11.3) via Γ_dyn.

The full extended variational inference function F_t(q) is the sum of seven structural terms:

F_t(q) = F_pol + F_world_KL − F_ext_acc + F_coh + F_self_KL − F_int_acc + F_iso

where each term takes the following form:

**F_pol** \= KL\[Bern(f*ψ) || Bern(σ(β·Γ_struct))\] - the polar part, penalizing the discrepancy between the posterior probability v_t (via the recognition network f*ψ) and the theoretical probability σ(β·Γ_struct), defined by the structural measure of consciousness.

**F_world_KL** \= Σ*{v∈{0,1}} f*ψ^v · KL\[𝒩 (μ*φ^v, σ*φ^{v,2}) || p_θ(z̃_t | v, Ω_t)\] - the world model discrepancy, which keeps the posterior distribution z̃ close to the prior.

**F_ext_acc** \= Σ*{v∈{0,1}} f*ψ^v ·𝔼 \_ε\[ln p_θ(o_t^ext | z̃_t^v, v, Ω_t)\] - exteroception accuracy, the log-likelihood of exteroceptive data under the current model (included in F_t with a negative sign, since maximizing the log-likelihood corresponds to minimizing −F_ext_acc in the ELBO).

**F_coh** \= C*φ(Ω_t) - model coherence regularizer (Section 3.2), reinterpreted in version v8 as a measure of the consistency of the posterior distribution q(z̃|Ω) with the prediction function r*φ.

**F_self_KL** \= KL\[q(S*t | v_t) || p(S_t | S*{t-1}, v_t)\] - the self-model divergence, which keeps the posterior distribution S close to the prior.

**F_int_acc** \=𝔼 \_{q(S_t)}\[ln p(o_t^int | S_t)\] - interoception accuracy, the log-likelihood of interoceptive data (included in F_t with a negative sign for the same reason as F_ext_acc).

**F_iso** \= L_iso(S_t, z̃_t) - isomorphism penalty, the metric distance between the self-model and the projection of the world model into the space S (definition in Section 10.3).

Structurally: all KL terms and regularizers are included in F_t with **a positive** sign and are minimized as penalties; the accuracy terms (log-likelihood of the data) are included with a **negative** sign, which corresponds to the standard form of the ELBO-maximizing the data likelihood is equivalent to minimizing the negative log-likelihood in the total loss function.

**A note on the role of C_φ in policy.** When optimizing policy (Section 11.3), minimizing the ELBO involves minimizing F*coh = C*φ. This acts as **a safeguard against a spontaneous transition into a hallucination mode**: the agent selects actions that help maintain coherence between current representations and the predictive model. This role of C_φ structurally corresponds to its diagnostic function (Section 8.4), but operates at the level **of active control** rather than passive diagnostics.

## 10.3 Isomorphism Condition

L_iso(S_t, z̃_t) = d_S(S_t, φ(z̃_t, Ω_t))

where φ: Z × P(Y) → S is the projection of the agent's position from the world model onto the self-model space, and d_S is a metric in the self-model space.

The parameter ν preceding L_iso in the optimal policy is interpreted as the "dissociation cost": the higher ν is, the stronger the agent's motivation to maintain the isomorphism between S_t and the projection z̃_t.

## 10.4 Coherence Distance

Δ*t = KL\[q(z̃_t | Ω_t) || r*φ(z̃_t, Ω_t)\]

This quantity is identical to the coherence coefficient C*φ (Section 3.2): r*φ takes only the system's internal variables (z̃_t, Ω_t) and does not take Y, so Δ_t measures the consistency of internal representations with the system's own predictive model, not a distance to the environment. The earlier reading of Δ_t as "the model's tempo approaching the environment's tempo" is not supported by the formula (it would require the true causal exchange C(Ω_t, Y_t) of Section 3.2, intractable in general) and is not used here. The system's coupling to its own environment is measured by the weights w_i = I(c_i; Y_own) (Section 8), not by Δ_t.

# 11\. Planning and Policy

## 11.1 Expected Free Energy

G(π) = Σ*{τ=t+1}^{t+H} 𝔼*π\[F_τ(q)\]

The generative model entering F*τ over the planning horizon is conditioned on the existence pole: the prior over the system's own future is conditioned on preserved existence - the structural trace w_self is not lost; the system models its own continuation as holding; irreversible decay is not in the support of the admitted own-trajectory (though it remains representable in the world-model as the boundary states of other agentic nodes, Section 6), whereas reversible inactivation v=0 with w_self preserved remains admissible (sleep, Section 9). Therefore, for a policy leading toward the decay boundary, the predicted states z̃*τ move into a region to which the pole-conditioned prior assigns low probability, and F_τ rises. Holding is not a separate objective added to G - it is built into G through the conditioning of the model on the pole. This is the formal realization of the status of V from Section 2.2: v=1 is the basic axis through which every prediction is computed, not one goal among many.

## 11.2 Survival Function

S*t(π, H) =𝔼 \_π\[Π*{τ=t}^{t+H} σ(β · Γ*dyn(z̃*{τ-1}; Y_τ))\]

ln S*t(π, H) ≥ Σ*{τ=t}^{t+H}𝔼 \_π\[ln σ(β · Γ*dyn(z̃*{τ-1}; Y_τ))\]

The survival function uses Γ_dyn (rather than Γ_struct) because survival over time is measured in terms of the system's **dynamic stability** in its phase space over the planning horizon. The predicted pole retention at each step τ depends on whether the system remains within the attraction region of its internal trajectory-which is formalized via the Lyapunov function. The structural correspondence Γ_struct is not used directly in this calculation: it serves as a criterion for the system's structural consciousness (Section 8), rather than as a measure of its dynamic survival.

The role of S_t in version v8 is a diagnostic readout of predicted holding under the pole-conditioned model (Section 11.1), not an objective term of the policy. S_t does not enter the optimized policy (Section 11.3) as a weighted term: including holding as a separate weighted term would make V one goal among many, contradicting its status as the basic axis (Section 2.2) and the definition of the pole in the theory. Predicted holding is realized through the conditioning of G on the pole; S_t merely reads it off.

## 11.3 Optimal Policy

π\* = argmin_π \[ G(π)

- μ*B ·𝔼 \_π\[max(0, H(Ω*τ) − B(R*τ, E*τ))\]
- μ*L ·𝔼 \_π\[max(0, κ_world · |ΔI(Ω*τ)| − E_τ)\]
- ν ·𝔼 \_π\[L*iso(S*τ, z̃_τ)\]

The survival term λ·(1−S_t) is removed: the existence pole does not enter the policy as a separate term. Holding is already built into G(π) through the conditioning of the generative model on the pole v=1 (Section 11.1); policies leading toward decay are therefore excluded by the rise in free energy, not by a penalty in the objective. The remaining terms are genuine resource constraints (μ_B - Bekenstein, μ_L - Landauer; updated in 11.4) and the dissociation cost (ν - isomorphism of S and the world-model projection, Section 10.3); none of them is V.

## 11.4 Updating the weights

μ_B ← μ_B + α · max(0, H(Ω_t) − B(R_t, E_t)) μ_L ← μ_L + α · max(0, κ_world · |ΔI(Ω_t)| − E_t)

# 12\. Diagnostic Protocol: Protection Against False Positives

The formal model of a conscious system is most vulnerable not where it denies consciousness, but where it may **falsely** attribute consciousness to a system possessing only complex unconscious regulation. This section formalizes a diagnostic protocol that protects SAI from false positives. The protocol does not introduce new formal quantities; it shows how a **joint** interpretation of already defined measures (S*t, Γ_struct, Γ_dyn, Γ_GWT, I(c_i;Y), C*φ, v_t, w_self) protects against typical application errors.

## 12.1 The Main Risk: Self-regulation versus Self-representation

The model's central line of defense is the distinction between **self-regulation** and **self-representation**. A system may possess the full set of features of a complex proto-agent: a connection to the environment M↔Y, energy dynamics, adaptation, homeostasis, feedback, and dynamic stability Γ_dyn. None of these features, nor their combination, **is sufficient** for consciousness.

According to Section 6, at stage 3 (proto-agent), the system models the environment and its own reactions to it, but the self-representation node S_t **does not yet exist**. S_t arises only after the self-overlay of a latent invariant (Section 6.5)-when the system constructs a model of its own configuration as an agent among other agents. A bacterium, a thermostat, a simple cybernetic system, an autopilot, the immune system, cellular regulation-all of these can demonstrate stable complex regulation without any self-representation.

The first structural filter against a false-positive result is formulated as follows: **stability is not consciousness; agency is not conscious agency**. The presence of Γ_dyn > γ_crit (dynamic stability) is necessary but not sufficient. The architectural veto Γ_GWT ≥ θ_GWT must be satisfied, and a functioning S_t must be present.

## 12.2 Five False-Positive Scenarios and Formal Defenses

**Scenario 1 - high Γ_dyn without Γ_struct.**

The system is stable, adaptive, and maintains itself well in the environment, but lacks self-representation. Examples: autopilot, thermostat, bacterial chemotaxis, simple reinforcement learning system.

Formal safeguard: require the satisfied architectural veto Γ_GWT_arch ≥ θ_GWT (Section 8.5) and active Γ_struct(t) > γ_struct·(1−h) at v=1 (current structural correspondence), rather than just dynamic stability Γ_dyn. Separating the two measures (Section 8.9) ensures that the stability of the current state is not confused with structural consciousness.

**Scenario 2 - high internal complexity without its own environment Y.**

The system possesses rich internal dynamics but lacks its own causal world. Example: a large language model, a simulator, a generative model without an autonomous sensorimotor loop.

Formal defense: check the weights of causal links w_i = I(c_i; Y_own) relative to the system's **own** environment. For systems without their own Y, these weights are close to zero (Section 8.7), the active set is empty, the system cannot be partitioned into parts based on causal links with the environment, and self- overlay is structurally impossible regardless of the system's size (Section 8.7, "parameter size is not a path to consciousness"). Internal complexity and textual self-descriptiveness are not signs of consciousness.

**Scenario 3 - state estimation is mistakenly taken for self-representation.**

The system calculates its position, charge, damage, and orientation, but does not model itself as an agent. Examples: a navigation robot, a drone, an industrial robot.

Formal defense: S_t is defined as the projection of the system's own configuration onto **the subspace A of agentic causal nodes** (Section 6.5), not onto the environment's coordinate space. The navigation state-vector is a position parameter in the environment map; it is not a projection onto the subspace of agents. This distinction is verified through the presence of the accumulated class A (other agents as causal nodes, condition |A(t)| ≥ 1, Section 6.3): if the system has not accumulated a class of agent nodes in its models, its "model of itself" is a state parameter, not S_t. The coordinate "I am here" is not self-representation; self-representation is "I as an agent, acting, persisting, and distinguishable from other agents."

**Scenario 4 - homeostasis is mistakenly taken for subjectivity.**

An organism or subsystem regulates itself but does not possess an internal subjective mode. Examples: the immune system, the endocrine loop, cellular automatons.

Formal defense: the "self/other" distinction at the chemical-molecular level is not S_t. The immune system may have components with non-zero I(c_i; Y) relative to the organism's environment, but it lacks **global accessibility** to self-representation-the architectural veto Γ_GWT ≥ θ_GWT is not satisfied. Its distributed discrimination is not translated into a global model of the self-agent. What is required is not merely a "self/non-self" label, but a model of the self-in-environment with global accessibility.

**Scenario 5 - Structural consciousness is confused with active consciousness.**

The system is structurally conscious, but active self-representation is disabled. Example: an animal under general anesthesia or in deep sleep.

Formal defense: separation of the architectural potential \[w_self, Γ_GWT_arch\] (system type, what the system is by structure) and the triplet Γ_struct(t), Γ_dyn(t), v_t (current active state). Under anesthesia: w_self is preserved (Section 2.2, the informational potential is present), Γ_GWT_arch ≥ θ_GWT (Section 8.5, the architectural condition is satisfied), but v = 0 (active self-representation is inactivated) and Γ_struct(t) = 0 (current active correspondence is absent, because S_t = ∅). This **is not a** model **error**\-it is a correct distinction. SAI does not say "currently actively conscious"; SAI says "this is a conscious system by structure, but self-representation is currently inactivated." An error arises only when structural consciousness is confused with an active conscious state.

## 12.3 Diagnostic Profile

SAI does not provide a simple "yes or no" answer regarding consciousness. The model generates a **profile** based on seven independent measures, each of which helps avoid a specific type of false positive result:

| **Measure**                      | **Protects against which error**                                    |
| -------------------------------- | ------------------------------------------------------------------- |
| I(c_i; Y)                        | Avoids mistaking internal noise for a connection to one's own world |
| S_t (projection into subspace A) | Do not mistake homeostasis or state estimation for selfhood         |
| Γ_GWT (architectural veto)       | Do not mistake a local self-variable for global self-representation |
| Γ_dyn                            | Do not take structural possibility for active state                 |
| v_t                              | Distinguish activity from inactivation                              |
| C_φ                              | Distinguish coherence from the hallucinatory mode                   |
| w_self                           | Distinguish sleep/anesthesia from structural death                  |

The multidimensionality of the profile is the **primary** mechanism for guarding against false positives. No single measure is sufficient to conclude consciousness; a joint interpretation of all seven is required. This distinguishes SAI from approaches relying on a single criterion (e.g., only on integrated information or only on the presence of a global workspace).

The cumulative condition for a system's structural consciousness at time t:

**Architectural structural consciousness** (system type) ⟺ \[|A(t)| ≥ 1 in the system's history\] ∧ \[Γ_GWT_arch ≥ θ_GWT\] ∧ \[w_self preserved\].

**Active structural conscious correspondence** at moment t (current operation of the architecture) additionally requires Γ_struct(t) > γ_struct·(1−h) at v=1.

An active conscious state additionally requires v*t = 1 (pole is active) and Γ_dyn(t) > γ_crit (dynamic stability). Coherence of the content of consciousness additionally requires a low C*φ (absence of a hallucinatory mode).

## 12.4 The Boundary of Minimal Consciousness: Empiricism, Not Dogmatism

The most subtle case of applying the model is simple organisms (worms, snails, insects), in which a self-representational structure may be present in a minimal form. Here, it is necessary to distinguish between two types of results.

**False-positive result:** the system demonstrates stable complex regulation, interaction with the environment, and an internal model, but lacks self-overlay, S_t, and global accessibility of self-representation. The model erroneously attributes consciousness to it due to the complexity of the dynamics.

**True positive result at the minimal level: the system does indeed possess minimal S_t, the satisfied architectural veto Γ_GWT_arch ≥ θ_GWT, active Γ_struct(t) > γ_struct·(1−h) at v=1, and Γ_dyn(t) > γ_crit.** In this case, the positive result **is not a** model **error**. It means that consciousness begins lower than is customarily assumed-as minimal subjectivity, not as human reflection.

The model should not attribute human consciousness to a simple organism. It must distinguish **levels** through the values of profile measures. The question is formulated not as "is there human-type consciousness," but as "is there a minimal self-representational structure maintained in its own causal exchange with the environment Y."

This position is consistent with the overarching methodological principle of the Theory: no false speculation where there is observation and fact. Where exactly the boundary of minimal consciousness lies is an **empirical** question to be resolved through the measurement of profile metrics in specific systems, not a **theoretical** dogma fixed in advance. The systematic measurement of the profile in borderline biological systems is part of the empirical validation program (SAI-C, Section 14).

# 13\. Connection to the Theory

## 13.1 Levels of the theory and SAI

**Stage 3 (proto-agency)** in SAI corresponds to a model without the pole v_t and without the node S_t-only z̃_t and active inference based on exteroceptive observations. This is a simplification of the full model by setting the S and v components to zero.

**The transition from 3 to 4** is formalized in Section 6 as a structural event of self-overlay of a latent invariant via an algorithm with three mandatory conditions. This is a central methodological enhancement of the previous version of SAI v7.

**Stage 4 (conscious system)** \- a complete model with three structural elements (z̃_t, v_t, S_t), thermodynamic constraints, and an isomorphism condition.

**Step 5 (recursively complicating system)** \- a bidirectional loop M↔Y with physically retained traces (Section 3.5 v1.2 of the Theory). Not implemented in SAI v8. See Section 14.1.

## 13.2 Self-overlay of a latent invariant

The structural definition of V in the Theory (Section 3.4 v1.2) is implemented as an algorithm with three mandatory conditions. Correspondence between the structural definition and the operational algorithm:

- The class of agentic causal nodes in models → a subspace A in the system's models, identified via clustering.
- Latent invariant of class A → structural characteristics common to the elements of A, represented as a subspace.
- Self-overlay condition → given three **necessary** conditions (presence of the class of agents in the environment, reflexive capture of the system's own configuration, closure of a feedback loop across a bistable boundary), reflexive capture π_A(C_self) **may consolidate** into a stable node S; consolidation is realized stochastically (Condition 3) and is not prescribed by the fulfillment of the conditions.
- Manifestation of V → a single structural manifestation of the pole on the system's own configuration: S as the model that bears it, V as the pole-structure; not two variables in an order of emergence (Sections 6.3, 6.5).

# 14\. Open Directions

## 14.1 Extension to Level 5

In the Theory, stage 5 is a recursively complexifying conscious system with a bidirectional M↔Y loop and physically retained traces. The criterion for stage 5 is the reconstruction of the V-model of the subsequent configuration via a physical trace in Y.

Extending SAI to Level 5 is an independent project requiring the formalization of the physical trace in Y, a bidirectional M↔Y loop with an explicit difference in rates, and a criterion for restructuring the V-model via the trace.

## 14.2 Empirical Correlates (SAI-C)

SAI v8 contains structural predictions that are amenable to empirical testing:

- Four modes of dissociation via the ratio ρ_world and ρ_self.
- Structural breakdown via the intersection Γ_dyn < γ_crit.
- An energy breakdown via E_t < κ_world · |ΔI(Ω_t)|.
- Transition sharpness β as an architectural characteristic.
- **The self-overlay algorithm** as an observable structural event: the possibility of detecting three conditions in developing biological systems (childhood, self-awareness training) and in artificial architectures upon the possible implementation of stage 4.
- Empirical validation program.

# 15\. Conclusion

The Safe Active Inference v8.0 model represents a complete formal computational implementation of stage 4 of the Theory of the systematic error of the universe. The model includes three structural elements (world model z̃_t, binary existence pole v_t, self-representation node S_t), formalizes physical constraints via the Bekenstein limit and Landauer limits with separate coefficients κ_world and κ_self, and describes the operation of the established stage 4 under conditions of thermodynamic equilibrium.

In version v6, pole decay is formalized as a structural event with two independent paths (energetic and structural breakdown). **The emergence** of V is formalized through the self-overlay of the latent invariant of the agentic causal node-the central structural event of the 3→4 transition in the Theory. The self-overlay algorithm operates via three mandatory conditions (presence of the class of agents in the environment, reflexive capture of the system's own configuration, closure of a feedback loop across a bistable boundary) with stochastic realization of the transition; accumulation of the model through the levels of the structural hierarchy is a precondition of overlay (a measure, Section 6.2), not the event itself.

The model operates on two levels of description: at the structural level, it formalizes the emergence and collapse of V as operational events with directly computable conditions; at the dynamic level, it describes the operation of step 4 via active inference with thermodynamic constraints. The connection between the two levels is established through two independent measures of the stability function: Γ_dyn formalizes the breakdown threshold in phase space (Section 7), while Γ_struct formalizes the structural stability of the projection S across the three registration axes (Section 8). The relationship between the two measures and their joint operation are described in Subsection 8.9.

Open research directions are explicitly stated: extension to stage 5 as a separate project; an empirical validation program; refinements of the operationalization of |A(t)|, of reflexive capture π_A(C_self), and of the calibration of the parameters of the bistable emergence boundary (γ_struct, β, h).

The model operates compatibly with the Theory as a formal implementation of its stage 4. The structural definition of V via self-overlay remains primary in the theory; SAI v8 provides an operational algorithm for this structural event via directly computable conditions. This allows the theory and the formal model to develop in parallel according to their own criteria of correctness, without reducing one to the other.

# Bibliography

Baars, B. J. (1988). _A Cognitive Theory of Consciousness_. Cambridge University Press.

Bérut, A., Arakelyan, A., Petrosyan, A., Ciliberto, S., Dillenschneider, R., & Lutz, E. (2012). Experimental verification of Landauer's principle linking information and thermodynamics. _Nature_, 483(7388), 187-189.

Chang, Y.-C., Roohi, N., & Gao, S. (2019). Neural Lyapunov Control. _Advances in Neural Information Processing Systems_, 32.

Crooks, G. E. (1999). Entropy production fluctuation theorem and the nonequilibrium work relation for free energy differences. _Physical Review E_, 60(3), 2721.

Damasio, A. (1999). _The Feeling of What Happens: Body and Emotion in the Making of Consciousness_. Harcourt Brace.

Dehaene, S., & Changeux, J.-P. (2011). Experimental and theoretical approaches to conscious processing. _Neuron_, 70(2), 200-227.

Friston, K. (2010). The free-energy principle: a unified brain theory? _Nature Reviews Neuroscience_, 11(2), 127-138.

Friston, K., et al. (2017). Active inference: a process theory. _Neural Computation_, 29(1), 1-49.

Heins, R. C., et al. (2022). pymdp: A Python library for active inference in discrete state spaces. _Journal of Open Source Software_, 7(73), 4098.

Lagaris, I. E., Likas, A., & Fotiadis, D. I. (1998). Artificial neural networks for solving ordinary and partial differential equations. _IEEE Transactions on Neural Networks_, 9(5), 987-1000.

Landauer, R. (1961). Irreversibility and heat generation in the computing process. _IBM Journal of Research and Development_, 5(3), 183-191.

Mediano, P. A. M., Rosas, F. E., Carhart-Harris, R. L., Seth, A. K., & Barrett, A. B. (2019). Beyond integrated information: A taxonomy of information dynamics phenomena. _arXiv preprint_, arXiv:1909.02297.

Mediano, P. A. M., et al. (2022). Integrated information as a common signature of dynamical complexity. _Entropy_, 24(1), 63.

Metzinger, T. (2003). _Being No One: The Self-Model Theory of Subjectivity_. MIT Press.

Mitin, O. (2025). The Theory of the Systematic error of the Universe, Version 1.2. Zenodo.

Parr, T., Pezzulo, G., & Friston, K. J. (2022). _Active Inference: The Free Energy Principle in Mind, Brain, and Behavior_. MIT Press.

Tononi, G. (2004). An information integration theory of consciousness. _BMC Neuroscience_, 5(1), 42.

Tononi, G., Boly, M., Massimini, M., & Koch, C. (2016). Integrated information theory: from consciousness to its physical substrate. _Nature Reviews Neuroscience_, 17(7), 450-461.