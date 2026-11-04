# hidns.vip redirect

This repository serves a static redirect page for `hidns.vip` via GitHub Pages.
All requests are redirected to https://www.hidoha.net, preserving path, query string and hash.

## Files

- `index.html`: redirect for the root path
- `404.html`: redirect for any other path
- `CNAME`: custom domain for GitHub Pages

## Notes

Redirection is done by JavaScript (with a meta refresh fallback), not an HTTP 301.
