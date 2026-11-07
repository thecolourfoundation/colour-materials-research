# Packaging, standards and qualification

> Part of [Colour Research](../README.md). Educational material. Numbers are approximate textbook or literature values unless sourced. See [research integrity](06-research-integrity.md).

Why customers care about heat, how electronic packages are built, how quality and qualification work, and how the industry is organised.

## Why heat matters to the customer

A chip produces heat in tiny hot spots. If the **junction temperature** exceeds its limit, the chip slows, ages faster or fails. The heat path is a series of layers: die, thermal interface material (TIM1), heat spreader or lid, another TIM (TIM2), a cold plate or heat sink, then air or liquid. Each layer adds thermal resistance. A **heat spreader** (where copper-diamond competes) spreads heat sideways before it hits the next layer.

- **Heat flux:** watts per square centimeter, the intensity of heat.
- **CTE mismatch:** if spreader and chip expand differently, thermal cycling creates stress and cracks the joint. Rough values, approximate: silicon about 2.6 ppm/K, SiC about 4, GaN about 5 to 6, copper about 17, diamond about 1. Tuning the copper-diamond mix tunes the composite's CTE between them.
- **Warpage:** bending of the package from mismatch or stress.
- **Die attach:** how the chip is bonded, for example by gold-tin solder.
- **Thermal cycling:** repeated heating and cooling, the main reliability test.

## Quality, standards and qualification

- **SPC (statistical process control):** control charts that show when a process drifts.
- **Cp and Cpk:** numbers that say how well a process fits inside spec limits.
- **Gauge R&R:** tests whether the measurement system itself is repeatable.
- **FMEA:** a structured review of what could fail, how badly, and how likely.
- **ISO 9001:** a general quality management standard. **ISO/IEC 17025:** the standard for calibration and testing labs, so an accredited lab's reports carry weight.
- **Traceability:** every sample linked to its inputs, equipment and operators.
- **Qualification:** the customer's process for approving your material. In electronics it commonly includes thermal cycling and reliability tests (often following JEDEC standards, so check which apply). Automotive adds a heavier process (PPAP and APQP). Qualification time is a major reason new materials are slow to adopt.

## The industry map

- **Raw material suppliers:** copper powder, diamond (synthetic, made at high pressure and temperature, or by chemical vapor deposition).
- **Material and component makers:** thermal solution vendors, heat spreader makers, substrate makers.
- **Semiconductor makers:** fabless designers, foundries, and OSATs (outsourced assembly and test companies).
- **System makers:** servers, power modules, RF and defense electronics.
- **End users:** data centers, aerospace, telecoms.

A new material usually reaches the market through a component maker or an assembler who qualifies it, not straight to the chip designer.
