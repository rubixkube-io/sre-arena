# RFC 0001 — Foundation & Vision

Status: Draft

---

# Introduction

Operational systems are entering a new phase.

AI-native tooling is increasingly being integrated into:
- incident response
- observability workflows
- infrastructure operations
- root cause analysis
- runtime diagnostics
- remediation systems

Across the ecosystem, new platforms are emerging rapidly.

However, evaluation methodologies for these systems remain fragmented and inconsistent.

Most demonstrations today rely on:
- isolated workflows
- private benchmarks
- synthetic environments
- narrowly scoped scenarios
- non-reproducible evaluations

As a result, it is difficult to meaningfully compare, validate, or reason about operational intelligence systems under realistic runtime conditions.

SRE Arena is proposed as an open initiative to explore shared approaches for evaluating AI-native operational systems.

---

# Motivation

Operational environments are fundamentally different from traditional benchmark domains.

Infrastructure systems are:
- stateful
- distributed
- dynamic
- noisy
- partially observable
- operationally ambiguous

An operational AI system is not simply retrieving information or completing deterministic tasks.

It is expected to:
- investigate incidents
- correlate signals
- reason across systems
- operate with incomplete context
- communicate findings clearly
- prioritize safe actions
- adapt to evolving runtime conditions

Traditional evaluation approaches often fail to capture these characteristics.

SRE Arena aims to encourage evaluation methodologies that better reflect real operational complexity.

---

# Vision

The long-term goal of SRE Arena is to help establish a shared and community-driven foundation for operational intelligence evaluation.

This may eventually include:
- reproducible runtime scenarios
- shared operational datasets
- transparent evaluation methodologies
- scenario replay systems
- remediation validation approaches
- operational reasoning benchmarks
- public evaluation reports

The initiative is intended to evolve collaboratively with participation from across the ecosystem.

---

# Principles

## Operational Realism

Evaluation environments should reflect realistic operational conditions rather than isolated scripted workflows.

## Reproducibility

Scenarios, methodologies, and environments should be reproducible and openly inspectable.

## Safety-Aware Evaluation

Operational intelligence systems should be evaluated not only on actionability, but also on correctness, explainability, confidence, and safe decision-making.

## Vendor Neutrality

SRE Arena is intended to support open collaboration across the broader operational ecosystem.

## Transparency

Evaluation methodologies and assumptions should remain open to discussion and community contribution.

---

# Areas Of Exploration

Initial exploration areas may include:
- incident investigation quality
- root cause analysis
- runtime context handling
- observability reasoning
- operational decision traceability
- remediation safety
- escalation behavior
- multi-system operational workflows

These areas are intentionally broad and expected to evolve through discussion and experimentation.

---

# Infrastructure Scope

SRE Arena is intended to remain infrastructure-agnostic.

Potential operational environments may include:
- cloud infrastructure
- distributed systems
- Kubernetes environments
- virtual machines
- networking systems
- observability stacks
- CI/CD workflows
- APIs and service dependencies
- databases and messaging systems
- hybrid operational environments

---

# Non-Goals

SRE Arena is not intended to become:
- a vendor marketing leaderboard
- a closed evaluation framework
- a replacement for operational expertise
- a single-company initiative
- a static benchmark suite

The project is intended to remain collaborative, exploratory, and community-oriented.

---

# Open Questions

Several important questions remain open:

- What constitutes meaningful operational realism?
- How should runtime ambiguity be represented?
- How should remediation safety be evaluated?
- How should operational reasoning quality be measured?
- How should long-running investigations be modeled?
- How should stateful memory and historical context be incorporated?
- How can evaluation environments remain reproducible while reflecting real operational complexity?

These questions are expected to evolve through RFCs, discussion, experimentation, and community participation.

---

# Participation

SRE Arena is currently in its early foundation stage.

Contributions, discussions, and RFC proposals are welcome from:
- practitioners
- infrastructure teams
- researchers
- platform engineers
- observability vendors
- operational tooling companies
- open-source contributors

The goal is to collaboratively shape meaningful approaches for evaluating operational intelligence systems.
