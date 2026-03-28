---
name: nzs3101-unified-portal
description: Unified NZS 3101 concrete design calculator portal - combines shear, torsion, punching shear, and reinforcement limits.
---

## When to use

When user asks for NZS 3101 web calculator or wants to access multiple concrete design calculations from one place.

## Interaction pattern

0. Provide local unified portal page:
   - `C:\Users\calfo\.openclaw\workspace\skills\nzs3101-unified-portal\index.html`

1. The portal provides:
   - Navigation to all 4 calculation tools
   - Local versions of each calculator for offline use
   - Professional consistent UI across all tools

## Individual tools

| Tool | NZS 3101 Clause | File |
|------|----------------|------|
| Shear Capacity | 7.5, 9.3.9 | ../nzs3101-concrete-shear-capacity/references/page.html |
| Torsional Capacity | 7.4, 9.4 | ../nzs3101-torsional-capacity/references/page.html |
| Punching Shear | 7.10, 11.5 | ../nzs3101-punching-shear/references/page.html |
| Min/Max Reinforcement | 7.6.1, 7.6.2, 9.3.2 | ../nzs3101-reinforcement-limits/references/page.html |

## GitHub sync

Portal can be deployed to GitHub Pages. Files to sync:
- `index.html` (main portal)
- All `references/page.html` from each skill folder