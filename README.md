# Gaming Research Website

[Hugo](https://gohugo.io)-based website with the
[Hugo-Theme-Codex](https://github.com/jakewies/hugo-theme-codex) theme tailored for the project. 

## Creating content

See the [docs](https://gohugo.io/getting-started/quick-start/#step-4-add-some-content):

```shell
$ hugo new one-more-page.md
```

Page or post file structure:

```markdown
---
title: "My First Post"
---

Your text
```

```shell
$ git add -A
$ git commit -m "Commit message"
```

## Deployment

```shell
$ git push
```

## Publishing

See [GitHub Pages](https://pages.github.com).

## Local Setup

```shell
$ CGO_ENABLED=1 go install -tags extended github.com/gohugoio/hugo@v0.81.0
$ hugo server
```
