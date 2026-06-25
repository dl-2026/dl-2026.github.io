---
permalink: /accepted/
title: "Accepted Papers"
layout: splash
header:
  overlay_image: /assets/images/big.jpg
  overlay_filter: "0.5" # darkens image for better text readability
  overlay_color: "#000" # black overlay (optional)
excerpt: "DL 2026 · July 17-19, 2026 · Lisbon, Portugal"
---
<style>
    .talk {
        background:#eef2ff;
        padding:5px 10px;
        border-radius:12px; 
        font-size:smaller;
}
    .poster {
        background:#fef3e8;
        padding:5px 10px;
        border-radius:12px; 
        font-size:smaller;
}
    .posterdemo {
        background:#e6f4ef;
        padding:5px 10px;
        border-radius:12px; 
        font-size:smaller;
}

details {
    margin-top: 0em;
    margin-left: 0em;
    margin-bottom: 0.8em;
}

summary {
    display: inline;
    cursor: pointer;
}

details div {
    font-size: smaller; 
    margin-top: 0.8em;
}
</style>


### Paper Acceptance Overview
-----
Accepted papers: **35**, comprising 13 extended abstracts and 22 full papers.

### Presentation Format  
-----
Oral presentations: **25** <span class=talk>Talks</span>.  
Poster & demo session papers: **10**, comprising 5 <span class=posterdemo>Posters & Demos</span> and 5 foundational <span class=poster>Posters</span>. 

### List of Accepted Papers (with Abstracts)
-----


<details><summary><span class=poster >Poster</span> OxidOWL: Development and Maintenance of OWL DL Reasoners with Coding Agents. 
<i>Riccardo Sieve</i> 🔍 </summary>  
<div id="id5"> Abstract: Description Logic reasoners enable automated reasoning over ontologies expressed using the Web Ontology Language (OWL). They can be used to infer logical consequences from a set of asserted facts or axioms within an ontology. However, many well known reasoners are currently non-maintained, or are not actively developed. This can lead to unpatched bugs, missing features, or non-adherence to possible new standards that might arise in the future. In this paper, we analyse and show how we can employ coding agents for the development and maintenance of OWL DL reasoners. To this end, we propose OxidOWL, an OWL DL reasoner developed and maintained through coding agents. We validate our approach through thorough testing and compare the proposed approach with existing well-known reasoners. </div>
</details> 

<details> <summary> <span class=posterdemo>Poster & Demo</span> Visualizing HS-Tree-Based Abductive Reasoning: An Educational Tool for Algorithm Exploration. 
<i>Michaela Tóthová, 
Janka Boborová,
Júlia Pukancová,
Jakub Kloc,
Martin Homola. </i> 🔍 </summary>  
<div id="id6"> Abstract: We present the HS-Tree Visualizer application, a visualization tool under development that currently supports displaying MHS and MHS-MXP trees from input JSON files produced by an abduction solver. The application supports step-by-step simulation of the algorithms, interactive manipulation of tree nodes and edges, and the ability to display or hide additional details, including branches that do not lead to explanations. These features make it a useful tool for learning, algorithm analysis, and debugging the underlying solver. In the future, the application will be extended to support additional abduction algorithms, and it also has the potential to be used by other abduction solvers. With further updates, it could even be adapted for other processes that can be represented using a tree/graph structure, as long as a suitable JSON file in the required format is provided.</div>
</details>

<details><summary><span class=talk>Talk</span> Towards Putting Perspective into OWL (Extended Abstract). 
 <i>Lucía Gómez Álvarez, 
 Sebastian Rudolph.</i> 🔍 </summary>  
<div id="id7"> Abstract: Standpoint extensions of KR formalisms have been recently introduced to incorporate multi-perspective modelling and reasoning capabilities. In such modal extensions, the integration of conceptual modelling and perspective annotations can be more or less tight, with monodic standpoint extensions striking a good balance as they enable advanced modelling while preserving good reasoning complexities. This extended abstract reports on a paper published in KR'25 where we consider the very expressive description logics SHOIQBs and SROIQBs, which subsume the popular W3C-standardized OWL 1 and OWL 2 ontology languages, and show that they allow for monodic standpoint extensions without any increase of standard reasoning complexity. We do this by first proving the result for the extension of C2 - the counting two-variable fragment of first-order logic - by monodic standpoints and then by showing how to handle role chain axioms. At the core of our treatise is a polytime translation of formulae in said formalism into standpoint-free C2, requiring elaborate model-theoretic arguments. By virtue of this translation, the NExpTime-complete complexity of checking satisfiability in C2 carries over to our formalism. As our formalism subsumes monodic S5 over C2, our result also significantly advances the state of the art in research on first-order modal logics. We prove that NExpTime-hardness already occurs in much less expressive DLs as long as they feature both nominals and monodic standpoints. We also show that, with inverses, functionality, and nominals present,  minimally lifting the monodicity restriction leads to undecidability.</div>
</details>

