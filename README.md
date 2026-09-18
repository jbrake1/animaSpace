# AnimaSpace

A no-touch micro assembler. Sound is the hands. Soup does the join.

Concept stage. No working machine exists. Read this tree as design intent.

## What it is

AnimaSpace is two machines that share one idea.

1. **Tissue assembler** — grow the patient’s own cells, then place them without tweezers into a kidney-shaped mass that already contains vessels, lymph, and nerves.
2. **Electronics assembler** — later, the same method places parts for three-dimensional boards. Those boards are how we build the tissue machine we cannot buy today.

It is not a printer. It does not squeeze a slurry through a nozzle and hope. It holds and moves cells or parts with acoustic wells and toroids, then lets surface forces and biochemistry finish the joint except where we need speed (fibrinogen + thrombin on a vessel face).

## Current process (tissue)

Full write-up: [docs/TISSUE_ASSEMBLY.md](docs/TISSUE_ASSEMBLY.md)

Short version:

- Blood → PBMCs → iPSC line on Earth → frozen stock to the factory.
- Thaw, viability, bioreactors. Factors on beads set **lineage and regional program**. Address is the build file and the neighbors.
- Pre-assembly groups ride a wet, PMUT-lined tube (the deposition unit) to the build face. The tube *is* the queue.
- Place is static. No pulse while depositing. About 2 mm/s in water. Longer hops: droplet in air at about 2 m/s.
- Vessels, lymph, and nerves are in the placed mass. Every cell stays within about 200 µm of a lumen.
- Hold during place: about 32 °C, high PO₂ soup. Anoxia abort if a cell is off a lumen: about 8–10 minutes at 32 °C. The plan is not anoxia.
- Pulse and nerve replay start after the mass is down and the tree is closed.

## Build file

The build file is instruction, not a row for every nucleus.

Scan the failing organ for scale and ports. An engineer edits the scan when the native shape *is* the failure. The file holds target anatomy, place order, lineage and program per slot, growth recipes, and lot history from the iPSC line through place (pose, echo, accept or reject).

First target organ: **kidney** — arteries, veins, lymph, nerves, parenchyma slots.

## Doctrine and hardware

- Process core: [docs/DOCTRINE.md](docs/DOCTRINE.md)
- Hardware already locked (alignment A–E, suck-weld, two loops, WP1 acoustic well) lives in the hardware notes, not in doctrine.

Root files named `something.docx (1).txt` are the July dump. **Reference only.** Do not treat them as current design.

## Why microgravity

Aqueous toroids collapse under gravity and under centrifuge. Free-fall turns buoyancy off and turns ordinary convection off. Residual motion during place is streaming — we keep that off too.

Ground work is still real: schema, compiler, simulation of one acoustic well, wet process on Earth where gravity is managed instead of removed.

## Status

| Piece | State |
|---|---|
| Doctrine | Living, 2026-09-17 |
| Tissue process spec | Living, see docs/TISSUE_ASSEMBLY.md |
| Kidney build-file schema / designer | Next software work |
| WP1 single-node acoustic well | Next hardware waypoint |
| Working assembler | Not built |

## Collaborators

Useful if you do inverse problems on phased arrays, acoustofluidics, PMUT drive, or kidney vascular anatomy. Open an issue.

## License

MIT. Public disclosure on purpose. Prior art follows the commit dates.

## Author

James Brake — [@jbrake1](https://github.com/jbrake1)
