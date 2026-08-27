# C3 — Research & Models

Model improvement claims need versioned experimental memory

A defensible evaluation-driven optimization loop should preserve at least:

```text
model version
→ evaluation dataset / metric version
→ diagnosed gap
→ changed dataset version
→ later model version
→ follow-up evaluation
```

Without those references, `model improved after dataset optimization` remains difficult to attribute causally

**Rule:** model improvement ≠ proof that one data change caused the improvement
