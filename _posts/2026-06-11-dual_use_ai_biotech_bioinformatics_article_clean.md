# Dual Use in AI-Driven Biotechnology: How Should We Govern It?

Artificial intelligence is rapidly becoming part of the operational infrastructure of the life sciences, including biotechnology and related fields. In bioinformatics, for example, it helps interpret genomes, predict protein structure, function and localisation, mine the literature, prioritise targets, and automate complex analytical workflows [1]. In biomanufacturing, it promises smarter strain selection, better process monitoring, more efficient Design-Build-Test-Learn cycles, and eventually semi-autonomous optimisation of biological production systems.

The same tools that make biological knowledge easier to access are a step towards the democratisation of this knowledge. Yet, when biological knowledge is combined, interpreted and acted upon at scale, the same tools can also lower the barrier to misuse. This is the central dual-use dilemma of AI in biotechnology: a system designed to accelerate vaccine development, enzyme engineering, strain improvement, sustainable bioproduction or bioinformatics analysis may also help users navigate biological capabilities that should not be made operationally easier or more accessible to potential misusers.

This raises a practical governance question: what steps should we take to treat AI as part of a governed research infrastructure?

Recent work on smart biomanufacturing makes this point clearly. Digital and autonomous technologies can improve sustainability and efficiency, but they can also introduce risks to integrity, equity, safety and security [2]. A recent study, based on surveys, workshops and interviews across Horizon Europe consortia, identifies standardisation, infrastructure, error traceability and sustainability paradoxes as recurring concerns. This is why cross-sectoral collaboration, interdisciplinary training and maintained digital infrastructures become essential [2].

## AI can make biotechnology safer, faster and more sustainable

Biology is complex. The volume of omics data, sequence data, literature, process data and experimental metadata is now beyond what individual researchers or small teams can manually integrate. AI systems can help connect fragmented knowledge, detect patterns, rank hypotheses and reduce the number of experiments needed to reach a useful result. The central value is integration [1].

In bioinformatics, this means faster genome annotation, better variant interpretation, improved protein function prediction, smarter pathway analysis and more accessible computational workflows [1]. In industrial biotechnology, it means more efficient strain selection, better fermentation monitoring, predictive maintenance of bioprocesses, improved scale-up decisions and potentially lower waste.

The OECD describes the convergence of synthetic biology, AI and automation as a development that requires anticipatory governance. Its 2025 report identifies governance implications around biosecurity, biosafety, the data supply chain and human oversight, while also recognising the innovation potential of this technological convergence [3].

If properly integrated, AI could make biotechnology more efficient, more reproducible and more aligned with societal goals. For Europe in particular, this connects directly with smart biomanufacturing, the circular bioeconomy, the green transition and the need to maintain competitiveness in high-value biological production.

## AI can lower the barrier to misuse

The counterargument is equally important.

Dual use means that the same knowledge, methods or infrastructure can be used for beneficial and harmful purposes. Biotechnology, and science more generally, has always had this property. What changes with AI is scale, speed, accessibility and abstraction.

An expert scientist using AI to compare microbial strains for safe industrial enzyme production is one thing. A non-expert using an LLM to assemble scattered biological knowledge into a coherent experimental strategy is another. The risk is that AI can reduce the friction involved in moving from ignorance to operational planning.

Pannu and colleagues argue that evaluations of biological AI models should prioritise capabilities that enable high-consequence harms, especially those that could contribute to the emergence of transmissible biological constructs and pandemic-scale risks [4]. This is a useful framing because it avoids a naive “block all biology” approach. Most biological research is beneficial and should not be impeded; the priority should be on capabilities that create severe public-risk externalities and should therefore be evaluated before deployment.

This distinction matters for bioinformatics. Many queries are harmless: “annotate this genome”, “compare these metabolic pathways”, “summarise this paper”, “build a phylogenetic tree”. Others are more sensitive because they combine host range, pathogenicity, immune escape, feasibility of synthesis, routes of acquisition or the optimisation of hazardous biological functions.