<details><summary><span class=posterdemo>Poster & Demo</span> DeLTA: Description Logic–based Text Annotation.
<i>Ildar Baimuratov</i> 🔍 </summary>  
<div id="id8"> Abstract: Enriching an ontology with complex axioms enables the inference of new knowledge, contextualized querying, and consistency checking, but it is error-prone and time-consuming. A further challenge is that domain experts are rarely ontology engineers, while ontology engineers often lack sufficient domain knowledge. This "knowledge acquisition bottleneck" has led to a prevalence of inexpressive ontologies, highlighting the need to facilitate the acquisition of expressive description logic axioms. In this work, we propose a domain-independent text annotation schema that maps directly to OWL DL syntax, enabling the algorithmic generation of expressive axioms from the annotations. Annotated text allows domain experts to participate in the loop, ensuring the trustworthiness of the resulting knowledge base. Additionally, the annotation process can later be automated using NLP once a sufficient number of annotations have been completed. We demonstrate the applicability and scalability of the approach through two distinct use cases: building requirements and scientific claims.</div>
</details>

<details><summary><span class=talk>Talk</span> Tree Description Dependencies.
<i>David Toman, 
Grant Weddell</i> 🔍 </summary>  
<div id="id9"> Abstract: We introduce a general variety of equality-generating dependencies based on tree descriptions (TDs) for an expressive dialect of the FunDL family of description logics called tree description dependencies (TDDs). In general, TDDs enable capturing equality generating dependencies in an ontology. The new capability is tailored to structurally matching parts of structured documents/JSON objects. We show that logical entailment for this new FunDL dialect is complete for EXPTIME if a given ontology appeals to an exclusive use of TDDs, but that logical entailment becomes undecidable when more coarse grained varieties of TDDs (called Path Description Dependencies, PDDs) are simultaneously allowed in the ontology. An extension to a referring expression type language for defining concepts in this description logic to serve as referring expressions that depend on structural identification is also presented and is tied to a diagnosis of a singularity condition for such concepts to logical entailment of TDDs for an ontology.</div>
</details>  

<details><summary><span class=talk>Talk</span> Deontic Defeasible Description Logic.
<i>Giovanni Casini, 
Rafael Penaloza Nyssen,
Thomas Meyer, 
Leendert van der Torre</i> 🔍 </summary>  
<div id="id10"> Abstract: We introduce an extension of Description Logics (DL), appropriate for modelling and reasoning about deontic notions. DLs represent a family of logical systems, most of them corresponding to a specific fragment of first-order logic, developed to reason about taxonomies and ontologies. Starting from defeasible ALC, an extension of the DL ALC which allows us to model and reason about defeasible information (rules that admit exceptions), we show how to modify the semantics in order to also represent and manage conditional obligations and permissions, and we present the correspondent, and easily implementable, decision procedures. Also, we define a semantics combining reasoning about expectations and reasoning about norms, pairing it with corresponding decision procedures.</div>
</details>   

<details><summary><span class=talk>Talk</span> Subsumption for ℱℒ<sub>⊥reg</sub> Is in ExpTime.
<i>Michał Henne, 
Barbara Morawska, 
Paweł Parys</i> 🔍 </summary>  
<div id="id11"> Abstract: A central reasoning task in description logics is concept subsumption, which has been extensively studied, although important open problems remain for certain logics. In this work, we investigate subsumption in the restricted logic FL_⊥reg and related logics FL_reg, FL_⊥, and FL_0. These logics support value restrictions over role names, where the subscript "reg" indicates the use of regular expressions over roles. We show that deciding subsumption between two concept descriptions in FL_⊥reg and FL_reg is PSpace-complete. When subsumption is considered with respect to a TBox (i.e., a set of axioms), the complexity increases to ExpTime-complete. Our results are obtained via a novel reduction to parity pushdown games.</div>
</details>  

<details><summary><span class=talk>Talk</span> QBF Reasoning for Concept Satisfiability via an Optimised Reduction From K.
<i>Momen Hassan, 
Uli Sattler</i> 🔍 </summary>  
<div id="id12"> Abstract: It is well known that satisfiability for the modal logic K, with multiple modalities, is a notational variant of concept satisfiability in the description logic ALC. Likewise, extensions of K are notational variants of more expressive description logics. This close relationship extends to their reasoning tasks and is well understood. The same cannot be said for Quantified Boolean Formulas and Modal/Description Logic: despite their reasoning tasks belonging to the same complexity class, reasoners for QBF and K have been developed and investigated mostly separately. While there have been some attempts at using QBF solvers to solve modal logic formulae, such attempts were made before recent significant optimisations of QBF reasoners and have not resulted in a good understanding of the relationship between measures of difficulty in both logics, particularly the polynomial hierarchy division of classes of modal formulae. We define a translation from satisfiable K formulae to true closed QBF, with an optimisation to close the gap in understanding of how the polynomial hierarchy relates to modal logic - and consequently concept satisfiability in ALC. We empirically evaluate our translation together with a modern QBF reasoner, depQBF, against native state-of-the-art modal logic reasoners. We show that the translation-based reasoner compares very favourably, in some cases vastly outperforming the native reasoners.</div>
</details>  

