# Tissue Assembly

## Patient Derived Stem Cells

We create tissue from living cells. We get blood from patients that have had some sort of damage to a tissue or organ, and their bodies are unable to repair the damage. The overview below will help you understand the system.

## Patient Scan and Build file

We scan the failing organ for patient scale and port geometry. A tissue engineer edits that scan when the native shape is the failure (size, mechanics, dead regions). The file is the living map: target anatomy, place order, lineage and regional program per slot, growth recipes, and lot history from the iPSC line through bead, pre-assembly, DU queue, and place (pose, echo, reject). Physics and soup still do the join. The file is instruction, not a row for every cell.

## Blood Sample

We will use the patient’s blood to get PBMCs (Peripheral Blood Mononuclear Cells) and then use the iPSC method (induced Pluripotent Stem Cell) to generate stem cells.

Then ship our patient specific stem cell stock to our zero g factory in orbit.

## Thawing and Triage

Because the cells are shipped frozen we warm them up, give them nutrients, make sure they are viable, then send them to the bioreactor.

## Bioreactor Design and Growing Cells for Assembling Organs

The bioreactors are vascular analogs where factors secreted and perfusate flow mimic natural cell conditions.

Each bioreactor is full of channels with beads held in position by PMUT (piezoelectric micromachined ultrasonic transducer) arrays. The majority of the perfusate flow is induced by our pulsatile pump and individual cell transport is handled by the PMUT arrays that line the vessels and chambers inside the bioreactor.

For moving individual or small groups of cells we focus sound waves into nodes and antinodes spaced appropriately so the toroid formed is the correct size for the cell being moved. The toroids have a quantity of entrained fluid that can be used to move small objects with precision without touching them and without causing shear induced damage. We control the toroids by controlling where the nodes and antinodes form.

## Bioreactor

We move the stem cells to beads where they will differentiate based on the factors introduced into that area of the vessel analog.

Timing of cell maturation is very important. The cells need to be at the correct age to be able to bond to neighbors. Cells mature over different time frames. Maturity of all cells is coordinated for the final assembly event.

The PMUT arrays holding the beads also monitor cell health by reading the echo from the cell. The PMUT arrays place the cells on the beads and help in removal and then moving healthy cells to chambers where complex multicellular arrangements are pre assembled.

## Deposition Unit Loading

Once the cell groups are formed and or individual cells have matured they are moved to the deposition units (DU). Each DU is a wet, PMUT-lined tube from the bioreactor assembly chamber to the build face. The tube is the queue. Placement sequence matches the order and layer those cells will be placed at.

## Build Chamber

The build chamber has a huge number of holes where the DUs are inserted. Each build chamber is built or sized for the organ or tissue it will be assembling. The DUs look like sea urchin spines. When the build chambers are assembled with their DUs it looks similar to a sea urchin.

## Deposition Unit (DU) Movement

The DUs poke into the inner area of the build chamber to within 0.1 millimeters of the tissue surface so that transit from the DU tip to the tissue surface is minimized.

The deposition process happens on the entire outer surface area of the tissue. Because we are in zero g we do not fight gravity, no settling. The DUs move away from the tissue surface in a steady motion depositing constantly as they move away from the tissue surface. The deposition units also have overlap with one another. As DUs back out from the tissue surface other DUs can move in.

## Deposition Unit Placement

The tip of each DU and the build chamber itself has PMUT arrays that place each cell or cell group exactly where it needs to be. The final alignment and attachment (cadherin / integrin expression) is left to the natural disposition of the cells except where we need faster assembly. For quickly creating viable blood vessels we use fibrinogen + thrombin to bind the cells into a watertight vessel surface. Fibrous materials like ligaments and tendons and bone will require other solutions we documented in the original patent applications.

## Assembly Order and Speed

The assembly process starts at the inlets and outlets of the pulsatile pump, lymphatic drainage and nerve stimulation.

We place the cells with proper lineage for that location.

Because cells:

