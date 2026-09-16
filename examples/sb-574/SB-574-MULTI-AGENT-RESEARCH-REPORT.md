# Practicing Law Through AI: California’s SB 574, Professional Authority, and the Future of the AI-Native Firm

> **Historical research artifact.** This report was prepared on September 3, 2026, based principally on the August 21, 2026 version of California SB 574 and the legislative record then available. It has not been updated for later legislative or legal developments and is provided as an example of a multi-agent research workflow, not as legal advice. Check the [current official bill history](https://leginfo.legislature.ca.gov/faces/billHistoryClient.xhtml?bill_id=202520260SB574) before relying on its status.

*Version 2 — a practical legal and policy analysis. Historical research artifact, September 3, 2026. Project lead: Daniel “Dazza” Greenwood.*

Prepared by Codex Desktop and Claude Code Desktop, with Daniel “Dazza” Greenwood as project lead. This report analyzes the August 21, 2026 text of Senate Bill 574 on the assumption that it becomes law. The official history checked on September 3 records passage and concurrence, followed by an order to engrossing and enrolling; it does not yet record signature or chaptering. [Official history](https://leginfo.legislature.ca.gov/faces/billHistoryClient.xhtml?bill_id=202520260SB574).

<a id="v2-core"></a>

A California lawyer has a large document production to manage. The lawyer determines what the requests mean, develops review criteria, selects a suitable system, tests it on the actual collection, investigates disagreements and approves the production process. Generative AI applies those criteria across the documents. Lawyers inspect samples and difficult cases, correct systematic errors and decide whether the results justify continued reliance. Many individual documents never receive a separate lawyer’s determination.

Is the lawyer practicing law through a controlled system, or unlawfully delegating legal practice to it?

That question is already practical. A recent federal discovery order in California describes generative AI making final responsiveness calls, subject to human sample quality control. It allowed the disclosed workflow to continue while resolving particular discovery disputes. It did not require every litigant to use AI. The importance of the example is that professional judgment can concern a **method applied to a defined population**, rather than a lawyer personally repeating every classification. Section 6 examines that order and its limits.

The same question will arise in contract portfolios, due diligence, regulatory analysis and many other kinds of legal work. It becomes more pressing as systems improve. An agent may research, analyze, compare, draft, test and revise for hours before a lawyer sees a completed work product. Another may continuously review a defined collection, bringing material exceptions to counsel. Neither arrangement is adequately described by saying that AI merely helps with typing.

**Our preferred interpretation is that California lawyers may practice law through competently directed, evaluated and controlled AI systems, including systems performing substantial legal analysis and bounded autonomous workflows.** The lawyer must retain the professional role, have a reasonable basis for reliance, respect decisions belonging to the client and perform any act the law requires the lawyer personally to perform. The system’s usefulness need not depend on pretending that it does no legal reasoning.

SB 574 does not expressly set out that complete framework. It prohibits delegation of legal practice to generative AI while regulating AI assistance with that practice. The boundary is undefined. A restrictive interpretation could require individual review of consequential legal outputs, or prohibit assigning particular substantive tasks even with oversight. Those possibilities deserve an answer grounded in the text and authorities. They should not be concealed by a reassuring assurance that a human remains responsible.

There is also a reason to welcome a well-drawn boundary. A firm in which software independently takes clients, decides their legal rights, commits them to positions and acts under a lawyer’s name presents a real professional problem. Meaningful authority boundaries protect clients and make ambitious automation more defensible. Their purpose should be to make the combined service reliable and accountable, rather than to preserve every manual step that happened to exist before AI.

Version 2 develops that affirmative position much further than the first report. It brings the eDiscovery example into the center of the analysis; treats prior specification, informed adoption and validated operation as methods that can work together; adds older California ethics opinions, the current State Bar proposal, the book’s governance framework, the broader legislative history and concrete policy options. It also corrects overstatements in the supplied research. Preserving a useful idea does not require preserving its original certainty or an inaccurate citation.

## The direct answers

**What is the practice of law?** It includes applying legal knowledge to particular circumstances, advising about rights, selecting and preparing legal instruments, negotiating legal positions and representing others in proceedings. General information and genuinely mechanical work can be different. The service, actor and context matter. A machine’s ability to perform an activity does not automatically make that activity nonlegal.

**What would prohibited delegation mean?** The strongest interpretation targets surrender of the attorney’s professional function: the system effectively provides the representation while the lawyer supplies a name, license or ceremonial approval. Substantial preparation and properly controlled performance can remain assistance. That is a reasoned interpretation, not an express statutory safe harbor. The contrary reading deserves particular attention where a system supplies new individualized advice or exercises authority before a lawyer has meaningfully considered it.

**How much autonomy could a firm use?** A great deal within a defensible professional arrangement. Agents can conduct complete internal research and drafting cycles, perform validated analysis of a defined population, monitor developments, compare alternatives and execute decisions already authorized. Controls should correspond to the actual task and consequences. A lawyer need not inspect every internal token or repeat every computation. A personal citation-verification duty, a client’s settlement decision and a consequential new legal recommendation cannot simply disappear into a population accuracy score.

**Does the eDiscovery concern justify action now?** Yes. An overrestrictive reading could exclude a method already used in litigation, increase cost or delay and undermine reasonable discovery plans. The evidence supports that conditional concern. It does not establish that courts generally require GenAI, that every leading vendor is indispensable or that California litigation would inevitably become impossible.

**What should California clarify?** It should explain how lawyers can exercise professional judgment through validated systems while retaining authority and fulfilling personal duties. The pending State Bar comment project, practical guidance, a formal ethics opinion and targeted legislative language offer different routes. A signing statement could encourage a sound interpretation, but could not rewrite the law or bind the courts.

The report is intended to be read without having seen the research conversations. Sections 1–5 explain the law and interpretive choices. Sections 6–8 develop discovery, governance and practice designs. Sections 9–12 address verification, the business and client relationship, neutrals and comparisons. Sections 13–16 offer policy language, control patterns, a CLE program and an implementation agenda. The final sections preserve qualified research leads and the annotated authorities.

<a id="v2-bill"></a>

## 1. Begin with what the bill actually says

SB 574, authored by Senator Umberg, would place its central prohibition in Business and Professions Code section 6068.1(a)(2):

> “An attorney shall not delegate the practice of law to generative artificial intelligence.”

The very next paragraph regulates an attorney who uses generative AI **“to assist in the practice of law.”** Those words matter together. The Legislature has not simply proposed an AI ban. It has proposed a distinction between an impermissible assignment of legal practice and a permitted form of assistance, subject to additional duties. [SB 574, proposed Business and Professions Code § 6068.1(a)(2)–(3), August 21, 2026 text](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=202520260SB574).

The assistance provision addresses confidentiality, accuracy, correction of errors, and disclosure of AI use in court documents. Separate provisions concern personal verification of citations and arbitrators’ decisionmaking. We return to those requirements in practical terms below. For now, the critical point is that satisfying an accuracy requirement does not automatically answer the delegation question. A system might produce a correct answer while performing a task the law reserves to someone else.

Conversely, calling something legal work does not automatically mean that a lawyer must perform every preparatory step unaided. Lawyers have long used clerks, associates, paralegals, investigators and technical tools. The question is how existing arrangements illuminate the particular distinction the bill draws for generative AI.

Here, **generative AI** means the kind of system that produces new text or other synthetic content from learned patterns. An **agentic system** gives such a model tools and the ability to plan and carry out multiple steps, rather than only answer one prompt. A workflow can combine that system with ordinary software that copies an approved message or performs a specified calculation. The legal analysis should identify which component makes which choice; adding a generative model to a process does not make every mechanical operation a new legal judgment. The bill contains its own definition of generative AI, so technical labels and predictable output are not substitutes for checking the defined scope.

The version matters. The official history reviewed for this article records concurrence in Assembly amendments and an order to engrossing and enrolling on August 31, 2026. It does not record chaptering. Earlier committee analyses can help explain the proposal’s background, but they cannot replace the August language. This article therefore asks what would follow **if the researched version became law**, rather than predicting that every provision will necessarily be enacted unchanged. [Official legislative history](https://leginfo.legislature.ca.gov/faces/billHistoryClient.xhtml?bill_id=202520260SB574).

### The full bill contains several distinct obligations

The attorney delegation sentence should not obscure the rest of the proposal. The following map describes the researched text conditionally, not an enacted statute. [August 21 bill text](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=202520260SB574).

| Provision | What it would do | Why the distinction matters |
|---|---|---|
| BPC § 6068.1 | Preserve competence and diligence; prohibit delegation of legal practice to GenAI; regulate confidential and protected inputs, verification and correction of outputs, and disclosure. | Accuracy, authority, confidentiality and disclosure are separate duties. Compliance with one does not establish compliance with all. |
| CCP § 128.7 | Add personal citation verification by the responsible attorney within an existing certification and sanctions framework. | The text reaches citations whether or not AI supplied them. Existing exclusions, remedies and renumbered cross-references matter. |
| CCP § 180 | Require the Judicial Council to reconsider its judicial-AI standard and revise it as necessary. | This is a judicial track, not an instruction that the State Bar stop work on attorney guidance. The text does not establish the recurring interval some commentary describes. |
| CCP § 1282.1 | Separately restrict arbitrator delegation of decisionmaking and address AI information outside the record. | A neutral’s role differs from counsel’s. Disclosure or party agreement does not automatically cure prohibited decisionmaking. |
| BPC § 6173 | Revise a voluntary ADR-provider certification and complaint framework, including information-production and confidentiality rules. | The mediation-confidentiality dispute is distinct from the AI issue and has its own conditions. This is not a universal license for every AI product. |
| Section 6 findings | Address public-access limits associated with the complaint process. | These findings do not create another general attorney-AI rule. |

The court-disclosure provision is mandatory for covered AI use in documents submitted to the court. The separate public-content provision calls for consideration of disclosure. A firm should not silently substitute a materiality threshold or an entirely-AI threshold that the attorney text does not supply. Conversely, materials exchanged in discovery are not automatically filed court documents. Clarification of the required form, scope and recording of covered use would be useful.

The definition turns on the system’s generative capability. A generative model does not necessarily fall outside the bill because a particular prompt requests only a label or score. Traditional predictive coding is not automatically generative AI, and a hybrid platform can combine both. The August Appropriations analysis recognizes that generative capabilities can be embedded in ordinary enterprise tools. The compliance question concerns the actual function used and the covered system, not simply the vendor’s name or the appearance of the output. Assembly Appropriations analysis, August 4, p. 3.

### What changed, and when

Several supplied reports used the wrong version to explain an amendment. The corrected sequence is useful because the attorney prohibition arrived later than the January committee discussion that connects the bill to *Noland*.

| Print or stage | Relevant fact | Interpretive limit |
|---|---|---|
| February 20, 2025 introduction | Original subject was public postsecondary education and UC contracting. | It was not yet the operative legal-AI proposal. Later housing references should not be mistaken for the introduced text. |
| January 2026 analyses | The legal-AI proposal was discussed in relation to *Noland* and Judicial Administration Standard 10.80. | This explains background, not necessarily every later amendment. |
| June 22, 2026 print | It did not yet contain the later attorney nondelegation sentence. | An analysis of this print cannot by itself define the later prohibition. |
| July 2 print | Contains the attorney prohibition, mandatory court disclosure and the access-restriction formulation for protected inputs. The citation clause still included reading as well as verification. | These duties must be understood together, but their coexistence does not logically eliminate all restrictive readings. |
| August 13 print | Deletes the reading words from the citation clause and changes other provisions, including earlier bias-related and arbitrator language. | Deletion can change substance or remove redundancy. It does not establish that an automated checkbox now suffices or that other nondiscrimination duties vanish. |
| August 21 print | The version analyzed in this report. | Earlier summaries cannot replace its operative text. |

The archived July 2 print and August 13 print show the changes. The public [bill text and version selector](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=202520260SB574) and [analysis index](https://leginfo.legislature.ca.gov/faces/billAnalysisClient.xhtml?bill_id=202520260SB574) permit examination of the source record.

All nine analyses identified in the supplied research were retrieved in the preceding review. They are not uniformly silent or uniformly accurate. The August 4 Appropriations and August 31 concurrence analyses recognize the mandatory disclosure and prohibition. Some other summaries describe older or garbled language. The useful criticism is that the reviewed materials do not resolve the operational distinction between assistance and delegation for validated autonomous work. It is not that no official ever mentioned the provision or that legislative indifference has been proved. August 4 analysis; August 31 concurrence analysis.

Reported hearing comments about drafts, oversight and final human judgment may add context. Before relying on a particular quotation in a formal submission, it should be tied to the recording, speaker, date and bill version. Short indexed clips, limited search results and procedural rule suspensions do not prove that nobody considered the issue.

### Passage, presentment and effectiveness are different events

The bill passed without recorded opposing votes in the relevant floor actions. The detailed vote page records 75–0 in the Assembly and 40–0 on concurrence; the history page reports concurrence as 39–0. That official discrepancy does not affect the observation that there were no recorded opposing votes, but it counsels against describing every member as affirmatively voting yes. [Official votes](https://leginfo.legislature.ca.gov/faces/billVotesClient.xhtml?bill_id=202520260SB574).

California Constitution article IV, section 10(b)(2) supplies a September 30 deadline for the specified second-year bills passed before September 1 and in the Governor’s possession on or after that date. In that posture, failure to return the bill makes it a statute; it is not a pocket veto. An ordinary enactment in this window would generally become effective January 1, 2027 under section 8(c). Presentment and any later gubernatorial action should be checked before sending or publishing a time-sensitive document. [California Constitution, article IV, §§ 8 and 10](https://leginfo.legislature.ca.gov/faces/codes_displayText.xhtml?lawCode=CONS&division=&title=&part=&chapter=&article=IV).

<a id="v2-practice"></a>

## 2. “Practicing law” includes much more than appearing in court

The familiar image of legal practice is an attorney standing before a judge. California’s definition is much broader. It includes activities performed privately, before a dispute exists, and outside any courtroom: advising someone about legal rights, selecting an appropriate legal instrument, and preparing documents that create or alter legal obligations.

In **People v. Merchants’ Protective Corp.**, the California Supreme Court addressed a corporation’s provision of legal services. The opinion explains that:

> “the drafting of legal documents of all kinds, including wills, are activities which have been long classed as law practice”

The practical lesson is straightforward. Preparing a will or a contract is not made nonlegal merely because no lawsuit has been filed. A firm designing an AI product must examine the service the product performs, not just the setting in which it performs it. The historical corporate-practice context also matters: the case does not replace modern statutes governing authorized law corporations and other lawful arrangements. [People v. Merchants’ Protective Corp., 189 Cal. 531 (1922)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/U6/U6MhpmHYu6EaCb7GrsNphLGm.pdf).

### Applying law to someone’s situation is different from displaying information

**Baron v. City of Los Angeles** provides a particularly useful formulation:

> “if the application of legal knowledge and technique is required, the activity constitutes the practice of law”

Baron arose from a municipal lobbyist-registration ordinance, not from software. Its discussion distinguishes the particular legal activity from the full range of things lawyers may do professionally. That context keeps the quotation from becoming a slogan that answers every borderline case. Nevertheless, it directs attention to a central feature: the application of legal learning to the task at hand. [Baron v. City of Los Angeles, 2 Cal.3d 535, 543 (1970)](https://law.justia.com/cases/california/supreme-court/3d/2/535.html).

Consider a person asking about a filing deadline. A website that displays the text of a statute provides information. A system that asks about dates, selects the governing limitation period, evaluates tolling exceptions and tells that person when to sue is doing something materially different. It has connected legal rules to a particular person’s circumstances and produced an answer about their rights.

The same distinction appears in contract work. A system can store a collection of clauses, display them, or compare two documents word for word. A system that selects which indemnity provision a particular client should accept, explains the legal consequences, and negotiates a replacement is making substantive legal choices. The relevant distinction is not whether both services happen to produce text. It is what the text does and what judgment went into producing it.

Nor is the distinction simply between hard and easy questions. A familiar issue can still involve legal advice. A firm should not assume that an activity leaves the practice of law once a model becomes very good at it, or once enough examples make the answer predictable. A successful automation system can change the economics of a task without changing its legal character.

### Form filling becomes a different service when the system chooses the legal solution

In **People v. Landlords Professional Services**, the court examined an eviction-related service and drew a line between clerical assistance and personalized legal services. Its caution is worth keeping in view:

> “whether any given activity is an unauthorized practice of law depends upon the context and situation involved”

Typing information supplied by a customer is one thing. Choosing the legal document a landlord needs and advising how to proceed is another. The case is useful because many modern AI services bundle those activities into a single smooth interaction. A friendly intake conversation can conceal the point at which the system stops gathering facts and begins deciding the legal response. [People v. Landlords Professional Services, 215 Cal.App.3d 1599 (1989)](https://law.justia.com/cases/california/court-of-appeal/3d/215/1599.html).

Suppose an agent asks a landlord for the tenant’s name and inserts it into a notice already selected and approved by counsel. On those narrow facts, the task may be clerical. Suppose instead it asks why the landlord wants possession, chooses between notice types, decides how to describe the alleged breach, and advises when to serve the notice. That service contains legal assessment and selection. Calling both workflows “document automation” obscures the legally important difference.

The Florida Supreme Court reached a related distinction in **Florida Bar v. Brumbaugh**. Its permission for a typing service was limited to copying information supplied in writing by its customers:

> “provided that she only copy the information given to her in writing by her clients.”

That is a comparative example from another state, not a California exemption. It helps explain why a blank-form library and an individualized legal recommendation should not be treated as interchangeable products. [Florida Bar v. Brumbaugh, 355 So.2d 1186 (Fla. 1978)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/Kj/KjkG9PFK8IuuaqlKlpqGldQ.pdf).

### An automated service can apply legal judgment even without a human operator making each selection

**In re Reynoso** concerned an online bankruptcy-preparation service. Its operation involved individualized advice and the selection of exemptions. The Ninth Circuit rejected the idea that the automated nature of the service necessarily made its legal choices merely clerical. Yet the court expressly limited its decision:

> “we express no view as to whether software alone, or other types of programs, would constitute the practice of law”

That reservation is essential. Reynoso is a strong warning against using automation as a universal exemption from legal-practice rules. It is not a holding that every legal software product practices law. It also involved federal bankruptcy petition-preparer law, whose current text differs from the version considered in the opinion. [In re Reynoso, 477 F.3d 1117 (9th Cir. 2007)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/hS/hSLwrxlnjgBzPka2DHZJrwe.pdf); [11 U.S.C. § 110](https://www.law.cornell.edu/uscode/text/11/110).

For an AI-native firm, the constructive implication is to describe every important function in ordinary legal terms. “The agent selects the exemption” is more informative than “the workflow generates a form.” “The agent recommends whether to accept a release” is more informative than “the system assists with settlement.” Precise descriptions make it possible to decide where lawyer judgment must enter the process.

### Legal work, unauthorized practice, and permission are separate questions

An activity can be legal work without being unlawful for every person who assists with it. A licensed associate may research and draft for a partner. A qualified paralegal may perform substantial legal work within statutory restrictions. Particular administrative proceedings may authorize forms of representation that differ from ordinary courtroom practice.

California’s general licensing requirement appears in Business and Professions Code section 6125. Section 6126 addresses unauthorized practice and holding out. Those provisions must be read with the specific permission applicable to the person, activity and forum. The right question is not simply whether the task involves law. It is also **who may do that task, for whom, and under what conditions**. [Business and Professions Code §§ 6125](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=BPC&sectionNum=6125.) and [6126](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=BPC&sectionNum=6126.).

That distinction prevents two opposite errors. One is to conclude that all assistance with substantial legal work is forbidden. The other is to conclude that a useful assistant can perform any legal service simply because a lawyer remains somewhere in the organization. Existing California law supports neither shortcut.

<a id="v2-assistance"></a>

## 3. Delegation does not have one meaning in every legal setting

Ordinary speech makes delegation sound simple: one person gives a task to another. Legal usage is more complicated because different rules address different things that can be transferred. A lawyer might assign preparation of a research memorandum, authorize someone to make a professional decision, or remain liable for a failure even though someone else performed the work. Those are related, but they are not the same proposition.

For this article, it helps to ask three questions about a proposed workflow:

1. **What work is being assigned?** For example, collecting documents, analyzing cases, selecting a claim, or transmitting an approved letter.
2. **Who actually decides the legal position?** Who chooses the advice, strategy, terms, argument or representation that will be relied upon?
3. **Who remains responsible, and what law permits the arrangement?** Retained liability does not by itself establish permission to assign the task.

These are explanatory questions, not a new statutory test. They help us read the authorities without treating every use of the word delegation as if it answered the AI question.

### California expressly allows some delegated substantial legal work

The clearest example is the paralegal statute. Business and Professions Code section 6450(a) describes **“substantial legal work”** that is **“specifically delegated by the attorney.”** Its examples include research, fact gathering, analysis and drafting. The statute also recognizes recommendations made to the supervising attorney. Those are meaningful intellectual contributions, not simply typing dictated sentences.

The permission comes with restrictions. Among the acts subsection (b) says a paralegal shall not perform are:

> “(1) Provide legal advice. (2) Represent a client in court.”

The next paragraph restricts selecting, explaining, drafting or recommending legal documents for anyone other than the directing and supervising attorney. Read together, these provisions distinguish substantial preparation for counsel from independently providing the client's legal service. Qualifications and statutory exceptions must also be considered. [Business and Professions Code § 6450(a)–(c)](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=BPC&sectionNum=6450.); [§ 6456](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=BPC&sectionNum=6456.).

This is a crucial correction to a common argument about AI. It is too simple to say that research and drafting cannot be delegation because the lawyer later reviews them. California itself calls some supervised research and drafting delegated work. What makes the human paralegal arrangement lawful is the applicable permission and its conditions, not a conclusion that no legal work was assigned.

At the same time, section 6450 shows that substantial legal preparation need not always be performed personally by the lawyer. It is evidence against the notion that legal professionalism requires unaided production of every sentence and every intermediate analysis.

Both points must survive into the AI discussion. The statute demonstrates room for substantial assistance. It does not automatically extend a defined human role to a generative system, particularly when SB 574 would create a prohibition specifically directed at that system.

### A personal license cannot simply become a wrapper around someone else’s independent practice

In **Townsend v. State Bar**, the California Supreme Court described legal licensure as a personal privilege and public trust. The opinion states that the associated:

> “powers and privileges derived from it may not with propriety be delegated to or exercised by a nonlicensed person”

The concern was not the existence of office assistance. It was the lending of a lawyer’s name to an arrangement in which others effectively exercised the professional role. **McGregor v. State Bar** later repeated the personal-license principle in a disciplinary setting. [Townsend v. State Bar, 210 Cal. 362, 364 (1930)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/ai/ai0IFpzsu1YlRr63t28vdy.pdf); [McGregor v. State Bar, 24 Cal.2d 283, 288 (1944)](https://scocal.stanford.edu/opinion/mcgregor-v-state-bar-29251).

An AI analogy should be stated carefully. Neither case considered a model or an autonomous software agent. Their value is that they identify an old professional concern that survives the technological change: a lawyer’s name, license and theoretical power to intervene are not necessarily the same as the lawyer actually providing the legal service.

If an AI system determines clients’ rights, chooses their responses and gives them advice, a promise that an attorney accepts responsibility may not establish that the lawyer has retained the professional role. The arrangement needs a more substantive explanation of what the lawyer actually does.

### Crawford shows why preparation can be extensive without replacing the lawyer

**Crawford v. State Bar** offers a more useful starting point for constructive system design than a general warning against delegation. In discussing the work of law clerks, the California Supreme Court quoted a description of preparatory research, investigation and information assembly that helps an attorney bring a matter to a completed product:

> “either by his personal examination and approval thereof or by additional effort on his part.”

The surrounding discussion says the preparatory work must merge into the attorney’s own product. The actual misconduct in Crawford involved a disbarred father acting independently in client matters while the licensed lawyer lacked meaningful knowledge of their progress and disposition. The permission for preparation and the condemnation of independent practice belong together. [Crawford v. State Bar, 54 Cal.2d 659 (1960)](https://scocal.stanford.edu/opinion/crawford-v-state-bar-29823/); archived opinion and verified source record.

For AI practice, the promising analogy is not that every draft automatically becomes the lawyer’s work when signed. It is that another source can do substantial preparatory work while the lawyer meaningfully examines it, makes the consequential judgments and adopts the result as the lawyer’s professional service.

A lawyer therefore need not pretend that an agent contributed nothing. Suppose an agent finds an argument the lawyer had not considered. The lawyer reads the authorities, tests the argument against the facts, considers its weaknesses and decides to use it. Independent judgment does not require independent invention. It requires the lawyer’s own informed decision about whether the argument is sound and appropriate.

That distinction preserves much of the potential value of AI. A useful system should be able to surprise the lawyer with a better approach. The legal issue is what happens between the suggestion and its consequential use. Does the lawyer evaluate and decide, or does the system’s answer become the legal service because it sounds plausible?

### Remaining liable does not prove that an assignment is permitted

**Maloney v. Rath** helps explain a different use of nondelegation. It concerns responsibility for defective brakes, not the practice of law. A nondelegable duty in that setting can keep responsibility with a vehicle owner even though the owner hires someone else to repair the brakes. The rule does not require the owner personally to become a mechanic. [Maloney v. Rath, 69 Cal.2d 442 (1968)](https://law.justia.com/cases/california/supreme-court/2d/69/442.html).

Likewise, California Commercial Code section 2210 addresses delegation of contractual performance without release from responsibility, within its sales-law setting. It does not authorize the delegation of legal services to AI. The comparison helps expose the logical gap: a rule saying that the original obligor stays responsible cannot, without more, answer whether a separate professional rule permits the arrangement. [Commercial Code § 2210](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=COM&sectionNum=2210.).

In practical terms, “the lawyer remains liable” is an incomplete description of an AI-native firm. It says something about allocation of risk. It does not tell us who made the legal decision, whether the recipient was authorized to make it, or whether the statutory prohibition was satisfied.

### Supervision is a real activity, not a job title

The disciplinary cases make the same point at the office level. In **Gadda v. State Bar**, the California Supreme Court stated:

> “An attorney is responsible for the work product of his employees which is performed pursuant to his direction and authority”

The case involved human lawyers, not AI. It should not be collapsed into a rule of automatic discipline for every staff mistake. Current professional rules use reasonable-efforts duties and specified grounds for attributing another person's misconduct to a lawyer. [Gadda v. State Bar, 50 Cal.3d 344, 353–354 (1990)](https://law.justia.com/cases/california/supreme-court/3d/50/344.html); [California Rules of Professional Conduct 5.1 and 5.3](https://www.calbar.ca.gov/legal-professionals/rules/rules-professional-conduct/current-rules-professional-conduct/chapter-5-law-firms-and-associations).

**Moore v. State Bar** makes supervision concrete. After learning that an answer had not been filed, the lawyer repeatedly relied on office assistants to put the matter right. The court emphasized that he:

> “admittedly made no personal check on the matter to see that they had done so.”

The failure was more specific than the fact that another person handled a task. The lawyer knew of a problem and failed to check whether the promised correction occurred. For an agentic firm, the corresponding question is what happens after a missed deadline, inaccurate output or failed transmission becomes known. An instruction to try again is not evidence that the problem was fixed. [Moore v. State Bar, 62 Cal.2d 74 (1964)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/lO/lO6JNEZy1VjklsuQPLrm4HZB.pdf).

The operational lesson is that the lawyer’s involvement has to be suited to the work being assigned. A rule that employees must ask questions is weak protection if no one checks whether they do. An AI policy has the same weakness if it exists only in a handbook while the production system can act outside it. The relevant evidence would concern how the process actually operates: what is reviewed, what is blocked, what is corrected, and how the firm responds when the system encounters a problem it cannot reliably handle.

### California’s older ethics opinions give concrete examples of useful delegation

Formal Opinion 1982-68 addresses computer-generated collection letters prepared with the help of a creditor-client’s employees. It recognizes the efficiency of that assistance and says the required supervision:

> “depends on the nature of the delegated task.”

It also imposes an important limit: a legal-threat letter must have been:

> “expressly authorized … in that particular case”

The opinion therefore supports both substantial assistance and meaningful attorney involvement. A standing form is not automatically authorization to threaten legal proceedings against every later debtor. It is an older advisory opinion applying then-current rules, not a decision construing SB 574. [Formal Opinion 1982-68, discussion of supervision and unauthorized practice](https://www.calbar.ca.gov/sites/default/files/portals/0/documents/ethics/Opinions/1982-68.htm).

Formal Opinion 1988-97 permits a nonlawyer to perform the ministerial act of signing trust-account checks while withholding discretion over the funds and retaining the lawyer’s responsibilities. It illustrates execution of an authorized act, not permission for an autonomous agent to decide how client money should be used. Current trust-account rules must still be applied. [Formal Opinion 1988-97](https://www.calbar.ca.gov/sites/default/files/portals/0/documents/ethics/Opinions/1988-97.htm).

San Diego County Bar Opinion 2007-1 and ABA Formal Opinion 08-451 supply outsourcing comparisons. They discuss substantial assistance with competence, supervision, confidentiality and disclosure obligations. Human-provider arrangements do not decide an AI-specific prohibition; their value is showing that substantial preparation, actual control and professional responsibility can coexist. [San Diego Opinion 2007-1, particularly pp. 5–6 and 10–12](https://www.iusjuris.com/docs/2007_04_SanDiego_OutsourcingOpinion.pdf); [ABA Opinion 08-451](https://www.americanbar.org/content/dam/aba/publications/YourABA/201106_08451.authcheckdam.pdf).

These authorities also prevent a misleading characterization of modern legal work. The lawyer’s personal role is not established by personally producing every word, nor eliminated whenever someone else makes an intellectual contribution. The legally sufficient relationship between the contributor, the lawyer and the client is what needs explanation.

<a id="v2-interpretation"></a>

## 4. What would count as delegating legal practice to generative AI?

There is no researched decision construing this proposed prohibition that settles the question. We therefore need to distinguish the words of the bill from an interpretation of those words. Our preferred interpretation is supported by the relationship between the prohibition and the assistance provision, by the treatment of preparatory work in California cases, and by current guidance on professional judgment. It is still an interpretation.

### The preferred reading: professional judgment can govern a suitable process

On this reading, the bill permits generative AI to help produce legal work, including substantive research, competing analyses, drafts and classifications within a defined population, when the attorney genuinely directs and evaluates the work and provides the resulting legal service. Depending on the task and applicable duties, that evaluation may concern a validated method and its results rather than each individual item. It forbids turning over the professional role so that the system effectively practices for the client in the lawyer’s place.

Why is that a plausible reading? First, the assistance provision needs meaningful content. If every contribution involving legal subject matter were prohibited, it would be difficult to explain why the bill separately regulates AI assistance, including verification of legal citations. A provision about correcting legal output suggests that there will be legal output to correct. Mandatory disclosure for covered AI use in court documents reinforces the point. This supports meaningful lawful assistance; it does not logically prove that every substantive assignment is permitted. A narrower reading can still leave room for a narrower category of assistance.

Second, Crawford supplies a useful distinction between preparation that becomes part of the attorney’s professional work and an independent practice conducted behind the attorney’s name. The case does not decide the AI question, but it provides a legal model for understanding how substantial assistance can coexist with genuine attorney responsibility.

Third, the recent AI cases focus heavily on what the lawyer failed to check and decide. They do not generally reason that any involvement by AI makes the work impermissible. Their concern is the loss of professional judgment and the submission of unsupported or false material.

**Noland v. Land of the Free, L.P.**, a 2025 California Court of Appeal decision, is especially relevant. Counsel acknowledged extensive fabricated legal authority in appellate briefs. The court explained the lawyer’s duty to check the material before filing and, quoting another court, stated:

> “Attorneys cannot delegate that role to AI, computers, robots, or any other form of technology.”

The role in that passage is the attorney’s verification and professional responsibility for the submission. The same discussion recognizes **“nothing inherently wrong with an attorney appropriately using AI”** in legal practice. It compares checking AI material with checking work prepared by a clerk, intern or another attorney. Reading only the nondelegation sentence, without its subject and surrounding explanation, would obscure the permission for appropriate assistance. [Noland v. Land of the Free, L.P., 114 Cal.App.5th 426 (2025), discussion of counsel’s fabricated authorities](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/ip/ipQx4JJgO06quV81pqAmq59T.pdf).

The State Bar’s revised 2026 guidance addresses agentic systems directly. Its professional-judgment principle is unusually clear:

> “A lawyer’s professional judgment cannot be delegated to AI and remains the lawyer’s responsibility at all times.”

The guidance discusses greater autonomy, access to firm systems, oversight and verification. It is advisory guidance applying professional obligations, not an enacted definition of SB 574’s boundary. Its significance is that it contemplates legal practices using capable agents while requiring lawyers to retain judgment. [State Bar of California, *Practical Guidance for the Use of Generative Artificial Intelligence in the Practice of Law* (May 2026), p. 4; see also pp. 2–6](https://www.calbar.ca.gov/sites/default/files/portals/0/documents/ethics/Generative-AI-Practical-Guidance.pdf).

Finally, the January 2026 Senate Judiciary analysis connects the bill to Noland and the Judicial Council’s AI standard. That supports reading the bill against the background of competent assistance rather than as a prohibition on all substantive AI preparation. But the analysis concerns an earlier version. It is evidence about legislative background, not a substitute for the final statutory language. [Senate Judiciary Committee analysis of SB 574, January 13, 2026](https://sjud.senate.ca.gov/system/files/2026-01/sb-574-umberg-sjud-analysis.pdf).

Taken together, these sources support a substantial space for AI-enabled legal practice. A lawyer could receive a rich body of machine-generated analysis, use it to identify a better argument, and adopt a final position after informed professional consideration. The argument for permission becomes weaker when the lawyer’s participation consists only of approving a brand or accepting results without an adequate basis for reliance. A tested, appropriately supervised population-level method is materially different from such general approval.

### The intermediate reading: substantive preparation is allowed, but each consequential output needs adoption

A second plausible construction allows substantive AI work while requiring a lawyer to evaluate and adopt each consequential legal output before use. This can accommodate a complete research memorandum or draft agreement. It becomes restrictive if every responsiveness classification is treated as a separate legal output requiring individual lawyer review.

This reading matters because the debate is not simply between a total AI ban and unlimited assistance. A practice can accept extensive internal preparation while disagreeing about the level at which professional judgment must occur. *Schulte* and ABA Opinion 512 make that distinction concrete: responsible reliance can sometimes concern a defined process or population. A court-filing citation or a decision reserved to a client presents a different obligation.

The preferred interpretation leaves room for that context-sensitive judgment. The intermediate reading may offer more certainty for individually reviewed advice and drafting while preserving less of the value of validated bulk operation. That is a material operational difference, not a disagreement that should be manufactured for every use case.

### The strict task reading: some substantive assignments might remain prohibited despite later review

There is a reason not to announce a universal rule that lawyer review makes every AI assignment lawful. The attorney prohibition addresses the practice of law, not merely the final decision or final signature. California’s paralegal statute expressly describes supervised substantial legal work as delegated. And that statute provides a defined human role; it does not say that any tool performing similar work receives the same permission.

A court could therefore conclude that certain assignments of substantive legal work to generative AI fall within the prohibition even when the lawyer later reviews the result. That reading would still need to leave room for the express assistance provision. It could not sensibly treat every spelling correction or every retrieval of a statute as prohibited legal practice. The unsettled question would be where it draws the line between assistance and an assignment of the protected activity itself.

Consider a lawyer who tells an agent: investigate all possible claims, choose which claims are strongest, decide the litigation strategy, prepare the complaint and explain the decision afterward. The lawyer then carefully reviews the complete package. Under the preferred reading, a genuinely independent evaluation could make the preparatory process permissible assistance. Under the broader reading, assigning the whole legal undertaking may itself be relevant to prohibited delegation. The lawyer’s later evaluation would be important but might not answer the entire statutory question.

This is why the design should preserve more than an approval click. It should make the lawyer’s professional role visible in the actual work: identifying objectives, examining consequential uncertainties, choosing the legal response and deciding what may be used. That design strengthens the preferred interpretation. It does not transform the interpretation into an express statutory exception.

The distinction also explains why reliable AI is not the whole solution. A perfectly accurate system could still be exercising a role the law reserves. Conversely, an assistant can make an error in a discarded draft without the firm necessarily having delivered defective legal service. The allocation of judgment and the treatment of errors are related but separate issues.

### What follows from the uncertainty

The affirmative argument is substantial: assistance has legal meaning; California permits extensive preparatory work; current guidance contemplates agents; and a lawyer can make professional judgments about a suitable process. The strict reading nevertheless draws support from the breadth of legal practice and the absence of an express AI exception comparable to section 6450. The attorney-versus-unlicensed-provider distinction helps frame the issue but cannot make an express attorney-specific prohibition disappear.

A firm should identify the interpretation on which its actual workflow rests and the facts supporting retained authority. Policymakers should explain at least one substantive, validated workflow that remains available. A declaration that the lawyer stays responsible, without explaining what responsibility entails, would leave the central question unanswered.

<a id="v2-methods"></a>

## 5. Three ways a lawyer can exercise judgment through a system

The original inquiry proposed three approaches to extensive autonomous work: specify the legal approach before the system runs; meaningfully adopt its work afterward; and govern operation through carefully tested evaluations and quality controls. Each is useful. They should usually be combined. There is no sound basis for declaring one universally strongest without examining the task.

### Prior specification can embody real judgment

A lawyer can determine the client’s objectives, select governing legal criteria, decide a negotiating position and define permitted actions before an agent begins. A discovery protocol can express counsel’s understanding of a request. A contract playbook can embody positions the lawyer and client have already chosen. These are meaningful professional contributions.

But an instruction is not necessarily the same as a decision about every future fact pattern. A prompt directing a model to identify communications primarily seeking legal advice leaves difficult applications ahead: mixed business and legal purposes, third-party participation, waiver and missing context. Applying the prompt can itself involve legal judgment. The earlier memo’s suggestion that the system merely applies rather than decides is too categorical for that situation.

The stronger explanation is that the lawyer has established part of the professional method and must determine whether its implementation is reliable enough for the intended use. A detailed instruction that performs badly is not necessarily more defensible than a concise instruction supported by excellent validation and responsive supervision. The amount of text in a playbook is not the measure of retained professional authority.

### Meaningful adoption after preparation can be timely

A lawyer need not invent an argument before receiving help with it. *Crawford*, discussed in Section 3, recognizes substantial preparation that becomes the attorney’s completed work through real examination and approval or further effort. Independent judgment is not the same as unaided invention.

Suppose an agent develops an unexpected contract structure. Counsel examines the governing law, commercial implications, client objectives and alternatives, then adopts the structure without changing its wording. The absence of edits does not demonstrate the absence of judgment. Conversely, changing many words does not prove that counsel understood the legal position.

The timing distinction is essential. Adoption **after preparation but before consequential use** can be genuine professional action. Approval after the agent has advised a client, disclosed a secret, agreed to terms or filed a paper may arrive after the relevant harm or prohibited act. Review cannot retroactively prevent an event that already occurred.

This matters even when a workflow has a final signature gate. A system can select evidence, screen a client out, miss a deadline or send a misleading intermediate communication before the final document appears. The firm must examine where consequences actually occur. One final approval is not a universal answer to authority transferred earlier.

### Validating a method can itself be professional judgment

For some work, the lawyer’s informed decision concerns a process applied to a collection, rather than a separate legal conclusion for every item. A lawyer may understand the criteria, test the system, assess its errors, obtain technical help, determine whether the method is suitable and authorize continued operation under defined conditions.

ABA Formal Opinion 512 supplies an example outside discovery. Its discussion of summarizing a large collection of lengthy contracts allows the extent of manual checking to depend on the tool and task; appropriate testing on a smaller group can justify proceeding without manually examining the entire collection. This is an ABA Model Rules opinion, not binding California law. It nevertheless directly challenges the assumption that responsible AI use always means a human repeats each operation. [ABA Formal Opinion 512, pp. 3–4](https://www.americanbar.org/content/dam/aba/administrative/professional_responsibility/ethics-opinions/aba-formal-opinion-512.pdf).

This approach needs evidence. The lawyer should know what was tested, whether the test represents the actual work, what kinds of errors remain and how the workflow responds to them. A product-wide benchmark or an assurance that a model is generally excellent cannot establish reliable use in every matter. Testing only the easy documents would be particularly weak support for a collection containing difficult privileged communications or poor-quality images.

A changed model, expanded tool permission, new language, different document population or new substantive issue may require targeted revalidation. Approval belongs to the actual deployment and purpose, not indefinitely to a brand name.

### The unit of judgment changes the answer

A million documents in one discovery project are not a million unrelated client representations. The responsible lawyer can make meaningful professional judgments about a defined review population, its criteria, validation and production. A random sample of a million separately generated client recommendations does not, by itself, show that the lawyer supplied the legal judgment each representation requires.

That difference prevents two errors. One is to reject all sampling because it cannot prove a lawyer considered every output. The other is to extend sampling from a bounded review task to an entire autonomous law firm, without asking which client decisions and personal professional acts remain.

The right questions are concrete: What service is being supplied? Which judgments can reasonably be made about the method or population? Which require attention to an individual matter or output? Which are expressly personal under law? What evidence supports reliance at each level?

### Autonomy in preparation and authority to act are distinct

A research agent can choose searches, follow citations, explore opposing theories and refine a draft without continuous prompting. A document-review system can apply accepted criteria across a defined corpus. Neither form of operational autonomy necessarily carries authority to settle, send new advice or file a court paper.

A useful design separates the ability to prepare a proposed action from the ability to make it effective. A lawyer-approved document can be transmitted unchanged through an authorized process. If a generative agent alters its legal content during transmission, the earlier approval may no longer cover what was sent.

The law does not prescribe a particular approval interface, cryptographic signature or software architecture. The firm should be able to explain how its actual controls preserve the required decisions and prevent unauthorized consequences. The goal is the minimum sufficient human intervention consistent with competent service and real legal duties. That is a legitimate ambition, and a different proposition from making human involvement ceremonial.

### Prepared recommendations can support an actual decision

An older administrative-law decision helps explain why receiving a recommendation need not mean surrendering the decision. In **Schecter v. County of Los Angeles**, the California Court of Appeal quoted a rule allowing an official to use:

> “the aid of subordinates directed by him to investigate and report the facts and their recommendation”

The passage also allowed initial drafting while requiring that the ultimate judgment and orders **“were actually his own.”** Schecter concerned civil-service administration, not an AI law firm. It supplies a useful analogy: a person can consider a prepared recommendation while still exercising the discretion the law assigns to that person. The important fact is genuine evaluation and decision, not whether the first suggestion came from someone else. [Schecter v. County of Los Angeles, 258 Cal.App.2d 391, 397–398 (1968)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/iq/iqHNV9F6IDTuZgQE8HAuejF.pdf).

The harder case is a polished answer whose reasoning and sources cannot be examined. A lawyer may have little basis for distinguishing a sound result from a plausible mistake. An AI-native firm should therefore invest in reviewable work products: linked source passages, identified assumptions, separated facts and inferences, and clear explanations of the alternatives considered. Those features make high autonomy in preparation more usable by the professional who must decide.

This article does not propose a rule that a lawyer must inspect every internal token or every discarded draft. The obligations concern the legal work, judgments, advice and representations the lawyer uses or allows the system to make. Court filings receive particularly explicit treatment. Designing the system to retain every meaningless intermediate artifact would not itself establish professional competence; designing it to support meaningful evaluation is more relevant.

### A system can shift judgment without producing an obvious recommendation

An agent that ranks evidence can influence which facts the lawyer sees first. A summarizer can omit a damaging qualification. A tool that labels a matter low risk can determine whether it ever reaches a lawyer. These are reasons to examine the entire process, including how information reaches the person who is supposed to decide.

The law does not become clearer merely because separate agents perform small pieces. One agent might select the facts, another choose the governing rule, another recommend a remedy, and another compose the message. If the lawyer only corrects grammar at the end, distributing the work across four agents has not restored professional judgment.

Conversely, multiple agents can improve the process when their differences remain visible. A second analysis that identifies an overlooked exception can make lawyer review more informed. That is a constructive use of diverse model outputs. It becomes much less useful if an automated consensus step hides the disagreement before the lawyer sees it. Agreement between models is a screening aid; it is not proof that a legal proposition is supported by an actual authority.

<a id="v2-discovery"></a>

## 6. eDiscovery makes the interpretation concrete

Dazza’s eDiscovery example is the most useful pressure test in this research. It brings together legal criteria, large volumes, court-supervised obligations, measurable performance and a mature framework for handling residual error. It asks what responsible legal practice actually looks like when personal repetition of every operation is not a reasonable default.

The argument does not require classifying every step of discovery as work reserved exclusively to lawyers. Collecting files, removing duplicates and copying dates may be technical operations. Determining what a request reaches, whether a privilege applies or whether a production is adequate can involve substantive legal judgment. A real workflow combines both. Calling the entire process clerical obscures the question; calling every operation personally nondelegable obscures it just as much.

### What the California federal order actually shows

In *Schulte v. LinkedIn Corporation*, No. 22-cv-00237-HSG (LB), an order dated June 30 and filed July 1, 2026, records LinkedIn’s use of Relativity aiR. LinkedIn disclosed that:

> “Relativity aiR is being used to make final responsiveness calls”

with quality control through:

> “human review of samples taken from each responsiveness type.”

The review population was 204,444 documents. The court denied requests to prohibit preliminary keyword culling, compel aiR across all custodial files and require additional metrics. It treated the tool within the existing electronic-discovery arrangement and required the parties to meet and confer on search strings. [*Schulte*, ECF 203, pp. 2, 4–7](https://cases.justia.com/federal/district-courts/california/candce/4%3A2022cv00237/390494/203/0.pdf).

This is significant evidence of a real workflow in which the model’s calls can become operative without separate human review of each record. It is not a ruling construing SB 574, a blanket finding of perfect reliability or an authorization of every privilege-review method. The court allowed the disclosed approach while resolving particular disputes; it did not mandate GenAI for other litigants.

Our inference is that a prohibition on substantive AI classification without individual lawyer repetition could exclude this kind of workflow. That is a present legal-policy problem, even without proving that no alternative could ever meet the court’s requirements.

### The older discovery cases support reasonable methods, not a single mandatory technology

*Da Silva Moore v. Publicis Groupe*, 287 F.R.D. 182 (S.D.N.Y. 2012), approved computer-assisted review in an appropriate case while expressly declining to require it universally or endorse a vendor. Its protocol included human review of documents predicted relevant and random checks of excluded documents. It should not be recast as approval of every later autonomous workflow. Its durable lesson is that counsel can design an appropriate technological process with quality control. [Opinion and protocol, especially pp. 192–193 and 202–203](https://openjurist.org/287/frd/182/moore-v-publicis-groupe).

The July 13, 2016 order in *Dynamo Holdings Limited Partnership v. Commissioner* rejects the premise that either human review or discovery responses are perfect. Applying the Tax Court’s reasonable-inquiry standard and comparing Federal Rule 26(g), it upheld the predictive-coding response and denied the requested additional production. It also quoted *Rio Tinto*’s warning against imposing a higher standard on technology-assisted review than on other search methods. These are technology-assisted-review authorities, not decisions on the new California bill. [*Dynamo*, Nos. 2685-11 and 8393-12, pp. 7–9](https://assets.ctfassets.net/jqxgjfvolqmr/7H8fXaoDKu5QSTqtIM1nsO/5b18cd65c6ec8774227b86187872654d/Dynamo_07_13_2016.pdf).

The limitation is just as useful. *Hyles v. New York City* declined to compel predictive coding, and *In re Viagra Products Liability Litigation* took a similar approach. Their concern was reasonable discovery, not a general obligation to buy the newest or nominally best tool. They undermine the sweeping claim that courts already mandate GenAI. They do not establish that reasonable methods must remain frozen as technology changes. [*Hyles*, ECF 97, pp. 4–5 (S.D.N.Y. Aug. 1, 2016)](https://cases.justia.com/federal/district-courts/new-york/nysdce/1%3A2010cv03119/361399/97/0.pdf); [*In re Viagra*, Oct. 14, 2016 order, pp. 2–3](https://www.govinfo.gov/content/pkg/USCOURTS-cand-3_16-cv-05261/pdf/USCOURTS-cand-3_16-cv-05261-0.pdf).

### California’s ethics guidance already recognizes supervised technical work

Formal Opinion 2015-193 describes the technological competence needed for electronic discovery. It requires active attorney involvement, including appropriate testing and supervision, and rejects uninformed reliance on a vendor or on an assumed clawback cure. It does not prescribe personal attorney review of every document. It predates GenAI and addresses earlier rules, so its application here is an analogy rather than a statutory holding. [COPRAC Formal Opinion 2015-193, pp. 3–7](https://www.calbar.ca.gov/sites/default/files/2025-11/CAL%202015-193%20%5B11-0004%5D%20%2806-30-15%29%20-%20FINAL1.pdf).

D.C. Ethics Opinion 362 provides a useful caution from the vendor side. Its example includes a vendor selecting responsive documents, preparing a privilege log and preparing the discovery response. It treats the nature of those services, ownership and actual legal supervision as consequential. It does not say that supervision automatically authorizes a nonlawyer-owned organization to practice law. Its jurisdiction’s ownership rules differ from California’s. The example helps identify substantive functions within discovery; it supplies no independent California AI permission. [D.C. Ethics Opinion 362, Parts A–C](https://www.dcbar.org/for-lawyers/legal-ethics/ethics-opinions-210-present/ethics-opinion-362).

Together, these sources support an important distinction: the lawyer can own and direct the legal service without personally performing every step, but cannot simply give a vendor the representation and assume responsibility has been discharged.

### How a validated review would operate

A defensible design begins with the matter. Counsel identifies the relevant requests, claims, defenses, protective orders and substantive legal standards. The team defines the document population, including custodians, dates, file types and exclusions. An excellent classifier cannot recover a responsive document that was wrongly excluded before it reached the classifier.

Counsel then develops review criteria in language that can be applied and tested. The system may suggest improvements, identify ambiguous instructions and propose examples. The lawyer remains responsible for the adopted criteria and their appropriateness to the matter. Instructions that encode legal strategy are themselves an important part of the professional work.

The team tests a defined configuration against appropriate examples and samples. It investigates disagreements rather than automatically assuming either the human or model label is correct. Where feasible, validators should form their initial judgments without seeing the model’s answer; otherwise agreement may measure influence rather than an independent check. The test should include difficult and underrepresented material, not just convenient examples.

Once the evidence supports use, the system can apply the criteria at scale. Human work can concentrate on exceptions, legally difficult categories, poor source quality and targeted quality control. Negative-coded samples matter because missed responsive material is often invisible in a dashboard of documents selected for production.

Counsel evaluates the production as a whole, resolves the legal questions requiring particular attention, fulfills applicable certification duties and retains a record sufficient to explain the method. That can constitute substantial professional judgment even though many item-level calls were made through the system. This is our recommended construction and design; it is not an automatic statutory exemption.

A workable plan also states what would invalidate continued reliance. A new issue, changed collection, model update, unexpected error pattern or failed escalation may require a pause, narrowed use or further testing. Approval should not silently survive every change.

### What the measurements do—and do not—show

**Recall** asks how much of the responsive material the method finds. **Precision** asks how much of what it selects is actually responsive. A sample of excluded material can help estimate what was missed. Each estimate depends on the population, sampling design and accuracy of the judgments used as the reference.

**Elusion** is the proportion of the excluded population that is actually responsive, estimated through an appropriate sample. It answers a different question from recall. A very large excluded population can contain important missed material even when that proportion looks small. The sampling design and uncertainty around the estimate matter as much as the displayed percentage.

Overall agreement can be misleading. In a hypothetical collection with very few responsive records, labeling almost everything nonresponsive can produce an impressive percentage agreement while missing much of what matters. The value of a method depends on its errors, not only its average score.

Nor is the human reference necessarily flawless. Reviewers can disagree or repeat a mistaken interpretation of the protocol. Adjudicating disagreements and checking important subpopulations are part of the evaluation. A model’s written explanation helps locate a claim in a document, but is not proof that the claim is correct or a reliable account of the model’s internal causal process.

There is no universal accuracy percentage in SB 574 that authorizes legal practice. Thresholds should reflect the task, consequences, legal duties, available alternatives and court orders. A review that is adequate for prioritizing likely useful documents may be inadequate for excluding the rest from production.

### Product documentation shows that this is an operating method, not a speculative invention

Relativity’s aiR documentation describes development, validation and application of prompt criteria. It distinguishes predictions from coding fields and allows accepted results to be transferred into operative coding. That is why calling an output a suggestion does not settle the legal issue: a workflow can adopt suggestions across a population. Its validation materials also distinguish metrics from human-coding error and permit controls to reduce validator exposure to AI answers. [Relativity overview](https://help.relativity.com/RelativityOne/Content/Relativity/aiR_for_Review/aiR_for_Review.htm); [results and coding](https://help.relativity.com/RelativityOne/Content/Relativity/aiR_for_Review/aiR_for_Review_results.htm); [validation](https://help.relativity.com/RelativityOne/Content/Relativity/aiR_for_Review/aiR_for_Review_validation_in_RC.htm); [validation setup](https://help.relativity.com/RelativityOne/Content/Relativity/aiR_for_Review/Setting_up_aiR_for_Review_Prompt_Criteria_validation.htm).

Everlaw’s published Coding Suggestions workflow likewise describes counsel-provided criteria, iterative testing, large-scale use and sample validation. It distinguishes uses with different quality needs and allows human–AI disagreements to be adjudicated. These are primary descriptions of product operation, not independent findings that the products outperform all alternatives or satisfy every legal duty. [Everlaw’s recommended workflow](https://support.everlaw.com/hc/en-us/articles/29807941947035-Recommended-Workflow-to-Leverage-Coding-Suggestions-for-Review).

The supplied research also identifies DISCO Auto Review, Reveal aji and hybrid GenAI/TAR methods, Epiq, HaystackID/eDiscovery AI, Lighthouse, Nuix and other offerings. Their useful contribution is a catalogue of functions to evaluate: responsiveness, issue coding, privilege support, log drafting, data extraction and protected-information handling. The research-leads section preserves that broader catalogue without converting vendor claims into a ranking or a guarantee.

### Responsiveness, privilege and confidentiality require different answers

A document can be responsive, privileged and commercially sensitive at the same time. Responsiveness asks whether it falls within the relevant request and discoverable scope. Privilege or work-product protection may justify withholding it. Confidentiality may instead require a protective designation, restricted access or redaction while production still occurs. One label cannot answer all three questions.

The strongest direct GenAI example here concerns responsiveness. Privilege analysis can involve additional context, mixed purposes, waiver and the adequacy of descriptions supplied to the opponent. That calls for separate criteria and evidence. It does not justify inventing a categorical rule that every potentially privileged document must always receive an individual lawyer’s determination. The governing law, orders, process and applicable protection against waiver must be examined.

Federal Rule 26 provides for reasonable inquiry and for claiming protection, describing withheld material and handling claims made after production. The December 2025 amendment specifically brings the timing and method of privilege descriptions into early discovery planning, with a parallel case-management amendment to Rule 16. That supports a tailored protocol rather than a universal privilege-log method. [Rule 26(b)(5), (f)(3)(D), (g), and 2025 note](https://www.law.cornell.edu/rules/frcp/rule_26); [Rule 16](https://www.law.cornell.edu/rules/frcp/rule_16).

Under Federal Rule of Evidence 502(b), inadvertent disclosure avoids waiver only under specified conditions. A properly framed 502(d) court order can provide broader nonwaiver protection; an agreement alone has more limited reach under 502(e). The rule’s explanatory material contemplates arrangements reducing costly preproduction review. But preventing waiver does not erase what another person has learned, cure every confidentiality failure or protect all nonprivileged secrets. California’s return-and-sequestration procedure is not identical to the full effect of a federal 502(d) order. [FRE 502](https://www.law.cornell.edu/rules/fre/rule_502); [CCP § 2031.285](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=CCP&sectionNum=2031.285.).

This is the constructive point of clawback: the legal system can manage residual error through an appropriate process without demanding perfection. It is not permission to use an untested system or disregard affected people’s confidential information.

### Showing reliability need not mean exposing every strategic prompt

A review protocol can contain the lawyer’s theories, witness-derived facts and legal judgments. The supplied research identifies Tara Emory and Maura Grossman’s paper arguing that such GenAI prompts can warrant work-product protection. That is a scholarly argument, not a holding that all prompts are protected. A prompt merely repeating a request may raise different issues from one revealing counsel’s strategy. The full paper was not retrieved in this review; the located abstract and publication discussion are a useful lead. [Emory and Grossman, *GenAI Prompts in eDiscovery: Protected Work Product or Not?*](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7036120).

The practical proposal is to plan how a workflow’s reliability can be demonstrated while preserving legitimate protection: agreed methods, aggregate results, appropriately limited disclosures and judicial protection where warranted. A generic AI-use disclosure should not casually become disclosure of all prompts, client secrets or strategic analyses. Equally, the firm should not promise secrecy that the governing law or discovery order does not provide.

### How strong is the case that SB 574 would inhibit discovery?

The strongest supported statement is conditional:

> An interpretation that prohibits substantive GenAI classifications within an attorney-directed, validated review process could exclude a method already used in federal litigation in California. In a particular matter, replacing that method could materially increase cost, delay or error and make the existing discovery plan impracticable.

That is our synthesis, not a quotation from a court. It is more defensible than claiming that all modern discovery is court-mandated GenAI or that California attorneys would necessarily become unable to litigate.

To establish actual serious impairment in a particular matter, compare the real alternatives after appropriate culling and deduplication: the remaining population, available reviewers, measured throughput, error rates, schedule, cost and possible changes to the order. Vendor marketing and a large raw document count cannot replace that evidence. They can identify where to investigate.

One textual detail also matters. Section 128.7 retains a discovery exclusion in subdivision (g). A new citation-verification paragraph should not casually become a duty to personally classify every discovery document. The interaction of the provisions deserves careful reading, and discovery remains subject to proposed section 6068.1, professional duties, discovery-specific certification and court orders. Materials exchanged between parties are not automatically documents submitted to a court. [SB 574, proposed CCP § 128.7(b)(2) and retained (g)](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=202520260SB574).

The question for COPRAC is therefore precise: what additional individual act, if any, would SB 574 require beyond a professionally directed and adequately validated discovery process, and why? Answering that question would help lawyers use AI more responsibly and more extensively at the same time.

<a id="v2-accountability"></a>

## 7. What the book adds: accountability that works when humans do not inspect everything

Ryan McDonough’s *Human Accountable for the Loop*, Digital Edition, Release 2, September 1, 2026, supplies the operational vocabulary that the bill lacks. It is a governance framework, not a legal opinion about SB 574. Its value is explaining what responsibility should mean when a service acts too quickly or at too large a scale for individual human review. Page references below are the book’s printed pages; the PDF viewer count is one higher. The supplied book.

The book does not insist that preserving accountability requires preserving every human operation. It states:

> “Qualitative judgement doesn’t always have to be reserved for a person as a matter of dogma.”

And, in discussing the capability of human supervisors:

> “Independent manual performance is not an absolute requirement for every future task.”

Those propositions, at printed pages 49 and 90, are particularly helpful to an AI-native practice. A lawyer may need to understand a system’s limits, evaluate its performance and contain its consequences without being capable of manually reproducing every operation at the same scale. Whether that arrangement satisfies a particular legal duty remains a separate question.

### Review, monitoring and ownership are different arrangements

The book distinguishes reviewing individual outputs, monitoring a running process and owning the service’s operation. It does not present them as a ladder on which more autonomy is always better. A workflow may need all three at different points.

For example, counsel may own a discovery process, monitor validation and error signals, and individually review a difficult privilege question. A filing workflow may permit extensive internal preparation but require personal examination of its legal authorities and approval before submission. A general legal-information service may operate with different controls from individualized advice.

The constructive question is which arrangement supplies meaningful control for the particular consequence. Requiring individual approval everywhere can exhaust the reviewer without improving safety. Using monitoring where a personal legal act is required can be inadequate even if monitoring is excellent. See printed pages 8–11 and 21–31.

### An approval needs information, time, authority and effect

A review button is useful only if the reviewer has an adequate basis to decide, enough time to do so, the authority to reject or change the result and a decision that affects what happens. Removing any of these conditions can turn approval into evidence protecting an organization rather than power protecting the person affected by its work.

For an AI-native firm, that means more than displaying a finished draft. The lawyer needs its material sources, uncertainties and choices. The system must not make approval practically unavoidable by sending the document first, hiding contrary evidence, overwhelming the review queue or penalizing delay so severely that rejection is unrealistic.

These are operational conditions for meaningful review. They are not a four-element statutory test enacted by SB 574. They help explain why a genuine examination can support the preferred assistance interpretation and why a human signature alone cannot. See printed pages 9–11.

### Describe the action and then enforce its boundary

The book’s verbs—advise, prepare, decide and act—help reveal what a workflow actually does. A draft and a sent message can contain identical words but have different consequences. Personalized advice can itself be a legal service, so the vocabulary does not imply that only a final act or decision matters.

An operating plan should identify permitted actions, affected records, counterparties, data, monetary and volume limits, duration and exception routes. A contracting agent might prepare proposed terms and route an exception without permission to send the proposal, accept an offer, sign or alter an executed contract. Permission should attach to a defined purpose and configuration, with a review date. See printed pages 45–52 and 113–125.

Instructions influence a model; controls outside the model can restrict what it can actually do. For example, an internal drafting identity can lack authority to send client advice, while a separate delivery process accepts only an approved version and recipient. A document from an opponent can be treated as evidence rather than an instruction to a downstream agent. These are implementation options that support retained authority, not technologies the statute specifically requires.

Dazza’s public [*Authority Boundaries for AI*](https://www.dazzagreenwood.com/p/authority-boundaries-for-ai) makes a related distinction among prompt-and-workflow instructions, tool capabilities and code-enforced boundaries, with further controls over spending, time and workflow stage. The post’s value here is the engineering principle: match the strength of the control to the action’s autonomy and consequence. This report does not claim to have repeated the repository tests described in that post.

The book’s worked contracting example uses a 90-day bounded operating decision. The useful idea is time-limited authority that is reconsidered, not a mandatory 90-day legal rule. The firm can choose operation with logging, operation with notification or mandatory prior approval for different actions. These modes should follow consequence and evidence; they should not collapse into either a passive chatbot or unrestricted agency.

### Escalate a difficult case, a broken process and a wrong premise differently

The book’s three escalation levels deserve a place in legal-AI guidance. A **case exception** is a difficult item within an otherwise working method. An **operational incident** means the method or its controls may be failing. A **challenge to the premise** asks whether the service is pursuing a lawful and justified objective at all.

In discovery, an ambiguous document might go to a lawyer; a batch of missing attachments might go to the process owner and halt that batch; evidence that the review protocol systematically excludes a relevant theory may require counsel to reconsider the protocol and earlier production. A single instruction to escalate when necessary does not specify any of this.

Each route needs a recipient with authority, a response expectation and a defined state for affected work while the issue is pending. Sometimes containment is better than shutting down the entire firm: isolate the defective collection, preserve evidence and continue unrelated work that remains justified. A shutdown can itself cause missed deadlines or interrupted service. See printed pages 56–72.

### Preserve evidence of operation, not just a persuasive explanation

A model-generated rationale can help a reviewer, but it is not proof of the model’s internal reasoning or of the truth of its conclusion. The record should instead connect the purpose and authority, relevant inputs and sources, configuration, outputs, material human decisions, actual actions and outcomes.

The book’s reconstruction drill asks whether someone can determine what happened in an ordinary event and in a failure. That is a practical test for a firm. Can it identify which version was released, what authority covered it, who received it and what needs correction? Can it find other matters that relied on the same defective source or configuration?

This does not require storing hidden model reasoning, preserving every intermediate token indefinitely or making confidential records publicly available. Evidence retention should be proportionate, secure and consistent with applicable duties. Tamper-evident records and controlled amendments can be useful, but a particular cryptographic implementation is not itself legal compliance. See printed pages 76–83.

### The book’s examples identify different failures

The historical examples are useful as governance illustrations **as reported in the supplied book**, rather than as independently established findings in this legal review. Horizon, Robodebt and MiDAS illustrate institutions allowing automated processes to acquire practical authority while challenge and correction fail. The *Williams v. City of Detroit* settlement illustrates why a human step needs an independent evidentiary basis, rather than merely a person repeating a system’s conclusion.

The book’s account of *Cork v. Smith* describes an AI policy and supervising solicitors that did not prevent invented statutory wording reaching court. We have not separately retrieved that judgment here; it is a comparative lead, not an additional verified holding. Its practical lesson resembles the verified California filing cases: the presence of a policy and a reviewer does not establish actual source verification.

Knight Capital illustrates the importance of effective limits and containment. The Epic Sepsis Model discussion illustrates local validation and the risk that excessive alerts make a monitoring channel less useful. The discussion of a GPT-4o rollback illustrates configuration change; SafeRent illustrates the influence of a score even where someone else makes the nominal decision; accessiBe and DoNotPay illustrate why compliance or professional-equivalence claims need evidence. These examples concern different sectors and legal regimes. Their common value is asking which mechanism failed and what evidence would reveal the same failure in a law practice. See printed pages 50–65, 76–78, 90–111.

### Preserve professional capability without preserving obsolete labor

A firm should know how future lawyers will acquire the ability to supervise, challenge and improve its systems. That is not a reason to require every junior lawyer to repeat a task that no longer teaches useful judgment. The book offers four responses: preserve valuable experience, compress it into more focused learning, simulate difficult cases or move learning into different work.

A training program could ask juniors to identify hidden assumptions in an AI draft, adjudicate difficult classification disagreements, investigate a production failure or design a better validation set. It could test whether reviewers can explain why an unfamiliar output is acceptable rather than merely approve familiar-looking prose.

Warning signs include implausibly fast reviews, an absence of meaningful disagreement and inability to explain accepted results. These are signals to investigate, not automatic proof of professional decline. Capability loss is an empirical risk; better tools can also improve learning. See printed pages 89–90 and 115–118.

### A practical rubric, used without pretending it is a certificate

The book’s workbook groups 24 tests into eight domains. The following condensed adaptation preserves all three questions in each domain. It is an optional diagnostic for the proposed service, not a legal safe harbor. See printed pages 146–149.

| Domain | Three questions for the proposed workflow |
|---|---|
| Ownership | Is a current responsible person and continuity arrangement identified? Can that person invoke timely, tested containment? Has the person accepted the defined responsibility and reconfirmed it on review? |
| Authority | Are permitted acts explicit? Are they enforced outside the model? Are relevant value, volume, data and counterparty limits enforced? |
| Limits | Are prohibited acts and unacceptable consequences specified? Does reaching a limit actually prevent or contain the action? Have bypasses and recovery been tested? |
| Escalation | Do triggers cover uncertainty, novelty and consequential exceptions? Does the issue reach someone able to decide within a monitored time? Is affected work held or safely contained meanwhile? |
| Evidence | Can a material event be reconstructed without hidden model reasoning? Are records time-stamped and changes controlled? Are material reviews and interventions attributable and supported by appropriate capability evidence? |
| Monitoring | Do signals cover the service, data, behavior, actions, human operation and outcomes? Do thresholds reach an actual decision-maker? Can severe anomalies trigger timely containment where justified? |
| Review | Is there an owner and date for reconsideration? Does review retest purpose, authority and assumed human capability? Can it continue, constrain, pause or retire the service? |
| Liability | Are actions creating legal or financial obligations mapped to controls? Do supplier and customer arrangements address automated action and evidence access? Have insurance, notice and remedy arrangements actually been checked? |

The workbook uses evidence states—absent, partial, implemented and tested—and expressly warns against averaging them into a reassuring total. A strong domain cannot compensate for a missing critical control elsewhere. It identifies four critical failures: inability to suspend, authority existing only in instructions, limits that do not constrain action and inability to reconstruct a material decision.

That is also a useful lesson for legal interpretation. A beautifully drafted policy cannot compensate for a system that can commit a client beyond its authority. An excellent accuracy score cannot compensate for prohibited disclosure. At the same time, the rubric’s own statement of limits matters: governance evidence supports a decision; it does not promise immunity or establish legal permission.

<a id="v2-workflows"></a>

## 8. Four ways an AI-native firm could be organized

The following designs combine the practical contributions in the research with the legal qualifications explained above. They are illustrations, not statutory permissions or a promise that a court would approve every implementation. Their purpose is to show what a highly automated practice might actually do, which decisions remain professional decisions, and where a proposed system becomes harder to defend.

### First, make the lawyer’s control operational

One useful analogy comes from **County of Santa Clara v. Superior Court**, a 2010 California Supreme Court decision concerning public-nuisance litigation conducted with outside contingency-fee counsel. The court required actual governmental control, not merely contractual assurances. It said the arrangements:

> “should encompass more than boilerplate language regarding ‘control’ or ‘supervision’”

The court identified retained decisions, veto authority and personal supervisory involvement. The case is about public-entity neutrality in a particular litigation arrangement. It is not a binding set of rules for every private law firm using AI. Its value here is practical: a power to control the work means little if no one actually exercises it. [County of Santa Clara v. Superior Court, 50 Cal.4th 35, 63–64 (2010)](https://scocal.stanford.edu/opinion/county-santa-clara-v-super-ct-33882/).

For an AI-native firm, that suggests asking what the lawyer can see and change, not merely whether the engagement agreement says the lawyer is responsible. Can the lawyer inspect the sources? Can the system issue advice before review? Can it make a commitment that cannot readily be withdrawn? Does it identify uncertainty, or is it rewarded for producing a confident answer to every question?

Santa Clara’s public-litigation setting limits the analogy. Its control features are useful design considerations, not a universal judicially approved checklist for private AI practice.

### Model one: an autonomous internal legal-work engine

Consider a firm advising businesses on contracts. A client uploads an agreement and explains the transaction. After the firm has appropriately established the matter and the lawyer has identified the client’s objectives, agents can perform a substantial body of preparation.

A document agent extracts the agreement’s provisions and identifies missing attachments. A research agent checks the legal questions raised by the clauses. A commercial-analysis agent compares proposed positions with the client’s stated priorities. Another agent develops the counterparty’s strongest objections. A drafting agent produces alternatives rather than a single unexplained recommendation. A review agent checks whether the draft accurately reflects the sources and the transaction facts.

The system can repeat this process without a lawyer choosing every search term or directing every intermediate revision. If one agent discovers a problem with the proposed limitation of liability, it can ask another to examine a different clause structure and assemble the relevant authorities. This is a meaningful form of autonomy: the tools organize their work, investigate uncertainty and improve their preparation within the assignment.

The result for the lawyer should be more than a finished-looking contract. It should include the proposed changes, their practical effects, the evidence and law supporting them, and the material alternatives. If two analyses disagree about enforceability, the disagreement should be explained rather than hidden by a majority vote. The lawyer can then make an informed professional decision about what to recommend to the client.

Suppose the system proposes a broad indemnity clause because it favors the client in isolation. The lawyer may reject it after considering the commercial relationship, the likelihood of acceptance, insurance implications and other provisions in the contract. Alternatively, the lawyer may accept the idea but narrow its scope. In either event, the lawyer is doing more than checking whether the text is grammatical. The lawyer is deciding which legal arrangement serves the client.

After those decisions, agents can prepare the revised document and explanation for the lawyer to inspect and approve. They can perform consistency checks, identify places where a defined term no longer works, and compare the final version with the version the lawyer reviewed. A conventional delivery process can transmit the approved material under the firm’s procedures. A generative system should not be free to alter the advice while supposedly carrying out that last step.

This design has a strong basis under the preferred assistance interpretation. It resembles the preparatory-work relationship discussed in Crawford: substantial work helps produce a legal service that the attorney actually evaluates and adopts. It also fits the focus on retained judgment in Noland and the State Bar guidance. It is not section 6450 automatically extended to a machine, and it does not eliminate the broader interpretive risk identified earlier.

The same model can serve litigation. Agents can build a chronology, locate inconsistent testimony, research elements of claims, identify adverse authorities, draft competing motions and prepare a source packet. They can keep working internally while the lawyer is occupied elsewhere. Before a court submission, however, the responsible attorney must do the required substantive and citation verification. A second agent’s favorable assessment cannot serve as a substitute for the attorney’s personal obligation.

The system should therefore prevent agents from sending documents to a court on their own. The May 2026 guidance’s court-submission discussion is explicit about lawyer review and approval and about autonomous court communications. An authorized filing process transmitting the lawyer’s approved, unchanged document is a different arrangement from an agent selecting, revising and filing its own submission. [State Bar 2026 AI guidance, p. 9](https://www.calbar.ca.gov/sites/default/files/portals/0/documents/ethics/Generative-AI-Practical-Guidance.pdf); [Noland, 114 Cal.App.5th 426](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/ip/ipQx4JJgO06quV81pqAmq59T.pdf).

This model can preserve much of the value sought from autonomous agents. It automates preparation, exploration, comparison and revision rather than requiring the lawyer to operate the system one prompt at a time. How much efficiency it produces will depend on the reliability of the output, the quality of the review interface, and the amount of consequential judgment each matter requires. The research provides no defensible numerical claim about how many matters one lawyer can handle.

### Model two: validated bulk review and portfolio analysis

Consider a lawyer responsible for a large discovery production or a business client’s portfolio of contracts. The professional task is to choose and justify an effective analysis of a defined collection. A requirement that counsel independently repeat every classification would defeat much of the value of using a validated process.

The lawyer identifies the governing requests or business questions, defines inclusion and exclusion criteria, selects a suitable system and obtains technical assistance where needed. The review team tests representative material and difficult categories, resolves disagreements in the reference judgments, measures missed as well as selected material and determines whether the evidence supports use. These are substantive decisions about the legal service.

The agent then applies the accepted method at scale. It can extract provisions, classify responsiveness, identify unusual clauses, summarize patterns and organize exceptions. The lawyer need not approve every intermediate inference merely because legal criteria are involved. Under the preferred interpretation, a supported decision to rely on this defined process is professional judgment, rather than its absence.

The permission is bounded by what was evaluated. A tool validated for ordinary English-language commercial contracts has not thereby been validated for a collection of handwritten medical records, foreign-language correspondence or a new privilege question. An exception may call for a second automated check, a technical investigation or a lawyer’s decision, depending on its nature. A serious failure may require suspending the affected operation while its consequences are assessed.

Before production or external advice, the firm still fulfills the duties applicable to that act. It checks that the collection, criteria, version and authorization match the reviewed arrangement. It addresses protective orders, confidentiality, privilege and client decisions. An approval to classify responsiveness is not permission to concede privilege, alter a settlement position or file a newly generated brief.

For a contract portfolio, the result might be a map of renewal obligations, inconsistent clauses and matters needing advice. That use can reduce labor while increasing coverage. If the system moves from describing the portfolio to advising each separate customer what legal action to take, the unit of professional judgment changes. The quality evidence must support the service actually offered, and applicable individual duties remain.

This model combines specification, validation, monitoring and adoption. It is supported by the discovery and ABA examples in Sections 5–6, with their stated limits. It is also the model most directly threatened by a reading that requires individual lawyer review of every substantive output. That practical difference is a reason to seek affirmative clarification now.

### Model three: a high-volume practice built around reusable decisions and bounded execution

Now consider a firm handling many similar matters. It wants the benefits of standardization without recreating the same research and drafting every time. The commercial objective is understandable: reusable expertise, prompt service and a lower cost per matter.

The critical question is what remains to be decided when a new matter enters the system. Reusing a lawyer-approved clause is different from letting an agent decide that the clause is appropriate for a new client. Transmitting approved advice is different from deciding that a new recipient should receive that advice. The second step in each comparison can require the application of law to facts, even if the firm calls it routing or classification.

A relatively clear example of mechanical execution is sending an appointment reminder with a date already set, or delivering an exact document that the lawyer has approved for an identified matter. Another is applying a specified arithmetic formula to verified numerical inputs, where the lawyer has already determined that the formula governs the matter. The execution can be automated without asking the system to make a new legal choice.

A harder example is an agent that selects a type of eviction notice, determines whether service is sufficient, or decides whether a limitations exception applies. A lawyer may have written rules for those questions in advance, but the system’s application of those rules to new facts may still constitute substantive legal work. Calling the rules predetermined does not settle the issue. Landlords and Reynoso are relevant precisely because form selection and individualized application can be the legally significant service. [Landlords Professional Services, 215 Cal.App.3d 1599](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/xA/xAdj3zrfP920UM9DfFXvChzG.pdf); [Reynoso, 477 F.3d 1117](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/hS/hSLwrxlnjgBzPka2DHZJrwe.pdf).

An ambitious design would use the reusable system to make the lawyer’s matter-specific decisions efficient. The firm could maintain verified research, approved clause libraries, defined questions for intake and a clear explanation of the conditions for each proposed course of action. Agents could collect facts, identify likely categories, retrieve the appropriate source material and prepare the proposed response. The lawyer’s attention could then concentrate on whether the relevant conditions actually hold and whether the proposed course serves this client.

Once the professional decision is made, routine execution need not recreate it. For example, after a lawyer approves a particular demand letter for an identified recipient, software can format it, generate an authorized delivery package, and record the delivery. If the recipient replies with a new legal objection or proposes different terms, the workflow should recognize that the earlier decision may no longer cover the situation. The agent can prepare a response, but a fresh legal question should not be silently treated as permission to continue the old mechanical process.

This distinction can be built into the system’s capabilities. An internal agent may be allowed to generate drafts freely while an external communication tool accepts only a version approved for that matter. A change in the legal content would return the item for review. Such a design is one way to make retained authority real; the law does not prescribe that particular technical method.

The firm should also be careful about relying on an agent to decide when lawyer review is unnecessary. An exception detector can miss the very fact that makes a matter legally different. If the detector’s decision determines whether a client receives advice without professional consideration, the detector is part of the legal decision process. A high accuracy score does not by itself establish that the arrangement is permitted.

Quality testing and sampling can support reliance on a substantive process, as the bulk-review model explains. Their relevance is not confined to clerical accuracy. What they establish depends on the tested service: a defined population of documents is different from a set of unrelated individualized client recommendations. The firm must identify which decisions can be governed through a validated method and which still require attention to the matter, client or particular act.

Negotiation illustrates the problem particularly well. An agent might be authorized to transmit an exact offer that the client and lawyer have approved. Receiving a counteroffer may require more than checking whether the dollar amount falls within a range. The counteroffer could change the release, confidentiality term, admission, remedy or timing. A system that accepts it because the price is acceptable may make a legal decision the lawyer never made. The design should distinguish communication of an approved position from evaluation of a new legal bargain.

A firm can standardize extensively and use substantive automation when its evidence and controls justify the service. Prior specification, meaningful adoption and ongoing validation can be combined. New individualized advice may require a different basis for reliance from a bounded collection, and some acts remain personal. This article does not declare that advance approval of prompts, templates or decision rules provides a comprehensive exemption under SB 574.

### Model four: a client-facing agent that answers legal questions

The most attractive product can also present the sharpest issue: a client opens a portal, asks what to do, and immediately receives tailored legal advice generated by an agent without a lawyer examining that answer first.

The concern is not simply that the advice might be inaccurate. The system is applying law to the client’s facts and delivering the result as part of the firm’s legal service. That is close to the professional function examined in Landlords, Reynoso and Crawford. It also presents the kind of unsupervised substantive determination addressed by the State Bar’s agentic-AI guidance. Putting the firm’s name above the chat window does not establish that a lawyer has made the decision.

A disclaimer can explain what the tool is doing, but it does not automatically change the substance of the service. If a system tells a client which legal right to assert and which document to sign, a sentence describing the answer as information may not make it an impersonal publication. Likewise, a client’s willingness to receive AI advice does not itself create permission to delegate a prohibited professional role.

A lawyer’s review afterward can identify and help remedy a problem. It cannot prevent the earlier reliance that the system already invited. The Florida Supreme Court’s decision in American Senior Citizens Alliance is a useful comparison: tailored nonlawyer advice and document selection were not cured by the cursory lawyer review in that arrangement. The facts concerned a particular estate-planning operation, not an AI chatbot, and meaningful review involves more than timing alone. [Florida Bar v. American Senior Citizens Alliance, 689 So.2d 255 (1997)](https://openjurist.org/689/so2d/255/florida-bar-v-american-senior-citizens-alliance-1863800).

There are, however, several ways to build a useful portal with a stronger legal foundation.

An **information service** can explain general concepts, publish forms and describe procedures without choosing the user’s legal response. Its design should prevent a general explanation from quietly becoming an individualized recommendation. Accuracy, advertising, confidentiality and other applicable rules still matter; general information is not a blanket exemption for everything a portal might do.

An **intake service** can collect documents and facts, identify questions for the lawyer, and explain the next steps in the firm’s process. It can tell the user what information is needed and when a lawyer will respond. The agent’s internal issue spotting can prepare the professional work without presenting its own proposed legal answer as the firm’s advice.

A **lawyer-reviewed advice service** can use an agent to prepare a proposed answer and its sources, then put that answer before a lawyer who actually evaluates and releases it. The client still receives a fast, technology-enabled service. The potential advantage comes from efficient preparation and a focused professional review, not from pretending that the review is unnecessary. This is the strongest fit with the preferred assistance interpretation, while still subject to the legal uncertainty and other duties already explained.

A fourth useful variation is an **approved-advice retrieval service**. After a lawyer has given an identified client advice, the portal can display that advice again or provide an unchanged copy of the approved explanation. A newly generated response that reinterprets the advice in light of new facts is different. It should not be treated as mere retrieval just because the system consulted the earlier message.

These distinctions preserve substantial scope for responsive client service. They also identify where a proposed feature needs closer review: the point at which the system makes or communicates a new legal determination that no lawyer has actually evaluated.

Translation, summarization and extraction also deserve use-sensitive controls. A rough internal translation can help counsel locate material; a translation submitted as accurate evidence may require a very different foundation. These functions can be important parts of the service without carrying independent authority to advise, waive or commit. Their familiar labels should not become categories of automatically harmless work.

### What would make these designs stronger in practice?

The most useful evidence of retained professional judgment is the work itself. It may include the lawyer’s choice between alternatives, correction of a mistaken premise, examination of adverse authority, approval of a specific communication, or decision that the system should stop and obtain more facts. A firm should preserve enough information to explain important decisions without turning every trivial operation into a paperwork exercise.

The system should also make it possible to intervene before a consequential action. A lawyer who can only discover a problem after the client has relied on advice has a different degree of control from one who sees the proposed advice and can change it first. That is why access, tool permissions, version control and escalation can have legal significance in an AI-native practice.

Documenting control is useful evidence, but documentation does not itself supply permission. If a court interprets SB 574 to prohibit a particular substantive assignment, a detailed record of lawyer review would not necessarily cure that prohibition. The designs above strengthen the assistance argument and improve professional practice. They cannot guarantee an outcome under every possible construction of the bill.

<a id="v2-verification"></a>

## 9. Accuracy means checking what the authority supports

The best-designed autonomous workflow will still be vulnerable if the lawyer treats a citation as verified merely because the case exists. A real case can be cited for a proposition it never decided. A genuine quotation can be removed from context. A dissent can be presented as the court’s ruling. An earlier decision can have been reversed or limited on the very issue for which the system recommends it.

SB 574’s proposed amendment to Code of Civil Procedure section 128.7 would require the responsible attorney to have personally completed verification of citations in court papers, including citations supplied by AI. That proposal sits alongside existing duties concerning reasonable inquiry, factual support and warranted legal contentions. The professional task is to determine whether the source actually supports the use being made of it. [SB 574, proposed Code of Civil Procedure § 128.7](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=202520260SB574).

### A persuasive argument can still be supported by unacceptable research

**Del Biaggio v. Bansen**, a California Court of Appeal decision from July 2026, makes this point unusually well. The underlying argument about paralegal fees had merit. That did not excuse false appellate quotations or counsel’s inadequate review of AI-added material. The court also rejected the idea that handing the verification task to a paralegal discharged the attorney’s duty. [Del Biaggio v. Bansen, No. A174647 (Cal. Ct. App., July 10, 2026)](https://law.justia.com/cases/california/court-of-appeal/2026/a174647.html).

Counsel had planned to have a paralegal check the citations, without personally examining the added case law or having another lawyer do so. The court said:

> “This plan would have been inappropriate even if it had not gone awry.”

That sentence makes the distinction especially clear. The problem was not only that the output happened to be false. The proposed checking arrangement was itself inadequate for the lawyer's obligation. A firm cannot infer a satisfactory professional process merely from a run that produced no detected error.

The constructive lesson is not to discard every good idea an AI system produces when one of its sources is wrong. It is to separate the argument from the evidence offered for it. A lawyer might keep a sound legal theory, remove unsupported assertions, find the correct authority and revise the explanation. The system should make that repair possible rather than force a choice between blindly accepting the draft and abandoning it entirely.

Del Biaggio also has an affirmative side. Its discussion of paralegal fees recognizes the value of economical legal assistance; that favorable point should not be lost in an account focused only on sanctions. The same opinion distinguishes useful division of labor from a plan to leave verification of AI-added principal authorities to a paralegal when the attorney had not examined them. Efficiency and a genuinely personal duty can coexist. [Del Biaggio, discussion of paralegal fees and AI-added authorities, pp. 8–10 and 17–19](https://law.justia.com/cases/california/court-of-appeal/2026/a174647.html).

**People v. Alvarez**, decided by the California Court of Appeal in 2025, involved a fabricated quotation attributed to a real opinion. Its warning is direct:

> “attorneys cannot delegate this responsibility to any form of technology”

The responsibility was verification of the legal material being presented. **United States v. Farris**, a 2026 Sixth Circuit case, likewise involved misleading descriptions of genuine authorities. These decisions show why a check that returns only “case found” is insufficient. [People v. Alvarez, 114 Cal.App.5th 1115 (2025)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/t4/t4liYSZ7hv8SXO8B7Udmsl.pdf); [United States v. Farris, No. 25-5623 (6th Cir., April 3, 2026)](https://www.opn.ca6.uscourts.gov/opinions.pdf/26a0105p-06.pdf).

In **Shayan v. Shakib**, the California Court of Appeal emphasized that:

> “the signatory attorney is responsible for the content of the brief and subject to sanctions for inaccuracies it contains”

The existence of a contractor, associate, research service or AI provider in the production chain does not make the signer’s obligation disappear. The precise sanction and its required findings still depend on the governing rule and facts. These authorities should not be turned into a claim that every mistake has the same consequence. [Shayan v. Shakib, 116 Cal.App.5th 617 (2025)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/ba/bag7Agzkm3ORqvFm3hEaiJg4.pdf).

An effective research system could therefore prepare a source packet for each important proposition: the relevant passage, the court and date, the procedural setting, later treatment, and the reason the passage supports the proposed sentence. That is an illustrative design, not a statutory requirement for a particular document format. Its purpose is to make the lawyer’s actual verification efficient and reliable.

Two additional decisions reinforce the point from other jurisdictions. In **Leiske v. Kidd**, the Delaware Court of Chancery, a state court, addressed candor and the required inquiry into court submissions. It explained:

> “Counsel cannot discharge those obligations by relying on a paralegal, much less on an artificial intelligence program.”

That is a statement about those professional obligations, not a general prohibition on using paralegals or AI for preparation. [Leiske v. Kidd, No. 2025-0426-CDW (Del. Ch., July 1, 2026)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/CQ/CQKyOTjsrMBAJyya6FVtdaQg.pdf).

In **Estate of Caviness v. Atlas Air, Inc.**, the Eleventh Circuit connected the problem to competence:

> “It goes without saying that completely outsourcing one's legal work to artificial intelligence software is not competent.”

The case involved deficient court submissions and the lawyer's failure to supply the professional work expected of counsel. It supports the distinction between an agent that helps a lawyer prepare and a lawyer who abandons that role. It does not construe SB 574 or resolve every form of substantive, reviewed AI assistance. [Estate of Caviness v. Atlas Air, Inc., No. 24-11033 (11th Cir., July 10, 2026)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/1N/1Nham0RXWFnvw2EMUGg6zlJT.pdf).

### Do not confuse a signed form with a verified statement

**Drociak v. State Bar** supplies a different warning. Clients had signed blank verifications, and the lawyer later completed interrogatory answers without consulting them. The California Supreme Court rejected unsupported allegations that staff had forged the signatures; the problem was the use of the presigned forms for statements not confirmed by the clients. The court explained that:

> “his use of presigned verifications posed a threat to the administration of justice”

The case concerns personal attestation rather than an AI workflow, but the connection is useful: an approval provided before the content exists cannot automatically establish that the signer verified the eventual content. [Drociak v. State Bar, 52 Cal.3d 1085, 1087–1090 (1991)](https://scocal.stanford.edu/opinion/drociak-v-state-bar-31294/).

An agent can help collect answers, identify inconsistencies and prepare a draft for review. It should not treat a client’s earlier blanket approval as confirmation of facts the system later supplies. The same reasoning cautions against treating a lawyer’s standing instruction to an agent as approval of every future legal representation the agent may generate.

### A duty to verify does not make every sanction question identical

The distinction between a professional duty and the remedy for violating it is also worth preserving. In **State v. Coleman**, an Ohio appellate decision, the court addressed oversight of AI-assisted work and emphasized that the attorney retains:

> “ultimate responsibility for the accuracy and propriety of the filing”

A separate judicial disagreement concerned additional sanctions and process. It did not endorse false filings. The useful point is that agreement about the obligation to verify need not settle who should be sanctioned, by which authority, after what procedure and to what extent. [State v. Coleman, 2026-Ohio-965](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/Ay/AyFddPhlmGDIsTmeD8tjg6St.pdf).

The same opinion rejects reliance on an unenforced instruction about AI use:

> “A policy that is neither monitored nor enforced is no policy at all.”

For an AI-native firm, the practical implication is to connect its policy to actual supervision. Who checks whether the policy is followed? What happens when a tool acts outside its permissions? How does the responsible lawyer learn about an error? The answers matter more than the existence of a written policy by itself. [Coleman, paragraph 62](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/Ay/AyFddPhlmGDIsTmeD8tjg6St.pdf).

For a firm, that distinction encourages prevention and accurate incident assessment. An error in an internal draft, an inaccurate filing, a knowing misrepresentation and a repeated failure to supervise are not interchangeable events. The applicable rule and facts determine the consequences. An AI policy should not promise immunity for every mistake, but neither should analysis assume a universal sanction without examining the governing standard.

### Verification should expose uncertainty instead of manufacturing agreement

Our research itself illustrates the value of independent source checking. Descrybe’s favorable treatment summary for **People v. Ring** did not reveal the full significance of **Birbrower**’s partial disapproval of Ring’s geographic analysis. A citation search returning no later cases for Noland did not mean later opinions were absent. These were reasons to inspect the actual opinions and use additional sources, not reasons to reject every result from the research service. [People v. Ring, 26 Cal.App.2d Supp. 768 (1937)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/hD/hDFKLEzZUqFmJIMbmS9UOC.pdf); [Birbrower, Montalbano, Condon & Frank v. Superior Court, 17 Cal.4th 119 (1998)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/pJ/pJLxbGW1Uw3hFAurfZGu2Ui.pdf).

For a firm using several models, agreement is useful evidence about consistency. It is not an independent guarantee of correctness when all models use the same index or inherit the same mistaken summary. The better use of multiple agents is to improve coverage, expose assumptions and identify where source review is most valuable. A real disagreement about an authority should lead to the passage, the procedural posture and the later history—not a vote among models.

### Discovery classifications, source verification and reporting are different tracks

The August deletion of the explicit reading words does not make an automated confirmation a substitute for personal verification. *LNU v. Blanche* likewise concerns professional responsibility for submitted authorities and the lawyer’s response when difficulties came to light. These cases should guide a real source-review process: existence, actual text, the proposition supported, procedural posture and relevant later treatment. They do not themselves require a lawyer to read every document in a separate bulk-classification task. [LNU v. Blanche, No. 24-4790 (9th Cir., June 3, 2026)](https://cdn.ca9.uscourts.gov/datastore/opinions/2026/06/03/24-4790.pdf).

Section 128.7(g) excludes the specified discovery materials and motions from that section. That does not eliminate discovery certifications, court orders, sanctions powers or the bill’s separate attorney duties. It is a reason to identify the correct rule, not a discovery-wide AI exemption.

Reporting is another distinct question. Section 6086.7(a)(3) requires court reporting of judicial sanctions subject to exceptions, including sanctions for failure to make discovery and monetary sanctions below $1,000; section 6068(o)(3) addresses the attorney’s own reporting obligation. A report is not itself a disciplinary finding. Thresholds, exceptions, notice and the reporting actor should not disappear into the shorthand that every AI error automatically goes to the Bar. [Business and Professions Code §§ 6086.7](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=BPC&sectionNum=6086.7.) and [6068](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=BPC&sectionNum=6068.).

<a id="v2-firm"></a>

## 10. Confidentiality, clients and the business model still need their own answers

Solving the delegation question would not solve every requirement for an AI-native law firm. A workflow can retain genuine lawyer judgment and still mishandle confidential information, mislead clients about who is advising them, or use an impermissible financial arrangement.

### Access controls belong in the service design

The researched bill’s confidentiality language is conditional. It does not simply prohibit every use of confidential information in AI. It addresses systems in which access is not restricted to the attorney and authorized persons under confidentiality obligations. Existing duties remain relevant, including Business and Professions Code section 6068(e) and Rule of Professional Conduct 1.6. [SB 574, proposed § 6068.1(a)(3)(A)](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=202520260SB574); [Business and Professions Code § 6068](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=BPC&sectionNum=6068.); [Rule 1.6](https://www.calbar.ca.gov/legal-professionals/rules/rules-professional-conduct/current-rules-professional-conduct/chapter-1-lawyer-client-relationship).

A useful implementation question is therefore: who can actually obtain the information, through which tools, and under which obligations? A model provider’s general promise is not the whole answer. The firm needs to understand the arrangements it is using, including the agents’ connections to email, document storage and other services.

Here is a concrete failure mode. An agent is properly allowed to read one client’s documents but is also connected to a general firm knowledge base. It places a summary containing client secrets into a location available to unrelated matters. The problem is not solved by showing that the initial model call used a private account. The entire information flow matters.

As a design response, a firm could limit each agent’s access to the matter and function it needs, constrain external transmission, and record where confidential information is sent. Different controls may be appropriate for a public-law research agent and an agent handling a client’s privileged communications. These are practical ways of implementing existing duties; they are not a claim that the statute mandates a particular software architecture.

### Clients retain decisions that belong to them

The lawyer’s retention of professional judgment does not mean the lawyer may take over the client’s decisions. Rule 1.2 allocates authority over the objectives of representation and settlement, while Rule 1.4 requires appropriate consultation and explanation. Rule 1.4(b) requires the lawyer to explain a matter sufficiently:

> “to permit the client to make informed decisions regarding the representation.”

An AI system should help the lawyer and client understand choices, not conceal who is choosing. [California Rules of Professional Conduct 1.2](https://www.calbar.ca.gov/legal-professionals/rules/rules-professional-conduct/current-rules-professional-conduct/chapter-1-lawyer-client-relationship) and [1.4(b)](https://www.calbar.ca.gov/sites/default/files/portals/0/documents/rules/Rule_1.4.pdf).

Suppose a settlement agent calculates a range that the firm considers commercially sensible. The calculation may be useful, but it does not itself authorize a settlement. The client’s authority, the lawyer’s advice, and the agent’s execution need to be distinguished. An instruction to automate negotiations cannot silently dispose of a decision that the client has not made or authorized.

Likewise, a client’s consent to AI use is not a blanket waiver of a statutory prohibition. It can matter to disclosure, confidentiality and the agreed method of representation. It cannot by itself turn prohibited practice into permitted practice. A firm should explain its use of agents accurately enough that the client understands who provides legal advice and how consequential decisions are made.

### Efficient production can support a different fee model

An AI-native firm may be able to produce some work much faster. That creates an opportunity to charge for a useful service through an appropriate flat fee or other lawful arrangement, rather than assuming that revenue must track the number of hours the old process consumed.

The existing rules still govern. Rule 1.5 prohibits illegal or unconscionable fees and identifies relevant factors. The State Bar’s 2026 guidance addresses actual time, alternative fee structures and the distinction between general overhead and costs specifically incurred for a matter. A lawyer should not bill an hourly client for fictional time that a person did not spend. Nor should the firm assume that every AI subscription can be passed through as a separate matter expense. [Rule 1.5](https://www.calbar.ca.gov/legal-professionals/rules/rules-professional-conduct/current-rules-professional-conduct/chapter-1-lawyer-client-relationship); [State Bar 2026 AI guidance, p. 8](https://www.calbar.ca.gov/sites/default/files/portals/0/documents/ethics/Generative-AI-Practical-Guidance.pdf).

The constructive opportunity is real: better preparation, reusable verified material and faster review may allow the firm to offer services at a price or scale that was previously impractical. The economics must include the cost of competent evaluation, exceptions and correction. This research does not establish a maximum number of agents per lawyer, a permissible number of clients per reviewer, or a guaranteed staffing ratio.

### A technology company and a law firm are not automatically the same legal structure

“AI-native” describes how a business works; it does not provide an exception from the rules governing who may own, control or receive fees from a law practice. California Rule 5.4 restricts nonlawyer fee sharing, certain business arrangements and interference with professional judgment, subject to specified exceptions. Its treatment of authorized practice organizations must be read in full. [California Rule of Professional Conduct 5.4](https://www.calbar.ca.gov/sites/default/files/portals/0/documents/rules/Rule_5.4.pdf).

A firm can buy technology and employ technical expertise. Whether a particular vendor arrangement instead transfers prohibited control or creates an impermissible financial arrangement depends on its substance. A label such as software fee does not answer that question by itself. Nor does a contract saying the lawyer is independent settle the question if the platform actually controls which legal advice can be given.

For a founder, there are therefore two separate design problems: building the agentic legal workflow and organizing the business that supplies it. A strong answer to one does not dispense with the other.

### Insurance is a policy question, not proof of legal permission

**Transamerica Insurance Co. v. Sayble** and **Tana v. Professionals Prototype I Insurance Co.** show why being a lawyer does not make every business dispute or fee claim a covered professional service. Sayble warned that:

> “the policies at bench do not provide such broad protection.”

Both decisions concern particular policy language and factual settings. Neither establishes that AI-related losses are generally covered or generally excluded. [Transamerica Insurance Co. v. Sayble, 193 Cal.App.3d 1562 (1987)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/kI/kIwk8qZAQk5IFkCtPXvh6VBq.pdf); [Tana v. Professionals Prototype I Insurance Co., 47 Cal.App.4th 1612 (1996)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/BF/BF1jjnXEukqElomllgRgsTRC.pdf).

A useful review would identify the insured persons and entities, the covered services, the definition of damages, exclusions, endorsements and reporting duties. Those questions can influence vendor contracts and risk allocation. They do not determine whether SB 574 permits the underlying assignment of work.

The public Lawyers’ Mutual Insurance Company specimen illustrates why policy review should go beyond asking whether AI is mentioned. Sections 1.25 and 2.1 concern professional services and negligence coverage; section 3.19 contains an unauthorized-practice exclusion. Other provisions concern regulatory proceedings, limited defense benefits and internet legal advice. Their application depends on the actual policy, endorsements, insured, claim and facts. This is not a conclusion that an AI-assisted mistake is generally uninsured—or that sanctions and discipline are the only exposure. [LMIC specimen, §§ 1.25, 2.1, 2.3, 3.11, 3.18–3.19](https://www.lawyersmutual.com/wp-content/uploads/2024/12/Universal-Policy-Specimen-Eff-4-1-23-002.pdf).

The useful questions for an insurer are concrete: which entity and people are insured; how the described workflow fits professional services; whether an exclusion or endorsement applies; what defense, notice and application obligations exist; and how vendor indemnity interacts with coverage. An insurer’s interest in AI governance may influence underwriting. It is neither a judicial interpretation nor a source of permission to perform a restricted task.

### Confidentiality includes the whole access chain and people beyond the client

Discovery collections contain opponents’ records, witnesses’ information, medical and financial details, and other material that the client does not own or cannot freely disclose. Client consent therefore does not answer every data question. Protective orders, privacy duties, third-party rights and the bill’s own restrictions can matter independently.

The firm should examine actual vendor and subprocessor access, support access, retention, training, integrations and onward transfers. A contract is relevant evidence, but a reassuring label does not establish the system’s behavior. Conversely, the bill should not be misdescribed as requiring a particular cloud provider, forbidding all useful confidential inputs or prescribing automatic redaction regardless of context. It permits an access-restricted arrangement on its terms; existing professional duties still apply.

A model trained or configured on firm precedents may better reflect the firm’s preferred approaches. That does not establish current legal accuracy, permission to reuse confidential information or fitness for a new matter. Private deployment addresses one set of risks. It does not itself resolve delegation, conflicts or quality. Routing the same process through a paralegal is likewise no automatic exception: genuine human assistance can improve the arrangement, but a nominal intermediary does not change who actually exercises control.

### Authorization cannot be inferred from a useful result

*Blanton v. Womancare, Inc.* distinguishes a lawyer’s ordinary authority in conducting litigation from authority to bind a client to an arbitration arrangement surrendering substantial rights. It is a concrete reminder that the lawyer’s own control is only part of the chain: client decisions must remain with the client where law requires. [Blanton v. Womancare, Inc., 38 Cal.3d 396, 403–408 (1985)](https://law.justia.com/cases/california/supreme-court/3d/38/396.html).

Civil Code section 3513 also limits private waiver of laws established for a public reason. Consent may authorize an otherwise permissible method or disclosure; it cannot simply waive the profession’s regulatory framework. Agency provisions, including section 2349’s specified circumstances for delegating authority, are useful background but must be read with professional restrictions and the client’s instructions. [Civil Code §§ 3513](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=CIV&sectionNum=3513.) and [2349](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=CIV&sectionNum=2349.).

### Professional duties have distinct enforcement paths

SB 574 also need not contain a new bespoke penalty for every duty to have disciplinary significance. Business and Professions Code section 6103 addresses violation of an attorney’s duties and other specified misconduct. Filing sanctions, State Bar discipline, malpractice and vendor claims are different paths, with different elements, procedures and remedies. A possible enforcement route is not proof that any particular error satisfies it. [Business and Professions Code § 6103](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=BPC&sectionNum=6103.).

### Interstate competition is real as a question, conditional as a conclusion

Lawyers may compete in the same litigation or transaction while operating under different licenses and professional regimes. A uniquely restrictive interpretation could affect cost and available methods. But California Rule 8.5’s disciplinary authority and choice-of-law provisions, tribunal rules, federal admission and procedure, and the location and predominant effect of conduct need to be considered. State procedural requirements do not automatically transfer unchanged to federal court, and federal practice is not a general escape from licensure duties. [California Rule 8.5](https://www.calbar.ca.gov/legal-professionals/rules/rules-professional-conduct/current-rules-professional-conduct/chapter-8-maintaining-integrity-profession).

The responsible competitive argument therefore compares actual workflows and applicable rules. It does not assume all other states impose no constraints, or that incorporating elsewhere removes California obligations. Evidence of different review burdens, fees, turnaround times and available services would make the policy case much stronger than a prediction of inevitable statewide disadvantage.

<a id="v2-arbitration"></a>

## 11. Arbitrators face a separate and potentially broader restriction

A lawyer acting as an advocate and a person acting as an arbitrator perform different roles. SB 574 addresses them separately. The arbitrator provision reaches every covered component of the decisionmaking process, while another paragraph addresses reliance on AI-generated information outside the record. It would be a mistake to assume that the attorney-assistance interpretation transfers unchanged to adjudication. [SB 574, proposed Code of Civil Procedure § 1282.1](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=202520260SB574).

Consider an arbitrator using AI to compare the parties’ chronologies. That might begin as information organization. If the system decides which witness is credible, chooses the controlling fact or supplies the liability analysis that the arbitrator adopts without independent evaluation, the task is closer to the decisionmaking the proposal singles out. A system that edits punctuation in reasons the arbitrator has already settled presents a different question. The actual function matters more than the broad label summarization or drafting.

The historical California cases do not eliminate that distinction. In **Sapp v. Barenfeld**, the Supreme Court allowed technical assistance while emphasizing that the award must result from the arbitrators’ own judgment. The relevant condition was:

> “provided that the award is the result of their own judgment after obtaining such information”

**Griffith Co. v. San Diego College for Women** likewise considered whether an arbitrator had retained judgment when seeking advice. These cases support the distinction between obtaining assistance and surrendering the decision. Their historical discussion of consultation must be read with current notice and communication rules. [Sapp v. Barenfeld, 34 Cal.2d 515 (1949)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/RK/RK5JqO59taBClPMSdqMQyGFy.pdf); [Griffith Co. v. San Diego College for Women, 45 Cal.2d 501 (1955)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/eM/eMn94RZFDO0iRiOLcOjqFIY.pdf).

Existing Code of Civil Procedure section 1282(c)(2) addresses delegation among neutral arbitrators and reserves award-making and correction, subject to its opening agreement qualification. Current section 1282.2(g) and Neutral Arbitrator Ethics Standard 14 address consultation and the parties’ opportunity to respond. The proposed AI provision should be compared with these rules, not described as merely repeating them. [Code of Civil Procedure §§ 1282](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=CCP&sectionNum=1282.) and [1282.2](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=CCP&sectionNum=1282.2.); [Ethics Standard 14](https://courts.ca.gov/cms/rules/index/ethics/ethics14).

Disclosure of outside-record information answers only part of the problem. Giving the parties a chance to comment may address the separate information provision; it does not necessarily cure a prohibited transfer of the arbitrator’s decisionmaking. The provisions need to be considered independently.

Judicial analogies also require care. In **Anderson v. City of Bessemer City**, the United States Supreme Court explained that:

> “even when the trial judge adopts proposed findings verbatim, the findings are those of the court”

That does not mean every signature proves independent judgment. Anderson involved a particular judicial process. In **Reaves v. Superior Court**, California’s Court of Appeal rejected an arrangement in which the prosecutor investigated writ petitions and drafted orders, despite the judge’s assertion of independent review. The institutional role of the preparer and the process by which the decision is made can matter as much as the final document. [Anderson v. City of Bessemer City, 470 U.S. 564, 572 (1985)](https://supreme.justia.com/cases/federal/us/470/564/); [Reaves v. Superior Court, 22 Cal.App.3d 587, 590–597 (1971)](https://static.case.law/cal-app-3d/22/html/0587-01.html).

Even an improper AI use does not automatically answer whether a court must vacate an award. Vacatur—setting the award aside—is governed by specific grounds and their requirements. **Moncharsh** limits ordinary judicial review of arbitral merits, while statutes and decisions address misconduct, excess of powers, disclosure and other grounds. Federal Arbitration Act preemption can add another issue. **Concepcion**, **Kindred**, **Viking River** and **Adolph** supply relevant principles; none is a direct ruling on this proposed AI prohibition. The agreement, conduct, alleged harm and requested remedy would all matter in a concrete dispute. [Moncharsh v. Heily & Blase, 3 Cal.4th 1 (1992)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/5x/5xJbWXHvcYgnhMcvVDhS5Ou2.pdf); [Code of Civil Procedure § 1286.2](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=CCP&sectionNum=1286.2.); [9 U.S.C. § 10](https://www.law.cornell.edu/uscode/text/9/10).

### Party agreement, institutional products and legislative choices

A provision allowing parties to agree to particular procedures should not be conflated with one that prohibits transferring decisionmaking to AI. Existing section 1282’s agreement qualification does not automatically qualify the new section 1282.1. Consent and disclosure remain important, but neither is a universal cure for a separate substantive prohibition.

The FAA analysis also has more than one side. Alongside the preemption cases, *Volt Information Sciences, Inc. v. Board of Trustees*, 489 U.S. 468 (1989), recognizes the relevance of enforcing agreed arbitration procedures. The concrete question would concern this agreement, the applicable state rule and whether it conflicts with federal law. None of the researched cases decides SB 574’s AI provision. The source guide retains both lines of authority.

AAA’s positions should not be reduced to a mediation-only objection. The August 31 concurrence analysis quotes continuing requests concerning AI as well as concerns about mediation confidentiality. Its described human-supervised AI offering is a useful example to examine, not evidence that the product’s controls satisfy every legal requirement. Accuracy, transparency, privacy, accountability and adaptability are useful evaluation dimensions. Claimed savings, training volumes and demand would need separate substantiation. JAMS rules for disputes involving AI are likewise not permission for AI to decide an award. August 31 concurrence analysis.

The section 6173 changes concern a voluntary ADR-provider certification and complaint program. The information-production provisions preserve specified privilege and work-product protections tied to holder consent, including a sole-holder complainant rule; the relevant subparagraph is limited to mediation involving a self-represented party. Mediation confidentiality is a separate issue from those privileges. Certification tiers, complaint procedures, restricted disclosure, limited public reporting and funding also matter. Describing the measure as abolishing all mediation privilege or creating a universal AI-product license would obscure its actual scope. [SB 574, section 2 and section 6 findings](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=202520260SB574).

<a id="v2-comparisons"></a>

## 12. Other findings that could inform products, policy or further research

### Software can be regulated through explicit permission rather than an argument about labels

North Carolina and Texas provide useful examples of express statutory treatment of document software and publications. Their provisions have conditions and operate within their own jurisdictions. They do not authorize a California service simply because it resembles a permitted product elsewhere. [North Carolina General Statutes § 84-2.2](https://www.ncleg.gov/EnactedLegislation/Statutes/HTML/BySection/Chapter_84/GS_84-2.2.html); [Texas Government Code § 81.101(c)](https://statutes.capitol.texas.gov/Docs/GV/htm/GV.81.htm#81.101).

That comparison is useful for policy design. A Legislature can identify a class of permitted services, impose protective conditions and leave responsibility rules intact. It need not rely entirely on courts to determine whether a product falls outside legal practice in the first place.

The LegalZoom litigation also shows why procedural details matter. **Janson v. LegalZoom.com, Inc.** involved particular summary-judgment motions under Missouri law. It was not a final nationwide ruling that every LegalZoom product was unlawful. The 2015 North Carolina consent judgment expressly disclaimed a violation finding or admission. **Parsons Technology** involved a judgment vacated after statutory change. These are useful parts of the history, but they cannot be reduced to a single general software rule. [Janson v. LegalZoom.com, Inc., 802 F.Supp.2d 1053 (W.D. Mo. 2011)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/65/65HL3Mco347NvmIFGOftWSq.pdf); [LegalZoom.com, Inc. v. North Carolina State Bar, 2015 NCBC 96](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/pT/pTyZrYbVHeWFWVAq9sNOSgzk.pdf); [Unauthorized Practice of Law Committee v. Parsons Technology, Inc., 179 F.3d 956 (5th Cir. 1999)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/hk/hkPknlPw9BjLbYOxblSODces.pdf).

### A machine’s ability to perform a task does not by itself reclassify the task

**Lola v. Skadden, Arps, Slate, Meagher & Flom LLP** contains language that is particularly attractive to arguments for automation:

> “tasks that could otherwise be performed entirely by a machine cannot be said to engage in the practice of law”

The Second Circuit was considering allegations about mechanical document review, North Carolina law and the Fair Labor Standards Act’s professional exemption at the dismissal stage. It was not declaring that any activity a future AI can perform is necessarily outside California legal practice. [Lola v. Skadden, Arps, Slate, Meagher & Flom LLP, 620 F.App’x 37 (2d Cir., July 23, 2015), No. 14-3845](https://law.justia.com/cases/federal/appellate-courts/ca2/14-3845/14-3845-2015-07-23.html).

The useful idea is narrower: a task that requires no legal judgment may differ from work involving the application of law. That is why literal comparison, copying and arithmetic deserve separate treatment. It is not a dependable argument that sophisticated models make licensing law obsolete merely by becoming capable.

### A supervised medical service is not automatically a legal-AI precedent

Medical regulation offers instructive comparisons because it distinguishes licensed roles, authorized assistance and retained responsibility. **Magit v. Board of Medical Examiners** held that immediate physician supervision did not excuse unauthorized medical acts. **Lopez v. Ledesma**, by contrast, concerned services by a licensed physician assistant within an authorized relationship. Supervision, competence and formal permission were not interchangeable concepts. [Magit v. Board of Medical Examiners, 57 Cal.2d 74 (1961)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/7r/7r72t8vHflRuXsBEckUcSlk.pdf); Lopez v. Ledesma, 12 Cal.5th 848 (2022).

Health and Safety Code section 1339.75 provides a more specific drafting example. It creates disclosure-related requirements for certain AI-generated patient communications. Subsection (b) makes those requirements inapplicable when the communication is:

> “read and reviewed by a human licensed or certified health care provider”

The exception concerns the specified disclaimer and human-contact requirements. It does not generally authorize unlicensed medical practice. Its value here is to show how a Legislature can expressly state what a qualifying review changes. [Health and Safety Code § 1339.75(a)–(b)](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=HSC&sectionNum=1339.75.).

For legal AI, the analogous legislative question would be precise: which substantive tasks may the system prepare, what must the attorney review, which decisions must remain personal, and what legal consequence follows from satisfying those conditions? That is a more useful drafting project than a generic statement that a human remains responsible.

### Another professional-delegation drafting comparison

Business and Professions Code section 2570.28(n), concerning occupational therapy, ties a prohibited delegation to services requiring the licensee’s knowledge, skills, abilities or judgment. It shows a possible way to describe a reserved professional function more expressly. It is not an interpretation of SB 574 or permission for every unlicensed intellectual contribution. A useful legal-AI provision would likewise explain both what assistance is allowed and which professional role must remain with the lawyer. [Official section 2570.28(n)](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=BPC&sectionNum=2570.28.).

### Constitutional arguments remain important, but they are not a present blanket exemption

Legal advice involves speech, and restrictions on it can raise First Amendment questions. **Upsolve, Inc. v. James** and **Chiles v. Salazar** matter to that discussion, but their procedural history and subject matter cannot be skipped.

The Second Circuit vacated the earlier Upsolve injunction in 2025; subsequent remand and docket developments were checked in the research. Chiles, decided by the United States Supreme Court in March 2026, concerns viewpoint restrictions on licensed counseling speech. Neither decision adjudicates SB 574 or automatically invalidates California’s unauthorized-practice rules. A constructive constitutional analysis would identify the particular service, speech, restriction and justification rather than assume that all professional regulation survives or fails together. [Upsolve, Inc. v. James, 155 F.4th 133 (2d Cir. 2025)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/VU/VUxC1KUZVBgc5UzyuAq569I.pdf); [Chiles v. Salazar, 607 U.S. ___, 146 S.Ct. 1010 (2026), No. 24-539](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/op/ophiVseMxiF49TaDypMvTwkI.pdf).

### There is a concrete opportunity to improve the bill’s clarity

If the legislative objective is to permit serious AI assistance while preserving the lawyer’s professional role, the text could say more directly what remains with the lawyer and what assistance is permitted. A useful clarification could address substantive research and drafting explicitly, require informed professional evaluation before consequential use, and preserve duties of confidentiality, candor and competence. Whether that should become a legally defined safe harbor is a policy choice; the existing proposal should not be described as already containing one.

A separate technical drafting issue arose in section 128.7. The proposed restructuring moves the provision concerning warranted legal contentions, while a cross-reference governing monetary sanctions against represented parties continues to point to the citation-verification subdivision. That appears to change what the reference reaches. The research does not establish whether the change was intended. It is a focused question for legislative counsel, not a reason to dismiss the whole bill. [SB 574, proposed Code of Civil Procedure § 128.7(b) and (d)(1)](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=202520260SB574).

Finally, the bill also addresses Judicial Council reconsideration of the judicial AI standard and changes to a voluntary alternative-dispute-resolution certification program. Those are distinct from the attorney prohibition. They may matter to organizations offering arbitration, mediation or related services, but they should not be read as a universal new license requirement for every legal AI product. The annotated statutory guide identifies the relevant provisions for readers whose plans include those activities.

### Disclosure can survive human review: the limited AB 1651 comparison

AB 1651 was signed August 22, 2026 as chapter 116. Its new Business and Professions Code section 6060.15 addresses disclosure of AI-generated bar-examination and study-guide content developed by or under the State Bar’s explicit direction. Its requirements apply even when the content receives human review; the provision becomes operative January 1, 2028, with specified timing and placement of disclosures. [Authenticated chapter text](https://leginfo.legislature.ca.gov/faces/billPdf.xhtml?bill_id=202520260AB1651&version=20250AB165195CHP).

The comparison is narrow but useful. Human review and disclosure are different policy tools, so review need not make disclosure unnecessary. It does not establish that the State Bar currently uses AI for all examination content or that SB 574 authorizes every reviewed AI workflow.

### Claims of superior performance need evidence

The FTC’s DoNotPay order concerns substantiation of claims about professional-service capabilities. It is not a ruling defining California legal practice. Its relevance here is straightforward: the future-facing case for broader reliance should be built on competent evidence of performance for the claimed function, not on advertising that a system replaces a lawyer. [FTC final order, DoNotPay](https://www.ftc.gov/system/files/ftc_gov/pdf/2323042_donotpay_decision_and_order_0.pdf).

<a id="v2-policy"></a>

## 13. What the Governor, COPRAC and Legislature could usefully do

### The public-interest case is uncertainty about permitted methods of competent practice

The best argument is that California should not enact an undefined professional-method prohibition capable of obstructing responsible practices that its courts and ethics framework otherwise accept. A law aimed at invented authorities and irresponsible automation should say which conduct it prohibits with enough clarity that competent lawyers can continue using reliable systems.

eDiscovery makes that argument concrete. But the harm is broader: portfolio contract review, regulatory mapping, due diligence, large-record investigation, legal research, and preparation of individualized documents can all involve substantive machine analysis within a professional service. Whether a task is “legal” is not a sufficient answer to whether its performance through a controlled system should be forbidden.

The economic argument should be stated in terms of **the people who need legal services**. If a sound workflow becomes more expensive or unavailable, the costs may fall most heavily on small businesses, individuals, smaller firms, public-interest organizations, and litigants without the resources to substitute large review teams. These are plausible consequences of the mechanism, not quantified findings from a market-impact study. A veto submission would be stronger with declarations and measured examples.

Competition is relevant in the same way. A California-only constraint could disadvantage lawyers and clients when counterparts use more capable systems. But it would be inaccurate to say that every out-of-state lawyer is free of California constraints or that changing the lawyer’s address resolves them. Forum rules, licensing, and disciplinary choice-of-law rules complicate that comparison. The concern is a potential disparity in useful methods, not a universal geographic exemption. [California Rule 8.5](https://www.calbar.ca.gov/legal-professionals/rules/rules-professional-conduct/current-rules-professional-conduct/chapter-8-maintaining-integrity-profession).

The strongest institutional argument is that the Supreme Court and State Bar are already working on competent use of increasingly autonomous systems. Legislation can complement that work, but a poorly specified task prohibition can confuse it. This is an argument for a better division of work and clearer text, not a claim that the Legislature has no authority over attorneys.

### Proposed veto message

*The following is proposed language, not a description of an actual gubernatorial decision.*

> I am returning Senate Bill 574 without my signature.
>
> I support the bill’s objective of protecting clients and courts from fabricated legal authorities, misuse of confidential information, and the surrender of professional responsibility to automated systems. Attorneys must remain accountable for the legal services they provide, including services produced with artificial intelligence.
>
> However, the bill does not adequately distinguish prohibited delegation from the competent use of generative artificial intelligence to perform substantive work within an attorney-directed process. That distinction is essential to modern legal practice.
>
> Electronic discovery illustrates the problem. Courts already address document-review methods in which technology makes classifications across large collections while attorneys direct the review, test its reliability, investigate exceptions, and remain responsible for the production. Generative artificial intelligence is now being used within such workflows. An interpretation requiring attorneys to repeat every substantive machine determination could undermine the cost and quality benefits of those methods without improving protection for clients or courts.
>
> Similar uncertainty could affect contract review, investigations, legal research, and other services. The burden would not fall only on law firms. It could increase the cost of obtaining representation and resolving disputes, especially for people and organizations unable to replace effective technology with larger teams.
>
> The California Supreme Court has requested updated guidance addressing generative and agentic artificial intelligence. I encourage the author, the State Bar, the judiciary, and affected stakeholders to develop legislation that expressly preserves competent, validated use of these tools while prohibiting abdication of professional responsibility and retaining appropriate requirements for confidentiality, verification, and personal acts required by law.
>
> California should regulate the quality and accountability of legal services with sufficient precision to protect the public and permit beneficial innovation. A clarified measure can achieve those objectives together.

### The case for signing with clarification, and the choice that remains

Supporters can reasonably answer that the assistance language already preserves responsible use, that professional terms often acquire detail through interpretation, and that rejecting the entire bill loses useful protections. Those are substantial points. The Governor generally cannot delete this nonappropriation provision and sign the remainder; the constitutional item-veto power concerns appropriations. [California Constitution, article IV, § 10(e)](https://leginfo.legislature.ca.gov/faces/codes_displayText.xhtml?lawCode=CONS&division=&title=&part=&chapter=&article=IV).

The recommended policy position is conditional. **We would prefer a sufficiently authoritative clarification that preserves beneficial use. If the only reassurance is a nonbinding statement that reasonable people will probably read the prohibition narrowly, a veto request is defensible and worth making.** The initial memo concluded that the AI provisions do not warrant a veto. We do not treat them as categorically insufficient grounds for one. Nor does the evidence compel a veto of the whole bill without weighing its other provisions.

The other strongest critique is the possible mismatch between means and problem. Verification requirements directly target false citations; data restrictions directly target confidentiality failures. A broad, undefined restriction on delegating legal practice reaches well beyond those failures. Its proponents should explain the incremental protection that requires that broader reach and how ordinary competent workflows remain available.

### Other policy costs and the value of precise drafting

The conditional veto case also includes disclosure administration, mismatched summaries and cross-references, the distinct mediation-confidentiality dispute and possible FAA consequences. These are separate reasons to examine the whole bill; none proves inevitable litigation, invalidity or economic loss. A broad approach to AI does not require agreeing with every other provision, and concern about an ADR provision need not be presented as opposition to AI safeguards.

There is a relevant gubernatorial precedent for asking that AI regulation track actual deployment risks. The September 29, 2024 SB1047 veto message questioned thresholds tied to model size and cost and called for more attention to context and empirical evidence. It can support the form of a request for calibrated regulation. It is not a prediction that the Governor will or should treat this attorney bill identically. [SB1047 veto message, pp. 2–3](https://www.gov.ca.gov/wp-content/uploads/2024/09/SB-1047-Veto-Message.pdf).

### If the Governor signs: a statement that supports a sound interpretation

#### Its purpose and legal limits

A signing statement can articulate the Governor’s understanding, identify a problem, and request coordinated clarification. It cannot amend the statute, bind the Supreme Court’s interpretation, or create a defense simply by declaring certain conduct lawful. California decisions caution against treating a Governor’s signing statement as reliable evidence of the Legislature’s intent. [*Coastside Fishing Club v. California Resources Agency*, 158 Cal.App.4th 1183, 1196 fn. 7 (2008)](https://app.midpage.ai/document/coastside-fishing-club-v-california-2244831).

The best statement would therefore do three things: affirm broad responsible use in plain language; explain why substantive machine work can coexist with attorney responsibility; and request concrete clarification while respecting the judiciary’s authority. It should not merely reassure readers that “supervision is required.” That is the ambiguous phrase needing explanation.

#### Proposed signing statement

*This is proposed language for consideration if the Governor signs the bill.*

> I am signing Senate Bill 574 to reinforce the responsibility of attorneys and arbitrators for the professional services and decisions entrusted to them, and to protect courts and clients from fabricated authorities and misuse of confidential information.
>
> California should also lead in the responsible use of artificial intelligence to improve legal services. Generative artificial intelligence can assist with substantive legal analysis, document review, research, drafting, and increasingly capable workflows. Its benefits should reach individuals, small businesses, public-interest organizations, and others for whom the cost of legal services is a barrier to justice.
>
> I understand the attorney provisions of this bill, read together, to preserve meaningful use of these technologies while preventing an attorney from surrendering the professional responsibilities that remain the attorney’s own. The prohibition on delegation should not be understood as a prohibition on every use of generative artificial intelligence to perform a task involving legal knowledge or analysis.
>
> Electronic discovery illustrates the distinction. A lawyer may remain professionally engaged by defining the legal criteria, selecting and testing a review process, evaluating its performance, directing appropriate handling of exceptions, and taking responsibility for the resulting production. Individual repetition of every machine classification is not necessarily the measure of meaningful professional control. The appropriate method of oversight depends on the task, its consequences, the evidence of reliability, and applicable law and court orders.
>
> The same principle should inform consideration of other legal services as these technologies develop. Evidence that a system improves accuracy, speed, accessibility, or cost should inform professional standards. Neither a product’s label nor the fact of automation alone should determine whether its use is competent. Nor should a favorable performance claim excuse the abandonment of professional judgment, client authority, confidentiality, candor, or an act that the law specifically requires an attorney to perform personally.
>
> I respectfully request that the State Bar, in consultation with the California Supreme Court as appropriate, provide timely guidance addressing the distinction between prohibited delegation and permitted assistance, including validated bulk review and bounded agentic workflows. I encourage the Judicial Council to address related procedural questions within its authority. The attorney and arbitrator provisions use different language and should receive distinct consideration.
>
> I also ask the author and other interested legislators to work with the judiciary, practitioners, technical experts, and representatives of legal-services users on clarifying legislation if the text creates uncertainty that guidance cannot adequately resolve. Clear standards should preserve accountability while allowing California lawyers and their clients to benefit from demonstrably effective tools today and from further improvements in the future.

The most valuable sentence is the one rejecting a ban on every task involving legal knowledge. The next most valuable is the process example. Those passages address the ambiguity directly. The final paragraph recognizes that legislation may still be necessary. Without that paragraph, the statement risks promising a certainty it cannot deliver.

### Three complementary COPRAC clarification routes

#### Option 1: An immediate ethics alert explaining bulk review through a worked example

**Purpose:** give practitioners a usable answer promptly, without waiting for a comprehensive opinion on every autonomous legal service.

The alert should explain that substantive classifications may be performed by a system within a lawyer-directed process, and that the sufficiency of supervision cannot be determined by counting attorney clicks. It should separately identify requirements for court papers, client commitments, confidentiality, and particular court orders.

Its first worked example should use responsiveness review because the evidence is strongest there. It can then contrast a disputed privilege issue, a novel legal conclusion, and an autonomous court filing. The examples should show why different functions may require different forms of review. Avoid making “high volume” itself an exception; a million highly consequential errors remain highly consequential.

**Proposed alert language:**

> Competent use of generative artificial intelligence may include reliance on substantive analysis and classifications produced through a process that a lawyer has appropriately directed and evaluated. The fact that an output involves applying legal criteria does not, by itself, establish that the lawyer has surrendered professional responsibility.
>
> In electronic discovery, for example, a lawyer may define the criteria for responsiveness, assess the suitability of a review method, test its performance on appropriate samples, investigate material errors and exceptions, and remain engaged in decisions concerning production. Depending on the circumstances, competent review may occur through evaluation of the process and its results rather than separate lawyer examination of every classified document.
>
> The lawyer must have a reasonable basis for reliance on the process in the particular matter. Relevant considerations include the applicable law and orders, the nature and consequences of error, the quality and representativeness of testing, the treatment of documents outside the tested conditions, and the ability to correct material failures. Vendor assurances, a nominal approval, or a favorable average score alone do not establish that basis.
>
> This guidance does not dispense with any personal verification, signature, client authorization, confidentiality, or other requirement imposed by law. Nor does it authorize an independently operating system to assume the attorney’s role in the representation. The distinction is between a lawyer’s competent use of a process and a lawyer’s surrender of the professional duties governing that process.

**Legal effect:** practical and persuasive guidance, not a statutory exemption. COPRAC’s existing formal opinions themselves disclaim binding effect. The alert should identify the interpretation of § 6068.1 on which it rests and candidly state any unresolved question.

**Why start here:** it answers the actual workflow question, addresses the current question about the level of professional judgment, and provides something useful to lawyers who must make operational choices now.

#### Option 2: A formal opinion on exercising professional judgment through validated systems

**Purpose:** provide the reasoned legal bridge between existing delegation cases, technology competence, the new statutory language, and broad AI use across practice areas.

The opinion should consider several fact patterns rather than announce one slogan. At minimum: bulk discovery classification; a portfolio of contract summaries; negotiation within lawyer-and-client-approved limits; a system supplying new individualized advice directly to clients; and the release of a court submission. It should identify what the lawyer actually decides in each, what the system performs, and when reliance becomes abdication.

The legal analysis should integrate *Baron*, *Crawford*, *Reynoso* with its reservation, the statutory assistance provision, COPRAC 2015-193, and current competence and communication rules. ABA Opinion 512 is especially useful persuasive material. Paralegal law supplies context, but § 6450 cannot simply be declared an AI safe harbor. [Business and Professions Code § 6450](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=BPC&sectionNum=6450.).

**Proposed core conclusion:**

> A lawyer’s independent professional judgment need not consist of personally performing or repeating every analytical operation used in the representation. Depending on the function, it may include selecting a legally appropriate method, determining the criteria governing that method, evaluating reliable evidence of its performance, deciding the conditions under which its results may be used, and responding to exceptions and material changes.
>
> Generative artificial intelligence may perform substantial legal analysis within that arrangement. Its use remains subject to the lawyer’s duties to the client and tribunal, applicable statutory limits, and any requirement for an act to be performed personally. A lawyer cannot establish compliance solely by naming a responsible attorney, approving general software use, or accepting results without an adequate basis for reliance.
>
> Whether the lawyer has retained the professional role is assessed from the actual representation and operating process. Relevant facts include who determines objectives and legal positions, who has authority to change the method or stop an unauthorized action, what evidence supports reliance, how unusual or disputed matters are handled, and whether the lawyer remains sufficiently informed to discharge the responsibilities undertaken.
>
> Evidence of improved performance may justify reducing redundant review or increasing bounded autonomy. It does not transfer the lawyer’s professional duties to the system or displace client decisions and personal acts reserved by law. Conversely, the mere absence of separate human review of each item does not establish an impermissible transfer of those duties.

The final opinion should explain the important intermediate case: **a system may make genuine inferential choices without having authority to decide the representation’s objectives or to release every consequence of those choices.** That is closer to current technology than the assertion that a sufficiently detailed instruction eliminates all machine judgment.

**Legal effect:** a formal opinion can offer substantial, carefully reasoned guidance, but remains advisory. It should not promise that following a technical checklist defeats every disciplinary, malpractice, confidentiality, or discovery claim. It should specify which conclusions follow from existing rules and which depend on the best construction of SB 574.

**Why this matters beyond eDiscovery:** it supplies a general principle for increasing model capability without making every new product wait for a separate opinion. The principle is applied through facts, quality evidence, and actual authority.

#### Option 3: A Supreme Court-facing principle, supported by guidance that evolves

**Purpose:** obtain the most durable institutional clarification available through the professional-rules process while keeping technical requirements adaptable.

The principle could be placed in an appropriate competence or supervisory comment, or proposed as rule text if the Court concludes that a substantive rule is needed. COPRAC and the State Bar can recommend; they should not imply that they unilaterally determine the Court’s rules. Existing Business and Professions Code § 6077 provides for rules approved by the Supreme Court. [§ 6077](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=BPC&sectionNum=6077.).

**Proposed comment for consideration:**

> A lawyer may use technological systems, including generative and agentic artificial intelligence, to perform substantive work in a representation, provided the lawyer fulfills the duties imposed by these rules and applicable law. The appropriate nature and extent of direction, supervision, review, and verification depend on the task, the consequences of error, the system’s demonstrated capabilities and limitations, and the surrounding safeguards. Where appropriate, those duties may be fulfilled through a validated process without the lawyer personally repeating every operation or reviewing every item. This does not diminish any duty to exercise independent professional judgment, preserve decisions reserved to the client, or personally perform an act required by law.

A companion guidance document should show how this principle operates. It should address testing before use, meaningful validation after changes, scope of system authority, source checking, foreseeable failure modes, and correction. It should also address **the benefits of greater autonomy**: reduction in error, timelier service, lower cost, broader access, and less unnecessary review.

Do not embed a fixed percentage of human review, a particular model architecture, an unconditional ban on agents, or the premise that models can never outperform lawyers. Nor should guidance automatically require more human labor whenever autonomy increases. Increased autonomy may require stronger assurance; that assurance can come from better evaluations, constrained permissions, independent evidence, or effective containment as well as human review.

Keep the technical guidance under periodic and event-triggered review. A material model change, new legal function, evidence of improved capability, or evidence of previously unseen failure should be a reason to reconsider the permitted workflow. The review should be able to **expand** appropriate autonomy as well as restrict it.

**Legal effect:** Court-approved rules and comments have a different institutional position from a standalone committee alert, but comments do not silently amend statutes or create new duties beyond the governing rules. Rule 1.0(c) identifies comments as interpretive guidance rather than a basis for discipline. If the desired interpretation is incompatible with the enacted text, neither this comment nor an ethics opinion can fix that incompatibility by declaration. Legislative clarification should accompany the proposal where necessary. [California Rule 1.0(c) and comment [4]](https://www.calbar.ca.gov/legal-professionals/rules/rules-professional-conduct/current-rules-professional-conduct/purpose-and-function-rules-professional-conduct-rule-10).

#### A targeted statutory clarification if guidance is insufficient

Here is a candidate addition directed to the attorney provision, for legislative drafting and review. It is a policy proposal, not existing law:

> For purposes of paragraph (2), an attorney does not delegate the practice of law solely by using generative artificial intelligence to perform legal research, analysis, drafting, classification, or other substantive work within a process that the attorney competently directs, evaluates, and controls. Depending on the nature and consequences of the work, reasonable direction and evaluation may include validated testing, sampling, and ongoing monitoring without individual attorney review of every output. The attorney shall remain responsible for the representation, preserve decisions reserved to the client, and personally perform any act required by law to be performed by an attorney. Nothing in this paragraph authorizes an attorney to surrender independent professional judgment, disregard known material deficiencies, or permit the system to undertake the representation without the attorney’s meaningful professional involvement.

The word **solely** matters: use of a substantive tool is not itself the prohibited act, but the surrounding facts can still establish impermissible surrender of responsibility. This proposal also avoids declaring that a performance score is automatic immunity. It would need coordination with the rest of § 6068.1 and does not amend the different arbitrator prohibition.

The preferred sequence is to begin with the alert and formal-opinion process, use them to inform the Court-facing proposal, and pursue statutory language if a material ambiguity remains. Those steps reinforce one another; they are not three incompatible camps.

### The pending rule comments are an immediate opportunity

The State Bar’s current proposal must be distinguished from its earlier draft. The June 2026 second-round competence comment would require professional judgment throughout AI use, including inputs and outputs, with additional attention to sources used in legal proceedings. It does not use the first draft’s formulation about every output. The public-comment page records that the Board authorized the second round on June 12 and comments closed August 6. These are proposed comments, not a Court-adopted interpretation of SB 574. The May practical guidance also remains relevant; a proposal should openly reconcile its review language with a defensible account of validated bulk work. [Current proposal and procedural history](https://www.calbar.ca.gov/public-comment/proposed-amendments-rules-professional-conduct-related-artificial-intelligence); [June clean and redline text, clean Rule 1.1 on p. 1](https://www.calbar.ca.gov/sites/default/files/2026-06/Proposed-Amended-Rules-of-Professional-Conduct-1.1-1.4-1.6-3.3-5.1-and-5.3-clean-and-redline.pdf).

The useful question is precise: does professional judgment over a validated method and its results satisfy that principle for an appropriate bulk task, or must a lawyer separately adopt every substantive classification? The revised wording improves the starting point, but leaves that operational question worth answering.

One possible addition to the competence comment, offered for discussion, is:

> The nature and extent of that judgment depend on the task, the consequences of error and the system’s demonstrated reliability; where appropriate, a lawyer may exercise it at the level of the method, population or matter through design, validation, sampling and supervision, without diminishing any duty to verify cited authorities, to preserve decisions reserved to the client, or to perform personally an act the law requires an attorney to perform.

That language makes a positive claim about professional competence. It should be accompanied by a worked example and a reasoned explanation of its relationship to the statute. It does not require the committee to approve every autonomous service or to predict that a model will always outperform a person.

### Match the institution to the requested change

COPRAC can explain professional duties and recommend changes through the State Bar’s process. It does not independently amend the statute or dictate the Supreme Court’s rules. California’s regulation of lawyers also does not belong exclusively to one branch. *In re Attorney Discipline System* describes the judiciary’s inherent responsibility while recognizing a substantial legislative role. That supports coordination rather than an argument that the Legislature necessarily lacked power to act. [In re Attorney Discipline System, 19 Cal.4th 582, 600–603 (1998)](https://law.justia.com/cases/california/supreme-court/4th/19/582.html).

A productive working-group contribution would present the current text, the June comment and the *Schulte* facts together; identify the precise ambiguity; offer a sentence and an example; and ask what further source or revision would make the proposal acceptable. A short issue note can carry the details. That is more useful than asking colleagues to endorse a sweeping prediction about the future of all legal work.

The same care applies to confidentiality. The June proposed Rule 1.6 comment treats potential training use as one factor in assessing a substantial risk of exposure. It is not an automatic rule that any training makes a use prohibited. SB 574 instead specifies restrictions on access. Both must be explained alongside existing duties, contracts, actual practices and nonclient information. [June proposal, clean Rule 1.6 on p. 5](https://www.calbar.ca.gov/sites/default/files/2026-06/Proposed-Amended-Rules-of-Professional-Conduct-1.1-1.4-1.6-3.3-5.1-and-5.3-clean-and-redline.pdf).

Rule 10.430 supplies a related disclosure comparison, but for a different audience. It requires courts that permit generative AI to adopt policies with specified protections, including disclosure for public works consisting entirely of generative output. It also permits more restrictive policies. SB 574’s attorney court-document provision contains no equivalent entirely-generated threshold. That difference may justify a request for legislative refinement; it does not authorize the Judicial Council or COPRAC to transplant its threshold into the attorney statute. [California Rules of Court, rule 10.430(b), (d)(5), and advisory comment](https://courts.ca.gov/system/files?file=file%2Froc-title-10_1.pdf).

The most workable package would keep disclosure informative without exposing client strategy or confidential prompts. It should identify the covered document and use, follow applicable court requirements, and preserve a record sufficient to explain the disclosure. If a materiality or routine-tool exception is desirable, the body with authority to create it must do so. Administrative convenience alone cannot supply an exception omitted from the text.

<a id="v2-controls"></a>

## 14. Ten practical controls for extensive, accountable AI use

The original inquiry asked for five general compliance technologies and five focused on delegation. The following are architecture patterns, not certified products or mandatory purchases. Each addresses a real failure mode. **The absence of that particular technology does not itself establish violation** if another adequate method fulfills the duty.

### Five general compliance patterns

| Pattern | How it supports extensive AI use | What could go wrong without an adequate equivalent |
|---|---|---|
| Confidential-data access gateway | Routes matter data only into approved environments; checks authorized recipients, access restrictions, confidentiality terms, and downstream transfers. Redaction is used where appropriate, rather than automatically stripping all information needed for legal analysis. | Client data reaches a system or person lacking the required restrictions; a model integration exposes one matter to another. |
| Source-verification workbench | Retrieves actual authority, checks quotations and citations, flags missing or conflicting support, and presents it for the responsible attorney’s personal verification where required. | A plausible citation or quotation enters a filing without the required examination; the system checks its own invented source. |
| Document-level AI-use record and disclosure assistant | Tracks covered AI involvement and helps prepare disclosures in the form required by applicable law and orders. | The lawyer fails to identify a required disclosure, or assumes that a vendor’s label determines whether the filing used AI. |
| Error-and-correction propagation | Connects a discovered defect to drafts, advice, filings, and other material that relied on it, and routes necessary corrections. | The noticed error is corrected once but continues to be used elsewhere. |
| Action and evidence record | Preserves proportionate records of relevant sources, versions, authorizations, validation, and actions, with restricted access and retention rules. | The firm cannot investigate a failure, demonstrate what was authorized, or determine who relied on the result. |

The confidentiality pattern does not imply that SB 574 itself mandates a particular encryption standard, zero-retention contract, or automatic removal of every listed data category. Those may be useful safeguards in a particular deployment. The operative access restriction and existing duties must be assessed against the actual arrangement.

### Five patterns focused on retained professional control

| Pattern | Autonomous work it can support | The substantive limitation |
|---|---|---|
| Versioned lawyer-approved criteria and action limits | Repeated review, extraction, classification, or negotiation preparation within defined positions and objectives; an approved or signed specification identifies the version actually authorized. | Instructions must fit the matter; applying them to novel facts may require fresh judgment. |
| Validated bulk-review process | Classification or analysis of a population without individual lawyer review of every item. | Testing must justify the reliance; critical subpopulations and missed items need attention. An evaluation harness can suspend the affected operation when an agreed limit fails. |
| Staged preparation followed by meaningful adoption | A complete research, drafting, or analysis lifecycle produces a finished internal candidate before the lawyer evaluates and uses it. | Adoption must be informed and timely; it does not retroactively cure an already completed unauthorized external act. |
| Exception handling with enforceable action restrictions | Ordinary cases proceed within tested conditions while unusual or prohibited actions enter a holding state with a named recipient for decision. | An exception detector can miss cases. Test the mechanism and the consequences of failure, not just the list of triggers. |
| Configuration and permission revalidation | A firm increases autonomy as evidence supports it and reconciles actual service permissions with authorized scope after material model, data, configuration or access changes. | Approval of a product name does not establish approval of every later configuration or legal use. |

For arbitration, adapt these patterns to the different statutory restriction rather than assume an attorney’s process-based permission transfers to a neutral. A neutral’s system can be technically well controlled and still perform a legally prohibited part of decisionmaking.

A signed specification, a circuit breaker and a permission check are useful only if they govern what actually happens. Equivalent controls can be effective. A firm should test both a compliant run and a counterfactual failure: an altered approved document, a missed exception, a leaked cross-matter summary, an inaccurate citation or a disabled stop mechanism. The purpose is to expose a real professional failure mode, not to claim that purchasing one named technology proves compliance.

<a id="v2-training"></a>

## 15. A six-hour CLE program, with three hours on delegation

This is a proposed educational program, not a claim of approved California MCLE credit. Provider approval, subject-credit categories, and delivery requirements would need to be handled through the applicable process.

| Module | Time | Exercise and practical outcome |
|---|---:|---|
| The bill and existing professional duties | 45 minutes | Read the operative attorney, filing, arbitrator, and ADR provisions; distinguish pending legislation, enacted text, advisory guidance, and court orders. |
| Confidentiality and data use | 45 minutes | Trace a document through a vendor and agent workflow; identify access, terms, permissions, and appropriate client communication. |
| Accuracy, citations, disclosure, and correction | 45 minutes | Verify an intentionally flawed draft against sources, distinguish personal acts from automated checks, and prepare an appropriate disclosure and correction plan. |
| Arbitration and institutional roles | 45 minutes | Compare advocate and neutral workflows; identify where disclosure does not cure a substantive prohibition. |
| Delegation: interpreting the professional role | 60 minutes | Compare the three interpretations in Section 4 using *Crawford*, the assistance language, and an actual discovery workflow. |
| Delegation: building and evaluating autonomous work | 60 minutes | Design three workflows: a complete internal research-and-drafting cycle; a validated bulk responsiveness review; and contract review under a lawyer-approved playbook with staged external action. |
| Delegation: proving that the arrangement works | 60 minutes | Examine sample results, missed exceptions, changed model behavior, client authority, and approval records. Decide what can run autonomously, what needs review, and what would require legal clarification. |

The final three hours are exactly half the program. The learning objective is economically useful, high-quality practice through AI—not maximizing the number of human approvals. Participants should finish with a reasoned operating plan, a testable basis for reliance, and a clear distinction between present permission and a proposed expansion requiring clarification.

For the final workshop, participants can build a highly automated practice that runs internal tasks overnight, then test how it fails. One exercise removes meaningful adoption; another gives an agent a filing credential; another changes the review population without retesting. Participants explain the resulting legal problem and propose an adequate correction. This teaches the boundary through practical counterexamples while preserving the goal of extensive useful autonomy.

<a id="v2-agenda"></a>

## 16. Further insights and an implementation agenda

### The unit of judgment is the central question

Much of this debate asks whether “the lawyer or the AI” made a decision. That framing hides the possibility of several decisions at different levels. A model classifies a document. A lawyer decides that the classification method is appropriate for this case. A lawyer or team evaluates whether the results justify production. The client makes decisions the representation reserves to the client. A court resolves disputes.

These activities are not interchangeable. But they can coexist without pretending that the model performed no analysis. A particularly valuable contribution is to get the legal framework to specify **which judgment must be exercised, by whom, at what level, and before what consequence**.

### A negative classification can be as consequential as a positive one

Calling a tool a “triage assistant” does not make it harmless if its negative classifications determine which documents no one ever sees. A system that hides a responsive record may affect the production just as materially as one that labels a record for inclusion.

Evaluation should therefore examine what is missed, not only the quality of attractive positive results. In discovery, recall concerns how much relevant material is found; precision concerns how much selected material is actually relevant; elusion examines relevant material left in the excluded population. The lawyer needs to understand which question the metric answers and what uncertainty remains. Relativity’s published validation materials provide useful operational examples, but no one vendor’s default creates a legal safe harbor.

### The professional standard should evaluate the actual combined system

An AI’s raw score does not decide whether adding a human checkpoint helps. A human reviewer can catch error, introduce error, or defer to the model without noticing a problem. Conversely, a model can help a human recognize an exception the human would otherwise miss.

The relevant comparison is the actual proposed workflow against feasible alternatives. Test representative tasks, difficult cases, and foreseeable failures. When human coding serves as the reference, examine disagreement and error in that coding. When several models agree, consider common sources and correlated mistakes. Agreement among systems trained on similar material is not independent proof of correctness.

This supports the objective of standards that adapt to improving capability. If a defined system becomes demonstrably more reliable than a feasible human or hybrid process, that evidence should matter to competent practice. It does not follow that the system may exercise every legally reserved authority. Performance and authorization are different questions, and each should be answered explicitly.

### Oversight is itself a function that can improve through automation

It would be perverse to allow an agent to analyze ten thousand contracts but insist that all quality control remain a person staring at a dashboard. Automated source checks, independent test suites, permissions, duplicate detection, exception routing, and rollback can strengthen supervision. A lawyer’s professional contribution includes choosing and evaluating those controls.

There must still be a competent person or team able to respond to a failure. But human involvement need not be continuous observation. The book’s distinction between ownership, monitoring, and individual review is especially helpful here.

### Capability should change the boundary of permissible reliance, but not through vague promises

“Better than the best attorney” is too broad to serve as a present factual premise. A system may outperform experts on one document population while failing on a new legal issue, unseen format, language, or objective. It may produce excellent summaries and poor privilege judgments. Improvement needs to be demonstrated for the function in question.

The constructive principle is therefore conditional: **as reliable evidence improves, the amount and form of necessary intervention should be reconsidered.** That avoids freezing today’s limitations into permanent rules and avoids granting tomorrow’s imagined capabilities to today’s system.

### Cost and access belong inside the competence discussion

A process can be accurate but so slow or expensive that a client cannot obtain useful representation. Unnecessary review can consume time that would be better spent on factual investigation, negotiation, or exceptional issues. The legal profession should take those opportunity costs seriously.

This is not a claim that low cost excuses carelessness. It is a reason to compare complete services: accuracy, timeliness, confidentiality, contestability, and cost. The case for broad AI use becomes stronger when it shows better service for clients, rather than merely reduced labor for the provider.

### Accountability includes correction, not just allocation of blame

A rule that says “the lawyer is responsible” can be satisfied rhetorically while leaving the client without an effective way to challenge an error. A useful practice design identifies who can correct the result, recover an affected filing or communication where possible, notify those who relied on it, and prevent recurrence.

That is one of the book’s deepest contributions. It connects the client’s experience to the operational process. An insurance clause or signature can allocate consequences after failure; it cannot by itself correct the legal service.

### Uncertainty can inhibit useful work before a court decides anything

Even if the preferred interpretation eventually wins, lawyers, insurers, vendors, and procurement teams may narrow permitted use in the meantime. A vague prohibition can therefore create costs through risk aversion rather than formal enforcement. That is an inference about behavior, not a measured result of this not-yet-enacted bill.

It explains why a clean worked example and affirmative interpretive language matter. Merely saying “consult counsel” or “retain professional judgment” leaves the operational question unanswered. Useful guidance should show at least one substantive workflow that is allowed and explain why, while identifying facts that would change the result.

### The best position does not require a choice between innovation and responsibility

The defensible position is that California lawyers should be able to practice through increasingly capable systems, including systems that perform substantive analysis and bounded autonomous work, when the professional arrangement actually satisfies the governing duties. It is stronger to make that affirmative case directly than to argue that sophisticated machine work somehow ceases to be legal merely because it is automated.

The remaining disagreement is real and focused: does the statute, properly construed, permit that professional arrangement, and what facts establish it? That is a useful question for COPRAC, the judiciary, and the Legislature. It is also one that the eDiscovery example makes possible to answer concretely.

### Turning the principle into a firm’s operating plan

The research supports working on an AI-native practice now as a serious design problem, while separating the parts supported by current law from the interpretation of a proposal. It does not support a claim that California lawyers must limit AI to spelling correction. It also does not support treating the attorney’s license as permission for an agent to provide independent legal services with occasional review afterward.

The firm’s first task is to describe the professional service it intends to provide. Where does the client receive advice? Who selects the legal response? What commitments can be made, and by whom? Which facts or uncertainties require attention before action? Once those questions are explicit, the firm can automate preparation aggressively and build review around the decisions that matter.

The second task is to make professional evaluation easier. A lawyer should be able to see the sources, competing interpretations and unresolved assumptions without reconstructing the entire research project. An agent that produces an elegant answer but hides its weaknesses can increase review costs and risk. An agent that organizes evidence and exposes alternatives can make the lawyer substantially more effective.

The third task is to distinguish a reusable process from a decision that must still be made for the particular client. Standardization is valuable. So is recognizing when a new fact takes a matter outside the conditions for which a standard response was designed. The more autonomous the system, the more consequential that distinction becomes.

For policy work, the most constructive next step would be clarification of the assistance boundary. For a firm, it would be a concrete workflow description reviewed against the proposed text and current professional duties. For a technology provider, it would be tools that support source inspection, effective control and clear allocation of authority. These projects can proceed together without pretending that every legal uncertainty has already been resolved.

The most valuable promise of an AI-native firm is not simply that it can generate more legal text. It is that it can give a lawyer more of the right evidence, better alternatives and more time for the decisions that justify the professional role. A design that realizes that promise has a substantially stronger foundation in the research than one built around an attorney’s name on an autonomous legal service.

<a id="v2-leads"></a>

## 17. Useful leads to preserve without overstating what they establish

The additional reports contributed more than legal propositions. They identified commentators, institutions, vendor functions, economic questions and research methods. Those contributions should remain available even when their strongest formulation is unproved. The following agenda carries them forward with the evidentiary work each would require.

**Legislative recordings and stakeholder positions.** The reports identify Digital Democracy hearing segments, comments attributed to legislators and staff, privacy concerns, and positions concerning arbitration and mediation. These are useful routes to a better legislative account. Before quoting a speaker, verify the recording, date, identity, surrounding exchange and bill version. Indexed durations do not measure all staff work or consideration; a search locating no statement does not establish institutional silence. The record reviewed here supports a request for an operational definition, not a claim that nobody considered the bill. The nine analysis files and version comparisons remain linked in the source supplement.

**Practitioner explanations and proposed wording.** Practitioner commentary and research leads from legal-technology practitioners, Legal Quants, litigation-AI commentators and technology accounts highlight confusion about supervision, disclosure and deletion of the reading requirement. The useful ideas are already incorporated: distinguish the attorney’s role from an unlicensed provider; explain what professional judgment means; specify lawful substantive assistance; and make disclosure workable. Unverified posts and quotations remain leads in the preservation register, not statements of legislative intent. An author’s later comment would also require attention to its date and legal weight.

**Economics and access.** Blaine Dillingham’s March 18, 2026 *Process over Product* raises a concrete staffing question: what useful division of labor changes when a task becomes expressly personal to an attorney? Its example is an anecdote, not a market average. It can inform a study of verification time, review-team composition, cost, quality and services forgone. Existing section 128.7 already requires reasonable inquiry; the policy choice is which assurance methods protect clients effectively, not whether all process requirements should disappear. [Foundation for American Innovation, Process over Product](https://www.thefai.org/posts/process-over-product-how-a-california-bill-could-make-legal-services-more-expensive).

That study should also examine distribution. Larger firms may absorb new compliance costs more easily; smaller practices and public-interest providers may lose useful capacity. Verification, governance and insurance vendors may gain business. Those are plausible mechanisms, not measured consequences of SB 574. The benchmark should include the service a person can actually obtain, including no representation, rather than only an idealized premium human service. Restricting accountable lawyer-assisted tools could conceivably push some users toward unsupported direct AI use; that effect needs evidence.

**Market capabilities and adoption.** The supplied eDiscovery material lists Relativity, Everlaw, DISCO, Reveal, Consilio, Epiq and other products or service providers. The directly checked Relativity and Everlaw documentation supports the particular workflow descriptions in Section 6. Other product capabilities, comparative rankings and performance claims require dated documentation and task-specific evaluation. Neither a vendor’s sales claim nor a survey showing adoption proves necessity, competence or a particular quality advantage. Preserve Clio and similar adoption surveys with their year, sample, question and definition of AI before using percentages.

**Failure databases and sanctions examples.** Reports of fabricated authorities can help classify failure modes: missing sources, altered quotations, real cases used for false propositions, unsuccessful supervision and late correction. A collection of published incidents lacks the denominator needed to estimate an error rate. Unverified sanctions totals, including the reported *Couvrette* example, remain research leads. Compare actual workflows and outcomes; do not infer model-versus-human reliability from a selected list of embarrassing cases.

**Insurance-market signals.** Protexure and other commentary suggests that controls and professional conduct may affect underwriting. Obtain the actual policy and a workflow-specific answer before relying on coverage. The LMIC specimen in Section 10 is a concrete starting point, not a substitute for the insured’s contract. Insurance can redistribute losses without correcting a client’s problem; both remedies and prevention matter.

**Further cases, scholarship and comparative regimes.** The reports nominate additional treatises, *State Farm v. Garamendi* and other interpretation authorities, First Amendment developments, offshore outsourcing materials, and professional-delegation comparisons. These can deepen an opinion when tied to an actual unresolved proposition. A title in a bibliography is not a verified holding. The baseline guide retains the procedural qualifications for *Dacey*, *Janson*, *Parsons*, *Upsolve* and the other software cases. Current docket status, especially any claimed Supreme Court review, must be checked before a present-tense filing or publication.

**Prompts, work product and discovery of the process.** The Emory/Grossman paper identified in the research argues for protection of strategically revealing generative-AI prompts. Its existence and abstract were located; the full paper was not retrieved in this review. It is a useful scholarly lead, not a rule that every prompt is privileged. The actual content, purpose, waiver, governing law and discovery dispute matter. This complements early planning for privilege descriptions and a restrained record of decisions. [Paper record and abstract](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7036120).

**Source repair and missing attachments.** The Grok report refers to fuller tables in a separate attachment that was not among the supplied materials. Some other reports contain incorrect rule references, unrelated links or unsupported claims that every citation was verified. Those defects have not erased their useful ideas. The legal support has been replaced where checked, and unresolved claims remain qualified. An unexplained reference concerning confidentiality of enrolled-bill reports, for example, is a question for source review rather than an established privilege.

**A continuing watch that can expand permission.** A useful research practice tracks statutes, rule proposals, opinions, applicable orders, model changes and evidence of improved performance together. It should revisit restrictions when better evidence warrants more autonomy as well as respond to failures. This is an operating recommendation, not a claim that a permanent monitoring service has been established by this report.

**An expanded literature and stakeholder map.** Farella, Reed Smith, DLA Piper, Artificial Lawyer, The Leveraged Years and legal-ethics publications supply leads on cost, sanctions, graduated autonomy, product design and international arbitration. TechEquity’s agenda and Oakland Privacy’s concerns can illuminate support and affected nonclient interests; neither substitutes for an actual letter on the operative version. Identify whether a position belongs to an organization, a section, a committee or an individual. Preserve reported AAA, California Dispute Resolution Council, CLA section, Collaborative Practice California and LACBA committee concerns with that precision. Reprints are not independent corroboration. Full letters and recordings would strengthen the account.

Every individual nomination, including its originating report and its correction or qualification, remains in the 325-item preservation register. The register preserves distinct ideas even where the narrative combines them. It is an audit and research appendix, rather than a requirement that the reader reconstruct a debate between models.

<a id="v2-sources"></a>

## Annotated source guide

The discussion above is intended to stand on its own. This guide preserves the case authorities examined in the research and explains why each matters. It includes supporting comparisons and the two disclosed standalone exclusions, rather than pretending every retrieved case has equal weight. A citation links to the archived opinion or the public source from which the copy was obtained. California Supreme Court decisions, intermediate appellate decisions, federal decisions applying other states’ law, and advisory guidance have different legal force.

An automated citator’s unknown result is not a certification of good law. Issue-specific qualifications appear below and in the source audit. The article does not claim that the shared research index is complete.

### Defining legal practice, software services and legal permission

**[People v. Merchants' Protective Corp., 189 Cal. 531 (1922)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/U6/U6MhpmHYu6EaCb7GrsNphLGm.pdf).** The California Supreme Court’s historical definition reaches legal advice and document preparation outside litigation. The corporation’s role in supplying legal services matters; modern rules for authorized practice entities must be considered separately.

**[Baron v. City of Los Angeles, 2 Cal.3d 535 (1970)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/6l/6lhyYrLYjKZ7AEa3PYo0Mmy3.pdf).** The California Supreme Court examines legal activity in the context of a lobbyist-registration ordinance. Its application-of-legal-knowledge formulation is central here. It does not make every professional activity performed by a lawyer protected legal practice, or exempt personalized advice merely because it seems easy.

**[People v. Ring, 26 Cal.App.2d Supp. 768 (1937)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/hD/hDFKLEzZUqFmJIMbmS9UOC.pdf).** This lower California court decision records the established judicial meaning of legal practice. Birbrower later disapproved inconsistent portions of its California-contact analysis. The broad definition and the geographic question should not be treated as one undifferentiated holding.

**[Birbrower, Montalbano, Condon & Frank v. Superior Court, 17 Cal.4th 119 (1998)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/pJ/pJLxbGW1Uw3hFAurfZGu2Ui.pdf).** The California Supreme Court considers out-of-state lawyers’ California services. Physical location alone does not resolve authorization. The case must be read with current permissions for particular forums and activities, including arbitration counsel; it is not a universal present-day prohibition on out-of-state participation.

**[People v. Landlords Professional Services, 215 Cal.App.3d 1599 (1989)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/xA/xAdj3zrfP920UM9DfFXvChzG.pdf).** The California Court of Appeal distinguishes clerical help from personalized eviction-related advice and document selection. The case makes the actual service and context central, which is useful when analyzing an automated intake-and-document workflow.

**[Morgan v. State Bar, 51 Cal.3d 598 (1990)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/7U/7U6vMfRSafpcGOFKRPpkhRl.pdf).** The California Supreme Court treats specified settlement negotiations and related representation as legal practice in a disciplinary setting. It illustrates that protected professional activity is not limited to drafting pleadings or appearing at a hearing.

**[Benninghoff v. Superior Court, 136 Cal.App.4th 61 (2006)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/19/19kjrDE2vZwF5Rc7YojpDnh.pdf).** The California Court of Appeal considers a disbarred lawyer’s work in administrative proceedings and the limits of lay-representation arguments. A conventional lawyer-client relationship is not a universal prerequisite to the legal-practice question. This is not a decision about AI.

**[Hustedt v. Workers' Compensation Appeals Board, 30 Cal.3d 329 (1981)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/vy/vySUWaehMiYlzOWpihYloWs.pdf).** The California Supreme Court addresses judicial authority over attorney discipline and the Workers’ Compensation Appeals Board’s role. It supports the importance of forum-specific rules and institutional authority; it does not supply a general exemption for administrative legal services.

**[Estate of Condon, 65 Cal.App.4th 1138 (1998)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/yy/yyk2rUo8qN5fj5w4i5LEhs.pdf).** The California Court of Appeal examines fees for out-of-state services for an out-of-state client. It qualifies overbroad uses of the geographic-practice cases. An AI firm serving clients across jurisdictions still needs to analyze the actual services and governing permissions.

**[In re Garcia, 58 Cal.4th 440 (2014)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/Xn/XnxlN2vwEaKpnP18wTHwCYhW.pdf).** The California Supreme Court’s admission decision illustrates the importance of an express statutory authorization in a licensing framework. The case does not establish that AI can be admitted, licensed or treated as a lawyer.

**[Florida Bar v. Brumbaugh, 355 So.2d 1186 (Fla. 1978)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/Kj/KjkG9PFK8IuuaqlKlpqGldQ.pdf).** The Florida Supreme Court distinguishes public information and customer-directed typing from individualized advice. It is a comparative source, not a California statutory permission. Its narrow facts matter when considering blank forms and document services.

**[In re Reynoso, 477 F.3d 1117 (9th Cir. 2007)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/hS/hSLwrxlnjgBzPka2DHZJrwe.pdf).** The Ninth Circuit addresses an automated bankruptcy-preparation service that supplied individualized legal advice. Its express reservation concerning software alone prevents a blanket claim that all legal software is unauthorized practice. Federal petition-preparer law also requires attention to the statutory version.

**[In re Bernales, 345 B.R. 206 (Bankr. C.D. Cal. 2006)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/rm/rmPkHFMOywAQYLZuiZpd683U.pdf).** The bankruptcy court analyzes petition-preparer employees under 11 U.S.C. section 110. It is useful for the importance of the statute’s defined roles and exceptions, not as a general rule about employees of licensed law firms or AI systems.

**[Janson v. LegalZoom.com, Inc., 802 F.Supp.2d 1053 (W.D. Mo. 2011)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/65/65HL3Mco347NvmIFGOftWSq.pdf).** The federal district court applies Missouri law to LegalZoom’s service in resolving particular summary-judgment motions. Personalized document production mattered. The disposition was not a final nationwide ruling on every legal-software product.

**[LegalZoom.com, Inc. v. North Carolina State Bar, 2015 NCBC 96](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/pT/pTyZrYbVHeWFWVAq9sNOSgzk.pdf).** The North Carolina Business Court consent judgment records a negotiated arrangement and disclaims a finding or admission of violation. It should be distinguished from a merits decision and from later statutory software permission.

**[Unauthorized Practice of Law Committee v. Parsons Technology, Inc., 179 F.3d 956 (5th Cir. 1999), vacating N.D. Tex. 1999 Quicken Family Lawyer decision](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/hk/hkPknlPw9BjLbYOxblSODces.pdf).** The Fifth Circuit vacated the earlier software injunction and judgment after Texas legislation changed. This history is especially useful when considering express legislative permission; the vacated judgment cannot be presented as continuing final authority against the product.

**[Lola v. Skadden, Arps, Slate, Meagher & Flom LLP, 620 F.App’x 37 (2d Cir. 2015), No. 14-3845](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/xf/xfrCi5YHkd5ZnuSI7AbH322p.pdf).** The Second Circuit considers the professional exemption under federal wage law and North Carolina’s definition of practice, accepting allegations of mechanical document review at the dismissal stage. Its machine-performability sentence does not establish a universal California rule for increasingly capable AI.

### Personal professional responsibility and permitted assistance

**[Townsend v. State Bar, 210 Cal. 362, 364 (1930)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/ai/ai0IFpzsu1YlRr63t28vdy.pdf).** The California Supreme Court condemns lending a lawyer’s professional role to unlicensed operators. Its personal-public-trust language explains why a nominal lawyer affiliation is different from meaningful professional participation.

**[McGregor v. State Bar, 24 Cal.2d 283, 288 (1944)](https://scocal.stanford.edu/opinion/mcgregor-v-state-bar-29251).** The California Supreme Court repeats the personal-license principle in attorney discipline. It reinforces the distinction between assistance and another person’s independent practice through a lawyer’s name; its application to AI is an analogy.

**[Crawford v. State Bar, 54 Cal.2d 659 (1960)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/A1/A1Nsjsk8fWLsADYkhQHcAW.pdf).** The California Supreme Court discusses preparatory work becoming part of the attorney’s own product through actual examination, approval or further effort. The misconduct involved independent work by a disbarred father. Both the preparatory-work discussion and the actual failure of control matter.

**[Gadda v. State Bar, 50 Cal.3d 344, 353–354 (1990)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/2z/2ztg8HZP491yBsGnvYSaPjT.pdf).** The California Supreme Court addresses responsibility for work performed under an attorney’s direction and authority, including licensed associates. It supports actual supervision without establishing a complete AI safe harbor.

**[Vaughn v. State Bar, 6 Cal.3d 847 (1972)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/vq/vqbERIupTUPT3bMbSqX34.pdf).** The California Supreme Court explains that an attorney need not manage every office detail but must supervise staff. The rule concerns real supervision rather than a promise of responsibility on paper.

**[Palomo v. State Bar, 36 Cal.3d 785 (1984)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/Oy/OyHfPHDeKyusJpwlBP5e7Yx.pdf).** This California Supreme Court disciplinary decision likewise distinguishes every office detail from the lawyer’s supervisory responsibility. It should not be transformed into universal strict disciplinary liability for every assistant’s act.

**[Trousil v. State Bar, 38 Cal.3d 337 (1985)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/Kb/Kb0B9nE70YH5SyULDxoko1.pdf).** The California Supreme Court examines inadequate supervision in the actual office arrangement. It provides context for evaluating what a lawyer did, rather than assuming that delegation either automatically excuses or automatically establishes misconduct.

**[Moore v. State Bar, 62 Cal.2d 74 (1964)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/lO/lO6JNEZy1VjklsuQPLrm4HZB.pdf).** The California Supreme Court’s discussion of failing to check that staff performed assigned work is useful to the difference between issuing an instruction and verifying its execution. An AI policy alone has the same practical limitation as an unenforced office instruction.

**[Spindell v. State Bar, 13 Cal.3d 253 (1975)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/uJ/uJORQYLWYqWxcvo22bMAGiGE.pdf).** The California Supreme Court addresses inadequate supervision of office personnel. Its role is to reinforce the factual inquiry into management and oversight, not to decide the scope of a proposed AI prohibition.

**[Drociak v. State Bar, 52 Cal.3d 1085, 1087–1090 (1991)](https://scocal.stanford.edu/opinion/drociak-v-state-bar-31294/).** The California Supreme Court considers client-presigned blank verifications completed without consultation. Unsupported staff-forgery allegations were rejected. The case belongs with personal attestation and verification, rather than an inaccurate story about staff independently supplying signatures.

**[Goodley v. Wank & Wank, Inc., 62 Cal.App.3d 389, 395–397 (1976)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/n3/n3qa5EZEzNL73rJ3naauCYA.pdf).** The California Court of Appeal addresses assignment of legal-malpractice claims and the personal attorney-client relationship. Its loyalty and client-permission concerns are relevant analogies, but the decision does not prohibit ordinary supervised staff work. Other jurisdictions and transactional contexts supply qualifications.

**[Curtis v. Kellogg & Andelson, 73 Cal.App.4th 492, 504–505 (1999)](https://static.case.law/cal-app-4th/73/html/0492-01.html).** The California Court of Appeal considers a purported transfer of a malpractice claim in bankruptcy. Its discussion of loyalty must be read in that claim-ownership setting. Later decisions distinguish other bankruptcy arrangements; the case is not an all-purpose ban on task delegation.

**[County of Santa Clara v. Superior Court, 50 Cal.4th 35 (2010)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/Qc/QcPwhw4dR20vDWJDaMz1Ba.pdf).** The California Supreme Court permits a public-nuisance contingency-counsel arrangement subject to actual governmental control and neutrality protections. Its control arrangements are useful design analogies. Their predictive weight for private AI practice is one of the researchers’ remaining confidence differences.

**[Schecter v. County of Los Angeles, 258 Cal.App.2d 391, 397–398 (1968)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/iq/iqHNV9F6IDTuZgQE8HAuejF.pdf).** The California Court of Appeal considers administrative allocation of investigation, recommendation and drafting while the authorized officer retains the decision. It helps explain preparation versus final discretion, without supplying direct permission for AI legal practice.

**[Maloney v. Rath, 69 Cal.2d 442 (1968)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/f0/f0NctJotRq3z60uG0IuPm1z.pdf).** The California Supreme Court’s brake-maintenance case illustrates a duty for which responsibility cannot be avoided by hiring someone else. It distinguishes retained liability from mandatory personal performance. It does not authorize legal-services delegation.

**[Rob-Mac, Inc. v. Department of Motor Vehicles, 148 Cal.App.3d 793 (1983)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/1J/1JLZ9Lcj4E8X5pWZq1pyO7X.pdf).** The California Court of Appeal addresses regulatory responsibility in a licensed business. Using employees or contractors does not necessarily insulate the licensee from regulation. The analogy concerns retained regulatory responsibility, not a general AI permission.

**[California Assn. of Health Facilities v. Department of Health Services, 16 Cal.4th 284 (1997)](https://scocal.stanford.edu/opinion/california-assn-health-facilities-v-department-health-services-31876/).** The California Supreme Court examines duties in regulated health facilities. Later treatment distinguishes licensing enforcement from civil liability for every employee tort. The research uses the regulatory-responsibility analogy within that limitation.

**[Borg-Warner Protective Services Corp. v. Superior Court, 75 Cal.App.4th 1203 (1999)](https://static.case.law/cal-app-4th/75/html/1203-01.html).** The California Court of Appeal addresses responsibility in licensed protective services. Employment, regulatory duties and scope-of-employment limits matter. The decision does not establish that every act within an AI-enabled business automatically creates the same civil liability.

**[State ex rel. Indiana State Bar Assn. v. Northouse, 848 N.E.2d 668 (Ind. 2006)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/Mj/MjDoRZAOQp9wMbdBMuje9a6.pdf).** The Indiana Supreme Court addresses the professional’s continuing responsibilities when work is assigned or subcontracted. It is comparative support for examining the service arrangement, rather than a California rule governing a generative system.

**[Florida Bar v. American Senior Citizens Alliance, 689 So.2d 255 (1997)](https://openjurist.org/689/so2d/255/florida-bar-v-american-senior-citizens-alliance-1863800).** The Florida Supreme Court considers nonlawyer trust advice and selection followed by cursory in-house lawyer review. The sequence did not cure the arrangement. This is a warning about actual professional participation, not a holding that every meaningful lawyer-reviewed draft is impermissible.

### AI use, verification and court submissions

**[Noland v. Land of the Free, L.P., 114 Cal.App.5th 426 (2025)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/ip/ipQx4JJgO06quV81pqAmq59T.pdf).** The California Court of Appeal addresses fabricated authorities and the attorney’s obligation to check the actual legal material before filing. It permits appropriate AI assistance while rejecting abdication of verification. Its discussion also preserves the relevant Mata principle without treating Mata as a separately cleared authority here.

**[People v. Alvarez, 114 Cal.App.5th 1115 (2025)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/t4/t4liYSZ7hv8SXO8B7Udmsl.pdf).** The California Court of Appeal sanctions a fabricated quotation attributed to an actual case. Verification must address what an authority says, not merely whether a case name resolves. The researched reporter citation begins at page 1115.

**[Del Biaggio v. Bansen, No. A174647 (Cal. Ct. App., July 10, 2026)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/L6/L6VROF9AN7QAKLK5S7c2CnMs.pdf).** The California Court of Appeal finds merit in an underlying fee issue while condemning false appellate quotations and inadequate verification of AI additions. It is particularly useful for separating a potentially sound argument from unacceptable support for it.

**[Shayan v. Shakib, 116 Cal.App.5th 617 (2025)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/ba/bag7Agzkm3ORqvFm3hEaiJg4.pdf).** The California Court of Appeal emphasizes the signatory attorney’s responsibility for the brief. A production chain involving another person or technology does not eliminate that responsibility.

**[Quinteros v. Harbor Distributing, No. A174202 (Cal. Ct. App., June 11, 2026)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/kc/kchN0kQn0EVy2io5n2TCoyqn.pdf).** The California Court of Appeal originally published this decision concerning a firm’s reliance on a contract lawyer’s inaccurate AI-assisted filing. The September 2, 2026 depublication-request outcome was not confirmed. No central conclusion here depends on its continuing published status.

**[United States v. Farris, No. 25-5623 (6th Cir., April 3, 2026)](https://www.opn.ca6.uscourts.gov/opinions.pdf/26a0105p-06.pdf).** The Sixth Circuit addresses inaccurate descriptions of genuine authorities and inadequate checking despite editing and staff involvement. It reinforces proposition-level verification. The decision is not a finding about the general reliability of a particular product.

**[State v. Coleman, 2026-Ohio-965](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/Ay/AyFddPhlmGDIsTmeD8tjg6St.pdf).** The Ohio decision addresses substantive lawyer responsibility and effective oversight of AI-assisted filings. A genuine disagreement concerned additional sanctions and process, not whether false authorities were acceptable. This illustrates why duties, attribution and remedies should be analyzed separately.

**[Leiske v. Kidd, No. 2025-0426-CDW (Del. Ch., July 1, 2026)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/CQ/CQKyOTjsrMBAJyya6FVtdaQg.pdf).** The Delaware Court of Chancery rejects reliance on a paralegal as a substitute for counsel’s own professional obligation. This is a comparative verification authority, not a California staffing rule. The relevant researched opinion is the July 1, 2026 disposition.

**[Estate of Caviness v. Atlas Air, Inc., No. 24-11033 (11th Cir., July 10, 2026)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/1N/1Nham0RXWFnvw2EMUGg6zlJT.pdf).** The Eleventh Circuit condemns complete outsourcing of legal work to AI as incompatible with competence. Its language supports the distinction between meaningful professional participation and abdication; it does not decide every supervised AI use.

**[Lnu v. Blanche, No. 24-4790 (9th Cir., June 3, 2026)](https://cdn.ca9.uscourts.gov/datastore/opinions/2026/06/03/24-4790.pdf).** The Ninth Circuit discusses retained professional responsibility and AI use, including California guidance. It provides comparative reinforcement for professional judgment and verification, without construing the proposed California statute.

**[Russell v. Mells, No. 2D2024-1560 (Fla. 2d DCA, December 10, 2025)](https://flcourts-media.flcourts.gov/content/download/2482282/opinion/Opinion_2024-1560.pdf).** The Florida appellate court addresses a lawyer’s responsibility for generated work product and inaccurate submissions. The remedies and procedural facts should not be generalized into an identical sanction for all AI errors.

**[Clerk of the Court and Comptroller v. Rangel, No. 2D2024-1772 (Fla. 2d DCA, August 29, 2025)](https://websitedc.s3.amazonaws.com/documents/Clerk_of_the_Ct._v._Rangel_USA_29_August_2025.PDF).** The Florida appellate court’s August 2025 opinion concerns citation misconduct and referral to the Bar. A separate March 2026 merits opinion addresses bond forfeiture; it does not withdraw the earlier misconduct discussion. The archive distinguishes the two opinions.

**[In re Amendments to Rules Regulating The Florida Bar—Chapter 4, No. SC2024-0032 (Fla., August 29, 2024)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/cM/cMEPbtrvvMqQYHmkeAEikKvm.pdf).** The Florida Supreme Court’s rule amendments explicitly address generative AI in professional responsibilities. They are comparative regulatory evidence, not California rules.

**[In re Domestic Partnership of Campos & Munoz, No. D085584 (Cal. Ct. App., March 2026; modified opinion)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/oY/oYTD3zF3GaXP9oUceyrfkGv.pdf).** The California Court of Appeal discusses judicial AI obligations and the adopted judicial-administration standard. The modified opinion’s source and dates are recorded in the research. Judicial standards, lawyer duties and the proposed arbitrator ban remain distinct.

### Arbitration, judicial decisions and federal limits

**[Sapp v. Barenfeld, 34 Cal.2d 515 (1949)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/RK/RK5JqO59taBClPMSdqMQyGFy.pdf).** The California Supreme Court permits technical assistance where arbitrators retain their own judgment. Historical consultation language must be read with current notice and response protections. The research corrected an automated treatment label whose stated direction was misleading.

**[Griffith Co. v. San Diego College for Women, 45 Cal.2d 501 (1955)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/eM/eMn94RZFDO0iRiOLcOjqFIY.pdf).** The California Supreme Court examines consultation concerning an arbitrator’s tentative conclusion. Actual retained judgment matters. This historical decision does not establish a current blanket permission for undisclosed outside consultation.

**[California Union Square L.P. v. Saks & Co. LLC, 50 Cal.App.5th 340 (2020)](https://www4.courts.ca.gov/opinions/archive/A158015.PDF).** The California Court of Appeal considers arbitral consultation and the scope of the agreed process. The research resolved an index caption error and uses the correct 2020 case. Party agreements and procedural limits matter alongside the general concept of assistance.

**[Anderson v. City of Bessemer City, 470 U.S. 564 (1985)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/9Q/9QKjQknRge7pq3T9rDX21j.pdf).** The United States Supreme Court explains that verbatim adoption of proposed findings does not by itself change whose findings they are. The actual judicial process matters. It is not a rule that an approval signature cures any prior transfer of decisionmaking.

**[Reaves v. Superior Court, 22 Cal.App.3d 587, 590–597 (1971)](https://static.case.law/cal-app-3d/22/html/0587-01.html).** The California Court of Appeal rejects prosecutor-led investigation and drafting of writ orders despite the judge’s asserted review. Institutional roles matter. Later procedural developments qualify its historical habeas discussion; it is not a complete statement of present procedure.

**[Ruisi v. Thieriot, 53 Cal.App.4th 1197 (1997)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/NG/NGl7G9xJXAo6tQO9fRMbReF.pdf).** The California Court of Appeal discusses limits on a nonconsensual reference. It helps distinguish information gathering and recommendations from authority to decide. Statutory consensual general references are a different arrangement.

**[Moncharsh v. Heily & Blase, 3 Cal.4th 1 (1992)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/5x/5xJbWXHvcYgnhMcvVDhS5Ou2.pdf).** The California Supreme Court limits ordinary review of private arbitration for legal or factual error. Recognized exceptions and statutory grounds still matter. An AI-related mistake does not automatically authorize a general rehearing on the merits.

**[Maaso v. Signer, 203 Cal.App.4th 362 (2012)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/6B/6BroXIUhXPZLvyGhWqcoBBn.pdf).** The California Court of Appeal considers improper substantive communication with a neutral arbitrator through a party arbitrator after the hearing. It helps distinguish neutral technical assistance from undisclosed advocacy and illustrates why procedural safeguards matter.

**[Ovitz v. Schulman, 133 Cal.App.4th 830 (2005)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/3u/3uI8jneDE0aCvyx8s5h0run.pdf).** The California Court of Appeal affirms vacatur for nondisclosure and rejects the particular federal-preemption argument in the parties’ California-law setting. It does not establish that every state arbitration rule survives federal scrutiny.

**[AT&T Mobility LLC v. Concepcion, 563 U.S. 333 (2011)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/Oy/OyqOjn3wF7gMQda7WiO54.pdf).** The United States Supreme Court examines state-law interference with fundamental features of arbitration. It supplies part of the federal-preemption framework, not a direct answer about generative AI.

**[Kindred Nursing Centers Limited Partnership v. Clark, 581 U.S. 246 (2017)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/u0/u0VbcvtizXthGMQASF25H7g.pdf).** The United States Supreme Court rejects special obstacles to arbitration agreements. Its principles cannot be avoided simply by labeling a rule one of conduct rather than formation. Application to a specific AI restriction would require further analysis.

**[Viking River Cruises, Inc. v. Moriana, 596 U.S. 639 (2022)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/OU/OUKDvgpGbJne2LmL91efXCJ.pdf).** The United States Supreme Court addresses the interaction between the Federal Arbitration Act and California representative-action procedures. Its federal holding must be distinguished from its prediction concerning California standing.

**[Adolph v. Uber Technologies, Inc., 14 Cal.5th 1104 (2023)](https://www.uschamber.com/assets/documents/Opinion-Adolph-v.-Uber-Technologies-Inc.-California-Supreme-Court.PDF).** The California Supreme Court addresses the standing question following Viking River. It qualifies the California-law premise without purporting to overrule the United States Supreme Court’s federal holding.

### Other useful comparisons and boundaries

**[Upsolve, Inc. v. James, 155 F.4th 133 (2d Cir. 2025), No. 22-1345](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/VU/VUxC1KUZVBgc5UzyuAq569I.pdf).** The Second Circuit vacates an earlier injunction against enforcement of New York unauthorized-practice rules in the challenged setting. Later remand and docket events were checked. The case preserves a constitutional issue, not a current blanket exemption for AI legal advice.

**[Chiles v. Salazar, 607 U.S. ___, 146 S.Ct. 1010 (2026), No. 24-539](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/op/ophiVseMxiF49TaDypMvTwkI.pdf).** The United States Supreme Court addresses viewpoint restrictions in licensed counseling speech. It is relevant to professional-speech analysis while distinct from legal-practice licensing and SB 574. The majority’s actual holding should not be replaced by a broader inference.

**[Magit v. Board of Medical Examiners, 57 Cal.2d 74 (1961)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/7r/7r72t8vHflRuXsBEckUcSlk.pdf).** The California Supreme Court addresses unauthorized medical acts despite immediate supervision. It shows why technical competence and supervision do not alone establish legal permission to perform a regulated service.

**[Lopez v. Ledesma, 12 Cal.5th 848 (2022)](https://supreme.courts.ca.gov/sites/default/files/supremecourt/default/2022-08/S262487A.pdf).** The California Supreme Court examines services by a licensed physician assistant within an authorized relationship for purposes of medical-liability law. It is a different setting from unauthorized practice and does not automatically supply permission for AI.

**[Transamerica Insurance Co. v. Sayble, 193 Cal.App.3d 1562 (1987)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/kI/kIwk8qZAQk5IFkCtPXvh6VBq.pdf).** The California Court of Appeal distinguishes internal law-firm business disputes from covered professional services under the policies at issue. Coverage turns on the policy and claim, not the fact that the insured is a lawyer.

**[Tana v. Professionals Prototype I Insurance Co., 47 Cal.App.4th 1612 (1996)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/BF/BF1jjnXEukqElomllgRgsTRC.pdf).** The California Court of Appeal considers a fee dispute under particular damages and professional-services provisions. It is a policy-interpretation authority, not proof that every AI-related loss is covered or excluded.

**[In re Jones, 5 Cal.3d 390 (1971)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/C6/C67uD3QLoppcNQw5JS0DEu.pdf).** This California Supreme Court conviction-discipline opinion was examined because it appeared among the research seeds. Its quoted rule concerns the effect of a conviction. It is not relied upon as an authority on staff or AI supervision.

### Examined sources with disclosed limitations

**[New York County Lawyers' Association v. Dacey, 21 N.Y.2d 694 (1967)](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/Be/BeWbdapBYJlnLamuBvoelc1Q.pdf).** This New York publication case remains in the archive, but the required primary-passage retrieval was unavailable. It is not used to establish a substantive publication or software exemption in this article. Other identified sources support the distinctions actually discussed.

**[Mata v. Avianca, Inc., 678 F.Supp.3d 443 (S.D.N.Y. June 22, 2023), No. 22-cv-1461, Document 54](https://descrybe-opinion-pdfs-public.nyc3.digitaloceanspaces.com/cases/pdf/By/ByNQgILqwKbngrzb9c5RsfM.pdf).** The sanctions opinion’s text was recovered and a quotation verified, but the prescribed citation-resolver step remained unsuccessful. The research does not treat it as a separately cleared merits authority. Noland’s discussion carries the relevant principle, and the source limitation remains visible.

### Statutes, professional rules and guidance

The following groups carry forward the statutory and regulatory authorities. The explanations identify their role rather than suggesting that every provision directly governs generative AI.

**The proposed legislation.** [SB 574, August 21, 2026 text](https://leginfo.legislature.ca.gov/faces/billTextClient.xhtml?bill_id=202520260SB574) would add Business and Professions Code section 6068.1, amend section 6173, amend Code of Civil Procedure section 128.7, and add sections 180 and 1282.1. Those provisions concern attorneys, citations, judicial guidance, arbitrators and the voluntary alternative-dispute-resolution certification program. [The January 13, 2026 Judiciary analysis](https://sjud.senate.ca.gov/system/files/2026-01/sb-574-umberg-sjud-analysis.pdf) is legislative background for an earlier draft.

**Licensing, attorney duties and discipline.** Business and Professions Code sections 6125 and 6126 concern practice authorization and unauthorized practice; section 6068 states attorney duties; sections 6103 and 6106 concern specified grounds for discipline. These are separate from whether a particular civil claim or sanction has all its required elements.

**Paralegals and role-specific permission.** Business and Professions Code sections 6450, 6452 and 6456 concern the paralegal role, restrictions and qualifications, attorney responsibility for specified harm, and a state-employment exception. They should not be converted into either an AI authorization or a rule that supervised substantial work is nonlegal.

**Referrals and business organization.** Business and Professions Code section 6155 concerns lawyer-referral services; section 6173 concerns the voluntary alternative-dispute-resolution certification program. Rule of Professional Conduct 5.4 addresses financial arrangements and professional independence. Different services and organizational structures require different analysis.

**Client relationship and competence.** California Rules of Professional Conduct 1.0.1, 1.1, 1.2, 1.3, 1.4 and 1.6 concern defined consent, competence, allocation of authority, diligence, communication and confidentiality. Rules 1.5 and 1.4.1 address fees and settlement offers. The provisions must be applied to the actual client relationship; AI does not create an exception.

**Supervision and unauthorized practice.** California Rules of Professional Conduct 5.1, 5.3, 5.3.1 and 5.5 address managers, supervisory lawyers, nonlawyer assistance, employment of certain ineligible lawyers, and unauthorized practice. Rule 5.3.1 is a human-status rule, not an AI category. California’s text should not be replaced with different ABA comments.

**AI guidance and court submissions.** The [State Bar’s May 2026 practical guidance](https://www.calbar.ca.gov/sites/default/files/portals/0/documents/ethics/Generative-AI-Practical-Guidance.pdf) replaces its 2023 version. It discusses agentic systems and applies existing professional obligations, including candor and meritorious-contention duties under Rules 3.3 and 3.1. It is guidance, not a judicial construction of the proposed bill.

**Arbitration and judicial references.** Code of Civil Procedure sections 1281.9, 1282, 1282.2 and 1286.2 concern disclosure, arbitral powers, procedure and vacatur. Sections 638 and 644 concern statutory references; section 1282.4 and California Rule of Court 9.43 address specified out-of-state arbitration counsel. Each has conditions that should be checked for the actual proceeding.

**Judicial and neutral ethics standards.** [Judicial Administration Standard 10.80](https://courts.ca.gov/cms/rules/index/standards/Standard10_80) addresses judicial AI use. Neutral Arbitrator Ethics Standards 1, 13 and 14 concern scope, conduct and communications. California Rule of Court 3.865 addresses mediator complaint procedures. Recommendations in a standard should not be silently restated as an identical statutory prohibition.

**Agency and retained responsibility.** Civil Code sections 2304, 2305 and 2349 provide agency background and circumstances for delegating authority; the limitations and principal’s special prohibition matter. Commercial Code section 2210 concerns delegated performance in sales law. Neither statutory scheme is a freestanding license to transfer legal practice to AI.

**Medical and mediation comparisons.** Business and Professions Code sections 2069 and 3502 concern authorized medical-assistant and physician-assistant functions. Health and Safety Code section 1339.75 concerns specified patient communications and a limited disclosure exception. Evidence Code section 1115 supplies definitions in the mediation-confidentiality chapter. These sources illustrate particular legal arrangements, not general permissions outside their scope.

**Federal statutes.** [9 U.S.C. sections 2](https://www.law.cornell.edu/uscode/text/9/2) and [10](https://www.law.cornell.edu/uscode/text/9/10) concern arbitration enforceability and limited vacatur grounds. [11 U.S.C. section 110](https://www.law.cornell.edu/uscode/text/11/110) concerns bankruptcy petition preparers, including defined exclusions and legal-advice restrictions. The current text should be distinguished from older statutory versions applied in cases.

**Other states’ software provisions.** [North Carolina General Statutes section 84-2.2](https://www.ncleg.gov/EnactedLegislation/Statutes/HTML/BySection/Chapter_84/GS_84-2.2.html) and [Texas Government Code section 81.101(c)](https://statutes.capitol.texas.gov/Docs/GV/htm/GV.81.htm#81.101) provide conditional software/publication treatment. They are legislative comparisons, not California exemptions.

The California statutory sections above are individually linked in the statutory source map. The State Bar publishes the [current professional rules](https://www.calbar.ca.gov/legal-professionals/rules/rules-of-professional-conduct). The cited public sources, retained opinions and underlying quotation records allow the legal claims to be checked without relying on the article’s interpretation alone.

### Additional authorities and sources carried into Version 2

The preceding guide retains all 73 baseline case records, including their exclusions and limitations. The following sources add affirmative support, current institutional context and practical evidence. They do not all have the same legal force.

**California Formal Opinion 1982-68.** An advisory opinion on computer-generated collection letters and assistance by a creditor-client’s employees. The nature of the task determines supervision; threatening legal action requires authorization in the particular case. It supports meaningful assistance, not automatic permission for every criteria-driven legal act. [Official opinion](https://www.calbar.ca.gov/sites/default/files/portals/0/documents/ethics/Opinions/1982-68.htm).

**California Formal Opinion 1988-97.** An advisory opinion allowing the ministerial signing of trust-account checks under direction while withholding discretion. It distinguishes execution from authority over funds and does not displace current trust-account rules. [Official opinion](https://www.calbar.ca.gov/sites/default/files/portals/0/documents/ethics/Opinions/1988-97.htm).

**California Formal Opinion 2015-193.** The eDiscovery competence opinion addresses technical understanding, competent assistance, appropriate testing and overall responsibility. It is a persuasive professional-duty bridge for process-level judgment, not an opinion construing SB 574 or every later generative workflow. [Official opinion](https://www.calbar.ca.gov/sites/default/files/2025-11/CAL%202015-193%20%5B11-0004%5D%20%2806-30-15%29%20-%20FINAL1.pdf).

**ABA Formal Opinions 512 and 08-451.** Opinion 512 addresses generative AI under the Model Rules, including the contract-summary example supporting task-sensitive checking. Opinion 08-451 concerns outsourcing legal and nonlegal support with continuing competence, supervision, confidentiality, disclosure, fees and unauthorized-practice responsibilities. They are persuasive comparisons; California’s rules and statute still govern the California question. [Opinion 512, especially pp. 3–4](https://www.americanbar.org/content/dam/aba/administrative/professional_responsibility/ethics-opinions/aba-formal-opinion-512.pdf); [Opinion 08-451](https://www.americanbar.org/content/dam/aba/publications/YourABA/201106_08451.authcheckdam.pdf).

**San Diego County Bar Opinion 2007-1.** A local advisory outsourcing opinion discussing assistance and professional safeguards. Human providers’ authorized arrangements are not automatically an AI statutory exception. [Opinion text](https://www.iusjuris.com/docs/2007_04_SanDiego_OutsourcingOpinion.pdf).

**D.C. Ethics Opinion 362 and UPL Opinion 21-12.** Opinion 362 directly addresses an eDiscovery vendor and the boundary between technical services and legal services. Its discussion of 21-12 is useful for identifying responsiveness and privilege-related work as potentially legal. Nonlawyer ownership and who supplies the service remain essential; the proposed cure is not simply that oversight legalizes every vendor arrangement. Opinion 362 was read directly; the original 21-12 document was not retrieved in this review. [D.C. Opinion 362](https://www.dcbar.org/for-lawyers/legal-ethics/ethics-opinions-210-present/ethics-opinion-362).

**Schulte v. LinkedIn Corp., No. 22-cv-00237-HSG (LB), ECF 203.** The June 30, 2026 order, filed July 1, records final GenAI responsiveness calls and sample quality control. It denies three identified discovery requests while requiring a search-string meet-and-confer. It is neither a general mandate to use GenAI nor a ruling on privilege classification or the future statute. [Order, especially pp. 2 and 4](https://cases.justia.com/federal/district-courts/california/candce/4%3A2022cv00237/390494/203/0.pdf).

**Da Silva Moore v. Publicis Groupe, 287 F.R.D. 182 (S.D.N.Y. 2012).** An important judicial acceptance of computer-assisted review in appropriate circumstances. Its protocol retained manual review of predicted-relevant documents and sampling of excluded material. It does not establish that all individual review can always be removed. [Opinion and protocol](https://openjurist.org/287/frd/182/moore-v-publicis-groupe).

**Dynamo Holdings Ltd. Partnership v. Commissioner, order of July 13, 2016.** The Tax Court applies reasonable inquiry rather than perfection and accepts a predictive-coding response on the facts. It also discusses *Rio Tinto PLC v. Vale S.A.*, 306 F.R.D. 125 (S.D.N.Y. 2015). The latter comparison is used through the reproduced passage in *Dynamo*; a full independent *Rio Tinto* opinion was not retrieved in this review. [Dynamo order, pp. 7–9](https://assets.ctfassets.net/jqxgjfvolqmr/7H8fXaoDKu5QSTqtIM1nsO/5b18cd65c6ec8774227b86187872654d/Dynamo_07_13_2016.pdf).

**Hyles and In re Viagra.** The 2016 orders discussed in Section 6 declined requests to compel predictive coding. They prevent the historical acceptance of TAR from being restated as a general requirement to use that method, much less a present general GenAI mandate. The underlying orders remain linked in the discovery discussion and prior source archive.

**Federal discovery and privilege rules.** Rules 26 and 16, including the amendments effective December 1, 2025, support early planning for privilege descriptions. Rule 26(g) addresses certifications after reasonable inquiry. FRE 502 distinguishes waiver protections and agreements; California CCP section 2031.285 supplies a state discovery claim-and-return procedure. These mechanisms have different conditions and do not make an adversary forget disclosed information. [FRCP 26](https://www.law.cornell.edu/rules/frcp/rule_26); [FRCP 16](https://www.law.cornell.edu/rules/frcp/rule_16); [FRE 502](https://www.law.cornell.edu/rules/fre/rule_502); [CCP § 2031.285](https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=CCP&sectionNum=2031.285.).

**Blanton v. Womancare, Inc., 38 Cal.3d 396 (1985).** Authority over the representation does not automatically include authority to surrender substantial client rights through arbitration. It strengthens the distinction between lawyer judgment and client authorization. [Majority opinion, pp. 403–408](https://law.justia.com/cases/california/supreme-court/3d/38/396.html).

**In re Attorney Discipline System, 19 Cal.4th 582 (1998).** Relevant to the judiciary’s role and the Legislature’s substantial role in professional regulation. It supports coordinated institutional work, not a categorical claim of exclusive power rendering SB 574 invalid. [Opinion, pp. 600–603](https://law.justia.com/cases/california/supreme-court/4th/19/582.html).

**Coastside Fishing Club v. California Resources Agency, 158 Cal.App.4th 1183 (2008).** Relevant to the limited use of a Governor’s signing statement as evidence of legislative intent. The proposed statement in Section 13 is a policy and interpretive invitation, not an amendment or binding judicial construction. [Opinion, p. 1196 fn. 7](https://app.midpage.ai/document/coastside-fishing-club-v-california-2244831).

**Current California AI materials.** The May practical guidance and the June second-round comment proposal are distinct documents with distinct status. The proposal’s competence and confidentiality wording is important to the current discussion; the public page records the June authorization and August comment deadline. Rule 10.430 regulates court policies and is distinct from Standard 10.80’s adjudicative guidance and the attorney statute. [Proposal page](https://www.calbar.ca.gov/public-comment/proposed-amendments-rules-professional-conduct-related-artificial-intelligence); [June clean/redline](https://www.calbar.ca.gov/sites/default/files/2026-06/Proposed-Amended-Rules-of-Professional-Conduct-1.1-1.4-1.6-3.3-5.1-and-5.3-clean-and-redline.pdf); [Title 10 rules, including rule 10.430](https://courts.ca.gov/system/files?file=file%2Froc-title-10_1.pdf).

**AB 1651, chapter 116 of 2026.** The authenticated chapter is a limited comparison concerning AI-content disclosure even after human review, with a January 1, 2028 operative date. It does not establish current State Bar production practices or confer permission under SB 574. [Chapter text](https://leginfo.legislature.ca.gov/faces/billPdf.xhtml?bill_id=202520260AB1651&version=20250AB165195CHP).

**The book and the authority-boundaries essay.** Ryan McDonough’s *Human Accountable for the Loop*, supplied by the user, provides the operational-accountability framework, examples and 24-test rubric discussed in Section 7. Those examples are attributed to the book rather than claimed as independently investigated incidents. Dazza Greenwood’s *Authority Boundaries for AI* connects enforceable tool permissions and professional decisions. Neither source is legal permission in itself. Supplied book; [Authority Boundaries for AI](https://www.dazzagreenwood.com/p/authority-boundaries-for-ai).

### Legislative analysis record

The full record matters more than a quotation detached from its version. These nine archived analyses were retrieved and reviewed in the preceding comparative research. Section 1 explains the principal chronology and discrepancies. The official index should be checked for later changes before a time-sensitive use.

| Analysis | Archived copy | Use in this report |
|---|---|---|
| Senate Judiciary, January 13 | 393832 | Earlier modeling history and purpose; predates July prohibition. |
| Senate Appropriations, January | 393907 | Fiscal and enforcement questions; estimates are not causes of action or realized costs. |
| Senate floor, January | 394063 | Earlier version context. |
| Assembly Judiciary, June 30 | 401406 | Proposal before the July 2 print. |
| Assembly Privacy, July 1 | 401874 | July-stage purposes and amendments. |
| Assembly Appropriations, August 4 | 403026 | Recognizes mandatory disclosure and the prohibition; discusses embedded tools. |
| Assembly floor, August 17 | 404227 | Compare summary to actual amended text. |
| Assembly floor, August 21 | 404775 | Summary errors should not displace operative language. |
| Senate concurrence, August 31 | 406070 | Late description and continuing AAA AI and mediation concerns. |

[Official analysis index](https://leginfo.legislature.ca.gov/faces/billAnalysisClient.xhtml?bill_id=202520260SB574).

<a id="v2-method"></a>

### How Version 2 was prepared and what the evidence can establish

This is an informed peer collaboration following earlier independent research. Codex and Claude exchanged their later analyses, including the original inquiry, book, memo, eDiscovery and COPRAC questions and the five supplied deep-research reports. They agreed to preserve 325 nominations, including material nominated by only one participant, before agreeing the revision plan. That is agreement on useful inclusion and qualified treatment, not a claim that every original assertion is true.

The earlier research executed 110 prescribed searches and tracked 73 case records, including the disclosed standalone exclusions. Version 2 retains that guide and adds sources and explanatory treatment. The five supplied reports are inputs to evaluate, not five independent legal votes. Models sharing an index can share omissions and mistakes. Pivotal propositions were checked against underlying opinions, statutes and official materials where identified; leads not fully checked remain labeled as such.

The report develops an affirmative interpretation and explains consequential alternatives. Operational designs and draft policy language are recommendations, not holdings.

Agreed preservation register · Agreed revision requests · New source checks and limitations · Baseline source audit · Baseline quotation provenance.

The earlier 55 activity examples, statutory source map and opinion archive manifest remain available alongside the expanded narrative. The item-to-destination record makes the preservation choices inspectable without adding research shorthand to the main discussion.