<details><summary><span class=talk>Talk</span> Two-Variable Logic for Hierarchically Partitioned and Ordered Data (Extended Abstract).
<i>Oskar Fiuk, 
Emanuel Kieroński, 
Vincent Michielini</i> 🔍 </summary>  
<div id="id13"> Abstract: We study Two-Variable Fragment of First-Order Logic, FO2, with certain semantic constraints that model hierarchical data. Our first logic extends FO2 with a linear order < and a chain of increasingly coarser equivalence relations E_1 ⊆ E_2 ⊆ ... . We show that its finite satisfiability problem is NExpTime-complete. We also demonstrate that the weaker variant of this logic without linear ordering posesses the exponential model property. Our second main contribution concerns FO2 extended with a chain of total preorders ⪯ 1 ⊆⪯ 2 ⊆ ... . We prove that it likewise admits an NExpTime-complete finite satisfiability problem. However, we show that the complexity increases to EXPSPACE-complete once access to the successor relations of the preorders is allowed.</div>
</details> 
 
<details><summary><span class=posterdemo>Poster & Demo</span> Introducing DeepEL (Extended Abstract).
<i>Alessandro Longato, 
 Ignacio Huitzil, 
 Rafael Peñaloza</i> 🔍 </summary>  
<div id="id15"> Abstract: Light-weight description logics like EL have been successfully used to represent the terminological knowledge of many application domains. Yet, identifying the characteristics of instances often requires sub-symbolic approaches. We introduce a neuro-symbolic extension of EL which allows for (neural) perception and classification of properties, accompanied by formal (symbolic) reasoning based on these perceptions. Through a prototypical implementation, based on a reduction to logic programming, we show that inferences and learning are effectively achievable. This is an extended abstract for a paper accepted for publication at KR 2026.</div>
</details>  

<details><summary><span class=talk>Talk</span> How Hard is it to Decide if a Fact is Relevant to a Query? (Extended Abstract).
<i>Meghyn Bienvenu, 
 Diego Figueira, 
 Pierre Lafourcade</i> 🔍 </summary>  
<div id="id17"> Abstract: In this extended abstract, we summarize our recent work (to appear at KR 2026) on the complexity of deciding whether a given fact is relevant to a Boolean conjunctive query (CQ), i.e. whether the fact belongs to some minimal subset of the data that makes the query hold. Despite being of central importance to query answer explanation, the combined complexity of deciding query relevance has not been studied in detail, leaving open what makes this problem hard, and which restrictions can yield lower complexity. Relevance has previously been shown to be harder than query evaluation: namely, Sigma^p_2-complete for CQs, even over a binary signature. We further observe that NP-hardness applies already to (acyclic) chain CQs. Our work identifies self-joins (multiple atoms with the same relation) as the culprit. Indeed, we prove that if we forbid or bound the occurrence of self-joins, then relevance has the same complexity as query evaluation, namely, NP (without structural restrictions) and LogCFL (for bounded hypertreewidth classes). In the ontology setting, we establish an analogous result for ontology-mediated queries consisting of a CQ and DL-Lite_R ontology, namely that relevance is no harder than query answering provided that we bound the interaction width (which generalizes both self-join width and a recently introduced ‘interaction-free’ condition). Our results thus provide useful insights into what makes relevance harder than query evaluation and allow us to identify natural classes of queries which admit efficient relevance computation.</div>
</details> 

<details><summary><span class=talk>Talk</span> Neighbourhood Description Logics for Multiperspective Reasoning.
<i>Tiziano Dalmonte, 
 Andrea Mazzullo, 
Rafael Peñaloza</i> 🔍 </summary>  
<div id="id18"> Abstract: Reasoning in presence of multiple viewpoints or approximate concepts is a long-standing challenge for knowledge representation formalisms. In this paper, we introduce ALC^{\lhd\Box}, a description logic extending the classical ALC with two pairs of concept constructors that allow us to talk about objects that ``on some/all accounts, are acknowledged to be $C$'' (with $\lhd C$ and $\Box C$, respectively), as well as ``on some/all accounts, are compatible with being $C$'' (with the duals $\rhd C$ and $\Diamond C$, respectively). Semantically, a function equips each element of the domain with a family of \emph{neighbourhoods}, subsets of the domain that represent multiple, possibly imprecise, or even conflicting, accounts on that element. We show that ALC^{\lhd\Box} concept satisfiability under a knowledge base is reducible in polynomial-time to the same problem for ALC, hence obtaining an ExpTime-completeness result. Moreover, we investigate additional conditions on the neighbourhood function, so to capture natural constraints that can be imposed on the accounts of an object: existence, consistency, partial consistency, correctness, and partial correctness. In all these cases, we show that the (tight) ExpTime upper bound is preserved, by providing reductions to ALC, ALCHI, or the two-variable guarded fragment GF^2.</div>
</details>  

