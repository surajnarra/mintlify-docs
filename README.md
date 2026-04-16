# Emergent Documentation

Mintlify documentation site generated from a crawl of
[app.emergent.sh](https://app.emergent.sh).

- **Run ID:** `2026-04-17--001922--05ffcd`
- **Target:** `https://app.emergent.sh`
- **Screenshots:** 65
- **Guides:** 22
- **Reference pages:** 5

## Preview locally

```bash
npm install
npm run dev
```

The dev server renders at `http://localhost:3000` by default.

## Structure

```
.
├── docs.json              Mintlify site configuration
├── index.mdx              Landing page
├── docs/                  Getting Started content
├── guides/                Feature guides (image-rich)
├── reference/             Sitemap, URL map, permissions, shortcuts, glossary
├── images/                Crawl screenshots referenced by the guides
├── run.json               Crawl manifest
└── package.json           Mintlify dev / build scripts
```
