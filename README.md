# zyb.cxayg.studio

Static GitHub Pages site for `zyb.cxayg.studio`.

The published files live in `site/`. Pushes to `main` deploy through GitHub Actions.

## Custom domain

GitHub Pages reads `site/CNAME`, which contains:

```text
zyb.cxayg.studio
```

In Cloudflare DNS, point `zyb` to the GitHub Pages hostname after the repository is created.
