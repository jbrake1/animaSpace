# AnimaSpace — General Micro Assembler

**A machine that builds the way nature does: shell by shell, using sound instead of hands.**

No grippers. No mechanical contact. No defects from handling.

---

## The Idea

Conventional assembly picks parts up and puts them down. Every touch is a chance to
introduce a defect, and every gripper has a minimum size that sets a floor on what you
can build.

AnimaSpace removes the hand entirely. Densely packed ultrasonic transducer arrays focus
sound into fields of high and low pressure. Those fields do two jobs:

- **Direct actuation** — acoustic radiation pressure pushes an object where you want it.
- **Transport by flow** — acoustic streaming forms stable toroidal currents that carry
  droplets, bubbles, cells, or particles along with them, the way a stream carries a leaf.

Joining happens through the material's own surface forces — adhesion, surface tension,
self-assembly — with adhesives introduced only where the chemistry needs help. The
assembler positions; physics and biochemistry do the bonding.

This is the distinction that matters: **it is not a printer, it is a builder.** It works at
the scale of the materials themselves, letting cells, crystals, and particles find their
natural alignment rather than forcing them into a deposited layer.

## Operating Envelope

| | |
|---|---|
| **Working scale** | Axial translation: unbounded (open path length). 6-DOF pose control per axial station. |
| **Media** | Functions in both gas and liquid; performance is substantially better in liquid |
| **Actuation** | Arrays of piezoelectric micromachined ultrasonic transducers (PMUTs) |
| **Control** | Transducers addressed individually for fine manipulation, or grouped for efficient bulk transport |
| **Environment** | Designed for microgravity; ground operation is possible but gravity disrupts toroid stability |

Because there is no gravitational "down," the build has no privileged direction. Material
can be added on every face at once — a mode of construction unavailable to any
gantry-based or contact assembler.

## Why Microgravity

Gravity is the dominant source of defects in three processes this platform targets:

- **Crystal growth** — buoyancy-driven convection and sedimentation produce dislocations
  and compositional striations that microgravity growth largely eliminates.
- **Living tissue** — without a substrate to settle onto, cells can be held in true 3D
  arrangements and allowed to self-organize rather than being scaffolded into shape.
- **Layered microelectronics** — defect-free 3D structures require placement precision that
  contact tooling cannot reach and settling cannot be allowed to disturb.

## Physics Basis

The core phenomenon — acoustic streaming producing stable toroidal fluid structures — has
established precedent:

- **E. N. da C. Andrade (1933)** — foundational work on acoustic streaming and vortical
  secondary flows.
- **NASA drop tower observations** — toroidal formation under short-duration microgravity.
- **ISS DECLIC experiments** — stable toroidal drop behavior over long-duration microgravity.
- **Modern acoustofluidics** — acoustic tweezers, containerless ultrasonic levitation, and
  vortex-ring dynamics demonstrating toroid-to-vortex transitions.

Under Earth gravity, the same drive produces a vertical streaming vortex rather than a
closed toroid. The predicted contrast between these two regimes is the sharpest available
test of the model.

## Status

**Concept stage. No working machine exists.**

The physics is grounded in published precedent, but the assembler itself is unbuilt and
unvalidated. Everything in this repository should be read as design intent, not
demonstrated capability.

### Path Forward

1. **Scaled-up prototype** — build the array oversized, where fabrication is tractable and
   the flow structures are directly observable.
2. **Miniaturization** — shrink toward the 0.5–1 mm target envelope.
3. **Orbital operation** — run the assembler in sustained microgravity.
4. **AI-driven characterization** — once in orbit, use automated experiment design to
   rapidly map the machine's real behavior across parameter space, and feed those findings
   back into a true general-purpose assembler.

### Prior Experimental Work

Drop testing using a heavy-lift drone (~150 ft release, ~3.5 s of free fall) was planned to
observe toroid formation versus Earth-gravity collapse using a phased array.

> *Update this section with results, or note that it was not completed.*

## Collaborators Wanted

The proof of concept needs three people. If one of these is you, open an issue.

- **Mathematician** — field synthesis, inverse problems, and control of many-element
  phased arrays.
- **Physicist** — acoustofluidics, streaming regimes, and microgravity fluid dynamics.
- **Integrated-circuit engineer** — dense PMUT array design, per-element drive electronics,
  and thermal budget.

## Applications

- Substrate-free 3D tissue and organ construction
- Defect-free crystal and advanced-materials growth
- Three-dimensional microelectronic assembly
- Tissue models for drug testing
- In-space manufacturing of materials that cannot be made on Earth

## Repository Contents

Supporting technical documents drafted for this platform. Several were written as patent
applications and retain that structure.

| File | Subject |
|---|---|
| `Whisper Power patent.docx (1).txt` | Low-power PMUT array architecture for cell positioning below the mechanotransduction threshold |
| `core tech - unproven.pdf` | The acoustic toroidal phenomenon — core physics |
| `Warming and Reanimation Machine.docx.txt` | Hypothermic cell intake, acoustic sorting, viability assessment, triage delivery |
| `bio reactor.docx (2).txt` | Sandwich-stack culture system with integrated PMUT arrays |
| `build, incubate and shipping chamber.docx (1).txt` | Combined build, incubation, and transport environment |
| `deposition unit.docx (1).txt` | Precision multi-cell-type placement |
| `perfusion system.docx (1).txt` | Nutrient delivery, waste removal, pH and temperature regulation |
| `GA_NonProv_Insertions_v1.docx` | Supplementary claims, embodiments, and application formatting |

### Accuracy Warning

⚠️ These documents contain AI-generated content with uncorrected hallucinations. Some
calculations are wrong. They are drafts. Do not treat any number in them as verified.

## License and Intent

Released under the **MIT License**.

This is a deliberate public disclosure. The concept exceeds what one person can execute, so
the material is published openly rather than held. Publication establishes prior art as of
the commit dates and is intended to let others build on the work freely.

## Author

Jimmy Claude Brake Jr. — [@jbrake1](https://github.com/jbrake1)

---

*AnimaSpace — building at the scale of the materials themselves.*
