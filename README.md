# NZS 3101 Concrete Design Calculators

Based on NZS 3101:2006 (New Zealand Concrete Structures Standard).

## Calculators Included

| Calculator | NZS 3101 Clause | Description |
|------------|-----------------|-------------|
| **Shear Capacity** | 7.5, 9.3.9 | Calculate Vc, Vs, Vn for rectangular beams |
| **Torsional Capacity** | 7.4, 9.4 | Pure and combined torsion for rectangular sections |
| **Punching Shear** | 7.10, 11.5 | Slab-column connection punching shear |
| **Min/Max Reinforcement** | 7.6.1, 7.6.2, 9.3.2 | Check reinforcement limits |

## How to Use

### Option 1: Local Files (Offline)

1. Download this repository
2. Open `index.html` in any web browser
3. Click the calculator you need

All calculators work offline - no internet required after initial font load.

### Option 2: GitHub Pages (Online)

Enable GitHub Pages on this repository:
1. Go to **Settings → Pages**
2. Set Source to `main` branch
3. Save

Then access at: `https://calforyanz-Openclaw.github.io/nzs3101-calculations/`

## Input Parameters

### Shear Capacity
- f'c (MPa), bw (mm), h (mm), cover (mm)
- As (mm²), stirrup diameter, legs, spacing, fy

### Torsional Capacity
- f'c (MPa), bw, h, cover
- Longitudinal steel Asl, stirrup details

### Punching Shear
- f'c (MPa), slab thickness h, effective depth d
- Column dimensions c1 × c2, applied shear V

### Min/Max Reinforcement
- f'c (MPa), fy (MPa), bw, h, cover
- Steel area As, compression steel As'

## Output

Each calculator provides:
- Step-by-step calculation breakdown
- Final capacity result
- Pass/Fail status
- NZS 3101 clause references

## Disclaimer

These calculators are for quick checks only. Always verify results with detailed design and comply with the full NZS 3101:2006 requirements.

## License

MIT License