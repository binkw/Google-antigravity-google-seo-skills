---
name: serp_reverse_engineering
description: Ontleed content type, intent, headings, schema, backlinks.
version: 1.0
language: nl
---

# SERP Reverse Engineering

## Doel
Analyseer top 10 Google resultaten om te begrijpen wat werkt.

## Inputs
- Keyword
- Land/regio (NL)

## Agent Workflow
1. Haal top 10 SERP
2. Classificeer intent
3. Analyseer content structuur
4. Identificeer ontbrekende subtopics
5. Maak 'winning outline'

## Output Format
SEO brief + outline + content gaps

## Checks / Failure Modes
SERP verschilt per locatie.
Personalization.

## Prompt Template
```text
Analyseer de SERP voor '{keyword}' in Nederland en maak een winnende content outline.
```
