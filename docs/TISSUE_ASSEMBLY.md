# Tissue assembly

Living process spec. 2026-09-17.
This file replaces the root dumps named `bio reactor.docx (2).txt` and friends as *current intent*. Those files stay in the tree as reference.

## Patient-derived stem cells

We build tissue from the patient’s cells when the body cannot repair an organ.

## Patient scan and build file

Scan the failing organ for scale and port geometry. A tissue engineer edits that scan when the native shape is the failure (size, mechanics, dead regions).

The file is the living map: target anatomy, place order, lineage and regional program per slot, growth recipes, and lot history from the iPSC line through bead, pre-assembly, DU queue, and place (pose, echo, reject). Physics and soup still do the join. The file is instruction, not a row for every cell.

First organ class: kidney.

## Blood sample

Venous blood → PBMCs (peripheral blood mononuclear cells) → iPSC (induced pluripotent stem cell) line. Ship the frozen patient-specific stock to the factory.

## Thaw and triage

Thaw, feed, confirm viability, then seed the bioreactor. This is not “reanimation of whole blood.” Reprogramming stays on Earth unless there is a hard reason to do colony work in orbit.

## Bioreactors

Vascular analogs. Perfusate flow and local factors mimic a niche so stem cells take a lineage and a regional program. That is not the same as a final XYZ coordinate.

Beads sit in acoustic wells. Bulk flow is the pulsatile pump. PMUT arrays hold, move, and read an echo signature. They are not a full lab assay by themselves.

Cells must reach bond-age before place. Maturation clocks are coordinated to the assembly event.

Healthy cells move to pre-assembly chambers for multicellular groups.

## Deposition units

A DU is an articulated tube, PMUT-lined on the inside, from the bioreactor assembly chamber to the build face. The magazine is the tube. Do not pre-load every cell a spine will ever place.

Joints live in the thick root. The poke-in section is thin so many spines can pack the chamber. Arm motion may be as slow as a plant tracking the sun. Tip transit stays short (~0.1 mm off the tissue face). The tube bore stays full of soup. Do not evacuate the cell path.

## Build chamber

Sized to the organ. DUs enter through many ports. The silhouette is an urchin: chamber plus spines. Overlap is allowed. As one spine retracts, another may enter.

Place happens on the whole outer surface at once. Free-fall: no gravity settling.

## Placement

PMUTs at the tip and on the chamber place the cell or group. Final alignment and attachment are left to the cells except where we need speed.

- Vessels: fibrinogen + thrombin for a watertight face.
- Ligament, tendon, bone: methods already in the patent file.

## Assembly order and speed

Start at the inlets and outlets of the pump, the lymph tree, and the nerve leads. Place the right lineage in the right address.

During place:

- no gravity settling
- high viscosity and small mass keep drift small
- streaming is held off

Aqueous place ~2 mm/s. Hops longer than a few centimeters may use a droplet in air at ~2 m/s under PMUT custody.

## Perfusion

No pulse during place. After the mass is down and the tree is closed, the pump runs oxygenated, nutrient-rich perfusate at a rate the wall can take. Pulse is a formation and identity cue, not life support for the print.

## Identity

You cannot build functional tissue if a cell is the wrong lineage, the wrong regional program, or the right cell in the wrong address. Neighbors and load hold what the reactor and the file set.

## Failure modes (locked claims)

**Oxygen.** Neurons with no O₂ fail in 4–6 minutes at 37 °C. At 32 °C that anoxic window is about 8–10 minutes — abort time only, if a cell is off a lumen. Print soup is 100% O₂ at about 2 atm PO₂, not 21% air. Every cell is placed within 200 µm of a lumen filled with that soup. That is supply. Do not stack those facts as 2 × 2 × 2 × lumens = one hour of anoxia.

**Shear.** No tweezers. Toroid translate. Impedance rotate. Reject if pose or echo is bad.

**Lymph in free-fall.** Print the tree. Add one-way valves because there is no gravitational assist.

**Nerves.** Map the patient. Replay after the mass can take it.

**Radiation.** Plastic plus a water jacket lowers dose. It does not beat sea level for GCR and does not make CPUs Earth-safe by itself. ECC stays. Keep mitosis dwell short.

**Leaks.** Factory flood at process pressure so seals see low ΔP.

**Buoyancy and convection.** Place is free-fall, no centrifuge. Buoyancy is off. Ordinary heat chimneys are off. Manage streaming.

**Toroids.** They collapse on Earth and under centrifuge. That is why the factory is free-fall during place.
