# Public Terminology Map

```text
Status: Draft public translation
Review Status: review_required
Delivery Ready: false
Production Ready: false
Market Validated: false
```

## Purpose

This map identifies public DesignLogic architecture language corresponding to selected internal USS lineage terms. It exists so public documentation can communicate architecture concepts in clearer, industry-readable language without using internal abbreviations as its operating vocabulary.

| Internal USS term | Public DesignLogic term |
| --- | --- |
| USS | DesignLogic Semantic Runtime Architecture |
| UST | Structured Meaning Layer / Structured Meaning Units |
| USR | Semantic Runtime Layer |
| USE | Semantic Engine Layer |
| SCE / SynCE | Semantic Core Layer |
| SCP | Semantic Control Layer |
| ORCH-C | Orchestration Layer |
| MeaningIR | Meaning Representation |
| ExecuteIR | Execution Representation |
| semantic tokens | structured meaning units |
| runtime-bound reasoning | bounded semantic execution |
| governance invariants | runtime governance rules |

## Mapping Boundary

This map is a public translation aid, not a raw USS canon export.

Each mapping indicates a public-facing term for lineage and communication purposes. It does not assert complete semantic equivalence, reproduce internal design detail, establish an implemented component, or confer authority on this repository.

Public architecture documentation should prefer terms such as structured meaning, semantic runtime, semantic engine, semantic core, semantic control, orchestration, bounded execution context, trace, review boundary, authority boundary, and runtime governance rule. Internal terms in this file are retained only to explain translation lineage.

## Layer Relationship

```text
USS
= internal source architecture / deep canon

DesignLogic Semantic Runtime Architecture
= public DesignLogic-facing translation of USS

DesignLogic Framework
= applied reusable modules built from the architecture

DesignLogic Apps
= products and capabilities built from the framework
```

## Interpretation Boundary

```text
Architecture coherence is not implementation proof.
Product thesis is not market validation.
Trace is not proof.
Model output is not authority.
Recommendation is not authorization.
Handoff is not deployment.
Execution-ready is not approved execution.
Semantic structure is not truth.
```
