# C2｜Standards, Protocols, Identity, and Interconnection

The usage-control technical file provides explicit contract-linked evidence fields

```text
terminationId
contractId
strategyId
reason
triggeredBy
timestamp

proofId
contractId
strategyId
logHash
blockchainTx (optional)
timestamp
connector signature
```

This is stronger than a generic “logging requirement” because the evidence model links execution to the exact contract and policy instance

**Rule:** technical interface definition ≠ universal interoperable implementation
