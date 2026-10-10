# &c group

A single-page static site listing the apps. No framework, no build step.

```
index.html    markup, plus the filter script
styles.css    layout, light and dark themes
favicon.svg
```

## Preview

```bash
python3 -m http.server 4173
```

Then open <http://localhost:4173>.

## Editing

Each app is one `<li class="item">` in `index.html`. `data-status` is either
`available` or `soon`, and the filter buttons match on it. The counts in the
filter bar are written by hand.

## Hosting

Served by GitHub Pages straight from `main`. Pushing is deploying.
