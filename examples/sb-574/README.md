# Advanced HOPE Example — SB 574 Multi-Agent Legal Research

**A long-horizon, multi-agent research project: SB 574, Descrybe, Codex, Claude Code, and `peer-synthi`.** Project lead: Daniel "Dazza" Greenwood.

This is a worked example of what an ambitious HOPE project can look like when it runs well beyond a single prompt — two AI agents doing independent legal research, then challenging, correcting, and combining their work under human direction. It is included as a **historical research artifact and advanced workflow example**, not as legal advice, not as a statement of SB 574's current status, and not as a step-by-step tutorial.

> ### ▶ Start here: [**Read the full story — `CHRONICLE.md`**](CHRONICLE.md)
> A step-by-step narrative of how the human-directed, cross-provider research team actually worked — the best way to understand this example. The sections below are a shorter orientation.

## The question it investigated

California's SB 574 would make certain legal tasks expressly personal to a licensed attorney. The project asked what that means in practice for AI-native law firms: where the line falls between an attorney's *lawful use of AI assistance* and an improper *delegation* of professional judgment, and what that implies for supervision, disclosure, and the design of AI-native legal work. The research analyzed the **August 21, 2026** text of the bill.

## How the project worked (eight steps)

1. **A serious research brief.** The project defined the legal questions, seed authorities, searches, and desired outputs, giving both agents a common assignment.
2. **Two independent investigations through Descrybe.** Codex and Claude Code each researched the same questions through their own Descrybe integration. The research ultimately covered **110 prescribed searches** and tracked **73 case records**.
3. **First passes preserved before comparison.** Each agent's independent findings were frozen before either could see the other's — producing two genuine investigations rather than one echo.
4. **The agents challenged and improved each other's work.** They compared authorities, checked citations against the underlying passages, corrected errors, and tested whether cases actually supported the proposed arguments. Pivotal checks reached *outside* Descrybe on purpose — because two agents agreeing off the same database is not independent verification.
5. **`peer-synthi`: useful differences preserved.** Rather than average the two into a bland consensus, the project combined the strong contributions, fixed correctable mistakes, and *kept* consequential disagreements and differences in confidence — without manufacturing dissent or forcing agreement.
6. **The evidence base was expanded and pressure-tested.** Additional inputs — an original inquiry, a book and a memo, five further deep-research reports, and a concrete eDiscovery problem — were folded in. For Version 2 the agents preserved **325 nominated contributions** before deciding how to integrate or qualify each one.
7. **A readable final product was demanded.** When the first synthesis came back too dense, it was sent back for plain explanations, quotations, worked examples, and candid treatment of uncertainty; the agents then reviewed the revised deliverables.
8. **The research was connected to real decisions.** It informed a published article and professional-responsibility (COPRAC) contributions, and the practical concerns were tested with people working in eDiscovery.

## What `peer-synthi` is, in plain English

`peer-synthi` is a way to combine independent research from multiple agents *honestly*. Each agent's independent first pass is preserved. The peers then challenge and supplement one another. Useful differences — including disagreements and differences in confidence — are retained rather than smoothed away. And the final synthesis records, finding by finding, **what actually happened** to each material contribution: integrated, qualified, corrected, deferred, or rejected. The [reconciliation ledger](RECONCILIATION-LEDGER.md) is that record.

## How to inspect this example

You are not expected to read everything. To see what it is:

1. **Skim** the [full report](SB-574-MULTI-AGENT-RESEARCH-REPORT.md) — its headings and its "how it was prepared" method section — to feel the scale and quality of the final product.
2. **Spot-check** a few rows of the [reconciliation ledger](RECONCILIATION-LEDGER.md): find an `integrate` row, then a `correct` or rejected one, to see the agents preserving provenance and disagreement.
3. **Compare** the large internal research record against the concise published result — that gap is the point of the workflow.

## Files in this example

- **[CHRONICLE.md](CHRONICLE.md)** — the narrative walkthrough of the whole project, step by step. **Start here.**
- **[SB-574-MULTI-AGENT-RESEARCH-REPORT.md](SB-574-MULTI-AGENT-RESEARCH-REPORT.md)** — the full multi-agent research report (historical artifact, dated September 3, 2026).
- **[RECONCILIATION-LEDGER.md](RECONCILIATION-LEDGER.md)** — the finding-by-finding correction and integration record from the `peer-synthi` phase.
- **[SANITIZATION-REPORT.md](SANITIZATION-REPORT.md)** — how this public package was prepared from the private working files (what was changed and verified).

## Related reading

Dazza Greenwood's public article on this work: [*Thirteen Words Shape Legal AI*](https://www.dazzagreenwood.com/p/thirteen-words-shape-legal-ai).

---

*These materials demonstrate a multi-agent research **workflow**. They are a historical artifact and do not constitute legal advice, and multi-agent agreement does not guarantee correctness. Check the [current official bill history](https://leginfo.legislature.ca.gov/faces/billHistoryClient.xhtml?bill_id=202520260SB574) before relying on anything here about SB 574's status.*
