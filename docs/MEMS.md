# MEMS and the micro assembler

**Status:** living — 2026-09-27
**Repo of record:** `jbrake1/animaSpace`
**Use:** product-class note. Doctrine stays in `docs/DOCTRINE.md`. Tissue process stays in `docs/TISSUE_ASSEMBLY.md`. Do not load this file as process core.

MEMS is the first product class the micro assembler is meant to make. It is not the name of the assembler and it is not the silicon-fab process that built MEMS to date.

## MEMS 1.0 vs MEMS 2.0

**MEMS 1.0** is silicon fab: lithography, etch, release, package. Planar, dry, high capex. That stack made sensors, actuators, PMUTs, and microfluidic chips. Those parts remain legal *inputs* when we buy them.

**MEMS 2.0** is the same scale (about 5–500 µm) built by the AnimaSpace assembler: chamber-specific soup, sound as transport and hands, poka-yoke seat, oxide-free cold-weld in UPW. Geometry is not required to stay planar. Vascular coolant stays off the weld face.

| | MEMS 1.0 | MEMS 2.0 (this program) |
|---|---|---|
| Factory | wafer fab | micro assembler in soup |
| Join | deposit / etch / bond | place + self-assembly + cold-weld |
| Medium | vacuum / dry / resist | UPW at machine weld; other soups in their chambers |
| Role here | bought parts (PMUT, pump) | first output class on the build ladder |

Fire / extract / mold is not the weld path. Honor present nature: crystals grow in soup; sound assembles those crystals into machines; later machines assemble tissue.

## Relation to the assembler

- The assembler is the machine.
- MEMS-scale DUs and mating parts are what gen-1 is allowed to ship.
- Build ladder stays: Earth micro-assembler → orbit builds the next assembler → that generation builds the tissue assembler.
- WP1 is still a single-node acoustic well for one DU size. That well may use a bought PMUT array. Using a 1.0 chip does not make the process 1.0.

Do not reopen locked hardware in this file: alignment A–E (E illegal as aligner), aqueous toroid ~2 mm/s, two loops, suck after seat only.

## GitHub use

One named file, one job. Search hits belong in the alias block below so doctrine and tissue notes stay thin.

<details>
<summary>Search aliases (collapsed — open only when hunting a phrase)</summary>

MEMS, MEMS 1.0, MEMS 2.0, micro-electro-mechanical systems, microelectromechanical, microsystem, microsystems, MST, micromachine, micromachining, silicon MEMS, SOI MEMS, surface micromachining, bulk micromachining, LIGA, DRIE, Bosch process, foundry MEMS, CMOS-MEMS, piezo MEMS, capacitive MEMS, RF MEMS, BioMEMS, optical MEMS, MOEMS, microfluidic chip, lab-on-chip, lab on a chip, µTAS, NEMS, nanoelectromechanical, transducer, microactuator, microsensor, inertial MEMS, IMU die, pressure sensor die, microphone MEMS, ultrasonic transducer, PMUT, CMUT, MUT array, piezoelectric micromachined ultrasonic transducer, capacitive micromachined ultrasonic transducer, SAW, BAW, resonator, comb drive, proof mass, sacrificial release, stiction, handle wafer, cap wafer, anodic bond, eutectic bond, fusion bond, DRIE trench, through-silicon via, TSV, wafer-level package, WLP.

Aqueous MEMS, wet MEMS, soup MEMS, oxide-free MEMS, cold-weld MEMS, UPW assembly, ultrapure water weld, self-aligning MEMS, self-assembly MEMS, acoustic MEMS assembly, phased-array acoustics, acoustic well, acoustic tweezers, acoustic levitator at microscale, no-touch assembly, contactless micro assembly, micro assembler, general micro assembler, deposition unit, DU, magazine DU, sea-urchin spine form, poka-yoke taper, asperity pad, noble-metal pad, suck-weld, Method E, alignment stack A-B-C-D-E, 5–500 micron parts, 5-500 um, micrometer-scale construction, material-scale construction, space MEMS, microgravity MEMS, orbital fab, in-space manufacturing of MEMS.

Bought 1.0 parts vs built 2.0 parts. Do not treat a purchased PMUT as proof the factory is a silicon line.

</details>

<!-- search-index only; not for human load path
MEMS MEMS2 MEMS-2.0 micro-electro-mechanical microelectromechanical-systems microsystem micromachined-ultrasonic PMUT CMUT BioMEMS MOEMS NEMS lab-on-chip microfluidic-MEMS silicon-fab alternative aqueous-assembly cold-weld-UPW acoustic-micro-assembler animaSpace-DU 5-500-um self-aligning-parts oxide-free-join space-factory-MEMS
-->
