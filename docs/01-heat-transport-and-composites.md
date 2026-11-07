# Heat transport and composites

> Part of [Colour Research](../README.md). Educational material. Numbers are approximate textbook or literature values unless sourced. See [research integrity](06-research-integrity.md).

How materials engineers think, why diamond conducts heat so well, and how composites combine materials.

## How materials people think

Materials science runs on one idea, often drawn as a four-point loop:

1. **Structure:** what the material is made of at every scale, from atoms to grains to the finished part.
2. **Processing:** how you make it (mixing, pressing, heating).
3. **Properties:** what it does (conducts heat, expands, breaks).
4. **Performance:** how it behaves in the customer's product.

Processing sets structure, structure sets properties, and properties set performance. When a sample conducts poorly, ask: is it the structure (a bad interface), the processing (too low a temperature), or the measurement?

**Scales:** atoms (angstroms), interfaces (nanometers), diamond particles (tens to hundreds of micrometers), the plate (millimeters), the product (centimeters).

## Why diamond conducts heat so well

Heat moves through solids in two ways:

- **Electrons** carry heat in metals like copper, around 400 W/mK (approximate).
- **Phonons** carry heat in insulators. A phonon is a packet of lattice vibration, like a wave running through the atoms.

Diamond is an electrical insulator but one of the best heat conductors known. Its carbon atoms are light, bonded by very stiff covalent bonds, and arranged in a very regular lattice, so vibrations travel fast and rarely scatter. Impurities, defects and boundaries scatter phonons, so diamond quality (for example nitrogen content) changes how well it conducts.

**Key equations:**
- Fourier's law: heat flow equals conductivity times temperature gradient.
- Thermal resistance of a slab: R = L / (k A), where L is thickness, k is conductivity and A is area. Resistances in series add up, so one bad layer can dominate a stack.
- Diffusivity link: k = alpha x density x specific heat. A laser flash instrument measures alpha (how fast heat spreads), and you supply density and specific heat.

## Composites and the mixing rules

A **composite** combines two materials so the result beats either alone. Here **diamond is the reinforcement** (the filler that conducts) and **copper is the matrix** (the continuous metal that holds it).

- **Parallel bound:** if heat flows through both materials side by side, conductivity is the volume-weighted average. This is the best case.
- **Series bound:** if heat must pass through each in turn, it is far worse. Real composites sit between.

Moving toward the best case needs a high diamond fraction, touching particles that give heat a direct path, and a good interface. Bigger particles usually help because there are fewer boundaries per unit length (General knowledge).

**Effective-medium models** (Maxwell, Bruggeman, Hasselman-Johnson) predict composite conductivity from the parts. Hasselman-Johnson adds the **interface resistance** and contains a useful idea: the **Kapitza length**, roughly interface resistance times matrix conductivity. A particle smaller than that length behaves like an insulator. A bad interface can make small diamond particles useless.