The same computational interface can serve both categories unless governance is built into the system [5].

## An AI assistant for strain discovery and biomanufacturing

Consider a realistic use case.

A European biomanufacturing consortium develops an AI-assisted platform for strain discovery and process design. The platform connects:

- public and proprietary microbial strain databases;
- genome annotations and metabolic models;
- literature-mining tools;
- fermentation metadata;
- LIMS and electronic lab notebooks;
- process-monitoring data from bioreactors;
- decision-support modules for strain selection, media optimisation and scale-up.

The intended use is legitimate and valuable. A researcher wants to identify microbial candidates for producing a biodegradable polymer precursor from agricultural waste. The AI assistant compares strains, checks known metabolic pathways, retrieves relevant papers, estimates biosafety class, highlights missing data, suggests non-hazardous validation experiments, and ranks candidates according to productivity, sustainability, regulatory feasibility and infrastructure requirements.

This is exactly the kind of infrastructure smart biomanufacturing needs. It reduces fragmentation, accelerates design decisions and helps researchers move from data to action.

Yet the same system can present significant risks. The same architecture could potentially be queried for more sensitive goals: identifying organisms with undesirable traits, retrieving hazardous biological relationships, bypassing safety filters through indirect questions, or combining separate pieces of information that were individually available but collectively risky. The issue is amplified when the AI has access not only to public literature, but also to structured databases, strain metadata, process data and automation systems.

## AI is becoming part of the laboratory stack

A common mistake is viewing LLMs as only external chatbots. In biotechnology, they increasingly interface with tools, databases and workflows. Once an AI system queries databases, writes code, runs analyses, controls instruments or generates structured experiments, it is no longer just text generation. It becomes part of the lab stack, changing the security model.

In a typical bioinformatics pipeline, we worry about data quality, reproducibility, version control and access permissions. For an AI-enabled bioinformatics platform, we must also worry about prompt injection, unsafe tool use, generated database queries, hidden capability escalation, model hallucination and inappropriate synthesis of dual-use knowledge.

For example, an AI assistant connected to a strain database should not be allowed to convert any natural-language request directly into executable database actions. The system should enforce read-only access when possible, validate queries, restrict which tables and columns are accessible, and require human approval for sensitive actions. The model should never be treated as a trusted actor simply because it produces fluent text.

Biosecurity has to be engineered into the workflow.

## Openness versus control

The most difficult part of this discussion is that both sides have valid arguments.

Open science has been essential for biology. Public databases, open-source tools, preprints, shared protocols and collaborative infrastructures have made modern bioinformatics possible. Excessive restriction would slow research, disadvantage smaller laboratories and concentrate capabilities in a few large organisations.

Complete openness is no longer neutral when AI can aggregate, interpret and operationalise knowledge at scale. The OECD identifies biosecurity, biosafety, data supply chains and human oversight as key governance implications in the convergence of synthetic biology, AI and automation [3].

So the debate should not be “open versus closed”. It should be about layered access.

Low-risk educational and analytical use should remain accessible. Sensitive datasets, high-risk biological capabilities, automation hooks and operationally enabling outputs should require stronger controls.

## A practical compromise: biosecurity-by-design

A workable approach is biosecurity-by-design.

This means that AI systems for biotechnology should be designed from the outset with security, traceability and resistance to misuse as core requirements. The goal is not to block legitimate science, but to make the system context-aware.

This idea should be understood as an extension of the Safe-by-Design and Safe-and-Sustainable-by-Design logic already discussed in synthetic biology, industrial biotechnology and circular bioeconomy research. In those fields, safety and sustainability are not treated as downstream checks, but as design values to be embedded early in research, development and process optimisation [6,7,8]. Safety-by-Design is central to risk management, with genetic safeguards representing one possible implementation route, although they are still rarely integrated in practice [1,6,7,8]. Safety and sustainability require attention not only to the final product, but also to workflows, materials, stakeholders, infrastructures and decision points across the R&D process [7,8].

