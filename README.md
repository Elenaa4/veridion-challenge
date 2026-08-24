# veridion-challenge

This repository contains my solution for the Veridion Internship Challenge — Autonomous Systems on Mars.

Challenge

The scenario considers an autonomous aircraft operating on Mars that detects a dust storm approximately 12 minutes ahead on its current route, while communication with Earth has a delay.

The aircraft therefore needs to evaluate the situation and make a decision autonomously.

My Approach

I approached the problem as a challenge under uncertainty, incomplete information, time constraints and limited energy.

The proposed system structures the decision process in three stages:

Evidence Reliability → Safety Feasibility → Best Feasible Action

The design focuses on:

* evaluating the reliability of potentially conflicting sensor signals;
* separating observations, inferences and confidence;
* accounting for uncertainty in the predicted location;
* determining when waiting for Earth is no longer operationally useful;
* preserving sufficient electrical energy for a recoverable safe state;
* rejecting unsafe actions before optimizing between feasible alternatives;
* continuously the decision as new information becomes available.

Design Document

The document contains:

* Part 1 — Problem Analysis
* Part 2 — Proposed Solution

It includes the assumptions, open questions, engineering, architecture, data flow, decision logic, pseudocode, validation strategy, limitations and proposed implementation approach.

AI Usage

AI tools were used during the exploration process to challenge assumptions, identify edge cases and help structure the analysis. Suggestions were evaluated and adapted rather than treated as requirements.

Author

Georgiana-Elena Dumitru
