---
"@leejpsd/nextjs-cache-handler": minor
---

Add opt-in `tagReadMode: "on-demand"` for Cache Components. Read Redis markers for
the tags relevant to each entry and route, skip request-time keyspace scans, and
keep outage fallback entries and local tag state bounded.
