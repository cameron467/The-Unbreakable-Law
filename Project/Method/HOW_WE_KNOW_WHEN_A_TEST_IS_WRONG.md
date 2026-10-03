# How We Know When a Test Is Wrong

- **Layer:** Project
- **Status:** Methodology and audit history
- **Last updated:** 3 October 2026
- **Peer review:** Requested

Emergent-physics research is unusually vulnerable to convincing false positives. A complicated system can produce an attractive dimension estimate, metric, propagation speed, spectrum or embedding without containing the physical structure we hoped to identify.

The Unbreakable Method therefore treats the diagnostic itself as something that must survive falsification.

> **A test is not trusted because it gives the answer we wanted. It becomes credible only after it recognises known positives and rejects or correctly classifies strong impostors.**

## The Parent #1 lesson

Early Parent #1 investigations produced encouraging geometry-like signals. Adversarial controls were then introduced, including structures with duplicated or twin neighbourhoods, compact/product behaviour, strong short-walk structure and geometry-like spectra.

The result was uncomfortable but useful: several diagnostics were measuring something real, but not necessarily what they had been interpreted as measuring.

Parent #1 was therefore retired as evidence for autonomous emergent 3D geometry.

## Diagnostic graveyard

| Diagnostic | What looked promising | What failed | Current status |
|---|---|---|---|
| Largest-relative-gap decoder | Spectral gaps appeared to select effective dimension | Failed sufficiently broad adversarial calibration | **Killed** |
| Ordered-eigenvalue / Weyl gate | Preregisterable scaling test | Failed its own clean calibration | **Failed as a gate** |
| Two-axis Weyl agreement | Two scaling directions appeared to agree | Axes were not sufficiently independent | **Consistency/extensivity screen only** |
| Three-point Gaussian closure | Local response looked Gaussian | Trivial global mixing could also drive the residual small | **Killed as standalone geometry test** |
| Response-metric persistence | Local geometries showed persistent structure | Twin/product impostors could mimic it | **Promising but insufficient** |
| Exact finite heat-feature rank | Suggested direct tangent dimension | Exact finite rank need not equal continuum dimension at finite scale | **Replaced by scaling-hierarchy target** |

## Why killing a test is progress

A failed diagnostic tells us what information that diagnostic does **not** contain.

Examples:

- spectrum alone may not determine local relational structure;
- finite-speed propagation does not guarantee relativity;
- one dimension estimator does not establish a manifold;
- one manifold diagnostic does not establish spacetime;
- one spacetime diagnostic does not establish Einstein dynamics.

Each failure removes a shortcut.

## False-positive rule

Every major claim should eventually have:

1. at least one strong positive control;
2. at least one strong impostor;
3. at least one orthogonal discriminator;
4. an explicit statement of known non-identifiability;
5. a declared scope beyond which the test is not trusted.

The objective is not an arbitrary number of checks. It is coverage of materially different failure mechanisms.

## No rescue by hidden retuning

A confirmatory test should be frozen before the unknown candidate is revealed.

If the rule changes after the result is known, the changed rule belongs to a new exploratory lineage. The confirmatory history should remain visible.

The desired sequence is:

```text
explore
  ↓
freeze
  ↓
reveal
  ↓
accept the result
```

not:

```text
reveal
  ↓
adjust the test
  ↓
pass
  ↓
call it confirmation
```

## A failure can belong to the instrument

When a Parent disagrees with a project diagnostic, the Parent is not automatically wrong. The diagnostic may be under-calibrated, outside its applicable regime, overfitted to a narrow model class or measuring the wrong structure.

For the formal handling of this case, see [`PARENT_DECODER_DISAGREEMENT_PROTOCOL.md`](PARENT_DECODER_DISAGREEMENT_PROTOCOL.md).

## What would make a test trustworthy

A strong decoder should eventually demonstrate:

- success on held-out known positives;
- failure or correct classification on strong impostors;
- stability under irrelevant representation changes;
- stability across system size and scale;
- no target dimension inserted in advance;
- no target geometry hidden in the probe interface;
- no post-unblinding threshold tuning;
- reproducible code and raw controls;
- an explicit statement of what the test cannot distinguish.

## TL;DR

The project has repeatedly discovered that nice-looking tests can be fooled. Instead of hiding those failures, the Method keeps them. A diagnostic earns trust only when it recognises real examples and survives deliberately designed fakes.
