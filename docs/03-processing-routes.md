# Processing routes

> Part of [Colour Research](../README.md). Educational material. Numbers are approximate textbook or literature values unless sourced. See [research integrity](06-research-integrity.md).

How copper-diamond composites are made, the main densification routes, machining challenges and common failure modes.

## Powder metallurgy and sintering

You do not melt the diamond. You make a powder compact and fuse it.

- **Green body:** pressed powder before heating.
- **Sintering:** heating below the melting point so particles fuse and pores close, driven by a drop in surface energy.
- **Densification:** pores shrinking, measured as relative density (percent of theoretical).
- **Mechanisms:** surface diffusion, grain boundary diffusion, lattice diffusion, and plastic flow (creep) when pressure is applied.
- **Three stages:** neck formation between particles, a connected network of open pores, then isolated closed pores.

**Pressure-assisted sintering** (hot pressing, SPS, HIP, HTHP) adds pressure so you reach full density at lower temperature and shorter times. **SPS (spark plasma sintering)** passes pulsed current through the die and powder, so it heats fast. **Infiltration** instead presses molten copper into a loose diamond bed.

For each variable (temperature, pressure, time) there is a window where density is high and diamond is protected. A good engineer finds and documents that window, then keeps the process inside it.

## Process routes

The literature covers vacuum hot pressing, spark plasma sintering (SPS), high-temperature high-pressure (HTHP) sintering and melt or gas-pressure infiltration [5].

| Route | How it works | Strengths | Watch-outs | Fit for first loop |
|---|---|---|---|---|
| Vacuum hot pressing | Heat and press powder in a vacuum furnace | Simple, proven, small batches | Slower cycles | Good |
| Spark plasma sintering | Pulsed current heats the powder under pressure | Fast cycles, quick iteration | Tool and sample size limits | Best for learning speed |
| HTHP | Extreme pressure and temperature | Reported to help density and avoid graphitization [10] | Specialized equipment | Later |
| Infiltration | Molten copper flows into a diamond preform | Near-net shapes, good for scale | Needs good wetting, tooling | Later |

In SPS, Cr-coated diamond with copper reached close to full density when pressure was raised gradually to 30 MPa during heating, and larger copper particles helped density [11]. Diamond can convert to graphite at high temperature, so control temperature and time (General knowledge, and see [10]).


## Machining and finishing


## Common failures and fixes

| Problem | Likely cause | What to try |
|---|---|---|
| Low conductivity | Weak interface, porosity, graphitized diamond, poor diamond quality | Check microstructure and density, change the coating, lower temperature or time |
| Cracks or debonding on heating and cooling | Expansion mismatch, weak interface [4] | Stronger interface layer, adjust diamond fraction |
| Low density | Pressure or temperature too low, powder too fine | Raise pressure gradually, use a larger copper powder [11] |
| Uneven coating | Process limits of sputtering or plating [14] | Improve coating uniformity, test another method |
| Diamond clumping | Mixing or settling [13] | Better mixing, shorter handling |
| Parts damaged in cutting | Wrong machining method | Use EDM or waterjet, design near-net shapes |

## Sources

1. TechSpot, Element Six copper-diamond composite: https://www.techspot.com/community/topics/e6-unveils-copper-diamond-composite-for-next-gen-thermal-management.290443/
2. Element Six announcement coverage: https://www.epdtonthenet.net/article/213433/Game-Changing-Copper-Diamond-Composite-Material-Unveiled.aspx
3. Research progress on diamond-copper composites (Powder Metallurgy Technology): https://pmt.ustb.edu.cn/en/article/doi/10.19591/j.cnki.cn11-1974/tf.2024110004
4. Schubert et al., Fraunhofer, on weak diamond-copper bonding and debonding: https://estudogeral.uc.pt/bitstream/10316/4191/1/filed869c6720a5c4821987312cc41648482.pdf
5. Xue et al., 2025, Frontiers in Materials review: https://frontiersin.org/journals/materials/articles/10.3389/fmats.2025.1582990/full
6. Review of copper-diamond interface thermal conductance, Journal of Materials Science (2020): https://link.springer.com/article/10.1007/s10853-020-05443-3
7. Abyzov et al., Materials and Design 76 (2015), W-coated diamond in copper: https://peeref.com/works/1029412
8. Titanium-doped copper-diamond composites, University of Waikato: https://researchcommons.waikato.ac.nz/entities/publication/43044e62-b1a6-4e64-a4fe-58097449387f
9. US patent 8,066,937: https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/8066937
10. Review of the HTHP method for diamond-copper composites, Materials Reports: https://www.mater-rep.com/EN/10.11896/cldb.24080072
11. Cr-coated diamond and copper by spark plasma sintering: https://journal.hep.com.cn/ijmmm/EN/10.1007/s12613-016-1285-1
12. Hasselman and Johnson (1987), as cited in [11].
13. NASA, NARloy-Z-D diamond composite fabrication challenges: https://ntrs.nasa.gov/api/citations/20160001827/downloads/20160001827.pdf
14. Chinese patent CN 121972664 A: https://www.goveda.com/patent/CN-121972664-A
