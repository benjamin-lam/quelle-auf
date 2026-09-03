# Quelle auf.

Public static output of the private `article-workbench` editorial pipeline.

The site is intentionally boring infrastructure: semantic HTML, one small CSS file, no client-side JavaScript, no CMS and no runtime database.

Published articles are generated from Markdown in the private workbench. Do not edit generated article HTML by hand; fixes belong in the source article and should be republished through the review pipeline.

## Public contents

```text
index.html
articles/<slug>/index.html
articles/<slug>/meta.json
assets/site.css
assets/favicon.svg
sitemap.xml
feed.xml
robots.txt
404.html
```

Private source snapshots, claim ledgers, prompts and reviewer responses are never copied here.

## GitHub Pages

Deployment uses the official GitHub Pages Actions flow. In repository settings select **Pages → Build and deployment → GitHub Actions** once.

Canonical base URL:

`https://benjamin-lam.github.io/quelle-auf/`

## Performance baseline

The site targets excellent Core Web Vitals/PageSpeed by construction:

- static HTML only,
- no JavaScript,
- system font stack,
- tiny CSS,
- no render-blocking third-party resources,
- semantic/accessibility-first markup.

A score is never assumed; measure the deployed page after publication.
