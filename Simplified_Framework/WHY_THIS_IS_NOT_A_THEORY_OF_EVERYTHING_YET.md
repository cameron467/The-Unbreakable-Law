# What Is Known, What Must Be Reconstructed, and What Is Still Open

- **Layer:** Simplified Framework
- **Status:** Plain-English scientific map
- **Last updated:** 3 October 2026

This page shows the structure of the scientific problem in a compact way.

The project is not starting from zero. It begins with two successful parts of modern physics:

- **quantum physics**, which works extremely well for microscopic phenomena;
- **relativity / gravity**, which work extremely well for spacetime and gravitation in their tested regime.

The open question is whether both come from a deeper common source.

## The overall picture

```mermaid
flowchart LR

    A["Established science"]
    B["Must be reconstructed"]
    C["Current Parent picture"]
    D["Assumed / imported"]
    E["Open / not established"]

    A ~~~ B
    B ~~~ C
    C ~~~ D
    D ~~~ E

    classDef known fill:#2ea043,stroke:#d8dee4,stroke-width:2px,stroke-dasharray:6 4,color:#ffffff;
    classDef required fill:#1f6feb,stroke:#d8dee4,stroke-width:2px,stroke-dasharray:6 4,color:#ffffff;
    classDef candidate fill:#8957e5,stroke:#d8dee4,stroke-width:2px,stroke-dasharray:6 4,color:#ffffff;
    classDef assumed fill:#bf8700,stroke:#d8dee4,stroke-width:2px,stroke-dasharray:6 4,color:#ffffff;
    classDef open fill:#30363d,stroke:#d8dee4,stroke-width:2px,stroke-dasharray:6 4,color:#ffffff;

    class A known;
    class B required;
    class C candidate;
    class D assumed;
    class E open;
```

```mermaid
flowchart TB

    Q0["ESTABLISHED SCIENCE<br/>Quantum physics works"]

    Q1["KNOWN QUANTUM FEATURES<br/>superposition<br/>interference<br/>noncommuting observables<br/>entanglement<br/>probabilities"]

    Q2["MUST BE RECONSTRUCTED<br/>A deeper Parent must reproduce<br/>successful quantum behaviour"]

    Q3["QUANTUM-SIDE REQUIREMENTS<br/>state structure<br/>observable structure<br/>composition of systems<br/>dynamics<br/>physically meaningful subsystems"]

    R0["ESTABLISHED SCIENCE<br/>Relativity / gravity works"]

    R1["KNOWN RELATIVITY / GR FEATURES<br/>relativistic spacetime<br/>causal structure<br/>gravity as spacetime behaviour<br/>GR in its tested regime"]

    R2["MUST BE RECONSTRUCTED<br/>A deeper Parent must reproduce<br/>successful spacetime / gravity behaviour"]

    R3["RELATIVITY-SIDE REQUIREMENTS<br/>effective space<br/>causal spacetime<br/>gravity / GR limit<br/>same spacetime seen by matter"]

    P0["CURRENT PARENT IDEA<br/>One deeper rule structure<br/>could underlie both forks"]

    P1["CURRENT HAMILTONIAN ROUTE<br/>Search for a serious Parent candidate<br/>HAM programme<br/>HAM3 is a live candidate"]

    P2["WHAT THE PARENT SHOULD HAVE<br/>genuine quantum structure<br/>nontrivial interactions<br/>room for subsystem structure<br/>room for emergent geometry<br/>no hand-inserted spacetime answer"]

    A1["ASSUMED / IMPORTED IN CURRENT CANDIDATES<br/>ordinary quantum formalism<br/>chosen carrier algebra<br/>some composition structure<br/>family label N"]

    O1["OPEN<br/>correct final Parent"]
    O2["OPEN<br/>derived physical subsystems"]
    O3["OPEN<br/>entanglement from Parent-derived subsystems"]
    O4["OPEN<br/>emergent space from Parent response"]
    O5["OPEN<br/>relativistic spacetime and GR limit"]
    O6["OPEN<br/>full quantum–gravity overlap"]

    Q0 --> Q1
    Q1 --> Q2
    Q2 --> Q3

    R0 --> R1
    R1 --> R2
    R2 --> R3

    Q3 --> P0
    R3 --> P0

    P0 --> P1
    P1 --> P2

    P2 --> A1

    P2 --> O1
    P2 --> O2
    P2 --> O3
    P2 --> O4
    P2 --> O5
    P2 --> O6

    classDef known fill:#2ea043,stroke:#2ea043,color:#ffffff;
    classDef required fill:#1f6feb,stroke:#1f6feb,color:#ffffff;
    classDef candidate fill:#8957e5,stroke:#8957e5,color:#ffffff;
    classDef assumed fill:#bf8700,stroke:#bf8700,color:#ffffff;
    classDef open fill:#30363d,stroke:#8b949e,color:#ffffff;

    class Q0,Q1,R0,R1 known;
    class Q2,Q3,R2,R3 required;
    class P0,P1,P2 candidate;
    class A1 assumed;
    class O1,O2,O3,O4,O5,O6 open;
```
## The problem in one sentence

