<div align="center">

# Colour Research

### Open notes on thermal composites and high-temperature magnets

*Literature reviews, primers and open questions for engineers, researchers and curious builders.*

![Status](https://img.shields.io/badge/status-pre--experimental-orange) ![Content](https://img.shields.io/badge/content-CC%20BY%204.0-blue) ![Corrections](https://img.shields.io/badge/corrections-welcome-brightgreen)

[Start here](#start-here) &middot; [Primers](docs/) &middot; [Reviews](reviews/) &middot; [Cite](#how-to-cite) &middot; [Contribute](CONTRIBUTING.md)

</div>

---

## Abstract

Two materials problems sit under a lot of modern hardware: **getting heat out** of dense electronics, and **keeping high-performance magnets working when hot** without depending on scarce heavy rare earths. This repository collects what the published literature says about both, explains the underlying science in plain language, and records the questions that are still open.

It covers two programmes:

1. **Copper-diamond thermal composites:** metal-matrix composites for heat spreading and baseplates in power electronics.
2. **High-temperature sintered NdFeB magnets:** recycling magnet scrap with hydrogen, and using less dysprosium and terbium through grain boundary diffusion.

**Status: pre-experimental.** Everything here is literature synthesis and teaching material. Colour has no validated samples and no measured data of its own yet, and nothing in this repository claims otherwise. When we do have data, including negative results, it will be published here with its methods.

## Why this matters

- **Heat limits electronics.** Thermal materials maker Element Six states that over half of electronic device failures are linked to heat, and reports a commercial copper-diamond composite at about 800 W/mK, roughly twice copper. These are manufacturer statements, not independent findings.
- **Magnet supply is fragile.** The International Energy Agency reports that demand for magnet rare earths has doubled since 2015 and may grow by another third by 2030, and that China placed export controls on seven heavy rare earths in April 2025.
- **The hard problems are specific.** In copper-diamond it is the **interface**, because copper does not wet diamond. In magnets it is **using less heavy rare earth** without losing high-temperature coercivity.

## Start here

| If you are... | Read this first |
|---|---|
| New to the field | [Heat transport and composites](docs/01-heat-transport-and-composites.md), then the [glossary](docs/08-glossary.md) |
| A materials scientist | [Interfaces and wetting](docs/02-interfaces-and-wetting.md) and [processing routes](docs/03-processing-routes.md) |
| An engineer evaluating materials | [Measurement and characterisation](docs/04-measurement-and-characterisation.md) and [packaging and qualification](docs/05-packaging-and-qualification.md) |
| Interested in magnets | [NdFeB recycling and heavy rare earth reduction](reviews/literature-review.md) |
| An investor or partner | [White paper](reviews/white-paper.md) and the [roadmap](ROADMAP.md) |
| A reviewer or critic | [Research integrity](docs/06-research-integrity.md), then open an issue |

## The 60-second version

### Copper-diamond thermal composites

- Diamond conducts heat far better than copper but is hard to shape. Copper is easier. A composite tries to get most of both.
- Conductivity and thermal expansion can be tuned by the diamond fraction, which matters because mismatched expansion cracks joints during thermal cycling.
- **The interface limits performance.** A thin carbide layer from elements such as Ti, Cr, W or B can bond the two, but too much of it blocks heat.
- Published results vary widely. Examples reported in the literature include about 690 W/mK for a W-coated diamond composite and 554 W/mK with only 93 MPa tensile strength for a Ti-doped copper matrix, showing the trade-off between conductivity and strength.
- The composite is very hard to machine, which affects cost and what shapes are realistic.

### High-temperature NdFeB magnets

- Heavy rare earths keep magnets from weakening in hot motors, but they are scarce and supply is concentrated.
- **Grain boundary diffusion** puts dysprosium or terbium only where it matters, near the grain surfaces, instead of throughout the magnet.
- **Hydrogen processing of magnet scrap** can turn old magnets into powder for new ones, but the route is patented, and oxygen control is the central practical problem.
- Feedstock consistency, not chemistry, may be the hardest problem for recycled magnets.

## A learning path

| Step | Topic | File |
|---|---|---|
| 1 | How materials people think, heat transport, composites | [docs/01](docs/01-heat-transport-and-composites.md) |
| 2 | The interface problem | [docs/02](docs/02-interfaces-and-wetting.md) |
| 3 | How the composite is made | [docs/03](docs/03-processing-routes.md) |
| 4 | How to measure it properly | [docs/04](docs/04-measurement-and-characterisation.md) |
| 5 | Packaging, standards and qualification | [docs/05](docs/05-packaging-and-qualification.md) |
| 6 | Magnets and rare earths | [reviews/literature-review.md](reviews/literature-review.md) |
| 7 | How we handle evidence | [docs/06](docs/06-research-integrity.md) and [docs/07](docs/07-methodology.md) |
| 8 | Vocabulary, reading, FAQ and a self-test | [docs/08](docs/08-glossary.md), [docs/09](docs/09-reading-list.md), [FAQ](docs/10-faq.md), [quiz](docs/11-check-yourself.md) |

## Repository map

```
colour-materials-research/
├── README.md              You are here
├── docs/                  Primers, glossary, methodology, reading list, FAQ
├── reviews/               Literature review (magnets) and white paper
├── templates/             Customer specification-sheet templates
├── ROADMAP.md             What we plan to publish, and what we will not
├── CONTRIBUTING.md        How to correct or extend the work
├── GOVERNANCE.md          Who decides, and how errors are handled
├── CODE_OF_CONDUCT.md     How we treat each other
├── SECURITY.md            Reporting safety or data issues
├── CHANGELOG.md           Version history
├── CITATION.cff           Machine-readable citation
└── .github/               Issue and pull request templates
```

## How we label evidence

| Label | Meaning |
|---|---|
| **Established** | Standard textbook or widely replicated science |
| **Reported** | A specific result from a named source, which we have not reproduced |
| **Hypothesis** | A reasoned proposal that we intend to test |
| **Unknown** | We could not find evidence either way |

If a statement here carries no label, treat it as Reported and check the source. Details are in [research integrity](docs/06-research-integrity.md).

## Open research questions

1. What interface layer thickness maximises conductivity without hurting strength, and how repeatable is it across batches?
2. How much does diamond particle size and quality change composite conductivity once the interface is controlled?
3. Which process routes give the best balance of density, interface quality and machinability at plate scale?
4. How well do coupon-scale thermal measurements predict behaviour in a real module baseplate?
5. Can grain boundary diffusion work on magnets made partly from recycled powder, and does it behave differently?
6. How consistent is magnet scrap feedstock across sources, and what limits repeatability?
7. Where do patents constrain the routes described here, and what remains open?

## Status and roadmap

We publish in stages and label what is plan and what is result. See [ROADMAP.md](ROADMAP.md).

## About Colour

Colour is an early-stage materials company working on these two programmes. **That is a commercial interest, and we disclose it:** we want these materials to work, which can bias judgement. Our safeguards are in [GOVERNANCE.md](GOVERNANCE.md) and [research integrity](docs/06-research-integrity.md). Please challenge our claims.

## Contribute

Corrections, missing references and technical reviews are welcome, especially from people who have worked on metal-matrix composites, powder metallurgy, thermal measurement, power-module reliability, NdFeB magnets or recycling. Start with [CONTRIBUTING.md](CONTRIBUTING.md) or open an issue using one of the templates.

## How to cite

```bibtex
@misc{colour_research_2026,
  author       = {{Colour}},
  title        = {Colour Research: open notes on thermal composites and high-temperature magnets},
  year         = {2026},
  howpublished = {GitHub repository},
  url          = {https://github.com/thecolourfoundation/colour-materials-research}
}
```

A machine-readable version is in [CITATION.cff](CITATION.cff).

## Sources at a glance

- International Energy Agency, *Rare earth elements*, executive summary: https://www.iea.org/reports/rare-earth-elements/executive-summary
- Xue et al., 2025, interface optimization of diamond-copper composites, *Frontiers in Materials*: https://frontiersin.org/journals/materials/articles/10.3389/fmats.2025.1582990/full
- Review of interface thermal conductance in copper-diamond composites, *Journal of Materials Science* (2020): https://link.springer.com/article/10.1007/s10853-020-05443-3
- Habibzadeh et al., *ACS Omega* 2023, magnet recycling by hydrogenation: https://doi.org/10.1021/acsomega.3c00299

Full source lists are in each document.

## License

Written content is shared under **Creative Commons Attribution 4.0 (CC BY 4.0)**: you may share and adapt it, including commercially, if you give credit. See [LICENSE-CONTENT.md](LICENSE-CONTENT.md).

## Contact

buildwithcolours@gmail.com &middot; https://thecolourfoundation.github.io/colour-website/

---

<sub>Educational and research material. It is not engineering, legal, patent, safety or investment advice. Powder handling, hydrogen, furnaces and plating chemicals are hazardous: do not attempt processes described here without proper training, facilities and supervision.</sub>
