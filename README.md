# Signal Graph

An interactive knowledge graph of my CV — roles, projects, and training linked
the way my own research links words to brain regions. Solid edges are
category membership, dotted edges trace career sequence, dashed edges mark a
shared technique across otherwise-unrelated roles.

**[Open the live graph →](https://REPLACE_WITH_USERNAME.github.io/cv-graph/)**

Sub-nodes (individual clients under Labrador Data Retrieval, pipeline stages
under the Voice Biomarker Pipeline, coursework under Psychoanalytic Training)
start collapsed behind a count badge — click a node to expand it in place.
Search jumps straight to a match and auto-expands whatever it's nested under.

## Running it locally

It's a single static file with no build step — open [`docs/index.html`](docs/index.html)
directly in a browser, or serve the folder:

```bash
python3 -m http.server -d docs 8000
```

Built with [D3.js](https://d3js.org/) force simulation.
