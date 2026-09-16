# Sanitization Report — SB 574 Public Package

This documents how the public package in this directory was prepared from three private working files, what was changed, and the verification run on the result. It reproduces no removed sensitive text; it names categories and locations only.

## 1. Source files and original SHA-256 hashes

These three files were treated as immutable sources. They were **not** modified, renamed, or copied into this package.

| Source file | SHA-256 (before) | SHA-256 (after) | Modified? |
|---|---|---|---|
| `574-example.md` | `0232d8846276bd68198e516841d5e5584fdcfb69b34af8e545e25c2039da2368` | *(unchanged)* | No |
| `reconciliation.md` | `1acfa57ef86304274920228717c3b49387660f5e4ef3a97f9b7c2031a41e8f31` | *(unchanged)* | No |
| `AI-Native-Law-Firms-and-SB-574-Line-1556.md` | `af1b6bac33c517b6e963c277aa231af2659633096cd90fcef44537d8b2a2e281` | *(unchanged)* | No |

Re-hash after the run matched all three byte-for-byte (Check 1 below).

## 2. Public files produced

- `README.md` — new public case study, built from `574-example.md` plus the process facts, rewritten in neutral third person.
- `SB-574-MULTI-AGENT-RESEARCH-REPORT.md` — the full report, **surgically sanitized** (private/local spans edited only; legal analysis unchanged).
- `RECONCILIATION-LEDGER.md` — the full reconciliation record with a new orientation intro; ledger body reproduced verbatim.
- `SANITIZATION-REPORT.md` — this file.

## 3. Categories of change

**README.md** (from `574-example.md`)
- Removed the private-audience framing (a personal first-name greeting).
- Converted second-person narration ("You started…") to neutral descriptions ("The project started…").
- Added title, one-paragraph question statement, plain-English `peer-synthi` explanation, a "How to inspect this example" section, links to the other package files, the published article, and the official bill history.
- Preserved the eight-step process story and the quantitative facts (110 searches, 73 tracked records, two independent agents, 325 nominations).

**SB-574-MULTI-AGENT-RESEARCH-REPORT.md** (from the full report) — surgical edits only:
- Added a prominent **Historical research artifact** notice immediately below the title, linking to the current official bill history.
- Neutralized audience-specific attribution: "a practical legal and policy analysis for Dazza Greenwood" and "Prepared for Dazza Greenwood by…" were rewritten to neutral project attribution identifying Dazza Greenwood as project lead.
- Removed the sentence stating that local links open on the author's machine and that a future public edition should replace them (this *is* that edition).
- Removed the sentences referencing a private working session record and unpublished draft outputs held for review.
- Rewrote the practitioner-commentary passage to remove two individual names and to present the material generically as practitioner commentary and research leads, without implying any named person supplied unreliable material.
- Converted every local-machine hyperlink to plain-text citation (see §4).
- **The substantive legal analysis, conclusions, tables, qualifications, alternative interpretations, source discussions, dates, and disclosed uncertainty were left unchanged.** Word count is essentially identical to the source (~34.6k words).

**RECONCILIATION-LEDGER.md** (from `reconciliation.md`)
- Added an orientation section (what the ledger is, the stable-ID families, the four columns, what dispositions mean, and that rejected/corrected rows show review, not failure).
- Ledger body preserved verbatim — every row, disposition, and confidence difference retained. No corrections, failed source gates, deferred items, or exclusions removed.

## 4. Local links removed / replaced

- **30 absolute local hyperlinks** (targets that were absolute paths into a private local filesystem), spread across 21 lines of the report, were **converted to plain-text citations**. The visible citation text (case names, analysis titles, register names) was preserved exactly; only the dead local hyperlink was removed.
- **Public URLs substituted for local links: none.** Per the project decision to avoid inventing or hunting URLs, no new links were added. Pre-existing public links already present in the source (leginfo bill text/history/analysis index, Stanford SCOCAL, the Descrybe public opinion bucket, ABA opinion PDFs, and similar) were left in place untouched — 139 such public links remain in the report.

## 5. Passages omitted for privacy / audience / reputational reasons

| Location (source) | Category | Handling |
|---|---|---|
| Example (opening) | Private-audience framing (personal first-name greeting) | Removed in README rewrite |
| Report (title block) | Audience-specific attribution | Rewritten to neutral project attribution (Dazza = project lead) |
| Report method appendix | Sentence about links opening on the author's local machine | Sentence removed |
| Report method appendix | Reference to a private working session record | Sentence removed |
| Report method appendix | Reference to unpublished draft outputs held for review | Sentence removed |
| Report practitioner-commentary passage | Two individual names grouped with "unverified posts/quotations" | Names removed; passage genericized |

No credentials, tokens, keys, email addresses, phone numbers, or private correspondence were found in the sources (confirmed by scan — Check 3).

## 6. Unresolved publication concern (for Dazza's optional decision)

- Three published legal sources that were formerly local links — **Lopez v. Ledesma, 12 Cal.5th 848 (2022)**, the **August 4 Appropriations analysis**, and the **August 31 concurrence analysis** — are now plain-text citations with **no live link**, because a verified public URL was not asserted (no invented/guessed URLs). This is fully compliant and reader-safe. *Optional future enhancement:* a verified public link could be added for each (the leginfo analysis index is already linked elsewhere in the report). Not blocking.

## 7. Confirmation: sources not modified

Re-hashed after the run; all three match §1 exactly. No source file was renamed, overwritten, deleted, or copied into this package.

## 8. Verification results

Commands were run against the finished package; summarized results:

| # | Check | Command (summary) | Result |
|---|---|---|---|
| 1 | Source hashes unchanged | `shasum -a 256` on the 3 sources | **PASS** — all 3 match §1 |
| 2 | Forbidden strings absent | `grep -rIF` for each scrubbed token — the local-path tokens, the private greeting names, the two individual names, and the working-session / draft-output phrases (tokens held in an external checklist, not reproduced here) | **PASS** — 0 matches across the entire package |
| 3 | No credentials/emails/phones | regex scan for emails, `sk-`/`ghp_`/PEM/`xox`, phone patterns | **PASS** — none found |
| 4 | Relative links resolve in-package | link resolver over all `.md` | **PASS** — all resolve |
| 5 | External links use https | scan for `http://` | **PASS** — 0 non-https external links |
| 6 | README links correct | report, ledger, article, bill history | **PASS** — all present |
| 7 | Report has visible historical banner | grep for the notice | **PASS** |
| 8 | Ledger has reader-orientation section | grep for the intro | **PASS** |
| 9 | No source file modified | re-hash (same as #1) | **PASS** |

*Prepared as part of the SB 574 public-package sanitization. This report describes the publication process only and is not legal advice.*
