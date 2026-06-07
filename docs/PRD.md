# Product Requirements Document (PRD)

## Product Name

AdQour Quantum Copilot

Version: V1 (Summer 2026 MVP)

Founder: Adarsh T

---

# 1. Executive Summary

AdQour Quantum Copilot is an AI-powered educational and development platform designed to help beginners learn, understand, debug, optimize, and experiment with quantum circuits.

Current quantum platforms such as IBM Quantum, Qiskit, and Xanadu provide powerful simulation capabilities but assume users already understand quantum computing concepts. Beginners often struggle to understand what a circuit does, why a circuit works, and how individual gates affect quantum states.

AdQour Quantum Copilot aims to act as a cognitive translation layer between complex quantum systems and human understanding.

The platform combines:

* Quantum circuit simulation
* AI-powered explanations
* Circuit simplification
* Reverse engineering
* Error detection
* Interactive learning support

into a unified beginner-friendly experience.

---

# 2. Problem Statement

Quantum computing tools are powerful but intimidating.

Common beginner problems include:

* Difficulty understanding gate operations
* Inability to interpret state vectors
* Lack of contextual explanations
* Limited educational guidance
* Optimization systems acting as black boxes
* No clear connection between circuits and real-world applications

Existing platforms answer:

"What is the output?"

Users often need answers to:

"Why does this work?"

"What is this circuit trying to achieve?"

"What should I learn next?"

---

# 3. Vision

To become the AI copilot for quantum computing education.

Long-term vision:

Allow anyone, regardless of mathematical background, to design, understand, optimize, and learn quantum circuits through natural language and interactive guidance.

---

# 4. Target Users

## Primary Users

### Beginner Quantum Students

* Undergraduate students
* First-time quantum learners
* Self-taught developers

Needs:

* Explanations
* Visualization
* Learning support

---

### Computer Science Students

Needs:

* Experimentation
* Interactive learning
* Project development

---

### AI/ML Engineers Exploring Quantum Computing

Needs:

* Faster onboarding
* Concept translation
* Practical understanding

---

# 5. Core Value Proposition

Current Platforms:

"Build quantum circuits."

AdQour Quantum Copilot:

"Understand quantum circuits."

Core differentiation:

* AI explanations
* Circuit-to-purpose translation
* Beginner-focused visualizations
* Optimization reasoning
* Learning guidance

---

# 6. User Stories

## Circuit Creation

As a beginner,

I want to create a quantum circuit visually,

so that I can experiment without memorizing syntax.

---

## Circuit Understanding

As a learner,

I want step-by-step explanations,

so that I understand what each gate is doing.

---

## Reverse Engineering

As a student,

I want to paste a circuit and learn its purpose,

so that I can understand existing quantum algorithms.

---

## Optimization

As a learner,

I want optimization suggestions explained,

so that I learn why circuits can be simplified.

---

## Error Detection

As a beginner,

I want warnings when I make mistakes,

so that I learn proper circuit design practices.

---

# 7. MVP Scope (Version 1)

## Feature 1: Circuit Builder

Users can:

* Add qubits
* Add gates
* Visualize circuits

Supported Gates:

* H
* X
* Y
* Z
* CNOT
* SWAP
* Measure

---

## Feature 2: Quantum Simulation

Using Qiskit backend.

Outputs:

* State vector
* Measurement probabilities
* Final state

---

## Feature 3: AI Circuit Explanation

Input:

Circuit

Output:

* Step-by-step explanation
* Gate descriptions
* Final outcome explanation

Explanation Levels:

* Beginner
* Intermediate
* Advanced

---

## Feature 4: Circuit Simplification

Detect:

* X·X = I
* H·H = I
* Redundant measurements
* Basic gate cancellations

Provide:

* Suggested simplifications
* Explanations

---

## Feature 5: Reverse Engineering Mode

Input:

Circuit

Output:

* Identified purpose
* Concept description
* Associated quantum concepts

Examples:

* Bell State
* GHZ State
* Teleportation
* SWAP

---

## Feature 6: Why It Matters

Every explanation includes:

Applications

Example:

Bell State →

* Quantum teleportation
* Superdense coding
* Quantum networking

---

## Feature 7: State Evolution Visualizer

Show:

Before Gate

After Gate

Probability changes

State changes

in beginner-friendly language.

---

## Feature 8: Quantum Mistake Detector

Detect:

* Incorrect measurement ordering
* Redundant gates
* Common beginner mistakes

Explain:

* What is wrong
* Why it matters
* Suggested fix

---

# 8. Out of Scope (V1)

The following are intentionally excluded:

* User authentication
* Cloud accounts
* Hardware execution
* Quantum error correction
* Custom transpilers
* Custom simulators
* Progress tracking
* Multiplayer collaboration
* Mobile application

---

# 9. V2 Roadmap

## Natural Language → Circuit

Example:

"Create a Bell State"

System generates circuit automatically.

---

## Quantum Copilot

Context-aware suggestions:

* Explain circuit
* Visualize state
* Optimize circuit
* Learn mathematics
* Convert to hardware gates

---

## Interactive Learning Mode

Quiz-driven exploration.

User predicts outcomes before seeing answers.

---

## Gate Knowledge Base

Detailed explanations for every gate.

---

## Multi-Level Teaching System

Beginner

Intermediate

Advanced

Research

---

# 10. Future Vision

## Learning Trajectory Engine

Adaptive teaching system.

Tracks user understanding.

Personalized learning paths.

---

## Algorithm Recognition Engine

Detect:

* QFT
* Grover's Algorithm
* Phase Estimation
* Teleportation
* Variational Algorithms

---

## Circuit-to-Purpose Translator

Large-scale semantic analysis of arbitrary circuits.

---

## AI Research Assistant

Explain:

* Quantum concepts
* Papers
* Algorithms
* Mathematics

---

# 11. Technical Architecture

Frontend

* React
* TypeScript
* TailwindCSS

Backend

* FastAPI
* Python

Quantum Layer

* Qiskit

AI Layer

* LLM API
* Prompt orchestration

Data Storage

* SQLite (MVP)

Deployment

* Vercel (Frontend)
* Render/Railway (Backend)

---

# 12. High-Level System Flow

User

↓

Circuit Builder

↓

Backend Orchestrator

↓

Qiskit Simulation

↓

Results

↓

AI Explanation Engine

↓

Visualization Layer

↓

User Interface

---

# 13. Success Metrics

Technical

* Successful simulation rate >95%
* Explanation latency <10 seconds

User

* User understands circuit purpose
* User understands gate operations
* User can simplify circuits using recommendations

Project

* Working MVP
* Public GitHub repository
* Documentation
* Demo video
* LinkedIn launch post

---

# 14. MVP Completion Criteria

Version 1 is considered complete when a user can:

1. Create a circuit
2. Simulate it
3. Receive an explanation
4. View state evolution
5. Receive optimization suggestions
6. Detect mistakes
7. Reverse engineer supported circuits

without requiring prior quantum computing expertise.