<details><summary><span class=talk>Talk</span> Reaching for the Stars in ℰℒ Concept Learning.
<i>Bente Gortworst, 
Cem Okulmus, 
Magdalena Ortiz, 
Anni-Yasmin Turhan</i> 🔍 </summary>  
<div id="id19"> Abstract: Learning concepts from data examples is an intensively investigated topic in description logics (DLs), in particular for the EL-family. So far, hardly any of these works on concept learning consider the Kleene star to express the (reflexive) transitive closure of roles. However, the star plays a central role in some closely related settings, like learning shape expressions in graph constraint languages such as SHACL, and learning graph queries from graph data. As a first step towards developing techniques for learning SHACL shape expressions, we consider learning from examples (aka the fitting problem) for the logic EL^*, which extends EL by the reflexive transitive closure of named roles. In contrast to EL, the DL EL^* can express a limited form of disjunction that can result in more informative fittings.  By adapting the automata-based techniques for EL, we obtain complexity bounds for deciding existence of EL^* fittings that coincide with those for EL. We also develop an algorithm for computing most specific fittings in EL^*.</div>
</details>  

<details><summary><span class=poster>Poster</span> Formal Reasoning with Learned Predicates (Extended Abstract).
<i>Gianluca Cima, 
Marco Console, 
Laura Papi</i> 🔍 </summary>  
<div id="id20"> Abstract: Machine Learning (ML) models are regularly employed in diverse application domains to support decision-making processes. In this context, the knowledge is induced by the ML models. Combining this learned knowledge with intensional knowledge specified by logic-based formalisms would be highly beneficial to these processes. In this paper we present our recent work on this subject, describing a framework that combines these two forms of knowledge and enables formal reasoning. The framework is based on the novel notion of Hybrid Knowledge Base (HKB), which consists of an ontology and a set of ML binary classifiers. The ontology defines the intensional knowledge over the domain, while the ML classifiers implicitly define the extensional knowledge. Specifically, a HKB combines these two components by associating each predicate of the ontology with a classifier, which virtually populates the predicate with positively classified instances. A further contribution of our work is the study of the query answering task. In particular, we provide its computational complexity analysis for ontologies specified in (the Description Logic counterpart of) RDFS, and binary Multi-Layer Perceptrons.</div>
</details>  

<details><summary><span class=posterdemo>Poster & Demo</span> Towards Visual Decision Support in Interactive Repair.
<i>Christian Alrabbaa, 
Franz Baader, 
Raimund Dachselt, 
Pratistha Kansakar, 
Julián Méndez, 
Afshin Zanganeh</i> 🔍 </summary>  
<div id="id21"> Abstract: Whether carefully engineered or automatically learned, ontologies may still contain modeling errors. The problem of repairing Description Logic (DL) ontologies has been extensively studied, with a primary focus on minimizing information loss. A given ontology may have many different repairs that minimize information loss, and thus domain knowledge is needed to find the one that is correct in the given application domain. Consequently, interactive approaches have been proposed that involve users in the repair process, with the aim of reducing the number of user decisions required to obtain a valid repair. These methods usually assume that users are always able to make definitive decisions. However, users may face situations where the semantics of axioms alone are insufficient for them to determine whether an axiom should be retained or removed. In this work, we introduce an interactive repair approach that not only guides users through the exponential space of possible repairs while minimizing the decisions required, but also provides support in cases of uncertainty. Our approach augments the repair process with several decision-support features, including information about important entailments, distance to reachable repairs, and structural differences in the class hierarchy. We have implemented this approach both as a standalone command-line tool and as a web-based interactive visualization prototype that provides analytical capabilities not easily achievable otherwise.</div>
</details>  

<details><summary><span class=talk>Talk</span> Using ASP(Q) to Handle Inconsistent Prioritized Data (Extended Abstract).
<i>Meghyn Bienvenu, 
Camille Bourgaux, 
Robin Jean, 
Giuseppe Mazzotta</i> 🔍 </summary>  
<div id="id22"> Abstract: This extended abstract summarizes our KR’26 paper, where we explore the use of answer set programming (ASP) and its extension with quantifiers, ASP(Q), for inconsistency-tolerant querying of prioritized data. We consider the variants of three well-known semantics (AR, brave and IAR) that use three notions of optimal repairs (Pareto-, globally- and completion-optimal), and for which query answering is in the first or second level of the polynomial hierarchy for a large class of logical theories. Notably, this paper presents the first implementation of globally-optimal repair-based semantics, as well as the first implementation of the grounded semantics, which is a tractable under-approximation of all these optimal repair-based semantics. Our experimental evaluation sheds light on the feasibility of computing answers under globally-optimal repair semantics and the impact of adopting different semantics, approximations, and encodings.</div>
</details>  

