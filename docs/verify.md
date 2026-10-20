# How to verify

## Public repositories

```bash
curl -s https://api.github.com/repos/surfd4wg/kali | grep created_at
git clone https://github.com/surfd4wg/kali && cd kali && git show --stat ec0178d5c24e73121986fb5de223f3dfca8c3244
```

The repository creation date comes from GitHub and cannot be set by the author.

## Internet Archive and Zenodo

Open each URL and DOI in TIMELINE.md. The snapshot date is in the archive URL.

## Withheld files

Ask the author for the file and its evidence ID. Then:

```bash
sha256sum <file>          # must equal the sha256 in manifest.tsv
```

For items with a Dropbox server copy, the author can share that copy directly from Dropbox. Its Dropbox content hash, computed as below, must match the local file's:

```python
import hashlib
def dropbox_content_hash(path):
    h = b""
    with open(path, "rb") as f:
        while (b := f.read(4 * 1024 * 1024)):
            h += hashlib.sha256(b).digest()
    return hashlib.sha256(h).hexdigest()
```

## This repository

```bash
sha256sum -c SHA256SUMS
python3 -m json.tool evidence/vendor-c-2023/manifest.json > /dev/null
```
