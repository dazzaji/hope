# Long-Horizon Exercise: Attorney Judgment Policy

Use an agent to plan and complete a small, evidence-gated project. The exercise demonstrates the same control pattern used for longer projects: define the goal, write a durable sprint, stop at human review gates, and reserve final judgment for the human participant.

This exercise does **not** require Descrybe or multiple agents. It should take approximately 10-15 minutes.

## Scenario

ACME, Inc.'s fictional in-house legal team needs a one-page policy identifying when an attorney must personally exercise independent legal judgment in an AI-assisted process.

For this **toy teaching exercise only**, assume that California SB 574 has taken effect exactly as described in the supplied articles, without later legislation, judicial interpretation, or regulatory guidance. This premise is fictional and is not a statement of current law or legal advice.

Use only these research inputs:

- [Authority Boundaries for AI](https://www.dazzagreenwood.com/p/authority-boundaries-for-ai)
- [Thirteen Words Shape Legal AI](https://www.dazzagreenwood.com/p/thirteen-words-shape-legal-ai)
- [Overnight Cookbook](https://github.com/dazzaji/interlateral_agents/blob/main/docs/overnight-cookbook.md)

## Goal

Create a one-page toy policy for ACME, Inc.'s in-house legal team identifying when an attorney must personally exercise independent legal judgment in an AI-assisted process.

The policy should distinguish work an AI agent may prepare from decisions requiring attorney review, revision, approval, or action.

Success means the policy is concise, operational, traceable to the supplied sources, and leaves consequential legal decisions with an attorney.

## Start The Exercise

Open your agent in this repository and give it the following prompt:

```text
We are completing the long-horizon teaching exercise in projects/long_horizon.

Read:
- projects/long_horizon/README.md
- the Overnight Cookbook linked in that README, especially its guidance on choosing the smallest adequate process, evidence-gated milestones, and final human acceptance
- the two linked articles that are the exercise's only research inputs

Help me first review and, if needed, improve the proposed goal in the README. Ask only questions necessary to clarify the purpose, audience, deliverable, success criteria, constraints, and decisions requiring my judgment.

When I approve the goal, save it in projects/long_horizon/goal.md. Then write projects/long_horizon/sprint.md for completing the exercise as a short L0 solo run.

The sprint must have two human gates:

GATE 1 - POLICY ELEMENTS
Extract relevant principles from the two articles and create POLICY-ELEMENTS-DRAFT-1.md in this directory. Identify proposed policy rules, decisions reserved to attorneys, permitted agent work, escalation conditions, safeguards, and source support. Then STOP so I can review and edit the artifact. Do not draft the policy before I approve Gate 1.

GATE 2 - FINAL POLICY
After I approve the edited policy elements, create ACME-AI-JUDGMENT-POLICY.md in this directory. The policy must fit on approximately one page and implement the approved elements. Then STOP so I can approve, reject, or modify it. Do not declare final acceptance for me.

Before doing research or drafting either artifact, show me the proposed goal and sprint and wait for my approval.
```

## Initial Approval

Review the proposed `goal.md` and `sprint.md`. Confirm that they include:

- the stated audience and one-page deliverable;
- the three supplied inputs and no open-ended research assignment;
- separate research-extraction and policy-drafting phases;
- Gate 1 before the policy is drafted;
- Gate 2 before the work is considered accepted; and
- a clear boundary between work the agent may perform and decisions reserved for you.

When satisfied, tell the agent:

```text
I approve goal.md and sprint.md. Begin the authorized work and stop at Gate 1.
```

## Gate 1: Review The Policy Elements

Open `POLICY-ELEMENTS-DRAFT-1.md`. Review the source extraction and edit the file directly so it contains the high-level policy elements you actually want.

Consider:

- Did the agent extract the relevant principles accurately?
- Which decisions must remain with an attorney?
- Is any proposed rule too broad or too permissive?
- Are the escalation conditions and safeguards practical?
- Is each important element traceable to one of the supplied articles?
- What should be added, removed, or rewritten?

When satisfied, tell the agent:

```text
I have reviewed and edited POLICY-ELEMENTS-DRAFT-1.md. Treat my edited version as the approved policy architecture. Continue the sprint, draft the one-page policy, and stop at Gate 2.
```

## Gate 2: Exercise Final Judgment

Open `ACME-AI-JUDGMENT-POLICY.md` and decide whether it is fit for the fictional ACME team.

Consider:

- Does it implement the elements you approved at Gate 1?
- Is it understandable and operational?
- Are attorney decisions stated precisely?
- Does it distinguish preparation from judgment and commitment?
- Would ACME personnel know when to stop and escalate?
- Did the agent stay within the exercise's assumptions and sources?

You, not the agent, must **approve, reject, or modify** the policy. If revision is needed, edit the artifact or give the agent specific revision instructions and review the result again.

## The Pattern

- `goal.md` defines the intended outcome and how success will be recognized.
- `sprint.md` defines the phases, evidence, boundaries, and stopping points.
- Gate 1 lets the lawyer decide the policy architecture before prose is drafted.
- Gate 2 reserves final acceptance and professional judgment for the lawyer.

The agent researches, extracts, proposes, drafts, and checks. The human decides what the policy should contain and whether the resulting work is fit for use.

For more ambitious projects, the [Interlateral Agents](https://github.com/dazzaji/interlateral_agents/) project provides additional patterns for multi-agent collaboration, communication, review, and gatekeeping.
