---
title: "AI and work"
description: "Analysis of how AI changes workflows, handoffs, knowledge use, decision rights, and the operating systems around work."
---


The smallest useful question about AI is whether it can complete a task.

The larger question is what happens to the workflow around that task.

A drafting assistant can save keystrokes while adding another review burden. An enterprise chatbot can improve access while hiding weak source ownership. An agent can automate handoffs while making it harder to see why a decision happened.

**AI changes work when it changes the operating path from intent to outcome, not merely when it produces output faster.**

That is the layer I care about.

## Stop measuring adoption by tool activity

Organizations can produce impressive AI activity without changing much work.

Employees attend prompt training. Teams create internal GPTs. Vendors add copilots to existing products. Usage dashboards climb. Pilot announcements multiply.

The harder questions remain:

- Which recurring workflow changed?
- Which step disappeared or improved?
- Which decision still belongs to a person?
- What evidence does the system use?
- Who can challenge the output?
- What happens after a failure?
- Did the organization improve the underlying process, or add AI on top of it?

Tool activity can show interest. It does not prove operational adoption.

The distinction matters because AI can automate a bad process just as efficiently as a good one.

## Move from task automation to workflow design

A useful AI workflow has boundaries.

It knows where information comes from, what the system may do, where human review matters, how exceptions move, and what happens to the output after generation.

That means the design unit should often be larger than the prompt.

Consider the difference:

**Task view:** Draft a product brief.

**Workflow view:** Intake the request, identify the approved source material, surface missing claims, draft within messaging constraints, route technical claims to the right reviewer, preserve citations, resolve changes, publish into the correct system, and create a maintenance obligation.

The model may participate in several steps. It should not quietly own the entire process.

This is the same operating principle behind my AI enablement work: build around the work people actually do, test where AI improves that work, then standardize what proves useful.

## Protect the decisions that require judgment

"Human in the loop" is too vague to be a design.

The useful question is which human, at which point, with what authority, using what evidence.

Some decisions are cheap to reverse. Others affect customers, employees, security, policy, money, or public claims. The workflow should reflect that difference.

Human review becomes meaningful when the reviewer can:

- see the source material
- understand what the system changed
- reject or correct the output
- escalate uncertainty
- stop the workflow
- preserve the reasoning behind a consequential decision

A reviewer who can only click approve is not exercising much judgment.

The goal is not to maximize manual intervention. It is to put intervention where the cost of being wrong justifies it.

## Make organizational context legible to AI

AI systems are only as useful as the context they can access and interpret.

That context is rarely clean.

Product truth may live in documentation. Commercial language may live in messaging guides. Exceptions may live in Slack. Policy may live in SharePoint. Customer context may live in a CRM. A subject-matter expert may know the most important limitation and never have written it down.

This is why AI adoption quickly becomes a knowledge-operations problem.

Before asking a model to reason across the organization, the organization needs stronger answers to source authority, ownership, lifecycle, permissions, and provenance.

AI does not eliminate the need for information architecture.

It makes the consequences of weak information architecture easier to see.

## Design for traceability

When AI participates in meaningful work, the system should preserve enough information to reconstruct what happened.

That may include:

- the initiating request
- source material used
- important system instructions or constraints
- generated output
- human changes
- approvals
- exceptions
- downstream actions
- corrections after use

The required depth depends on the stakes. Not every draft needs a forensic record.

But if an AI-assisted workflow creates a customer commitment, changes a policy, updates a knowledge source, or triggers an external action, "the model did it" is not an operating explanation.

Traceability is part of accountability.

## Treat agents as participants in the work system

Agentic systems make these questions sharper because the system can do more than answer.

An agent may retrieve information, create artifacts, update systems, send messages, schedule work, open tickets, or trigger another agent. Once the system can act, architecture and governance become collaboration concerns.

The design needs to account for:

- identity
- permissions
- scope
- source authority
- action boundaries
- approval
- observability
- rollback
- escalation

An agent should not receive broader organizational power merely because automation is convenient.

The useful standard is the same one we should apply to people and services: the system gets the access it needs for the job, its actions are visible at the appropriate level, and someone owns the consequences.

## Use AI to reduce coordination tax, not human understanding

Many knowledge-work processes contain coordination overhead that contributes little value.

People copy status between tools. Rewrite the same context for different audiences. Search repeatedly for source material. Turn meetings into summaries. Reformat decisions. Chase reviewers. Reconstruct why something changed.

AI can remove part of that tax.

The risk appears when the organization removes the understanding along with the overhead.

A workflow that generates a summary is useful. A workflow that causes nobody to read the source behind a consequential decision may not be.

The operating question is therefore not how much human work AI can remove.

It is **which human work carries judgment, learning, accountability, or context that the organization still needs.**

## Research questions

This section will track questions such as:

- Which AI use cases change workflows rather than merely accelerate tasks?
- Where should organizations require source-backed output?
- What does meaningful human intervention look like at different risk levels?
- How should agent permissions map to business roles and workflows?
- When does AI reduce coordination cost, and when does it add review debt?
- How should organizations capture corrections so the source system improves?
- What becomes a new system of record when AI spans multiple platforms?
- How should collaboration platforms expose provenance and agent activity?

AI will continue to produce new interfaces.

The more durable subject is the operating system underneath them.
