# What Is Known, What Must Be Rebuilt, and What Is Still Open

- **Layer:** Simplified Framework
- **Status:** Plain-English scientific map
- **Last updated:** 3 October 2026

## The problem

We already have two successful descriptions of nature:

- **Quantum physics** — works extremely well for microscopic phenomena.
- **Relativity / gravity** — works extremely well for spacetime and gravitation in their tested regimes.

The project asks whether both could come from **one deeper model**.

## The overall map

```mermaid
flowchart LR

    A["Established science"]
    B["Must be rebuilt"]
    C["Current deeper-model picture"]
    D["Put in at the start"]
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

    Q0["ESTABLISHED<br/>Quantum physics works"]
    R0["ESTABLISHED<br/>Relativity / gravity works"]

    Q1["MUST BE REBUILT<br/>quantum states<br/>probabilities<br/>interference<br/>entanglement<br/>quantum dynamics"]

    R1["MUST BE REBUILT<br/>space and time<br/>relativistic cause and effect<br/>gravity<br/>General Relativity<br/>shared spacetime"]

    P0["CURRENT IDEA<br/>One deeper model may underlie both"]

    P1["CURRENT CANDIDATE SEARCH<br/>Build explicit mathematical models<br/>HAM3 is one live candidate"]

    P2["A SUCCESSFUL MODEL NEEDS<br/>real quantum behaviour<br/>nontrivial interactions<br/>meaningful parts<br/>room for spacetime to emerge<br/>no hidden spacetime answer"]

    A1["PUT IN AT THE START<br/>ordinary quantum rules<br/>chosen mathematical ingredients<br/>some combination rules<br/>model-size label"]

    O1["OPEN<br/>correct deeper model"]
    O2["OPEN<br/>meaningful physical parts"]
    O3["OPEN<br/>entanglement between those parts"]
    O4["OPEN<br/>emergent space"]
    O5["OPEN<br/>relativistic spacetime"]
    O6["OPEN<br/>gravity / GR"]
    O7["OPEN<br/>full quantum + gravity closure"]

    Q0 --> Q1
    R0 --> R1

    Q1 --> P0
    R1 --> P0

    P0 --> P1
    P1 --> P2

    P2 --> A1

    P2 --> O1
    P2 --> O2
    P2 --> O3
    P2 --> O4
    P2 --> O5
    P2 --> O6
    P2 --> O7

    classDef known fill:#2ea043,stroke:#2ea043,color:#ffffff;
    classDef required fill:#1f6feb,stroke:#1f6feb,color:#ffffff;
    classDef candidate fill:#8957e5,stroke:#8957e5,color:#ffffff;
    classDef assumed fill:#bf8700,stroke:#bf8700,color:#ffffff;
    classDef open fill:#30363d,stroke:#8b949e,color:#ffffff;

    class Q0,R0 known;
    class Q1,R1 required;
    class P0,P1,P2 candidate;
    class A1 assumed;
    class O1,O2,O3,O4,O5,O6,O7 open;
```

## What we already know

### Quantum physics

Established science already shows:

- superposition;
- interference;
- quantum probabilities;
- entanglement;
- non-classical measurement behaviour;
- successful quantum dynamics.

### Relativity / gravity

Established science already shows:

- space and time form spacetime;
- cause and effect obey relativistic limits;
- gravity is tied to spacetime;
- General Relativity works extremely well in its tested regime;
- different kinds of matter agree on the same effective spacetime to very high accuracy.

## What a deeper model must rebuild

```mermaid
flowchart LR

    Q["Quantum side"]
    P["Deeper model"]
    G["Spacetime / gravity side"]

    Q --> P
    G --> P

    P --> Q2["Recover quantum behaviour"]
    P --> G2["Recover spacetime and gravity"]

    classDef side fill:#2ea043,stroke:#2ea043,color:#ffffff;
    classDef parent fill:#8957e5,stroke:#8957e5,color:#ffffff;
    classDef target fill:#1f6feb,stroke:#1f6feb,color:#ffffff;

    class Q,G side;
    class P parent;
    class Q2,G2 target;
```

A successful deeper model must eventually recover both sides.

| Quantum side | Spacetime / gravity side |
|---|---|
| quantum states | effective space and time |
| quantum probabilities | relativistic cause and effect |
| interactions | gravity |
| composition of systems | General Relativity where tested |
| entanglement | common spacetime for matter |

## What the current candidate route already has

The technical project calls the proposed deeper structure the **Parent**.

One live candidate is **HAM3**.

You do not need the technical details here. For this page, HAM3 is simply:

> **one explicit quantum model being tested as a possible deeper starting point.**

| Property | Status |
|---|---|
| Genuine quantum description | **Present** |
| Non-classical observables | **Present** |
| Quantum evolution | **Present** |
| Nontrivial interactions | **Present** |
| Explicit mathematical model | **Present** |
| Final accepted deeper model | **No** |

## What is put in at the start

These are **assumed**, not derived:

- ordinary quantum rules;
- the chosen mathematical starting structure;
- some rules for combining ingredients;
- a label controlling model size.

That is allowed.

The important rule is:

> **Do not call something "derived" if it was put in at the start.**

## What the mathematics seems to allow

These are **possible in principle**, but not yet demonstrated physically:

- meaningful subsystems may be recoverable;
- entanglement may then arise between those subsystems;
- a geometry-like description may emerge from large-scale behaviour;
- quantum behaviour and geometry may coexist.

## What is still open

```mermaid
flowchart TB

    A["Correct deeper model"]
    B["Meaningful physical parts"]
    C["Entanglement between those parts"]
    D["Emergent space"]
    E["Relativistic spacetime"]
    F["Gravity / General Relativity"]
    G["Quantum + gravity together"]
    H["Full closure"]

    A --> B
    B --> C
    A --> D
    D --> E
    E --> F
    C --> G
    F --> G
    G --> H

    classDef open fill:#30363d,stroke:#8b949e,color:#ffffff;
    class A,B,C,D,E,F,G,H open;
```

Still unresolved:

- the correct deeper model;
- whether HAM3 survives serious testing;
- physically meaningful subsystems;
- entanglement between those derived subsystems;
- emergent space;
- relativistic spacetime;
- gravity / General Relativity;
- the correct quantum–gravity overlap;
- full closure from one deeper rule.

## The key distinction

| Category | Meaning |
|---|---|
| **Established** | Already known from successful science |
| **Must be rebuilt** | Any deeper theory has to reproduce it |
| **Present in candidate** | Exists in the current model |
| **Put in at the start** | Assumed rather than derived |
| **Possible in principle** | Algebra allows a route, but physics is not demonstrated |
| **Open** | Not yet established |

## TL;DR

- **Quantum physics is known.**
- **Relativity / gravity are known.**
- A deeper model must recover both.
- The project has explicit candidate models.
- HAM3 already has genuine quantum structure and interactions.
- Important ingredients are still assumed rather than derived.
- Meaningful subsystems, emergent space, relativistic spacetime, gravity, and full quantum–gravity closure remain open.

> **We know much more about the behaviour that must come out than we know about the deeper rule that produces it.**
