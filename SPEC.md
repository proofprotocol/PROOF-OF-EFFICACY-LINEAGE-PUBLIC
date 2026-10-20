# Proof of Efficacy Lineage Record (public edition): record format

| Field | Value |
|---|---|
| Version | 1.1.0 |
| Date | 2026-10-20 |
| Author | Craig Thomas Ellrod (ORCID 0009-0004-1058-7666) |
| Status | Record |

## 1. Purpose

This repository records, with dates that can be checked, the lineage of proof of efficacy. It is written for people and for machines: every table in the Markdown files has a machine-readable counterpart or can be checked from public sources.

## 2. Redaction rule

1. Vendors and customers are named by letter (Vendor A, Vendor B, ...) in order of first appearance, unless the vendor has agreed to be named. The mapping is held in the private record. Spyderbat is named with its consent (version 1.1.0).
2. A private repository is shown by its owner and first-commit hash; a name that contains a vendor name is withheld.
3. A withheld file is shown by an evidence ID, its SHA-256, its byte size and its file time. Its path is held in the private record.
4. Nothing is redacted that a reader needs to check a public source.

## 3. Evidence manifest

`evidence/<set>/manifest.tsv` and `manifest.json` list one entry per file, conforming to `schemas/lineage-evidence.schema.json`:

| Field | Meaning |
|---|---|
| `id` | Evidence ID, `EV-<set letter>-<4 digits>`, stable for this version |
| `group` | What kind of file it is (see EVIDENCE.md) |
| `ext` | File extension |
| `bytes` | Size in bytes |
| `sha256` | SHA-256 of the file's bytes |
| `file_mtime_utc` | File modification time on the author's computer, UTC. Supporting only |
| `dropbox_server_copy_utc` | Time Dropbox recorded for a byte-identical server copy, where one exists |
| `dropbox_content_hash_match` | `true` when the local file's Dropbox content hash equals the server copy's |

## 4. What each kind of evidence proves

| Evidence | Proves | Does not prove |
|---|---|---|
| A public commit hash | The content existed in that repository; GitHub's repository creation date bounds it | That the commit date was not set by the author |
| An Internet Archive snapshot | The page existed with that content on the snapshot date | Anything about the page before that date |
| A Zenodo DOI | The deposit existed on its publication date | Anything not in the deposit |
| A Dropbox server copy with matching content hash | The exact file existed on Dropbox on that date | Who wrote it, beyond the account that owns it |
| A file time | Nothing on its own | It can be changed by the owner |
| A hash in this repository | The file existed by this repository's creation date, and any copy shown later can be checked byte for byte | Anything about the file's content until it is shown |

## 5. Verification

See [docs/verify.md](docs/verify.md).

## 6. Changes

A correction is a new commit; history is never rewritten. An evidence ID, once published, is never reused for a different file.