<details><summary><span class=talk>Talk</span> Temporal ℰℒ and Equations over Sets of Integers.
<i>Anton Gnatenko, 
Roman Kontchakov</i> 🔍 </summary>  
<div id="id23"> Abstract: We study TEL^o , an extension of the description logic EL with the temporal operator O^n (‘in n instants from now’),by encoding its canonical models with sets of integers. We characterise reasoning in TEL^o in terms of operations on such sets and arrive at a correspondence between (fragments of) TEL^o and (classes of) resolved systems of equations over sets of integers. This generalises the previously established link between TEL^o and formal grammars, leading to simpler proofs of known results as well as yielding new results.</div>
</details>  

<details><summary><span class=talk>Talk</span> ontopEO: VKGs over Earth Observation Data (Extended Abstract).
<i>Albulen Pano, 
Davide Lanti, 
Diego Calvanese, 
Piero Campalani, 
Alexander Jacob, 
Alessandro Mosca</i> 🔍 </summary>  
<div id="id24"> Abstract: Earth Observation (EO) data publication and dissemination continues to grow driven by the need to consistently monitor the earth in times of climate change. openEO is one of the most well known APIs to query and process EO data and is operationally available on many EO cloud platforms such as the Copernicus Data Space Ecosystem or Destination Earth. To be truly valuable, EO data often needs to be combined with other data sources, notably relational databases. Knowledge graphs offer a way to bridge the semantic gap between EO data and these other sources. An unsolved issue with this solution is that the execution of integrated queries can be costly due to the enormous volume of EO data. In this paper, we tackle this challenge through the use of Virtual Knowledge Graphs — a paradigm that presents data to end-users as a knowledge graph, while being kept its original sources and formats. Our approach is prototyped and evaluated against multiple real-world openEO examples.</div>
</details>  

<details><summary><span class=talk>Talk</span> Finite Characterizations of ℰℒ Ontologies and Concept Inclusions.
<i>Maurice Funk, 
 Simon Hosemann, 
 Carsten Lutz</i> 🔍 </summary>  
<div id="id25"> Abstract: We study the problem of finitely characterizing ontologies, concept inclusions, and concept equivalences, all formulated in the description logic ℰℒ, in terms of positive and negative examples. We consider two different kinds of examples: finite interpretations and finite pointed interpretations, with the expressive power of the latter being higher than that of the former. We prove that non-tautological concept inclusions and concept equivalences are characterizable by a finite set of pointed examples, and that acyclic inclusions and equivalences are even characterizable by a finite set of non-pointed examples. For ontologies, in contrast, finite characterizability fails even for pointed examples. This leads us to consider the important class of left-atomic ontologies, where only concept names can appear on the left side of concept inclusions and equivalences. There, finite characterizability in terms of pointed examples is regained.</div>
</details>  

<details><summary><span class=poster>Poster</span> Modeling Bias in Machine Learning with Description Logics and Epistemic Modalities.
<i>Mattia Petrolo, 
Ekaterina Kubyshkina</i> 🔍 </summary>  
<div id="id26"> Abstract: The identification and mitigation of bias in machine learning systems requires a precise formal representation of the norms against which inferences are evaluated. Formal ontologies provide a natural foundation for this task. In this work, we develop a Description Logic–based general formalization of the structure underlying several types of bias, with explicit attention to the epistemic states of agents. First, we employ the Description Logic ALC to axiomatize the ontological structure that encodes the normative conditions under which an inference counts as biased or unbiased. Second, we provide a translation of the ALC formalization into a first-order modal framework enriched with necessity and knowledge operators. This step allows us to integrate ontological constraints with representations of agents' epistemic attitudes, thereby connecting DL-based knowledge representation with epistemic reasoning. The combined framework makes it possible to characterize formally the epistemic conditions under which agents may generate biased inferences and to distinguish them from configurations in which bias cannot arise.</div>
</details>

<details><summary><span class=talk>Talk</span> Towards Monitoring of Patients with Bipolar Disorder (Extended Abstract).
<i>Greta Adamo, 
Roman Kontchakov, 
Davide Lanti, 
Kajsa A. Pedersen, 
Andrey Rivkin</i> 🔍 </summary>  
<div id="id27"> Abstract: Bipolar disorder is a condition characterised by episodes of extreme mood fluctuation. Effective treatment typically includes psychoeducation, which aims to equip patients with the knowledge needed to make informed decisions that can influence the course of their illness. Key to this process is the ability to monitor the patient’s behaviour (both by patients themselves and involved healthcare specialists) in order to recognise early signs of future episodes. To support this monitoring task, we propose a framework grounded in medical ontologies and metric interval temporal logic (MITL). The framework enables monitoring of patient behaviour and the identification of emerging episodes based on behavioral patterns and established clinical guidelines. This paper outlines the formal foundations of the framework and describes future steps towards its adoption in practice.</div>
</details>  

<details><summary><span class=talk>Talk</span> Coherence Update Semantics for Horn DL-Lite through Stratified Datalog<sup>¬</sup> Rewriting.
<i>Stefan Borgwardt, 
 Duy Nhu</i> 🔍 </summary>  
