# Understanding Linear Algebra

The OmniStax edition of *Understanding Linear Algebra*, from David Austin (Grand Valley State University).
The app that reads it, the shared tools and the rules for building a book are in [OmniStax/OmniStax](https://github.com/OmniStax/OmniStax); clone this repository into that one's `omnistax-content/` folder under the name `Understanding Linear Algebra` (`npm run books` there does it, from `omnistax-content/books.json`).

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), © David Austin. Source: https://understandinglinearalgebra.org, PreTeXt at https://github.com/davidaustinm/ula (cloned read-only into `source/ula/`, gitignored).

## Building from the source

```
python3 tools/convert.py --index --all     # every source.md, toc.md, modules.json and media/
```

`PREFIG=<path to prefig>` renders the PreFigure diagrams the book ships no SVG for (`pip install prefig`; `prefig init` once).
