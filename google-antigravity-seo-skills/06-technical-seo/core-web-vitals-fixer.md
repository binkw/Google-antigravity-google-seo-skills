---
name: core_web_vitals_fixer
description: Optimaliseer LCP, INP, CLS.
version: 1.0
language: nl
---

# Core Web Vitals Fixer

## Doel
Detecteer en los CWV issues op.

## Inputs
- URL
- Lighthouse report (optioneel)

## Agent Workflow
1. Diagnose LCP bronnen
2. Check JS blocking
3. Check image optimization
4. Output concrete dev fixes

## Output Format
Checklist met dev tickets

## Checks / Failure Modes
Geen toegang tot hosting.
Meetdata ontbreekt.

## Prompt Template
```text
Analyseer Core Web Vitals issues voor {url} en geef concrete fixes.
```
