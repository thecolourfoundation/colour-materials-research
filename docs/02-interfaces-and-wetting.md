# Interfaces and wetting

> Part of [Colour Research](../README.md). Educational material. Numbers are approximate textbook or literature values unless sourced. See [research integrity](06-research-integrity.md).

The interface between copper and diamond is where most of the difficulty sits. This note explains why, and summarises published approaches.

## Interfaces, the heart of the problem

**Wetting.** A liquid or solid on a surface either spreads or beads up. The contact angle measures it: below 90 degrees wets, above 90 degrees does not. Copper does not wet diamond (large contact angle), so there is no natural bond.

**Carbide bridge.** Titanium, chromium, tungsten, molybdenum, zirconium and boron react with carbon at the surface to form carbides (TiC, Cr carbides, WC and W2C, B4C). Copper wets those carbides, so the carbide acts as a bridge: diamond to carbide to copper.

**Thickness trade-off.** Too thin leaves bare patches. Too thick and the carbide itself, which conducts worse than diamond, becomes the bottleneck.

**Interface thermal conductance (h, W/m2K):** how much heat crosses per unit area per degree. Its inverse is the **interface thermal resistance** (Kapitza resistance). Two models describe it:
- **Acoustic mismatch:** vibrations partly reflect where the stiffness and density of two materials differ.
- **Diffuse mismatch:** vibrations scatter at a rough or disordered boundary.

Heat in diamond travels as phonons and in copper mostly as electrons, so crossing the boundary needs a coupling step. A well-matched carbide layer can act as a phonon-friendly bridge.

**Graphitization.** Diamond is only stable at very high pressure. At ordinary pressure it can turn to graphite when hot enough, and graphite conducts poorly across the plane. Control temperature, time and atmosphere. Raman spectroscopy detects graphitic carbon.

## The central problem: the interface

Copper does not wet diamond, so the two bond poorly. The weak bond creates thermal resistance at each particle and limits the whole composite [3, 4]. Two main fixes appear in the literature:

1. **Coat the diamond** with carbide-forming elements such as Ti, Cr, W, Mo, Zr or B, using methods like electroless plating, magnetron sputtering, molten salt, vacuum electroplating or embedding [5].
2. **Alloy the copper** with small amounts of a carbide former, using gas atomization or alloy smelting [5].

Both form a thin carbide layer that bonds the two materials. **The trade-off:** too little additive leaves bare patches, and too much builds a thick layer that itself blocks heat [6].

**Data points to calibrate intuition** (different papers, so not directly comparable):

| Example | Result |
|---|---|
| 200 micron diamond, W coating, 1:1 volume with copper, pulse plasma sintering | 690 W/mK, interface conductance 45 MW/m2K [7] |
| Ti-doped copper (0.5 weight percent), processed at 1050 C | 554 W/mK but only 93 MPa tensile strength [8] |
| SiC-converted, copper-coated diamond, 35 to 40 percent diamond, hot isostatic pressing or field-assisted sintering | 550 to 566 W/mK [9] |

**Lesson:** conductivity and strength can pull in opposite directions. Decide with the customer which matters more, then engineer toward it.

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
