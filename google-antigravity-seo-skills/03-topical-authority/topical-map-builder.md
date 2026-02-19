---
name: topical_map_builder
description: Van money pages tot supporting blogs + FAQ.
version: 1.0
language: nl
---

# Topical Map Builder

## Doel
Bouw een complete topical map voor een niche.

## Inputs
- Niche
- Regio
- Services

## Agent Workflow
1. Maak pillar topics
2. Genereer cluster topics
3. Koppel interne link structuur
4. Prioriteer op impact

## Output Format
CSV/JSON met pages + intent + priority

## Checks / Failure Modes
Te breed: map moet focussen op koopintentie.

## Prompt Template
```text
Maak een topical map voor {niche} in Nederland met 100 pagina ideeën.
```
