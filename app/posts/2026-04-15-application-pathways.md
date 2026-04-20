---
title: Designing approval routes for the new research application system
description: A summary of the thinking behind research application routings for approvals
date: 2026-04-15
---

## Background

As part of the work to replace IRAS, we needed to design how applicants would be directed through the correct approval route for their study. The current IRAS system requires applicants to navigate this themselves, which is a known source of confusion and error.

The new system has an opportunity to do this more intelligently — routing applicants based on what we know about their study, compiling multiple question sets into a conditional logic driven solution that removes duplication and streamlines the application process.

## What we explored

**A single unified route** — presenting applicants with one linear journey regardless of approval type, with differences handled behind the scenes or at the point they become relevant.

**Conditional routing based on study type** — using answers to earlier questions to determine which approval route applies, and surfacing them for strategic completion of questions required

## What we decided
We converged on conditional routing based on study type, with the ability to view all required questions as well.

This decision was informed by user research, which showed that applicants — particularly less experienced researchers — struggle to identify which approvals their study requires. Asking them to choose a route upfront introduces a decision point that many are not equipped to make confidently.

Input from approvals specialists was also critical. They helped us understand the logic that determines route eligibility, which gave us confidence that the right route could be determined from study characteristics already captured earlier in the application.

Technical feasibility was a factor too. The conditional logic required is achievable within the constraints of the new system architecture.

## What this means for the design

Applicants will not be asked to select an approval route directly. Instead, the system will determine the appropriate route based on their answers and present only the relevant sections and review steps.

This reduces cognitive load for applicants and should help reduce errors caused by applicants selecting the wrong route or missing required approvals.

##Next steps

- Validate the routing logic with approvals specialists against a range of real study types
- Test the conditional journey with researchers in usability sessions
- Document any edge cases where manual triage may still be needed