<div id="id28"> Abstract: We investigate a formula-based approach for updating ABoxes in DL-Lite (ℋℱ) horn, a description logic that enjoys a low computational complexity of reasoning. Specifically, we extend the existing coherence update semantics from DL-Lite (ℋℱ) core to deal with conjunctions on the left-hand side of TBox axioms, which introduce ambiguity in the update result. We address this problem by proposing the new prioritized coherence update semantics that employs rankings over conjuncts to select among competing updates while preserving the central properties of minimal change, syntax independence, and uniqueness. We further show that updated ABoxes can be computed via a stratified Datalog¬ program based on a novel consequence-based calculus. The approach runs in polynomial time, matching the complexity of standard reasoning in DL-Lite (ℋℱ) horn.</div>
</details>  

<details><summary><span class=talk>Talk</span> In the Heart of the Beholder: User-Tailored Explanations for Description Logics.
<i>Stefan Borgwardt, 
Anke Hirsch, 
Nina Knieriemen, 
Alisa Kovtunova</i> 🔍 </summary>  
<div id="id29"> Abstract: Many techniques have been developed to explain logical reasoning, such as proofs or abduction. However, such methods are useful mainly for experts in logic, e.g., for debugging ontologies. For actually explaining logical consequences and missing consequences to end users of logic-based systems, e.g., in the Semantic Web, it is necessary to study how to adapt and present such explanations in an understandable way. We report on a series of user studies investigating both entailment explanations via proofs and missing entailment explanations via abduction and counterexamples in the context of Description Logic (DL) ontologies. For the former, we assess the influence of prior knowledge on the necessary explanation granularity; for the latter, we compare the efficacy of abductive versus counterexample-based approaches. While we did not find objectively quantifiable results, we analyse and discuss the results of detailed qualitative user interviews, and extract recommendations for executing user studies on logical reasoning systems.</div>
</details>  

<details><summary><span class=talk>Talk</span> Baby Steps Towards Finite Satisfiability For LoopPDL.
<i>Bartosz Bednarczyk, 
Mikołaj Swoboda</i> 🔍 </summary>  
<div id="id30"> Abstract: Propositional Dynamic Logic (PDL), known in the Description Logic community as ALCreg, is a well-established modal logic of programs. To increase its expressive power, several extensions have been proposed. One such extension is the loop operator, which expresses that an element can reach itself via a path defined by a regular expression. Although the satisfiability problem for LoopPDL is well understood, the decidability of its finite satisfiability problem has remained open for over 40 years. Our ongoing work aims to resolve this question. While a full solution is still pending, we have obtained some results of independent interest. In this workshop paper, we present a simplified version of our approach, applied to a logic with loops restricted to atomic roles and their transitive closures. </div>
</details>  

<details><summary><span class=poster>Poster</span>  Preferential Temporal Description Logics with Typicality, weighted KBs and preference combination.
<i>Mario Alviano, 
Laura Giordano, 
Daniele Theseider Dupré</i> 🔍 </summary>  
<div id="id31"> Abstract: In this paper we study a preferential temporal description logic with typicality, which allows for defeasible reasoning in a temporal description logic. We consider an encoding of preferential temporal description logics with typicality into temporal extensions of ALC, based on Linear Time Temporal Logic, a result which extends to the multi-preferential case. For the multi-preferential case, we revisit a previous semantics of weighted knowledge bases by considering preference combination.</div>
</details> 

<details><summary><span class=talk>Talk</span> Introducing Prism Embeddings: A New Family of Geometric Ontology Embeddings.
<i>Giuseppe Federico,
Mena Leemhuis,
Oliver Kutz</i> 🔍 </summary>  
<div id="id32"> Abstract: One way of enhancing link prediction in knowledge graphs in an interpretable and trustworthy way is to use ontology embeddings. These embeddings translate a knowledge graph together with its background ontology into a vector space by representing concepts as convex sets and logical operators between these concepts as geometric operations between the resp. sets. This allows for using both geometric regularities and background knowledge for learning. Some fragments of the description logic ℰℒ++ such as ℰℒℋ𝒪(○)^\bot are particularly well-suited as a basis for an embedding, as they offer a good trade-off between expressiveness and complexity. One popularapproach for embedding these ontologies is to interpret concepts as boxes in some R^n. Although box embeddings proved to be particularly useful in this context, they are not able to represent every ontology correctly. In this work, we open the door to a new geometric framework by introducing prism embeddings. Firstly, we show that prisms do not suffer from the same restrictions as boxes. To illustrate this advantage, we present concrete ontology examples that are problematic for box embeddings but can be represented using prisms. Secondly, we show that prism embeddings extend box embeddings in the sense that each box interpretation of an ℰℒℋ𝒪(○)^\bot ontology induces a prism interpretation, though possibly at the cost of an increase in dimensionality of at most two. Finally, we discuss the usage of prism embeddings in practice by sketching adaptations of implementations of box-based embedding approaches to the prism case.</div>
</details>  

