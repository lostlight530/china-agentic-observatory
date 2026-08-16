# C3｜Research, Models, Algorithms, and Evaluation

The data flywheel reframes model evaluation as an input to future data construction rather than a terminal score

A useful lifecycle becomes:

```text
model application
→ success / failure / safety / coverage evidence
→ feedback data
→ dataset revision
→ model iteration
```

The National Data Administration explicitly frames model-application feedback and dynamic interaction data as part of dataset optimization

**Open problem:** how feedback is filtered for noise, bias, reward hacking, unsafe behavior, and non-representative edge cases before retraining
