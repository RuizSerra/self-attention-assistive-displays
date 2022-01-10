

Original distill automation implementation from [Neuroevolution of Self-Interpretable Agents](https://github.com/attentionagent/attentionagent.github.io.git).


### Instructions to Build and Test
```bash
git clone https://github.com/attentionagent/attentionagent.github.io.git
cd attentionagent.github.io
npm install
```

Edit the following files:

- `draft_header.html` - start of the document
- `draft.md` - main text of the article (markdown)
- `draft_appendix.md` - appendix (markdown)
- `draft_bib.html` - the citations
- `index.html` - generated, don't edit this file

```bash
# build document into index.html
./bin/make
# serve on the base directory to view index.html at http://localhost:8000
python -m http.server
```

To watch all markdown files for changes and then compile them, you can run the following
```bash
brew install fswatch
./bin/watch
```

### If all you want to do is view the page locally

1. Run `python -m http.server` in the base directory to serve
2. Browse to `http://localhost:8000`

### Citation

For attribution in academic contexts, please cite this work as

BibTeX citation
```
@article{Ruiz-Serra2022,
  author = {Ruiz-Serra, Jaime and
            White, Jack and
            Petrie, Stephen and
            Kameneva, Tatiana and
            McCarthy, Chris},
  title  = {Learning vision processing for assistive displays through self-attention agents},
  eprint = {},
  url    = {},
  note   = "\url{}",
  year   = {2022}
}
```
