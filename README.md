# HypeDE wiki

https://wiki.hypede.xyz — the HypeDE wiki in English and Russian.

Pages are Markdown in `src/en` and `src/ru`. Edit them, then rebuild the HTML:

```
pip install markdown
python3 tools/build.py
```

Commit both the Markdown and the generated pages. GitHub Pages serves the
repository root; `CNAME` holds the domain.
