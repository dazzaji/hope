# Descrybe Exercise: Check a Draft, Then Research Both Sides

Help me complete the two tasks in the accompanying fictional teaching memo:

- **Argument 1 is written and cited.** Check its citations, quotations, and descriptions of what the cases say.
- **Argument 2 is only a proposed topic sentence.** Find cases that support its assertion of copyright protection **and cases that oppose, narrow, or weaken it**. Then propose a completed second paragraph.

Treat "original editorial judgment" as a claim to test, not an established fact.

## Sources and files

Use the **Descrybe Legal Engine** for case identification, primary-opinion passages, quotation verification, and visible-treatment checks. Memory and generated summaries are leads, not proof. Use focused retrieval; do not save bulk tool responses or any full opinions except the three required for the case packet below.

Read `projects/legal_research/MEMO.md` when working from the repository root; it is beside this prompt file. If its location is ambiguous or inaccessible, ask me for its location or text and stop. **Do not read the instructor's answer key or earlier exercise answers.**

Preserve `projects/legal_research/MEMO.md` and `projects/legal_research/PROMPT.md`. Create a fresh run folder inside `projects/legal_research/work/` and save all outputs there. Do not overwrite earlier work.

Assume a **federal district court in New York**. Do not invent directory features or copying facts. Identify missing facts and reason conditionally. If Descrybe is unavailable, report that limit rather than substitute unsupported conclusions.

## Required case packet

Create a `cases/` subdirectory inside the fresh run folder. Obtain and save the full opinions for exactly these three cases so the reviewing lawyers can inspect the authorities themselves:

1. *Feist Publications, Inc. v. Rural Telephone Service Co.*, 499 U.S. 340 (1991).
2. *Baker v. Selden*, 101 U.S. 99 (1880).
3. *Matthew Bender & Co. v. West Publishing Co.*, 158 F.3d 674 (2d Cir. 1998).

Resolve each case through Descrybe first and record its Descrybe case ID. Use Descrybe's case-PDF route when available. If Descrybe does not provide a downloadable PDF, use an official or otherwise reliable public judicial source and record that source. Save the actual opinion PDFs with clear filenames; do not substitute summaries, headnotes, commentary, or a different opinion with a similar caption.

Also create `cases/README.md` listing each citation, court and year, Descrybe case ID, local filename, source URL, and retrieval status. If an opinion cannot be downloaded, mark it `MISSING`, preserve the best direct source link, and continue without claiming that the file exists. Do not collect every other case found during the exercise.

Retrieve *Feist* and *Baker* while completing Step 1. Retrieve *Matthew Bender* while completing Step 2.

## Step 1 - Check Argument 1

1. Resolve every citation, including short forms. Separately check identity, reporter citation, court, year, and pinpoint where possible.
2. Verify every quotation and whether the opinion supports each attributed proposition. A real case or matching quotation does not by itself establish support.
3. Classify propositions as **SUPPORTED**, **CONTRADICTED**, **NOT ESTABLISHED**, or **INCONCLUSIVE**. Distinguish contradiction from insufficient evidence.
4. Give supported corrections. Flag unverified pinpoints and unresolved discrepancies; a failed quotation search alone does not prove fabrication.

Save `STEP-1-CITE-CHECK.md` in the fresh run folder with a findings summary and this table:

| Citation/use as written | Identity and pinpoint check | Quotation check | Proposition and result | Correction | Source evidence and limits |
| --- | --- | --- | --- | --- | --- |

Use a separate row for each citation use or distinct proposition, including repeated uses of one case. Support substantive findings with a primary-opinion excerpt of **no more than 20 words**, Descrybe case ID, link or reproducible locator, and material limits. Identify metadata as metadata.

**Respond in chat in no more than 150 words:** explain the main problems in plain English, identify unresolved checks, and link the report. **Stop and wait for CONTINUE.** Do not research or draft Argument 2 yet.

## Step 2 - Research Argument 2 and develop the paragraph

After I reply **CONTINUE**:

1. Test this assertion: **the directory's selection and categorization justify copyright protection**. Start with Supreme Court and Second Circuit authority.
2. Search deliberately for both supporting and opposing or limiting cases. Aim for **two on each side**; do not pad with weak cases or count one case twice to manufacture balance. A case may help on one issue and hurt on another.
3. Examine creative selection and arrangement, plus comprehensive coverage, routine verification, conventional categories, insufficient creativity, and merger (where protecting expression would effectively protect the underlying idea).
4. Keep **copyrightability** separate from **infringement**. Explain narrow protection, but do not invent a copying dispute or let infringement replace the main question.
5. Retrieve primary passages for material legal propositions. Distinguish holdings from dicta, majority reasoning from dissents, and binding from persuasive authority. Check the actual result: a remand is not a final win.
6. Run Descrybe's bounded case-status check on every authority actually relied upon in the proposed paragraph. Preserve cautions; this is **not a comprehensive citator**. Generic tool weight labels do not determine binding force in this forum.
7. Draft **one completed Argument 2 paragraph of 120-180 words**, with citations. Revise or qualify the topic sentence if warranted. Address the strongest material limitation and missing facts. Do not force a favorable conclusion or invent pinpoints.

### Save the detailed work

Save `STEP-2-RESEARCH-BRIEF.md` in the fresh run folder with:

- An assessment of no more than 150 words.
- An authority table: supporting/limiting role, citation, court, rule, actual holding or procedural outcome, relevance, primary excerpt of no more than 20 words, Descrybe ID/link or locator, and treatment limitations.
- The strongest argument for protection and strongest counterargument.
- Up to five material factual questions.
- The proposed paragraph and why it changes the original assertion.
- Compact retrieval notes and unresolved issues sufficient to check the analysis.

Save the same paragraph separately as `PROPOSED-ARGUMENT-2.md` in the fresh run folder. Leave the source memo unchanged.

### Final chat response

Use **no more than 350 words total**, excluding file links:

**What I did** - Recap the Step 1 problems and Step 2 research.

**What the research means** - Give a plain-English verdict. Name the authorities that support the assertion **and those that oppose or weaken it**, explain why, and identify material unresolved limits.

**Proposed Argument 2** - Show the complete proposed paragraph, not just a link.

**Detailed work** - Link both reports, the proposed-paragraph file, and `cases/README.md`.

Keep tables and detailed research in the files. The chat response must make sense without opening them.
