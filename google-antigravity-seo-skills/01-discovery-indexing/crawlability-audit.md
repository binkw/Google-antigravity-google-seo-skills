---
name: crawlability_audit
description: Detecteer blokkades (robots, JS, redirects).
version: 1.0
language: nl
---

# Crawlability Audit

## Doel
Check of Google de site technisch kan crawlen.

## Inputs
- URL
- Sitemap URL (optioneel)

## Agent Workflow
1. Check robots.txt
2. Check statuscodes
3. Check redirect chains
4. Check JS rendering issues
5. Output issues + fixes

## Output Format
JSON issues list + severity

## Checks / Failure Modes
False positives bij CDN.
Sitemap ontbreekt.

## Prompt Template
```text
Voer een crawlability audit uit voor {url} en geef fixes.
```