- in zero g moved by sound waves have very little to no drift because of the high viscosity of water and their small mass
- do not settle due to gravity
- during the assembly process we also make sure there is no streaming

The assembly process can move as quickly as we can place the cells which is about 2 mm/s in fluid.

## Perfusion

No pulse during place. As soon as the tissue or organ is formed the pulsatile pump begins pumping perfusate — oxygenated, nutrient rich fluid — at a safe rate the tissue can handle as all its inner bonds firm up. The pulse is important in making sure the tissue forms properly in both the mechanical structure but also so the cells continue to maintain correct lineage, and are fully supported as they bind to one another.

## Failure Modes

### Nerve Cells O2 Needs

Nerve cells with no O₂ die in 4–6 minutes at 37 °C. We lower the temperature to 32 °C. That anoxic window is about 8–10 minutes if the cells had no O₂. We use 100% O₂ at about 2 atm PO₂ rather than a gas mixture of 21% O₂. Because all cells are placed within 200 µm of a lumen filled with this soup we have about an hour from when the cells leave the bioreactors until the pulsatile pump needs to start pumping perfusate. The 8–10 minute number is abort time if a cell is off a lumen.

### Neuron Fragility

Neurons also are extremely fragile which is the primary reason we invented the no-touch whisper technology. Shear caused by tweezers, physical probes, walls, high sound waves, or strong streams is addressed by our PMUT arrays that place and manipulate cells by moving cells with toroids and turning cells with gentle impedance.

### Unstable Cell Identity

Unstable stem cell morphology. We address this problem by putting cells near the neighbors they are meant to be near which causes the cells to keep the identity — epigenetic programming — we gave them in the bioreactor.

### Lymph Drainage in Space

We create the lymphatic system in the organ as in the body but add one-way valves so they function properly in zero g.

### Nerve Stimulation

We map the patient’s healthy nerve activity then replay that once the tissue has been formed and the nerve stimulation will not negatively affect the tissue as it firms up.

### Mitosis in High Radiation Orbital Conditions

We line our orbital factory with a layer of thick plastic beneath a metal skin. Beneath the plastic is a water jacket approximately 2 feet thick. During mitosis cells are highly vulnerable to genetic damage caused by cosmic and solar radiation. Shielding lowers dose. It does not put orbit below sea-level GCR by itself. ECC and short mitosis dwell stay. Warranty of the organ is a service claim, not a shield spec.

### Leaks

We keep leaks from the cell intake, transit tubes, bioreactors, deposition units, and build chambers by flooding the factory with water at the same pressure as the areas growing cells and assembling tissue. This minimizes pressure on seals which minimizes leak potential caused by material fatigue from pressure differential.

### Flipped Bits

Computers, especially CPUs, MPUs, TPUs, data streams and memory can have their analytics or data corrupted by cosmic and solar radiation. Water shielding lowers that risk. ECC, scrub, and watchdog stay. It is not automatically the same as Earth.

### Buoyancy

Buoyancy induced by gravity or centrifugal force causes objects to float or sink in fluids and gases.

Because our factory is zero g, buoyancy is off during place.

Because the placement of cells is extremely important, buoyancy would break the tissue assembly process if it were present.

### Convection Currents

Heat dissipation in gravity or centrifuge causes convection currents. Those currents would move cells from the location we placed them. Because our factory is in zero g, that buoyancy-driven convection is off. Streaming from pumps and PMUTs is held off during place.

## Every Cell is Unique

You cannot build functional tissue if a cell is the wrong lineage, the wrong regional program, or the right cell in the wrong address.

Same genome. Bioreactors set lineage and regional program (palm vs cheek). Address is the build file and the neighbors it is placed next to. After place, those neighbors and mechanical load hold both.

## Transit Speed

If we take too long to move cells between locations they might die in transit. We move the droplets of water with cells in them through air when we need to move them more than a few centimeters. We can move the droplets through air using toroids at about 2 m/s vs 2 mm/s in water.

## Toroids

Toroids collapse on Earth due to gravity and also collapse when the fluid or gas they are in is under centrifugal force.
