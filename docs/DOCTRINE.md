# AnimaSpace Doctrine

**Status:** living — 2026-09-13  
**Repo of record:** `jbrake1/animaSpace` (old tree is reference only; rewrite as built)  
**Use:** this file is the process core. Hardware notes (alignment stack, suck-weld, loops) sit under it. They do not replace it.

## Honor present nature

Life started in water. Soup. Chemicals, proteins, and minerals mixing in water. That is how life as we know it works today.

Our infrastructure was built mainly on fire: extract, refine, mold dead material.

Horticulture, culture, and husbandry start with living stock. Seeds, starts, breeding stock, live cultures. Optimal conditions, little competition, protected starters. Harvest the excess.

This process merges both.

We grow cells in soup. We grow crystals in soup.  
Controlled sound in our machines assembles crystals into machines.  
Those machines grow cells. Those machines use controlled sound to assemble living cells into living tissue.

No miracle. Humble respect for how the observed universe works.

## Speed and compute

We assemble machines and tissue fast relative to present factory build and present growth.

Speed comes from compute plus placement rate — millions to billions of placements per second — so a human-scale product or tissue can finish in about a minute after the long setup.

Sound is transport and hands. No-touch is possible because of microgravity. It is required because cells and many parts are fragile at 5–500 µm.

Precision joins rely on self-assembly. We cannot touch at the scale we need. Put parts near each other in the right soup. Soup does the join.

## Soups are chamber-specific

Good soup is tailored to the outcome. Not one vat.

| Chamber | Working fluid (intent) |
|---|---|
| Bioreactor | cell-growth soup |
| Crystal growth | crystal soup |
| Tissue build | oxygenated saline + nutrients the cells need |
| DU machine assembly | ultrapure water (UPW), flooded, oxide-free |
| Cell-hold | specified T, salinity, dissolved gas |

Process fluids span a wide P–T envelope. Quality and speed are joint objectives. We keep seeking higher limits.

Two fluid loops stay separate:

- Assembly / tissue soup (or UPW at machine weld)
- Closed electronics coolant (vascular, single-phase)

Only heat crosses at a heat exchanger. Do not share the weld face. Do not put coolant on the join.

## Build file

The build file is the only thing that comes close to a miracle.

It is one living map:

- tissue anatomy
- machine CAD + CAM
- cell growth process
- part-build process
- assembly process of parts into machines
- assembly process of cells into tissue

Physics and soup still do the join. The file is instruction, not magic.

## Time shape

Pre-fabrication and some cell work take days or weeks. That work stabilizes identity.

Final assembly is one fast step after that setup — spawning, egg-laying, the rut. Dramatic and short.

After the event: training, hardening, footing. Not more factory placement. Then purpose.

## Yield

Most pre-assembly cells and parts miss the cut or exist as buffer. Overproduction is wise. Reject-mode is normal, not failure.

Cull the weak. Recycle. Protect starter stock. Improve the ratio over time. Do not starve the final cue.

## Service is the product

Target:

- forty-year warranty on organs
- lifetime warranty on machines classed durable

Training, hardening, and separate coolant vs soup exist so that claim can hold.

## Hardware stack this doctrine already locked

Do not reopen these in the doctrine file. They live in the hardware notes.

- Alignment: A acoustic well → B patterned double layer → C poka-yoke taper/key/vents → D asperity noble-metal pad → E port-timed ΔP suck after C is seated. E is illegal as an aligner.
- Aqueous acoustic toroid stable speed ~2 mm/s. Faster transport is gas-phase droplet corridors under PMUT custody.
- Sequence: reject-mode, push to lip ≤2 mm/s, pose confirm, A quiet, smooth suck, weld+hold, stop, next part. Suck does not strip bound water.
- Build grows from the perfusion inlet lip. Magnetic far-edge hinge first, then underside ring-suck. PMUT off during drain.
- Preload is (P_station − P_gap) × sealed underside area. Watch oil-canning of thin faces.
- Next waypoint WP1: single-node acoustic well for one DU size before drawing tapers.

## GitHub use

Keep doctrine and hardware notes as named files with one job each.

Do not add another `*.docx (2).txt` at repo root.  
Do not treat the July dump as current design.  
Push only rewrite-as-built text.
