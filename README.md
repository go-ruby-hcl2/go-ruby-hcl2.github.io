<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-hcl2/brand/main/social/go-ruby-hcl2.png" alt="go-ruby-hcl2/go-ruby-hcl2.github.io" width="720"></p>

# go-ruby-hcl2.github.io

The organization's institutional landing page, served at
<https://go-ruby-hcl2.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`).

Documentation lives in a separate repository,
[go-ruby-hcl2/docs](https://github.com/go-ruby-hcl2/docs), served at
<https://go-ruby-hcl2.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
