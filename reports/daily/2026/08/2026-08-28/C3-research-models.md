# C3 — Research, Models, Algorithms, Evaluation

## Finding

A model/application evaluation result can trigger targeted dataset optimization, but the resulting dataset is no longer the same analytical object

If optimization changes data composition, labels, weights, synthetic samples or filtering, then prior quality evidence may no longer describe the new version completely

The research loop should therefore preserve:

```text
model_version
→ evaluation_result
→ diagnosed_gap
→ dataset_v1
→ optimization
→ dataset_v2
→ quality_result_v2
→ model_v2
→ follow-up_evaluation
```

## Boundary

This is a research-control model; no national standard currently publishes this full causal chain
