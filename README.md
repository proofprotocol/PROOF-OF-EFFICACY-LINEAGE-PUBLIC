# Proof of Efficacy Lineage Record (public edition)

A dated record of where proof of efficacy came from: proving that a security product does what its vendor says, under adversarial pressure, judged by the outcome rather than by the vendor's own console or script.

Original inventor and author: Craig Thomas Ellrod (ORCID [0009-0004-1058-7666](https://orcid.org/0009-0004-1058-7666)).

This is the public edition of a private lineage record. Everything a reader needs to check a date is here. Customer and vendor names, private repository names and the underlying files are withheld; each withheld item is fixed by a SHA-256 hash, so the original can be shown to a verifier later and checked against this record.

## The method in one line

Run the same attack against a target with the control present and with it absent, and judge the control by the outcome observed outside the control's own console. That is proof of efficacy, and it is what PP-SPEC-077 through PP-SPEC-080 formalize.

## Where to start

| File | What it is |
|---|---|
| [TIMELINE.md](TIMELINE.md) | The timeline, 2007 to 2026: practice first, names second, publication third |
| [EVIDENCE.md](EVIDENCE.md) | The key 2023 evidence items with hashes and third-party timestamps |
| [evidence/vendor-c-2023/manifest.tsv](evidence/vendor-c-2023/manifest.tsv) | SHA-256 of every file in the 2023 Vendor C engagement folder (393 files) |
| [evidence/vendor-c-2023/manifest.json](evidence/vendor-c-2023/manifest.json) | The same manifest for machines |
| [SPEC.md](SPEC.md) | The record format and what each kind of evidence does and does not prove |
| [docs/verify.md](docs/verify.md) | How to check every entry yourself |
| [schemas/](schemas/) | JSON Schema for the manifest |
| [SHA256SUMS](SHA256SUMS) | SHA-256 of every file in this repository |

## What kind of evidence this is

| Kind | Who keeps the clock | Can the author change it later |
|---|---|---|
| Public GitHub repositories (creation date, first commit) | GitHub | Commit dates can be set by the author; repository creation dates cannot |
| Internet Archive snapshots | Internet Archive | No |
| Zenodo DOIs | Zenodo / CERN | No |
| Dropbox server copies of the 2023 files | Dropbox | No; and the local files are byte-identical to those copies (Dropbox content hash matches) |
| File modification times | The author's computer | Yes; treat as supporting only |
| This repository | GitHub, from its creation date | It proves the hashes existed on that date, not earlier |

## License

Proof Protocol License 1.0 (LICENSE.md); text Apache License 2.0 under Part A. See NOTICE.md for attribution.
