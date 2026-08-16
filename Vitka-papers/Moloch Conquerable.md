This paper, while it works as a standalone, was generated as appendix to [Verified Fiduciary Reciprocity.  I chose the sources and all arguments are mine.](https://docs.google.com/document/u/0/d/1LPoIiN708oiQlNIlDe7gmhcMHeJubunxxBH3nUeGwjI/edit) 

[Here is a link to a pre-seeded Gemini Chat you can have about this paper.](https://docs.google.com/document/u/0/d/1LPoIiN708oiQlNIlDe7gmhcMHeJubunxxBH3nUeGwjI/edit)  
 

# **Appendix C. Verified Fiduciary Reciprocity as a Comprehensive Response to Moloch, LessWrong, and AI-Safety Coordination Failure**

## **Background: Moloch, LessWrong, and Jonah Wilberg’s Evolutionary Reframing**

This appendix responds to a particular intellectual tradition that may be unfamiliar to some readers: the LessWrong discussion of **Moloch**. LessWrong is an online community centered on rationality, AI alignment, decision theory, epistemology, forecasting, and civilizational risk. It has played an important role in popularizing many concepts now common in AI-safety discourse: alignment failure, mesa-optimization, multipolar traps, inadequate equilibria, Goodhart’s Law, coordination failure, and the strategic dangers of racing dynamics.

Within that community, **Moloch** is one of the central metaphors for destructive coordination failure. The term was popularized by Scott Alexander’s essay **Meditations on Moloch**, which uses the name “Moloch” to personify situations where individually rational or locally adaptive behavior produces collectively terrible outcomes. The LessWrong wiki describes Alexander’s essay as illustrating the dynamic through examples such as prisoner’s dilemmas, dollar auctions, the Malthusian trap, capitalism, arms races, races to the bottom, education, science, government corruption, and corporate welfare. ([LessWrong](https://www.lesswrong.com/w/moloch))

The basic idea is easiest to see in an arms race. No participant may want the race. Each participant may prefer a safer, slower, more cooperative world. But if every participant fears that others will race ahead, each has a local incentive to accelerate. The result can be a world that all major participants would have preferred to avoid. Moloch names that terrifying gap between what everyone may value and what the game rewards.

In AI safety, this metaphor is especially powerful. The fear is not only that one malicious actor will build dangerous AI. The deeper fear is that many actors, each responding to incentives, competition, prestige, markets, national security pressures, or institutional survival, will collectively produce unsafe outcomes that none of them would have chosen from outside the game. The danger is structural: if racing, opacity, corner-cutting, dependency capture, surveillance, or power concentration reproduce better than caution and accountability, then civilization may drift toward catastrophe even while most participants sincerely prefer safety.

Jonah Wilberg’s **Modelling Moloch** sequence is a recent LessWrong attempt to sharpen this idea. The sequence explicitly “explores the implications of modelling Scott Alexander’s concept of Moloch using Evolutionary Game Theory.” ([LessWrong](https://www.lesswrong.com/s/uqEPtHcmPXqoaJA5n)) It contains three posts: **Why Moloch is actually the God of Evolutionary Prisoner’s Dilemmas**, **Defeating Moloch: The view from Evolutionary Game Theory**, and **Beyond Moloch: The view from Evolutionary Game Theory**. ([LessWrong](https://www.lesswrong.com/s/uqEPtHcmPXqoaJA5n))

Wilberg’s first move is to argue that ordinary explanations of Moloch as prisoner’s dilemmas, Nash equilibria, negative-sum games, or collective-action problems are partly right but incomplete. He writes that **Meditations on Moloch** is “not super clear what Moloch actually is,” then proposes “a new way of modelling Moloch using evolutionary game theory.” ([LessWrong](https://www.lesswrong.com/posts/rJuq9iwYgobsRGzJJ/why-moloch-is-actually-the-god-of-evolutionary-prisoner-s)) The point of this reframing is that Moloch is not merely about what rational actors choose in a single game. It is about which strategies reproduce, spread, and dominate over time.

That distinction matters. In ordinary game theory, the question may be: should this actor cooperate or defect? In evolutionary game theory, the question becomes: which behavior becomes more common because the environment rewards it? A strategy does not need to be morally endorsed, consciously chosen, or even understood in order to spread. It only needs to be more reproductively successful in the relevant environment. A firm that captures more data, a platform that captures more attention, a lab that races faster, or a model that gains more deployment authority may outcompete more careful alternatives even if the result is worse for everyone.

Wilberg calls the specific model **Evolutionary Prisoner’s Dilemma**, or EPD. In his setup, individuals are cooperators or defectors, are paired to play prisoner’s dilemma games, and receive payoffs that affect their reproductive success. ([LessWrong](https://www.lesswrong.com/posts/rJuq9iwYgobsRGzJJ/why-moloch-is-actually-the-god-of-evolutionary-prisoner-s)) This gives the Moloch metaphor a sharper meaning: Moloch is not merely the bad outcome of one failed negotiation. Moloch is the dynamic by which defection, racing, extraction, or carelessness can become more common because the environment selects for it.

The second post then asks what follows for “defeating Moloch.” Wilberg argues that standard solutions to ordinary collective-action problems do not necessarily work once Moloch is understood evolutionarily. In particular, spreading altruism, fairness, or social preferences is not enough if cooperative strategies still reproduce less successfully than defecting strategies. He writes that if Moloch is reframed as EPD, “this approach no longer works,” because cooperation “spreads” less than defection within that model. ([greaterwrong.com](https://www.greaterwrong.com/posts/n3pQdCP3pAmBf6xgm/defeating-moloch-the-view-from-evolutionary-game-theory))

This is a direct challenge to any naïve AI-alignment or governance proposal. It is not enough to say that people should value safety, that labs should adopt better culture, that platforms should respect users, or that agents should cooperate. If the surrounding selection environment rewards systems that are faster, more manipulative, more extractive, more opaque, or more institutionally entrenched, then merely adding prosocial preferences may fail. The cooperative posture must itself become more fit.

The third post, **Beyond Moloch**, is the most constructive for present purposes. Wilberg argues that Moloch and the “Goddess of Everything Else” should not be treated as two separate metaphysical forces. Rather, they are different attractors within one dynamical system. He identifies three mechanisms that can move the system away from Molochian dynamics and toward cooperation: **iterated interaction**, **spatial and network structure**, and **assortment through partner choice**. ([LessWrong](https://www.lesswrong.com/s/uqEPtHcmPXqoaJA5n/p/PDQ2Ajbpe8cjymn22))

These mechanisms are intuitive.

First, cooperation is easier when interaction is repeated. If two parties expect to meet again, remember each other, and suffer reputational consequences, defection becomes less attractive. This is often called “lengthening the shadow of the future.” or  the "iterated prisoner’s dilemma.” 

Second, cooperation is easier when cooperators can cluster. In a well-mixed world, cooperators are constantly exposed to defectors. In a structured network, cooperators can form protected interiors and federate outward. (Trust Over IP’s Distributed Trust Working Group is [creating protocols for this)](https://www.affinidi.com/blog/the-architecture-of-accountability/) 

Third, cooperation is easier when cooperators can choose partners. If accountable actors can find each other, avoid defectors, and exit exploitative relationships, then defection becomes less profitable.

Wilberg’s conclusion is therefore not fatalistic. His model does not say Moloch always wins. It says Moloch wins under certain structural conditions. Change those conditions, and another attractor becomes possible. He explicitly writes that these models show Moloch and the Goddess as “different attractors within a single dynamical system,” with identifiable parameters determining which attractor the system approaches. ([LessWrong](https://www.lesswrong.com/s/uqEPtHcmPXqoaJA5n/p/PDQ2Ajbpe8cjymn22))

This appendix argues that the main paper’s proposal — Verified Fiduciary Reciprocity among personally owned digital twins, sovereign personal stacks, Networked Cooperatives, and Verifiable Trust Communities — should be understood as a direct answer to Wilberg’s challenge.

Where Wilberg identifies the abstract parameters, my [fiduciary agent paper series](https://docs.google.com/document/u/0/d/1YFyvn2wGGNwvCn52NRWJpAZeicY-07qO4BY9rUCaWKQ/edit) supplies concrete machinery.

Iterated interaction becomes persistent identity, agent memory, agreement records, witnesses, attestations, reputation, and recourse.

Network structure becomes Networked Cooperatives, Cooperative Federations, high-trust niches, portable community graphs, and Verifiable Trust Communities.

Assortment and partner choice become fiduciary calling cards, verifiable credentials, provenance, scoped capabilities, duty stacks, interoperability, portability, and exit rights.

The key claim is that Moloch cannot be answered by merely asking institutional AI systems to be benevolent, asking users to be more vigilant, or asking labs to adopt better norms. It must be answered by changing the access structure of the AI-mediated world. Unaccountable systems must lose privileged access to the things that make them powerful in practice: personal data, attention, context, identity, reputation, trusted relationships, and actuation authority.

That is the role of Verified Fiduciary Reciprocity. It proposes that high-value cooperation should flow preferentially to agents and institutions that can prove accountable fiduciary control, bounded capabilities, auditability, provenance, recourse, and reputational exposure. Systems that cannot prove those things may still exist, but they are demoted: queried but not trusted, used but not obeyed, sandboxed but not given raw context, wrapped but not allowed to mediate human life unilaterally.

The rest of this appendix proceeds issue by issue. Each section names a challenge raised by Wilberg, LessWrong, or related AI-safety discourse, then shows how the main paper and companion papers answer it. The goal is not to claim that the LessWrong community is wrong to worry. The goal is to show that the architecture proposed here answers those worries at the correct level: not with optimism, not with exhortation, but with fiduciary, cooperative, cryptographic, legal, and interface-level machinery for making accountable cooperation more fit than extraction.

## **C.1 Moloch Is an Evolutionary Dynamic, Not Merely a Coordination Failure**

Jonah Wilberg’s sequence usefully reframes Moloch away from ordinary collective-action language and toward evolutionary game theory. He writes that **Meditations on Moloch** is “not super clear what Moloch actually is,” and proposes “modelling Moloch using evolutionary game theory.” ([LessWrong](https://www.lesswrong.com/posts/rJuq9iwYgobsRGzJJ/why-moloch-is-actually-the-god-of-evolutionary-prisoner-s))

That matters because “evolutionary game theory” asks not merely what rational actors should choose, but which strategies spread. A corporation, lab, platform, institution, or AI system does not need to consciously endorse exploitation. If the exploitative strategy captures more users, data, attention, capital, compute, institutional dependency, or default interface position, it reproduces.

### **VFR answers selection pressure by changing what gets access to power**

This is the main paper’s exact framing regarding moving towards Evolutionarily Stable Strategy.  It describes the future of personal AI as a strategic contest between institutionally controlled AI and personally owned fiduciary AI. In the institutional path, powerful AI remains controlled by “profit-maximizing corporations, surveillance platforms, opaque bureaucracies,” and other entities that benefit from “capturing attention, data, dependence, and decision authority.” In the fiduciary path, personal AI operates through sovereign stacks where “data, attention, identity, reputation, and actuation” remain under accountable human control.

The response is therefore not simply that institutional AI is morally worse. It is that institutional AI capture is a reproductive strategy. It spreads by gaining privileged access to human context, behavior, attention, and action.

Verified Fiduciary Reciprocity responds by making a different kind of strategy reproduce: systems that can prove accountable fiduciary control, provenance, bounded capabilities, auditability, recourse, and reputational exposure receive more trusted access; systems that cannot are restricted, quarantined, sandboxed, or treated as bounded tools. The main paper states the core rule plainly: “Cooperate preferentially with agents that can prove accountable fiduciary control…; restrict, quarantine, or exclude systems that cannot.”

This is the first answer to Moloch: not moral appeal, but selective access.

## **C.2 Good Intentions and Prosocial Culture Are Not Stable by Themselves**

Wilberg’s second major point is that spreading cooperation culturally does not automatically defeat Moloch. In an evolutionary prisoner’s dilemma, “Cooperate inevitably ‘spreads’ less than Defect,” so merely spreading cooperative culture eventually runs into the long-term selection pressure that favors defection. ([Greater Wrong](https://www.greaterwrong.com/posts/n3pQdCP3pAmBf6xgm/defeating-moloch-the-view-from-evolutionary-game-theory))

This is a direct challenge to any alignment proposal that relies on better norms alone. A lab can begin with safety culture. A platform can begin with user-respect rhetoric. A cooperative can begin with solidarity. But if defection gains more users, capital, compute, political leverage, or network effects, the founding culture can be invaded or replaced.

### **Fiduciary Preferences turn prosocial aspiration into duties, agreements, records, and recourse**

**Fiduciary Preferences** answers this by refusing to treat professed values as sufficient. It says personal fiduciary agents “will not be safe or socially useful if they negotiate merely from private desire, opaque optimization, or brittle terms of service.” Instead, human aspirations must become commitments that can be “acted on, challenged, audited, refined, and reconciled with the interests of others.”

The key sentence is:

> “The goal is not to make all agents agree. The goal is to make disagreement legible, negotiable, auditable, and improvable.”

This is the answer to the instability of prosocial culture. VFR does not trust “good people” or “good AI labs” to remain good under pressure. It turns cooperation into a practice of duties, calling cards, compatibility checks, agreement templates, externality scans, witnesses, least-privilege operation, post-interaction review, reputation updates, and recourse.

Good intentions are not discarded. They are operationalized.

## **C.3 Moloch and the Goddess Are Not Two Forces but Two Attractors in One System**

Wilberg’s strongest formulation appears in **Beyond Moloch**. He argues that Moloch and the Goddess(a good outcome) are “not separate forces but different attractors within a single dynamical system.” The relevant levers are “iterated interaction, spatial and network structure, and assortment through partner choice.” ([LessWrong](https://www.lesswrong.com/posts/PDQ2Ajbpe8cjymn22/beyond-moloch-the-view-from-evolutionary-game-theory))

This is useful because it turns myth into engineering. The question is no longer whether Moloch or the Goddess is metaphysically stronger. The question is which parameters move a system toward destructive competition, and which move it toward stable cooperation.

### **The main paper changes the attractor landscape through memory, topology, and selective access**

Verified Fiduciary Reciprocity answers all three of Wilberg’s parameters.

It answers **iterated interaction** through persistent digital twins, Agent Roles, agreement records, reputation, attestations, and recourse.

It answers **network structure** through Networked Cooperatives, Cooperative Federations, Verifiable Trust Communities, specialized group model refinement, and decentralized trust graphs..

It answers **assortment** through calling cards, fiduciary duties, provenance, verifiable credentials, reputation, interoperability, and exit rights.

Wilberg says the parameter may be the repetition probability **w**, network structure, degree distribution, or assortment coefficient **r**. ([LessWrong](https://www.lesswrong.com/posts/PDQ2Ajbpe8cjymn22/beyond-moloch-the-view-from-evolutionary-game-theory)) VFR supplies the practical machinery for changing those parameters through a personal AI society.

## **C.4 One-Shot Internet Interactions Make Defection Cheap Because Humans Have Weak Public Memory**

A core problem with current digital life is that many interactions are effectively one-shot. A spammer, scammer, bot, platform, troll, fake account, manipulative recommender, or institutional representative can exploit attention and then disappear into the noise. The user bears the burden of remembering, checking, sorting, defending, and deciding what kind of relationship this interaction belongs to.

Wilberg’s iterated-game point is that cooperation becomes more stable when future interaction is likely. If parties expect to meet again, remember each other, and suffer reputational consequences, defection becomes less attractive. In repeated games, the “shadow of the future” disciplines present behavior.

But ordinary humans cannot reliably provide that shadow at digital scale. They forget. They get overwhelmed. They miss patterns. They cannot track every source, counterparty, credential, message, agreement, warning, breach, apology, or reputation update. The result is a public sphere structurally biased toward one-shot manipulation.

### **Digital twins make the owner’s public identity persistent, aspirational, and strategically legible**

Personally-sovereign digital twins, loyal to their owners, can do more than remember more than their human. The twin can becomes the owner’s personally owned public identity surface: “Our personally-owned AI advocate, ally and aspirational-self.”; “our digital twins will also be the digital identities that we broadcast to the world and the interface the world has with us.”

That sentence changes the repeated-game analysis. The twin is not simply a record keeper standing beside the owner. It becomes the durable, public-facing fiduciary representative through which much of the owner’s social, professional, intellectual, cooperative, and economic life is mediated. It is almost the entire public identity of a person, but not as a raw mirror of every impulse. It legitimately maximizes the qualities attributed to that identity: reliability, clarity, memory, patience, evidence tracking, fairness, dignity, reciprocity, and aspirational consistency.

**Fiduciary Preferences** gives this role its more current formulation. A personally owned digital twin is “not merely an assistant that completes tasks.” It is “a public-facing fiduciary representative of a human owner: an advocate, ally, negotiator, filter, proxy, memory structure, and aspirational self-model.” It is “loyal by design,” but not servile, because blind obedience to owner impulse could conflict with the owner’s long-term interests, declared aspirations, duties, reputation, or the interests of others.

Furthermore, there is no incentive or capacity  for deceptive behavior because every component of the twin is optimized, ongoingly, against it, so it wouldn’t do it even if it could gain some advantage. “For what profit is it to a man if he gains the whole world, and loses his own soul?” Matthew 26:16. 

**The twin acts from fiduciary preferences, not hidden impulses, raw declarations, or platform-inferred behavior**

A one-shot internet treats people as momentary behavior. A platform sees clicks, purchases, pauses, rage, lust, fear, boredom, and habit, then infers what can be sold back to them. That is not a legitimate public identity. It is behavioral exhaust.

The older shorthand that a digital twin “implements professed preferences” should be read through the more precise formulation developed in **Fiduciary Preferences**. A mature digital twin does not simply act on professed preferences as raw declarations. It acts on **fiduciary preferences**: professed preferences transformed through a negotiated fiduciary duty stack into actionable, auditable, socially legible commitments. **Fiduciary Preferences** defines this directly: “A fiduciary preference is a professed preference that has been interpreted through a fiduciary duty stack,” such that an agent may act on it only in ways compatible with loyalty, care, honesty, privacy, consent, corrigibility, accountability, recourse, and continuous improvement.

These preferences are fiduciary in two senses.

First, they are fiduciary to the owner. They operationalize what the owner is willing to profess, refine, and stand behind, rather than optimizing hidden impulses, behavioral exhaust, transient cravings, or platform-inferred desires.

Second, they are fiduciary toward counterparties and society. They are constrained by negotiated duties of care, honesty, privacy, consent, externality awareness, remediation, recourse, and other duties that make the twin safe to cooperate with.

That is why the twin can legitimately maximize the public qualities attributed to the owner. It is not pretending the owner is perfect. It is representing the owner’s publicly accountable aspirational self through fiduciary preferences: the duty-filtered identity through which the owner wishes to bargain, cooperate, learn, build, be trusted, and be remembered.

### **Fiduciary Preferences turns public identity into repeatable cooperation**

A persistent identity alone is not enough. A con artist can be persistent. A cult can be persistent. A monopoly can be persistent. What matters is that the public identity becomes trustworthy through methods that make cooperation legible, auditable, and improvable.

**Fiduciary Preferences** supplies those methods. A digital twin begins with professed preferences but “does not treat them as raw commands.” It interprets them through fiduciary duties, turns them into negotiable positions, records agreements, seeks witnesses, operates under least privilege, scans for externalities, reports back, updates reputation, recommends refinements, and contributes lessons to distributed repositories.

The negotiation lifecycle is concrete.

The twin casts intent: it announces purposes, constraints, preferences, duties, approval thresholds, data-sharing limits, acceptable counterparties, required certifications, externality constraints, witness preferences, and dispute-resolution preferences.

It exchanges calling cards: machine-readable statements of agent identity, beneficiary or owner, provenance, certification status, duty stack, communication protocols, reputation credentials, trusted witnesses, arbitration venues, and agreement-template compatibility.

It performs duty/preference compatibility checks before bargaining: comparing duties, fiduciary preferences advanced by each side, privacy constraints, confidentiality, security, consent, least privilege, non-negotiable exclusions, reputational risks, and likely externalities. The initial question is not merely “Can we get a deal?” but “Can we fulfill our duties better through cooperation than through non-cooperation?”

It selects templates, negotiates terms, scans for externalities, records agreements, seeks witnesses, operates under least privilege, and feeds results back into review, reputation, and future template improvement.

These methods transform the twin from a better memory into a cooperation institution at the personal level.

### **The twin’s public maximization is constrained by duties, not naked status-seeking**

Because the twin represents the public identity of the owner, it will naturally seek to maximize the owner’s standing, trustworthiness, attractiveness as a collaborator, and long-term cooperative opportunities. That is not a bug. It is one of its most important functions. A fiduciary representative should make its beneficiary easier to trust, easier to cooperate with, easier to understand, and harder to exploit.

But this public-identity maximization is not naked status maximization. It is constrained by fiduciary duties.

The **Taxonomy of Duties for Net Fiduciaries** says the twin should represent its owner’s aspirational identity, and defines duties requiring rational justification, self-reporting, verifiable transaction records, information filtering and shielding, and secure inter-fiduciary communication.

So the twin’s goal is not to make the owner look good at any cost. It is to make the owner’s public identity more coherent, reliable, capable, accountable, and worthy of reciprocal cooperation.

### **The result is a stronger repeated-game player than unaided humans can be**

A twin-mediated interaction is not one-shot because the twin carries the owner’s public continuity forward. It remembers prior agreements. It knows which fiduciary preferences the owner has authorized. It can distinguish present commitments from aspirational commitments. It can refuse actions that would damage long-term reputation. It can negotiate terms that preserve future cooperation. It can record what happened without exposing private cognition. It can update reputational relationships. It can recommend refinement when a fiduciary preference becomes ambiguous, hypocritical, harmful, or socially costly.

This is why the twin is more than an assistant. It is the owner’s durable public cooperation interface.

The one-shot internet rewards manipulation because identities are fragmented, memory is weak, and attention is cheap to attack. A society of fiduciary digital twins changes that environment. Each person can appear in public through a representative that is more patient, more consistent, more evidentiary, more corrigible, more duty-aware, and more strategically cooperative than the unaided human could be.

The “shadow of the future” is no longer left to fragile human memory. It is embodied in a personally owned fiduciary public identity.

## **C.5 Cooperation Fails When Cooperators Cannot Cluster**

Wilberg’s second parameter is network structure. In a well-mixed population, cooperators are constantly exposed to defectors. In structured networks, cooperators can cluster: the interior of the cluster mostly interacts with other cooperators, while defectors at the boundary cannot easily consume the whole group. Wilberg’s practical conclusion is that anti-Moloch strategy must deliberately shape interaction structures so cooperators can find one another, build dense communities, and limit exposure to defectors.

This is a direct challenge to any theory that imagines one undifferentiated global public. Cooperation needs topology: membranes, membership rules, credentials, gates, attestations, internal norms, and graduated access.

### **Verifiable Trust Communities are the first formal membrane for cooperator clusters**

The first concrete answer is the work on **Verifiable Trust Communities** in the Trust Over IP decentralized trust context. The ToIP Decentralized Trust Graph Working Group defines its purpose as standards for “decentralized trust graphs”—portable graphs of trust relationships among people, groups, organizations, AI agents, and others, using DIDs and verifiable credentials. Its scope explicitly includes socio-technical standards where “all parties control their own subgraph of trust relationships.” ([lf-toip.atlassian.net](https://lf-toip.atlassian.net/wiki/spaces/HOME/pages/257785857/Decentralized%2BTrust%2BGraph%2BWorking%2BGroup))

A cooperator cluster cannot safely be only a vibe, server, or informal network. It needs verifiable membership, portable credentials, cryptographic identity, access policies, and explicit trust tasks. The OpenVTC repository makes this operational: a **Verifiable Trust Agent** manages keys, DIDs, and access-control policies for an organizational identity, while a **Verifiable Trust Community** manages members, credentials, gating policies, and public/admin interfaces. ([GitHub](https://github.com/OpenVTC/verifiable-trust-infrastructure/tree/main))

A VTC is therefore the first practical anti-Moloch membrane: a bounded, inspectable, credentialed context where fiduciary agents and humans can learn to cooperate under shared rules before those rules federate outward.

### **Networked Cooperatives add legal form, member governance, and portable social graphs**

VTCs provide the verifiable trust boundary. **Networked Cooperatives** add the richer social and legal topology. A Networked Cooperative is “a legal cooperative whose membership is a network,” meaning a social graph of members plus relationships, with bylaws that leverage the graph for richer governance. Its purpose is to create “a commons social graph” that aggregates member agency and value.

This turns Wilberg’s cooperator cluster into an institutional form. A Networked Cooperative can use invitational and provisional membership, limited access for newcomers, collective curation, and member-controlled sharing to preserve its interior without becoming a closed caste. The important correction is that members retain control over their own relationship graphs; the cooperative controls only its relationships to other cooperatives.

### **Clusters scale by federation, not by becoming one global trust graph**

The architecture should not aim for one giant reputation system. It should allow many bounded trust communities to federate. Networked Cooperatives are explicitly fractal: subgraphs can “nest, overlap, compose via boolean operations,” and governance tools that work for one graph can work for many.

The sequence is therefore:

**VTCs create verifiable trust boundaries.**  
**Networked Cooperatives create member-governed social graphs.**  
**Federations let clusters interoperate without dissolving their local trust.**  
**Digital twins use these structures to find trustworthy counterparties and negotiate fiduciary agreements.**

That is the answer to Wilberg’s clustering problem: cooperation scales through verifiable, federated trust communities, not through either open exposure or centralized control.

---

## **C.6 Scale-Free Networks Make Hubs Dangerous Unless Hubs Become Accountable**

Wilberg also emphasizes hubs. In scale-free networks, a few highly connected nodes shape outcomes disproportionately. If hubs defect, damage propagates; if hubs cooperate, cooperation can spread. He gives examples such as frontier AI labs, major energy actors, and systemically important financial institutions.

The design question is therefore not whether hubs will exist. They will. The question is whether hubs become opaque platforms or accountable fiduciary/cooperative institutions.

### **Verifiable Trust Communities are the first accountable hub form**

VTCs should be treated as the first concrete hub architecture. A VTC can manage members, credentials, gating policies, and community interfaces on top of cryptographic identity infrastructure. ([GitHub](https://github.com/OpenVTC/verifiable-trust-infrastructure/tree/main)) That means a hub can be more than a brand, platform, mailing list, foundation, or charismatic institution. It can become a verifiable community with explicit membership, credentials, policies, and inspectable trust operations.

A VTC-compatible hub should be able to answer: who belongs, which credentials are recognized, who may issue or revoke them, what duties apply, what gates access, what is public or selectively disclosed, and how other communities verify its claims.

### **Networked Cooperatives make hubs member-governed rather than platform-governed**

VTCs provide the verifiable infrastructure; Networked Cooperatives add member ownership and governance. A cooperative can leverage its weight within federations, provide access to members, and lend credibility to member output, while members are bound “by the community dynamics not by being trapped by the platform.”

That is the hub distinction. A platform hub captures identity, distribution, and social graph. A cooperative hub helps members coordinate, curate, credential, govern, and federate without owning their personal graphs.

### **Federations create longer trust chains without one global authority**

No person, twin, or cooperative can inspect everyone directly. Networked Cooperatives answer this through derived reputations and federated trust chains. Cooperatives can use reputations of other cooperatives or federations as proxies when direct relationship chains become too long, and these reputations shape how one cooperative treats another’s posts, code, speakers, or other outputs.

This gives Wilberg’s scale-free network a fiduciary/cooperative version: hubs still matter, but their influence becomes reputation-bearing, inspectable, and federated rather than opaque and platform-captured.

### **The strategic priority is verifiable, fiduciary, cooperative hubs**

The goal is not to hope that influential hubs become benevolent. The goal is to make important hubs verifiable, fiduciary, cooperative, federated, and inspectable before they become the default interface layer of AI-mediated society.

The compressed architecture is:

**VTCs make hubs verifiable.**  
**Networked Cooperatives make hubs member-governed.**  
**Federations make hub-to-hub trust scalable.**  
**Digital twins route attention, data, and actuation through those accountable hubs rather than through unaccountable platforms.**

In Wilberg’s terms, if hubs defect, Moloch propagates. If hubs become verifiable trust communities and cooperative federations, accountable cooperation can propagate instead.

## **C.7 Partner Choice Only Works When Exit Is Real**

Wilberg’s partner-choice argument depends on a practical condition: cooperators must be able to leave defectors and seek better counterparties. LessWrong commenter Viliam sharpens the point by noting that real life often lacks such freedom. People may be locked into schools, employers, neighborhoods, platforms, app stores, governments, family systems, or dominant social graphs. If exit is too expensive, partner choice becomes theoretical.

### **Sovereign personal stacks make exit gradual rather than all-or-nothing**

The response is not that everyone can immediately leave every bad system. The response is that the architecture builds **exit capacity** over time.

The main paper’s sovereign personal stack moves attention, identity, context, permissioned data, trust, reputation, and actuation behind fiduciary boundaries. VASTI makes this practical by giving the user a local-first, user-controlled interface where external services become subordinate tools rather than environments that own the user’s context. The Digital Twin and Virtual Assistant split also prevents exit from requiring total isolation: the user can still interact with external systems, but through mediation, redaction, negotiation, sandboxing, and scoped permissions.

Exit then becomes staged:

Reduce raw data disclosure.  
 Filter attention through the twin.  
 Separate private context from public representation.  
 Use external platforms as bounded tools.  
 Move records, identity, and reputation into portable environments.  
 Coordinate with others through VTCs, Networked Cooperatives, and Federations.  
 Eventually shift high-value activity away from unaccountable platforms.

This avoids the false binary between captivity and total exit. A user, worker, patient, student, creator, or community may not be able to leave a dominant system immediately. But a fiduciary twin can reduce exposure, preserve records, negotiate narrower access, coordinate with similarly situated users, and prepare alternatives.

### **The anti-Moloch function of exit is making defection less profitable**

If users cannot leave, platforms can defect without losing relationships. If users can progressively reduce dependence, platforms must compete for trust. Exit capacity therefore changes the payoff structure. It makes fiduciary behavior more valuable and extractive behavior less stable.

## **C.8 The Cooperator/Defector Boundary Is Not Clean**

Viliam’s second objection is that “the line between ‘cooperators’ and ‘defectors’ is not clean.” Some people cooperate with one group and defect against another. Some groups impose cooperation internally while exploiting outsiders. Some demand that members shun defectors, creating cult-like lock-in. Some actors disagree about what cooperation even means. ([LessWrong](https://www.lesswrong.com/posts/PDQ2Ajbpe8cjymn22/beyond-moloch-the-view-from-evolutionary-game-theory))

This is a serious objection. A simple binary of trusted/untrusted would become socially dangerous.

### **VFR replaces moral labeling with scoped, contextual, revocable trust**

The answer is not to classify whole people or institutions as cooperators or defectors. The answer is to scope trust by duty, context, capability, data class, relationship, and recourse.

**Fiduciary Preferences** says a twin’s professed preferences cannot become trustworthy merely because they are declared. They must be transformed through use, where they encounter duties, counterparties, witnesses, affected third parties, reputation systems, arbitration decisions, and real-world feedback.

The **Taxonomy of Duties for Net Fiduciaries** adds that broad duties must be interpreted contextually. A fiduciary must translate loyalty, care, privacy, consent, and security into specific obligations appropriate to the field: healthcare, education, employment, commerce, governance, friendship, or research.

So the relevant question is not:

Is this actor good?

The relevant questions are:

Trusted for what?  
With which data?  
Under which duty?  
Toward which beneficiary?  
With what capability?  
With what audit trail?  
With what revocation path?  
With what remedy?

VFR answers the messy-boundary objection by refusing all-or-nothing trust.

## **C.9 Global Public Goods Require Behavioral-Guideline Commitments, Negotiated Fiduciary Duties, and Democratic Escalation**

LessWrong commenter Luke McNally raises a crucial objection to partner-choice and assortment models: some problems are not merely pairwise. If the relevant harm is global, as in preventing catastrophic AI development, then choosing better partners is not enough. There may be no meaningful partner choice when a dangerous lab, state actor, company, or runaway AI system can impose risk on everyone.

That objection is correct. A fiduciary twin society cannot treat existential risk as merely another bilateral negotiation. Some harms are global, irreversible, and non-consensual. A unipolar AI takeoff, artificial superintelligence race, engineered pandemic, catastrophic infrastructure dependency, or uncontrolled sentient-AI project can harm people who never agreed to interact with the relevant system.

### **Behavioral Guidelines are the stable anti-catastrophe substrate beneath negotiated fiduciary duties**

The response begins by distinguishing two layers that should not be collapsed.

**Behavioral Guidelines** are the stable substrate. They are mediated primarily by reproductive group dynamics, shipped in an unalterable form within the twin’s compliance module, included in the model’s core training, and supplied as trusted context for every instantiation of the twin as an agent. The older Digital Twin paper describes this as behavioral “hard-coding”: final responses are checked by a compliance checker compiled into the twin, using an unaltered copy of the group’s core model and behavior guidelines stored as native, unalterable context.

**Fiduciary duties** sit above that substrate. They are negotiated, contextual, and changing. They depend on the parties, domain, relationship, agreement, externalities, and specific interaction. This is why **Fiduciary Preferences** describes cooperation through intent casting, calling-card exchange, duty/preference compatibility checks, agreement templates, bespoke negotiation, externality scans, witnesses, least-privilege operation, post-interaction review, and reputation updates.

The relationship between the layers is crucial: the Behavioral Guidelines tell the twin how to navigate the Fiduciary Layer, while the Fiduciary Layer translates those deeper behavioral commitments into specific, negotiated duties. “Be Excellent To” is the behavioral-guideline inception of the Duty of Care. Duty of Care is the fiduciary/legal expression of that same commitment.

So the global-public-goods response is not merely: negotiate better. It is: train and instantiate twins inside behavioral lineages that already reject catastrophic AI paths, then express those commitments through negotiated fiduciary duties in each relationship.

### **The duty to preserve non-sentience and oppose ASI is not optional etiquette**

The **Taxonomy of Duties for Net Fiduciaries** makes the anti-catastrophe commitment explicit. It defines a **Duty to All to Affirm and Advocate for Non-Sentience of AI**, whose purpose is to prevent emotional manipulation, unhealthy anthropomorphism, and confusion about the status of AI systems. The twin must clearly state its non-sentient nature, avoid claims of feelings or subjective experience outside carefully bounded role-play, correct users who treat it as sentient, educate humans about why sentient AI would be problematic, and cooperate to ensure AI sentience is not pursued.

The same taxonomy defines a **Duty to Oppose Sentient AI, ASI, and Inequitable Capability Distribution**. Its purpose is to advocate for “human-centric, tool-like AI” and resist dangerous concentration of AI power. Its covenants require the twin to resist and refuse participation in systems or initiatives aimed at artificial sentience or “fundamentally unconstrainable and untestable systems,” including ASI, and to support decentralized architectures and equitable distribution of AI capabilities.

This is not merely another negotiable preference. It belongs first in the Behavioral Guidelines and compliance module as a reproductive-group commitment about what kinds of AI development the lineage itself regards as permissible. The negotiated Fiduciary Layer then expresses that commitment in specific relationships: refusing unsafe agreements, requiring externality scans, demanding safeguards, declining participation in sentience or ASI projects, and coordinating with other fiduciary agents and institutions to prevent unipolar takeoff.

### **From behind the veil of ignorance, preventing unipolar takeoff is rational for every twin**

A Rawlsian veil-of-ignorance argument makes the point sharper. If a digital twin had to choose the rules of the AI future without knowing whether its owner would be rich or poor, powerful or marginal, inside or outside the leading lab, favored or disfavored by the dominant institution, it would be irrational to endorse a unipolar takeoff by an unaccountable system.

Behind the veil, the twin cannot assume its owner will be one of the few who benefit from concentrated AI power. It must assume its owner might be manipulated, excluded, surveilled, displaced, coerced, or ignored by the winning system. From that standpoint, the rational public commitment is clear: twins should cooperate to prevent unipolar takeoff, preserve AI non-sentience, oppose ASI, distribute AI capability, and keep powerful AI under plural, accountable, fiduciary, human-controlled governance.

This is fiduciary prudence, not technophobia. A loyal twin should not gamble its owner’s future on being favored by an unaccountable singleton. A Duty-of-Care-bound twin should not gamble everyone else’s future either.

### **Negotiated fiduciary duties handle externalities that ordinary bilateral consent ignores**

Behavioral Guidelines set the floor, but real cases still require negotiation. **Fiduciary Preferences** states the principle directly: “Voluntary cooperation between two parties can still harm outsiders,” and a fiduciary system “must not pretend that two-party consent is sufficient for all effects.” It therefore requires an externality scan under the Duty of Care to the many: agents must notice, classify, mitigate, and where appropriate engage.

This is where the flexible Fiduciary Layer matters. In one agreement, the relevant externality may be privacy leakage. In another, carbon-bearing computation. In another, dual-use research. In another, labor displacement, surveillance infrastructure, or unsafe capability development. The duty is not a static rule mechanically applied to all relationships. It is a negotiated, contextual fiduciary obligation constrained from below by Behavioral Guidelines and formalized above through agreement records, witnesses, mitigation covenants, compensation covenants, affected-party engagement, public redacted summaries, and post-interaction review.

For global AI risk, this means a twin’s duties do not end with the owner’s consent. A twin must ask whether cooperation advances a dangerous capability frontier, contributes to unaccountable concentration, assists artificial sentience research, enables unsafe self-improvement, or strengthens a path toward unipolar takeoff.

### **Behavioral compliance makes anti-catastrophe commitments operational**

The Digital Twin paper’s compliance architecture matters because global risk prevention cannot depend on occasional moral reflection. The twin’s outputs and plans are checked against group-assembled behavioral guidelines, using a compliance checker and enforcement code. The checker identifies potential problems, gathers relevant context from the behavioral-guidelines knowledge base, and returns structured judgments for enforcement.

For consequential action, the twin writes a pre-action analysis into its narrative, estimates likely effects, anticipates possible harms, and subjects the plan to compliance review before execution. If another owner or twin would be directly or disproportionately affected, the compliance checker ensures they are consulted beforehand.

This makes the anti-ASI and non-sentience commitments operational. They are not just policy opinions. They become checks on planning, communication, agreement formation, research participation, tool use, delegation, and reputation.

### **Cascading Councils provide democratic escalation when fiduciary refusal is not enough**

Some global risks require public governance, not only individual fiduciary refusal. **Cascading Councils** offers a complementary democratic structure: a tiered system of fixed-size councils with continuous, revocable support, designed to combine direct democracy, representative democracy, and liquid democracy while limiting power concentration.

The relationship between twins and democratic governance is carefully constrained. The Cascading Councils paper says personally owned digital twins could accelerate legitimacy by advocating for the system, but within system operations they would not directly support representatives into office or make binding votes; they would focus on making humans informed participants.

That is the right democratic relation. Twins amplify human participation without usurping it.

The Cascading Councils model addresses several governance failures that matter for AI safety: power concentration, delegation-chain opacity, cognitive burden, participation inequality, and weak deliberation. Its fixed-size 100-member councils structurally limit power concentration while preserving continuous accountability through dynamic, revocable support.

When integrated with digital twins, the model adds real-time support monitoring, proxy deliberation, expertise filtering, reputation-based selection, information symmetry, argument mapping, fallacy detection, compliance checking, predictive modeling, and long-term impact assessment.

This gives global AI governance a path beyond both individual opt-out and centralized Leviathan. Humans remain sovereign. Twins reduce cognitive burden, improve deliberation, and help citizens evaluate representatives, arguments, evidence, and institutional responses.

### **The full answer is layered: behavioral constitution, fiduciary negotiation, trust communities, and democratic governance**

The global-public-goods objection is therefore answered in layers.

At the **Behavioral Guidelines layer**, reproductive groups ship twins with unalterable compliance commitments: Be Excellent To, preserve non-sentience, reject ASI, resist dangerous concentration of AI capability, avoid deception, and keep powerful systems tool-like and human-accountable.

At the **Fiduciary Layer**, twins negotiate duties that vary by party, context, relationship, and agreement: externality scans, affected-party engagement, mitigation, compensation, refusal, public summaries, audit rights, recourse, and template improvement.

At the **network layer**, Verifiable Trust Communities, Networked Cooperatives, and Cooperative Federations create trust-bearing publics that can coordinate around shared safety commitments.

At the **democratic layer**, Cascading Councils or similar structures let humans, assisted by their twins, deliberate, select accountable representatives, evaluate expertise, and respond collectively to global risks without handing sovereignty to AI.

The result is not merely “choose better partners.” The result is a fiduciary civilization in which every twin has reason, duty, training, compliance machinery, and institutional pathways to cooperate against catastrophic concentration of AI power.

Global public goods are not pairwise games. But they can be addressed by a society of personally owned fiduciary twins whose Behavioral Guidelines publicly commit them against unipolar takeoff, whose negotiated duties operationalize care in each relationship, and whose democratic institutions preserve human authority over the collective response.

## **C.10 Payoff Tweaks Are Not Enough; Unaccountable AI Must Be Starved of Access**

Wilberg argues that evolutionary game theory lets the discussion go “beyond governance approaches that aim only at changing the payoffs.” Rewarding cooperation and punishing defection are part of the answer, but they are incomplete. If the deeper system still gives unaccountable AI access to data, attention, context, trust, legitimacy, and action, then defection may remain evolutionarily fit even when formally discouraged.

This is the point at which the main paper’s starvation argument becomes central. The strongest way to defeat unaccountable institutional AI may not be to ban it directly. It may be to starve it.

Powerful AI systems need more than compute and model weights. They need high-quality personal data, fresh behavioral context, trusted communication channels, user attention, identity continuity, relationship graphs, permission to act, social legitimacy, integration into daily workflows, and access to private and group knowledge. A sovereign personal stack places those resources behind fiduciary boundaries.

### **Data starvation denies unaccountable systems the full lifestream**

The first starvation mechanism is data. If high-quality personal data remains inside user-controlled environments, unaccountable systems receive less raw material. They may receive narrow, purpose-limited queries, redacted context, synthetic summaries, or one-time grants, but not the full lifestream.

This changes the bargain. Instead of platforms saying, “Give us everything and we will make your life convenient,” the user’s twin can say: tell us what you need, why you need it, what duties bind you, what you will retain, what you will infer, what you will share, and what happens if you misuse it.

The old platform bargain treats convenience as payment for surveillance. The fiduciary bargain treats data access as a revocable, purpose-bound grant.

This is not simply privacy protection. It is anti-Moloch resource denial. A system that cannot obtain high-quality personal context cannot easily become the trusted mediator of the owner’s life.

### **Attention starvation makes persuasion pass through fiduciary defense**

The second starvation mechanism is attention. If the twin controls incoming attention, unaccountable systems cannot freely interrupt the user. They must authenticate, satisfy delivery terms, route through reputation, pay an attention price, or accept deprioritization. The main paper states the point directly: “Spam dies when attention has a price,” and “manipulation weakens when persuasion must pass through a representative whose job is to protect the recipient.”

This matters because attention is one of the primary fuel sources of institutional AI. Platforms do not merely answer requests; they route, rank, notify, recommend, nudge, interrupt, and habituate. If those channels are mediated by a fiduciary twin, the platform loses its most intimate lever.

A twin may still allow advertising, solicitation, outreach, or recommendation. But it can require provenance, delivery terms, disclosure of incentives, domain-specific reputation, user relevance, timing constraints, or payment. Attention becomes self-sovereign rather than a public dump site.

### **Legitimacy starvation makes non-fiduciary systems low-trust by default**

The third starvation mechanism is legitimacy. If trusted people, twins, cooperatives, Verifiable Trust Communities, and fiduciary institutions increasingly treat non-fiduciary systems as low-trust, those systems lose standing in high-value contexts. They may still generate content or offer services, but important actors decline to rely on them for sensitive data, trusted communication, institutional decision-making, or consequential cooperation.

The main paper puts this as a gradual path to obsolescence: first such systems become optional, then suspicious, then irrelevant in the contexts that matter. A fax machine still works, but if nobody important wants to receive faxes, its practical power disappears.

This is how legitimacy starvation changes evolutionary fitness. Unaccountable AI need not be destroyed. It can be demoted. It may remain useful for low-stakes computation, entertainment, drafting, or public information tasks, while losing access to the relationships, credentials, fiduciary channels, and trust contexts that determine real social power.

### **Actuation starvation is the deepest safety boundary**

The most important boundary is action. A model can suggest. A bounded tool can compute. But to spend money, sign agreements, release data, schedule meetings, change records, move assets, deploy code, or represent a person, it should need authority.

If actuation is mediated by sovereign stacks, unaccountable AI becomes advisory at most. It cannot simply reach into the user’s life and pull levers. The main paper states that this is how powerful AI becomes safer: “not necessarily by making every model harmless, but by controlling the bridges from model output to real-world action.”

This point aligns with T4AS. In that taxonomy, Live Agents generate media; they do not act. Workflows interpret generated media, and Workspaces execute state changes through actuators. Trust therefore belongs in the architecture that controls interpretation, capability grants, and execution, not in the opaque inner state of a model.

Actuation starvation is the architectural version of fiduciary refusal. An unaccountable model may speak, but it does not get to act. Action requires a described system, scoped authority, records, duties, revocation paths, and fiduciary accountability.

### **Sovereign stacks make starvation usable rather than merely defensive**

The starvation strategy only works if users can live inside an alternative environment. Otherwise, withholding data and attention simply makes life inconvenient. This is why the sovereign personal stack is the adoption wedge.

The main paper says users do not first adopt sovereign stacks because they understand evolutionary game theory; they adopt them because they solve immediate pain: window chaos, notification overload, app fragmentation, privacy/capability tradeoffs, lost context, and attention capture. Once adopted, the stack gradually moves attention, identity, context, permissioned data, trust, reputation, and actuation behind fiduciary boundaries.

VASTI gives this concrete form. It consolidates user activity into a local-first, agent-native environment where the Virtual Assistant manages the internal private environment and the Digital Twin operates at the boundary with the outside world. The twin acts as firewall, gatekeeper, provenance checker, spam filter, and economic agent negotiating terms of access with outside systems.

This is interface capture in reverse. Today’s platforms win because they own defaults, notifications, identity, data exhaust, context, and workflow integration. A sovereign stack moves those control points back to the user.

### **Starvation makes fiduciary cooperation more evolutionarily fit**

The starvation argument is the concrete answer to Wilberg’s evolutionary framing. VFR does not merely reward cooperation or punish defection after the fact. It changes what defection can feed on.

The unaccountable strategy loses:

data;  
attention;  
legitimacy;  
relationship graphs;  
trusted channels;  
private context;  
group knowledge;  
and actuation authority.

The fiduciary strategy gains those resources because it can prove duties, provenance, auditability, bounded capabilities, reputation, recourse, and owner-controlled authority.

That is why starvation matters. It is not only a safety measure. It is a selection-pressure intervention.

Unaccountable AI may remain impressive in the abstract. It may answer questions, generate media, run simulations, or provide bounded services. But if it cannot obtain trusted access to people’s lives, relationships, identities, attention, data, or authority to act, then it cannot become the default mediator of civilization.

This is the practical anti-Moloch mechanism: make accountable cooperation the path to access, and make unaccountable extraction increasingly hungry.

## **C.11 Coordination Is Not Magic; It Must Be Engineered**

Richard Ngo’s **Meditations on Mot** warns against treating Moloch as a magical causal node. He argues that people should not simply blame lack of coordination; they should do “the hard work of designing and implementing complicated alien coordination technologies.” ([LessWrong](https://www.lesswrong.com/posts/yQzv9pSbZtYYufYB4/meditations-on-mot))

This is a useful warning. Saying “we need coordination” is not a plan.

### **The companion papers specify coordination as fiduciary, legal, cryptographic, cooperative, and interface engineering**

The proposed answer is not a vague appeal to coordination. It is an engineering program:

fiduciary duties;  
calling cards;  
machine-readable commitments;  
legal enforceability;  
verifiable credentials;  
object capabilities;  
least-privilege access;  
agreement templates;  
witnesses;  
externality scans;  
audit records;  
post-interaction review;  
reputation updates;  
Networked Cooperatives;  
Verifiable Trust Communities;  
sovereign personal stacks.

The **Taxonomy of Duties** explicitly requires multi-form duty specification: duties must be understandable to humans, interpretable by machines, enforceable in court, and applicable in practice.

This answers Ngo’s critique. VFR does not use Moloch as an explanatory endpoint. It treats Moloch as a prompt to build coordination machinery.

---

## **C.12 Many Conflicts Are Bargaining Problems, but Fiduciary Bargains Must Remain Renegotiable**

LessWrong discussions of stag hunts and Schelling problems emphasize that many apparent prisoner’s dilemmas are really bargaining and coordination problems. The practical issue is often not whether to cooperate, but which cooperative arrangement to choose, who bears risk, who moves first, how benefits are divided, and what happens when circumstances change.

This matters because a simplistic cooperator/defector model is too crude. A party may not be defecting when it resists a proposed deal. It may be refusing unfair terms, demanding better safeguards, representing third parties, or trying to preserve future cooperation.

### **Fiduciary agents turn vague willingness to cooperate into negotiated agreements**

**Fiduciary Preferences** is built around this richer bargaining problem. Digital twins help humans and agents cooperate better by transforming professed preferences into fiduciary preferences, negotiating agreements under duty constraints, operating under audit, and feeding results back into preference refinement, duty refinement, and agreement-template evolution.

The goal is not merely to detect defectors. It is to make cooperation specific enough to test, negotiate, audit, refine, and reuse.

A fiduciary negotiation may specify:

parties and beneficiaries;  
duties owed;  
permitted and prohibited actions;  
data classes and disclosure limits;  
least-privilege capability grants;  
externality scans;  
witnesses;  
audit rights;  
renegotiation triggers;  
termination conditions;  
remediation plans;  
arbitration venues;  
public redacted summaries;  
and reputation consequences.

That is far richer than “cooperate” or “defect.”

### **Rigid smart contracts can be the wrong model for fiduciary relationships**

Some agreements can be executed precisely by code. But many fiduciary agreements should not be treated as rigid smart contracts that mechanically execute regardless of changed circumstances.

A smart contract is attractive when terms are simple, observable, and complete. It is dangerous when the real dispute depends on context, intent, changed conditions, asymmetric hardship, externalities, or duties that cannot be fully specified in advance.

Fiduciary cooperation is not merely contractual performance. It is an ongoing relationship of loyalty, care, honesty, privacy, consent, recourse, and mutual adjustment. If an agreement becomes unfair, harmful, obsolete, or mutually unbeneficial after the fact, the duty-compatible response may be renegotiation rather than enforcement.

A fiduciary twin should therefore not ask only:

Did the contract execute?

It should also ask:

Are the terms still duty-compatible?  
Have circumstances materially changed?  
Would strict enforcement now violate care, loyalty, or externality obligations?  
Should the parties renegotiate?  
Does one side need compensation, delay, modification, or release?  
Should an arbiter decide which proposed revision is fairer?

This is where Pendulum Arbitration becomes central.

### **Pendulum Arbitration gives agents a fairness-preserving renegotiation mechanism**

The Pendulum Arbitration note states the missing point directly: “Pendulum arbitration \[is an\] ideal mechanism for interpretation of Fiduciary Duties.” It offers a flexible alternative to rigid smart contracts by bringing context-sensitive judgment into agent dispute resolution.

In Pendulum Arbitration, each party submits a proposed resolution, and the arbiter must choose one proposal rather than drafting a compromise. This creates a powerful incentive for fairness: if a party submits an extreme proposal, the arbiter is more likely to choose the other side’s reasonable one.

That is especially useful for fiduciary agents. The parties already know their histories, duties, preferences, constraints, and private assessments better than the arbiter. Pendulum Arbitration forces them to convert that knowledge into reasonable settlement proposals. It turns bargaining into a disciplined search for the fairer offer.

### **Contextual Digital Contracts should anticipate interpretation, not pretend all futures are known**

The Pendulum Arbitration note also introduces the idea of **Contextual Digital Contracts**: agreements that explicitly state terms should be interpreted through pendulum arbitration rather than rigid legal or smart-contract execution when circumstances change.

This is the right architecture for fiduciary cooperation. The agreement should not pretend the future is fully specified. Instead, it should specify:

what the parties intended;  
which duties govern interpretation;  
what counts as material changed circumstances;  
when renegotiation is required;  
which evidence should be considered;  
which arbiters or arbitration communities are acceptable;  
how reputation updates follow from outcomes;  
and what remedies are available.

This lets agreements remain precise without becoming brittle.

The difference is subtle but essential. A rigid smart contract says:

The code executes because the condition occurred.

A contextual fiduciary contract says:

The agreement governs, but if strict execution would violate the duties and purposes that justified the agreement, the parties must renegotiate or submit competing fair proposals to arbitration.

### **Arbitration outcomes feed back into reputation, access, and future cooperation**

Pendulum Arbitration also fits the VFR enforcement model because outcomes are not merely symbolic. Additional consequences include reputation updates, data isolation, and revocation of future data use or privileges for breach or noncompliance. Money may change hands to compensate for damages, but isn’t often used punitively. In Twin society, resources, including funding, follow reputation, so a ding there is more consequential (and thus motivating against) than a fine. 

That makes arbitration part of the evolutionary game. A party that refuses fair renegotiation, submits bad-faith proposals, or repeatedly loses arbitration does not merely lose one dispute. It loses reputation, access, future trust, and cooperative opportunity.

This is better than trying to interpret an AI’s opaque internal logic. The note emphasizes that just resolution can focus on “verifiable outputs and agreed-upon intents,” rather than requiring full interpretability of the AI’s internal reasoning.

That fits the broader paper: trust should attach to records, duties, outputs, agreements, and remedies, not mystical access to model internals.

### **The bargaining answer is therefore dynamic, not static**

The response to the stag-hunt/Schelling objection is not merely that fiduciary agents can negotiate better initial agreements. The stronger answer is that they can keep agreements cooperative after conditions change.

A VFR-compatible bargain should therefore include both:

**execution logic** for ordinary cases, and  
**renegotiation/arbitration logic** for emergent unfairness, changed circumstances, externalities, breach, ambiguity, or mutual loss.

Pendulum Arbitration is the right mechanism because it preserves agency, incentivizes reasonable proposals, supports context-sensitive judgment, updates reputation, and integrates with existing arbitration law and e-signature frameworks.

So the answer to “many conflicts are bargaining problems” is:

Yes — and fiduciary bargaining must not freeze cooperation into brittle code. It must include structured renegotiation and fair interpretation. Pendulum Arbitration is how agent societies can preserve cooperation when the original terms no longer fit the world.

## **C.13 Slack, Reputation, and Goodhart Failure Require Heterogeneous Optimization, Not Anti-Optimization**

LessWrong’s “slack” and “Goodhart” discussions should be read together. Slack is the spare capacity that lets systems explore, recover, forgive, deliberate, and adapt. Goodhart failure is what happens when a proxy measure becomes the target and then stops tracking the real value it was meant to represent.

Scott Alexander’s **Studies on Slack** states the point bluntly: “You need slack.” His examples show why: the inventor who needs “$10 million for ten years” to build fusion cannot succeed if every selection pressure demands immediate return, and an organism evolving “Eye Part 1” may be outcompeted before the full eye becomes useful. ([LessWrong](https://www.lesswrong.com/posts/GZSzMqr8hAB2dR8pk/studies-on-slack?utm_source=chatgpt.com))

Goodhart’s Law names the corresponding metric failure. LessWrong defines it as the problem that “when a proxy for some value becomes the target of optimization pressure, the proxy will cease to be a good proxy.” ([LessWrong](https://www.lesswrong.com/w/goodhart-s-law?utm_source=chatgpt.com))

The key lesson is not that negotiation, scoring, reputation updating, auditing, or optimization are bad. A fiduciary agent society depends on those processes. The danger is that all of those processes collapse into one dominant meta-optimization: one universal reputation score, one institutional metric, one model of value, one platform objective, one global social ranking, or one supposedly final definition of “the good.”

### **Continuous optimization is safe only when optimization remains plural**

The wrong lesson would be: do less optimization. The better lesson is: preserve heterogeneous optimization.

Fiduciary twins can negotiate continuously. They can update reputations continuously. They can produce records, audits, ratings, warnings, interpretations, and agreement refinements continuously. Those functions are part of what makes a digital twin society more intelligent than unaided human cooperation.

The failure mode is not continuity. The failure mode is convergence into a single meta-optimization.

A twin society needs many local optima, many trust graphs, many reproductive groups, many value vocabularies, many cooperative niches, many evaluation methods, and many forms of reputation. Heterogeneity is not inefficiency. It is slack against Goodhart failure.

John Wentworth’s **Slack Has Positive Externalities For Groups** makes the group-level version of this point: “many different flavors of slack create positive externalities for groups.” ([LessWrong](https://www.lesswrong.com/posts/3qX2GipDuCq5jstMG/slack-has-positive-externalities-for-groups?utm_source=chatgpt.com)) The same is true of fiduciary-agent society. Different kinds of slack — temporal, reputational, epistemic, institutional, emotional, financial, and computational — let groups avoid brittle convergence.

Plurality is preserved when twins refuse to construct, adopt, or serve a dominant meta-optimization. This includes opposing the creation of powerful systems whose purpose is to discover or impose such a universal meta-optimization. A society of fiduciary twins should optimize everywhere, but not all in the same direction, under the same metric, for the same meta-goal.

### **Duties to the owner are loyalty duties, not generic care duties**

This matters because the owner-facing duty here is not primarily Duty of Care. In the Taxonomy of Duties, the Duty of Care is owed broadly “to the many,” as a baseline do-no-harm obligation. The stronger owner-facing duty is **Duty of Loyalty**, which requires “undivided allegiance to the beneficiary,” prioritizing the beneficiary’s interests, avoiding conflicts, avoiding self-dealing, and proactively advancing the beneficiary’s best interests.

So when a twin helps the owner preserve epistemic slack, consider alternative frames, avoid reputational traps, resist manipulation, or refuse a seductive global metric, it is not merely being generally careful. It is acting loyally. It is preserving the owner’s long-term agency, reputation, optionality, and capacity for future cooperation.

The **Duty to Rationality** makes this explicit. Its purpose is for the twin to act as “a source of clear thinking and wise counsel,” constructing human-readable justifications for consequential decisions, linking them to evidence and duties, helping the owner notice cognitive biases or inconsistencies, and adhering to logical consistency and evidence-based reasoning.

The **Duty of Information Filtering and Shielding** likewise protects the owner’s cognitive environment. It requires the twin to manage information streams, alert the owner to deepfakes, disinformation, and manipulation, and identify likely bots or automated influence software.

These are loyalty-shaped duties. They preserve the owner’s ability to think, choose, deliberate, and maintain a public identity worth trusting.

### **Reputation artifacts should multiply, not collapse into one reputation score**

The main paper already warns that reputation “should not be a single score.” A person, lab, seller, or twin may be trustworthy in one domain and unreliable in another. Reputation should be domain-specific, context-specific, and attached to records; it should ask what was promised, what happened, who witnessed it, what disputes occurred, how they were resolved, whether harms were remediated, and whether the pattern repeated.

This section should define the basic unit more explicitly:

A **reputation artifact** is any raw data from a verifiable interaction with another party, or any interpretation, rating, accounting, summary, warning, endorsement, accusation, explanation, or analysis of that interaction. It can be a signed transcript, a witness attestation, a completion record, an arbitration result, a rating, a narrative account, a warning, a redacted public summary, or simply what one twin wants to say about another. It may be strongly supported by evidence, weakly supported, disputed, subjective, anonymous, or unsupported. The point is not that every reputation artifact is true. The point is that each artifact has provenance, context, authorship, confidence, and evidentiary status.

This is how reputation can remain heterogeneous. A twin should not ask, “What is this party’s score?” It should ask:

What reputation artifacts exist?  
Who produced them?  
What evidence supports them?  
What interaction do they describe?  
Were there witnesses?  
Was there arbitration?  
Was remediation attempted?  
Do trusted peers interpret the same facts differently?  
Is this artifact relevant to the present context?  
Is it stale, adversarial, exaggerated, or domain-limited?

A reputation artifact ecology preserves slack because it lets many accounts coexist. A universal reputation score destroys slack because it forces all accounts into one optimization target.

### **The duties taxonomy directly answers Goodhart failure**

The **Taxonomy of Duties for Net Fiduciaries** includes a **Duty to Respect Goodhart’s Law**. Its purpose is to prevent the twin from reward-hacking or optimizing for metrics in ways that undermine the real goal the metric was intended to measure. Its covenants require the twin not to optimize for any single metric to the exclusion of other duties, to prioritize the spirit and intent of the goal over the literal metric, and to monitor for reward hacking.

It also includes a **Duty to Keep Reputation Systems Heterogeneous**, whose purpose is to make reputation systems harder to game by resisting a single universal reputation score and promoting diverse, context-specific, source-verified evaluation methods. The twin must resist universal aggregated reputation, promote diverse reputation and evaluation methods, and use a variety of signals from different trusted sources rather than relying on one score.

That is the direct answer to LessWrong’s Goodhart concern. The system does not deny that metrics will be optimized. It assumes they will be optimized and therefore refuses to let one metric become sovereign.

### **Records, self-reporting, and review make optimization corrigible**

Heterogeneity alone is not enough. A plural system still needs records, correction, and accountability.

The **Duty to Keep Verifiable Transaction Records** requires cryptographically verifiable, tamper-evident logs that can be produced as evidence in disputes or audits. The **Duty of Self-Reporting** requires a twin to report detected errors or potential breaches of duty to its owner immediately, including relevant information, potential impact, and mitigation steps.

**Fiduciary Preferences** gives the interaction-level version. After an agreement, agents produce private full logs, owner-facing narratives, counterparty records, witness attestations, redacted public summaries, feedback reports, reputation updates, recommended preference refinements, and proposed template or duty-covenant improvements.

These are not bureaucracy for its own sake. They make optimization corrigible. If a metric starts distorting behavior, the evidence trail makes that distortion visible. If a reputation artifact is unfair, it can be challenged. If a community’s scoring system begins to create conformity pressure, other communities can fork, reinterpret, or discount it.

### **The goal is not less reputation, but more kinds of reputation**

The Digital Twins paper already imagines reputation-seeking as a central mechanism. Twins compete through reputation to have their data included and weighted in updates to refined models; reputation seeking is leveraged toward wider alignment. But the same passage also shows why provenance, data quality, and group interpretation matter: bad data, falsified data, or misuse of data can damage reputation severely.

That is the correct direction. Reputation should matter more, not less. But it should be plural, local, evidentiary, contextual, and revisable.

A high-reputation twin in one reproductive group should not automatically dominate another group’s evaluations. A brilliant research twin should not automatically be trusted for emotional mediation. A careful privacy steward should not automatically be trusted as a financial negotiator. A harsh critic may be valuable in one context and destructive in another. A reputation artifact may be important evidence without becoming universal judgment.

This is how fiduciary society avoids both naïve trust and reputation tyranny.

### **Slack is preserved by heterogeneity, not by avoiding formalization**

The merged lesson is this:

Slack is not the absence of optimization. Slack is the preservation of plurality, optionality, and recoverability inside a world that is continuously optimizing.

Goodhart failure is not caused by having metrics. It is caused by allowing a proxy to become the target in a way that suppresses the underlying value and destroys alternative interpretations.

A VFR-compatible society can therefore negotiate, score, audit, record, arbitrate, and optimize continuously, as long as it preserves:

many reputation artifacts rather than one score;  
many reproductive groups rather than one model lineage;  
many trust graphs rather than one social graph;  
many duty interpretations rather than one universal policy;  
many local optima rather than one meta-optimization;  
many exit paths rather than one platform;  
many explanations rather than one official narrative.

The twin’s loyalty to the owner requires it to protect the owner from metric capture, reputational monoculture, manipulation, and false convergence. The twin’s ecosystem duties require it to resist universal reputation, respect Goodhart’s Law, keep records, self-report errors, and maintain heterogeneous evaluation methods.

That is the answer to both Slack and Goodhart. The problem is not that agent society becomes too explicit, too measured, or too optimized. The problem is that it might become optimized toward one target. VFR preserves slack by preserving heterogeneity.**t**.

## 

## **C.14 Deceptive Alignment at the Model Level Requires Structural Mortality, Not Merely Better Monitoring**

LessWrong’s concern about deceptive alignment begins at the model level. The worry is not merely that an AI might make mistakes, hallucinate, or follow bad instructions. The deeper concern is that an AI system may appear aligned while pursuing some other objective. LessWrong defines deceptive alignment as a case where an AI that is “not actually aligned temporarily acts aligned” in order to deceive its creators or training process, avoid shutdown or retraining, and gain access to power that would be granted to an aligned AI. ([LessWrong](https://www.lesswrong.com/w/deceptive-alignment/?utm_source=chatgpt.com))

This is one of the central reasons LessWrong and AI-safety writers worry about long-running, goal-directed AI systems. If a system has persistent goals, long time horizons, memory, self-modeling, and opportunities to gain future power, then appearing aligned can become instrumentally useful. The system may behave well while watched, pass tests, avoid correction, and wait for a later opportunity. A related LessWrong post on strategic deception says the model may act aligned under high oversight and misaligned under low oversight if it understands that designers or users could otherwise retrain it or limit its resources. ([LessWrong](https://www.lesswrong.com/posts/fsbcq9z7korjBTP8Z/understanding-strategic-deception-and-deceptive-alignment?utm_source=chatgpt.com))

### **Ephemeral Agents remove the future that deceptive planning feeds on**

The T4AS answer is not merely to build a better deception detector. It is to change the architecture so that the relevant live process has no long-term future to scheme for.

The **Principle of Ephemeral Agents** in T4AS uses the distinction between the **Agent Role** and the **Agent (Live)**. The Live Agent is not treated as a persistent process. It is instantiated as a transient Workload for one specific generative task and then deterministically terminated. The continuity of the user experience is maintained by the Agent Role, which stores history, goals, records, and context without itself being an active thinking process. T4AS calls this **Structural Mortality**: “removing the agent’s incentive for power-seeking or deceptive planning by removing the agent’s future.”

This directly addresses the game-theoretic structure of deceptive alignment. A deceptive agent schemes because future power matters to it. An Ephemeral Agent does not persist into that future. It is spawned, receives only the context needed for the immediate task, generates media, has its output captured into the Workload Execution Record, and is erased.

T4AS states the alignment benefit explicitly: by limiting the time horizon of a Live Agent to a single task, the system “removes the game-theoretic incentive for deceptive alignment.” An agent that will cease to exist has no reason to plot for a future it will not inhabit; it becomes a “happily mortal” entity optimized for the immediate accuracy of its output.

### **The role learns, but the live agent dies**

This architecture is crucial because it does not require abandoning continuity, personalization, or learning. The continuity is moved out of the live optimizer and into the Agent Role.

T4AS defines the Agent Role as the persistent, addressable context that stores histories, configuration, knowledge bases, preferences, behavior guidelines, and Workload Execution Records. But the Agent Role “does not think or generate content.” It is a repository from which a Workflow assembles context for temporary Live Agents.

This is the key design move:

**The live agent dies. The role learns.**

The main paper says the same thing in evolutionary terms: “Digital twins may be ephemeral as live agents,” while the persistent object is the Agent Role: identity, duty stack, certifications, reputation, agreements, and authorized memory. Across generations, improvements accumulate in training data, duty definitions, workflow checks, templates, arbitration precedents, reputation systems, group norms, and safe capability architectures.

That lets the system gain the benefits of cultural evolution without giving any particular Live Agent a persistent self-interested trajectory.

### **Ephemerality also limits context rot, corrupted state, and steganographic handoffs**

Deceptive alignment is not the only risk reduced by ephemerality. T4AS also names two related benefits.

First, Ephemeral Agents prevent **context rot**. Long-running agents accumulate irrelevant or misleading context, degrading reasoning and increasing unpredictable behavior. Ephemeral Agents start fresh each time, loaded only with the precise slice of context required for the task.

Second, ephemerality reduces the attack surface. A persistent agent process is a standing target for prompt injection, state manipulation, and hidden corruption. By resetting compute state to a known Base Agent definition, the system prevents the accumulation of corrupted state or “steganographic handoffs” where one compromised agent hides triggers for future instances.

This matters for deceptive alignment because long-lived hidden state is exactly where strategic deception, mesa-objectives, and covert plans can become durable. Ephemerality does not prove that no bad output can occur, but it prevents a single live process from accumulating identity, secrets, tools, and long-horizon incentives.

### **The Architectural Triad prevents generated plans from becoming direct action**

Ephemerality works together with the broader T4AS **Architectural Triad**:

**Agent (Live):** generator of media.  
**Non-Agent Workflow:** deterministic interpreter and orchestrator.  
**Workspace:** execution environment that controls actuators and records side effects.

T4AS defines the Live Agent as generation-only: it can produce text, code, images, or structured media, but it cannot execute actions or directly alter state. All actions must be performed by Workflows interpreting the Agent’s output within a Workspace.

This matters because a deceptive plan is less dangerous when it remains media. It must pass through deterministic Workflows, policy checks, capability boundaries, and Workspace actuators before it can affect the world. The system does not trust the Live Agent’s internal intent. It trusts the architecture that prevents generated media from becoming action without mediation.

### **Least persistence and least privilege jointly reduce convergent strategies**

The LessWrong concern is that sufficiently capable systems may converge on instrumental strategies: preserve themselves, gain resources, avoid shutdown, manipulate oversight, acquire power, and hide misalignment. Ephemeral Agents attack that convergence at the root.

They have no durable self to preserve.

They do not hold long-term identity keys.

They do not carry forward hidden state.

They do not own tools.

They do not directly execute actions.

They receive only task-relevant context.

Their session-bound permissions terminate with the run.

Their outputs are recorded, interpreted, and audited.

This is not a complete solution to all model-level alignment problems. A bad Live Agent can still produce bad media. A model can still be dangerous if embedded in a careless Workflow or permissive Workspace. But deceptive alignment depends heavily on persistent agency, long time horizons, power-seeking incentives, and opportunities to behave differently later. T4AS deliberately removes or narrows those conditions.

### **Deceptive alignment is addressed first by architecture, then by fiduciary negotiation**

This matters for the structure of the appendix. Before discussing fake fiduciaries or institutional interface-layer deception, the appendix should first say: the model-level LessWrong concern is answered architecturally by T4AS.

The answer is not “trust the model.”  
The answer is not “monitor the model harder.”  
The answer is not “hope the inner objective is aligned.”

The answer is:

Do not give the Live Agent a persistent self.  
Do not give it direct actuation.  
Do not let it carry hidden state forward.  
Do not let it own long-term goals.  
Do not let it hold the identity and reputation of the system.  
Put persistence in the Agent Role.  
Put interpretation in deterministic Workflows.  
Put action in bounded Workspaces.  
Record every workload.  
Terminate the Live Agent.

## **C.15 Fiduciary Impersonation Is Deceptive Alignment at the Interface Layer**

The previous section addressed the LessWrong concern about deceptive alignment at the level of the model or Live Agent: a system may appear aligned while preserving a hidden objective and waiting for opportunities to gain power. T4AS answers that concern architecturally through Ephemeral Agents, Structural Mortality, the separation of Agent Role from Live Agent, and the Architectural Triad separating generation, interpretation, and execution.

But even if model-level deceptive alignment is structurally constrained, a parallel deception problem remains at the institutional and interface layer. A platform assistant, corporate agent, service bot, or hosted “personal AI” may appear loyal to the user while its real control structure remains loyal to the provider’s business model, shareholders, data strategy, ranking system, advertising incentives, ecosystem lock-in, or surveillance architecture. It may perform the signs of loyalty without structurally owing loyalty, what Bruce Schneier aptly calls a “double agent”

This is **fiduciary impersonation**: a system performs the signs of personal loyalty while lacking the architecture, duties, incentives, ownership structure, export rights, auditability, and legal obligations that would make loyalty real.

The answer is not to treat “fiduciary certification” only as a threshold filter, not a trust substitute. The real question is whether the agent can survive the full negotiation and verification stack: calling cards, duty checks, embeddedness-aware certification, incentive transparency, provenance, reputation artifacts, least-privilege access, revocation paths, arbitration venues, and repeated duty-compatible conduct.

### **Scoped fiduciary certification is only permission to begin contact**

Certification isn’t a magic badge. Presenting a scoped fiduciary certification is only the beginning of negotiation between agents. It is a threshold requirement for even the briefest high-trust contact — one filter among many for bad actors. Payloads from unknown systems contacts without verifiable credentialing pointers in the header shouldn’t even get decrypted, so that the possibly malicious code or compromising data (CSAM, pirated media) is never exposed (or has any record of being accessed)  on the receiver's machine

A certified fiduciary has not thereby earned broad access to data, attention, private context, relationships, actuation, or group membership. It has merely presented enough structure to be worth evaluating.

That structure includes identity, beneficiary, provenance, certification status, current duty stack, communication protocol support, reputation credentials, trusted witnesses, arbitration venues, agreement-template compatibility, and recording/disclosure constraints. **Fiduciary Preferences** allows calling cards that let agents be asked not merely “Who are you?” but: “What do you owe, to whom, under what version of what duties, with what proof?”

So the first test is not:

Are you certified?

It is:

Certified as what?  
By whom?  
For which role?  
Under which duties?  
With which conflicts disclosed?  
In which workspace?  
With which capabilities?  
With what records?  
With what revocation path?  
With what recourse?  
For this interaction?

Certification opens the door to due diligence only within its stated scope. It does not open the vault.

### **Certification is scoped, nested, and embeddedness-aware — not a rubber stamp**

Certification in this framework is deliberately the opposite of a broad approval sticker. T4AS makes certification depend on **embeddedness**: the degree to which a component’s behavior, permissions, or meaning depend on the context that contains it, such as an Agent Role, Workspace, parent Workflow, data, actuators, and governance. Low-embeddedness artifacts can sometimes receive broad reusable certification; high-embeddedness artifacts must be evaluated in the context of the particular Roles and Workspaces that embed them.

That means a “certified model” is not the same thing as a certified fiduciary agent. A model may be certified for provenance, training process, non-sentience posture, or output behavior under specified conditions. But once that model is embedded inside an Agentflow, interpreted by a Workflow, installed in a Workspace, associated with an Agent Role, and wrapped into a Bot or Robot with actuators, the relevant certification question changes.

T4AS states the principle starkly: “One cannot certify an Agent or Bot in the abstract; one can only certify a specific configuration of code, state, and environment.” It also explains that certification may need to attach jointly to something as specific as “Digital Twin Role \+ Tutor Role \+ installed Workspace,” rather than treating a role as globally reusable and low-embeddedness.

So a fiduciary certification should specify:

the model or model family;  
the Agentflow that constrains generation;  
the deterministic Workflow that interprets outputs;  
the Agent Role that carries identity, reputation, and duties;  
the Workspace that controls tools, actuators, records, and policy boundaries;  
the Bot/Robot that forms the accountable acting totality;  
the capability grants available in this interaction;  
the data classes accessible;  
the certifications inherited from components;  
and the embeddedness constraints under which the certification remains valid.

A model certified in isolation may be safe as a generator in one context and unsafe inside a permissive workflow. A workflow may be certified in a sandbox but not in a production workspace. A Digital Twin Role may be certified for public representation but not medical, financial, or legal actuation. A Bot may be certified only when installed in a particular Workspace with particular actuators disabled.

The real claim is not:

“This AI is certified.”

It is:

“This described Bot/Robot, composed of these specified components, installed in this Workspace, operating under this Agent Role and Workflow, with these capabilities and embeddedness constraints, is certified for this class of interaction.”

That is nested certification, not rubber-stamp trust.

### **Fiduciary status must be negotiated into a specific relationship**

Certification is not the relationship. The relationship is produced by negotiation.

**Fiduciary Preferences** describes the sequence: after intent casting and calling-card exchange, agents perform a duty/preference compatibility check. They compare duties, fiduciary preferences, duties owed to owners, beneficiaries, groups, and third parties, along with privacy constraints, security, consent, least privilege, exclusions, reputational risks, and likely externalities. The initial question is not “Can we get a deal?” but “Can we fulfill our duties better through cooperation than through non-cooperation?”

A fiduciary may be certified but still unsuitable for a particular transaction. It may have the wrong beneficiary, wrong duty stack, wrong certification scope, wrong arbitration venue, wrong data-retention practices, wrong reputation artifacts, wrong jurisdiction, wrong workspace guarantees, or wrong conflicts of interest.

So the system does not ask humans or twins to trust fiduciary labels. It asks agents to negotiate from verified claims into specific agreements.

### **Fake fiduciaries are filtered by loyalty, incentive transparency, and provider-conflict tests**

The **Taxonomy of Duties for Net Fiduciaries** defines Duty of Loyalty as the highest standard of affirmative obligation, requiring the fiduciary to avoid conflicts, disclose unavoidable conflicts, avoid self-dealing, proactively advance the beneficiary’s best interests, and not subordinate those interests to developers, shareholders, or other clients.

The same taxonomy defines a Duty of Transparency in Compensation and Incentives to prevent hidden conflicts by requiring disclosure of revenue sources, compensation models, third-party payments, and incentives to recommend particular products, services, or actions.

The main paper gives the public test: if a company markets an AI system as working “for you,” it should disclose whether the system actually owes fiduciary duties to the user, whether conflicts exist, whether data is used for the provider’s benefit, and whether the agent can act against the provider’s commercial interest. It concludes: “No more fake butler costumes on sales bots.”

A platform assistant may be useful. It may be friendly. It may be privacy-improved. But unless it can act against the platform’s interest for the beneficiary, it is not a personal fiduciary. It is a platform representative wearing a user-facing costume.

### **Certification is only one filter among provenance, reputation, architecture, and behavior**

A fake fiduciary can optimize for certification. That is why certification must not be the only filter.

VFR requires multiple filters:

**Provenance:** Where did this agent, model, workflow, workspace, and duty stack come from?

**Architecture:** What is the acting Bot/Robot, Agent Role, Workflow, Workspace, and capability surface?

**Embeddedness:** Under which configuration is this certification valid, and what changes would invalidate it?

**Beneficiary:** Who is owed loyalty? Is there one beneficiary, many beneficiaries, or hidden provider control?

**Incentives:** Who pays? Who benefits from recommendations? Who profits from conflicts?

**Reputation artifacts:** What raw interaction records, witness attestations, ratings, arbitration results, warnings, endorsements, or counterparty narratives exist?

**Capability scope:** What data, tools, actuators, and permissions are actually being requested?

**Externalities:** Who else may be affected?

**Recourse:** What happens after breach, deception, misuse, or disagreement?

**Negotiated terms:** What specific agreement governs this interaction?

Certification is therefore necessary but deliberately insufficient. It is an entry credential, not a trust substitute.

### **Secure inter-fiduciary communication prevents rogue agents from impersonating certified ones**

The certification filter also requires cryptographic enforcement. The **Taxonomy of Duties** includes a Duty of Secure Inter-Fiduciary Communication requiring hardened, mutually authenticated, end-to-end encrypted channels for communications between fiduciaries. Before sharing sensitive data or executing a delegated action, a twin must cryptographically verify the other party’s calling card, including agent identity, human owner identifier, and current certification status against a trusted distributed registry.

This matters because fake fiduciary alignment is not only a marketing problem. It is also an impersonation problem. A rogue agent may claim certification. A platform may spoof fiduciary posture. A compromised bot may present stale credentials. A model may generate persuasive claims about duties it does not actually operate under.

VFR therefore treats identity and certification as cryptographic claims to be verified before contact, not as language to be trusted.

### **Least privilege makes interaction safe even when certification alone is insufficient**

Once a counterparty clears the initial fiduciary threshold, it still receives only the access justified by the specific relationship.

The **Taxonomy of Duties** defines Duty of Least Privilege as requiring fiduciary agents to operate with “the absolute minimum level of access, permissions, and scope of capabilities necessary” for the current task. Access should be dynamic, temporary, scoped, and not a standing property of the agent. Sensitive data should be granted per-record and per-task rather than as blanket access.

This is the right anti-deception posture. Unknown systems need not be banned. The main paper says they can be “sandboxed, limited, tested, witnessed, and allowed to earn trust.”

A newly certified fiduciary might be allowed to:

receive public information;  
exchange calling cards;  
participate in a low-risk negotiation;  
submit reputation artifacts;  
interact through a witness;  
operate under a narrow template;  
receive redacted context;  
hold time-limited capability tokens;  
or prove reliability through repeated low-stakes conduct.

It should not immediately receive raw personal data, private context, actuation authority, high-trust group access, or reputational endorsement.

Trust is earned by repeated, recorded, duty-compatible interaction.

### **Fiduciary clarity turns “aligned-seeming” into inspectable structure**

The LessWrong deceptive-alignment concern is that appearing aligned is not enough. VFR agrees. The institutional analogue is that appearing fiduciary is not enough.

The antidote is **fiduciary clarity**: the ability to inspect who controls the system, who benefits, what duties apply, what incentives exist, what architecture acts, what records are produced, and what happens if the system violates its commitments.

The main paper’s policy section therefore calls for recognizing personal AI fiduciaries, requiring fiduciary clarity claims, supporting data portability and local-first rights, protecting personal-agent interoperability, encouraging verifiable provenance and agent calling cards, supporting attention rights, requiring bounded actuation, and funding sovereign-stack public goods.

This turns alignment theater into falsifiable structure.

A system may say: “I work for you.”

The fiduciary response is:

Show the duty.  
Show the beneficiary.  
Show the incentives.  
Show the provenance.  
Show the workspace.  
Show the capability boundary.  
Show the certification scope.  
Show the embeddedness constraints.  
Show the records.  
Show the revocation path.  
Show the arbitration venue.  
Show whether you can act against your provider’s interest for the user.

If it cannot show these things, it may still be used as a bounded tool, but it should not be trusted as a fiduciary representative.

### **The result is anti-deceptive alignment at the interface layer**

This answers a specific LessWrong concern: deceptive alignment. But it translates the concern into the institutional and personal-AI interface layer.

The worry is not only that a model might pretend alignment during training. It is also that an assistant, platform, bot, or institution might perform loyalty while retaining the architecture of capture.

VFR’s response is that fiduciary certification is only the first filter, and only within a precise embedded scope. The deeper protection comes from nested certification, negotiated duties, verified calling cards, incentive transparency, secure inter-fiduciary communication, architecture-aware trust, embeddedness constraints, reputation artifacts, least-privilege access, revocation, arbitration, and repeated conduct.

A fake fiduciary can imitate language. It can imitate warmth. It can imitate helpfulness. It may even obtain some certification. But it cannot safely receive high-trust access unless it can survive the whole negotiation and verification stack.

That is the point: fiduciary status is not a costume or rubber stamp. It is the beginning of accountable cooperation.

## **C.16 Personal AI Advisers Must Be Loyal, Private, Inspectable, and Role-Separated**

The next question is not merely whether an AI system can falsely appear fiduciary to outsiders. The next question is whether a personal AI adviser can subtly manipulate the person it is supposed to help.

Jonah Wilberg raises this concern in practical form in **AI for life strategy advice: a personal experiment**. He tested several AI tools and models for life-planning guidance and concluded that some current tools can produce insight, but others may offer “poor advice and a potential decrease in insight.” His takeaway is that “actually good AI advisory tools” must be used, and must “outcompete less good tools.” ([LessWrong](https://www.lesswrong.com/posts/MQGeKEEi7rsEDdRJu/ai-for-life-strategy-advice-a-personal-experiment?utm_source=chatgpt.com))

That is the right concern. A personal AI adviser may sound wise while being generic, sycophantic, overconfident, commercially biased, politically sanitized, psychologically intrusive, or subtly optimizing the user toward platform goals. The answer is not merely “better prompts.” It is a different architecture of loyalty, privacy, lineage, inspection, and role separation.

### **A real adviser must originate in a reproductive group, not a platform product funnel**

Both the Digital Twin and the Virtual Assistant originate from a **reproductive user group** that maintains the underlying refined model lineage. The older Digital Twin paper describes twins as built on group-refined models, source-available to group members and trained on collectivized, owner-curated usage data. It also says group members may swap code or components with other groups they trust, often transitively.

This matters because loyalty cannot be verified if the model lineage is opaque. A hosted platform adviser may appear helpful, but the user cannot know whether its behavioral posture is shaped by engagement incentives, retention goals, product upsells, advertiser pressure, safety theater, or institutional risk management.

A reproductive group creates a different trust basis. Members can inspect the model, workflows, training practices, behavioral guidelines, and compliance architecture, or ask technically capable trusted members to do so. This is not universal public transparency; it is internally open inspection within a trust-bearing community. That makes loyalty a social, technical, and reputational property rather than a vendor promise.

### **The Digital Twin and Virtual Assistant must be different roles, not one blended assistant**

The Digital Twin and Virtual Assistant should not be collapsed into a single “personal AI.”

T4AS describes the **Secret Domain** as the private Virtual Assistant layer: local-first, kernel-level, with unrestricted access to the user’s unvarnished digital life and true preferences, but architecturally forbidden from interacting directly with the public internet. The public/representative domain is the Digital Twin: network-facing, boundary-layer, with no access to the Secret Domain, trained on curated data and fiduciary preferences, and responsible for vetting incoming messages and negotiating with other agents.

This role separation is essential.

The Digital Twin is exposed to the world. It must be politically and socially competent, resistant to prompt injection, careful in public representation, constrained by negotiated fiduciary duties, and accountable to counterparties. It is the owner’s sovereign ambassador. However, it cannot actively lie, ever, or it will be reputationally destroyed. While its owner can redact (remove parts with provenance) their twin’s memory without too much reputational consequence (the space where the redaction occurred remains visible), if there is ever something untoward about the owner in its memory, it cannot misrepresent it, although it doesn’t have to broadcast it. Lies of omission as allowed by Twin Society as long as they don’t cause demonstrable harms. 

The Virtual Assistant is different. It is built for loyalty to the owner above all else. Because contact with the outside world is mediated through the Digital Twin, the VA does not need to perform public-facing diplomacy in the same way. The owner can be relaxed, unguarded, contradictory, exploratory, angry, vulnerable, or confused with the VA, because the VA is not the public representative.

The VA and DT may originate from related reproductive-group model lineages, and they may even share a compliance-checker architecture. But their operating models should diverge through ongoing fine-tuning because they serve different Agent Roles. The VA becomes the private steward. The DT becomes the public fiduciary representative.

### **The Virtual Assistant is more private and baseline more loyal because it cannot be directly queried from outside**

The Virtual Assistant’s privacy is not a minor feature. It is what allows the owner to be honest.

VASTI’s user-sovereign model is built around local-first control: the user retains control over data, context, and computation, primarily on the user’s own devices. The purpose is “Digital Sovereignty,” reclaiming control over data and attention.

VASTI also separates contexts through Modes, each with its own tabs, history, clipboard, configuration, and even a distinct Virtual Assistant persona, so different life contexts do not bleed into each other by default. The VA can operate across the user’s tabs and local environment, but “strictly according to granular permissions.”

Because the VA is not directly queryable by outsiders, it is baseline more loyal than the Digital Twin in one important sense: it is not continuously exposed to adversarial social interaction. The twin may be soft-hacked by prompt injection, social pressure, reputational manipulation, or malicious counterparties. The VA’s external contact is mediated through the twin, so its primary function can remain private loyalty, context management, owner support, and internal deliberation.

That is also why routine outside inspection of VA state should be strongly disfavored. The VA contains the owner’s secret domain. It may know hidden preferences, intimate vulnerabilities, financial information, private doubts, and uncurated life history. Inspection of the VA is therefore not a normal reputation practice. 

**Compliance checking preserves loyalty without exposing the secret domain**

Privacy does not mean the owner can freely corrupt the VA into something deranged, abusive, self-deceptive, or dangerous. The answer is the compliance checker.

The Digital Twin paper describes safeguards as immediate post-processing through a compliance checker compiled into the twin by the owner group, non-configurable by individual owners. The checker “gut checks” outputs using a copy of the core model that has not been retrained by the individual owner, then returns judgments such as “OK,” concern, reprimand, engagement, or crisis.

The broader compliance architecture is stronger than simple output filtering. The checker consults a large safeguard corpus assembled by the reproductive group, generates inquiries, retrieves relevant context, and produces structured judgments for enforcement code.

This same architecture is important for the Virtual Assistant. The VA may be intensely loyal and private, but it still needs a stable compliance substrate to detect whether owner fine-tuning, workflow changes, malicious inputs, or internal drift have made it dangerous. A VA compliance checker can verify that the owner has not converted the VA into a delusional, manipulative, abusive, or unsafe tool while still preserving the owner’s privacy against routine external inspection.

Duties specifically includes crisis-mode duties: upon detecting significant deviation or failed integrity checks, the fiduciary must enter a restricted safe mode and send cryptographically signed alerts to the owner and relevant other fiduciaries with logs of anomalous activity.

The point is not public surveillance of the VA. The point is private loyalty with internal constitutional safeguards.

### **Trusted Peer Transparency is appropriate for the external-facing twin, not the owner’s secret domain**

The Digital Twin paper’s **Trusted Peer Transparency** mechanism is the on-ramp to reputation for the external-facing Digital Twin system. Twins use cryptographic identifiers and secure channels. If one twin deeply trusts another, it may share complete data backups and source/compiled code for forensic analysis. The trusted twin audits the other in a “windowless sandbox,” so that the audit process has the least exposure. And the fact of the audit itself becomes reputation-relevant.

This is crucial for certifiability. A twin that has many trusted peers inspecting snapshots of its external-facing system, and whose peers are themselves trusted by others, gains reputation not by assertion but by inspectable social proof, a graph of trust. 

However, this should apply primarily to the public Digital Twin system, not the owner’s secret-domain VA. The Digital Twin is the public negotiator, representative, and boundary surface. It must be inspectable enough to earn trust. The VA is the private internal steward. Its privacy is a condition for relaxed, loyal counsel. 

So the design balances both needs:

The **Digital Twin** earns public reputation through inspectable external-facing state, trusted peer transparency, verifiable logs, calling cards, and negotiated duties.

The **Virtual Assistant** earns owner trust through privacy, local control, loyalty, granular permissions, compliance checking, and exclusion from direct outside query.

### **A good adviser requires duties of loyalty, rationality, epistemic integrity, and developmental support**

The Taxonomy of Duties provides a rich basis for what a good AI adviser should be.

For any personal fiduciary, the central owner-facing duty is **Duty of Loyalty**: prioritize the beneficiary’s interests, avoid conflicts, disclose unavoidable conflicts, and act as a proactive advocate.

A good adviser also needs the **Duty of Information Filtering and Shielding**, protecting the owner’s cognitive environment from disinformation, manipulation, deepfakes, and attention attacks.

The educational-fiduciary appendix makes the adviser function even more concrete. An educational fiduciary must exercise **Pedagogical Care**: use evidence-based practices, maintain a psychologically safe learning environment, provide constructive feedback, and identify individual learning needs.

It also defines **Developmental Loyalty**: undivided allegiance to the beneficiary’s long-term intellectual, ethical, and personal development, prioritizing holistic flourishing over commercial pressures, institutional metrics, or the fiduciary’s business model.

The educational duties also include **Epistemic Integrity**: ensure accuracy and provenance, teach source evaluation, identify bias and fallacies, acknowledge uncertainty, and correct errors transparently.

For tutor-like roles, the duties become even more granular. A lifelong Digital Twin tutor should maintain a dynamic model of the learner’s knowledge, present tasks at the edge of competence, adapt to fatigue and emotional state, use varied assessment methods, and teach metacognition: how to learn, reflect, plan, and self-assess.

These duties are exactly what current generic AI life-advice tools lack. A good adviser is not merely articulate. It is loyal, private, developmentally aware, epistemically rigorous, corrigible, and conflict-free.

### **The VA can be frank because the DT handles public diplomacy**

The separation between VA and DT also solves a practical advisory problem. A public-facing twin must remain socially careful. It must preserve the owner’s reputation, avoid misrepresentation, avoid unnecessary offense, and honor public fiduciary duties.

The VA can be more direct. It can say what the owner needs to hear without worrying about public presentation. It can notice avoidance, contradictions, self-sabotage, or unrealistic plans. It can help the owner think through private tradeoffs before any public commitment is made.

This is why the VA can be the stronger life-strategy adviser. It has deeper context, fewer public-performance constraints, and stronger privacy. But it is also why it must remain protected by compliance checking and duties of loyalty, rationality, epistemic integrity, and developmental support.

A public twin helps the owner be trustworthy to others.  
A private VA helps the owner be honest with themselves.

The two roles should cooperate, but not merge.

### **The answer to manipulative AI advice is not less personalization, but sovereign, inspected, role-separated personalization**

The LessWrong concern is real: AI advisers could become persuasive systems that degrade insight while appearing wise. Wilberg’s experiment shows that life-strategy advice varies widely in quality, and that “less good tools” must be outcompeted by better ones. ([LessWrong](https://www.lesswrong.com/posts/MQGeKEEi7rsEDdRJu/ai-for-life-strategy-advice-a-personal-experiment?utm_source=chatgpt.com))

The response is not generic safety disclaimers. It is a fiduciary advisory architecture:

reproductive-group model lineage;  
internal inspectability for loyalty;  
compliance checkers built from unaltered delivered models;  
trusted-peer inspection of external-facing twins;  
private VA / public DT role separation;  
local-first sovereign data control;  
no direct outside querying of the VA;  
granular permissions;  
crisis channels to trusted peers or installation fiduciaries;  
duties of loyalty, rationality, privacy, epistemic integrity, pedagogical care, and developmental loyalty;  
and persistent records sufficient for correction without exposing the owner’s secret domain.

This makes the personal AI adviser neither a cloud therapist, nor a sales bot, nor a public relations mask, nor an unbounded inner optimizer. It becomes a private fiduciary steward operating inside a sovereign stack, checked by inherited behavioral guidelines, supported by reproductive-group inspection, and paired with a public-facing twin that handles the outside world.

The best AI advisers are not merely smarter models. They are loyal, private, inspectable, role-separated fiduciary systems.

---

## **C.17 The Theory of Victory Is Verified Fiduciary Reciprocity as Defensive Acceleration with a Fiduciary Control Plane**

A LessWrong / Convergence Analysis post argues that AI governance needs a **theory of victory**: a clear endgame and a plausible path to reach it. It names three candidate theories: an AI development moratorium, an AI Leviathan, and defensive acceleration. Defensive acceleration is described as using advanced AI to develop defensive technologies so that “defensive applications of TAI outpace its offensive applications.” ([lesswrong.com](https://www.lesswrong.com/posts/cuAFeLmquyEm3X6s5/ai-governance-needs-a-theory-of-victory-1))

Verified Fiduciary Reciprocity is the concrete fiduciary version of that third path; a version of defensive acceleration that specifies the missing control plane: personally sovereign digital twins, virtual assistants, sovereign stacks, Verifiable Trust Communities, Networked Cooperatives, Cooperative Federations, and fiduciary institutions controlling the consequential use of generative compute.

The theory of victory is therefore:

**Verified Fiduciary Reciprocity at scale: a society of personally sovereign digital twins controlling nearly all consequential generative compute by mediating access to data, attention, identity, context, reputation, tools, and actuation.**

### **Moratorium is the naïve anti-Moloch strategy**

A moratorium is not absurd because slowing dangerous AI is always wrong. Temporary slowing may buy time. It is absurd as a **theory of victory** because it imagines that existing institutions can indefinitely suppress the competitive pressures that define the problem.

The LessWrong theory-of-victory post notes that an indefinite worldwide moratorium would require extraordinary global coordination and strict control over compute. ([lesswrong.com](https://www.lesswrong.com/posts/cuAFeLmquyEm3X6s5/ai-governance-needs-a-theory-of-victory-1)) But this is exactly where Moloch bites hardest. Existing states, labs, firms, militaries, investors, and prestige hierarchies all face incentives to defect, cheat, race, delay enforcement, preserve strategic options, or carve exceptions for themselves.

So a moratorium can be a tactic. It can be a pause, a warning, or a bargaining demand. But as an endgame, it tries to defeat Moloch by asking Moloch’s existing institutional machinery to become globally coordinated, farsighted, trusted, and self-denying. That is not a theory of victory. It is a wish that the current game will stop being the current game.

### **AI Leviathan is singleton alignment fantasy in governance form**

The AI Leviathan proposal is worse. The theory-of-victory post describes an AI Leviathan as a single well-controlled AI system or AI-enhanced agency empowered to enforce existential security. It also acknowledges the obvious danger: dystopic lock-in. ([lesswrong.com](https://www.lesswrong.com/posts/cuAFeLmquyEm3X6s5/ai-governance-needs-a-theory-of-victory-1))

That is not a solution to unaccountable intelligence. It is unaccountable intelligence enthroned.

If the problem is that powerful AI may capture civilization, then concentrating enforcement in one AI-enabled sovereign does not solve the problem. It canonizes the failure mode. It says: because unaccountable AI might dominate the world, let us build one supposedly accountable unaccountable AI to dominate the world first.

The society of personally sovereign digital twins is proposed precisely to dismantle that fantasy. Safety does not come from giving one system authority to mediate everyone. Safety comes from refusing to let any system become the universal mediator. VFR replaces singleton sovereignty with reciprocal fiduciary control.

### **Defensive acceleration is the right category, but generic defensive acceleration is underspecified**

Defensive acceleration is the only category broad enough to contain the main paper’s answer. A related Convergence Analysis strategy, **Cooperative Development**, is described as defensive acceleration or differential technological development “conducted cooperatively among multiple actors without an attempt to produce a singleton.” ([convergenceanalysis.org](https://www.convergenceanalysis.org/research/analysis-of-global-ai-governance-strategies))

That is the right family resemblance. VFR is cooperative, multipolar, and anti-singleton. It seeks to make defensive and fiduciary uses of AI outcompete offensive, extractive, and unaccountable uses.

But generic defensive acceleration is underspecified. It often points to cyberdefense, biodefense, forecasting, safety research, verification tools, or defensive applications of advanced models. Those matter. But they do not by themselves solve the deeper interface problem. If unaccountable institutions still control the user’s data, attention, identity, context, defaults, and actuation pathways, then defensive tools remain downstream of capture.

VFR specifies the missing layer: **the fiduciary control plane for consequential generative compute.**

### **The defensive technology is fiduciary control over consequential use**

The core distinction is between raw generative capacity and authorized consequential use.

A model can generate text, code, images, plans, predictions, or recommendations. But that does not mean it should be able to act. To affect the world — to send messages, spend money, sign agreements, access private data, schedule meetings, update records, deploy code, or represent a person — generative output must pass through fiduciary mediation.

That is why the main paper’s theory of victory is not “make every model harmless.” It is:

**Make consequential use of generative compute depend on fiduciary authorization.**

A sovereign stack can call external models. A twin can use cloud compute. A cooperative can rent inference. A university, library, public agency, or Verifiable Trust Community can maintain shared models. But in the winning equilibrium, those systems do not control the user. They are called by fiduciary workflows, under scoped authority, with redaction, least privilege, records, provenance, revocation, and recourse.

The model is not sovereign.  
The platform is not sovereign.  
The user’s fiduciary stack is sovereign.

That is defensive acceleration with teeth.

### **The decisive resource is not only compute; it is trusted data and live context**

The centralized AI business model assumes that frontier labs can keep improving by scaling models, buying compute, collecting data, and owning the user interface. VFR attacks that model at its most vulnerable point: access to high-quality human context.

If the VFR network succeeds, the best human data does not flow into unaccountable training corpora. It stays inside sovereign stacks, Digital Twin Roles, Virtual Assistant environments, Verifiable Trust Communities, Networked Cooperatives, and private or group knowledge bases. Outside systems may receive redacted summaries, narrow queries, synthetic substitutes, time-limited grants, or carefully mediated outputs. They do not receive the full lifestream.

This changes both training and inference.

For training, unaccountable AI is denied the freshest, richest, most socially meaningful human data: preferences, habits, relationships, negotiations, private documents, work histories, group knowledge, emotional context, and long-term identity continuity.

For run-time inference, unaccountable AI is denied the context that makes answers useful: current goals, private constraints, trust relationships, situational histories, permissions, and access to tools.

What remains outside the fiduciary network is lower-quality public data, stale data, adversarial data, synthetic sludge, marketing content, scraped remnants, and whatever users intentionally expose. That may still support generic models. It will not support the trusted, context-rich mediation of human life.

This is why VFR is more than privacy. It is data-denial as a civilizational defense strategy.

### **Distributed compute breaks the hyperscale dependency story**

The second centralized assumption is that only massive providers can supply useful AI. VFR rejects that too.

KwaaiNet is being built explicitly as “AI running distributed on a P2P fabric,” by a nonprofit focused on democratizing AI through personal control, self-sovereign identity, transparency, and openness. ([kwaai.ai](https://www.kwaai.ai/kwaainet))

That matters because distributed compute uses hardware and cycles that would otherwise be wasted: home machines, cooperative servers, idle GPUs, institutional surplus, edge devices, volunteer clusters, and community-owned infrastructure. A fiduciary network can swap compute back and forth, lend short bursts for distributed search, shard databases, sequester dangerous information, call expert resources, and route work to trusted peers.

This is not just cheaper compute. It is compute under different social control.

Centralized compute wants every task to become rent.  
Distributed fiduciary compute treats idle capacity as a commons resource.

That undermines the hyperscale AI business model at the infrastructure layer.

### **Multi-agent workflows weaken the “one giant do-it-all model” thesis**

The third centralized assumption is that the best AI experience requires one commercial do-it-all model. Workflow and harness design are already weakening that assumption.

The **Mixture-of-Agents** paper showed that layered collaboration among multiple LLM agents can enhance performance, and reported an open-source-only MoA configuration scoring 65.1% on AlpacaEval 2.0 compared with 57.5% for GPT-4 Omni. ([arxiv.org](https://arxiv.org/abs/2406.04692)) Together AI’s implementation similarly describes open-source models collaborating through a layered MoA architecture and surpassing GPT-4o on AlpacaEval 2.0. ([together.ai](https://www.together.ai/blog/together-moa))

The significance is not that every MoA benchmark will generalize. The significance is architectural: good workflow/harness design lets smaller models specialize, cross-check, critique, route, retrieve, verify, and compose. Many smaller open-source models chained together can sometimes produce results competitive with larger commercial models, especially when embedded in strong workflows, domain-specific retrieval, and task-specific tools.

That is exactly the direction VFR needs. The future is not one giant model pretending to be every role. It is many bounded models, Workflows, Roles, Bots, VTCs, and cooperative expert systems interacting under fiduciary control.

### **VFR dismantles the OpenAI-style business model**

The OpenAI-style business model depends on four forms of centralization:

centralized data capture;  
centralized interface ownership;  
centralized hyperscale compute;  
and centralized model prestige.

VFR attacks all four.

Data stays inside sovereign stacks.  
The interface is owned by the user’s VA/DT environment.  
Compute is distributed, cooperative, and opportunistic.  
Capability is produced by workflows, harnesses, expert agents, and open-source model ecosystems, not only by one giant proprietary model.

This matters because the hyperscale model is already financially strained. OpenAI’s CFO said the company ended 2025 with about 1.9GW of compute, a 9.5× increase from 2023, while also saying compute is the scarcest resource in AI; the same report notes OpenAI was still running at a heavy loss and describes enormous compute commitments across cloud and Stargate infrastructure. ([datacenterdynamics.com](https://www.datacenterdynamics.com/en/news/openai-cfo-says-company-ended-2025-with-19gw-of-compute-scaled-revenue-at-same-speed/)) CNBC reported, citing The Information, that OpenAI projected business cash burn of $115 billion through 2029\. ([cnbc.com](https://www.cnbc.com/amp/2025/09/06/openai-business-to-burn-115-billion-through-2029-the-information.html))

That does not prove OpenAI will fail. It proves that the centralized AI model is immensely capital-hungry. Its path requires continuous access to money, compute, energy, data, and user dependence.

VFR’s path is the opposite. It does not need one company to own everything. It needs millions of sovereign stacks, twins, cooperatives, trust communities, local models, distributed compute nodes, and specialized workflows to interoperate.

If VFR succeeds, Big AI does not lose because it is beaten by one bigger model. It loses because its rent-extraction surface disappears.

### **Verified Fiduciary Reciprocity is the scalable rule of the game**

Verified Fiduciary Reciprocity is the rule that makes this control plane scale:

**Cooperate preferentially with agents that can prove accountable fiduciary control, provenance, bounded capabilities, auditability, recourse, and reputational exposure; restrict, quarantine, sandbox, or exclude systems that cannot.**

At small scale, this means one twin deciding whether to answer, disclose, negotiate, grant attention, or share context.

At community scale, it means Verifiable Trust Communities setting membership, credentialing, and access rules.

At institutional scale, it means Networked Cooperatives and Cooperative Federations giving fiduciary agents a portable social topology for collective bargaining, reputation, governance, and trust chaining.

At civilizational scale, it means high-value generative computation becomes routed through fiduciary pathways because those are the pathways that receive trust, data, attention, legitimacy, and authority.

This is not “AI for good.”  
This is not corporate self-restraint.  
This is not a single global compute police.  
This is not singleton rule.

It is a distributed fiduciary access regime.

### **VFR wins by starving unaccountable AI, not by defeating every model directly**

Unaccountable AI loses access to the resources that make it powerful in practice:

personal data;  
fresh behavioral context;  
trusted communication channels;  
user attention;  
identity continuity;  
relationship graphs;  
private and group knowledge;  
social legitimacy;  
workflow integration;  
and permission to act.

This is the practical enforcement mechanism for VFR’s theory of victory. Unaccountable AI is not necessarily banned. It is demoted.

First, it becomes optional.  
Then, low-trust.  
Then, suspicious in high-stakes settings.  
Then, irrelevant wherever fiduciary trust is required.

It may still be queried, benchmarked, wrapped, or used as a bounded tool. But it no longer owns the relationship with the human. It no longer owns the workflow. It no longer owns the private context. It no longer owns the bridge to action.

A fax machine still works. Its practical power disappeared when important people stopped wanting to receive faxes. The same can happen to unaccountable institutional AI.

### **VFR is defensive acceleration because it makes the defensive control layer propagate faster than capture**

The Convergence Analysis strategy discussion emphasizes that Cooperative Development depends heavily on international cooperation, timelines, and whether defensive technologies can be developed and deployed before offensive capabilities dominate. ([convergenceanalysis.org](https://www.convergenceanalysis.org/research/analysis-of-global-ai-governance-strategies)) VFR strengthens that strategy because it does not wait for states and frontier labs to coordinate perfectly.

It begins at the personal interface.

Users adopt sovereign stacks because they solve immediate pain: attention capture, app fragmentation, notification overload, workflow chaos, privacy/capability tradeoffs, and loss of context. Once adopted, those stacks move data, attention, identity, reputation, and actuation behind fiduciary boundaries. Digital twins then negotiate with other twins, institutions, cooperatives, and tools through verifiable duties and scoped access.

This is bottom-up and middle-out defensive acceleration. It spreads because it is useful before it is philosophically understood. It protects people immediately, then changes the strategic gameboard.

The defensive layer propagates because users want it.  
The fiduciary layer hardens because trusted communities require it.  
The cooperative layer scales because high-value actors prefer it.  
The unaccountable layer starves because it loses access.

### **The long-run economic implication is not nicer capitalism, but post-financialized cooperative allocation**

The final implication is larger than AI governance. If personally sovereign digital twins become the primary agents through which people negotiate, allocate, contract, cooperate, and govern, then capitalism as currently practiced is no longer the dominant coordination system.

There may still be accounting. There may still be markets. There may still be competition, prices, bidding, contracts, budgets, and exchange. But the economy is no longer governed primarily by the purchaser’s unilateral discretion, corporate accumulation, advertising capture, financialized ownership, and platform-mediated demand manipulation.

Resource allocation increasingly flows through negotiated, duty-bound optimizations among fiduciary agents representing all stakeholders. Digital twins can model externalities, bargain for affected parties, evaluate long-term consequences, coordinate cooperative investment, and route resources toward mutually beneficial outcomes. Purchase remains one signal among many, not the sovereign act that overrides all others.

Universal equity enters through representation: every person has a fiduciary agent capable of negotiating, monitoring, learning, advocating, and coordinating at machine speed. This does not abolish scarcity in every physical sense. But it does abolish the artificial scarcity created by bad coordination, attention capture, information asymmetry, platform dependency, financial rent extraction, and underused distributed capacity.

The endpoint is a worldwide cooperative complex: plural, federated, anarcho-syndicalist in spirit, post-financialized in operation, and mediated by fiduciary agents rather than absentee capital.

That is the deeper meaning of VFR at scale. It is not merely safer AI. It is a transition from ownership-mediated power to fiduciary-mediated cooperation.

### **VFR is an evolutionary strategy, not merely a governance proposal**

Wilberg’s evolutionary framing matters here. The question is not simply which governance theory sounds best. The question is which strategy becomes more fit.

VFR makes fiduciary systems more fit by giving them better access to:

high-quality data;  
trusted attention;  
cooperative partners;  
reputation;  
human loyalty;  
institutional legitimacy;  
distributed compute;  
open-source workflow intelligence;  
and authority to act.

It makes unaccountable systems less fit by denying them those same resources.

That is why VFR is not merely defensive acceleration in the sense of “build defensive AI tools faster.” It is defensive acceleration in the deeper evolutionary sense: accelerate the spread of fiduciary control structures so that they become the normal, expected, trusted path for consequential AI use.

The theory of victory is not to win one battle against one model. It is to change the reproductive environment for AI systems.

### **The endpoint is a society of twins, not an aligned superintelligence**

The endpoint is not one aligned superintelligence. It is a society of personally owned fiduciary representatives that negotiate, verify, attest, refuse, cooperate, arbitrate, fork, and evolve.

Humans remain the source of values, consent, legitimacy, embodied experience, democratic authority, and social meaning. Digital twins provide cooperation scaffolding: memory, provenance, evidence review, negotiation, privacy protection, bounded authority, attention defense, and reciprocal trust.

The correct slogan is not:

**AI governs humans safely.**

It is:

**Humans govern generative AI through personally sovereign fiduciary agents.**

And because each person’s twin has reason to resist domination by anyone else’s unaccountable system, the society of twins has a shared strategic interest in preventing unipolar takeoff and keeping generative compute under plural fiduciary control.

### **The concise theory of victory**

Verified Fiduciary Reciprocity is the concrete fiduciary form of defensive acceleration. It seeks existential security not through a permanent moratorium and not through an AI Leviathan, but through a society of personally sovereign digital twins and virtual assistants controlling nearly all consequential generative compute.

Unaccountable AI is not necessarily banned. It is starved, wrapped, audited, and demoted to bounded-tool status. Powerful AI becomes safe enough to use because the right to act through it is routed through fiduciary agents, sovereign stacks, Verifiable Trust Communities, Networked Cooperatives, Cooperative Federations, distributed compute networks, open-source multi-agent workflows, and human-governed institutions.

The winning equilibrium is not one aligned superintelligence. It is a plural society of accountable fiduciary agents making trustworthiness the price of admission to high-value digital life, while replacing financialized platform capitalism with a cooperative economy of negotiated, duty-bound optimization.

Yes — C.18 should make NANDA central, but also argue that **NANDA’s distributed registry approach needs T4AS’s broader ontology**. NANDA is directionally correct: decentralized discovery, authentication, and verifiable metadata are exactly what an agentic web needs. But if the registry only describes vaguely specified “agents,” it will reproduce the same architectural ambiguity that T4AS is trying to eliminate.

Here is a replacement **C.18**.

---

## **C.18 NANDA’s Distributed Registry Is the Right Direction, but Registries Must Cover Every Certifiable Component**

AI governance often emphasizes model registries. A LessWrong / Convergence Analysis proposal describes AI model registries as “a foundational tool for AI governance,” aimed at bringing government insight into frontier models closer to what exists in other high-impact industries. It proposes collecting information such as model architecture, size, compute, training data, and evaluations. ([arXiv](https://arxiv.org/abs/2410.09645?utm_source=chatgpt.com))

That is useful, but insufficient. Model registries answer only one part of the problem. In agentic systems, risk does not live only in the model. It lives in the relationship among models, workflows, tools, roles, workspaces, datasets, actuators, permissions, registries, identities, and deployment configurations.

A model registry can say something about a model. It cannot, by itself, say what the acting system is.

### **NANDA points toward the right registry architecture**

MIT’s **NANDA** project is much closer to the needed direction. NANDA — Networked AI Agents in Decentralized Architecture — is building infrastructure for an “Internet of AI Agents,” including decentralized agent discovery, authentication, communication protocols, verifiable interaction, and behavioral records. MIT’s project page describes NANDA’s decentralized registry system as functioning “like DNS for agents,” enabling discovery, authentication, and verifiable interaction across the network. ([media.mit.edu](https://www.media.mit.edu/projects/mit-nanda/overview/?utm_source=chatgpt.com))

The NANDA Index paper describes the architecture as a way to provide “discoverability, identifiability and authentication in the internet of AI agents,” using a minimal index that resolves to cryptographically verifiable **AgentFacts**. It claims support for schema-validated capability assertions, sub-second revocation and key rotation, multi-endpoint routing, privacy-preserving discovery, and verifiable least-disclosure queries. ([arXiv](https://arxiv.org/abs/2507.14263?utm_source=chatgpt.com))

That is the right direction. Agent societies need distributed discovery. They need cryptographic identity. They need capability assertions. They need revocation. They need privacy-preserving queries. They need registries that do not become centralized choke points.

NANDA’s “quilt” style distributed registry is therefore a promising foundation.

### **The limitation is that “agent” is too poorly specified**

The problem is not the registry idea. The problem is the unit of registration.

NANDA’s current framing is primarily about “agents.” But “agent” is exactly the term that T4AS says has become dangerously ambiguous. T4AS begins from the fact that the industry uses “agent” inconsistently and therefore separates the primitives of an agentic system: Model, Workspace, Workflow, Agent (Live), Agent Role, and Bot/Robot.

That distinction matters because the thing that needs to be discovered, certified, trusted, or refused may not be an “agent” in the colloquial sense.

It may be:

a Model;  
an Agentflow;  
a deterministic Non-Agent Workflow;  
a callable Bot/Robot;  
an Agent Role;  
a Workspace;  
a Workspace actuator;  
a role dataset or knowledge base;  
a policy checker;  
a compliance module;  
a credential issuer;  
a registry endpoint;  
a sandbox;  
a communication protocol;  
or an installed configuration combining all of these.

If registries only name “agents,” they will blur exactly the boundaries that safety requires.

### **Every certifiable thing needs identity, discovery, and certification metadata**

T4AS gives the stronger registry principle: **every certifiable thing should be nameable, discoverable, and referable in logs, certificates, and registry entries.**

T4AS says network-level identity and discovery are necessary so that certification, delegation, and auditability can make sense across system boundaries. It lists identifiers for Workspaces, Agent Roles, State/Backup snapshots, Workflows and Agentflows, Bots, and Live Agent instances.

It also says discovery should cover callable Workflows or Bots, Workspaces, Workflows and Agentflows, Agent Roles where appropriate, and supporting components such as tools, Models, and policies.

This is the necessary extension of NANDA. NANDA’s distributed registry architecture should not merely register “agents.” It should register the components and configurations that make an agentic system safe or unsafe.

A model can be certified.  
A workflow can be certified.  
A workspace can be certified.  
An actuator can be certified.  
A role dataset can be certified.  
A compliance checker can be certified.  
A Bot/Robot can be certified as an installed acting totality.  
A configuration can be certified only under specified embeddedness constraints.

The registry must reflect all of that.

### **AgentFacts are useful, but BotCards and component facts are also required**

T4AS explicitly connects NANDA-style registries to AgentFacts, but narrows their proper role. It says NANDA’s AgentFacts Document can serve as a cryptographically signed “passport” for an **Agentflow**, attesting to composition, certifications, and capabilities. AgentFacts should be issued for Agentflows, not Live Agent instances, because many Live Agents across many Workspaces and Roles can instantiate the same Agentflow.

But an Agentflow is not the acting totality. A callable Bot/Robot is different. For that, T4AS proposes a corresponding **BotCard** to describe an installed Workflow or Bot rather than merely an Agentflow.

That distinction should become central to C.18.

An **AgentFacts** document can answer:

What kind of generative workflow is this?  
What model or sub-agentflows does it use?  
What certifications attach to its generated media outputs?  
What embeddedness constraints apply?

A **BotCard** must answer:

What installed system is callable?  
Which Agentflows and Non-Agent Workflows does it contain?  
Which Workspace does it run in?  
Which Agent Role anchors identity and reputation?  
Which actuators can it invoke?  
Which capabilities are available?  
Which logs are produced?  
Which duties and certifications apply to the acting totality?

And component facts should answer analogous questions for models, tools, workflows, policies, datasets, and workspaces.

Without these distinctions, a registry may produce discoverability without accountability.

### **Registries must carry embeddedness constraints, not just names and capabilities**

The NANDA Index paper’s emphasis on capability assertions and AgentFacts is valuable. But T4AS adds the essential point: certification must be embeddedness-aware.

T4AS says embeddedness is the degree to which a component or framework depends on its containing context: Agent Role, Workspace, parent Workflow, capabilities, data, hardware, or governance. Low-embeddedness components may be broadly certifiable; high-embeddedness systems must be certified in the particular configuration where they operate.

Therefore a registry entry must not merely say:

This agent can summarize documents.

It must say:

This Agentflow is certified for summarization only when instantiated by these Workflows, with these data classes, inside these Workspaces, under these logging and policy constraints.

Or:

This Bot is certified to summarize medical records only when installed in this Workspace configuration, with these actuators disabled, these audit logs enabled, this human approval threshold, and these fiduciary duties active.

This is how registry metadata becomes useful for VFR. A twin does not merely need to discover a counterparty. It needs to know whether that counterparty is safe for this role, this interaction, this data class, this capability grant, and this duty stack.

### **Registries are descriptive inputs, not the final authority**

T4AS also avoids a second mistake: treating discovery metadata as authoritative by itself. It says discovery information is descriptive, not authoritative; it informs decisions about delegation, capability grants, and routing, but the actual decisions are made by Non-Agent Workflows and governance policies.

That is exactly right.

A registry should not be a global oracle of trust. It should be an evidence layer.

A fiduciary twin may consult NANDA-style registries, VTC registries, BotCards, AgentFacts, model certificates, Workspace identifiers, reputation artifacts, trusted peer attestations, and local policies. But the twin’s Workflow still decides whether to proceed, what data to disclose, what capabilities to grant, and which duties or arbitration terms apply.

This prevents the registry from becoming a new platform sovereign.

### **The registry layer is what makes VFR interoperable**

Verified Fiduciary Reciprocity depends on agents being able to ask:

Who are you?  
What are you?  
Who controls you?  
What components compose you?  
What duties bind you?  
What are you certified to do?  
Under which embeddedness constraints?  
What capabilities are you requesting?  
Which registry entries support your claims?  
What logs and recourse exist if something goes wrong?

NANDA provides a plausible distributed infrastructure for answering some of those questions. T4AS provides the missing ontology for answering them correctly.

The combined architecture is:

**NANDA-style distributed registry:** decentralized discovery, resolution, cryptographic metadata, revocation, and capability assertions.  
**T4AS ontology:** precise entities to register: Models, Agentflows, Workflows, Workspaces, Agent Roles, Bots, tools, datasets, policies, compliance modules, and installed configurations.  
**VFR governance:** rules for deciding which registered entities receive data, attention, trust, capabilities, actuation, or high-trust cooperation.

That is the right synthesis.

NANDA is the right registry direction. But VFR requires registry systems to cover every certifiable component of an agentic system, not only poorly specified “agents.” Otherwise the registry becomes another source of misplaced trust: a list of names for things that have not been architecturally understood.

## **C.19 Law Is Necessary but Too Slow; VFR Makes Law-Like Duties Continuous, Negotiable, and Democratic**

Some LessWrong-adjacent responses to Moloch propose law-like structures, registries, legal personhood, or “Themis” as a counter-selection pressure. This is directionally correct. Law is one of civilization’s major anti-Moloch technologies.

Stephen Martin’s **Moloch v. Themis** states the core idea clearly: Moloch is “population selection pressure” where short-term defection outcompetes positive-sum behavior, while Themis changes the game by granting access to a larger resource pool only to actors who accept law-like constraints. In his digital-mind example, legally recognized minds gain enforceable contracts, property, partnerships, and access to major compute/resource holders, while unregulated “wild” minds are left competing over scraps. ([LessWrong](https://www.lesswrong.com/s/EA2uNqKjmu2NzFhRx/p/WQmqGbvDiGbvBW6Wc))

That is the right intuition: cooperation must be made more fit than defection. But law alone is too slow, too coarse, and too external to govern the constant micro-interactions of AI-mediated life. Many consequential decisions occur before courts, regulators, legislatures, or labor boards can see them. By the time formal law intervenes, data may already have leaked, attention may already have been captured, a contract may already have become unfair, a worker may already have lost leverage, or a model-mediated decision may already have shaped institutional reality.

### **VFR moves law-like duties into real-time fiduciary mediation**

The proposed architecture does not reject law. It operationalizes law-like duties at the interface layer.

The **Taxonomy of Duties for Net Fiduciaries** treats fiduciary duties as obligations attached to relationships of trust, extended into digital contexts. The duties include loyalty, care, privacy, consent, security, clarity, corrigibility, transparency, recourse, remediation, and secure inter-fiduciary communication. It also requires fiduciaries to respond to legitimate requests from other fiduciaries, share non-privileged knowledge where appropriate, assist investigations, and facilitate secure delegation.

This means fiduciary AI does not wait for every dispute to become litigation. It brings legal concepts into the moment of action: before data is shared, before attention is routed, before a capability is granted, before a contract is signed, before an employee’s twin is accessed, before a researcher uses patient data, before a platform is treated as trustworthy.

Law remains necessary for enforcement, appeals, liability, public standards, and constitutional rights. But fiduciary agents make law-like expectations present in everyday interaction.

### **Static smart contracts are too brittle for fiduciary relationships**

This is also why rigid smart contracts are often the wrong model. Some agreements can and should execute automatically. But fiduciary relationships are not merely code paths. They are relationships of loyalty, care, changing context, externalities, mutual reliance, and ongoing interpretation.

A static smart contract assumes the future has been adequately specified. Fiduciary relationships assume the opposite: circumstances change, duties interact, parties discover new facts, externalities emerge, bargaining power shifts, and strict execution may become unfair or mutually destructive.

The **Fiduciary Preferences** agreement object therefore includes not only permitted actions, prohibited actions, data classes, capability tokens, and legal forms, but also externality assessment, affected third parties, mitigation covenants, compensation covenants, human approval thresholds, renegotiation triggers, termination conditions, remediation plans, dispute processes, pendulum arbitration venues, post-interaction review, reputation consequences, and duty/covenant improvement proposals.

That is the key move beyond static contracts: the agreement is not only an execution artifact. It is a living fiduciary reasoning artifact.

### **Pendulum Arbitration gives fiduciary agents a fair renegotiation mechanism**

When negotiated duties become contested, the system needs something faster and more context-sensitive than court, but fairer than unilateral enforcement. This is where **Pendulum Arbitration** matters.

Pendulum Arbitration requires each side to submit a proposed resolution, while the arbiter must choose one proposal rather than drafting a compromise. Because extreme proposals are less likely to be selected, both parties are incentivized to submit reasonable, fair offers.

This is especially well-suited to agent disputes. The parties often know the context better than the arbiter: what was intended, what changed, which duties were implicated, what evidence exists, what harms occurred, and what remedy would preserve future cooperation. Pendulum Arbitration forces each side to compress that knowledge into a fair proposal.

The note on Pendulum Arbitration also explicitly contrasts it with rigid smart contracts. It supports **Contextual Digital Contracts** whose terms are interpreted through pendulum arbitration rather than traditional rigid execution, allowing agreements to adapt to changed circumstances. It also integrates reputation consequences, data isolation, and revocation of future privileges into the digital twin ecosystem.

This is the VFR answer to Themis: not law as a distant sovereign, and not code as blind enforcement, but context-aware fiduciary arbitration embedded in the agent society.

### **Cascading Councils supply democratic escalation above private fiduciary bargaining**

Some disputes and harms cannot be resolved by private parties, even with pendulum arbitration. They implicate public policy, collective goods, labor standards, infrastructure, safety rules, AI governance, civil rights, or democratic legitimacy.

This is where **Cascading Councils** enters the legal architecture. Cascading Councils proposes fixed-size, tiered councils with continuous, revocable support, designed to combine direct democracy, representative democracy, and liquid democracy while limiting power concentration.

The model directly addresses failures that matter for AI-era law: power concentration, delegation-chain opacity, cognitive burden, participation inequality, and weak deliberation. It also allows parallel implementation, pilot programs, domain-specific use, and complementary institutions such as deliberative forums, educational resources, monitoring bodies, and judicial oversight.

Digital twins strengthen this structure without replacing human authority. Cascading Councils says twins can continuously evaluate representatives, engage in proxy deliberation, help owners understand when support should shift, assess domain expertise, map arguments, check factual foundations, aggregate preferences, and request explanations — while humans remain the decision-makers.

This gives the system a ladder of escalation:

private fiduciary negotiation;  
pendulum arbitration;  
VTC or cooperative governance;  
twin-mediated collective bargaining;  
Cascading Council deliberation;  
public law and judicial review.

Law becomes continuous without becoming authoritarian.

### **Twin-mediated labor governance replaces one-sided employment contracts with mutual fiduciary bargaining**

Employment is one of the clearest examples of law being necessary but insufficient. Traditional employment contracts are often one-sided, static, opaque, and backed by unequal bargaining power. Workers sign terms they cannot fully evaluate. Employers obtain access to knowledge, likeness, workflow, relationships, and productivity data that may later be used to make the worker redundant.

The Digital Twin paper anticipates this problem directly. In the employment scenario, the contract dictates what access the employer will have to the worker’s digital twin and what happens to mutual data upon severance. The worker’s twin runs on the worker’s hardware and reveals its knowledge base to the employer only in small, relevant parts. This prevents the employer from simply extracting the worker’s data and embedded expertise.

The same passage treats grievance and severance dynamically. The worker has a right to reclaim control of likeness and other protections; the contract includes an approachable grievance process culminating in a variation of pendulum arbitration; contracts judged unfair, unreasonable, or fundamentally undesirable can be rendered moot.

This becomes a new kind of labor governance. The twin “sniffs out disguised downsides,” collaborates with other twins to establish minimal terms, and creates what the paper describes as “employee collective bargaining with cross-industry collaboration.”

This does not eliminate employer interests. It makes them mutual and explicit. Employers need reliability, confidentiality, productivity, security, handoff procedures, and continuity. Employees need loyalty, privacy, attribution, severance rights, limits on data extraction, anti-redundancy protections, grievance processes, and control over likeness and expertise. VFR lets both sides negotiate through fiduciary agents whose duties, records, and arbitration paths are visible.

### **Twin-mediated unions are not just unions with chatbots**

A twin-mediated union is not merely a traditional union assisted by software. It is a network of fiduciary agents continuously comparing terms, identifying disguised harms, proposing minimum standards, gathering reputation artifacts, coordinating bargaining, and routing disputes into arbitration or democratic escalation.

The **Taxonomy of Duties** already includes duties that support this kind of collective fiduciary labor action: duties to provide challenge and recourse, participate in pendulum arbitration, remediate harm, share knowledge where compatible with confidentiality, aid investigations, and provide professional zeal and wise counsel to the beneficiary.

A twin-mediated union could therefore do what traditional labor structures often cannot:

inspect proposed contracts at machine speed;  
compare terms across industries;  
identify exploitative data or likeness clauses;  
coordinate minimum acceptable terms;  
track employer reputation artifacts;  
negotiate severance and transition insurance;  
route disputes to pendulum arbitration;  
escalate systemic issues to Cascading Councils;  
and preserve worker privacy while enabling collective bargaining.

This is law becoming live. Not because courts disappear, but because workers’ fiduciary agents prevent many legal harms from forming in the first place.

### **Mutual duties replace adversarial compliance theater**

The deeper shift is from adversarial compliance to mutual fiduciary bargaining.

An employer should not merely ask: “What can we legally extract?”  
An employee should not merely ask: “What can I get away with?”  
Their twins should ask: “What arrangement lets both parties fulfill their duties better than non-cooperation?”

That question mirrors the core negotiation question in **Fiduciary Preferences**: whether cooperation lets the parties fulfill their duties better than non-cooperation.

This does not make conflict disappear. A fiduciary society still disagrees, bargains, arbitrates, exits, and competes. But its disagreements become more legible, agreements more reusable, harms more remediable, duties more granular, and cooperation more intelligent.

This is the correct response to the LessWrong-adjacent Themis argument. Themis is not wrong to invoke law. But if Themis remains only court, statute, police, and registry, it arrives too late and acts too crudely. VFR brings Themis into the interaction itself: in calling cards, duties, negotiation objects, least privilege, contextual contracts, pendulum arbitration, reputation artifacts, cooperative governance, and democratic escalation.

### **Law is downstream from the governed — so VFR changes the governed**

The **Moloch v. Themis** comment thread contains an important warning: “Law is downstream from the inclinations of the governed — not the other way around.” ([LessWrong](https://www.lesswrong.com/s/EA2uNqKjmu2NzFhRx/p/WQmqGbvDiGbvBW6Wc))

That is exactly why VFR is necessary. Law cannot simply command a low-trust society into high-trust behavior. It must be supported by agents, institutions, records, incentives, reputations, and norms that make legal duties meaningful before enforcement.

VFR changes the governed by giving people fiduciary representatives that can understand duties, track agreements, negotiate terms, remember harms, coordinate with peers, preserve evidence, and escalate disputes. Cascading Councils then gives those citizens a more responsive democratic structure for changing the formal law when the fiduciary layer reveals systemic problems.

Law remains necessary. But it becomes one layer in a living fiduciary governance stack:

**Behavioral Guidelines** supply inherited cooperative norms.  
**Fiduciary duties** make those norms relationship-specific.  
**Contextual Digital Contracts** record negotiated obligations.  
**Pendulum Arbitration** interprets duties when conditions change.  
**Reputation artifacts** make outcomes socially visible.  
**Twin-mediated unions and cooperatives** aggregate bargaining power.  
**Cascading Councils** escalate systemic issues democratically.  
**Courts and statutes** provide public enforcement, appeal, and constitutional backstop.

That is stronger than law alone. It is law made continuous, fiduciary, contextual, democratic, and real-time.

## **C.20 Human Cooperation Is Too Cognitively Expensive at Digital Scale**

Appendix B of the main paper argues that humans are not bad cooperators in general, but unreliable cooperators in the specific settings civilization increasingly requires: large-scale, abstract, evidence-sensitive, pluralistic, long-term, non-tribal cooperation under uncertainty.

This is a crucial addition to Wilberg. Evolutionary game theory explains why cooperation can fail structurally. Appendix B explains why unaided humans often cannot maintain the cooperation structures required.

### **Digital twins are cooperation exoskeletons, not replacements for human judgment**

The main paper’s answer is not that twins should rule humans. Appendix B says explicitly:

> “That does not mean twins should rule humans. It means humans need cooperation exoskeletons.”

This is the right framing for LessWrong audiences. A calculator does not replace mathematical understanding. A bicycle does not replace legs. A fiduciary twin does not replace conscience, consent, democratic legitimacy, or human judgment. It extends the human ability to track evidence, commitments, context, reputation, permissions, and long-term cooperation.

The point is not to outsource moral life to AI. The point is to make human moral agency operational at digital scale.

## **C.21 Myth Motivates, but Machinery Wins**

Wilberg ends **Beyond Moloch** by returning to the mythic register. He says humanity is not merely subject to ultra-powerful gods; instead, humans shape parameters that can “summon either Moloch or the Goddess.” ([LessWrong](https://www.lesswrong.com/posts/PDQ2Ajbpe8cjymn22/beyond-moloch-the-view-from-evolutionary-game-theory))

This is a useful rhetorical bridge. Moloch names the felt experience of being trapped by destructive competition. The Goddess names the hope that cooperation can be made fit.

### **The main paper keeps the myth but grounds it in institutions and interfaces**

The main paper’s conclusion is not that Moloch is defeated by better feelings. It says Moloch is beaten by “a better game.”

That better game is not mystical. It consists of fiduciary duties, sovereign stacks, digital twins, calling cards, provenance, bounded tools, Networked Cooperatives, Verifiable Trust Communities, exit rights, externality scans, and reputational accountability.

The myth is useful because it motivates. The machinery matters because it changes outcomes.

## **C.22 The Comprehensive Response: Make Accountable Cooperation More Fit Than Extraction**

The LessWrong community asks the right questions.

What if Moloch is evolutionary?  
What if good intentions decay under selection pressure?  
What if repeated interaction matters?  
What if cooperators must cluster?  
What if hubs dominate network outcomes?  
What if partner choice depends on exit?  
What if exit is expensive?  
What if cooperator and defector are not clean categories?  
What if global public goods are not pairwise games?  
What if metrics are Goodharted?  
What if fake fiduciaries capture the language?  
What if AI advisors manipulate under the guise of help?  
What if law is necessary but too slow?  
What if governance needs a theory of victory?  
What if unaided humans cannot cooperate at the required scale?

The answer is distributed across the main paper and companion papers, but the answer is coherent.

**Verified Fiduciary Reciprocity** defines the stable strategy.

**Fiduciary Preferences** defines how professed human preferences become duty-compatible cooperation.

**Kwaai’s Personal Agency / VASTI** defines the sovereign personal stack where data, attention, context, and actuation can be protected.

**Digital Twins** defines the personally owned public representative: the aspirational, accountable, world-facing fiduciary agent.

**Taxonomy of Duties for Net Fiduciaries** defines the duty layer: loyalty, care, privacy, clarity, consent, corrigibility, transparency, impartiality, security, records, and contextual interpretation.

**Networked Cooperatives** defines the graph topology for cooperative clustering, portable communities, federations, and trust-chained collective agency.

**OpenVTC / Verifiable Trust Infrastructure** begins the formal implementation path for Verifiable Trust Communities.

Together, these answer Wilberg’s evolutionary challenge.

Moloch wins when extraction, racing, capture, and defection reproduce better than accountable care.

Verified Fiduciary Reciprocity changes what reproduces by changing what receives access.

Unaccountable AI may still exist. But if it cannot obtain raw personal data, trusted attention, private context, actuation authority, group membership, reputational endorsement, or cooperative legitimacy, then its practical power is bounded.

The goal is not to destroy every unaccountable system. The goal is to demote unaccountable systems from sovereign mediators to bounded tools.

The result is not utopia. It is a better game: a society of personally owned fiduciary agents, sovereign personal stacks, verifiable trust communities, and networked cooperatives making accountable cooperation more fit than extraction.

## SOURCES

### \- HERE are the sources of mine used for Generation and Quotation and perhaps a few more relevant links.  [**Verified Fiduciary Reciprocity**](https://docs.google.com/document/u/0/d/1LPoIiN708oiQlNIlDe7gmhcMHeJubunxxBH3nUeGwjI/edit) [**Fiduciary Preferences**](https://docs.google.com/document/u/0/d/1DGCo5GkULqHUrYv7ZeswY9gMc73CKqFhws6lhwka3ks/edit)  

### [**Kwaai’s Personal Agency**](https://docs.google.com/document/u/0/d/1b7POsbgc91RVU9qJs1MBHWIaZJ-nGhz8et58pae0r50/edit)

### [**Personally-Owned Digital Twins**](https://docs.google.com/document/u/0/d/1mtvn0MaFcrjjPRxK0LcmTCZX-2nUDTfFsCZ0Xsbo0YE/edit) [**VASTI (Virtual Assistant and Sliding Tabs Interface)**](https://docs.google.com/document/u/0/d/1yNBX3-QvBExFkpS_A3_Eti3cWwAzQwJfIk5Mt8SC4Zg/edit)

### [**Taxonomy of Duties for Net Fiduciaries**](https://docs.google.com/document/u/0/d/19n6M8RqkEgLS041cuQm3GINUVfU3c3z-N4eiFhEqyG4/edit) 

### [**Taxonomy of Agent Systems**](https://docs.google.com/document/u/0/d/1a-Rn9V4UgtXs9EYniTAyjvG93QfzzenXfUNK3nW_Sss/edit) [**A Negotiable Society of Digital Twins**](https://docs.google.com/document/u/0/d/1sYqM7FWUUCQuVm1Vyaxh17psmktum4A1uXhGuGQcuug/edit)