<details><summary><span class=talk>Talk</span> LPX-AbPoint: Abduction and Pinpointing for Explaining Link Predictions on DL Knowledge Graphs.
<i>Roberto Barile, 
 Claudia d'Amato, 
Nicola Fanizzi</i> 🔍 </summary>  
<div id="id34"> Abstract: The need for explanations to predictions in knowledge graphs is increasing because they are generally computed via embedding-based methods that are efficient, but do not explain predictions. Many explanation methods rely on axioms in the knowledge graph that are incomplete, thus often making the explanations incomplete. One way to address this gap is to consider, for explanations, hypothetical knowledge at the schema or assertion level. However, methods based on hypothetical assertions often ignore existing facts. Conversely, approaches that enrich explanations via rule learning typically disregard the available schema. We propose LPX-AbPoint, the first method using a combination of abduction and pinpointing techniques to compute explanations consisting of both schema axioms and existing or hypothetical assertions. We present a comparative empirical study showing that our method produces more useful explanations than approaches relying solely on observed knowledge, while remaining complementary to rule learning techniques.</div>
</details> 

<details><summary><span class=talk>Talk</span> A Horn Extension of DL-Lite with NL data complexity.
<i>Janos Arpasi, 
Bartosz Jan Bednarczyk, 
Magdalena Ortiz</i> 🔍 </summary>  
<div id="id35"> Abstract: The literature on ontology-mediated query answering (OMQA) has been shaped by two key results: first-order rewritability for DL-Lite, and PTime hardness of data complexity for essentially every description logic beyond it. This has effectively positioned DL-Lite as the only practical choice for query rewriting, restricting OMQA solutions to first-order queries and ontologies that can be rewritten into them. This AC0--PTime dichotomy is especially limiting if we consider that OMQA targets graph-structured data, and that standard graph query languages (including the recent ISO standards GQL and SQL/PGQ) are typically NL-complete. Towards identifying a rich Horn DL that can be rewritten into graph query languages and that can still express many ELI and DL-Lite ontologies, we introduce a stratification mechanism for ELI^\bot that controls the interaction between conjunction and recursion. In this way, we obtain ELI^\bot_\preceq, a description logic that strictly extends the core DL-Lite, supports reachability axioms and restricted conjunction, and allows for reasoning in NL. We establish the NL upper bound via a rewriting into nested two-way regular path queries, a fragment of GQL,  providing initial evidence that our ontology language is a promising candidate for extending OMQA to graph query languages.</div>
</details> 

<details><summary><span class=posterdemo>Poster & Demo</span>  Optimization and Empirical Evaluation of the CATS ABox Abduction Solver (Extended Abstract).
<i>Janka Boborová, 
 Jakub Kloc, 
Martin Homola, 
Júlia Pukancová </i> 🔍 </summary>  
<div id="id36"> Abstract: CATS is a JFact-based ABox abduction solver that implements three classical complete approaches: Reiter’s minimal hitting set algorithm and its more recent variants HS-Tree and RC-Tree. In addition, it provides fast but incomplete methods, namely QuickXplain and MergeXplain, as well as hybrid variants in which the complete algorithms are ``boosted'' using MergeXplain. This hybrid strategy is theoretically motivated and is expected to provide significant performance advantages for specific classes of inputs, as suggested by earlier preliminary results. In this work, we report on the recently implemented optimizations and on the first empirical evaluation conducted on three real-world ontologies, enabling a comparison of all eight implemented algorithms. Among other insights, it shows a decisive advantage of the hybrid methods over all three baselines on all classes of inputs.</div>
</details> 

<details><summary><span class=talk>Talk</span> ProofTeller: Exposing Recency Bias in LLM Reasoning and Its Side Effects on Communication (Extended Abstract).
<i>Mayank Jobanputra, 
Alisa Kovtunova, 
Brisca Balthes, 
Fedor Grigoryevich Pogulskiy, 
Yifan Wang, 
Stefan Borgwardt, 
Vera Demberg</i> 🔍 </summary>  
<div id="id37"> Abstract: This abstract is for a paper published in 2025 in the proceedings of the 14th International Joint Conference on Natural Language Processing and the 4th Conference of the Asia-Pacific Chapter of the Association for Computational Linguistics, and we extend it here with a new study that closes the gap with previous research. Large language models (LLMs) are increasingly applied in domains that demand reliable and interpretable reasoning.  While formal reasoning methods can generate correct proofs, these proofs are often inaccessible to non-expert users.  This raises a natural question: Can LLMs, when given a proof, faithfully interpret its reasoning and communicate it clearly?  Recently, we have introduced ProofTeller, a benchmark that evaluates this ability across three tasks: (1) identifying key proof steps,  (2) summarizing the reasoning, and (3) explaining the result in concise natural language. The benchmark covers three domains: Biology, Drones, and Recipes, representing scientific, safety-critical, and everyday reasoning scenarios. We find a consistent near-conclusion bias: LLMs tend to focus on steps closest to the final proof conclusion rather than on the most informative ones. A targeted human study confirms that explanations based on such steps are rated less appropriate for end users. These findings indicate that even when reasoning is provided, current LLMs face challenges in communicating key information in a useful manner, highlighting the need for LLMs that can communicate important details reliably.</div>
</details>  

