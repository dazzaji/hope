# A Research Team Across AI Providers: The SB 574 Chronicle

**How a human-directed team used independent research, agent communication, source verification, and repeated synthesis to turn a large body of material into an inspectable research report.**

Project lead: Daniel “Dazza” Greenwood. This account describes the September 2026 research workflow. The accompanying legal report is a historical research artifact; this chronicle makes no claim about the bill’s present status.

The project began with a short sentence in California’s SB 574 and a substantial research question: how should the boundary between legal work, AI assistance, and delegation be understood? Answering it required cases, statutes, professional rules, technical context, and concrete examples of how legal work gets done.

Dazza organized the work as a sequence of investigations and reviews. Different AI systems contributed through different routes. Two working agents conducted the core legal research, exchanged findings, and reviewed the combined result. In a parallel effort, Dazza commissioned five broader deep-research reports, then brought those reports back to the working agents for detailed extraction and another synthesis cycle. At each stage, he set the questions, expanded the evidence base, and judged whether the result was useful enough to move forward.

The result was a substantial research foundation with citations, explanations, alternative interpretations, and a record of how the findings survived review.

## The team and its tools

| Participant or tool | Role in this project |
|---|---|
| **Dazza Greenwood** | Directed the assignment, supplied materials and practical questions, commissioned additional research, and set the standards for usefulness and clarity. |
| **OpenAI Codex and Anthropic Claude Code** | Conducted the core Descrybe investigations, preserved their first passes, compared and checked findings, developed the combined analysis, and reviewed revisions. Codex maintained the integrated research artifacts; both contributed substantive work and review. |
| **Perplexity, Grok, Claude, ChatGPT, and Gemini research reports** | Supplied five additional perspectives gathered separately by Dazza, expanding the evidence and questions beyond the core legal-retrieval assignment. |
| **Descrybe integrations** | Gave the working agents direct access to legal search, case identification, opinion passages, quotation checks, treatment information, and opinion retrieval. |
| **Interlateral Agents** | Supplied cross-agent communication and reusable coordination skills, including the new `peer-synthi` workflow developed during this project. |
| **Primary public sources and durable project files** | Supported independent source checks, preserved evidence, and made revisions and completion claims inspectable. |

The distinction between the two working agents and the five supplied research reports matters. Grok contributed through the broader research material; this account does not describe Grok as a third live Descrybe peer. The project combined direct agent collaboration with human-directed research across multiple providers.

## 1. Start with a research protocol that can be executed

The starting brief broke the assignment into phases with named questions, seed cases, specific searches, and required outputs. The research covered:

- The relevant codified text and the definition of the practice of law.
- Software and automated services in legal-practice cases.
- Attorney delegation and supervision, plus useful comparisons outside that setting.
- Arbitrator decisionmaking and AI-citation cases.
- Professional-services and insurance questions.
- Verification of selected authorities and concrete activity classifications.

That structure gave both agents a common assignment while leaving room to pursue useful additional leads. It also made coverage visible: the team could distinguish a completed search phase from a promising but unfinished line of inquiry.

The completed core research recorded **110 prescribed searches**. Those were search queries, not the total number of tool calls: resolving citations, retrieving passages, checking quotations, examining treatment, and collecting opinions required additional work.

**Gate:** define the scope and evidence standard before treating a fluent answer as a completed investigation.

## 2. Give the agents a way to work together

Before combining the research, the team needed a dependable way to coordinate across providers and desktop applications.

The agents joined the **Interlateral Agents** communications system with distinct identities and separate working locations. Important handoffs used direct peer delivery together with a durable communications record. A receipt from the other agent confirmed that a request had actually been read; merely writing a message into a file did not establish that work had begun.

Separate work areas preserved ownership of originals. An assigned integrator maintained the combined deliverables, allowing both agents to contribute without competing to overwrite the same document.

Dazza also identified a requirement that shaped the collaboration: a valuable finding should survive even if only one agent discovered it, and a meaningful difference of interpretation should remain visible without turning the report into a running argument between models.