The project knows a lot about the **behaviour that must be recovered**, but not yet the **deeper mechanism that produces it**.

## The two known branches

### Quantum branch

Established science already tells us that a successful deeper theory must eventually account for:

- quantum states;
- superposition;
- interference;
- noncommuting observables;
- quantum probabilities;
- composition of systems;
- entanglement;
- the successful quantum dynamics already seen in experiment.

### Relativity / gravity branch

Established science already tells us that a successful deeper theory must eventually account for:

- effective space and time;
- relativistic causal structure;
- gravitational behaviour;
- General Relativity in the regime where it already works;
- agreement across different kinds of matter about the same effective spacetime.

## What both branches demand from a deeper Parent

A deeper Parent would need to support both kinds of reconstruction.

| Requirement | Why it matters | Status |
|---|---|---|
| Quantum structure | Needed to recover known microscopic physics | **Partly present in current candidate route** |
| Composition / subsystem structure | Needed to define real parts and entanglement | **Open** |
| Testable response | Needed so later checks examine what the Parent actually does | **Partial / open** |
| Emergent space-like behaviour | Needed to connect to the geometry side | **Open** |
| Relativistic spacetime | Needed to reach relativity rather than only ordinary space | **Open** |
| Gravity / GR limit | Needed to recover known gravity | **Open** |
| Probe-independence | Needed so spacetime is not specific to one chosen sector | **Open** |
| Quantum–gravity overlap | Needed so both branches can coexist in one framework | **Open** |
| Full closure | Needed for the final project goal | **Open** |

## The current Parent / Hamiltonian picture

The project is testing the possibility that one deeper Parent might underlie both branches.

One live route toward that Parent is the **Hamiltonian programme**.

The current leading live candidate in that route is **HAM3**.

### What the current route already has

| Property | Current status |
|---|---|
| Genuine quantum structure | **Present** |
| Noncommuting observables | **Present** |
| Unitary quantum dynamics | **Present** |
| Nontrivial interaction structure | **Present** |
| Explicit Hamiltonian | **Present** |
| Serious Parent search programme | **Active** |
| HAM3 as a live candidate | **Yes** |
| Final accepted Parent #2 | **No** |

So HAM3 is not an empty placeholder. It is a real mathematical candidate.

## What is currently assumed or imported

The current route still begins with some ingredients rather than deriving them.

Examples include:

- ordinary quantum formalism;
- the chosen carrier algebra;
- some composition structure;
- the family label \(N\);
- some measurement / operational assumptions.

That is not automatically bad.

The important rule is simply:

> **What is imported should not later be described as though it was derived.**

## What seems algebraically available

There is a middle category between “pure assumption” and “fully derived result”.

Some things appear to be **mathematically available in principle**, even though they are not yet physically demonstrated.

| Algebraically available possibility | Current status |
|---|---|
| Nontrivial subsystem structure may be possible | **Possible in principle** |
| Entanglement may be possible if meaningful subsystems are derived | **Possible in principle** |
| A geometry-like description may arise from suitable large-scale response | **Possible in principle** |
| Quantum behaviour and geometry may coexist in one regime | **Possible in principle** |

This is encouraging, but it is still weaker than a real derivation.

## What is still open

The main unresolved questions are:

- What is the correct final Parent?
- Is the Hamiltonian route the right route?
- If so, what is the correct Hamiltonian?
- How are physically meaningful subsystems produced?
- How does entanglement arise between those subsystems?
- How does space emerge?
- How does relativistic spacetime emerge?
- How does gravity emerge?
- Why do different kinds of matter see the same effective spacetime?
- How do quantum physics and gravity coexist and interact correctly?
- Can one deeper rule structure close all of these gaps at once?

## A useful distinction

The project uses four different categories.

| Category | Meaning |
|---|---|
| **Established** | Already known from successful science |
| **Must be reconstructed** | Any deeper theory would have to recover this |
| **Assumed / imported** | Put into the current candidate rather than derived |
| **Open** | Not yet demonstrated or established |

That distinction is important because it helps stop the project from overstating what it has actually achieved.

## TL;DR

Quantum physics and relativity are already established.

That means the project already knows a great deal about the **target behaviour** any deeper theory must reproduce.

The current project picture is that a deeper Parent may exist, and the Hamiltonian programme is one route being used to search for it. HAM3 is a serious live candidate in that search.

Some important ingredients are already present in the current route, especially genuine quantum structure and nontrivial interactions.

But the biggest tasks remain open: meaningful subsystems, entanglement from those subsystems, emergent space, relativistic spacetime, gravity, and the final closure between the quantum and gravitational branches.

In short:

> the project knows much more about the **destination** than it knows about the **deeper mechanism that gets there**.