<details><summary><span class=talk>Talk</span> Will My Favorite Chases Terminate if Evaluating Conjunctive Queries Does? One Does Not Simply Decide This (Extended Abstract).
<i>Lucas Larroque, 
Quentin Manière</i> 🔍 </summary>  
<div id="id39"> Abstract: This extended abstract summarizes our recent contribution, currently under double-blind review at IJCAI'26, in which we ask: Within a class of existential rules that supports decidable query entailment, do the usual abstract classes become concrete? We answer in the negative for classes based upon the termination of all classical chase variants and for the bts class. This explains the necessity of diverse, class-specific techniques for proving chase termination, as query entailment offers no systematic tool for this purpose.</div>
</details>  

<details><summary><span class=talk>Talk</span> Revisiting Conjunctive Query Entailment for S (Extended Abstract).
<i>Yazmin Ibanez-Garcia, 
Jean Jung, 
Vincent Michielini, 
Filip Murlak</i> 🔍 </summary>  
<div id="id40"> Abstract: We clarify the complexity of answering unions of conjunctive queries over knowledge bases formulated in the description logic S, the extension of ALC with transitive roles. Contrary to what existing partial results suggested, we show that the problem is in fact 2ExpTime-complete; hardness already holds in the presence of two transitive roles and for Boolean conjunctive queries. We complement this result by showing that the problem remains in coNExpTime when the input query is rooted or is restricted to use at most one transitive role (but may use arbitrarily many non-transitive roles).</div>
</details> 

<details><summary><span class=talk>Talk</span> The More the Merrier: Combining Properties for ABox Abduction under Repair Semantics for ℰℒ<sub>⊥</sub>.
<i>Anselm Haak, 
 Patrick Koopmann, 
Yasir Mahmood, 
Anni-Yasmin Turhan</i> 🔍 </summary>  
<div id="id41"> Abstract: Abduction is a central approach to explain missing entailments from a knowledge base by providing a hypothesis, that would, if added to the knowledge base, make the missing entailment become true. Abduction under repair semantics has recently been investigated in detail, where several desirable properties and optimality criteria were considered, such as signature-restrictions and minimality in size  and of introduced conflicts. Naturally, hypotheses that satisfy more than one of these properties or combine a property with an optimality criterion would be even more desirable for applications.  So far, such hypotheses have not been investigated in the literature.  In the present paper, we consider the ABox abduction problem for hypotheses satisfying more than one property or additional optimality criteria, for EL_bot under brave and AR semantics. Our main observation is that often requiring additional properties for hypotheses does not lead to an increase of complexity.</div>
</details>  

<details><summary><span class=poster>Poster</span> BoxLitE: A Faithful Knowledge Base Embedding Based on Convex Optimization (Extended Abstract).
<i>Bruno F. Lourenço, 
Hesham Morgan, 
Ana Ozaki, 
Aleksander Pavlovic, 
Emanuel Sallinger</i> 🔍 </summary>  
<div id="id43"> Abstract: Knowledge base (KB) embeddings aim at combining the capability of classical knowledge graph embeddings to generalize the information present in facts, the ABox, with conceptual knowledge represented in an ontology language, the TBox. Several authors have recently explored the idea of mapping concepts to convex regions in a vector space. This is useful to represent hierarchies, typically present in TBoxes, since more general concepts can be mapped to larger regions, containing those regions associated with more specific concepts. However, the power of convexity is rarely leveraged during the actual learning tasks. Here, we introduce BoxLitE, a KB embedding model for DL-Lite that allows for convex optimization. We show that for any satisfiable DL-Lite KB, there is a BoxLitE embedding that is a weakly faithful model. As a proof of concept, we show how to formulate the KB embedding task as a convex optimization problem and how to obtain embeddings with such desirable faithfulness properties.</div>
</details>  

<details><summary><span class=talk>Talk</span> Finding New Boxes for the Diamonds: On the Behavior of Convex Modal Operators for Temporal Description Logics.
<i>Stefan Borgwardt,
Alisa Kovtunova</i> 🔍 </summary>  
<div id="id44"> Abstract: Temporal extensions of description logics often lead to a substantial increase in the complexity of reasoning. Nevertheless, tractable extensions of ℰℒ have been developed by restricting the occurrences of temporal concepts. One can even add so-called convex metric temporal diamond operators to ℰℒ, if they are only allowed to occur on the left-hand side of concept inclusions. In this paper, we consider the dual convex box operators for the first time, and investigate the behavior of complex temporal formulas in which convex diamond and box operators can be combined via composition, union and intersection. We demonstrate the intricate interplay between these operators, and present decision procedures for checking subsumption between complex temporal formulas.</div>
</details> 

*<span style="color:gray; font-size:smaller;">(published on May 22, 2026)</span>*
{: .text-right}

