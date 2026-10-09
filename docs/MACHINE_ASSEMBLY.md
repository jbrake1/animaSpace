# Machine Micro-Assembler (MEMS 2.0)

**Status:** living — 2026-10-09
**Repo of record:** `jbrake1/animaSpace`
**Use:** hardware how-to for machine deposition units and mating parts. Doctrine stays in `docs/DOCTRINE.md`. Tissue process stays in `docs/TISSUE_ASSEMBLY.md`. MEMS product class stays in `docs/MEMS.md`.

## Contrast to tissue micro-assembler

| | Machine (this file) | Tissue |
|---|---|---|
| Parts | crystals / MEMS-scale components | living cells and cell groups |
| Fluid | degassed UPW, oxide-free | oxygenated saline + nutrients |
| Join driver | surface energy + metallurgical or chemical bond | biological adhesion (cadherin, integrin) + optional fibrinogen |
| Place tolerance | drop within ~5 µm; fluid finishes the align | drop within acoustic well; cells finish the bind |
| Bond permanence | metallic cold-weld, SAM, or intermetallic | living junctions that mature under load |

Tissue does not cold-weld metal. Machine does not rely on biology for the structural join.

## Why pure vacuum-like cold weld is improbable at this scale

At 5 µm² – 50 µm² contact areas in degassed UPW, a trapped water monolayer remains between clean metal faces. Spontaneous metallic cold-weld without assistance is highly improbable. Surface forces dominate gravity, so the water can be used rather than fought.

## Phase 1 — Self-alignment (capillary & hydrophobic driving forces)

The micro-assembler only needs to drop the part within ~5 µm of the target. Surface-energy patterning finishes the align.

```
       [ Micro-Component ]  <- Hydrophobic gold pad
          \   |   / 
  ~~~~~~~~~~\~|~/~~~~~~~~~  <- UPW Environment
             v v            
       [=== Target Pad ===] <- Hydrophobic gold pad on hydrophilic substrate
```

- Pattern a specific gold (Au) geometry (example: 5 × 5 µm square) on both the component and the substrate.
- Treat the surrounding substrate hydrophilic.
- Water minimizes contact with the hydrophobic Au pads. A localized volume of water (or a microscopic droplet of a secondary immiscible fluid such as a high-density lubricant/thiol) trapped between the two pads minimizes free energy.
- Lateral capillary restoring force spontaneously pulls the component into sub-micron alignment with the substrate pad.

This is Method D of the alignment stack (asperity noble-metal pad) acting through the fluid. Acoustic well (A) and poka-yoke taper/key/vents (C) remain available for coarser pose. Suck (E) is still illegal as an aligner and is gated on seat.

Literature precedent exists for capillary-force-induced cold welding of gold and silver nanowires in aqueous media and for surface-tension-driven self-alignment of microparts with hydrophobic/hydrophilic patterns.

## Phase 2 — Converting contact into a permanent bond

Once self-aligned, displace or bridge the fluid layer.

### 1. Gold-to-gold micro-contact (closest to cold weld)

Pure Au does not oxidize in UPW.

- After capillary alignment, apply a small, brief downward force (micro-assembler tip or integrated MEMS actuator).
- Gold is ductile and hydrophobic; the squeeze forces trapped water out laterally.
- Plastic deformation at asperities produces a true gold-to-gold thermocompression or micro-cold-weld at room temperature.

### 2. Self-assembled monolayers (SAMs) for chemical adherence

When electrical conductivity is not required.

- Coat one pad with a thiol terminating in amine (–NH₂), the other with a thiol terminating in carboxylic acid (–COOH).
- On close approach the groups form electrostatic or covalent bonds through the water layer without high compressive force.

### 3. Transient liquid phase / eutectic micro-bonding

When a localized micro-heater pulse is available.

- One side Au, the other a thin layer of Sn or In.
- Brief thermal pulse melts the low-temperature metal, dissolves into gold, ejects the micro-scale water as vapor, and solidifies into a strong intermetallic joint.

Fire/extract/mold remains outside the weld path. These are still soup-mediated self-assembly steps.

## Design constraints at 5 µm² – 50 µm²

- **Surface roughness** $R_a < 1$ to $2$ nm. Rougher faces trap water pockets that cushion the joint and prevent adherence.
- **Part mass vs surface forces.** At this scale surface tension and van der Waals dominate gravity. Parts stick to the tool. Release must be active (piezo-shaker, electro-osmotic, or equivalent). Tool design is part of the assembler.
- **Fluid quality.** Degassed UPW, no O₂, no pollutants. Same chamber rule as doctrine.
- **Two loops.** Electronics coolant never shares the weld face.

## Open questions for the next waypoint

- Confirm which bond option is primary for gen-1 DU (Au-Au squeeze vs SAM vs eutectic).
- Measure actual restoring force and residual misalignment for a 5 × 5 µm Au pad pair in degassed UPW.
- Verify release mechanism so the part transfers from tool to fluidic pad without residual adhesion.

WP1 remains a single-node acoustic well for one DU size before drawing tapers. This fluidic path sits inside that well once the part is near the target.
