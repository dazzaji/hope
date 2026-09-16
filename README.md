# HOPE

Hands-On Projects and Experimentation.
[GitHub](https://github.com/dazzaji/hope) Version | [Website](https://dazzaji.github.io/hope/) Version

## The HOPE Lab

Learn more about this free hands-on session at here [TimeAndTokens.ai/HOPE](https://timeandtokens.ai/HOPE).

## Legal research exercise

First ensure you have a Descrybe account.  Then ensure you (or your agent) have [installed and tested the Descrybe integrations](https://computationallaw.org/materials/descrybe26.html) for Claude Code, Codex, or your preferred agent.

The current Descrybe exercise is in [`projects/legal_research/`](projects/legal_research/).

1. Open your file-capable agent in this repository's root directory.
2. Confirm that the Descrybe Legal Engine integration is available to that agent.
3. Ask the agent to read `projects/legal_research/MEMO.md` and `projects/legal_research/PROMPT.md` and describe the two-step assignment.
4. Give the agent the instructions in `PROMPT.md`.
5. Review the Step 1 citation-check report. When satisfied, reply `CONTINUE` to begin Step 2.
6. Review the research brief, proposed second paragraph, and the three opinions saved in the run folder's `cases/` subdirectory.

The agent creates a fresh run folder under `projects/legal_research/work/`. Participant work is local and is not part of the course repository.
