# Inverse-LLaVA project website

Published at [inverse-llava.github.io](https://inverse-llava.github.io/).
Static HTML and CSS, with no build step or third-party runtime.

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`. Check desktop/mobile layouts, keyboard navigation,
full-resolution figure links, and the benchmark table before publishing.
Wide tables and code blocks scroll within their own containers.

## Content sources

- The [7B model card](https://huggingface.co/xuhuizhan5/Inverse-LLaVA-7B) and
  [evaluation records](https://huggingface.co/xuhuizhan5/Inverse-LLaVA-research-artifacts/tree/main/evaluations)
  provide the current common-protocol results.
- Originally published LLaVA scores remain in a separate, labeled table.
- SVG figures and logos match the [source artwork](https://github.com/xuhuizhan5/Inverse-LLaVA/tree/main/assets).
  `static/images/overview.json` retains example provenance.
- HD and 13B are 5%-data studies. The example-count comparison excludes backbone
  pretraining and is not a runtime or FLOP measurement. The paper is a preprint.

Original site adapted from [Nerfies](https://github.com/nerfies/nerfies.github.io)
under CC BY-SA 4.0. Artwork and the VizWiz example retain the attribution and
terms documented in the source repository's `assets/README.md`.