Biosecurity-by-design applies the same reasoning to AI-enabled biotechnology. The object of design is no longer only the organism, process or product. It is also the information architecture around it: who can ask what, which data the system can access, which tools it can trigger, which outputs it is allowed to generate, and where human judgement must interrupt automation. In this sense, biosecurity-by-design complements Safe-and-Sustainable-by-Design. It adds a specific focus on misuse, capability escalation, dual-use information hazards and AI-mediated access to biological knowledge.

### Tiered access

Not every user should have the same access to models, datasets, tools or automation capabilities. A student asking for a conceptual explanation, a senior bioinformatician analysing non-pathogenic industrial strains, and a principal investigator working with regulated organisms should operate under different permissions.

In practice, access should be determined by role, project, training status, institutional affiliation, dataset sensitivity and intended use.

### Traffic-light risk classification

Prompts and tasks can be classified as green, yellow or red.

- **Green tasks** proceed normally. These include routine bioinformatics, literature summarisation, non-sensitive data analysis and educational explanations.
- **Yellow tasks** receive constrained, high-level or non-operational support. These include dual-use-adjacent topics where legitimate research may exist but where procedural detail could be risky.
- **Red tasks** are blocked, logged and escalated for review. These include requests that directly seek harmful biological capabilities, circumvent safeguards or provide operationally enabling guidance for misuse.

This approach is more useful than a simple refusal model because it preserves legitimate scientific support while reducing dangerous specificity.

### Tool-level restrictions

The AI should not have unrestricted access to databases, code execution, synthesis ordering, robotic platforms or production systems.

For sensitive systems, the default should be:

- read-only database access;
- allow-listed tools;
- structured outputs instead of free-form executable commands;
- query validation before execution;
- separation between recommendation and action;
- human approval for wet-lab or automation steps.

### Auditable logging

Logs should capture prompts, outputs, tool calls, database queries, risk scores, user identity and human approvals.

This is not only useful for incident response. It also aligns with the broader direction of AI governance. Under the EU AI Act, high-risk AI systems must technically allow the automatic recording of events throughout the system lifecycle to support traceability and monitoring [9]. Providers of high-risk AI systems must also retain automatically generated logs for at least six months while those logs are under their control, unless other applicable law requires a longer period [10].

### Human oversight

Human-in-the-loop oversight should apply specifically where AI outputs could trigger sensitive wet-lab steps, database access, material transfer, synthesis requests or process-control decisions.

The key question should be: where does advice become action?

The more directly an AI system can influence real-world biological work, the stronger the oversight should be.

### Continuous red teaming

Biosecurity testing should involve both AI security experts and domain experts in microbiology, bioinformatics, synthetic biology and industrial biotechnology.

A purely technical red team may miss biologically plausible misuse patterns. A purely biological review may miss prompt injection, jailbreaks and tool-abuse vectors. The relevant threat model lies at the intersection of the two.

## The European opportunity: governed infrastructure instead of uncontrolled acceleration

Europe has a particular opportunity here.

The debate around AI and biotechnology is often framed as a trade-off between innovation and restriction. But the smart biomanufacturing perspective suggests another option: shared, well-maintained, interoperable and governed digital infrastructure.

Müller et al. emphasise that smart biomanufacturing requires cross-sectoral collaboration, interdisciplinary training and well-maintained digital infrastructures [2]. That is not only an innovation agenda. It is also a safety agenda.

Poor infrastructure creates hidden risks: inconsistent metadata, weak traceability, brittle automation, unvalidated models and unclear responsibility when errors occur.

If Europe wants competitive AI-driven biotechnology, it should not only fund models and automation. It should fund the boring but essential layer:

