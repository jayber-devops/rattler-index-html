# 🐍 `rattler-index-html`

### A simple index.html for your conda-compatible index

[rattler-index](https://github.com/conda/rattler), as opposed to [conda-index](https://github.com/conda/conda-index), does not generate any html output for visualization, but only `repodata.json` for each subdir (platform).

This index.html takes inspiration from `conda-index` html templates to generate a visual representation for an index dynamically from each platform's repodata using [alpinejs](https://github.com/alpinejs/alpine).

Simply place `index.html` at the root of your web server or S3 static site.

#### License

Licensed under BSD 3, like `conda-index` and `rattler`.  See [LICENSE](LICENSE).

#### Contibuting

Welcoming contributions which improve performance, styling, etc.

This was tested on an index with few packages, and I could see potential performance and visualization issues with indexes with a large number of packages.