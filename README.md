# Garage Design

Canonical repository for the garage interior design project.

## Current baseline

The approved baseline is version `v1.0.0` and is defined by:

- off-white primary walls
- dark charcoal Corvette feature wall
- vivid graphite epoxy/polyaspartic floor
- longitudinal linear LED ceiling lighting
- no floor parking lines
- 2026 Tesla Model 3 at left
- Chevrolet Corvette C8 centered at rear
- Yamaha YZF-R1 at right rear
- Ducati Streetfighter V4 at right front
- equal-size engineering wall art for all four vehicles
- at least 50 cm spacing between adjacent art pieces

The machine-readable source of truth lives in `baseline/garage_baseline.json`.
The visual source of truth lives in `baseline/garage_baseline_reference.jpg`.

## Repository structure

```text
garage/
├── README.md
├── baseline/
│   ├── garage_baseline.json
│   ├── garage_baseline.schema.json
│   ├── garage_baseline_prompt.json
│   └── garage_baseline_reference.jpg
├── variants/
├── references/
├── history/
│   └── garage_baseline_change_history.json
├── docs/
│   └── design-principles.md
└── manifest.json
```

## Versioning

- `v1.0.0`: approved baseline milestone
- `v1.x.0`: additive design refinements that preserve the baseline direction
- `v2.0.0`: major design direction change

## Working rule

Future variations branch from the approved baseline. A variation does not replace the baseline unless it is explicitly promoted to a new milestone.