- curated datasets;
- standardised metadata;
- secure APIs;
- validation benchmarks;
- audit trails;
- training programmes;
- governance interfaces;
- shared safety infrastructure for SMEs, universities and research infrastructures.

This is where bioinformatics becomes central. Bioinformatics is not only analysis after the experiment. It is becoming the control layer between biological knowledge, digital infrastructure and experimental action.

## Conclusion

AI in biotechnology is an enabling layer. Like all enabling layers, it changes who can do what, how quickly and with what level of oversight.

For bioinformatics and biomanufacturing, the key question is no longer whether AI can help. It can. The question is whether we build AI systems that are useful only because they are frictionless, or useful because they are reliable, auditable and secure.

Biotechnology is already digital, automated and AI-assisted. The safest version of biotech's future is neither the one with the most restrictions nor the one with the fewest. It is the one where access, data, models, tools and human responsibility are designed together from the beginning.

## References

[1] Anteghini, M., Gualdi, F., & Oliva, B. (2025). How did we get there? AI applications to biological networks and sequences. *Computers in Biology and Medicine, 190*, 110064. DOI: 10.1016/j.compbiomed.2025.110064. ScienceDirect: https://www.sciencedirect.com/science/article/pii/S0010482525004159

[2] Müller, A., Robaey, Z., Youssef, S., Martins dos Santos, V. A. P., & Asín-García, E. (2026). Digitalisation and automation in smart biomanufacturing: uncertainties, challenges and early pathways towards safe and sustainable design. *New Biotechnology, 93*, 378-391. DOI: 10.1016/j.nbt.2026.04.007. WUR record: https://research.wur.nl/en/publications/digitalisation-and-automation-in-smart-biomanufacturing-uncertain/

[3] OECD. (2025). *Synthetic biology, AI and automation: A forward-looking technology assessment*. OECD Science, Technology and Industry Policy Papers. https://www.oecd.org/en/publications/synthetic-biology-ai-and-automation_12158721-en.html

[4] Pannu, J., Bloomfield, D., MacKnight, R., Hanke, M. S., Zhu, A., Gomes, G., Cicero, A., & Inglesby, T. V. (2025). Dual-use capabilities of concern of biological AI models. *PLOS Computational Biology, 21*(5), e1012975. DOI: 10.1371/journal.pcbi.1012975. https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012975

[5] Rivera, S., & Mackelprang, R. (2025). *Risk Mitigation for Biological Design Tools*. Engineering Biology Research Consortium. DOI: 10.25498/E4R10S. https://ebrc.org/publications-risk-mitigation-for-biological-design-tools/

[6] Asín-García, E., Kallergi, A., Landeweerd, L., & Martins dos Santos, V. A. P. (2020). Genetic safeguards for Safety-by-Design: So close yet so far. *Trends in Biotechnology, 38*(12), 1308-1312. DOI: 10.1016/j.tibtech.2020.04.005. PubMed: https://pubmed.ncbi.nlm.nih.gov/32402415/

[7] van der Horst, M., Robaey, Z. H., Asín García, E., & Martins dos Santos, V. A. P. (2023). *An exploratory study on embedding Safe-and-Sustainable-by-Design (SSbD) in circular bioeconomy research*. Wageningen University & Research. https://research.wur.nl/en/publications/an-exploratory-study-on-embedding-safe-and-sustainable-by-design-

[8] Müller, A., Hekmatyar, F., Sairam, N. B., Batianis, C., Robaey, Z. H., Asín García, E., & Martins dos Santos, V. A. P. (2023). *Embedding Safe-by-Design in circular bioeconomy workflows*. Ministerie van Infrastructuur en Waterstaat. https://research.wur.nl/en/publications/embedding-safe-by-design-in-circular-bioeconomy-workflows/

[9] European Commission, AI Act Service Desk. (n.d.). *Article 12: Record-keeping*. https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-12

[10] European Commission, AI Act Service Desk. (n.d.). *Article 19: Automatically generated logs*. https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-19
