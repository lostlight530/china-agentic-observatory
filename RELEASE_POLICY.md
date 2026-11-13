# Release and Archival Policy

This repository treats `main` as the current repository state and release tags as immutable point-in-time snapshots.

## Policy

- Create a release or tag only from a reviewed and merged `main` revision.
- A release records a historical snapshot; it does not override later repository state, governance, contracts, or evidence.
- Release identifiers may be repository-specific. Do not invent a semantic version where the repository has not established one.
- Add `version`, `date-released`, DOI, SWHID, or other archival identifiers to citation metadata only after those identifiers actually exist.
- Do not rewrite historical tags or releases to reflect later corrections; publish a new release or correction record instead.
- Archive externally only after the release snapshot and its metadata have been validated.

For current repository truth, follow the repository's native implementation, evidence, governance, and recovery surfaces rather than citation or archival metadata.

## Initial archived software publication — 2026-09-16

The repository has a public Zenodo software publication dated **2026-09-16**.

- DOI: `10.5281/zenodo.22791309`
- DOI resolver: `https://doi.org/10.5281/zenodo.22791309`
- Code repository: `https://github.com/lostlight530/china-agentic-observatory`

This DOI is an archival publication identifier, not a moving identifier for every later `main` revision. Later repository changes must not be represented as part of the archived publication unless a new archival release explicitly includes them.

A future archived release should preserve this record as point-in-time publication history and use its own confirmed release metadata. DOI presence, citation metadata, or archival availability does not by itself establish event timing, implementation maturity, policy deployment, source truth, scientific validity, or reproduction.

## Verified archived version lineage (2026-10-10)

The September 16 publication described above is the **initial archival snapshot**; it is not the only release now registered under this software concept. The citation/CodeMeta DOI `10.5281/zenodo.22791309` is the **concept DOI**, not the DOI for the latest specific release.

| Archived release | Published/release date | Immutable version DOI |
| --- | --- | --- |
| `v2026.09-open-research-baseline` | 2026-09-16 | [`10.5281/zenodo.22791310`](https://doi.org/10.5281/zenodo.22791310) |
| `v2026.09-natural-month-close` | 2026-09-30 | [`10.5281/zenodo.23068347`](https://doi.org/10.5281/zenodo.23068347) |
| `v2026.10-open-research-production-framework` | 2026-10-04 | [`10.5281/zenodo.23137211`](https://doi.org/10.5281/zenodo.23137211) |

The October GitHub release [`v2026.10-open-research-production-framework`](https://github.com/lostlight530/china-agentic-observatory/releases/tag/v2026.10-open-research-production-framework) reports `published_at=2026-10-04T13:00:26Z`. These identifiers are confirmed public release/DOI records, **not a claim that present `main` was frozen in that snapshot**. The existing `CITATION.cff` September 16 date remains a recorded archival baseline; do not silently rewrite it into a present-day retrieval or publication date. This documentation note creates **no new software release, DOI, prospective observation, or evidence of external research adoption**. The [independent identity audit](https://github.com/lostlight530/research-software-identity-audit) observes ten fixed software objects and remains an external control repository, not an eleventh research sample.

## Archived checkpoint — 2026-10-14

The fourth archived version is [v2026.10-fourteen-day-evidence-checkpoint](https://github.com/lostlight530/china-agentic-observatory/releases/tag/v2026.10-fourteen-day-evidence-checkpoint).

- Version DOI: [10.5281/zenodo.23365548](https://doi.org/10.5281/zenodo.23365548)
- GitHub `published_at`: `2026-10-14T11:16:00Z`
- Tagged source commit: [`6fa92c662ffbe8b8eac14f7c8711f507583c2a92`](https://github.com/lostlight530/china-agentic-observatory/tree/6fa92c662ffbe8b8eac14f7c8711f507583c2a92)
- Software-family concept DOI: [10.5281/zenodo.22791309](https://doi.org/10.5281/zenodo.22791309)

Use the version DOI for this exact checkpoint and the concept DOI for the software family. `CITATION.cff` and CodeMeta retain the family identifier and recorded September 16 baseline date. Later changes to `main` belong to subsequent repository state; the checkpoint tag remains unchanged.

## Research stage, snapshot and DOI roles / 科研阶段、归档快照与 DOI 身份

**中文**：公开研究的 Daily、Weekly、Monthly 记录是带日期边界的研究证据，不是 GitHub Release；`main` 是持续变化的代码与记录状态，Git tag 指向特定修订；Zenodo **concept DOI** `10.5281/zenodo.22791309` 表示软件版本家族，而版本 DOI 仅代表对应发行的归档字节；复现实验时优先引用所用版本的 DOI，并补充精确 tag／commit、输入和可检查的运行收据；README 或 Pages 可以展示阶段状态，但不得声称内容已被当前概念 DOI 冻结

**English**: Dated Daily/Weekly/Monthly research records are not GitHub software releases; `main` continues to evolve, while a tag identifies a specific revision. Zenodo concept DOI `10.5281/zenodo.22791309` identifies the software family; each version DOI identifies the archived release bytes. Reproduction should cite the version DOI actually used, with exact tag/commit, inputs, and observable run receipts. A README or Pages stage display cannot claim that the current working state is frozen by the concept DOI

## Open-science reuse and research records

- Cite the software family through [CITATION.cff](CITATION.cff) or [CodeMeta](codemeta.json); cite the version DOI above when a result depends on this checkpoint.
- Use the linked tagged source commit for code inspection and retrieval, and record the revision, environment, procedure and observed result when performing a rerun.
- Follow [OPEN_RESEARCH.md](OPEN_RESEARCH.md) and the repository-native research contracts; use [RESEARCH_TEMPLATE.md](RESEARCH_TEMPLATE.md) for a new bounded research record where a more specific native template does not apply.
- Reuse repository-owned material under [LICENSE](LICENSE), preserve [authorship attribution](AUTHORS), and submit changes through [CONTRIBUTING.md](CONTRIBUTING.md).
- Keep later findings and corrections in new dated records so the archived checkpoint remains recoverable.


## Latest archived checkpoint — 2026-11-10

The latest archived repository snapshot is `v2026.11-ten-day-evidence-checkpoint`.

- GitHub Release: [v2026.11-ten-day-evidence-checkpoint](https://github.com/lostlight530/china-agentic-observatory/releases/tag/v2026.11-ten-day-evidence-checkpoint)
- GitHub release published: `2026-11-10T14:40:39Z`
- Tagged source commit: [`3e84c9ad0b644a41b7fe5f98ea71526f622bf824`](https://github.com/lostlight530/china-agentic-observatory/commit/3e84c9ad0b644a41b7fe5f98ea71526f622bf824)
- Zenodo exact-version record: [10.5281/zenodo.24112469](https://doi.org/10.5281/zenodo.24112469)
- Software-family concept DOI: [10.5281/zenodo.22791309](https://doi.org/10.5281/zenodo.22791309)

The Zenodo version record identifies the exact GitHub tag as its source reference. This is an immutable 2026-11-10 snapshot; subsequent changes on `main` are not part of this archive. The concept DOI remains the software-family identifier and is intentionally distinct from the version DOI.