The team reviewed existing coordination skills and developed **`peer-synthi`** for that purpose. The new skill was reviewed, refined, and merged into the public Interlateral Agents repository. Its installation included the repository’s different skill-discovery locations and updates to the catalog and guides, so the workflow could be found from different agent environments. The existing `peer-superset` skill remained available unchanged. See the [public skill addition](https://github.com/dazzaji/interlateral_agents/pull/2).

`peer-synthi` distinguishes approval of a report’s faithful representation from agreement with every interpretation in it. That allows a research assignment to finish with useful alternatives intact. The [skill itself](https://github.com/dazzaji/interlateral_agents/blob/main/.agent/skills/peer-synthi/SKILL.md) is reusable for research, technical designs, proposals, and other advisory work.

**Gate:** establish who is participating, where each person’s work lives, who integrates it, and how a peer confirms receipt and review.

## 3. Investigate independently, then preserve the originals

Codex and Claude Code researched through their own Descrybe integrations. They worked from the same protocol but could select different follow-up searches, identify different useful authorities, and draw different conclusions from the material.

During the independent stage, coordination concerned operational matters such as access, progress, and service limits. The substantive first passes were preserved before release for comparison. File hashes—digital fingerprints of their contents—recorded which originals had been frozen.

This gave the later review something concrete to compare. A reader could distinguish an agent’s original finding from an idea acquired through its peer or developed during joint analysis. Later additions went into supplements rather than being inserted retrospectively into the independent originals.

The investigators shared a legal index, so independence of analysis did not mean independence of the underlying source collection. The workflow accounted for that with primary-source checks outside the shared retrieval system.

**Gate:** preserve substantive first-pass findings before exchanging them; label later shared discoveries honestly.

## 4. Turn retrieved material into evidence

The agents worked through several distinct questions for the authorities they wanted to use:

1. Is this the intended case, with the correct court, date, citation, and disposition?
2. Can the relevant opinion text be retrieved?
3. Does the quoted language match the source?
4. Does its surrounding context support the proposition being advanced?
5. Does later treatment or a different procedural setting limit that use?

These questions exposed the difference between finding a citation and establishing support for an argument. A real case can still be described too broadly. A quotation can be accurate while the inference drawn from it is too strong. An empty forward-citation result establishes what that search returned, not that no later authority exists.

For pivotal propositions and coverage gaps, the agents checked official bill materials, statutes, rules, and published opinions outside Descrybe. The project retained source records and distinguished original court PDFs from generated copies or clearly identified reproductions.

The combined core register eventually tracked **73 case records**: **71 used affirmatively and two retained as disclosed standalone exclusions**. Preserving an excluded record made its limitation inspectable without promoting it into supporting authority.

**Gate:** retain the source and its limitations, and check what it supports before relying on it.

## 5. Compare findings and build a stronger combined analysis

Once the originals were released, the agents compared contributions item by item. Each material finding received a stable identifier and a recorded destination or disposition.

Compatible findings could be merged. A useful discovery from one peer could be added. An overbroad proposition could be narrowed. A claim with insufficient support could remain a research lead or be excluded. Where an interpretation or confidence difference mattered to the answer, the synthesis explained it.

The [public reconciliation ledger](RECONCILIATION-LEDGER.md) shows this work. It includes source-identity corrections, distinctions between a case’s holding and a possible analogy, qualifications on the scope of decisions, and preserved differences in confidence.

The team also developed new combined ideas. For example, bringing legal definitions together with supervision doctrine and technical workflow descriptions made it possible to ask separate questions about the nature of a task, its assignment, and the authority for performing it. New synthesis was identified and reviewed as new reasoning, rather than presented as a finding both agents had independently reached.

The final core analysis retained two consequential reservations concerning interpretive confidence and the predictive value of an analogy. Their presence was compatible with completion because the report represented them fairly.

**Gate:** give every material contribution a reasoned treatment; review new combined reasoning as well as the original findings.

## 6. Keep a long-running assignment coordinated

The project crossed multiple sessions and encountered shared service limits. The agents exchanged status and throttling information, respected retry instructions, and coordinated outstanding requests. Saved progress and explicit lists of missing materials allowed the work to resume without restarting the whole investigation.

They also distinguished missing evidence that might affect a conclusion from missing archival convenience copies. Where an authorized public source supplied an opinion, the record identified that source rather than claiming a previously unsuccessful retrieval had succeeded.

Scheduled follow-ups supported continuity, while important peer actions still required acknowledgments. A passive desktop inbox did not, by itself, wake its agent; human relays were used when needed. This was sustained, supervised work with explicit checkpoints.

The Interlateral [Overnight Cookbook](https://github.com/dazzaji/interlateral_agents/blob/main/docs/overnight-cookbook.md) provides the broader operational playbook for this kind of assignment: durable state, clear ownership, verified handoffs, bounded repair, and honest completion conditions. It now references `peer-synthi`. The cookbook is a living resource; its full current contents should not be read as a list of every mechanism used in this particular run.

**Gate:** confirm actual receipt and progress, preserve restartable work, and distinguish an operational delay from a substantive evidence gap.

## 7. Make the research understandable and test it against examples

Dazza made readability an explicit acceptance criterion. The research needed to explain the questions and authorities to a reader who had not followed the investigation.

The team developed a longer explanatory report with direct answers, short source quotations, contextual explanations, and practical examples. Claude contributed practical system-design scenarios; Codex integrated them with the legal analysis; peer review tested both their support and their clarity.

The core work included **55 activity scenarios and control-failure examples**. These helped test abstract distinctions against concrete tasks and workflows. An example could illuminate a proposed interpretation while remaining clearly identified as an application of the analysis, rather than a court-approved design.

Readability review also changed presentation: unexplained case lists became explanations of what the cases contributed, and quotations were accompanied by context. The detailed audit records remained available behind the more readable report.

**Gate:** require an explanation a new reader can use, with examples that preserve the limits of the supporting law.

## 8. Dazza opens a second research track

The legal retrieval established a foundation, but the assignment also needed broader context: technical capabilities, actual workflows, economic implications, professional guidance, and the history and structure of the relevant public materials.

Dazza conducted a separate research effort using **Perplexity, Grok, Claude, ChatGPT, and Gemini**, producing five deep-research reports. These explored material beyond what the Descrybe-centered investigation alone could supply. They complemented the legal research and supplied further legal leads as well.

He also brought forward his original inquiry, an initial memorandum, a book on human accountability for AI, and a concrete eDiscovery example. That broadened the questions from the meaning of individual legal authorities to how the law and technology might interact in real, high-volume work.

The working agents were instructed to examine each report for useful facts, ideas, distinctions, sources, and implications—and explain what each could contribute. A report could provide a valuable idea even where a date, citation, or degree of certainty needed correction.

**Gate:** expand the evidence base deliberately, while treating model-generated research as material to investigate rather than authority in itself.

## 9. Extract the useful material in several passes

The second synthesis was a substantial assignment of its own. The team processed the new material through a sequence designed to prevent valuable contributions from disappearing during summarization.

### Pass A: Review each report and the earlier materials

The agents produced analyses identifying useful contributions and their relevance, along with necessary corrections and additional checks. They also considered how those contributions should change the existing analysis.

### Pass B: Exchange the completed analyses

Each working agent read the other’s analysis of the expanded source set. This phase was explicitly informed collaboration: the agents had already exchanged earlier research and did not claim a new blinded investigation.

### Pass C: Agree on what to preserve

The team assembled **325 nominations: 219 from Codex and 106 from Claude**. These were nominations for useful inclusion, including overlapping contributions and qualified leads—not 325 independently verified facts or 325 unique discoveries.

Each item recorded its origin, the useful content, its qualification or evidence status, and its intended role. An idea nominated by only one participant could survive. Overlapping ideas could share a final explanation while retaining their separate provenance.

The peers agreed on this preservation inventory before revising the report. That agreement meant the useful contribution would receive a fair treatment; it did not certify every assertion in the source report.

### Pass D: Convert the inventory into revision requests

The agents agreed on **18 revision requests**. These organized the material into coherent changes: strengthen source treatment, clarify distinctions, develop practical examples, revise overconfident formulations, and improve the report’s structure.

Each request was linked to the material it was meant to carry forward. This made the revision plan reviewable before the long report was changed.

### Pass E: Integrate, qualify, and trace

The team revised the report around the questions a reader needed answered. Related contributions were combined; promising but unverified ideas remained labeled; new sources received appropriate checks. The destination record accounted for all 325 nominations, and the revised source guide retained the substantive treatment of all 73 earlier case records.

This was the payoff from the extraction work: a coherent report supported by a preservation map, rather than a stack of disconnected summaries.

**Gate:** agree on preservation, then agree on revisions, then verify that the delivered report accounts for the material.

## 10. Review the files actually being delivered

The final review covered substantive representation, source support, qualifications, and readability. Review comments identified specific repairs, and the repaired versions were checked again where necessary.

Approvals were tied to file hashes, so the record identified the version actually reviewed. Earlier versions were preserved. The closeout distinguished three separate facts: whether the agreed work was complete, whether review was confirmed, and whether material alternatives remained.

That distinction allowed the project to finish with genuine uncertainty accurately represented. Completion meant the agreed research and review had been done; it did not claim that legal uncertainty had disappeared or that agreement between models guaranteed correctness.

The resulting research foundation was available for Dazza’s own analysis and communication. Human direction remained central throughout: selecting the questions, adding sources, demanding clearer explanations, and deciding how to use the findings.

## The scale, and where to inspect the result

| Recorded milestone | What it measures |
|---|---|
| **2 working research peers** | Codex and Claude Code, with separate first passes and reciprocal review. |
| **110 prescribed searches** | Coverage of the core protocol; additional retrieval and verification calls were separate. |
| **73 case records** | The retained case register, including two disclosed standalone exclusions. |
| **55 scenarios** | Concrete activities and control-failure examples used to test the analysis. |
| **5 additional deep-research reports** | Dazza’s broader research inputs from multiple AI providers. |
| **325 nominations** | Contributions preserved for Version 2, including overlap and qualified leads. |
| **18 agreed revision requests** | The reviewed plan for integrating the expanded research. |

Start with the [full research report](SB-574-MULTI-AGENT-RESEARCH-REPORT.md), especially its final methodology section. Then sample the [reconciliation ledger](RECONCILIATION-LEDGER.md) to see how findings were integrated, corrected, qualified, or retained as alternatives. The [example README](README.md) provides a shorter orientation.

The public package contains selected outputs, rather than every internal working file or communication. This chronicle draws on the project’s protocol, phase logs, reconciliation and review records, and Version 2 preservation and completion records. It presents the research process without reproducing private communications or internal discussions.

For adapting the method, the useful pattern is: **a shared brief; independent investigations; preserved originals; source-based cross-review; a contribution inventory; an agreed revision plan; a readable synthesis; and explicit review of the delivered version.** Multiple providers supplied different findings and perspectives. The process made those differences usable—and left a record that a human could inspect.
