---
title: "Mental models for organising work: task lists versus application management"
description: Getting to grips with the growing complexity of the service
date: 2026-04-15
---

## Background

Task lists have been the primary way the service organises work for users since early in its development. At that stage, the service was smaller in scope and notifications functionality did not exist, so a task list approach was a reasonable fit — it gave users a clear view of what needed doing and in what order.

As the service has grown, task lists have accumulated more information and more action types. They are beginning to show the strain of being asked to do too much. This prompted us to step back and examine whether the task list is still the right organisational device, or whether something closer to an application management model would serve users better as the service matures.

## The problem with task lists at scale

Task lists work well when the scope of work is bounded and sequential. They become problematic when:

- The number of items grows beyond what a user can meaningfully scan
- Items vary significantly in type, urgency, or ownership
- Users return to the service at different intervals with different intentions
- Notifications introduce a parallel channel that duplicates or fragments the task list's function

In our case, all of these conditions now apply. The task list is no longer giving users a clear signal about what matters — it is giving them volume.

## Different users, different mental models
Not all users relate to the service in the same way, and this has a direct bearing on how they think about organising their work.

**Researchers and applicants** tend to think in terms of their own application. Their mental model is centred on a single piece of work they own end-to-end. For them, a task list can feel appropriate during active submission, but becomes confusing when the application is under review and there is nothing actionable to do — yet items persist.

**Coordinators and research office staff** often manage multiple applications on behalf of others. Their mental model is closer to a caseload or inbox — they need to see across applications, understand status at a glance, and pick up work that belongs to different people or studies. A single task list does not map well to this.

**Reviewers and approvals staff** have a different relationship again. They are not owners of the application; they are actors within a process. Their concern is with what has been assigned to them and by when. They are also likely to be lower-frequency users, returning when notified rather than checking in regularly.

## Ownership as a complicating factor

Ownership in research applications is rarely simple. A single application may involve a chief investigator, a sponsor, a research office, and one or more reviewing bodies — each with a legitimate stake in different parts of the process, and each with different expectations about what "their" view of the work should look like.

A task list implicitly assumes a single owner working through a linear set of actions. An application management model can accommodate shared ownership, delegated actions, and status visibility without requiring every stakeholder to see the same view.

## What an application management model might offer
Rather than organising the service around tasks to be completed, an application management approach organises it around the application as the primary object. Users see their applications, their status, and the actions available to them in context — rather than a decontextualised list of things to do.
This model also integrates more naturally with notifications. Rather than notifications duplicating the task list, they point users back into the application at the right moment and place.

## Questions this work needs to answer

- How do different user groups currently understand and navigate the task list? What workarounds have emerged?
- At what point does an application move from "active work" to "monitored progress" — and does the organisational device need to change at that point?
- How do users with caseload-style needs currently manage across multiple applications?
- What is the right level of task visibility for lower-frequency users who arrive via notification?

## Next steps

- Review existing research for evidence of task list pain points across user groups
- Map the different ownership models present in the service and identify where task lists fit poorly
- Sketch alternative organisational patterns for testing — including application-centric views and mixed models
- Run comparative concept testing with researcher, coordinator, and reviewer participants
