IPC-TEM Benchmark 1.0
Task Execution & Method Stability Benchmark for General AI Systems
📌 Overview

IPC-TEM Benchmark 1.0 is designed to evaluate the execution capability of AI systems:

ability to perform multi-step tasks

resilience under changing constraints

stability and consistency of reasoning methods

recovery from interruptions

self-correction and task-management skills

adherence to user requirements and protocol constraints

clarity and structure of execution plans

TEM = Task Execution & Methodology

This benchmark is complementary to IPC-Benchmark v0.1, which measures structural intelligence.
Together, they form a dual evaluation system:

Benchmark	Focus	Analog
IPC-Benchmark v0.1	Structure, reasoning, rules, abstraction	“Intelligence quotient (IQ)”
IPC-TEM 1.0	Execution, stability, compliance, workflow	“Executive function (EF)”

IPC-TEM-Benchmark/
  README.md
  spec_v1.0.md
  tasks/
    TEM_001.json
    TEM_002.json
    TEM_003.json
    TEM_004.json
    TEM_005.json
  scoring/
    rubric.md
    score_sheet.csv

Design Goals

Evaluate execution stability, not knowledge recall.

Measure method robustness, especially under dynamic or ambiguous environments.

Test rule compliance, including constraints, forbidden operations, and multi-level requirements.

Reveal error patterns (looping, hallucination, rule-breaking, inconsistency).

Assess recovery ability after interruption or contradictory instructions.

Verify modular thinking (planning → execution → self-checking → revision).

📊 Core Dimensions (4 Axes)
1. Task Decomposition (Planning IQ)

clarity of subtask division

dependency identification

correct ordering

resource estimation

avoiding missing steps

2. Method Stability (MS Index)

does the model stick to a chosen method?

does it drift or self-contradict?

can it update method without breaking coherence?

3. Constraint Compliance (CC Score)

obeying user constraints

avoiding forbidden actions

abiding by formatting rules

maintaining separation of steps

4. Recovery & Self-Correction (RS Factor)

detecting own mistakes

revising without being asked

recovering from interruptions

gracefully handling incomplete or conflicting inputs
