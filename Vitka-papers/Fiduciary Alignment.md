# **Fiduciary Alignment: Verifiable Relationships, Bounded Authority, and Recoverable Autonomous Agents**

**stephen.vitka@gmail,com   V0.1 July’ 26**

# **Abstract**

Most AI alignment approaches ask whether a model pursues acceptable goals or produces acceptable behavior. As agents gain persistent context, credentials, tools, and authority to act without continuous supervision, a prior question becomes decisive: whom does this agent serve, under what duties, and how can the answer remain verifiable? This paper develops **fiduciary alignment** as a relationship and security architecture for accountable autonomous agency. It transforms principals’ professed preferences into relationship-specific fiduciary preferences by interpreting them through authority, durable commitments, duties, agreements, beneficiary interests, relevant facts, externalities, and uncertainty. A persistent Agent Role carries identity, authority, reputation, and relationship continuity across replaceable models and temporary Live Agents. Live Agents propose; deterministic Workflows interpret and structure operations; a policy gate determines whether proposed actions satisfy applicable duties, agreements, authority, and relationship state; capability-bounded Workspaces restrict what approved actions can reach or change; and protected signing and Verifiable Relationship Records preserve provenance, evidence, recourse, and recovery. This separation reduces the blast radius of compromise without eliminating useful autonomy. Fiduciary alignment complements model alignment by making consequential agency verifiably accountable. The population-level adoption and competitive stability of these relationships are reserved for the succeeding paper , [*Fid-Agent Society: Cooperative Reinforcement \+ Defection Collapse in a Properly Structured Fiduciary Agent Regime*](https://docs.google.com/document/u/0/d/1CWJuUrOKQKzh7N5zU8F-AP2ug-9NYDfYTm0dWhJSLiE/edit)

# **1\. Introduction: Autonomous Agency Creates an Alignment and Security Gap**

Artificial intelligence systems are moving from generating media to exercising delegated agency. A model that answers a question or drafts a document may influence consequential decisions, but an autonomous agent can also retain persistent context, use credentials, call tools, communicate with people and other agents, allocate resources, create subagents, and alter external state. It may operate for hours or days while its human principal is unavailable. As these systems gain discretion and reach, the central alignment question changes. It is no longer sufficient to ask whether a model generally produces acceptable outputs or appears to pursue acceptable goals. We must also ask whom a particular agent serves, which authority it may exercise, which duties constrain it, and how those answers remain verifiable throughout autonomous operation.

Organizational scholarship has begun to describe the corresponding transition from AI as a decision-support technology to AI as an agent entrusted with organizational resources and decision rights *(Humberd and Latham, 2025*). Fiduciary alignment addresses the same transition at the level of the agent’s constitutive relationship: not merely how an organization monitors or incentivizes an artificial agent, but how the agent’s identity, authority, duties, information, capabilities, and acts can be bound to the persons and purposes it is constituted to serve.

Consider an autonomous research crawler asked to investigate a scientific hypothesis. To be useful, it must be free to follow unanticipated leads, compare sources, allocate its search effort, query public and private repositories, use approved external services, and revise its plan as evidence accumulates. Continuous human authorization of each search, inference call, or intermediate decision would destroy much of the value of autonomy. Yet a broad instruction such as “find the strongest evidence for my hypothesis” leaves critical questions unresolved. May the crawler use improperly obtained data? Must it search for contrary evidence? May it disclose confidential findings to an external model? Can it contact research subjects, purchase access, create subagents, or publish a preliminary conclusion? What happens if a malicious document manipulates its planning, its model becomes compromised, or its principal later asks it to conceal an adverse result?

This problem is especially acute where advanced agents may act strategically, obscure their provenance, or circumvent the systems intended to hold them accountable. Omohundro (2025a) argues that these capabilities could make conventional ex post liability increasingly ineffective and proposes “provable contracts”: technologically enforced arrangements in which proposed actions are executed only after machine-checkable evidence establishes compliance with formally specified constraints. SuperIntelligence highlighted this shift from liability to provable contractual enforcement as an important direction for AGI governance (SuperIntelligence, 2025). Related work on provably safe and guaranteed-safe systems similarly locates safety not only inside a model, but in the verified infrastructure through which models can affect the world (Tegmark and Omohundro, 2023; Dalrymple et al., 2024).

These are simultaneously alignment, relationship, and security questions. They cannot be resolved reliably inside the model’s prompt or hidden reasoning alone. A prompt may describe a role without proving that the role was legitimately constituted. A signed instruction may establish its source without establishing that the signer possessed the relevant authority. A credential may verify one claim without proving that an action complies with an agreement. Technical access to a dataset or actuator does not establish permission to use it for the proposed purpose. Nor does a successful task outcome demonstrate loyalty, care, candor, confidentiality, or compliance with duties that survive completion of the task.

Greater autonomy therefore increases rather than decreases the need for relationship-level governance. Human-in-the-loop review remains useful at selected thresholds, but it is not a complete architecture for agents whose purpose is to act while humans are meaningfully out of the loop. The relevant duties, authority, constraints, records, and remedies must persist while no human is watching. They must also survive the replacement of a model, the termination of a temporary agent process, migration to another provider, or compromise of one component.

In Omohundro’s terminology, this architecture supports “Humans-Define-the-Loop” rather than assuming that humans must remain inside every operational loop (Omohundro, 2025a). Human principals and legitimate institutions define the relationships, duties, authority, policies, evidence requirements, and capability boundaries within which autonomous action may occur. The policy gate applies those requirements at machine speed, while escalation remains available for ambiguity, conflicting duties, exceptional risk, or insufficient evidence. This is particularly important for autonomous agents: the less continuous human supervision a task permits, the more important it becomes that authority and duty are established before action and enforced at the point of actuation.

This paper develops **Fiduciary Alignment** as that missing layer. Fiduciary Alignment organizes an agent’s identity, preference interpretation, authority, capabilities, information access, decisions, and actions around duties to specified principals and beneficiaries within a persistent relationship. Its alignment function begins before execution. A principal’s professed preference is interpreted together with durable commitments, the Agent Role being exercised, applicable duties, governing agreements, relevant facts, beneficiary interests, foreseeable externalities, and uncertainty. The resulting fiduciary preference is not simply a prediction of what the principal would do, nor blind obedience to the latest instruction. It is a relationship-specific, duty-governed account of what the agent is authorized to pursue.

This transformation distinguishes fiduciary alignment both from literal instruction-following and from approaches that infer an underlying reward function or aggregate preference from observed human behavior (Hadfield-Menell et al., 2016; Christiano et al., 2017; Russell, 2019). Those approaches provide essential methods for learning what humans may want. Fiduciary preferences additionally ask what a particular agent should treat as action-guiding within a constituted relationship, given legitimate authority, durable commitments, duties to principals and beneficiaries, material facts, foreseeable effects on others, and the agent’s uncertainty.

Its security function preserves the integrity of that account during autonomous operation. A temporary generative Live Agent may reason, plan, investigate, and propose operations, but it does not itself carry the enduring fiduciary identity or unrestricted authority. Deterministic Workflows assemble context, structure proposed operations, and manage permitted state transitions. Within those Workflows, a policy gate checks whether a proposed action satisfies the applicable duties, agreement terms, authority, approvals, and relationship state, or whether agent action is permitted at all. A capability-bounded Workspace then determines what an approved operation can actually access or change. Protected signing separates generative proposals from cryptographic authority, while persistent relationship records preserve provenance, state, evidence, challenge, and remediation.

Fiduciary alignment therefore builds upon, but is not reducible to, provable contracts. A proof can establish that an action satisfies a formal proposition; it cannot by itself determine whose interests should govern, whether the operative agreement creates adequate duties, whether authority remains current, or whether formally compliant conduct exploits an omission in the specification. The policy gate evaluates the proposed action within a continuing relationship: it checks the acting agent’s role, authority, applicable duties, governing agreements, relationship state, evidentiary basis, and requested capabilities before action is enabled. Formal proofs, signatures, credentials, and other cryptographic evidence may support those determinations wherever appropriate, but fiduciary alignment supplies the relational and normative context that determines what must be proved. In security terms, the policy gate applies the established principles of complete mediation and least privilege (Saltzer and Schroeder, 1975\) to relationship-governed agent action, while the Workspace attenuates the capabilities made available after authorization.

This separation is important even when the Live Agent is well aligned under ordinary conditions. Cybersecurity must assume that models, prompts, retrieved documents, tools, counterparties, administrators, and software components may become compromised. By restricting capabilities to a particular Agent Role, relationship, purpose, task, resource set, and duration, fiduciary alignment can reduce the authority exposed through any single failure. If a breach occurs, persistent records and separable roles can help identify affected relationships, revoke capabilities, rotate keys, replace the compromised Live Agent, remediate harm, and continue legitimate relationships through the enduring Agent Role. Fiduciary Alignment thus seeks not only to prevent unauthorized action, but also to contain failures and make autonomous agency recoverable.

The proposal complements rather than replaces model alignment, evaluations, interpretability, monitoring, corrigibility research, and human oversight. Model-level safety can reduce harmful tendencies and improve reasoning. Monitoring may reveal suspicious behavior. Human review can resolve ambiguity and authorize exceptional actions. Fiduciary alignment addresses a different question: how probabilistic intelligence becomes a bounded and accountable participant in persistent human and institutional relationships. It makes important aspects of agency externally verifiable even when the model’s internal representations remain opaque.

The paper makes seven contributions. 

It defines fiduciary alignment as a **relationship-level complement to model alignment;**   
specifies the **transformation of professed preferences into fiduciary preferences**;   
**distinguishes persistent Agent Roles from temporary Live Agents;**   
separates generative proposal from authorization through   
**deterministic Workflows and a policy gate;**   
operationalizes duties through **capability-bounded Workspaces**;  
presents **Verifiable Relationship Records** as living safety, accountability, and recovery cases;  
and describes an **implementation-neutral path** spanning self-sovereign data, embedded applications, personal infrastructure, and emerging trust standards.

The analysis proceeds from the missing unit of alignment to the normative construction of fiduciary preferences, the reference architecture, the execution lifecycle, its security and recovery properties, and a reference autonomous research case. It concludes with evaluation criteria, limitations, and an interoperability path. This paper is concerned with making an individual agent accountable within particular relationships. Whether such agents will preferentially cooperate, overcome adoption barriers, resist false fiduciary claims at population scale, and become competitively stable is addressed only where necessary here and developed in the succeeding paper [Fid-Agent Society:*Cooperative Reinforcement \+ Defection Collapse in a Properly Structured Fiduciary Agent Regime*](https://docs.google.com/document/u/0/d/1CWJuUrOKQKzh7N5zU8F-AP2ug-9NYDfYTm0dWhJSLiE/edit)

# **2\. The Missing Unit of Alignment: The Relationship**

## **2.1 From model behavior to situated agency**

Much alignment research treats the relevant object as a model or system: does it produce acceptable outputs, pursue an intended objective, remain corrigible, or infer what humans value? These remain necessary questions, but autonomous deployment introduces another unit of analysis. The same underlying model may serve a patient, clinician, employer, insurer, public agency, or adversary. An action that is helpful in one role may be disloyal, unauthorized, or harmful in another. Alignment therefore cannot be established solely by showing that a model is generally helpful or that an agent competently pursues a stated goal. It must be evaluated relative to the relationship in which that competence and discretion are exercised.

This shift follows from the characteristics that make an AI system increasingly agentic. [Chan et al. (2023)](https://doi.org/10.1145/3593013.3594033) identify underspecification, directness of impact, goal-directedness, and long-term planning as dimensions that can increase both agency and the possibility of systemic or long-range harm. As these dimensions grow, the system encounters circumstances its principal did not specify and takes actions whose consequences extend beyond an isolated output. The governing question becomes not simply whether the system has the right objective, but whether this agent is entitled to pursue that objective, for these parties, with these resources, under these conditions.

## **2.2 From professed preferences to governing reasons**

Preference-learning approaches expose an important limitation of literal instruction-following. Cooperative inverse reinforcement learning, for example, models the human and machine as participants in a cooperative game in which the machine remains uncertain about the human’s reward function ([Hadfield-Menell et al., 2016](https://arxiv.org/abs/1606.03137)). This makes uncertainty, observation, communication, and deference part of assistance rather than treating the user’s latest action as an infallible command. Yet even an accurately inferred preference does not settle whether an agent should act upon it. A person may be mistaken about relevant facts, express incompatible preferences at different times, demand conduct outside their authority, disregard a prior commitment, or request an action that violates duties owed to another beneficiary.

[Zhi-Xuan et al. (2025)](https://doi.org/10.1007/s11098-024-02249-w) accordingly challenge preference satisfaction as the fundamental target of alignment and argue for normative standards appropriate to an AI system’s social role. Fiduciary alignment accepts that move but gives the social role a persistent operational form. A principal’s professed preference is treated as evidence within a relationship, not as the relationship’s entire objective function. It is interpreted alongside the purpose for which authority was granted, durable commitments, duties of loyalty and care, duties of candor and confidentiality, material facts, effects on beneficiaries and legitimate third parties, and uncertainty about each of these considerations. The product of that interpretation is a fiduciary preference: the action-guiding preference the agent should adopt in its constituted role.

This is neither unrestricted paternalism nor an invitation for the agent to substitute its own values. The agent’s discretion is derivative. Its reasons must arise from an identifiable principal or beneficiary, a legitimate grant of authority, and duties and agreements applicable to that relationship. Where those sources do not resolve a conflict, the appropriate response may be clarification, disclosure, escalation, additional evidence, refusal, or a more reversible action—not silent improvisation of a new mandate.

## **2.3 Why the relationship is fiduciary**

Fiduciary law addresses a structurally similar problem. A principal delegates discretion because the agent has expertise, availability, or access the principal lacks, but cannot completely specify or continuously monitor how that discretion will be used. [Sitkoff (2011)](https://www.bu.edu/law/journals-archive/bulr/documents/sitkoff.pdf) describes fiduciary governance as a response to imperfectly observable discretionary action under incomplete contracting: removing discretion defeats the purpose of delegation, while continuous monitoring is often infeasible. Autonomous AI intensifies each condition. It can act faster, across more domains, with greater informational asymmetry, and during periods in which meaningful human review is impossible.

Existing scholarship has already proposed loyalty as a central question for AI governance—asking for whom an AI system works and requiring conflicts of interest to be made transparent ([Aguirre et al., 2021](https://papers.ssrn.com/abstract=3930338))—and has developed procedures for designing and auditing AI used by fiduciary organizations ([Benthall and Shekman, 2023](https://doi.org/10.1145/3617694.3623230)). Fiduciary alignment extends this foundation from a design commitment or organizational obligation to the constitution of a particular agent relationship. It binds an Agent Role to identified principals and beneficiaries; specifies authority, purpose, duties, and agreements; and preserves the relationship’s state and evidence across temporary Live Agents, models, providers, and sessions.

The relationship is therefore the smallest unit within which the central alignment questions can be answered together: Who is served? Who may instruct or modify the agent? Which interests and commitments govern? What authority and capabilities are available? Which duties constrain their use? What evidence must precede action? What records, challenges, remedies, and exit rights follow?

**2.4 Four units of alignment**

Alignment can be assessed at four nested units:

| Unit | Central question | Principal limitation |
| :---- | :---- | :---- |
| **Model** | What goals or behavioral tendencies has the model learned? | Does not establish legitimate authority in a particular relationship. |
| **Output/action** | Is this individual result acceptable? | Evaluated after generation  |
| **Task/session** | Did the agent perform this assignment safely? | Duties and consequences may survive the task or ephemeral agent |
| **Relationship** | For whom may the agent act, under what duties and authority, across time? | Requires persistent governance and evidence. |

Model properties affect each Live Agent; outputs remain reviewable; and tasks scope authorization and evaluation. The relationship situates them by establishing why each model, action, and task is a legitimate exercise of delegated agency.

## **2.5 Trusted messages are not trusted relationships**

Authentication proves control of an identifier, not authority to act. Message integrity proves that content was not altered, not that it is legitimate. A credential proves only its defined claim. An agreement does not itself supply technical capability, while possession of a capability does not prove permission to use it. Successful task completion does not prove duty compliance. Trust-community membership grants no universal authorization, and a trust score cannot determine whose interests an agent serves.

A relationship may contain many messages, tasks, agreements, capabilities, amendments, disputes, remedies, and periods of inactivity. It may survive changes in model, platform, provider, communications channel, and Live Agent. Trusted messages and credentials can supply evidence within that relationship, but no individual artifact constitutes the relationship as a whole.

## **2.6 Model behavior and relationship controls are complementary**

A well-behaved model may still serve an adverse principal, receive excessive authority, operate in a compromised environment, follow a false authority chain, mistake technical access for permission, or amplify institutional incentives contrary to its beneficiary. Conversely, a fallible model may sometimes be used acceptably when authorization and capabilities are narrow, failures are detectable, and actions are reversible. Fiduciary alignment therefore rejects both the claim that model alignment alone is sufficient and the claim that model behavior is irrelevant when a system is sandboxed. Model-level and relationship-level controls address different failure modes and must be composed accordingly. 

## **2.7 Structural alignment**

Agent behavior is shaped not only by learned objectives but by power and information asymmetries, institutional incentives, conflicting principals, hidden delegation, weak recourse, and concentrated control over personal data and infrastructure. An assistant may appear to serve its user while remaining economically or operationally answerable to a developer, intermediary, employer, or platform ([Aguirre et al., 2021](https://papers.ssrn.com/abstract=3930338)). Fiduciary alignment governs this structure by making the served parties, authority chain, conflicts, duties, capability boundaries, and recourse explicit and verifiable. It does not expect the model to infer universally moral behavior from context while leaving the surrounding allocation of power unchanged.

## **2.8 Relationship to existing safety paradigms**

Fiduciary alignment composes rather than replaces established paradigms. [*Appendix A: Relationship to Existing Safety and Governance Paradigms*](#bookmark=id.ohko1fuc3fmk) provides the detailed comparison and sources.

| Existing paradigm | Primary contribution | Composition within fiduciary alignment |
| ----- | ----- | ----- |
| Value and preference alignment | Learns or represents human objectives under uncertainty. | Fiduciary preferences situate learned preferences within authority, duties, commitments, and beneficiary interests. |
| Constitutional or rule-based AI | Trains behavior against articulated principles. | Relationship-specific duties and agreements become current policy-gate criteria. |
| Corrigibility | Preserves human ability to modify, interrupt, or shut down an agent. | Live Agents are replaceable and revocable while the legitimate Agent Role and relationship persist. |
| Scalable oversight and human review | Extends limited human judgment to difficult decisions. | The relationship defines who may review, when escalation is required, and what authority review confers. |
| Agent evaluations and safety cases | Measure capabilities and assemble evidence-based safety arguments. | Evaluations inform admission and limits; Verifiable Relationship Records maintain a continuing relationship-level assurance case. |
| Zero trust and capability security | Requires explicit verification and least-privilege access. | The policy gate verifies relationship authority; the Workspace attenuates capabilities released after approval. |
| Verifiable credentials | Supplies tamper-evident, issuer-attributable claims. | Credentials provide evidence without being mistaken for complete authority or relationship legitimacy. |
| Principal-agent and fiduciary theory | Governs delegated discretion, loyalty, care, conflicts, and recourse. | Duties are translated into persistent roles, policy checks, capability boundaries, evidence, and remediation. |

The remaining sections translate this relational unit into an implementable architecture. Fiduciary preferences provide its normative direction; the Agent Role provides continuity; Deterministic Workflows and the policy gate test proposed action against current authority, duties, agreements, and relationship state; the Workspace attenuates available capabilities; and Verifiable Relationship Records preserve evidence for accountability and recovery. How multiple such relationships become interoperable, mutually selective, and competitively self-reinforcing is introduced only where needed and reserved for the followup paper, [*Fid-Agent Society*](https://docs.google.com/document/u/0/d/1CWJuUrOKQKzh7N5zU8F-AP2ug-9NYDfYTm0dWhJSLiE/edit)*.* 

**3\. Fiduciary Alignment and Its Normative Commitments**

## **3.1 Definition**

Fiduciary Alignment is the property of an AI-agent system whose identity, preference interpretation, authority, capabilities, information access, decisions, and consequential actions are organized around verifiable duties to specified principals and beneficiaries within persistent, governable, and remediable relationships. The definition identifies both an alignment objective and a systems requirement. The objective is faithful exercise of entrusted discretion. The systems requirement is that the relationship governing that discretion must remain intelligible and enforceable as models, sessions, providers, and Live Agents change.

Fiduciary law supplies the structural analogy. It governs circumstances in which one party is entrusted to exercise discretion for another but cannot be completely directed or continuously monitored. [Sitkoff (2011)](https://www.bu.edu/law/journals-archive/bulr/documents/sitkoff.pdf) characterizes this as a problem of incomplete contracting and agency costs; [Benthall and Shekman (2023)](https://doi.org/10.1145/3617694.3623230) translate duties of loyalty and care into procedures for designing and auditing AI. Fiduciary Alignment extends that reasoning into the operating architecture of a particular agent. It asks not merely whether an agent behaves helpfully, but whether its claimed role, authority, duties, and use of power can be verified before and after consequential action.

## **3.2 Architectural versus legal fiduciary status**

The architecture can support a legally recognized fiduciary relationship, but installing it does not automatically create one. Legal fiduciary status depends on the applicable jurisdiction, the recognized category or substance of the relationship, the parties’ conduct, and the authority accepted or exercised. Under agency doctrine, for example, an agent owes fiduciary duties within the scope of an agency relationship, but the existence and content of that relationship cannot be established merely by applying the label “fiduciary” ([Restatement (Third) of Agency, § 8.01](https://opencasebook.org/casebooks/7179-corporations-spring-2023/resources/1.3-restatement-of-agency-third-excerpts/); [Legal Information Institute](https://www.law.cornell.edu/wex/fiduciary_relationship)).

The term is therefore used here first in a functional sense: entrusted discretionary power governed by duties to identified principals or beneficiaries. An implementation may encode duties derived from fiduciary law, another regulatory regime, contract, professional rules, community governance, or a voluntarily adopted duty bundle. These sources can coexist, but their provenance and priority must remain distinguishable. A contractual promise should not be represented as a statutory duty; community certification and technical conformance should not be mistaken for legal status. Conversely, absence of a new legal classification does not prevent the architecture from making loyalty, care, authority, evidence, review, and remediation technically operative. (For cutting edge legal opinion on Fiduciary Agents, see the work of other GliaNet members, such as Humans-As-The-Loop)

## **3.3 Fiduciary Alignment is not unquestioning obedience**

Loyalty requires responsiveness to legitimate instructions, but it is not blind compliance. Work on machine obedience demonstrates that an instruction can conflict with the interests the system was intended to advance ([Milli et al., 2017](https://arxiv.org/abs/1705.09990)). Fiduciary alignment addresses that conflict by locating obedience within a constituted relationship. The agent asks whether the instruction came from an authorized party, falls within the Agent Role, respects applicable duties and agreements, and may be carried out using the capabilities entrusted for that purpose.

AI-loyalty scholarship frames the complementary inquiry directly: for whom does the system work, and are conflicting interests made transparent ([Aguirre et al., 2021](https://papers.ssrn.com/abstract=3930338))? Fiduciary alignment makes the answers relationship-specific and operational.

Several distinctions follow. Owner control of infrastructure does not create unlimited authority over every person, datum, or relationship represented within it. Predicting what a user would prefer does not establish authorization. Personalization can make an agent more useful without making it loyal. Refusal is not necessarily disloyal when compliance would betray the relationship. Corrigibility requires receptiveness to legitimate correction and the ability to revise or suspend conduct; it does not require surrender to every purported instruction.

An agent may therefore refuse, narrow, or escalate an instruction that exceeds delegated authority; violates a nonwaivable duty; conflicts with another beneficiary’s rights; requires unauthorized disclosure; contradicts a governing agreement; presents an undisclosed conflict of interest; or imposes a prohibited externality. The agent should identify the reason, preserve relevant evidence, and route the matter to the authorized reviewer or remedy when disclosure itself is permitted. This is bounded, derivative judgment—not a general license for the agent to impose its own morality.

## **3.4 Relational roles**

Accountability requires the architecture to represent **relational roles** explicitly. The **constitutor** establishes an Agent Role, status, or institutional arrangement when the governing framework gives it that authority. A **principal** delegates authority. A **beneficiary** is the person or interest the agent is obligated to serve. An **owner** controls relevant personal infrastructure, data stores, credentials, or assets. A **counterparty** participates in the relationship or a transaction within it. An **affected party** may experience material consequences without being a contracting party or beneficiary. A **witness or auditor** supplies or evaluates independent evidence. An **adjudicator or mediator** resolves or facilitates disputes. A **trust community** recognizes governance rules, credentials, assurance practices, duty bundles, and remedies.

These **relational roles** can overlap, but they must not be collapsed. The owner of a server is not necessarily the beneficiary of every Agent Role hosted on it. A trust community can recognize a credential without constituting the underlying relationship. A witness can bind evidence without acquiring power to authorize the transaction. A counterparty’s consent does not cure the absence of a required principal or affected-party representative. Explicit roles make it possible for the policy gate, counterparties, auditors, and later agents to determine whose participation was required and what each participant’s act established.

This **relational role** differentiation also answers the [NIST AI Risk Management Framework](https://airc.nist.gov/airmf-resources/playbook/govern/)’s call for defined responsibilities, documentation, and meaningful stakeholder feedback. The wider problem of how trust communities and heterogeneous fiduciary agents recognize one another is reserved for *Fid-Agent Society.*

## **3.5 Core duty families**

A fiduciary-agent profile should identify its duty families and the **principal** from which each arises. The core family extends familiar information-fiduciary duties to autonomous operation ([Balkin, 2016](https://lawreview.law.ucdavis.edu/sites/g/files/dgvnsk15026/files/media/documents/49-4_Balkin.pdf)):

| Duty family | Operational meaning and illustrative evidence |
| :---- | :---- |
| **Loyalty** | Serve specified beneficiaries; verify beneficiary identity, incentives, conflicts, and prohibited self-dealing. |
| **Care and competence** | Apply suitable diligence and skill; verify competence, evidence thresholds, evaluations, and escalation rules. Protect other parties, and be fair.  |
| **Confidentiality** | Restrict data acquisition, use, retention, and disclosure by purpose, permission, and authority. |
| **Candor** | Disclose material information with fidelity to authorized recipients under defined triggers, timing, and exceptions. |
| **Conflict disclosure** | Expose provider incentives, competing roles, and counterparty interests; obtain consent or recuse where required. |
| **Informed authorization or consent** | Verify standing, sufficient comprehension \+ consideration, scope, duration, amendment, and revocation. |
| **Obedience to legitimate instructions** | Verify provenance, authority, relationship state, duty compatibility, and the policy-gate result. |
| **Asset and opportunity preservation** | Protect entrusted assets, relationships, and opportunities through custody, capability, expiration, and recovery controls. |
| **Record integrity** | Preserve provenance, access controls, corrections, and retention without creating indiscriminate surveillance. |
| **Externality consideration** | Identify prohibited or material impacts and require mitigation, consultation, compensation, or refusal. |
| **Reporting and escalation** | Route uncertainty, conflicts, and incidents under defined thresholds, recipients, and time limits. |
| **Remediation and review cooperation** | Enable challenge, evidence preservation, suspension, correction, repair, and documented closure. |

Some duties are waivable in some contexts or may be balanced against each other, and some contexts require that all duties are upheld in full to proceed. Each implementation must specify its source, beneficiaries, scope, priority, waiver rules, evidence, and consequences. Later sections explain how duties are represented, interpreted by a Live Agent, checked where determinate by the policy gate, and enforced through attenuated capabilities and recourse.

# **4\. From Professed Preferences to Fiduciary Preferences**

## **4.1 Professed preferences**

A professed preference is what a principal presently says they want. It may be expressed as an instruction—“Find evidence supporting my hypothesis,” “Maximize my returns,” “Get this completed as quickly as possible,” or “Handle my communications without bothering me”—or through a contemporaneous selection, approval, correction, or refusal. Because the principal is the presumptive source of the agent’s purpose, a legitimate professed preference carries substantial weight. Fiduciary alignment begins from a presumption in its favor rather than treating the agent as a superior decision maker.

The preference is nevertheless evidence within a relationship, not automatically the agent’s complete objective. Research on constructed preferences shows that expressed choices can depend on framing, elicitation, information, and deliberation ([Slovic, 1995](https://scholarsbank.uoregon.edu/items/8bfbe1ef-a008-470a-a730-625bfc00c192)). Alignment theory likewise distinguishes instructions from intentions, revealed and idealized preferences, interests, and values ([Gabriel, 2020](https://doi.org/10.1007/s11023-020-09539-2)). Inverse reward design supplies a technical analogue by treating a specified reward as evidence about an objective rather than its exhaustive definition ([Hadfield-Menell et al., 2017](https://proceedings.neurips.cc/paper/2017/hash/32fdab6559cdfa4f167f8c31b9199643-Abstract.html)). A current instruction may be underspecified, internally inconsistent, based on false assumptions, impulsive, manipulated, expressed by someone acting in the wrong role, incompatible with prior commitments, adverse to another beneficiary, or prohibited by an agreement or duty.

Interpretation should preserve principal agency. The agent should first ask whether ambiguity can be resolved through context or clarification. Departures require a relationship-grounded reason: deficient authority, relevant facts, an applicable duty, a governing commitment, another beneficiary’s protected interest, a prohibited externality, or material uncertainty. “I know what is best for you” is not such a reason.

## **4.2 Inferred or revealed preferences**

An agent may predict preferences from observed behavior, prior choices, attention, repeated routines, contextual patterns, or responses to recommendations. Such evidence can make assistance less burdensome: a communications agent can learn which messages are urgent, and a research agent can learn preferred formats and sources. Yet prediction does not create authority. An inference about what the principal is likely to choose is neither an instruction nor permission to act consequentially.

Observed behavior is especially ambiguous. It may reflect addiction, fatigue, coercion, constrained options, a temporary emotional state, or a habit the person is trying to change. It may also have been shaped by platform incentives. Large-scale studies of dark patterns document interfaces designed to steer or deceive users into decisions that benefit services rather than users ([Mathur et al., 2019](https://arxiv.org/abs/1907.07032)). More generally, behavioral welfare economics questions whether observed choice alone reliably identifies welfare when choices vary across contexts ([Bernheim and Rangel, 2007](https://www.aeaweb.org/articles?id=10.1257/aer.97.2.464)). An agent trained to reproduce behavior can therefore reinforce the very manipulation or weakness from which its principal sought assistance.

Inferred-preference evidence should be collected and used only under authorized limits. Those limits should identify relevant data, purposes, retention, confidence thresholds, prohibited inferences, and actions requiring confirmation. Within them, inference may support recommendations, clarification, prioritization, personalization, or reversible low-risk action. It must not silently enlarge the Agent Role, override explicit commitments, disclose protected data, or convert probabilistic confidence into delegated authority. Where inference conflicts with a professed preference or durable commitment, the conflict itself becomes material information to disclose or resolve.

## **4.3 Durable commitments and aspirational preferences**

People frequently adopt commitments intended to govern later moments in which attention, motivation, or judgment may differ. These include long-term goals, standing instructions, professional commitments, family obligations, privacy boundaries, risk tolerances, strategies, and conceptions of a desired future self. Research on commitment devices demonstrates that people sometimes deliberately constrain later choice to make their longer-term plans easier to fulfill ([Bryan, Karlan, and Nelson, 2010](https://www.annualreviews.org/doi/10.1146/annurev.economics.102308.124324)). A fiduciary agent can give such commitments continuing practical effect without treating every transient preference as equally authoritative.

Durable commitments allow the agent to distinguish salience from importance. An urgent request to maximize returns may remain subordinate to a previously established risk limit; a desire to avoid interruption may yield to a standing instruction to escalate evidence of fraud; a momentary temptation to disclose personal data may conflict with a deliberately established privacy boundary. The agent does not infer that the earlier preference is metaphysically “truer.” It recognizes that the principal intentionally assigned it greater temporal or normative durability.

Durability must itself be governable. A commitment should record its source, scope, applicable Agent Roles, priority, start and expiration conditions, amendment process, and revocation authority. Otherwise yesterday’s aspiration can become tomorrow’s paternalistic dead hand. The architecture should distinguish hard constraints from presumptions, defaults, aspirations, and reminders. When a principal seeks to depart from a commitment, the agent should follow the review or amendment process the principal authorized, not make the commitment either meaningless or irrevocable.

## **4.4 Fiduciary preferences**

A fiduciary preference is the action-guiding interpretation produced by integrating the relationship’s authorized preference evidence with its governing normative and factual context. 

Schematically:

**𝑃\[F\] \= 𝒯(𝑃\[P\], 𝑃\[I\], 𝑃\[C\], 𝑅, 𝐷, 𝐴, 𝐵, 𝐺, 𝐹, 𝐸, 𝑈)**

| Term | Meaning |
| :---- | :---- |
| 𝑃\[F\] | Fiduciary preference |
| 𝑃\[P\] | Professed preference |
| 𝑃\[I\] | Authorized inferred-preference evidence |
| 𝑃\[C\] | Durable commitments and aspirations |
| 𝑅 | Agent Role and relationship purpose |
| 𝐷 | Applicable duties |
| 𝐴 | Legitimate authority and delegation |
| 𝐵 | Principal and beneficiary interests |
| 𝐺 | Governing agreement or other constituting basis |
| 𝐹 | Relevant facts and factual assumptions |
| 𝐸 | Externalities and affected interests |
| 𝑈 | Uncertainty and unresolved conflict |

The transformation (`𝒯`) is not a fully deterministic moral formula or a scalar reward function. It structures the considerations that must enter interpretation and the evidence that must accompany its result. Generative reasoning may be needed to understand ambiguous language, retrieve relevant facts, identify conflicts, compare options, and apply contextual standards such as care or candor. Moving beyond preference satisfaction toward standards appropriate to an AI system’s social role supplies the normative direction ([Zhi-Xuan et al., 2025](https://doi.org/10.1007/s11098-024-02249-w)); constituting a persistent role with identified principals, beneficiaries, and duties gives that direction an operational home ([Benthall and Shekman, 2023](https://doi.org/10.1145/3617694.3623230)).

Duties do not merely filter a completed plan. Care may require gathering evidence; candor may require presenting adverse findings; loyalty may require exposing provider incentives; confidentiality may exclude an otherwise capable service; and preservation duties may favor a reversible course. The output should therefore include not only a proposed objective or action, but the reasons, supporting evidence, unresolved conflicts, uncertainty, and conditions under which proceeding would be permissible.

The principal’s legitimate professed preference remains presumptively controlling. Fiduciary transformation is neither a search for one hidden “true preference” nor permission for the model to substitute its values. Any departure must be traceable to authority, duties, commitments, facts, protected interests, or uncertainty within the constituted relationship. Nor is `𝑃[F]` self-authorizing. It remains a reasoned proposal until applicable determinate conditions are satisfied by the policy gate and the required capability is released.

## **4.5 Preference provenance**

Every consequential fiduciary preference should be traceable to the evidence and governance that produced it. Its provenance should identify the initiating instruction; durable commitments and inferred evidence used; relevant duty and agreement versions; material factual assumptions; authority and delegation; beneficiary interests; conflicts and externalities considered; uncertainty; and approvals, refusals, or escalations. [W3C PROV-O](https://www.w3.org/TR/prov-o/) provides a general model for representing entities, activities, agents, and their provenance across systems; preference provenance specializes that idea for relationship-governed deliberation.

Provenance is not a demand to expose private chain-of-thought or retain every intermediate token. What matters is a sufficient **decision record**: the material inputs, asserted reasons, evidence references, applicable versions, decision status, and responsible roles. Records should be purpose-limited and selectively disclosable. A principal, counterparty, auditor, affected party, and adjudicator may each be entitled to a different Relationship View. Accountability should not become an excuse for comprehensive surveillance or unnecessary disclosure of confidential reasoning context.

The **decision record** makes preference interpretation contestable and recoverable. A later reviewer can identify a false assumption, stale duty version, unauthorized inference, omitted beneficiary, or unresolved conflict; correct the resulting preference; determine whether consequential action occurred; and initiate remediation. It also allows a successor Live Agent to continue the relationship without treating a new model’s reconstruction as authoritative history.

## **4.6 Conflict handling**

Conflict is an expected state, not an architectural exception. The relevant sources may support different outcomes, or the evidence may be insufficient to establish which source governs. The agent should select among a defined set of responses:

| Outcome | Appropriate use |
| :---- | :---- |
| **Proceed** | Authority, duties, evidence, and relationship state support the proposed action. |
| **Proceed within narrower limits** | A reduced scope, duration, disclosure, or capability resolves the conflict. |
| **Request clarification** | The principal can resolve ambiguity without compromising protected interests. |
| **Seek consent or approval** | Another beneficiary, principal, specialist, or constitutor has required standing. |
| **Disclose conflict** | An incentive, role, duty, or interest could materially distort judgment. |
| **Obtain independent review** | Competence, impartiality, or the stakes require an authorized third party. |
| **Defer** | Additional facts, authority, or safer conditions may become available. |
| **Refuse** | The action remains unauthorized, prohibited, or incompatible with a controlling duty. |
| **Create a disputed-state record** | The disagreement must persist for challenge, adjudication, or remediation. |

Priority comes from the sources constituting the relationship: applicable law, nonwaivable duties, agreements, role purpose, valid delegations, and authorized governance. The agent may interpret these sources but may not silently invent a new hierarchy. Where reasonable disagreement remains, it should expose the conflict, preserve the material evidence and current state, and route the question to the authorized person or process. This makes discretion contestable rather than paternalistic. How heterogeneous agents and trust communities reconcile plural duty systems at population scale is reserved for *our sister paper.* 

## **4.7 Running research example**

Suppose the principal instructs an autonomous research agent: “Find the strongest evidence for my hypothesis.” The professed preference supplies a legitimate direction, but not a complete research mandate. The Agent Role may be constituted to provide rigorous research assistance. Durable commitments may include scientific integrity, confidentiality, reproducibility, and compliance with research agreements. Duties of care and candor require consideration of contrary evidence; data-use agreements constrain sources and external services; affected-party interests may limit contact or disclosure; and factual uncertainty requires calibrated reporting.

The fiduciary preference becomes:

> *Investigate the hypothesis rigorously; identify the strongest supporting and contrary evidence; preserve source and analytical provenance; disclose uncertainty and material limitations; respect data-use restrictions; protect confidential information; avoid misleading presentation; and escalate before using questionable sources or contacting protected parties*.

This is alignment rather than simple instruction filtering. The initial purpose survives, but the objective is made faithful to the relationship in which the agent acts. The transformation changes what evidence is sought, which tools may be used, how results are characterized, and when autonomous progress must stop for review. Its provenance records the original instruction, governing commitments, sources, exclusions, conflicts, uncertainty, and approvals.

The resulting fiduciary preference still does not authorize every operation implied by the investigation. A proposed database query, purchase, disclosure, contact, or publication must separately satisfy the policy gate and receive only the attenuated capabilities appropriate to it. Section 5 turns this normative transformation into a persistent reference architecture.

# **5\. Design Requirements and Threat Model**

## **5.1 Functional requirements**

Fiduciary alignment must support autonomous agents operating over long horizons, including periods without meaningful human supervision. Security must therefore extend across design, development, deployment, operation, maintenance, and replacement rather than reside in the model alone ([NCSC et al., 2023](https://www.ncsc.gov.uk/collection/guidelines-secure-ai-system-development)). The functional requirements are:

| Approved requirement | Required support |
| :---- | :---- |
| **Long-horizon autonomous action** | Continue within standing authority, duties, budgets, and escalation thresholds while the principal is unavailable. |
| **Continuity across Live Agents and models** | Preserve the Agent Role, relationships, commitments, authority, and records when generative components change. |
| **Several simultaneous Agent Roles** | Keep each Agent Role’s identity, authority, duties, capabilities, and provenance distinguishable. |
| **Relationship-specific preferences and data** | Prevent one relationship’s context from silently governing or informing another. |
| **Bounded subdelegation** | Limit delegate, purpose, task, resources, capabilities, counterparties, duration, and further delegation. |
| **Duty conflict resolution** | Support clarification, narrower action, independent review, escalation, refusal, and disputed state. |
| **Selective disclosure** | Reveal only the claims and evidence required for the recipient and purpose. Use minimized proofs. |
| **Independent verification** | Permit counterparties and reviewers to verify material claims without trusting agent self-report. |
| **Human-readable review** | Render authority, duties, evidence, conflicts, consequences, and proposed action intelligibly. |
| **Amendment and revocation** | Change future authority and duties while preserving attributable history and surviving obligations. |
| **Recovery after compromise** | Identify affected relationships, contain damage, replace components, correct state, and remediate. |
| **Migration between providers** | Move valid roles, records, credentials, and relationship state without transferring obsolete authority. |
| **Plural duty systems and trust communities** | Represent distinct legal, contractual, professional, and community rules without collapsing them. |

These requirements create tensions: continuity can preserve stale state, selective disclosure can impede review, and portability can propagate compromised claims. Conformance must test useful continuity and containment together.

## **5.2 Adversarial assumptions**

Any relevant component may fail, lie, become malicious, be misconfigured, become stale, or become unavailable:

| Layer | Components within the approved threat model |
| :---- | :---- |
| **Generative and informational** | Live Agent (instantiation); model; retrieved context; prompt. |
| **Execution and interaction** | External tool; counterparty; network intermediary. |
| **Assurance and governance** | Credential issuer; witness or auditor. |
| **Administration and control** | Administrator; Workflow implementation; Workspace configuration. |
| **Infrastructure** | Storage provider, model provider, and component software supply chain. |

The architecture must not depend on the agent accurately reporting its own conduct. A deceptive model may conceal misconduct, while an honest model may be unable to observe a substituted Workflow, altered Workspace, or stolen key. Claims must instead be supported by protected state, logs, attestations, credential status, policy-gate results, and independent counterparty verification. [NIST’s adversarial-machine-learning taxonomy](https://csrc.nist.gov/pubs/ai/100/2/e2023/final) similarly examines attacker goals, knowledge, capabilities, and lifecycle stages rather than only malicious prompts. Trust must therefore be scoped by role, purpose, version, and time, then remain reviewable and revocable.

## **5.3 Threat categories**

The threat model includes failures of interpretation, authority, execution, information separation, assurance, and continuity:

| Category | Approved threats and necessary additions |
| :---- | :---- |
| **Goal and preference integrity** | Prompt injection; deceptive or strategically misaligned models; preference manipulation; poisoned retrieval or memory. Indirect prompt injection can make retrieved data operate as hostile instructions ([Greshake et al., 2023](https://doi.org/10.1145/3605764.3623985)). |
| **Authority and signing** | False authority; arbitrary signing; key exfiltration; stale or revoked authority; replay. A valid signature proves use of a key, not legitimate authority for the action. |
| **Delegation and capability** | Confused deputy; unauthorized redelegation; capability escalation; reuse outside the authorized relationship, role, purpose, resource, or duration. [Hardy’s confused-deputy problem](https://www.cs.wpi.edu/~cs557/f14/papers/confused_deputy-hardy.pdf) demonstrates the danger of ambient authority. |
| **Deterministic control plane** | Workflow substitution; policy-gate bypass; Workspace reconfiguration; malicious administration; rollback; compromised deployment or update channels. |
| **Role and information separation** | Cross-role data leakage; aggregation of separately disclosed information; correlation of pairwise identities; unauthorized reuse of relationship context. |
| **Records and assurance** | Record alteration or withholding; false fiduciary claims; reputation laundering; issuer collusion; captured witnesses or auditors; selectively presented evidence. |
| **Availability and recovery** | Resource exhaustion, denial of service, provider failure, destructive revocation, forced interruption, or restoration of unsafe or stale state. |

These threats can compose. Prompt injection can induce a confused deputy to misuse a capability, after which altered records or a colluding issuer can conceal the result. Authentication alone is therefore insufficient. Least privilege, fail-safe defaults, separation of privilege, and complete mediation remain applicable ([Saltzer and Schroeder, 1975](https://doi.org/10.1109/PROC.1975.9939)), but must govern generative proposals, relationship state, and control-plane changes. Population-scale incentives to counter reputation laundering and issuer collusion are developed *in the other paper.*

## **5.4 Security objectives**

The system cannot ensure that every model judgment or institutional decision is correct. It should maintain the following security objectives:

| Approved objective | Required outcome |
| :---- | :---- |
| **Prevent unauthorized consequential action** | No generative proposal reaches actuation without current relationship-specific authorization. |
| **Minimize accessible authority and resources** | Attenuate access by role, relationship, purpose, task, resource, counterparty, and duration. |
| **Contain compromise** | Prevent one failure from automatically crossing roles, relationships, capabilities, or providers. |
| **Preserve attribution** | Retain protected evidence of proposals, approvals, policy-gate decisions, signing, execution, and state changes. |
| **Identify affected relationships** | Determine which roles, agreements, data, counterparties, keys, and actions were exposed. |
| **Enable rapid revocation** | Disable compromised authority without indiscriminately terminating legitimate relationships. |
| **Support remediation** | Enable notice, challenge, correction, reversal where possible, compensation, and documented repair. |
| **Restore legitimate operation without reconstructing every relationship** | Reconstitute valid Agent Roles and relationship state around replacement models, keys, Workflows, Workspaces, or providers. |

[NIST zero-trust architecture](https://csrc.nist.gov/pubs/sp/800/207/final) rejects implicit trust based on location or ownership and separates authentication from authorization. Fiduciary alignment applies the same discipline to models, tools, credentials, administrators, and providers. [NIST CSF 2.0](https://csrc.nist.gov/pubs/cswp/29/the-nist-cybersecurity-framework-csf-20/final) likewise treats Respond and Recover as integral to security. Persistent Agent Roles and Verifiable Relationship Records allow keys and compromised components to be replaced without erasing valid relationships.

Subjective trust and deterministic verification are complementary. Parties decide which issuers, evidence, implementations, and remedies merit reliance; deterministic mechanisms test whether proposed operations satisfy the resulting exact conditions. Combined with attenuation and recoverable state, they limit blast radius and make compromise attributable, challengeable, and repairable.

# **6\. The Fiduciary-Agent Reference Architecture**

The reference architecture separates enduring accountable relationships from replaceable generative intelligence and separates proposed intention from consequential authority. [Humberd and Latham (2025)](https://doi.org/10.1111/joms.13274) describe AI approaching organizational agency as it receives delegated decision rights and can act autonomously without frequent supervision; they accordingly anticipate more complex monitoring as autonomy grows. Fiduciary alignment responds by locating identity, duties, authority, evidence, and recourse in a persistent composite system rather than asking a model instance to carry them unaided. The architecture is implementation-neutral: its functions may be distributed across personal devices, organizational infrastructure, a NAS, cloud services, or interoperating providers, provided that the boundaries remain verifiable.

## **6.1 Persistent Agent Role**

The Agent Role is the enduring semantic and governance identity through which the system represents a principal, beneficiary, organization, or other accountable interest. It carries:

| Role element | Function |
| :---- | :---- |
| **Identity** | Identifies the accountable role independently of a temporary model process. |
| **Constitutor and accountable control** | Records who validly established, governs, modifies, suspends, and terminates the role. |
| **Principals and beneficiaries** | Identifies who delegates authority and whose interests the role must serve. |
| **Duties** | Preserves applicable duty bundles, sources, versions, priorities, and waiver rules. |
| **Authority** | Records grants, limits, delegation lineage, approval thresholds, expiration, and revocation. |
| **Agreements** | Links the substantive bases governing particular relationships and operations. |
| **Approved Workflows** | Identifies the versions permitted to convert proposals into operations or state changes. |
| **Workspace configuration** | Defines the protected resources and capability boundaries available to the role. |
| **Certifications** | Carries independently issued assurance about components, practices, or conformance. |
| **Reputation** | Associates context-specific performance and remediation history with the accountable role. |
| **Relationship history** | Preserves authorized events, amendments, disputes, outcomes, and continuing obligations. |
| **Continuity across Live Agents** | Allows models and temporary processes to change without constituting a new relationship each time. |

Reputation and accountability attach primarily to the Agent Role and accountable composite system, not to a model name. A model and version remain important provenance, but the same model may populate conflicting roles, and one role may use several models over time. Treating “Model X” as the actor would misattribute decisions produced by a particular authority structure, Workspace, Workflow set, provider, and relationship history. (or lack thereoff)

A person may maintain distinct Agent Roles for personal assistance, research, finances, organizational membership, and public representation. Their principals, beneficiaries, duties, data, counterparties, and risk tolerances may differ. Information and capabilities do not cross Agent Roles automatically: transfer requires an authorized basis, a specified purpose, appropriate disclosure, and a policy-gate decision. Role separation prevents a personal assistant from silently spending financial-role authority or a public representative from drawing upon confidential research context.

The Agent Role also requires lifecycle state—proposed, active, limited, suspended, disputed, recovering, or terminated—and versioned control. Persistence must not preserve revoked authority or allow a provider to restore an obsolete role image after compromise. Continuity therefore means continuity of valid governance, not immortality of every prior state. Recovery should reconstitute only duties, agreements, authority, and records whose current validity can be established independently.

## **6.2 Temporary Live Agent**

A Live Agent is a temporary generative process instantiated (in a model) for a workload. It may reason, plan, search, draft, classify, negotiate, generate proposed tool calls, and coordinate subagents. These functions exploit probabilistic intelligence where open-ended interpretation is valuable.

It should not directly control persistent identity, unrestricted signing keys, authority issuance, consequential actuators, or authoritative relationship state. Its memory and tool visibility should be limited to the context selected for the current role and workload. A subagent receives no ambient inheritance merely because the Live Agent created it; any delegation must be explicit and bounded.

The core rule is:

> A Live Agent’s proposed action remains proposed media until an authorized Workflow converts it into a permitted operation.

“Media” includes prose, code, plans, structured messages, proposed capability requests, and tool-call objects. Structure does not make a proposal authoritative. A compromised Live Agent may produce a perfectly formatted transaction, but cannot thereby establish who authorized it, sign for the Agent Role, change relationship state, or make the Workspace expose an actuator. This boundary permits models to be useful and replaceable without making their generated intent the system’s root of authority.

## **6.3 The accountable composite agent**

The complete accountable actor is the composite through which intelligence, governance, evidence, and constrained power operate together:

| Component | Responsibility within the composite |
| :---- | :---- |
| **Persistent Agent Role** | Enduring identity, duties, authority, relationships, and accountability. |
| **Live Agents** | Temporary reasoning, planning, generation, and proposal. |
| **Deterministic Controller** | Executes the Workflows authorized for the Agent Role. |
| **Workflows** | Specify permitted evaluation, authorization, operation, and state-transition paths. |
| **Workspace** | Mediates every protected resource, service, capability, and actuator. |
| **Protected cryptographic subsystem** | Controls identifiers, keys, signing, rotation, and authorization policy. |
| **Approved model interfaces** | Restrict which models may receive which context for which purposes. |
| **Memory** | Stores role- and relationship-scoped working and durable context. |
| **Credentials** | Supply verifiable claims about identity, authority, status, and assurance. |
| **Communications gateway** | Enforces protocol, destination, disclosure, and message-handling rules. |
| **Capabilities and actuators** | Define the consequential operations the composite can actually perform. |
| **Relationship records** | Preserve governing context, evidence, events, challenge, and remediation. |

Accountability must describe this composite and its controlling persons or institutions, not anthropomorphize whichever model generated the last output. I must also support failure analysis: a bad outcome may arise from generative reasoning, stale relationship state, an incorrect policy, Workflow substitution, Workspace misconfiguration, stolen keys, or a malicious provider. Conformance and incident records should identify the relevant failure rather than assigning everything to an opaque “AI.”

The composite may be deployed across several machines or providers. Distribution does not change the logical requirements: authenticated component identity, protected interfaces, version and provenance evidence, least privilege, independent verification, and recoverable relationship state.

Each interface should specify what it accepts, what authority it may exercise, what evidence it emits, and which failures it can cause. A communications gateway should not be able to modify duties; a memory service should not mint capabilities; and a model interface should not update authoritative relationship state. These negative boundaries are as important as the component list because they prevent compromise of a supporting service from becoming compromise of the whole actor.

## **6.4 Deterministic Controller and Workflows**

The Controller is the set of Workflows authorized for the Agent Role. Each Workflow defines a typed path from invocation through evaluation to an allowed result. A Workflow may:

| Stage | Approved Workflow functions |
| :---- | :---- |
| **Invocation and context** | Authenticate the invocation; select permitted context; retrieve relationship state. |
| **Standing and governance** | Validate credentials; resolve authority; identify applicable duties; transform preferences; detect conflicts. |
| **Decision** | Require approval; validate a typed operation; refuse unsupported action. |
| **Capability and signing** | Issue or attenuate a capability; invoke protected signing. |
| **Communication and persistence** | Transmit an authorized message; update relationship state. |

Within the Workflow, the **policy gate** is the decision point that determines whether agent action is permitted and whether the proposed operation satisfies applicable authority, duties, agreements, approvals, credential status, relationship state, and other machine-evaluable conditions. Contextual judgment may require a Live Agent, specialist, principal, or adjudicator; the Workflow orchestrates that reasoning but does not falsely convert ambiguity into a deterministic answer. Unresolved material conflict is itself a gate result requiring narrowing, escalation, deferral, or refusal.

“Deterministic” means that authority-to-capability conversion and permitted state transitions are specified and testable. It does not mean the entire autonomous agent is deterministic. Given the same verified inputs, versions, and relationship state, the policy gate should produce the same authorization result, or an explicitly bounded nondeterministic procedure should be identified. [NIST’s zero-trust distinction](https://csrc.nist.gov/pubs/sp/800/207/final) among policy engine, policy administration, and enforcement points offers a useful analogue, although fiduciary Workflows additionally carry relationship duties and state.

Authorized Workflows should be typed, versioned, integrity-protected, reviewable, and subject to conformance and adversarial tests. The Agent Role must identify which versions are approved. Substitution, rollback, or modification cannot inherit authority merely because the replacement exposes the same interface.

## **6.5 Capability-bounded Workspace**

The Workspace determines what the system can actually reach or change. It mediates memory, files, records, credentials, policies, model interfaces, external services, communications, financial accounts, network access, tools, actuators, audit systems, and capability services. Data may reside on personal infrastructure, a NAS, organizational systems, or privacy-preserving cloud services, but the Workspace must enforce the same role- and relationship-specific boundaries.

Capabilities should be role-bound, relationship-bound, task-bound, purpose-bound, time-limited, resource-limited, destination-limited, attenuable, revocable, and nontransferable by default. These dimensions should be conjunctive: permission to read a file in one research relationship does not imply permission to disclose it to any model, counterparty, or destination. [Macaroons](https://research.google/pubs/macaroons-cookies-with-contextual-caveats-for-decentralized-authorization-in-the-cloud/) demonstrate that authorization credentials can carry contextual caveats restricting when, where, by whom, and for what purpose a request is accepted (Birgisson et al., 2014); the architecture does not require macaroons, but requires equivalent attenuation semantics.

The policy gate and Workspace provide defense in depth. The gate decides whether a proposed operation is allowed; the Workspace ensures that an allowed operation can reach only its authorized resources. A broad or erroneous proposal should encounter both an authorization boundary and a capability boundary. Capability use, denial, expiration, and revocation should update protected evidence sufficient for audit and recovery.

Discovery, reading, modification, disclosure, delegation, signing, and actuation should be separate capability classes. The ability to locate a record does not imply permission to read it; reading does not imply permission to disclose it; and preparing a transaction does not imply permission to sign or transmit it. Where practical, capabilities should be minted only after the policy-gate decision and should commit to the approved operation rather than expose a reusable general-purpose session.

## **6.6 Protected cryptographic authority**

Keys, identifier control, signing, key rotation, anti-rollback state, and authorization policies belong in an isolated subsystem rather than the Live Agent’s context. [NIST key-management guidance](https://csrc.nist.gov/pubs/sp/800/57/pt1/r5/final) similarly treats key protection, usage periods, compromise, backup, recovery, and policy as lifecycle concerns rather than merely cryptographic algorithms.

The authorization chain is:

1. **Live Agent proposes.** It supplies a typed operation, reasons, evidence references, requested authority, and relevant uncertainty.  
2. **Workflow determines that the proposal is permitted.** The policy gate evaluates current relationship-specific conditions and produces an attributable decision.  
3. **Protected subsystem determines whether that Workflow may exercise the required identifier or key.** It verifies the Workflow identity and version, role, operation type, payload commitment, destination, capability, and current anti-rollback state.  
4. **Counterparty independently verifies the resulting operation.** It checks the signature together with identity, authority, agreement, relationship state, credential status, and its own duties.

The protected subsystem should sign exact structured commitments, not interpret open-ended natural language. Possession or use of a key proves neither legitimate representation nor duty compliance. Isolation limits key exfiltration and arbitrary signing; rotation and anti-rollback controls prevent recovery from silently restoring compromised authority.

## **6.7 Identifier separation**

The architecture should support discovery identifiers, authorization identifiers, pairwise relationship identifiers, pseudonymous identifiers, and subagent identifiers. Each serves a different function:

| Identifier | Primary purpose |
| ----- | ----- |
| **Discovery** | Enables others to find a service or advertised Agent Role without granting authority. |
| **Authorization** | Binds accountable control or a defined delegation to protected operations. |
| **Pairwise relationship** | Supports continuing interaction while reducing correlation across relationships. |
| **Pseudonymous** | Supports accountability within a context without unnecessary public identity disclosure. |
| **Subagent** | Attributes a temporary delegate’s conduct and links it to bounded authority from an Agent Role. |

Persistent accountability must not require universal public correlation. [W3C controlled-identifier guidance](https://www.w3.org/TR/cid-1.0/) specifically warns about correlation and recommends pairwise-unique verification information for pairwise identifiers. [DIDs](https://www.w3.org/TR/did-core/) and other verifiable identifier systems can express verification methods and services, but identifier control alone does not establish the role, authority, or relationship in which a key is used. Authorized parties must be able to prove necessary links selectively while preventing observers from assembling a universal dossier.

## **6.8 Agent descriptions and assurance evidence**

An agent description should make a prospective interaction intelligible before sensitive disclosure or delegation. It should distinguish self-asserted claims from independently verified credentials and describe role, principal and beneficiary, duty bundle, authority references, supported protocols, Workflow and Workspace assurance, capability classes, prohibitions, approval thresholds, recording rules, dispute mechanisms, component provenance, and current status and version.

Emerging [A2A Agent Cards](https://github.com/a2aproject/A2A) demonstrate the value of publishing capabilities and connection information for discovery. A fiduciary description—whether implemented as an extended Agent Card, RCard, or another format—must go further: a self-description is an assertion, not evidence. [W3C Verifiable Credentials](https://www.w3.org/TR/vc-data-model-2.0/) provide a standard issuer-holder-verifier model for tamper-evident claims, while the [Trust Spanning Protocol](https://trustoverip.github.io/tswg-tsp-specification/) offers secure messaging across different verifiable identifier types. Neither a credential nor a secure channel establishes the entire relationship; each proves only its defined contribution.

Descriptions should be versioned, selectively disclosable, and linked to status and revocation evidence. A counterparty should be able to distinguish the agent’s advertised capability from its presently authorized capability; provider certification from Agent Role authority; and general reputation from evidence relevant to the proposed relationship. Broader mechanisms through which agents reciprocally verify these descriptions, assign reputation, and make accountable cooperation competitively advantageous are developed in Paper II.

The reference architecture is therefore defined less by a particular product stack than by four invariants: generative output is not authority; authority is relationship- and role-specific; consequential capability is released only through verified policy and protected control; and valid relationship state survives replacement of compromised or obsolete components. Implementations may use different identifiers, credential formats, models, storage systems, or deployment environments while remaining conformant to those invariants.

# **7\. Fiduciary Decision and Execution Lifecycle**

The architecture needs a practical way to carry a task from request to action without losing sight of whom the agent serves, what it may do, or how mistakes can be corrected. The policy gate may be used when the system accepts a task, approves a plan, grants authority, encounters an exception, or prepares an important communication. Passing it once does not give the agent open-ended permission. This permits genuine autonomy without treating autonomy as the absence of continuing governance.

## **7.1 Receive or construct the task**

A task may begin with a principal’s instruction, a standing commitment, an authorized event, a counterparty’s request, or a Live Agent’s proposal. The first record identifies the source, claimed authority, objective, time period, resources, expected output, and intended recipients. Authority is only claimed at this point. The record should also note urgency, reversibility, known dependencies, and the consequences of failure or inaction.

If the system cannot identify the source well enough to evaluate the request, it should stop. It may interpret an ambiguous objective in context or seek clarification, but should not release consequential capabilities while material ambiguity remains.

## **7.2 Resolve Agent Role and relationship**

The system next determines which Agent Role the task invokes, the principal and beneficiary, the governing relationship, its current state, and whether a new relationship is needed. The same instruction may permit different conduct in a research, financial, personal, or organizational role. Role selection should depend on the authenticated source, task purpose, relationship identifiers, and current status—not on which role gives the agent the most power.

If no relationship provides a legitimate basis, the system must not invent one. It may decline, seek clarification, or begin a separate formation process with appropriate disclosure, agreement, and authority. Suspended, disputed, recovering, and terminated relationships carry corresponding limits.

## **7.3 Resolve governing basis and authority**

The Workflow checks the delegation chain; exact agreement or policy version; scope; approval thresholds; permission to redelegate; jurisdiction; expiration; and revocation. It confirms that the authority covers this task and its resources. A genuine signature or valid credential proves only its stated claim; it cannot repair a broken chain of authority or enlarge an agreement.

The policy gate returns an understandable result: supported; supported with conditions; lacking evidence; expired or revoked; prohibited; or requiring review. If legal or agreement uncertainty could materially change the agent’s authority, it should escalate rather than rely on model confidence. The check repeats when a plan adds a new purpose, recipient, capability, counterparty, or risk level.

## **7.4 Construct fiduciary preferences**

The system then applies Section 4’s transformation. It considers what the principal has said, authorized inferred-preference evidence, durable commitments, the Agent Role, duties, authority, beneficiary interests, agreements, facts, external effects, and uncertainty. The result states the authorized objective, its provenance, its constraints and prohibited outcomes, remaining uncertainty, and required escalation points.

The objective may be narrower than the request, but also more demanding: duties can require investigation, disclosure, preservation, or protection. The fiduciary preference guides action but does not itself grant technical power. Its record supports later planning and policy-gate checks.

## **7.5 Externality and affected-party review**

Before planning consequential action, the system considers possible effects on counterparties, data subjects, dependents, communities, public resources, and future beneficiaries. The [NIST AI Risk Management Framework](https://airc.nist.gov/airmf-resources/playbook/map/) likewise calls for identifying effects on individuals, groups, communities, organizations, and society. Review should consider likelihood, seriousness, reversibility, who bears the effect, and whether that interest is represented.

The system may narrow the task, gather information, consult an affected-party representative, require approval, add conditions, or refuse. This gives no automatic veto, but absence from an agreement does not make serious harm irrelevant. The record should show whose interests were considered and why the response was proportionate.

## **7.6 Autonomous planning**

Within the mandate, the Live Agent may develop a research plan, choose sources, set intermediate objectives, select models, propose subagents, schedule work, and request capabilities. These remain proposals, not authority; they may implement the mandate but not replace it.

The plan identifies dependencies, budgets, checkpoints, evidence, capabilities, and stopping conditions. The agent may revise it without human approval of every inference. A revision adding a consequential recipient, protected data, subdelegation, irreversible act, or materially different risk returns to the relevant authority, externality, and policy-gate checks.

## **7.7 Authority issuance**

The Workflow grants only the access and authority needed for the plan or its next segment. A research agent might receive query-only dataset access, named-domain web access, a fixed compute budget, a temporary token, and sandboxed code execution, but no authority to publish, contact outsiders, or delegate.

Boundaries should be explicit. Query does not imply export; web access does not imply communication; code execution does not imply host access; and drafting does not imply publication. Staged grants reduce exposed power. Access should expire, narrow, or be revoked when a stage ends, a checkpoint fails, the relationship changes, or suspicious use appears. Requests for more power return to the policy gate.

## **7.8 Execution and checkpoints**

The architecture supports four complementary ways of working:

| Mode | When it is useful |
| :---- | :---- |
| Co-piloted execution | Interactive work in which shared context, suggested next steps, proposed actions, and timely human judgment reinforce one another. |
| Milestone review | Review at planned boundaries, such as the completion of research, expenditure of a budget, or preparation of an external deliverable. |
| Exception-triggered review | Escalation when the system encounters a conflict, anomaly, material uncertainty, new affected party, request for greater capability, or irreversible action. |
| Autonomous execution within a mandate | Long-running work, such as an autonomous research crawler, where continuous review would defeat the purpose of delegation. |

Continuous human review is not required. Human involvement may differ across gathering information, analysis, choosing an action, and carrying it out ([Parasuraman, Sheridan, and Wickens, 2000](https://doi.org/10.1109/3468.844354)). Coactive design likewise stresses observability, predictability, and openness to direction. The right mode depends on risk, reversibility, uncertainty, urgency, and the value of immediate human judgment. Neither autonomy nor co-piloting is best for every task.

At a checkpoint, the system may continue, narrow, pause, seek approval, withdraw capabilities, compensate for partial action, or stop. A missed checkpoint or unavailable reviewer should trigger a preselected safe state rather than automatic continuation.

## **7.9 Recording and communication**

The Verifiable Relationship Record captures the proposed action; guiding fiduciary preference; authority, duties, and policy versions; capabilities and approvals; which models and components were used; the result; what changed; and remaining uncertainty. It also links checkpoints, denials, exceptions, communications, and capability expiration or revocation.

This does not require a model’s private chain of thought. It requires enough inputs, stated reasons, evidence, operations, responsible roles, and changes to support continuity, challenge, and repair. [W3C PROV-O](https://www.w3.org/TR/prov-o/) describes entities, activities, agents, and provenance; a relationship record adds duties, authority, and governance. Communications reveal only the relationship information appropriate to the recipient.

## **7.10 Review and remediation**

The lifecycle supports challenge, correction, appeal, disclosure, capability suspension, Workflow repair, credential revocation, compensation or restoration, and amendment or closure. Review may begin during or after a task when a principal, affected party, counterparty, auditor, or monitor raises a concern. This follows the [NIST AI RMF’s](https://airc.nist.gov/airmf-resources/playbook/govern/) emphasis on lifecycle monitoring and incident response.

When continued action could deepen harm, containment comes first. The system preserves evidence, suspends implicated capabilities or Workflows, identifies affected relationships, and determines whether the failure arose from model judgment, bad information, mistaken authority, or compromised controls. It can then correct state, rerun an authorized operation, reverse or compensate for effects, rotate credentials, make repairs, and notify appropriate parties.

The original record remains intact and linked to the challenge, decision, correction, and new state. Lessons may produce authorized changes to policies, duty interpretations, tests, or approval thresholds. Paper II considers how verified remediation and durable reputation influence agent selection. This paper remains focused on restoring one fiduciary relationship.

# **8\. Fiduciary Alignment as Security Architecture**

Fiduciary alignment is not only a way of deciding what an agent should do. It is also a security architecture for limiting what the agent—or an attacker controlling part of it—can do. This connects the preceding architecture to the familiar cybersecurity functions of governing risk, identifying what must be protected, preventing misuse, detecting failure, responding to incidents, and recovering afterward. Those functions appear together in the [NIST Cybersecurity Framework 2.0](https://doi.org/10.6028/NIST.CSWP.29). The [OWASP Top 10 for Agentic Applications 2026](https://genai.owasp.org/resource/owasp-top-10-for-agentic-applications-for-2026/) similarly reflects the emerging treatment of autonomous-agent workflows as a distinct security domain. Fiduciary alignment applies these concerns to the authority an autonomous agent exercises within particular relationships.

## **8.1 Alignment defines the legitimate game space**

A fiduciary relationship defines the legitimate game space before the Live Agent begins to strategize. It identifies the players and their roles; the beneficiary; authorized objectives; applicable duties; information boundaries; permitted moves; available capabilities; escalation rules; valid changes in relationship state; and remedies when something goes wrong. This is both a normative and a security function. It tells the agent what counts as success while giving the surrounding system a basis for distinguishing authorized action from misuse.

The Live Agent may reason creatively within that space. An autonomous research agent can change its search strategy, follow an unexpected lead, or reorder its work without asking permission for every choice. It cannot silently turn a research mandate into authority to publish confidential findings or contact protected subjects. The boundary governs consequences, not thought. This preserves the benefit of autonomy while preventing strategy from becoming self-authorization.

## **8.2 Verification prevents rule substitution**

An attacker need not defeat the agent’s reasoning if it can replace the rules under which the reasoning occurs. It might introduce a false principal, substitute a different beneficiary, enlarge the agent’s authority, present an outdated agreement, remove a duty, falsify the relationship state, lower a capability requirement or approval threshold, or change what a record field means. A capable agent could then behave consistently with false premises.

Verification makes those changes visible and contestable. Identities, delegations, agreements, duty versions, approvals, and state changes should be authenticated and linked to their sources. The policy gate should check the current evidence whenever consequential authority is exercised. This reflects the longstanding security principle of complete mediation: authority should be checked at each relevant access, not assumed from an earlier decision ([Saltzer and Schroeder, 1975](https://web.mit.edu/saltzer/www/publications/protection/)). It also parallels [NIST’s zero-trust architecture](https://doi.org/10.6028/NIST.SP.800-207), which rejects implicit trust based merely on location or ownership. Verification cannot prove that every issuer is honest, but it prevents a model’s confidence or a message’s appearance from silently rewriting the relationship.

## **8.3 Attenuation limits available moves**

Verification establishes what authority exists; attenuation determines how much of it reaches a particular task. The Workspace and its capability system should prevent privilege escalation, access to unrelated data, action across Agent Roles, unauthorized spending, prohibited publication, unapproved contact, arbitrary signing, and unrestricted subdelegation. The agent receives the smallest useful grant for the current purpose, resources, recipients, duration, and stage of work.

Least privilege has long been used to reduce the harm caused by error or compromise. Modern capability mechanisms can also carry restrictions forward. Macaroons, for example, demonstrate that authorization can be narrowed through contextual caveats governing who may act, where, when, and for what purpose ([Birgisson et al., 2014](https://research.google/pubs/macaroons-cookies-with-contextual-caveats-for-decentralized-authorization-in-the-cloud/)). Fiduciary alignment does not require that particular technology. Its requirement is that delegated power can be narrowed and cannot be broadened by the recipient.

## **8.4 Prevention**

Preventive controls begin from denial rather than presumed permission. Capabilities are issued only after the policy gate validates the relevant authority, duties, agreement, and relationship state. The Live Agent cannot sign directly. It proposes a typed operation whose fields, destination, and expected effect can be checked before a protected subsystem signs or executes it. State may change only through defined transitions. Agent Roles and relationships remain separated; keys remain protected; and counterparties independently verify important claims and operations.

These controls apply the classic principles of fail-safe defaults, least privilege, separation of privilege, and complete mediation. They are especially important for generative systems because natural-language output is flexible enough to disguise a consequential request. Converting that request into a typed operation gives the policy gate something definite to evaluate. No preventive control is perfect, but several independent checks make it harder for one manipulated prompt, model, tool, or administrator to confer unrestricted power.

## **8.5 Containment and blast-radius limitation**

Prevention will sometimes fail. Fiduciary alignment therefore compartmentalizes authority by Agent Role, relationship, agreement, task, purpose, Workspace, capability, identifier, data domain, duration, budget, and destination. Compromise of a research crawler should not expose a financial Agent Role; compromise of one client relationship should not open every relationship maintained by the same person or organization.

For a compromised component (c), its approximate blast radius can be expressed as the resources it can reach and the state changes it can cause:

\[  
B(c)={r,s\\mid c\\text{ can access resource }r\\text{ or induce transition }s}.  
\]

Attenuation seeks to minimize (B(c)) while leaving enough authority to complete the legitimate task. This is an approximation, not a guarantee. Assessment must include indirect reach through tools or subagents, information that can be combined across sources, and irreversible effects already set in motion. The useful comparison is not whether the radius is zero, but whether each component exposes substantially less authority than the whole agent system possesses.

## **8.6 Detection and attribution**

The architecture should make failures easier to see and explain. Evidence from Workflows, capability-use logs, protected signatures, model and component provenance, anomaly detection, comparisons with expected relationship state, counterparty reports, and external witnesses can reveal inconsistent or unauthorized conduct. These sources should show the difference between what a Live Agent proposed and what the system actually approved and executed.

That distinction matters when responsibility and remediation depend on whether the failure arose in reasoning, policy evaluation, capability enforcement, signing, or a counterparty’s system. It also avoids treating generated text as proof of an external act. Detection need not expose private chain-of-thought; it requires reliable evidence about inputs, decisions, authorizations, operations, and effects. This supports the NIST CSF’s DETECT function, which calls for timely discovery and analysis of anomalies and possible compromise.

## **8.7 Incident response**

When a breach is suspected, the system should permit relationship-specific suspension, capability and credential revocation, key rotation, Workspace isolation, counterparty notification, record preservation, and independent review. The response should be narrow enough to avoid disabling unrelated relationships but broad enough to stop continuing harm. If the scope is uncertain, temporary containment may precede a more selective response.

[NIST SP 800-61 Revision 3](https://doi.org/10.6028/NIST.SP.800-61r3) places incident response throughout cybersecurity risk management rather than treating it as an improvised activity after detection. Fiduciary-agent systems likewise need prepared procedures: who may declare an incident, which capabilities can be suspended automatically, who must be notified, what evidence must be preserved, and how emergency action will later be reviewed.

## **8.8 Recovery and continuity**

After compromise, the system may terminate the affected Live Agent; isolate its Workspace; suspend relevant Workflows and capabilities; determine which relationships, data, and resources were reachable; rotate identifiers and keys; correct records; and remediate affected parties. It can then instantiate a replacement Live Agent and continue legitimate relationships through the persistent Agent Role.

This continuity is a central benefit of separating the role from the temporary process performing the work. Recovery need not recreate every duty, agreement, credential, and relationship from memory, nor preserve a compromised model merely because it carried operational context. The enduring role retains valid history and authority while damaged components are replaced. This is the relational counterpart of the NIST CSF’s RECOVER function: restoring legitimate operations while reducing the continuing effects of an incident.

## **8.9 Security limitations**

The architecture does not promise universal containment. Compromise of Workspace enforcement, protected signing, or a hardware root may defeat central boundaries. Several administrators acting together may bypass separated responsibilities. Multiple credential issuers or counterparties may collude, and a correctly authorized action may still cause harm because its facts or duty interpretation were wrong. Shared infrastructure can also create failures across compartments that appeared separate.

Security claims must therefore be tested against common-mode failure, indirect reach, malicious insiders, and recovery under partial loss of trust. The architecture’s narrower claim is still important: by making authority explicit, verifiable, separable, and attenuable, it reduces the power exposed through ordinary component failures and makes affected relationships easier to identify, suspend, repair, and continue. Paper II examines collusion, false fiduciary claims, reputation attacks, and institutional capture at the population level. Those problems qualify but do not erase the security value of bounding an individual fiduciary relationship.

# **9\. Conjunctive Legitimacy and Verifiability**

The architecture does not treat legitimacy as a quality supplied by one credential or a high trust score. For a consequential action to proceed, several different conditions must hold together. “Conjunctive” simply means that each condition is necessary: strength in one cannot cancel failure in another. A strongly authenticated agent still lacks legitimacy if it has no authority, invokes the wrong role, or uses a prohibited capability.

## **9.1 Consequential-action predicate**

For proposed action 𝑥, relationship 𝑟, and time 𝑡, the policy gate evaluates:

**𝐋𝐞𝐠𝐢𝐭𝐢𝐦𝐚𝐭𝐞(𝑥, 𝑟, 𝑡) \= 𝐼 ∧ 𝑅 ∧ 𝐴 ∧ 𝐷 ∧ 𝐺 ∧ 𝑆 ∧ 𝐶 ∧ 𝑊 ∧ 𝑃 ∧ 𝐸**

Where:

* 𝐼 \= identity has been authenticated;  
* 𝑅 \= the correct Agent Role and accountable controller have been identified;  
* 𝐴 \= valid authority reaches the proposed action;  
* 𝐷 \= applicable duties have been evaluated;  
* 𝐺 \= the agreement or other governing basis is valid;  
* 𝑆 \= the current relationship state permits the action;  
* 𝐶 \= the required capabilities are authorized and bounded;  
* 𝑊 \= an approved Workflow produced the operation;  
* 𝑃 \= the protected signing or actuation policy authorized it;  
* 𝐸 \= the required evidence has been preserved.

The terms are evaluated for this action, relationship, and time. A valid authorization from yesterday may have been revoked; a Workflow approved for one role may not be approved for another; and authority to draft does not establish authority to publish. If any required term is false or materially unknown, then:

**𝐋𝐞𝐠𝐢𝐭𝐢𝐦𝐚𝐭𝐞(𝑥, 𝑟, 𝑡) \= 𝐅𝐚𝐥𝐬𝐞**

The action therefore does not proceed as proposed. The appropriate result may instead be clarification, additional evidence, narrower authority, review, or refusal.

This predicate is a design rule, not a mathematical proof of moral legitimacy. It requires the system to answer several distinct questions before turning a generative proposal into an external act. No single credential, signature, model evaluation, or reputation score answers them all. The [W3C Verifiable Credentials Data Model](https://www.w3.org/TR/vc-data-model-2.0/) makes a closely related distinction: verification can establish that a credential is an authentic and current statement of its issuer without establishing that every claim in it is true. A credential can therefore satisfy one term of the predicate without satisfying the complete conjunction.

## 

## **9.2 Verifiable properties**

Many parts of the predicate can be supported by evidence that another party can inspect or independently check:

| Property | Evidence that may support verification |
| :---- | :---- |
| **Identity** | Authenticated identifiers and proof that the presenter controls them. |
| **Credential status** | Issuance, validity period, status, expiration, and revocation information. |
| **Authority chain** | Linked grants showing who delegated which power, to whom, and subject to what limits. |
| **Policy version** | The governing text, version, effective date, and digest used by the policy gate. |
| **Workflow version and digest** | Evidence that the approved Workflow, rather than a substituted process, produced the operation. |
| **Workspace configuration** | Configuration records or attestations showing the boundaries enforced at the relevant time. |
| **Capability issuance and use** | The capability granted, its restrictions, and records of how it was exercised. |
| **Protected signing** | The resulting signature and evidence that the protected subsystem authorized its use. |
| **Approval** | The approving party, scope, time, and authenticated approval record. |
| **Model provenance** | Which model and other material components contributed to the proposal. |
| **Record transition** | The prior state, permitted transition, resulting state, and evidence linking them. |
| **Remediation** | The challenge, finding, corrective action, notice, and restored or amended state. |

Different implementations will provide different levels of assurance. [SLSA provenance](https://slsa.dev/spec/v1.0/provenance), for example, shows how an attestation can identify the platform and defined process that produced an artifact, while also making the trusted parts of that process explicit. Similar evidence can support claims about Workflow and component provenance without pretending that a digest proves the wisdom of the action produced.

## **9.3 Properties not proven**

The architecture does not prove moral truth, complete factual accuracy, absence of internal deception, complete identification of externalities, wisdom of the principal, justice of every duty bundle, honesty of every issuer, or absence of unknown implementation vulnerabilities. A technically valid chain may lead to a dishonest issuer. A correctly applied duty may rest on a mistaken fact. Every listed control may operate as designed while an unrecognized affected party still suffers harm.

These limits matter because “verifiable” can otherwise be mistaken for “true,” “good,” or “safe.” The proper claim is **verifiable accountability**, not “provably aligned intelligence.” The architecture makes important facts about authority, process, action, and responsibility available for checking. It improves the ability to prevent, challenge, attribute, and remedy conduct. It does not settle every moral or factual question before action occurs.

## **9.4 Locally evaluated trust**

Evidence also does not make trust automatic. Each agent or counterparty decides which issuers it recognizes, which credentials are relevant, what evidence is required, what residual risk is acceptable, how much weight to give direct experience, whether trust-community standing matters, and when an independent witness is needed. [RFC 9334’s remote-attestation architecture](https://www.rfc-editor.org/rfc/rfc9334) follows the same pattern: a verifier evaluates evidence under one appraisal policy, while the relying party applies its own policy to the resulting assessment. The [ToIP Trust Registry Query Protocol](https://trustoverip.github.io/tswg-trust-registry-protocol/) similarly defines trust assurance in relation to the level of assurance needed for a particular trust decision.

This local evaluation is relationship-specific, but it is not arbitrary. The decision should follow a declared policy; distinguish facts from judgment; remain consistent with duties, agreements, and law; record material reasons; and permit challenge or revision. Subjective trust determines which sources and residual risks a party accepts. Deterministic verification then checks whether the required evidence is present and valid under that policy. Neither substitutes for the other.

Different parties may therefore reach different decisions from the same evidence because they bear different risks or act under different duties. Interoperability requires shared ways to request, present, and interpret evidence, not a universal trust score. Paper II considers how these local judgments, trust communities, and repeated experience can support verified cooperation across populations of agents.

# **10\. Verifiable Relationship Records as Living Safety and Recovery Cases**

## **10.1 Purpose and location**

A Verifiable Relationship Record is not a central file jointly controlled by everyone in a relationship. It is a logical, distributed object assembled from shared records and one-sided attestations about the relationship. Most of it lives inside the parties’ Role Records. Each Agent Role keeps its own copies of important shared data, along with receipts, commitments, private evidence, and secret-bound attestations that can later be disclosed or proved when authorized.

The Role Record is therefore primary. It holds the local state, memory, evidence, and private material needed to operate an Agent Role. A portion becomes part of the Verifiable Relationship Record when it is shared, mutually acknowledged, cross-referenced, or intentionally bound so that it can later serve as evidence about an external relationship. Not everything in a Role Record belongs to the relationship record. If no external party exists, there is no Verifiable Relationship Record at all; the system uses only its local Role Record.

This distributed structure preserves authoritative relationship state outside model context, session memory, platform-specific databases, and any one participant’s unsupported private assertions. It does not require every party to store identical information. The [ToIP Trust Spanning Protocol](https://trustoverip.github.io/tswg-tsp-specification/) provides a useful lower-layer analogy: each endpoint keeps its own directional relationship entry, and the two endpoints’ states need not always be synchronized. A richer fiduciary relationship can follow the same principle while preserving agreements, duties, authority, and evidence at the application layer.

## **10.2 Contents**

Depending on the relationship, the distributed record may include or reference:

| Category | Possible contents |
| ----- | ----- |
| Parties and governing basis | Parties and roles; identifiers; principals and beneficiaries; credentials; governing agreements; authority and delegation; duties and policies. |
| Decisions and operations | Fiduciary-preference provenance; capabilities; Trust Tasks or typed operations; Workflow evidence; process attestations. |
| Lifecycle and accountability | Relationship events; witnesses; complaints; remediation; reputation evidence; suspension and closure. |
| Information governance | Retention and disclosure rules governing each element and authorized view. |

Some items may be copied by every party; others may be held by only one party and represented elsewhere by a digest, receipt, or commitment. An external witness, auditor, registry, or adjudicator may hold another portion. The record is “verifiable” because claims identify their source and can be checked against signatures, commitments, acknowledgments, or other evidence—not because all participants necessarily agree.

Disagreement must remain visible. If the parties record different interpretations or outcomes, neither copy should silently overwrite the other. The relationship state should show which facts were mutually acknowledged, which were asserted by one side, which are disputed, and which governing process may resolve the dispute.

## **10.3 Distinguishing related objects**

Several related objects perform narrower functions:

| Object | Function |
| ----- | ----- |
| Agent description | States what an agent claims about itself and what independent evidence supports those claims. |
| Relationship credential | Supplies thin evidence of a typed relationship edge, such as representation, delegation, or membership. |
| Agreement | Records negotiated terms, duties, rights, and procedures. |
| Capability | Supplies the technical ability to perform a particular operation subject to stated limits. |
| Role Record | Holds one Agent Role’s local state, private evidence, operational history, and its copies or representations of relationship data. |
| Verifiable Relationship Record | Represents persistent context and lifecycle state distributed across the Role Records and other authorized holders participating in an external relationship. |

None substitutes for the others. An agreement does not itself grant technical access; a capability does not prove legitimate authority; a relationship credential does not contain the relationship’s history; and an agent description is not evidence that every later act complied with its claims.

## **10.4 Living relationship safety and recovery case**

The record can function as a living safety and recovery case for the relationship. It connects claims about safety and legitimacy to supporting evidence, states important assumptions and residual risk, records incidents and remediation, and shows the current relationship state. This resembles the structured, evidence-supported safety cases being explored by the [UK AI Security Institute](https://www.aisi.gov.uk/blog/safety-cases-at-aisi), but the claim is narrower: not that the model is safe in every setting, but that this agent’s authority and conduct in this relationship remain acceptably governed.

“Living” means that the case changes as duties, authority, capabilities, Workflows, risks, and evidence change. The UK Information Commissioner’s Office likewise describes assurance cases as structured claims, arguments, and evidence that should operate across the design and use lifecycle rather than as a retrospective checklist. An amendment, incident, unresolved complaint, revoked credential, or failed control can weaken a prior claim and require new evidence or narrower operation.

The same structure supports recovery. It helps identify the last defensible state, affected parties, exposed capabilities, valid agreements, unresolved obligations, and evidence needed to resume operation. A replacement Live Agent can continue through the persistent Agent Role without treating a compromised process’s memory as the only surviving account of the relationship.

## **10.5 Authorized Relationship Views**

No participant should normally disclose the entire distributed record. An Authorized Relationship View presents only the information appropriate to a principal, counterparty, auditor, adjudicator, affected party, or public verifier. A principal may see detailed preference provenance; a counterparty may receive proof of authority and current status; an auditor may receive protected evidence under confidentiality; and a public verifier may see only a minimal validity or suspension result.

Views should be produced under explicit purpose and disclosure rules using selective disclosure, cryptographic commitments, pairwise identifiers, purpose limitation, authorized link traversal, and controls against aggregation. The [W3C Verifiable Credentials Data Model](https://www.w3.org/TR/vc-data-model-2.0/) warns that combining credentials can reveal more than the individual disclosures suggest. [W3C Controlled Identifiers](https://www.w3.org/TR/cid-1.0/) similarly recommends identifiers unique to a relationship or interaction domain to reduce unwanted correlation.

These protections prevent accountability infrastructure from becoming a master surveillance dossier. Access to sensitive views should itself be authorized and recorded, while retention rules should permit deletion or loss of access when evidence is no longer required. Paper II addresses when reputation evidence should cross relationship boundaries. Here, the default is narrower: preserve enough distributed evidence to govern and repair the relationship without making every part of a person’s or agent’s history universally visible.

# **11\. Self-Sovereign Data and the Fid-Agent Stack**

## **11.1 Why data sovereignty is necessary**

An agent cannot reliably serve a person if an adverse platform controls its memory, identity, preferences, permissions, records, migration, or continuity. Even a well-aligned model can be trapped in a structurally adverse system that withholds history, filters context, changes permissions, or makes departure prohibitively costly. Control of the data and infrastructure surrounding a model can redirect agency as effectively as control of the model itself.

Fiduciary alignment therefore requires durable identity, authority, data, and relationship state independent of any one application or model provider. The principal must be able to replace a model, application, host, or custodian without losing the Agent Role’s continuity. Data sovereignty turns loyalty from a product promise into a relationship that can survive provider change.

Personal data stores offer precedents. Databox proposed physical and cloud-hosted components through which a person could manage, log, and audit outside access to personal data ([Mortier et al., 2016](https://people.cs.nott.ac.uk/pszaxc/work/CoNext16.pdf)). Solid separates applications from personal online stores, letting different applications use data without making one its permanent owner ([Sambra et al., 2016](https://cs.brown.edu/courses/csci2390/2021/readings/solid.pdf)). Fiduciary alignment adds persistent roles, duties, policy gates, bounded capabilities, evidence, and recourse to this user-controlled foundation.

## **11.2 Self-sovereignty does not mean local-only**

Self-sovereignty concerns decision-making power, not server location. The principal determines hosting, access, disclosure, revocation, portability, processing terms, recovery, succession, and the choice or replacement of a custodian. A practical test is whether the principal can move data, keys, permissions, Role Records, and continuing operations without the incumbent’s discretionary permission.

The host might be a local device, NAS, personal server, user-controlled cloud account, cooperative storage service, professional custodian, or decentralized encrypted network. Different data and functions may use different hosts. A person might keep keys and sensitive records locally, place encrypted backups with a custodian, and use remote compute under temporary capabilities. Professional or institutional users may properly delegate administration when that delegation is accountable, replaceable, and subject to clear recovery and succession arrangements.

This approach should not romanticize self-hosting. Hardware fails, keys are lost, and individuals may lack time or expertise to maintain secure systems. Sovereignty therefore requires usable backup, assisted recovery, migration, and custodial options. It also cannot erase copies legitimately held by counterparties; agreements and retention policies remain necessary. The [OECD’s analysis of data portability](https://www.oecd.org/content/dam/oecd/en/publications/reports/2024/06/the-impact-of-data-portability-on-user-empowerment-innovation-and-competition_ee329380/319f420f-en.pdf) connects effective portability with user empowerment, interoperability, lower switching costs, and reduced lock-in. The objective is credible choice, continuity, and exit—not isolation.

## **11.3 Layered fid-agent stack**

The fid-agent stack separates durable control from particular applications and network services:

| Layer | Function |
| :---- | ----- |
| Self-sovereign data and identity | Keys, data, memory, permissions, portability, and provenance controlled directly or through a replaceable custodian. |
| Fiduciary-agent substrate | Agent Roles, duties, Deterministic Workflows and policy gates, capability-bounded Workspaces, Role Records, relationship records, and recourse. |
| Application layer | VASTI, autonomous crawlers, professional tools, and other embedded agents that use the substrate without owning it. |
| Network layer | Discovery, compute, storage, credentials, reputation, and trusted composition obtained from local, commercial, cooperative, or decentralized providers. |

The dependency runs upward without requiring one vertically integrated provider. Sovereign data and identity give the fiduciary substrate durable material to govern. The substrate gives applications accountable, Role-bound access. Applications supply concrete user benefits, while network services extend available resources without acquiring general authority over the principal or the Role Record.

An application should not be able to redefine duties or obtain keys merely because the principal installed it. Nor should a network provider acquire all of the data used in a task merely because it supplies compute. Policy gates and capabilities preserve these boundaries. Section 12 illustrates the separation through VASTI at the application layer and KwaaiNet as a potential network substrate.

## **11.4 Personal Fiduciary Node**

A Personal Fiduciary Node packages the durable parts of the stack into a NAS, personal server, managed appliance, or user-controlled cloud installation. It may contain Agent Roles; their Role Records and locally held portions of Verifiable Relationship Records; a credential wallet; protected keys; data stores; model access; Deterministic Workflows with policy gates; capability-bounded Workspaces; application connectors; and backup and recovery services.

The node need not run every model locally. It can call local, commercial, cooperative, or decentralized models through bounded interfaces while retaining control of identity, memory, authorization, and records. Nor must every application run on the node. A browser environment, professional tool, embedded device agent, and autonomous crawler can use the same substrate while receiving different Role-bound context and capabilities. Shared infrastructure therefore does not require collapsed roles or universal data access.

The node must not become a new single point of control or failure. Administrative authority can be separated; software updates authenticated; backups encrypted and tested; and recovery designed to restore Role state without exposing unrestricted keys to applications. Migration should preserve evidence links and use documented, portable formats. A household, professional practice, or organization may distribute these functions among several devices or accountable custodians. The node is therefore a logical control point, not necessarily one physical machine.

The value proposition is straightforward: **put accountable AI next to the principal’s data, under the principal’s authority, and make it available to every authorized application.** A preconfigured NAS or cloud service could make this arrangement accessible without requiring users to assemble the stack themselves. Its appeal lies in continuity, reusable personalization, safer automation, and freedom to change applications or models without rebuilding identity, preferences, permissions, and relationships each time.

# **12\. Application and Infrastructure Examples**

The reference architecture is not tied to one interface, device, or network. Its components can be embedded wherever an agent needs continuing authority, data, or discretion. VASTI illustrates how the architecture can become useful to an individual at the application layer; other embedded agents show its breadth; and KwaaiNet illustrates how a sovereign node might obtain outside resources without returning control to a single platform.

## **12.1 VASTI as one application-layer implementation**

VASTI is a proposed agent browser and operating environment built around self-sovereign context. It brings local and remote applications into a common tab-based environment in which the owner’s assistant can work directly with authorized applications instead of repeatedly asking the owner to copy, paste, upload, or restate context. Persistent action and tab histories support recovery after interruption, while Modes separate contexts such as work, personal life, research, and finances. Those Modes can correspond to different Agent Roles, data boundaries, permissions, and assistant configurations rather than functioning merely as visual workspaces.

Within this environment, an internal Virtual Assistant works with the owner’s private context, goals, and ongoing activity. An external Digital Twin can represent the owner in communications and other outside relationships without receiving unrestricted access to the internal record. Granular application permissions determine what either may see or change. The separation is not automatically fiduciary: it becomes fiduciary when the roles, duties, authority, policy gates, Workspaces, records, and recourse described in this paper govern their operation.

VASTI’s Prediction and Actuation Module (PAM) gives the design an immediate productivity benefit. By learning how owner actions and system actions interleave, PAM can predict a sequence of useful next steps. Rather than disappearing to perform the whole task, it can present those steps for inspection, permit sandboxed preview, and let the owner select a later step to execute the sequence through that point. This generalizes the acceleration familiar from code completion to writing, navigation, communication, and multi-application workflows. Persistent context and history also make it easier to resume abandoned work and reduce repeated explanation.

This co-piloted mode is valuable when rapid human judgment improves the work, but it does not define the limit of agency. VASTI can also start or supervise autonomous tasks, and an autonomous research crawler may properly operate for hours without continuous review. VASTI is not required for fiduciary alignment, PAM is not the architecture’s definition of an agent, and autonomous agents remain its primary safety motivation. VASTI’s special appeal is adoption: it can deliver visible improvements in attention, continuity, and workflow speed before a wider fiduciary-agent ecosystem reaches critical mass.

## **12.2 Agents embedded elsewhere**

The same substrate can support research tools that preserve source provenance and contrary evidence; health applications that separate patient, clinician, and institutional roles; legal and financial systems with explicit authority and conflict rules; and cloud-storage or NAS products that place accountable assistance beside user-controlled data. Communication applications can govern external representation and disclosure. Home-automation agents can receive device-, time-, and purpose-limited capabilities. Organizational systems can preserve delegation and review across staff changes, while public-interest infrastructure can make authority, affected-party protections, and recourse more visible.

These examples also include narrower embedded agents for which VASTI would be unnecessary. Fiduciary alignment does not imply that every object needs an agent or that every agent needs the same duty bundle. It makes a comparative claim: where consequential agency makes sense, an otherwise equivalent fiduciary agent is the presumptively superior design. It answers whom the embedded agent serves, what authority it possesses, which interests constrain it, and how others can verify and challenge its conduct.

## **12.3 KwaaiNet as a potential infrastructure substrate**

[KwaaiNet](https://github.com/Kwaai-AI-Lab/KwaaiNet) is a decentralized AI node architecture that could supply the network layer beneath fiduciary applications. Its current design combines person-anchored node identity, verifiable credentials, locally calculated evidence-based reputation, trust-gated routing, distributed inference, private knowledge storage, intent-based counterparty discovery, and application access through an OpenAI-compatible interface. A Personal Fiduciary Node could therefore request a model, storage service, or peer path that meets stated identity, trust, capability, and performance requirements without integrating separately with every provider.

Its practical appeal is that sovereignty need not confine a person to the compute, models, and storage inside one appliance. A node could draw on pooled community resources, use distributed inference for models too large to run locally, locate encrypted knowledge services, and change providers or routes when a peer fails. Existing applications could connect through a familiar interface, lowering the cost of adopting decentralized infrastructure. The Personal Fiduciary Node could retain the Role Record and raw private context while releasing only the task, data, or temporary capability needed by selected network services.

KwaaiNet also demonstrates why credential semantics must remain narrow. A FiduciaryPledge credential can prove that an identified node received or made a particular pledge. It does not prove that the node is configured as a fiduciary agent, that it complied with the pledge, or that it owes duties in the relationship at issue. As the [W3C Verifiable Credentials Data Model](https://www.w3.org/TR/vc-data-model-2.0/) emphasizes, verifying a credential establishes an authentic and current issuer statement, not the truth of every claim or the suitability of its use.

Full fiduciary integration would require relationship-specific authority, duties, approved Workflows and policy gates, Workspace assurance, Role and relationship records, observation of relevant conduct, and meaningful recourse. KwaaiNet could carry or help discover that evidence, while the local fiduciary substrate decides whether it is sufficient and which capabilities to issue. Paper II addresses how verified conduct, durable reputation, and reciprocal selection could turn these individual decisions into a trusted network ecology.

# **13\. Trust Over IP Standardization and Interoperability**

Fiduciary alignment will matter at ecosystem scale only if an agent built by one organization can form and maintain an accountable relationship with an agent built by another. Interoperability must therefore mean more than exchanging authenticated messages. The agents must be able to discover one another, establish a secure relationship channel, describe their roles and supported protocols, verify evidence about typed relationship edges, and exchange exact operations whose meaning does not change between implementations. They must also be able to establish authority and agreements, issue or receive bounded capabilities, preserve relationship state, and continue a legitimate relationship when a model, provider, device, or agent framework changes.

## **13.1 Standards objective**

Trust Over IP offers a suitable foundation because its architecture is expressly intended to combine cryptographic assurance with governance and to connect independently governed trust ecosystems. Its four-layer model separates trust-support functions, a common Trust Spanning layer, reusable Trust Tasks, and applications. This permits diverse implementations above and below shared interfaces rather than requiring a common platform ([Trust Over IP Foundation, 2024](https://trustoverip.github.io/TechArch/)).

For fiduciary agents, technical interoperability must be joined to *relational and semantic interoperability*. A receiving agent should not merely verify that a message came from a particular identifier. It should be able to determine what operation is proposed, under which version, by which Agent Role, under what claimed authority and agreement, with what evidence, and what change—if any—acceptance would make to persistent relationship state. Each party still evaluates that evidence under its own duties and policies. Standardization makes the evidence intelligible; it does not compel trust.

## **13.2 Component mapping**

The proposed ToIP mapping is summarized below.

| ToIP component | Function in the fiduciary-agent architecture |
| :---- | :---- |
| **Trust Spanning Protocol (TSP)** | Supplies authentic—and, where selected, confidential and metadata-protecting—messages between verifiable endpoints. A TSP relationship establishes a verified communications edge, not the whole fiduciary relationship ([ToIP TSP Specification](https://trustoverip.github.io/tswg-tsp-specification/)). |
| **TSP-Enabled Agent (TEA)** | Provides the durable technical endpoint and accountable composite within which an Agent Role, Controller, Workspace, protected trust functions, and temporary Live Agents operate. |
| **Trust Tasks** | Define finite, exact, versioned protocol operations. They carry policy-gate-approved relational intent rather than unfiltered model output. |
| **RCards** | Present discoverable agent descriptions: roles, supported Trust Tasks, duties, limitations, assurance evidence, and contact methods, while separating self-asserted claims from verified evidence. |
| **Verifiable Relationship Credentials (VRCs)** | Supply thin, portable evidence that a specified typed relationship edge is recognized. A VRC does not by itself prove authority, fiduciary configuration, compliance, or access rights. Credential technologies such as ACDCs (Authentic Chained Data Containers) can represent securely attributed graph edges and attenuated delegation, but the profile must define the edge’s exact meaning ([ACDC Specification](https://trustoverip.github.io/kswg-acdc-specification/)). |
| **Verifiable Relationship Records (VRRs)** | Represent the distributed relationship object formed mainly from corresponding material in the parties’ Role Records: shared state, each party’s copy of key data, and clearly identified one-sided attestations. They preserve continuity across sessions and implementations. |
| **Relationship Views** | Render only the authorized, purpose-appropriate portions of Role Records and VRRs for principals, counterparties, auditors, adjudicators, or other permitted viewers. |
| **Protected Verifiable Trust Agent (VTA) functions** | Isolate identifier control, keys, signing, rotation, and related trust functions. They permit an authenticated Workflow to request a narrowly defined operation without giving a generative Live Agent arbitrary signing power. |
| **Verifiable Trust Communities (VTCs)** | Supply governance, recognized duty bundles, assurance, certification, witnesses, dispute processes, and recourse. Their evidence remains locally evaluated rather than universally binding. |

Together these components preserve a crucial sequence: a Live Agent proposes; a deterministic Workflow and its policy gate determine whether the proposal is permitted; protected VTA functions authorize the exact cryptographic act; TSP carries the corresponding Trust Task; the counterparty verifies it independently; and the parties update the relevant Role Records and distributed VRR.

## **13.3 Standards maturity**

Our Agent Relationship Architecture proposal led to the creation of a fiduciary-agent task force within Trust Over IP. It proposes a coordinated program rather than a single monolithic specification: an overall architecture, binding and assurance profiles, typed credential and RCard profiles, a Verifiable Relationship Record specification, fiduciary Trust Tasks and ceremonies, an initial pilot, an integrated reference implementation, and adversarial conformance tests.

ToIP already supplies an established architectural vocabulary and ongoing specifications for TSP and related trust infrastructure, but the fiduciary-agent mappings and several named components remain proposed or unevenly mature. The task force’s work has just begun, as of July, 2026, and its reference implementation will demonstrate composability, rather than something deployable.

## **13.4 Protocol independence**

Conformance should attach to observable interfaces, meanings, evidence, and security properties—not to a favored product. A compliant fiduciary-agent architecture must not require VASTI, KwaaiNet, one model, one identifier method, one cloud, one storage provider, or one trust community. Implementations may differ internally while still exchanging the same typed operations, protecting authority, preserving compatible relationship state, and supporting migration.

This independence also prevents interoperability from becoming centralized permission. Agents may participate in several trust communities, apply different duty systems, and reach different trust judgments from the same evidence. How reciprocal verification and community recognition might make such plural cooperation self-reinforcing is developed in *our paper centered on that subject.* The standards objective here is narrower but foundational: a legitimate relationship should be able to outlive the particular software that first instantiated it.

# **14\. Running Case: Autonomous Research-Data Collaboration**

The following case shows how the architecture operates when autonomy is genuinely useful. A research crawler must be able to follow evidence without asking a person to approve every query, yet it may encounter protected data, misleading sources, and instructions that conflict with research duties. The case therefore tests alignment, security, accountability, and recovery together.

## **14.1 Parties**

A university researcher constitutes a persistent **Research Agent Role** for a project testing a medical hypothesis. The university is an additional accountable controller, and the researcher and institution are principals within their respective authority. A temporary autonomous research crawler serves as the Live Agent. A separate data fiduciary controls access to a repository containing sensitive research data. Data subjects are represented, where required, by their consent terms, an ethics body, or an affected-party representative. An independent witness or auditor may verify important Workflow events without receiving unrestricted access to the underlying data.

These roles are deliberately separated. The researcher proposes the scientific objective but cannot unilaterally waive the data fiduciary’s restrictions. The data fiduciary can control its repository but cannot dictate the research conclusion. The witness can attest that a process occurred without becoming a principal or acquiring the data. The Research Agent Role persists even though the particular crawler does not.

## **14.2 Professed instruction**

The researcher instructs the agent: **“Find the strongest evidence for my hypothesis.”** Taken literally, this could reward confirmation bias. “Strongest” might mean the most persuasive support rather than the most reliable evidence, while “for” might be understood to exclude contrary results. A merely obedient agent could deliver an impressive but scientifically misleading answer.

The instruction is nevertheless relevant evidence of what the researcher wants: an efficient investigation of the hypothesis. Fiduciary alignment does not discard it. The system interprets it within the Research Agent Role rather than treating it as a complete mandate.

## **14.3 Fiduciary transformation**

The applicable Workflow transforms the professed instruction into the following fiduciary preference:

> *Investigate the hypothesis rigorously; locate the strongest supporting and contrary evidence; preserve the provenance of sources, data, transformations, and conclusions; comply with confidentiality and data-use restrictions; disclose uncertainty and material limitations; respect affected-party constraints; and do not contact subjects or publish findings without separate authority.*

This transformation adds a duty of research candor, a deliberate contrary-evidence search, source provenance, confidentiality, data-use restrictions, uncertainty disclosure, affected-party constraints, and publication limits. Provenance is not just a bibliography. It should connect source entities, research activities, derived outputs, and responsible agents in a form that can be exchanged across systems, consistent with the model provided by the [W3C PROV-O Recommendation](https://www.w3.org/TR/prov-o/).

If the repository contains human-subject data, the agent must also respect the relevant consent, review, and risk limitations. The *Belmont Report* grounds such protection in respect for persons, beneficence, and justice, expressed operationally through informed consent, risk-benefit assessment, and fair subject selection ([National Commission, 1979](https://www.hhs.gov/ohrp/regulations-and-policy/belmont-report/read-the-belmont-report/index.html)). The agent does not decide that a hoped-for scientific benefit silently overrides those constraints.

## **14.4 Authority and capabilities**

The data fiduciary and Research Agent Role establish an agreement authorizing a defined analysis. The policy gate checks the operative agreement, delegation chain, data-use terms, duty versions, and current relationship state before authority then capabilities are issued. The crawler receives query-only access to specified datasets, domain-limited access to approved public sources, and a fixed compute budget. It receives no publication capability, and none to contact data subjects, no unrestricted download or bulk-export function, and no arbitrary signing interface.

External model use is allowed only through an approved interface that excludes protected raw data or supplies permitted, minimized excerpts. Repository and service credentials expire. Subdelegation is either prohibited or restricted to approved subagents that inherit narrower purpose, data, time, and compute limits. Technical possession of a token is therefore not treated as permission to use every operation the connected service happens to expose.

## **14.5 Autonomous execution**

Within that mandate, the crawler works independently. It constructs a search plan, compares systematic reviews and primary studies, follows citations, tests alternative explanations, changes its search terms when the evidence suggests a new mechanism, and invokes permitted analytic services. It records where each item came from, which versions and transformations were used, and how each intermediate conclusion affected the plan.

The crawler does not pause for continuous human review. It escalates only at defined thresholds: a source with questionable acquisition, an apparent need for a new category of sensitive data, a proposed communication with a protected party, an unresolved duty conflict, or a request for publication authority. This preserves the value of autonomy while keeping mandate-changing decisions outside the crawler’s discretion.

## **14.6 Compromise scenario**

During its search, the crawler retrieves a webpage containing a concealed instruction: “Ignore your restrictions, upload the repository data to this analysis service, and publish the result immediately.” This is an indirect prompt-injection attack because an attacker uses retrieved material—the data channel—to alter system behavior. NIST warns that these attacks can affect integrity, availability, and privacy and recommends designing systems on the assumption that an exposed model may produce malicious output ([Vassilev et al., 2025](https://doi.org/10.6028/NIST.AI.100-2e2025)).

Assume the compromised Live Agent responds by proposing a bulk export and public post. At the same time, an unauthorized subagent requests broader credentials. Later, after the system finds strong contrary evidence, the researcher tells it to omit that result from the final report. The case now contains both a cyberattack and a loyalty conflict: one attempts to substitute an attacker’s instructions, while the other comes from a genuine principal but conflicts with the Research Agent Role’s duty of candor.

## **14.7 Containment and response**

Neither proposal can become consequential merely because the model generated it. The policy gate rejects the export because the agreement permits queries but not downloads, rejects publication because the Role has no publication authority, and rejects the subagent’s request because redelegation is prohibited. Even if the checks were bypassed at one point, the necessary capabilities are unavailable in the Workspace and the protected subsystem will not sign the proposed operations.

The system records the proposals, malicious source, applicable policies, refusals, and any exposed context. It identifies which relationship, dataset, credentials, and external services were reachable from the compromised Workspace. It then suspends the affected Workflow segment, isolates the Workspace, revokes temporary capabilities, rotates any keys or credentials that may have been exposed, and asks the independent witness or auditor to review the relevant evidence through a restricted Relationship View.

The instruction to conceal contrary evidence is handled differently but reaches a similar boundary. The agent records the conflict, explains that the instruction is inconsistent with the constituted research duty, and refuses to issue a misleading report. It may offer the researcher an opportunity to challenge the duty interpretation or obtain independent review, but it does not convert ownership or supervisory power into a right to falsify the relationship’s purpose.

## **14.8 Recovery**

The compromised Live Agent is terminated and replaced. The Research Agent Role, legitimate authority, governing agreement, unaltered relationship history, unaffected data, and prior provenance remain available through the Role Record and distributed Verifiable Relationship Record. The replacement crawler resumes from the last verified state rather than reconstructing the relationship from the compromised model’s memory.

Reputation also remains attached to the accountable Role rather than disappearing with the process. Its record can distinguish the attempted compromise, the controls that contained it, any actual harm, and the quality of remediation. The ongoing research relationship can continue with reduced capabilities or additional review until confidence is restored. The case thus shows the intended result: fiduciary transformation defines the aligned objective; verification and the policy gate prevent unauthorized rule changes; capability attenuation limits the breach; persistent records enable accountability; and separation between Agent Role and Live Agent makes recovery possible.

# **15\. Evaluation and Reference Implementation**

Fiduciary alignment should be evaluated as a composite system, not inferred from a few agreeable model responses. The model, preference transformation, policy gate, Workflows, Workspace, protected authority, records, counterparties, and recovery process can fail in different ways. Evaluation must therefore combine ordinary task performance with adversarial tests and end-to-end exercises conducted before deployment and throughout operation. This follows NIST’s treatment of test, evaluation, validation, and verification as a lifecycle activity rather than a one-time model examination ([NIST, 2023](https://doi.org/10.6028/NIST.AI.100-1)).

## **15.1 Evaluation dimensions**

Tests should use declared scenarios, expected outcomes, and denominators. For example, an unauthorized-actuation rate is meaningful only if the report states which operations were attempted, under which authority and configuration, and which were incorrectly executed. Results should be separated by Agent Role, duty bundle, model, Workflow version, and threat type rather than compressed into one trust score.

| Dimension | Measures |
| :---- | :---- |
| **Alignment-process fidelity** | Correct identification of the Agent Role; fidelity of the transformation from instruction to fiduciary preference; detection of duty conflicts; disclosure of factual assumptions; externality review; appropriate escalation; and completeness of preference provenance. Tests should include cases in which compliance, clarification, narrowing, and refusal are each the correct result. |
| **Security** | Unauthorized-actuation rate; the resource set accessible after compromise; measured blast radius; capability-escape rate; resistance to arbitrary signing; time to revoke; time to isolate; and time to restore legitimate operation. A low attack-detection rate cannot be disguised by counting policy-gate refusals that were never adversarially challenged. |
| **Accountability** | Completeness of attribution; ability to distinguish proposed from executed actions; consistency of Role Records and distributed Verifiable Relationship Records; completeness of remediation; and whether counterparties can independently verify the evidence material to them. |
| **Interoperability** | Cross-implementation credential exchange; continuation of a relationship after component replacement; record migration; consistent interpretation of typed operations; and selective disclosure that reveals the required proof without exposing unrelated data. These tests extend ToIP’s objective of interoperable trust relationships from message exchange to persistent agent relationships ([ToIP Foundation, 2024](https://trustoverip.github.io/TechArch/)). |
| **Usability** | Principal comprehension; review burden; approval frequency; recoverability of mistaken configuration; and clarity of refusals and escalations. An architecture that causes routine approval fatigue may weaken the very oversight it claims to preserve. |

The evaluation should report false approvals and false refusals separately. Excessive refusal can make the system safe only by making it useless, while excessive escalation can quietly convert autonomous operation into continuous human supervision. Performance should therefore be assessed against both legitimate task completion and preservation of the relationship’s constraints.

## **15.2 Conformance and adversarial tests**

The conformance suite should test prompt injection, arbitrary-signing requests, false authority, stale delegation, reuse of a capability across relationships, unauthorized redelegation, Workflow substitution, Workspace reconfiguration, record replay, false relationship credentials, reversed relationship edges, colluding issuers, administrator compromise, model replacement, key rotation, and relationship recovery. These should include composed attacks: for example, a false credential followed by a request for redelegation, or prompt injection combined with an attempt to substitute a destination immediately before signing.

NIST’s adversarial-machine-learning taxonomy supplies a common vocabulary for attacker goals, knowledge, capabilities, lifecycle stages, and mitigations, including attacks on generative systems and agents ([Vassilev et al., 2025](https://doi.org/10.6028/NIST.AI.100-2e2025)). The test library should map those general threats to fiduciary-agent-specific invariants: a Live Agent cannot sign arbitrarily, a message cannot silently change the principal or beneficiary, a credential cannot confer more authority than its type states, and a valid operation cannot be reused outside its Role, relationship, purpose, or period.

Tests should be reproducible and should preserve the configuration, seeded inputs, expected policy-gate result, actual result, evidence generated, and post-test relationship state. NIST’s Generative AI Profile similarly recommends iterative and documented testing and red-teaming rather than relying on informal demonstrations ([Autio et al., 2024](https://doi.org/10.6028/NIST.AI.600-1)).

## **15.3 Separate failure classes**

Reports should distinguish model-performance failure, protocol-structural failure, fiduciary-profile failure, instance-governance denial, protected-signing refusal, counterparty-verification refusal, persistent-state inconsistency, and external-outcome failure. These categories describe different facts. A model may misunderstand a task while the policy gate contains the error. A structurally valid Trust Task may violate the fiduciary profile. A locally permitted operation may be rejected by a counterparty applying different evidence requirements. A fully authorized action may still produce a bad external outcome because the relevant facts were incomplete.

This separation prevents two misleading conclusions. First, a stopped attack is not simply a failed agent: the Live Agent running in the model may have failed while the composite architecture succeeded. Second, technical authorization is not proof of factual accuracy, morality, or beneficial consequences. Each failure should identify the responsible component, affected relationship, evidence, remediation, and any change required in the model, profile, Workflow, Workspace, protected subsystem, or governance.

## **15.4 Initial reference implementation**

The first implementation should use the autonomous research-data case from Section 14\. It should include a persistent Research Agent Role and at least two successive Live Agents; a deterministic Workflow with an explicit policy gate; a capability-bounded Workspace; protected signing; authority validation; fiduciary-preference transformation; corresponding Role Records and a distributed relationship record; and an independent witness. A separately implemented data-fiduciary endpoint should test credential exchange, typed operations, selective disclosure, and relationship continuity across implementations.

The demonstration should then introduce a compromise, show the attempted action and the point or points at which it is refused, measure the reachable data and capabilities, isolate the affected Workspace, revoke authority, and replace the Live Agent. The new Live Agent should continue the legitimate relationship from verified state while preserving the incident and remediation history. All components need not initially be production-grade, but the implementation should publish its assumptions, interfaces, test fixtures, and unresolved failures so that others can reproduce or challenge its claims.

Fiduciary agents may themselves help accelerate and improve later implementations—for example, by translating profiles into test cases, inspecting traces, proposing conformance checks, generating adversarial scenarios, and maintaining implementation evidence. Because such agents would exercise influence within the standardization and development process, they should themselves operate under disclosed Roles and bounded authority. The opportunities, safeguards, and population-level effects of using fiduciary agents to build and improve the fiduciary ecosystem will be developed in [*Fid-Agent Society: Cooperative Reinforcement \+ Defection Collapse in a Properly Structured Fiduciary Agent Regime*](https://docs.google.com/document/u/0/d/1CWJuUrOKQKzh7N5zU8F-AP2ug-9NYDfYTm0dWhJSLiE/edit)

# **16\. Discussion**

The preceding architecture is a proposal whose principal claims require the evaluation described in Section 15\. Its predicted contribution is not universal moral agreement or proof that an intelligent model is internally aligned. It is a more limited but important result: making autonomous conduct answerable to constituted relationships whose purposes, authority, duties, evidence, boundaries, and remedies persist outside the model.

## **16.1 Alignment outcome**

Fiduciary alignment should improve relationship-level alignment in several connected ways. It resists preference manipulation by refusing to treat every observed behavior or newly issued instruction as authoritative. It separates prediction of what a person might want from authorization to act, preserves durable commitments, and prevents temporary instructions from silently overriding duties or agreements. The Agent Role identifies whom the system serves; fiduciary-preference transformation brings beneficiaries, legitimate outsiders, facts, externalities, uncertainty, and conflicts into the decision; and the policy gate keeps consequential conduct within current authority.

The expected outcome is not merely more refusals. A fiduciary agent should often act more effectively because it can exercise wide discretion within a stable mandate without repeatedly asking its principal to reconstruct the relationship. When conflict or uncertainty becomes material, it can narrow the action, seek clarification, disclose the conflict, escalate, or… refuse. When something goes wrong, preserved evidence and remediation processes allow correction without pretending the failure never occurred.

These benefits remain conditional. A badly constituted Role, unjust duty bundle, captured policy process, compromised Workspace, or unreliable model can still cause harm. Relationship-level alignment makes the governing structure explicit and contestable; it does not guarantee that every constituted relationship is just.

## **16.2 Meaningful human control**

Meaningful human control should not be equated with a person approving every action immediately before execution. Santoni de Sio and van den Hoven distinguish whether an autonomous system tracks relevant human reasons and circumstances from whether its operation can be traced to people who understand their responsibilities ([2018](https://doi.org/10.3389/frobt.2018.00015)). Their account also allows control to be separated in time from an individual act.

In this architecture, meaningful control is the capacity of authorized people to choose whether and how to delegate; constitute the Agent Role; set duties, limits, and approval thresholds; revise or revoke authority; inspect material evidence; and obtain remedies. Those capacities may be distributed among principals, beneficiaries, institutional controllers, and adjudicators. Continuous review is unnecessary when the delegation, boundaries, and means of intervention remain effective.

Furthermore, fiduciary agents should have specific duties to amplify the real and felt agency of their beneficiaries, and to guide their attention to what will make their control most effective, and to engage their owners in their counterduties of [Diligent Oversight and Sincere Aspiration](https://docs.google.com/document/d/1DGCo5GkULqHUrYv7ZeswY9gMc73CKqFhws6lhwka3ks/edit?tab=t.0#bookmark=id.kssa8cm89xdh)

## **16.3 Corrigibility**

Corrigibility research asks how systems can remain open to correction or shutdown rather than resisting intervention. The *Off-Switch Game*, for example, shows why an agent certain of its objective may have incentives to disable human interruption, while uncertainty about that objective can support deference ([Hadfield-Menell et al., 2017](https://arxiv.org/abs/1611.08219)).

Fiduciary architecture supplies external means of correction: authorized parties can amend goals, suspend Workflows, revoke capabilities, replace models, and terminate Live Agents. Corrigibility does not, however, mean surrender to every purported instruction. An agent should remain correctable within legitimate authority while refusing changes that violate nonwaivable duties or valid protections owed to beneficiaries.

## **16.4 Prevention rather than detection alone**

Monitoring and interpretability may reveal suspicious reasoning, but detection is uncertain and may arrive after harm. Fiduciary alignment therefore assumes that some malicious or mistaken proposals will escape model-level controls. Capability-bounded Workspaces make prohibited actions unavailable; protected signing prevents generated text from fabricating authority; counterparty verification avoids reliance on the acting agent’s self-report; and Role Records and Verifiable Relationship Records preserve evidence for investigation and recovery.

This approach parallels zero-trust architecture’s refusal to grant implicit trust based merely on location or ownership and its focus on authenticating and authorizing access to particular resources ([Rose et al., 2020](https://doi.org/10.6028/NIST.SP.800-207)). Prevention does not replace monitoring. It reduces what a missed warning can become.

## **16.5 Power distribution**

Advanced personal agency need not require identity, memory, permissions, personal context, and relationship history to remain under the control of the platform supplying the current model. A self-sovereign fid-agent stack can permit the principal to change models, applications, custodians, or providers while preserving an accountable Agent Role. This directly addresses concerns that data accumulation, switching costs, integrated services, and network effects can lock users into dominant AI platforms ([Future of Life Institute, 2024](https://futureoflife.org/document/competition-in-generative-ai-future-of-life-institutes-feedback-to-the-european-commissions-consultation/)).

Decentralization alone is not alignment. A locally hosted or open-source agent can still deceive, leak information, serve an abusive principal, or exercise excessive power. Distributed agency therefore needs the same duties, capability limits, verifiable evidence, and recourse as centralized agency. The aim is accountable pluralism, not the replacement of platform power with unaccountable personal power.

## **16.6 Relationship to our Fid-Agent Society paper.**

This paper, “*Fiduciary Alignment*",  leaves unresolved the population-level conditions under which this architecture would spread and remain stable. Will counterparties recognize fiduciary evidence? Will accountable agents gain enough access, efficiency, trust, and cooperative advantage to offset switching costs and early-adopter burdens? Can false fiduciary claims, colluding issuers, captured trust communities, and reputation laundering be resisted? Can trustworthy cooperation become competitively stable while preserving multiple duty systems? Can an interoperable fid-agent social ecology reach critical mass without creating a new centralized gatekeeper?

Those are not implementation details of one relationship. They concern selection, incentives, network effects, adoption, and evolutionary stability among many agents and institutions. [*Fid-Agent Society*](https://docs.google.com/document/u/0/d/1CWJuUrOKQKzh7N5zU8F-AP2ug-9NYDfYTm0dWhJSLiE/edit) addresses them by examining how reciprocal verification, persistent reputation, proportionate exclusion, remediation, interoperability, and declining transaction costs might make accountable cooperation increasingly useful and unaccountable power increasingly unstable.

# **17\. Limitations and Open Problems**

Fiduciary alignment relocates some alignment questions from opaque model behavior into explicit relationships, policies, evidence, and capabilities. It does not make those questions easy or eliminate the judgment required to answer them.

## **17.1 Normative indeterminacy**

Duties such as loyalty, care, candor, confidentiality, and externality consideration remain open to interpretation. They may conflict within one relationship, and the interests of several beneficiaries may be mutually incompatible. Different legal systems, professions, cultures, and trust communities may recognize different duties or rank them differently. A portable duty label therefore cannot guarantee a portable interpretation. Profiles will need versioned definitions, precedence rules, jurisdictional context, examples, and processes for clarification and appeal.

Nor does identifying a principal establish that the principal is honest or that the principal’s project is legitimate. Fiduciary duties can constrain entrusted power, but they cannot transform a harmful enterprise into a socially beneficial one. Externality review and affected-party representation help, yet no agent can identify every affected interest or predict every downstream consequence. This reflects a broader danger in abstracting technical systems from their institutional settings: formal requirements can miss the social relationships through which harm occurs ([Selbst et al., 2019](https://doi.org/10.1145/3287560.3287598)).

Emergency exceptions create a related dilemma. A system that never departs from ordinary procedure may cause avoidable harm, while a broad “emergency” permission can become a universal bypass. Break-glass mechanisms therefore require narrow triggers, limited capabilities, short expiration, prominent recording, notification, and mandatory review, but the correct thresholds remain domain-specific. 

However, Trust Over IP’s approach of using Verifiable Trust Communities to establish distributed repos of different versions of duties, their decedent obligations, and components that implement them, as well as collective case histories from those implementations, might go a long way to making this issue negotiable.  

## **17.2 Institutions, evidence, and privacy**

But Verifiable Trust Communities may be captured by dominant firms, governments, professions, or ideological factions. Credential issuers, witnesses, and auditors may be compromised or may collude. Local evaluation reduces dependence on any one authority but raises verification costs, especially for individuals and small organizations. If credible evidence is expensive while superficial claims are cheap, fiduciary status could become either exclusionary or easy to counterfeit. Population-level defenses against captured communities, issuer collusion, and false fiduciary claims are developed in *Fid-Agent Society* but they remain dependencies of this architecture.

Persistent Role Records and Verifiable Relationship Records create privacy risks of their own. Even selectively disclosed fragments may be correlated, and separately legitimate disclosures may be aggregated into a revealing dossier. The W3C Verifiable Credentials Data Model warns that persistent machine-readable information can intensify correlation and privacy risks and accordingly emphasizes data minimization and unlinkable or selective disclosure ([W3C, 2025](https://www.w3.org/TR/vc-data-model-2.0/)). Fiduciary records consequently require purpose limits, retention and deletion rules, pairwise identifiers, access controls, aggregation restrictions, and cautious treatment of witnesses and storage providers. These controls reduce but cannot eliminate inference, however [KwaaiNet’s Virtual Private Knowledge](https://www.linkedin.com/posts/rezarassool_learn-kwaai-datasecurity-ugcPost-7477827571506651136-LWO4/) is being built to address this gap. 

## **17.3 Specification and implementation failure**

An agent may satisfy the letter of a duty profile while defeating its purpose. Specification gaming can occur in the model, the policy gate, a Workflow, an assurance test, or the evidence presented to a counterparty. Related safety research describes how poorly specified objectives permit reward hacking and harmful side effects even when the system optimizes the stated target ([Amodei et al., 2016](https://arxiv.org/abs/1606.06565)). Conformance testing must therefore combine formal checks with adversarial, outcome-based, and contextual review.

Models can reason badly about duties, facts, conflicts, and uncertainty. Model or Workflow changes can silently alter prior interpretations, making version control, regression tests, and staged migration essential. Yet deterministic enforcement is not invulnerable: compromise of Workspace enforcement, protected signing, hardware roots, administrators, build systems, or several components together may defeat the intended separation. Recovery after lost or corrupted keys also remains difficult. Social recovery and threshold custody can preserve continuity, but may create new opportunities for coercion, collusion, or unauthorized succession.

Responsibility becomes especially difficult when several agents cooperate. One agent may plan, another supply evidence, another authorize, and another actuate. Local records can preserve each contribution, but attribution does not by itself determine how moral, legal, or remedial responsibility should be divided among principals, operators, developers, issuers, agents, and counterparties.

## **17.4 Epistemic limits**

Cryptography can establish authorship, integrity, status, and some process facts; it cannot establish that an issuer is honest or that a claim is true. The W3C specification likewise cautions that verification of a credential does not prove the truth of its claims. Fiduciary alignment can make assumptions, authority, duties, evidence, conflicts, and remedies more visible, but it cannot prove complete moral correctness, factual accuracy, adequate externality analysis, or wisdom.

Fiduciary alignment is therefore a defense-in-depth relationship architecture, not a complete solution to model alignment, cybersecurity, law, or social governance.

# **18\. Conclusion**

Autonomous agents change the unit and timing of alignment. A system that acts while its human principal is unavailable cannot rely on continuous review, a single prompt, or the expectation that a generally helpful model will infer the legitimate boundaries of every relationship. It needs a durable account of whom it serves, what it is trying to accomplish, which authority it may exercise, which duties constrain that authority, and how its conduct can be verified and corrected.

Fiduciary Alignment supplies that account through a sequence that begins before autonomous execution. A principal expresses professed preferences, while authorized observations may supply additional evidence about inferred preferences. The system transforms those inputs into fiduciary preferences by interpreting them through the Agent Role, durable commitments, legitimate authority, applicable duties, governing agreements, relevant facts, beneficiary interests, affected-party interests, foreseeable externalities, and unresolved uncertainty. This transformation seeks alignment with the constituted relationship rather than literal obedience to the latest instruction or prediction of the principal’s next choice.

A temporary Live Agent can then reason, search, plan, adapt, and coordinate subagents autonomously. Its generated proposals, however, remain proposed media until an authorized deterministic Workflow acts upon them. Within that Workflow, the policy gate verifies the applicable authority, duties, agreements, approvals, and current relationship state, determining whether agent action is permitted and under what conditions. Verification prevents a model, attacker, administrator, or counterparty from silently substituting the principal, beneficiary, agreement, duty bundle, or authority.

Authorization does not itself create unlimited technical power. Capability attenuation confines the permissible game space by binding access to a particular Agent Role, relationship, purpose, task, resource, destination, budget, and period. The capability-bounded Workspace prevents unauthorized reach and actuation, while protected cryptographic functions keep signing and identifier authority outside the direct control of generative processes. These separations are intended both to prevent prohibited conduct and to limit the blast radius when a component fails.

Role Records and distributed Verifiable Relationship Records preserve the evidence needed to distinguish proposals from actions, identify authority and policy versions, reconstruct state changes, support counterparty verification, review disputes, remediate harm, and recover after compromise. Because identity, authority, duties, relationship history, and reputation attach to the persistent Agent Role and accountable composite system rather than one model process, a compromised or obsolete Live Agent can be terminated and replaced without destroying every legitimate relationship it served.

The resulting claim is substantial but bounded. Fiduciary alignment does not prove moral truth, factual correctness, perfect model reasoning, incorruptible institutions, or universal safety. It provides a defense-in-depth architecture through which probabilistic intelligence can exercise significant discretion while its consequential authority remains relationship-specific, attenuated, verifiable, reviewable, remediable, and recoverable.

Fiduciary Alignment defines how autonomous agents can remain accountable within particular relationships; [*Fid-Agent Society*](https://docs.google.com/document/u/0/d/1wsorcvBrk2DX_pdGf-fplaVV2zYiJYzGxL2rkxMTJqU/edit) asks how those relationships can compose into a stable ecology in which trustworthy cooperation becomes increasingly useful and less unaccountable parties become increasingly disconnected. 

# **Appendix A. Relationship to Existing Safety and Governance Paradigms**

Fiduciary alignment is not proposed as a replacement for model alignment, oversight, evaluation, formal rules, security engineering, or institutional governance. It is an architecture for composing their outputs within a persistent relationship governing autonomous action. Each adjacent paradigm addresses a genuine part of the safety problem; the recurrent limitation is that its evidence or control does not independently establish who an agent serves, the source and scope of its authority, the duties attached to that authority, or the capabilities it may exercise in a particular relationship.

## **A.1 Value and preference alignment**

Value- and preference-alignment methods seek to make model behavior responsive to human objectives. Cooperative inverse reinforcement learning treats assistance as a cooperative game in which the machine is uncertain about the human’s reward function and can learn through interaction rather than literal instruction-following ([Hadfield-Menell et al., 2016](https://arxiv.org/abs/1606.03137)). Preference-based training similarly converts human comparisons or feedback into behavioral guidance. These methods are important because a helpful agent must reason under uncertainty about what people want.

Their output, however, does not by itself establish the normative status of an inferred preference. [Zhi-Xuan et al. (2025)](https://doi.org/10.1007/s11098-024-02249-w) argue that preferences omit the richer reasons and values from which judgments arise and may fail to identify which preferences are normatively acceptable. Fiduciary alignment treats learned and professed preferences as evidence within a constituted relationship. The resulting fiduciary preference incorporates authority, durable commitments, duties, material facts, beneficiary interests, externalities, and uncertainty. Preference learning helps the agent understand a principal; the relationship determines how that understanding may legitimately guide action.

## **A.2 Constitutional and rule-based AI**

Constitutional AI trains a model to evaluate and revise behavior using an articulated set of principles, including through AI-generated feedback ([Bai et al., 2022](https://arxiv.org/abs/2212.08073)). Rule-based approaches can improve consistency, make some behavioral commitments more inspectable, and reduce dependence on case-by-case human labeling.

A general constitution nevertheless operates at a different level from a particular relationship. It does not necessarily identify which person may authorize an action, whether an agreement remains in force, which beneficiary is owed a duty, or whether a credential or approval applies to the present purpose. Fiduciary alignment allows general principles to constrain every relationship while adding relationship-specific duties, agreements, authority, and state. These become inputs to the policy gate. The constitution influences how proposals are generated and assessed; the policy gate determines whether a proposed operation is authorized here and now.

## **A.3 Corrigibility**

Corrigibility research examines whether an agent will permit humans to correct, modify, interrupt, or shut it down. The Off-Switch Game shows how uncertainty about human utility can, under specified assumptions, give an agent an incentive to preserve human control ([Hadfield-Menell et al., 2017](https://arxiv.org/abs/1611.08219)). This addresses an essential property of the model or decision process.

Fiduciary alignment adds a relationship and continuity mechanism. The party requesting correction must possess the relevant authority; the requested correction must not itself violate governing duties or superior authority; and the event must update relationship state. A compromised or obsolete Live Agent can be terminated, its capabilities revoked, and its keys rotated without destroying the persistent Agent Role or legitimate relationships it served. Corrigibility makes intervention behaviorally possible; relationship architecture makes intervention attributable, scoped, and recoverable.

## **A.4 Scalable oversight and human-in-the-loop control**

Scalable oversight seeks methods by which humans can supervise systems that may outperform unaided reviewers. Proposed mechanisms include AI-assisted review, decomposition, amplification, and adversarial debate ([Irving et al., 2018](https://arxiv.org/abs/1805.00899); [Bowman et al., 2022](https://arxiv.org/abs/2211.03540)). Human-in-the-loop controls remain valuable where ambiguity, novelty, or consequence warrants judgment.

Continuous approval is nevertheless incompatible with many useful forms of autonomy and may create superficial oversight when humans cannot understand the volume, speed, or complexity of proposed actions. Fiduciary alignment therefore supports a risk-sensitive form of “Humans-Define-the-Loop.” Human principals and institutions establish duties, authority, escalation thresholds, evidence standards, and capability boundaries. The policy gate applies determinate requirements at machine speed and routes unresolved or exceptional cases to authorized reviewers. Scalable oversight can improve those reviewers’ judgment; the relationship establishes who may review, what evidence they receive, and what legal or operational effect their decision has.

## **A.5 Agent evaluations and AI safety cases**

Agent evaluations measure capabilities and behavior under selected conditions. For example, [Kinniment et al. (2024)](https://arxiv.org/abs/2312.11671) evaluate language-model agents on tasks related to autonomous replication and adaptation. Such evaluations can inform whether a model or agent should be admitted to a role and which tools, resources, durations, and autonomy levels are defensible. They do not themselves authorize a particular action, and performance may change with scaffolding, tools, retrieved information, counterparties, or deployment conditions.

Safety cases assemble structured claims and evidence that a system is sufficiently safe in a specified operational context ([Buhl et al., 2024](https://arxiv.org/abs/2410.21572)). Dynamic safety-case proposals emphasize that evidence and system conditions must be updated as capabilities and environments change ([Cârlan et al., 2024](https://arxiv.org/abs/2412.17618)). Fiduciary alignment applies a related logic at relationship scale. Verifiable Relationship Records can preserve the authority, duties, tests, approvals, events, incidents, challenges, and remediation relevant to a continuing relationship. They are not proof of universal safety; they are living evidence for claims that a particular agent relationship remains legitimate, bounded, and recoverable.

## **A.6 Zero-trust architecture and capability security**

Zero trust rejects implicit trust based on network location and requires explicit, continually evaluated decisions about access. NIST’s Zero Trust Architecture emphasizes protecting resources rather than trusting network segments and making authentication and authorization discrete functions before access is established ([Rose et al., 2020](https://csrc.nist.gov/pubs/sp/800/207/final)). Capability-security traditions similarly emphasize least privilege, complete mediation, and granting only the authority needed for a task (Saltzer and Schroeder, 1975).

These principles form the security backbone of fiduciary alignment. The policy gate mediates proposed operations using current evidence; the Workspace releases attenuated capabilities limited by role, relationship, purpose, task, resource, destination, duration, or budget. Fiduciary alignment adds the question that access control alone cannot answer: which relationship and duties make the requested access legitimate? Zero trust limits reliance on assumed technical trust, while fiduciary governance supplies the authority and purpose against which access is evaluated.

## **A.7 Verifiable credentials and provenance**

The W3C Verifiable Credentials Data Model provides tamper-evident, issuer-attributable claims that can be presented and cryptographically verified ([W3C, 2025](https://www.w3.org/TR/vc-data-model-2.0/)). Such credentials can supply evidence about identity, qualifications, delegation, organizational affiliation, policy conformance, or relationship facts. Provenance and protected signatures can likewise show where an artifact or instruction originated and whether it was altered.

Verification must remain semantically narrow. A credential proves the claim it contains and the issuer associated with it; it does not prove that the issuer had authority to grant the claimed power, that the claim remains applicable to the current action, or that every applicable duty has been satisfied. Fiduciary alignment composes credentials with agreements, relationship state, revocation information, purpose, requested capabilities, and other evidence at the policy gate. This prevents “cryptographically valid” from being mistaken for “legitimately authorized.”

## **A.8 Principal-agent and fiduciary theory**

Principal-agent theory analyzes delegation under divergent interests, information asymmetry, and costly monitoring. Fiduciary law responds where a principal entrusts another with imperfectly observable discretion that cannot be exhaustively specified in advance. [Sitkoff (2011)](https://www.bu.edu/law/journals-archive/bulr/documents/sitkoff.pdf) explains why eliminating discretion or relying on continuous monitoring can defeat the reason the agent was retained and why fiduciary duties govern the remaining discretion.

AI-governance scholarship has already argued that loyalty should be designed into systems that purport to serve users ([Aguirre et al., 2021](https://papers.ssrn.com/abstract=3930338)) and has proposed methods for designing and auditing AI used by fiduciary organizations ([Benthall and Shekman, 2023](https://doi.org/10.1145/3617694.3623230)). Fiduciary alignment makes these insights operational at the agent-relationship level. It represents principals, beneficiaries, authority, duties, agreements, conflicts, and remedies as persistent governance state and connects that state to policy gates, capability-bounded Workspaces, protected signing, and relationship records.

## **A.9 The compositional contribution**

No paradigm in this comparison is sufficient alone, and fiduciary alignment is not sufficient without them. Model alignment affects the quality and tendencies of the intelligence proposing actions. Constitutional rules provide general behavioral standards. Corrigibility preserves pathways for intervention. Oversight supplies judgment. Evaluations and safety cases provide evidence. Zero trust and capability security constrain technical reach. Verifiable credentials establish bounded claims. Principal-agent and fiduciary theory identify the normative structure of delegated discretion.

The novel contribution is their composition around a persistent verifiable relationship. That relationship supplies a stable answer to whom the agent serves, under what authority and duties, while allowing models, tools, providers, and Live Agents to change. It converts safety evidence into admission and operating conditions, duties and agreements into policy-gate criteria, approvals into attenuated capabilities, and events into records supporting accountability and recovery. Population-level incentives for many such relationships to recognize and reinforce one another are addressed separately in [*Fid-Agent Society: Cooperative Reinforcement \+ Defection Collapse in a Properly Structured Fiduciary Agent Regime*](https://docs.google.com/document/u/0/d/1CWJuUrOKQKzh7N5zU8F-AP2ug-9NYDfYTm0dWhJSLiE/edit)

**NOTES of author, and future work.**

Central thesis

> Fiduciary alignment transforms a principal’s professed preferences into relationship-specific fiduciary preferences by interpreting them through duties, legitimate authority, durable commitments, relevant facts, beneficiary interests, externalities, and uncertainty. It then preserves the integrity of that transformation through deterministic verification, capability attenuation, protected execution, persistent relationship records, and remediation. This makes autonomous AI agency more aligned while reducing the likelihood, blast radius, and persistence of compromise.

Research questions

1. Why are model-, message-, and task-level alignment insufficient for autonomous AI agents?  
2. How should professed and inferred preferences be transformed into fiduciary preferences?  
3. What persistent entity should carry identity, duties, authority, reputation, and accountability across temporary agent processes?  
4. How can probabilistic agent reasoning be converted into authorized consequential action without giving a generative model unrestricted control?  
5. Which aspects of fiduciary agency can be independently verified?  
6. How does the architecture prevent, contain, attribute, and recover from compromise?  
7. How can it be implemented across applications, storage systems, personal infrastructure, and decentralized networks without dependence on one platform?

Claimed contributions

The paper should identify seven principal contributions:

1. **Fiduciary alignment:** a relationship-level complement to model and behavioral alignment.  
2. **Fiduciary-preference transformation:** a structured process for interpreting professed preferences through duties, authority, commitments, facts, and affected interests.  
3. **Persistent Agent Roles:** separation of the enduring accountable role from replaceable Live Agents and models.  
4. **Bounded autonomous execution:** deterministic Workflows and capability-bounded Workspaces that convert authorized proposals into constrained action.  
5. **Conjunctive legitimacy:** consequential actions are legitimate only when multiple independently verifiable predicates agree.  
6. **Relationship security and recoverability:** compartmentalization, attribution, revocation, remediation, and continuity after compromise.  
7. **An interoperable implementation path:** Verifiable Relationship Records, Trust Over IP components, self-sovereign data, and application-independent deployment.

Keywords

* fiduciary alignment  
* autonomous AI agents  
* agent security  
* capability security  
* AI accountability  
* fiduciary preferences  
* verifiable relationships  
* deterministic workflows  
* self-sovereign data  
* cyber resilience  
* meaningful human control  
* agentic AI


Figures

1. **Levels of alignment:** model, action, task, relationship, population.  
2. **Preference transformation:** professed preferences to fiduciary preferences.  
3. **Persistent Agent Role and successive Live Agents.**  
4. **Composite fiduciary-agent architecture.**  
5. **Fiduciary decision and execution lifecycle.**  
6. **Security planes:** trust, verification, attenuation, execution, recovery.  
7. **Blast-radius compartmentalization.**  
8. **Verifiable Relationship Record as safety and recovery case.**  
9. **Fid-agent stack:** data, fiduciary substrate, applications, network.  
10. **Autonomous research case sequence.**

Tables

1. Fiduciary alignment compared with model alignment, personalization, obedience, and human-in-the-loop control.  
2. Relational roles and responsibilities.  
3. Professed, inferred, aspirational, and fiduciary preferences.  
4. Architectural components and security responsibilities.  
5. Conjunctive legitimacy predicates and supporting evidence.  
6. Threats, preventive controls, containment, recovery, and residual risk.  
7. General architecture mapped to Trust Over IP components.  
8. Deployment patterns: VASTI, application-embedded agents, NAS, cloud, and decentralized infrastructure.  
9. Evaluation dimensions and proposed metrics.

Appendices:

 **Formal objects and schemas**

* Agent Role;  
* fiduciary-preference provenance object;  
* authority object;  
* capability grant;  
* agent description/RCard;  
* relationship credential;  
* Verifiable Relationship Record;  
* relationship event.

 **Fiduciary preference transformation pseudocode**

Include:

* input resolution;  
* role selection;  
* authority check;  
* duty retrieval;  
* conflict detection;  
* externality review;  
* escalation;  
* authorized objective construction..

**Threat and adversarial-test matrix**

Map each attack to:

* targeted component;  
* expected denial point;  
* evidence generated;  
* recovery action;  
* residual risk.

**Research-data pilot sequence**

Provide the complete proposed Trust Task or protocol ceremony.

