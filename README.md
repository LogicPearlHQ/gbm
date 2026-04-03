# GBM Treatment And Trial Navigator

This is a runtime-only public export.

Included:
- trial_corpus.generated.json
- trial_options.generated.json
- literature_corpus.generated.json
- dataset_catalog.json
- static shell assets
- curated GBM manifest with embedded case outputs
- navigator report
- evidence graph
- markdown walkthrough

Excluded:
- build scripts
- fetch scripts
- raw registry downloads
- raw PubMed caches
- human-facing pearl generation artifact
- domain generation code

To preview locally:

```bash
cd <this-export>
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```
