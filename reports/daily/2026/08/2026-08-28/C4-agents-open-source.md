# C4 — Agents, Platforms, Open Source, Engineering

## Finding

Agent systems make dataset-version governance more urgent because operational feedback can generate new training or evaluation data continuously

The engineering risk is silent inheritance:

```text
feedback
→ dataset mutation
→ same dataset name
→ old quality result reused
```

A safer architecture is version-explicit:

```text
feedback
→ data-work item
→ dataset_vN+1
→ quality / governance gate
→ training admission
```

## Boundary

No public national Agent platform interface was found today that exposes this full state machine as a common API
