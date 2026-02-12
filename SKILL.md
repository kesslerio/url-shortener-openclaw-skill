---
name: shorten
description: URL shortening via is.gd (no auth required, permanent links). Use when: 'shorten this URL', 'short link', 'make URL shorter', 'create short link'. Simple, fast, no tracking. NOT for branded short links or analytics (no custom domains supported). NOT for YOURLS links (use shapescale-tools for YOURLS).
---

# Shorten

Quickly shorten URLs using the [is.gd](https://is.gd) service. No API key or account required.

## Usage

```bash
shorten "https://example.com/very/long/url"
```

## Examples

**Standard usage:**
```bash
shorten "https://google.com"
# Output: https://is.gd/O5d2Xq
```

## Notes
- Links are permanent.
- No analytics dashboard (simple redirect).
- Rate limits apply (be reasonable).
