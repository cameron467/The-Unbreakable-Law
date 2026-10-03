# Parent–Decoder Disagreement Protocol

- **Layer:** Project
- **Status:** Methodology
- **Last updated:** 3 October 2026

A future Parent and a project decoder may disagree. That disagreement must not automatically be interpreted as "the Parent is wrong."

Possible causes include:

- the Parent is wrong;
- the decoder is wrong;
- the decoder is being applied outside its valid regime;
- the Parent has not yet reached the effective regime the decoder is designed to recognise;
- the interface supplied to the decoder is incomplete or nonphysical.

## Classification

| Outcome | Meaning |
|---|---|
| **INCOMPATIBLE WITH ESTABLISHED PHYSICS** | The candidate contradicts a well-established external requirement in a regime where that requirement is known to apply |
| **UNRESOLVED MISMATCH** | Parent and decoder disagree, but the decoder, regime or interface is not secure enough to identify the cause |
| **COMPATIBLE SO FAR** | No contradiction was found under the current test and declared scope |

### Incompatible with established physics

Use this label only when the conflict is with external physics, not merely an internal project preference.

Examples may include a low-energy preferred-frame effect already excluded at the relevant scale, failure to reproduce a required quantum prediction in the regime being claimed, or failure to recover the validated GR limit while claiming that same regime.

### Unresolved mismatch

Use this when the Parent and decoder disagree but multiple explanations remain live.

The result should be recorded as:

```text
Parent output ≠ current decoder expectation
cause unresolved
```

That is a scientific result in its own right.

### Compatible so far

This means only that no contradiction was found under the current test. It does **not** mean the Parent is correct, the decoder is complete, the emergent structure is unique, or the theory has been confirmed.

## Required metadata

Every material Parent–decoder disagreement should record:

| Field | Required content |
|---|---|
| Parent version | Frozen candidate, hash or configuration |
| Decoder version | Frozen decoder, hash and thresholds |
| Interface version | Frozen response object and conventions |
| Regime | Size, scale, coupling, state, energy, time/frequency window |
| Expected behaviour | Preregistered expectation |
| Observed behaviour | Actual result |
| External physics involved | If any |
| Decoder validation status | Exploratory / candidate / validated |
| Parent status | Exploratory / candidate / frozen |
| Classification | One of the three outcomes above |
| Alternative explanations | Explicitly listed |
| Retuning allowed? | No for the confirmatory lineage |

## Regime errors

A microscopic quantum Parent is not required to look classically geometric at every scale. A continuum decoder should not kill a Parent merely because it fails at a scale where no continuum was expected.

The key question is:

> **Was the candidate expected, before unblinding, to be inside the decoder's domain of validity?**

If not, the result is not a valid falsification of the deeper theory.

## Instrument errors

Warning signs that the decoder itself may be at fault include:

- known positive controls fail;
- strong impostors pass;
- output is highly threshold-sensitive;
- the result disappears under harmless representation changes;
- the decoder needs post-result parameter adjustment;
- the allowed model class is so narrow that uniqueness becomes automatic;
- the input interface already contains the target geometry.

Any of these reduces the epistemic force of a Parent failure.

## Interface errors

A Parent may contain useful physics that the chosen interface does not expose. It may possess nontrivial quantum correlations, higher-order response, sector structure, nonlinear propagation or scale-dependent effective variables while the decoder receives only an impoverished observable.

The response is not to enrich the interface after seeing the desired answer. Any richer interface must be independently motivated or derived, then frozen as a new lineage.

## Dual-freeze rule

For a confirmatory comparison:

1. freeze the Parent / physical-response construction;
2. freeze the decoder;
3. record prior exposure;
4. reveal the comparison only after both sides are frozen;
5. do not retune either side using the outcome.

Scientifically justified changes may begin a new exploratory cycle, but the original result remains in the record.

## TL;DR

If a future Parent and the geometry decoder disagree, we do not immediately decide which one is wrong. The honest outcomes are **incompatible with established physics**, **unresolved mismatch**, or **compatible so far**.
