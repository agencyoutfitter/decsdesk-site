# Decsdesk

Decsdesk — part of Agency Outfitter.

Static site (Hugo + PaperMod) deployed to Cloudflare Pages on push to `main`.

- Custom domain: `decsdesk.com`
- CF Pages project: `decsdesk-site`
- Built with Hugo `0.157.0` extended.

## Local dev

```bash
hugo server -D
```

## Deploy

Push to `main`. The GitHub Action handles build + deploy.
